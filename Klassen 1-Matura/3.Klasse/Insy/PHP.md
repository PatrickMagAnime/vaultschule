[[3.Insy]]
___
PHP (recursive acronym for PHP: Hypertext Preprocessor) is a widely-used open source general-purpose scripting language that is especially suited for web development.

## Key Aspects:

*   **Scripting Language:** PHP code is interpreted at runtime.
*   **Server-Side:** PHP code is executed on a web server.
*   **General-Purpose:** Primarily for web development, but can be used for command-line scripting.
*   **Open Source:** Free to use and distribute.

## Key Features and Concepts:

*   **Syntax:** Influenced by C, Java, and Perl. Uses curly braces `{}`, semicolons `;`, and keywords like `if`, `else`, `for`, `while`, `function`.
*   **Variables:** Prefixed with a dollar sign `$`. Example: `$name = "John";`
*   **Data Types:**
    *   String: `"Hello"`
    *   Integer: `10`
    *   Float: `3.14`
    *   Boolean: `true`, `false`
    *   Array: `array("apple", "banana", "cherry")`
    *   Object
    *   NULL
*   **Arrays:** Can hold a collection of values of different data types, indexed numerically or associatively.
*   **Functions:** Reusable blocks of code.
*   **Object-Oriented Programming (OOP):** Supports classes, objects, inheritance, polymorphism, and encapsulation.
*   **Databases:** Excellent support for interacting with databases like MySQL, PostgreSQL, SQLite, MariaDB.
*   **Web-Specific Features:** Built-in functions for HTTP requests, sessions, cookies.
*   **Frameworks:** Laravel, Symfony, CodeIgniter, etc., provide structure and reusable components.
*   **Templating Engines:** Twig separates presentation logic (HTML) from application logic (PHP code).
*   **Error Handling:** Mechanisms for handling errors and exceptions.

## How it Works in Web Development:

1.  **User Request:** User enters a URL.
2.  **Server Receives Request:** Web server (Apache, Nginx) receives the request.
3.  **PHP Processing:** Server passes PHP files to the PHP interpreter.
4.  **PHP Code Execution:** PHP interpreter executes the code (database connections, calculations, HTML generation).
5.  **HTML Output:** PHP interpreter generates HTML.
6.  **Server Sends Response:** Web server sends the HTML to the browser.
7.  **Browser Renders HTML:** Browser displays the web page.

## Example:

```php
<?php
  echo "Hello, World!";
?>
```

## Why Use PHP?

*   Widely Used
*   Easy to Learn
*   Cross-Platform
*   Database Support
*   Frameworks
*   Open Source

## Database Access (MariaDB Examples):

PHP offers several ways to connect to and interact with MariaDB (or MySQL):

**1. MySQLi (MySQL Improved Extension):** This is the recommended extension for newer PHP versions.

```php
<?php
$servername = "localhost";
$username = "username";
$password = "password";
$database = "mydatabase";

// Create connection
$conn = new mysqli($servername, $username, $password, $database);

// Check connection
if ($conn->connect_error) {
  die("Connection failed: " . $conn->connect_error);
}
echo "Connected successfully";

// Example query
$sql = "SELECT id, firstname, lastname FROM users";
$result = $conn->query($sql);

if ($result->num_rows > 0) {
  // output data of each row
  while($row = $result->fetch_assoc()) {
    echo "<br> id: ". $row["id"]. " - Name: ". $row["firstname"]. " ". $row["lastname"]. "<br>";
  }
} else {
  echo "0 results";
}

$conn->close();
?>
```

**Explanation:**

*   `mysqli()`: Creates a new connection to the MySQL server.
*   `$conn->connect_error`: Checks for connection errors.
*   `$conn->query()`: Executes an SQL query.
*   `$result->num_rows`:  Gets the number of rows in the result set.
*   `$result->fetch_assoc()`: Fetches a result row as an associative array.
*   `$conn->close()`: Closes the connection.

**2. PDO (PHP Data Objects):**  PDO provides a consistent interface for accessing different databases.  This makes it easier to switch databases later.

```php
<?php
$servername = "localhost";
$username = "username";
$password = "password";
$database = "mydatabase";

try {
  $conn = new PDO("mysql:host=$servername;dbname=$database", $username, $password);
  // set the PDO error mode to exception
  $conn->setAttribute(PDO::ATTR_ERRMODE, PDO::ERRMODE_EXCEPTION);
  echo "Connected successfully";

  // Example query
  $sql = "SELECT id, firstname, lastname FROM users";
  $stmt = $conn->prepare($sql);
  $stmt->execute();

  // set the resulting array to associative
  $result = $stmt->setFetchMode(PDO::FETCH_ASSOC);
  foreach(new TableRows(new RecursiveArrayIterator($stmt->fetchAll())) as $k=>$v) {
    echo $v;
  }


} catch(PDOException $e) {
  echo "Connection failed: " . $e->getMessage();
}
$conn = null;
?>
```

```php name=TableRows.php
<?php
class TableRows extends RecursiveIteratorIterator {
  function __construct(RecursiveIterator $it) {
    parent::__construct($it, self::LEAVES_ONLY);
  }

  function current() {
    return "<td>" . parent::current(). "</td>";
  }

  function beginChildren() {
    echo "<tr>";
  }

  function endChildren() {
    echo "</tr>" . "\n";
  }
}
?>
```

**Explanation:**

*   `new PDO()`: Creates a new PDO instance, specifying the database type (mysql), host, and database name.
*   `$conn->setAttribute()`: Sets PDO attributes, in this case, setting the error mode to exception handling.
*   `$conn->prepare()`: Prepares an SQL statement for execution.  This is good for security (prevents SQL injection).
*   `$stmt->execute()`: Executes the prepared statement.
*   `$stmt->setFetchMode()`: Sets the fetch mode to associative array.
*   `$stmt->fetchAll()`: Fetches all the result rows into an array.
*   `$conn = null;`: Closes the connection.

**Important Considerations:**

*   **Security:**  Always use prepared statements (as shown in the PDO example) to prevent SQL injection vulnerabilities. Never directly embed user input into SQL queries.
*   **Error Handling:** Implement proper error handling to catch connection errors and query errors.
*   **Credentials:**  Never hardcode database credentials directly into your PHP code. Use environment variables or configuration files to store sensitive information.
*   **Database Abstraction:** PDO provides a good level of database abstraction, making it easier to switch between different database systems if needed.

Remember to replace `"username"`, `"password"`, and `"mydatabase"` with your actual MariaDB credentials.
