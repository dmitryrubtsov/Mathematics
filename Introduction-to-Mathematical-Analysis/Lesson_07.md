# Производные функций одного переменного.

1. $y = \frac{1}{x} + \frac{2}{x^2} - \frac{5}{x^3} + \sqrt{x} - \sqrt[3]{x} + \frac{3}{\sqrt{x}}$

   $y' = -\frac{1}{x^2} - \frac{4}{x^3} + \frac{15}{x^4} + \frac{1}{2\sqrt{x}} - \frac{1}{3\sqrt[3]{x^2}} - \frac{3}{2\sqrt{x^3}}$

2. $y = x \cdot \sqrt{1 + x^2}$

   $y' = \sqrt{1 + x^2} + x \cdot \left(\frac{1}{\sqrt{1 + x^2}} \cdot 2x\right) = \sqrt{1 + x^2} + \frac{x^2}{\sqrt{1 + x^2}} = \frac{2x^2 + 1}{\sqrt{1+x^2}}$

3. $y = \frac{2x}{1 - x^2}$

   $y' = \frac{2(1-x^2) - 2x(-2x)}{(1 - x^2)^2} = \frac{2x^2 + 2}{(1 - x)^2}$

4. \* $y = \sqrt{x + \sqrt{x + \sqrt{x}}}$

      $y' = \frac{1}{2\sqrt{x + \sqrt{x + \sqrt{x}}}} \cdot \left(1 +\frac{1}{2\sqrt{x+\sqrt{x}}} \cdot \left(1 + \frac{1}{2\sqrt{x}} \right)\right)$

5. $y = (x^2 + 2)^5 \cdot (3x - x^3)^3$

   $y' = {\color{red}{f(x)}} \cdot (\ln{[f(x)]})'$

   $y' = (x^2 + 2)^5 \cdot (3x - x^3)^3 \cdot \left(\frac{5 \cdot 2x}{x^2 + 2} + \frac{3 \cdot (3 - 3x^2)}{3x - x^3} \right)$

6. $y = \sqrt[x]{x}$

   $y' = {\color{red}{f(x)}} \cdot (\ln{[f(x)]})'$

   $y' = \sqrt[x]{x} \cdot (\ln{x^{\frac{1}{x}}})' = \sqrt[x]{x} \cdot \left(\frac{\ln{x}}{x}\right)' = \sqrt[x]{x} \cdot \frac{\frac{1}{x} \cdot x - \ln{x} \cdot 1}{x^2} = \sqrt[x]{x} \cdot \frac{1 - \ln{x}}{x^2}$

   ${\color{blue}{y = \sqrt[x]{x} = x^{\frac{1}{x}} = e^{\frac{\ln{x}}{x}}}}$

7. \* $y = \frac{(2 - x^2)^3 \cdot (x - 1)^2}{(2x^3 - 3x) \cdot e^x}$

   $y' = {\color{red}{f(x)}} \cdot (\ln{[f(x)]})'$

   $y' = \frac{(2 - x^2)^3 \cdot (x - 1)^2}{(2x^3 - 3x) \cdot e^x} \cdot \left(\frac{3(-2x)}{2 - x^2} + \frac{2}{x - 1} - \frac{6x^2 - 3}{2x^3 - 3x} - 1\right)$

8. \* $\begin{cases}
        x =\frac{t^2}{t -1}\\
        y = \frac{t}{t^2 - 1}
        \end{cases}$

      $\begin{cases}
          x'_t = \frac{2t \cdot (t - 1) - t^2 \cdot 1}{(t - 1)^2} \\
          y'_t = \frac{1 \cdot (t^2 - 1) - t \cdot 2t}{(t^2 -1)^2} 
      \end{cases}$

      $y'_x = \frac{y'_t}{x'_t} = \frac{(-t^2 - 1) \cdot (t - 1)^2}{(t^2 - 1)^2 \cdot (t^2 - 2t)}$

9. \* $\arctan{\frac{y}{x}} = \ln{\sqrt{x^2 + y^2}}, \quad {\color{red}{x^2 + y^2 > 0}}$

      $\frac{1}{1 + \left(\frac{y}{x}\right)^2} \cdot \frac{y' \cdot x - y \cdot 1}{x^2} = \frac{1}{2} \cdot \frac{1}{x^2 + y^2} \cdot (2x + 2y \cdot y')$

      $\frac{y' \cdot x - y}{x^2 + y^2} = \frac{2x + y \cdot y'}{x^2 + y^2}$

      $y' \cdot x - y = 2x + y \cdot y'$

      $y' \cdot (x - y) = x + y$

      $y' = \frac{x + y}{x - y}$

10. $y = \ln{(x + \sqrt{x^2 + 1})}$ 

    $y' = \frac{1}{x + \sqrt{x^2 + 1}} \cdot \left(1 + \frac{x}{\sqrt{x^2 + x}}\right) = \frac{1}{x + \sqrt{x^2 + 1}} \cdot  \frac{\sqrt{x^2 + 1} + x}{\sqrt{x^2 + 1}} = \frac{1}{\sqrt{x^2 + 1}}$

11. $y = x \cdot \ln{(x + \sqrt{x^2 + 1})} - \sqrt{x^2 + 1}$

    $y' = \ln{(x + \sqrt{x^2 + 1})} + \frac{x}{\sqrt{x^2 +1}} - \frac{x}{\sqrt{x^2 + 1}} = \ln{(x + \sqrt{x^2 + 1})}$

12. \* $y = \arcsin{(\sin{x})}$

       $y' = \frac{\cos{x}}{\sqrt{1 - \sin^2{x}}} = \frac{\cos{x}}{|\cos{x}|}$

13. \* Найти длину $x$  и ширину $y$ прямоугольника при заданном периметре $P=144см$, при которых данный прямоугольник имеет наибольшую площадь $S$.

$\begin{cases}
  2(x + y) = 144 \\
  S = xy
\end{cases}$

$\begin{cases}
  y = 72 - x\\
  S(x) = 72x - x^2
\end{cases}$

$S' = 72 - 2x$

$72 - 2x = 0$

$x = 36$

$\begin{cases}
  x = 36 \\
  y = 36
\end{cases}$
