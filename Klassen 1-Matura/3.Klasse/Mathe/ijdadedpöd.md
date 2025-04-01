# Aufgabe 6.54

## a) 
$$\frac{5x-1}{x^2-1}=\frac{5x-1}{(x+1)(x-1)}$$  Partialbruchzerlegung:
$$\frac{5x-1}{(x+1)(x-1)}=\frac{A}{x+1}+\frac{B}{x-1}$$  Lösen für A und B:
$$5x-1=A(x-1)+B(x+1)$$  
$$5x-1=Ax-A+Bx+B$$  
$$5x-1=(A+B)x+(-A+B)$$  
$$A+B=5$$  
$$-A+B=-1$$  
$$\Rightarrow A=3,\quad B=2$$  **Ergebniss:**
$$\frac{5x-1}{x^2-1}=\frac{3}{x+1}+\frac{2}{x-1}$$  

## c) 
$$\frac{3x^2+6x+2}{x^3+3x^2+2x}=\frac{3x^2+6x+2}{x(x^2+3x+2)}$$  
$$x^2+3x+2=(x+1)(x+2)$$  Partialbruchzerlegung:
$$\frac{3x^2+6x+2}{x(x+1)(x+2)}=\frac{A}{x}+\frac{B}{x+1}+\frac{C}{x+2}$$  Lösen für A, B und C
$$3x^2+6x+2=A(x+1)(x+2)+B\,x(x+2)+C\,x(x+1)$$  
$$3x^2+6x+2=A(x^2+3x+2)+B(x^2+2x)+C(x^2+x)$$  
$$3x^2+6x+2=(A+B+C)x^2+(3A+2B+C)x+2A$$  
$$A+B+C=3$$  
$$3A+2B+C=6$$  
$$2A=2\quad\Rightarrow\quad A=1$$  
$$\Rightarrow B+C=2,\quad 3+2B+C=6$$  
$$2B+C=3$$  
$$\Rightarrow B=1,\quad C=1$$  Ergebniss:
$$\frac{3x^2+6x+2}{x^3+3x^2+2x}=\frac{1}{x}+\frac{1}{x+1}+\frac{1}{x+2}$$  

# Aufgabe 6.55

## a) 
$$\frac{2x^2-13x+27}{x^3-6x^2+9x}=\frac{2x^2-13x+27}{x(x^2-6x+9)}=\frac{2x^2-13x+27}{x(x-3)^2}$$  
Die rechte Seite:  
$$\frac{3}{x}-\frac{1}{x-3}+\frac{2}{(x-3)^2}$$  
Schreibe dies auf einen gemeinsamen Nenner:  
$$=\frac{3(x-3)^2 - x(x-3)+2x}{x(x-3)^2}$$  
$$=\frac{3(x^2-6x+9)-x^2+3x+2x}{x(x-3)^2}$$  
$$=\frac{3x^2-18x+27 -x^2+5x}{x(x-3)^2}$$  
$$=\frac{2x^2-13x+27}{x(x-3)^2}$$  
Damit ist gezeigt:  
$$\frac{2x^2-13x+27}{x^3-6x^2+9x}=\frac{3}{x}-\frac{1}{x-3}+\frac{2}{(x-3)^2}$$  

## b) 
$$\frac{5x^2-13x+15}{x^3-4x^2+5x}=\frac{5x^2-13x+15}{x(x^2-4x+5)}$$  
Die rechte Seite:  
$$\frac{3}{x}+\frac{2x-1}{x^2-4x+5}$$  
Gemeinsamer Nenner:  
$$=\frac{3(x^2-4x+5)+x(2x-1)}{x(x^2-4x+5)}$$  
$$=\frac{3x^2-12x+15+2x^2-x}{x(x^2-4x+5)}$$  
$$=\frac{5x^2-13x+15}{x(x^2-4x+5)}$$  
Also gilt:  
$$\frac{5x^2-13x+15}{x^3-4x^2+5x}=\frac{3}{x}+\frac{2x-1}{x^2-4x+5}$$  

# Aufgabe 6.56

## a) 
$$\int\frac{x+12}{x^2-x-6}\,dx$$  
Den Nenner faktorisiere:  
$$x^2-x-6=(x-3)(x+2)$$  
Partialbruchzerlegung:  
$$\frac{x+12}{(x-3)(x+2)}=\frac{A}{x-3}+\frac{B}{x+2}$$  
$$x+12=A(x+2)+B(x-3)$$  
$$x+12=(A+B)x+(2A-3B)$$  
$$A+B=1$$  
$$2A-3B=12$$  
Multipliziere die erste Gleichung mit 2:  
$$2A+2B=2$$  
Subtrahiere:  
$$ (2A-3B) - (2A+2B)=12-2$$  
$$-5B=10\quad\Rightarrow\quad B=-2$$  
$$A=1 - B=3$$  
Daher:  
$$\int\frac{x+12}{x^2-x-6}\,dx=\int\left(\frac{3}{x-3}-\frac{2}{x+2}\right)dx$$  
$$=3\ln|x-3|-2\ln|x+2|+C$$  

## b) 
$$\int\frac{7x-2}{2x^2+x-1}\,dx$$  
Faktorisiere den Nenner:  
$$2x^2+x-1=(2x-1)(x+1)$$  
Partialbruchzerlegung:  
$$\frac{7x-2}{(2x-1)(x+1)}=\frac{A}{2x-1}+\frac{B}{x+1}$$  
$$7x-2=A(x+1)+B(2x-1)$$  
$$7x-2=Ax+A+2Bx-B$$  
$$7x-2=(A+2B)x+(A-B)$$  
Vergleiche Koeffizienten:  
$$A+2B=7$$  
$$A-B=-2$$  
Aus der zweiten Gleichung:  
$$A=B-2$$  
Einsetzen:  
$$(B-2)+2B=7$$  
$$3B-2=7$$  
$$3B=9\quad\Rightarrow\quad B=3$$  
$$A=3-2=1$$  
Daher:  
$$\int\frac{7x-2}{2x^2+x-1}\,dx=\int\left(\frac{1}{2x-1}+\frac{3}{x+1}\right)dx$$  
$$=\frac{1}{2}\ln|2x-1|+3\ln|x+1|+C$$  

## c) 
$$\int\frac{3x^2-2x+1}{x^3-x}\,dx$$  
Faktorisiere den Nenner:  
$$x^3-x=x(x^2-1)=x(x-1)(x+1)$$  
Partialbruchzerlegung:  
$$\frac{3x^2-2x+1}{x(x-1)(x+1)}=\frac{A}{x}+\frac{B}{x-1}+\frac{C}{x+1}$$  
$$3x^2-2x+1=A(x-1)(x+1)+B\,x(x+1)+C\,x(x-1)$$  
$$3x^2-2x+1=A(x^2-1)+B(x^2+x)+C(x^2-x)$$  
$$3x^2-2x+1=(A+B+C)x^2+(B-C)x-A$$  
Vergleiche Koeffizienten:  
$$A+B+C=3$$  
$$B-C=-2$$  
$$-A=1\quad\Rightarrow\quad A=-1$$  
Einsetzen:  
$$-1+B+C=3\quad\Rightarrow\quad B+C=4$$  
$$B-C=-2$$  
Addition:  
$$2B=2\quad\Rightarrow\quad B=1$$  
$$C=3$$  
Daher:  
$$\int\frac{3x^2-2x+1}{x^3-x}\,dx=\int\left(-\frac{1}{x}+\frac{1}{x-1}+\frac{3}{x+1}\right)dx$$  
$$=-\ln|x|+\ln|x-1|+3\ln|x+1|+C$$  

# Aufgabe 6.57

## a) 
$$\int\frac{2x^3-4x^2-4}{x^3-2x^2}\,dx$$  
Faktorisiere den Nenner:  
$$x^3-2x^2=x^2(x-2)$$  
In GeoGebra ist das Ergebnis:  
$$2x-\frac{2}{x}+\ln\frac{x}{x-2}+C$$  

## b) 
$$\int\frac{4x^2+6x-9}{4x^3+9x}\,dx$$  
Faktorisiere den Nenner:  
$$4x^3+9x=x(4x^2+9)$$  
In GeoGebra ist das Ergebnis:  
$$\ln(4x^2+9)+\arctan\frac{2x}{3}-\ln|x|+C$$ 