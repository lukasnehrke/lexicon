# Quadratische Gleichung

Eine quadratische Gleichung ist eine Gleichung, bei der die Unbekannte quadriert wird.  
Die Gleichung hat die allgemeine Form
$$ax^2+bx+c=0$$
wobei $a \neq 0$ sein muss.

## Bezeichung
Ist die Gleichung in allgemeiner Form $ax^2+bx+c=0$ gegeben, bezeichnet man
  - $ax^2$ als quadratisches Glied
  - $bx$ als lineares Glied
  - und $c$ als absolutes Glied.
  
Eine Gleichung mit $b=0$ heißt auch **reinquadratischen Gleichung**.

### Normalform
Eine quadratische Gleichung ist in Normalform, wenn $a=1$ ist.

Eine Gleichung in allgemeiner Form lässt sich einfach in Normalform umschreiben, indem man
die Gleichung durch den Koeffizienten $a$ teilt.  
$$ax^2+bx+c=0 \Longleftrightarrow \frac{a}{a}x^2+\frac{b}{a}x+\frac{c}{a}=\frac{0}{a}
\Longleftrightarrow x^2+px+q=0$$

## Bestimmen der Lösungen (in R)
Eine quadratische Gleichung kann (in $\R$) keine, eine oder zwei Lösungen haben.
Je nach der vorliegenden Form, sollte man andere Lösungsansätze wählen.

### 1. Reinquadratische Gleichungen
Wenn $b=0$ ist, lassen sich die Lösungen durch einfaches Umformen bestimmen.

**Beispiel 1**: $2x^2-8=0 \Leftrightarrow 2x^2=8 \Leftrightarrow x^2=4$  
Jetzt kann man einfach die Wurzel ziehen, dann ergeben sich die Lösungen
$$x_1 = \sqrt{4} = 2$$ 
$$x_2 = -\sqrt{4} = -2$$
Wichtig: Das Ziehen der Quadratwurzel ergibt zwei Lösungen!

**Beispiel 2**: $x^2+4=0 \Leftrightarrow x^2=-4$  
Hier müsste man die $\sqrt{-4}$ berechenen, die Wurzel aus negativen Zahlen ist aber 
**nicht definiert**!  
Diese Gleichung hat also **keine Lösung**.

### 2. Gleichungen ohne absolutes Glied
Wenn $c=0$ ist, also die Gleichung die Form
$$ax^2+bx=0$$
hat, kann man die Lösung durch Ausklammern von $x$ bestimmen.

**Beispiel**: 
$$
\begin{aligned}
2x^2+4x &= 0 \\
x(2x+4) &= 0
\end{aligned}
$$
Die erste Lösung ist also $x_1=0$. Für die zweite Lösung müssen wir noch $2x+4=0$ ausrechnen.
$$
\begin{aligned}
2x+4    &= 0 \\
2x      &= -4 \\
x       &= -2
\end{aligned}
$$
Die Lösungen sind also $x_1=0$ und $x_2=-2$.

### 3. Allgemeine Gleichungen
Liegt weder Form (1) noch Form (2) vor, dann kann man die Lösungen nicht durch einfaches Umformen
bestimmen.  
Um Gleichungen in allgemeiner Form zu lösen, benötigt man die 
[Mitternachtsformel](-mitternachtsformel). Setzt man die Koeffizienten $a$, $b$ und $c$ in die 
Formel ein, ergeben sich die Lösungen $x_1$ und $x_2$.

$$\boxed{x_{1/2}=\frac{-b \pm \sqrt{b^2-4ac}}{2a}}$$
