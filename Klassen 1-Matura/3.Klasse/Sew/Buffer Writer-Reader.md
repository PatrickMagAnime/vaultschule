[[3.Sew]]
```java
import java.io.*; // Importiert alle Klassen für Input und Output

public class Main {
    public static void main(String[] args) {
        System.out.println("Dieses Programm erstellt eine Datei"); 
        // Ausgabe zur Info für den Benutzer

        // Der Pfad für die zu erstellende Ausgabedatei
        String outputfilepath = "output.txt"; 

        // Eine Datei wird erstellt und in diese geschrieben
        writeToFile(outputfilepath); 

        // Der Inhalt der Datei wird gelesen und ausgegeben
        readToFile(outputfilepath); 
    }

    
    private static void writeToFile(String inputfilepath) {
        try {
            // BufferedWriter um Text in eine Datei zu schreiben
            // FileWriter erstellt oder überschreibt die Datei am angegebenen Pfad
            BufferedWriter writer = new BufferedWriter(new FileWriter(inputfilepath)); 
            
            // Inhalt wird in die Datei geschrieben
            writer.write("Hallo Welt!"); 
            System.out.println("File successfully written"); // Erfolgsnachricht
            
            // Der Buffer wird geschlossen, damit die Datei richtig gespeichert wird
            writer.close(); 
        } catch (IOException e) { // Fehlerbehandlung, falls Dateioperation fehlschlägt
            System.err.println(e.getMessage()); // Fehlermeldung wird ausgegeben
        }
    }

    
    private static void readToFile(String outputfilepath) {
        try {
            // BufferedReader um Text aus einer Datei zu lesen
            // FileReader öffnet die Datei zum Lesen
            BufferedReader reader = new BufferedReader(new FileReader(outputfilepath)); 
            
            String line; // Variable für jede gelesene Zeile
            
            System.out.println("Reading from file"); 
            // Ausgabe zur Info für den Benutzer
            
            // Schleife liest die Datei Zeile für Zeile
            while ((line = reader.readLine()) != null) { 
                System.out.println(line); // Jede Zeile wird ausgegeben
            }
            
            // Der Buffer wird geschlossen, um Ressourcen freizugeben
            reader.close(); 
        } catch (IOException e) { // Fehlerbehandlung, falls Dateioperation fehlschlägt
            System.err.println(e.getMessage()); // Fehlermeldung wird ausgegeben
        }
    }
}
```

### **Schrittweise Erklärung:**

1. **Programmstart und Datei-Pfad**:  
    Das `main`-Programm definiert `outputfilepath` als Pfad für die Datei. Es ruft dann zwei Methoden auf:
    - `writeToFile`: Um eine Datei zu erstellen und etwas hineinzuschreiben.
    - `readToFile`: Um die Datei zu öffnen und ihren Inhalt zu lesen.
    
1. **`writeToFile`-Methode** 
    - Hier wird ein `BufferedWriter` erstellt. Dieser verwendet einen `FileWriter`, um Text in eine Datei zu schreiben.
    - `writer.write("Hallo Welt!")`: Schreibt den Text in die Datei.
    - `writer.close()`: Schließt den Buffer, um sicherzustellen, dass alle Daten in die Datei geschrieben werden.
    
1. **`readToFile`-Methode**:
    - Hier wird ein `BufferedReader` erstellt. Dieser verwendet einen `FileReader`, um Text aus einer Datei zu lesen.
    - Die Methode liest jede Zeile der Datei in einer Schleife, bis keine Zeilen mehr vorhanden sind (`reader.readLine()` gibt `null` zurück).
    - Jede gelesene Zeile wird auf der Konsole ausgegeben.
    
1. **Fehlerbehandlung**:
    - `IOException` wird in beiden Methoden behandelt. Falls z. B. die Datei nicht geschrieben oder gelesen werden kann, wird eine Fehlermeldung ausgegeben.

---

### **Wie arbeiten `BufferedWriter` und `BufferedReader`?**

- **`BufferedWriter`**:  
    Dieser schreibt Daten in einem Puffer, bevor sie in die Datei geschrieben werden. Das erhöht die Effizienz, da nicht jedes Zeichen einzeln in die Datei geschrieben wird.
    
- **`BufferedReader`**:  
    Dieser liest Daten zeilenweise in einen Puffer. Das Lesen aus der Datei wird dadurch schneller und einfacher, besonders bei großen Dateien.
    

---
