---
title: Grundlagen
type: lexicon:article
---

# Quadratische Gleichung

Eine quadratische Gleichung ist eine Gleichung, bei der die Unbekannte quadriert wird. Das Lösen einer quadratischen
Gleichung ist identisch mit dem Bestimmen der Nullstellen einer quadratischen Funktion.

::: info Quadratische Gleichung  
Eine quadratische Gleichung hat die allgemeine Form

<lx-math block>
ax^2+bx+c=0
</lx-math>

wobei <lx-math>a \neq 0</lx-math> sein muss.
:::

Beispiele für quadratische Gleichungen:
  - <lx-math>2x^2-8x+4=0</lx-math>
  - <lx-math>7x^2=9x</lx-math>
  - <lx-math>(x+2)^2=-1 \Leftrightarrow x^2+4x+5=0</lx-math>

## Bezeichungen
Liegt eine Gleichung in allgemeiner Form <lx-math>ax^2+bx+c=0</lx-math> vor, bezeichnet man
  - <lx-math>ax^2</lx-math> als quadratisches Glied
  - <lx-math>bx</lx-math> als lineares Glied
  - und <lx-math>c</lx-math> als absolutes Glied.
  
Eine Gleichung mit <lx-math>b=0</lx-math>, also ohne lineares Glied, heißt auch **reinquadratische Gleichung**.  
Beispiele für reinquadratische Gleichungen:
  - <lx-math>x^2=8</lx-math>
  - <lx-math>6x^2=6</lx-math>

### Normalform
Eine quadratische Gleichung ist in Normalform, wenn <lx-math>a=1</lx-math> ist.

Eine Gleichung in allgemeiner Form lässt sich einfach in Normalform umschreiben, indem man
die Gleichung durch den Koeffizienten <lx-math>a</lx-math> teilt.

<lx-math block>
\begin{aligned}  
  ax^2+bx+c &= 0 \\  
  \frac{a}{a}x^2+\frac{b}{a}x+\frac{c}{a} &= \frac{0}{a} \\  
  x^2+px+q &= 0  
\end{aligned}  
</lx-math>

## Bestimmen der Lösungen (in R)

::: info Anzahl der Lösungen  
Eine quadratische Gleichung kann in <lx-math>\R</lx-math> **keine**, **eine** oder **zwei** Lösungen haben.  
:::

Je nach der vorliegenden Form sollte man andere Lösungsansätze wählen, um möglichst schnell zum Ergebnis zu kommen.

### 1. Reinquadratische Gleichungen
Liegt die Form <lx-math>ax^2+c=0</lx-math> vor (also <lx-math>b=0</lx-math>), lassen sich die Lösungen durch einfaches Umformen bestimmen.

#### Beispiel 1
  
Bestimme die Lösungen von <lx-math>2x^2-8=0</lx-math>.  

Die Gleichung hat kein lineares Glied, sie ist also reinquadratisch. Man muss nun versuchen, mit Äquivalenzumformungen 
das <lx-math>x^2</lx-math> alleine auf eine Seite zu bringen.

<lx-math block>
\begin{aligned}  
  2x^2-8 &= 0    & &| +8 \\  
  2x^2   &= 8    & &| :2 \\  
  x^2    &= 4    &  
\end{aligned}  
</lx-math>

Jetzt kann man die Wurzel ziehen, dann ergeben sich die **zwei** Lösungen:

<lx-math block>
\begin{aligned}  
  x_1 &= \sqrt{4} = 2 \\  
  x_2 &= -\sqrt{4} = -2  
\end{aligned}  
</lx-math>

::: warning Beachte: Wurzel ziehen  
Das Ziehen der Wurzel ergibt zwei Lösungen.
<lx-math>x^2=y \Longrightarrow x = \pm \sqrt{y}</lx-math>
:::

#### Beispiel 2
Bestimme die Lösungen von <lx-math>3x^2+6=0</lx-math>.

Es liegt wieder eine reinquadratische Gleichung vor, da <lx-math>b=0</lx-math> ist. Wir formen also wieder um:

<lx-math block>
\begin{aligned}  
  3x^2+6 &= 0   & &| -6 \\  
  3x^2   &= -6  & &| :3 \\  
  x^2    &= -2  
\end{aligned}  
</lx-math>

Hier müsste man <lx-math>\sqrt{-2}</lx-math> berechnen, die Wurzel aus negativen Zahlen ist aber **nicht definiert**!  
Diese Gleichung hat also **keine Lösung**.

::: danger Beachte: Wurzel ziehen  
Man darf keine Wurzeln aus negativen Zahlen ziehen.
:::

### 2. Gleichungen ohne absolutes Glied
Hat die Gleichung die Form <lx-math>ax^2+bx=0</lx-math>, also wenn <lx-math>c=0</lx-math> ist,
kann man die Lösung durch Ausklammern von <lx-math>x</lx-math> bestimmen.

#### Beispiel
Bestimme die Lösungen von <lx-math>2x^2+4x=0</lx-math>.

<lx-math block>
\begin{aligned}  
  2x^2+4x        &= 0  & | \: x \text{ ausklammern} \\  
  x \cdot (2x+4) &= 0  
\end{aligned}  
</lx-math>

Nach dem Satz vom Nullprodukt ist ein Produkt null, wenn eines seiner Faktoren null ist. Damit ist die erste 
Lösung <lx-math>x_1=0</lx-math> schon gefunden.  
Für die zweite Lösung muss man noch <lx-math>2x+4=0</lx-math> ausrechnen.

<lx-math block>
  \begin{aligned}  
  2x+4    &= 0   & &| -4 \\  
  2x      &= -4  & &| :2 \\  
  x       &= -2  
\end{aligned}  
</lx-math>

Die beiden Lösungen der Gleichung sind also <lx-math>x_1=0</lx-math> und <lx-math>x_2=-2</lx-math>.

### 3. Allgemeine Gleichungen
Liegt weder Form (1) noch Form (2) vor, dann kann man die Lösungen nicht durch einfaches Umformen
bestimmen.  
Um Gleichungen in allgemeiner Form zu lösen, benötigt man die 
[Mitternachtsformel](-mitternachtsformel). Setzt man die Koeffizienten <lx-math>a</lx-math>, <lx-math>b</lx-math> und <lx-math>c</lx-math> in die 
Formel ein, ergeben sich die Lösungen <lx-math>x_1</lx-math> und <lx-math>x_2</lx-math>.

<lx-math block>
\boxed{x_{1/2}=\frac{-b \pm \sqrt{b^2-4ac}}{2a}}
</lx-math>

Die Mitternachtsformel wird auf der nächsten Seite im Detail betrachtet.
