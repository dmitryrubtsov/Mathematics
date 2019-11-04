# Найти частные производные первого и второго порядка.
## Убедиться в равенстве смешанных производных.

1. $U = x^3 + 3xy^2 +z^2 -39x -36y +2z +26$

   $U'_x = 3x^2 + 3y^2 - 39$

   $U'_y = 6xy - 36$

   $U'_z = 2z + 2$

   $U''_{xx} = 6x$

   $U''_{xy} = 6y$

   $U''_{xz} = 0$

   $U''_{yy} = 6x$

   $U''_{yx} = 6y$

   $U''_{yz} = 0$

   $U''_{zz} = 2$

   $U''_{zx} = 0$

   $U''_{zy} = 0$

2. $U = \frac{256}{x} + \frac{x^2}{y} + \frac{y^2}{z} +z^2$

   $U'_x = -\frac{256}{x^2} + \frac{2x}{y}$

   $U'_y = -\frac{x^2}{y^2} + \frac{2y}{z}$

   $U'_z = -\frac{y^2}{z^2} + 2z$

   $U''_{xx} = \frac{512}{x^3} + \frac{2}{y}$

   $U''_{xy} = -\frac{2x}{y^2}$

   $U''_{xz} = 0$

   $U''_{yy} = \frac{2x^2}{y^3} + \frac{2}{z}$

   $U''_{yx} = -\frac{2x}{y^2}$

   $U''_{yz} = -\frac{2y}{z^2}$

   $U''_{zz} = \frac{2y^2}{z^3} + 2$

   $U''_{zx} = 0$

   $U''_{zy} = -\frac{2y}{z^2}$

3. Найти производную функции $U = x^2 + y^2 + z^2$ по направлению вектора $\vec{c}(−9, 8, −12)$ в точку M(8; −12; 9).

$U'_x =2x$

$U'_y = 2y$

$U'_z = 2z$

$\mathrm{grad}\ U = (2x, 2y, 2z)$


$\mathrm{grad}\ U |_{(8, -12, 9)} = (16, -24, 18)$

$|\vec{c}| = \sqrt{(-9)^2 + 8^2 + (-12)^2} = 17$

$\vec{c_0} = \frac{\vec{c}}{|\vec{c}|} = (-\frac{9}{17},\frac{8}{17}, -\frac{12}{17})$

$\mathrm{grad}\ U'_\vec{c}|_{(8, -12, 9)} = 16 \cdot (-\frac{9}{17}) - 24 \cdot \frac{8}{17} + 18 \cdot (-\frac{12}{17}) = -\frac{552}{17}$

4. Найти производную функции $U = e^{x^2 + y^2 +z^2}$ по направлению вектора $\vec{d} = 4, −13, −16$ в точку $L(−16; 4; −13)$.

$U'_x =2x \cdot e^{x^2 + y^2 +z^2}$

$U'_y = 2y \cdot e^{x^2 + y^2 +z^2}$

$U'_z = 2z \cdot e^{x^2 + y^2 +z^2}$

$\mathrm{grad}\ U = (2x \cdot e^{x^2 + y^2 +z^2}, 2y \cdot e^{x^2 + y^2 +z^2}, 2z \cdot e^{x^2 + y^2 +z^2})$

$\mathrm{grad}\ U |_{(-16, 4, -13)} = (-32 \cdot e^{441}, 8 \cdot e^{441}, -26 \cdot e^{441})$

$|\vec{d}| = \sqrt{(4^2) + (-13)^2 + (-16)^2} = 21$

$\vec{d_0} = \frac{\vec{d}}{|\vec{d}|} = (\frac{4}{21},-\frac{13}{21}, -\frac{16}{21})$

$\mathrm{grad}\ U'_\vec{d}|_{(-16, 4, -13)} = e^{441}\cdot (-32 \cdot \frac{4}{21} + 8 \cdot \left(-\frac{13}{21}) + (-26) \cdot (-\frac{16}{21})\right) = \frac{184}{21} \cdot e^{441}$

5. \* Найти производную функции $U = \log_{21}(x^2 + y^2 + z^2)$ в точку $F(−19; 8; −4)$ по самому быстрому направлению.

$U'_x =\frac{2x}{x^2 + y^2 + z^2} \cdot \ln{(21)}$

$U'_y = \frac{2y}{x^2 + y^2 + z^2} \cdot \ln{(21)}$

$U'_z = \frac{2z}{x^2 + y^2 + z^2} \cdot \ln{(21)}$

$\mathrm{grad}\ U = \left(\frac{2x}{x^2 + y^2 + z^2} \cdot \ln{(21)}, \frac{2y}{x^2 + y^2 + z^2} \cdot \ln{(21)},\frac{2z}{x^2 + y^2 + z^2} \cdot \ln{(21)} \right)$

$\mathrm{grad}\ U |_{F(-19, 8, -4)} =  \left(-\frac{38}{441 \cdot \ln{(21)}}, \frac{16}{441 \cdot \ln{(21)}},-\frac{8}{441 \cdot \ln{(21)}} \right)$

$\left|\mathrm{grad}\ U |_{F(-19, 8, -4)}\right| = \sqrt{\left(-\frac{38}{441 \cdot \ln{(21)}}\right)^2 + \left(\frac{16}{441 \cdot \ln{(21)}}\right)^2 + \left(-\frac{8}{441 \cdot \ln{(21)}} \right)^2} = \sqrt{\left( \frac{2 \cdot 21}{441 \cdot \ln{(21)}} \right)^2} = \frac{2}{21 \cdot \ln{(21)}}$

$\mathrm{grad}\ U_0 |_{F(-19, 8, -4)} = \left(-\frac{19}{21}, \frac{8}{21}, -\frac{4}{21}  \right)$

$U'_{\mathrm{grad}\ U} = (\mathrm{grad}\ U_0 \cdot \mathrm{grad}\ U)$

$\left . U'_{\mathrm{grad}\ U} \right |_{F(-19, 8, -4)} = \frac{2 \cdot 19^2}{21^3 \ln{(21)}} + \frac{2 \cdot 8^2}{21^3\ln{(21)}} + \frac{2 \cdot 4^2}{21^3\ln{(21)}} = \frac{2 \cdot 21^2}{21^3 \ln{(21)}} = \frac{2}{21\ln{(21)}}$

## Исследовать на экстремум следующие функции:

6. $U = x^2y + \frac{1}{3}y^3 + 2x^2 + 3y^2 - 1$

$\begin{cases}
    U'_x =2xy + 4x = 0 \\
    U'_y = x^2 + y^2 + 6y = 0
\end{cases}$

$\begin{cases}
    \left[ \begin{array}{lc} x = 0 \\ y = -2 \end{array} \right. \\
    x^2 + y^2 + 6y = 0 
\end{cases}$

$\left[
    \begin{array}{lc}
        \begin{cases}
            x = 0 \\
            y^2 + 6y = 0
        \end{cases} \\
        \begin{cases}
            y = -2 \\
            x^2 = 8
        \end{cases}
\end{array}
\right.$

$\begin{array}{|l}
    (0,0) \\
    (0, -6) \\
    (2 \sqrt{2}, -2) \\
    (-2\sqrt{2}, -2)
\end{array}$

$U'_x = 2xy + 4x$

$U'_y = x^2 + y^2 +6y$

$U''_{xx} = 2y + 4$

$U''_{xy} = U''_{yx} = 2x$

$U''_{yy} = 2y + 6$

$\begin{pmatrix}
    U''_{xx} & U''_{xy} \\
    U''_{yx} & U''_{yy}
\end{pmatrix}$

$\begin{pmatrix}
    2y + 4 & 2x \\
    2x & 2y + 6 
\end{pmatrix}$

$\Delta_1 = 2y + 4$

$\Delta_2 =$
$\begin{vmatrix}
    2y + 4 & 2x \\
    2x & 2y + 6
\end{vmatrix}$
$=4y^2 +20y +24 - 4x^2$

$(0,0)$

$\Delta_1 = 2y + 4 = 4 > 0 \quad \Delta_2 = 4y^2 + 20y + 24 - 4x^2 = 24 > 0$

$(0,-6)$

$\Delta_1 = 2y + 4 = -8 < 0 \quad \Delta_2 = 4y^2 + 20y + 24 - 4x^2 = 48 > 0$

$(\pm 2\sqrt{2}, -2)$

$\Delta_1 = 2y + 4 = 0 \quad \Delta_2 = 4y^2 + 20y + 24 - 4x^2 = -32 < 0$

7. \* $U = e^{\frac{-x}{2}}(x^2 + y^2)$

$\begin{cases}
    U'_x = -\frac{1}{2} e^{ \frac{-x}{2} }(x^2 + y^2) + e^{ \frac{-x}{2} }\cdot 2x = 0 \\
    U'_y = e^{ \frac{-x}{2} } \cdot 2y = 0
\end{cases}$

$\begin{cases}
    -\frac{1}{2} (x^2 + y^2) + 2x = 0 \\
    y = 0
\end{cases}$

$\begin{cases}
    x^2 - 4x = 0 \\
    y = 0
\end{cases}$

$\begin{array}{|l}
    (0,0) \\
    (4,0)
\end{array}$

$U'_x = -\frac{1}{2} e^{ \frac{-x}{2} }(x^2 + y^2) + e^{ \frac{-x}{2} }\cdot 2x$

$U'_y = e^{ \frac{-x}{2} } \cdot 2y$

$U''_{xx} = \frac{1}{4} e^{ \frac{-x}{2} }(x^2 + y^2) - \frac{1}{2} e^{ \frac{-x}{2} } \cdot 2x - \frac{1}{2} e^{ \frac{-x}{2} } \cdot 2x + 2e^{ \frac{-x}{2} }$

$U''_{xy} = U''_{yx} = - \frac{1}{2} e^{ \frac{-x}{2} } \cdot 2y$

$U''_{yy} = 2e^{ \frac{-x}{2} }$

$(0,0)$

$\Delta_1 = 2 > 0$

$\Delta_2 =$
$\begin{vmatrix}
    2 & 0 \\
    0 & 2
\end{vmatrix}$
$= 4 > 0$

$(4,0)$

$\Delta_1 = \frac{1}{4} e^{-2} \cdot 16 - \frac{1}{2} e^{-2} \cdot 8 - \frac{1}{2} e^{-2} \cdot 8 + 2e^{-2} = -\frac{2}{e^2} < 0$

$\Delta_2 =$
$\begin{vmatrix}
    -\frac{2}{e^2} & 0 \\
    0 & -\frac{2}{e^2}
\end{vmatrix}$
$= -\frac{4}{e^4} < 0$
