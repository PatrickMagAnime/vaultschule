[[3.Mathe]]
___
![[mathebuch partielle integration.png]]
BSP:
$$\int x*e^x= x*e^x- \int 1*e^x= xe^x-e^x+C$$
anderes bsp:
$$\int x *\cos(x)=x*\sin(x)-\int 1*\sin(x)= x*\sin(x)+\cos(x)+C$$
1.Stammformel
2.das erste Differenzieren und dass andere integrieren
3.dann als erstes nur mit integrierung aufschreiben und das andere gleich lassen, minus das andere mit differenzierung und integrierung aufschreiben
4.der zweite teil muss nochmals integriert werden
$$\int 7x*\sin(x) dx= 7x*(-\cos(x))-\int 7*(-\cos(x))=-7x\cos(x)+ 7\sin(x)$$
![[Mathe Buch 7.11.png]]
I: 1=16a-4b
II:1=16a+4b
___
a=$\frac{1}{16}$ b=0
$f(x)=\frac{1}{16}*x^{2}$
$${\int_{-4}^{4}}\frac{1}{16}x^2=\frac{8}{3}$$

Wir wollen die Fläche unter der Funktion $y=2xy = \sqrt{2x}$ im Intervall $x∈[0,3]x \in [0,3]$ berechnen:

$A=∫032x dxA = \int_0^3 \sqrt{2x} \, dx$

$2x=(2x)12\sqrt{2x} = (2x)^{\frac{1}{2}}$

Das Integral lautet:

$A=∫03(2x)12 dxA = \int_0^3 (2x)^{\frac{1}{2}} \, dx$

Da $212=22^{\frac{1}{2}} = \sqrt{2}$, können wir das umschreiben als:

$A=2∫03x12 dxA = \sqrt{2} \int_0^3 x^{\frac{1}{2}} \, dx$

Nun wenden wir die Potenzregel für Integrale an:

$∫xn dx=xn+1n+1\int x^n \, dx = \frac{x^{n+1}}{n+1}$

Für $n=12n = \frac{1}{2}$ ergibt sich:

$∫x12 dx=x3232=23x32\int x^{\frac{1}{2}} \, dx = \frac{x^{\frac{3}{2}}}{\frac{3}{2}} = \frac{2}{3} x^{\frac{3}{2}}$

Also erhalten wir:

$A=2⋅23x32∣03A = \sqrt{2} \cdot \frac{2}{3} x^{\frac{3}{2}} \Big|_0^3$

Zuerst für $x=3x = 3$:

$332=(33)=(27)=333^{\frac{3}{2}} = \left( \sqrt{3^3} \right) = \left( \sqrt{27} \right) = 3\sqrt{3}$

Dann für $x=0x = 0$:

$032=00^{\frac{3}{2}} = 0$

Also:
$A=2⋅23(33−0)A = \sqrt{2} \cdot \frac{2}{3} \left( 3\sqrt{3} - 0 \right) =22⋅333= \frac{2\sqrt{2} \cdot 3\sqrt{3}}{3} =663= \frac{6\sqrt{6}}{3} =26= 2\sqrt{6}$
$A=26A = 2\sqrt{6}$
