[[3.Sew]]
___
Rekursion ist eine Programmiertechnik, bei der eine Methode sich selbst aufruft, um ein Problem zu lösen. Diese Technik wird häufig verwendet, um Probleme zu lösen, die in kleinere, ähnliche Teilprobleme zerlegt werden können.

## Grundlagen der Rekursion

Eine rekursive Methode hat zwei Hauptbestandteile:
1. **Basisfall**: Die Bedingung, unter der die Rekursion endet. Dies verhindert eine unendliche Rekursion.
2. **Rekursiver Fall**: Der Teil der Methode, in dem die Methode sich selbst aufruft.

### Beispiel: Fakultät berechnen

Die Fakultät einer Zahl `n` (geschrieben als `n!`) ist das Produkt aller positiven ganzen Zahlen kleiner oder gleich `n`. Der Basisfall für die Fakultät ist `0! = 1`. Für alle anderen Werte von `n` gilt `n! = n * (n-1)!`.

```java
public class Fakultaet {
    public static void main(String[] args) {
        int zahl = 5;
        int ergebnis = berechneFakultaet(zahl);
        System.out.println("Die Fakultät von " + zahl + " ist: " + ergebnis);
    }

    public static int berechneFakultaet(int n) {
        if (n == 0) {
            return 1; // Basisfall
        } else {
            return n * berechneFakultaet(n - 1); // Rekursiver Fall
        }
    }
}
```

## Ein kleines Programm, das Rekursion nutzt

Hier ist ein weiteres Beispiel, das die Summe der ersten `n` natürlichen Zahlen berechnet. Auch hier gibt es einen Basisfall (`n == 1`) und einen rekursiven Fall (`n + sum(n-1)`).

```java
public class Summe {
    public static void main(String[] args) {
        int zahl = 10;
        int ergebnis = berechneSumme(zahl);
        System.out.println("Die Summe der ersten " + zahl + " natürlichen Zahlen ist: " + ergebnis);
    }

    public static int berechneSumme(int n) {
        if (n == 1) {
            return 1; // Basisfall
        } else {
            return n + berechneSumme(n - 1); // Rekursiver Fall
        }
    }
}
```

In diesem Programm wird die Methode `berechneSumme` rekursiv aufgerufen, um die Summe der Zahlen von `1` bis `n` zu berechnen.

Rekursion kann sehr mächtig sein, aber es ist wichtig sicherzustellen, dass ein Basisfall definiert ist, um unendliche Rekursionen zu vermeiden, die zu einem Stack Overflow führen würden.

## Weitere Erklärungen zu Rekursion

### Rekursive Methoden vs. Iterative Methoden

Rekursive Methoden und iterative Methoden (Schleifen) können oft verwendet werden, um dasselbe Problem zu lösen. Der Hauptunterschied besteht darin, wie sie arbeiten:

- **Rekursive Methoden**: Verwenden sich selbst, um das Problem zu lösen. Sie sind oft einfacher und eleganter zu schreiben, aber sie können mehr Speicherplatz verwenden, da jeder Aufruf der Methode auf den Stapelspeicher (Stack) gelegt wird.
- **Iterative Methoden**: Verwenden Schleifen (wie `for` oder `while`), um das Problem zu lösen. Sie sind oft effizienter in Bezug auf Speicherplatz, aber der Code kann komplizierter sein.

### Beispiel: Fibonacci-Zahlen

Die Fibonacci-Zahlen sind eine Sequenz, bei der jede Zahl die Summe der beiden vorhergehenden Zahlen ist. Die Sequenz beginnt mit 0 und 1. Der Basisfall ist `fib(0) = 0` und `fib(1) = 1`. Der rekursive Fall ist `fib(n) = fib(n-1) + fib(n-2)`.

#### Rekursive Methode

```java
public class Fibonacci {
    public static void main(String[] args) {
        int zahl = 10;
        int ergebnis = berechneFibonacci(zahl);
        System.out.println("Die " + zahl + ". Fibonacci-Zahl ist: " + ergebnis);
    }

    public static int berechneFibonacci(int n) {
        if (n == 0) {
            return 0; // Basisfall
        } else if (n == 1) {
            return 1; // Basisfall
        } else {
            return berechneFibonacci(n - 1) + berechneFibonacci(n - 2); // Rekursiver Fall
        }
    }
}
```

#### Iterative Methode

```java
public class FibonacciIterativ {
    public static void main(String[] args) {
        int zahl = 10;
        int ergebnis = berechneFibonacciIterativ(zahl);
        System.out.println("Die " + zahl + ". Fibonacci-Zahl ist: " + ergebnis);
    }

    public static int berechneFibonacciIterativ(int n) {
        if (n == 0) {
            return 0; // Basisfall
        } else if (n == 1) {
            return 1; // Basisfall
        } else {
            int a = 0, b = 1, c;
            for (int i = 2; i <= n; i++) {
                c = a + b;
                a = b;
                b = c;
            }
            return b;
        }
    }
}
```

## Vorteile und Nachteile der Rekursion

### Vorteile

- **Einfacher und eleganter Code**: Rekursive Lösungen sind oft kürzer und leichter zu verstehen.
- **Direkte Problemlösung**: Rekursion ist besonders nützlich für Probleme, die sich natürlich in kleinere Unterprobleme zerlegen lassen (z.B. Baumstrukturen).

### Nachteile

- **Leistungsverlust**: Jeder rekursive Aufruf benötigt zusätzlichen Speicherplatz auf dem Stapelspeicher (Stack), was zu einem Stack Overflow führen kann, wenn die Rekursion zu tief wird.
- **Schwieriger zu debuggen**: Rekursive Aufrufe können es schwieriger machen, den Programmablauf zu verfolgen und Fehler zu finden.

## Fazit

Rekursion ist ein mächtiges Werkzeug in der Programmierung, das es ermöglicht, komplexe Probleme auf elegante und intuitive Weise zu lösen. Es ist jedoch wichtig, die Vor- und Nachteile zu kennen und die geeignete Methode (rekursiv oder iterativ) je nach Problemstellung und Ressourcenanforderungen zu wählen.