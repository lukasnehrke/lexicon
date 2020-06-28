# Mitternachtsformel

Mithilfe der Mitternachtsformel (auch ABC-Formel genannt) kann man quadratische Gleichungen lösen bzw.
die Nullstellen einer quadratischen Funktion bestimmen.

Gegeben ist eine Gleichung der Form $ax^2+bx+c=0$ (allgemeine Form).  
Dann lauten die Lösungen $x_1$ und $x_2$ dieser Gleichung:
$$x_{1}=\frac{-b + \sqrt{b^2-4ac}}{2a}$$
$$x_{2}=\frac{-b - \sqrt{b^2-4ac}}{2a}$$
Oder in Kurzschreibweise zusammengefasst:
$$\boxed{x_{1/2}=\frac{-b \pm \sqrt{b^2-4ac}}{2a}}$$

Wobei $\boxed{b^2-4ac}$ auch als Diskriminante $D$ bezeichnet wird.

## Anwendung Schritt für Schritt
Mit diesen fünf Schritten klappt das Bestimmen der Lösungen immer:

### Schritt 1: In allgemeine Form bringen
Zu Beginn muss man die Gleichung in allgemeine Form $ax^2+bx+c=0$ bringen.
Verwende dazu dir bekannte Rechenregeln (z.B. Ausmultiplizieren, Zusammenfassen oder "auf die andere Seite bringen").

### Schritt 2: Überprüfung
Die Mitternachtsformel kann nur bei **quadratischen** Gleichungen angewendet werden. Wenn es ein $x$ mit höheren
Exponenten als 2 gibt (z.B. $x^3$ oder $x^4$), lässt sich die Formel _nicht_ anwenden.

### Schritt 3: Koeffizienten ablesen
Für die Formel benötigt man die Koeffizienten $a$, $b$ und $c$, die sich aus der Gleichung ablesen lassen.  
Dabei ist
  - $a$ die Konstante vor dem $x^2$, 
  - $b$ die Konstante vor dem $x$ 
  - $c$ die alleinstehende Konstante (ohne $x$)

Hier ein paar Beispiele:
| Term           | $a$      | $b$      | $c$      | Anmerkungen                                |
| :------------- | :------: | :------: | :------: | :----------------------------------------- |
| $4x^2+7x+2=0$  | $4$      | $7$      | $2$      | Der "Regelfall"                            |
| $-8x^2+x-5=0$  | $-8$     | $1$      | $-5$     | Vorsicht mit negativen Zahlen!             |
| $6x^2+1=0$     | $6$      | $0$      | $1$      | Manche Terme können fehlen! ($=0$)         |
| $7x^3+2x^2-8$  | $\times$ | $\times$ | $\times$ | Keine quadratische Gleichung! ($x^3$)      |
| $x+11$         | $\times$ | $\times$ | $\times$ | Keine quadratische Gleichung! (kein $x^2$) |

### Schritt 4: Diskriminante ausrechnen
Haben wir die Koeffizienten ermittelt, sollten wir danach die Diskriminante $D$ ausrechnen, um zu überprüfen, ob
die Gleichung überhaupt lösbar ist.
$$ D = b^2-4ac $$

Falls $D < 0$ ist, sind wir fertig, denn das bedeutet, dass die Gleichung keine reelle Lösung hat.

### Schritt 5: In die Formel einsetzen  
Ist $D \geq 0$, dann können wir die Koeffizienten in die Formel einsetzen und die Lösungen bestimmen.  
Zur Erinnerung: Eine quadratische Gleichung kann zwei Lösungen haben:
$$ x_1 = \frac{-b + \sqrt{D}}{2a} = \frac{-b + \sqrt{b^2-4ac}}{2a}$$
$$ x_2 = \frac{-b - \sqrt{D}}{2a} = \frac{-b - \sqrt{b^2-4ac}}{2a}$$

**Hinweis:** Ist $D = 0$, dann sind $x_1$ und $x_2$ identisch.

## Komplettes Beispiel

**Aufgabe:**  
Bestimme die Nullstellen der Funktion $f(x)=2(x+4)^2-8$

Um die Nullstellen zu bestimmen, müssen wir die Funktionsgleichung gleich null setzen: 
$$2(x+4)^2-8=0$$

### Schritt 1: In allgemeine Form bringen  
Die Funktion ist in Scheitelpunktform gegeben, für die Mitternachtsformel brauchen wir aber die Normalform. Also 
Multiplizieren wir die Klammer aus:
$$
\begin{aligned}
  2(x+4)^2-8&=0 \\
  2(x^2 +8x +16) - 8 &= 0 \\
  2x^2 +16x +32 - 8 &= 0 \\
  2x^2 +16x +24 &= 0
\end{aligned}
$$

### Schritt 2: Überprüfung  
Der höchste Grad ist 2, es handelt sich also um eine quadratische Gleichung und wir können die Formel anwenden.

### Schritt 3: Koeffizienten ablesen  
Die Koeffizienten lassen sich leicht bestimmen:
  - $a = 2$
  - $b = 16$
  - $c = 24$

### Schritt 4: Diskriminante ausrechnen  
Die Diskriminante ist $b^2-4ac$, also für unser Beispiel:
$$D = \underbrace{16^2}_{b}-4\cdot \underbrace{2}_{a} \cdot \underbrace{24}_{c} = 256 - 192 = 64 > 0$$

Die Diskriminante ist größer als $0$, also gibt es zwei verschiedene Lösungen.

### Schritt 5: In die Formel einsetzen  
Jetzt nur noch die Koeffizienten in die Mitternachtsformel einsetzen:

$$ x_1 = \frac{-2 + \sqrt{64}}{2\cdot2} = \frac{-16 + 8}{4} = \frac{-8}{4} = -2$$
$$ x_2 = \frac{-2 - \sqrt{64}}{2\cdot2} = \frac{-16 - 8}{4} = \frac{-24}{4} = -6$$

Fertig! Die Nullstellen sind $x_1=-2$ und $x_2=-6$.
