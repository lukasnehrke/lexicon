---
title: Mitternachtsformel
type: lexicon:article
description: Mit der Mitternachtsformel (auch abc-Formel) lassen sich die Lösungen einer quadratischen Gleichung ermitteln.
---

# Mitternachtsformel

Mithilfe der Mitternachtsformel (auch abc-Formel genannt) kann man quadratische Gleichungen lösen bzw.
die Nullstellen einer quadratischen Funktion bestimmen.

::: info Mitternachtsformel  
Gegeben ist eine Gleichung der Form <lx-math>ax^2+bx+c=0</lx-math> (allgemeine Form).  
Dann lauten die Lösungen <lx-math>x_1</lx-math> und <lx-math>x_2</lx-math> dieser Gleichung:

<lx-math>
\begin{aligned}
  x_{1} &= \frac{-b + \sqrt{b^2-4ac}}{2a} \\[1.5em]
  x_{2} &= \frac{-b - \sqrt{b^2-4ac}}{2a}
\end{aligned}
</lx-math>

Oder in Kurzschreibweise zusammengefasst:

<lx-math>
\boxed{x_{1/2}=\frac{-b \pm \sqrt{b^2-4ac}}{2a}}
</lx-math>

Wobei <lx-math>\boxed{b^2-4ac}</lx-math> auch als Diskriminante <lx-math>D</lx-math> bezeichnet wird.
:::

## Anwendung Schritt für Schritt
Mit diesen fünf Schritten kann das Bestimmen der Lösungen nicht schiefgehen.

**Beispielaufgabe:**  
Bestimme die Lösungen der Gleichung: <lx-math>20x + 2x^2 + 4 = 4x -20</lx-math>.

### Schritt 1: In allgemeine Form bringen
Zu Beginn sollte man die Gleichung in allgemeine Form <lx-math>ax^2+bx+c=0</lx-math> bringen. Dieser Schritt erhöht die 
Übersichtlichkeit erheblich und verringert damit Fehler.  
Verwende zur Umformung dir bekannte Rechenregeln (z.B. Ausmultiplizieren, Zusammenfassen oder "auf die andere Seite bringen").

**In unserem Beispiel:**

<lx-math>
\begin{aligned}
  20x + 2x^2 + 4   &= 4x -20   & | +20 \\
  20x + 2x^2 + 24  &= 4x       & | -4x \\
  16x + 2x^2 + 24  &= 0        & | \text{ sortieren} \\
  2x^2 +16x +24    &= 0        &
\end{aligned}
</lx-math>

### Schritt 2: Überprüfung
Die Mitternachtsformel kann nur bei **quadratischen** Gleichungen angewendet werden. Wenn es ein <lx-math>x</lx-math> mit höheren
Exponenten als 2 gibt (z.B. <lx-math>x^3</lx-math> oder <lx-math>x^4</lx-math>), lässt sich die Formel _nicht_ anwenden.

Ist die Gleichung [reinquadratisch](-grundlagen) oder hat sie [kein absolutes Glied](-grundlagen), _sollte_ man die
Mitternachtsformel nicht anwenden, weil man die Lösungen schneller durch Umformen bestimmen kann.

### Schritt 3: Koeffizienten ablesen
Für die Formel benötigt man die Koeffizienten <lx-math>a</lx-math>, <lx-math>b</lx-math> und <lx-math>c</lx-math>, die sich aus der Gleichung ablesen lassen.  
Dabei ist
  - <lx-math>a</lx-math> die Konstante vor dem <lx-math>x^2</lx-math>
  - <lx-math>b</lx-math> die Konstante vor dem <lx-math>x</lx-math>
  - <lx-math>c</lx-math> die alleinstehende Konstante (ohne <lx-math>x</lx-math>)

Hier ein paar Beispiele:
| Term                              | <lx-math>a</lx-math>      | <lx-math>b</lx-math>      | <lx-math>c</lx-math>      | Anmerkungen                                                 |
| :-------------------------------- | :-----------------------: | :-----------------------: | :-----------------------: | :---------------------------------------------------------- |
| <lx-math>4x^2+7x+2=0</lx-math>    | <lx-math>4</lx-math>      | <lx-math>7</lx-math>      | <lx-math>2</lx-math>      | Gleichung in allgemeiner Form                               |
| <lx-math>-8x^2+x-5=0</lx-math>    | <lx-math>-8</lx-math>     | <lx-math>1</lx-math>      | <lx-math>-5</lx-math>     | Vorsicht mit negativen Zahlen!                              |
| <lx-math>6x^2+1=0</lx-math>       | <lx-math>6</lx-math>      | <lx-math>0</lx-math>      | <lx-math>1</lx-math>      | Manche Terme können fehlen! (<lx-math>=0</lx-math>)         |
| <lx-math>7x^3+2x^2-8=0</lx-math>  | <lx-math>\times</lx-math> | <lx-math>\times</lx-math> | <lx-math>\times</lx-math> | Keine quadratische Gleichung! (<lx-math>x^3</lx-math>)      |
| <lx-math>x+11=0</lx-math>         | <lx-math>\times</lx-math> | <lx-math>\times</lx-math> | <lx-math>\times</lx-math> | Keine quadratische Gleichung! (kein <lx-math>x^2</lx-math>) |

**In unserem Beispiel:**  
Aus der Gleichung <lx-math>2x^2 +16x +24</lx-math> können wir ablesen: <lx-math>a=2,\; b=16,\; c=24</lx-math>.

### Schritt 4: Diskriminante ausrechnen
Haben wir die Koeffizienten ermittelt, sollten wir danach die Diskriminante <lx-math>D</lx-math> ausrechnen, um zu überprüfen, ob
die Gleichung überhaupt lösbar ist.

::: info Diskriminante einer quadratischen Gleichung  
Die Diskriminante <lx-math>D</lx-math> bestimmt, wie viele Lösungen die Gleichung besitzt.

<lx-math>
D = b^2-4ac
</lx-math>

Dabei gilt:
  - <lx-math>D > 0</lx-math>: Die Gleichung hat zwei Lösungen
  - <lx-math>D = 0</lx-math>: Die hat eine gemeinsame Lösung (<lx-math>x_1</lx-math> und <lx-math>x_2</lx-math> sind identisch)
  - <lx-math>D < 0</lx-math>: Die Gleichung hat keine Lösung
:::

**In unserem Beispiel:**  
Wir rechnen die Diskriminante aus:

<lx-math>
D = \underbrace{16^2}_{b}-4\cdot \underbrace{2}_{a} \cdot \underbrace{24}_{c} = 256 - 192 = 64 > 0
</lx-math>

Da <lx-math>D > 0</lx-math> ist, hat die Beispielgleichung zwei Lösungen.

### Schritt 5: In die Formel einsetzen  
Ist <lx-math>D \geq 0</lx-math>, dann können wir die Koeffizienten in die Formel einsetzen und die Lösungen bestimmen.  
Zur Erinnerung: Eine quadratische Gleichung kann zwei Lösungen haben:

<lx-math>
\begin{aligned}
  x_1 &= \frac{-b + \sqrt{D}}{2a} = \frac{-b + \sqrt{b^2-4ac}}{2a} \\[1.5em]
  x_2 &= \frac{-b - \sqrt{D}}{2a} = \frac{-b - \sqrt{b^2-4ac}}{2a}
\end{aligned}
</lx-math>

**In unserem Beispiel:**  
Wir setzen die Koeffizienten und <lx-math>D</lx-math> in die Mitternachtsformel ein:

<lx-math>
\begin{aligned}
  x_{1/2} &= \frac{-16 \pm \sqrt{64}}{2\cdot2} = \frac{-16 \pm 8}{4} \\[1.5em]
  x_1     &= \frac{-16 + 8}{4} = \frac{-8}{4} = -2 \\[1em]
  x_2     &= \frac{-16 - 8}{4} = \frac{-24}{4} = -6
\end{aligned}
</lx-math>

Fertig! Die Lösungen der Gleichung sind <lx-math>x_1 = -2</lx-math> und <lx-math>x_2 = -6</lx-math>.
