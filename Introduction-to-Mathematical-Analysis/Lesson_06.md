# Lesson 06.
## Понятие о производной

1. Найти производную выражения:

a. $$\sin{x} \cdot \cos{x} = (\sin{x})'\cdot \cos{x} + \sin{x} \cdot (\cos{x})' = \cos^2{x} - \sin^2{x}$$

b. $$\ln{(2x + 1)^3} = \frac{1}{(2x + 1)^3}\cdot 3(2x + 1)^2 \cdot 2 = \frac{6}{2x +1}$$

c. $$\sqrt{\sin^2{(\ln(x^3))}}= \cos{|\ln{(x^3)|}} \cdot \frac{1}{x^3} \cdot 3x^2 = \frac{3 \cos{|\ln{(x^3)|}}}{x}$$

d. $$\frac{x^4}{\ln{(x)}} = \frac{4x^3\cdot \ln{(x)} - x^4 \frac{1}{x} }{\ln^2{(x)}} = \frac{x^3\ln{(x^4)} - x^3}{\ln^2{(x)}} = \frac{x^3(\ln{(x^4)} - 1)}{\ln^2{(x)}}$$

2. Найти выражение производной функции и ее значение в точке

$$f(x) = \cos{(x^2 + 3x)}, x_0 = \sqrt{\pi}$$

$$f'(x) = -\sin{(x^2 + 3x)} \cdot (2x +3) = -(2x +3)\sin{(x^2 + 3x)}$$

$$f'(\sqrt{\pi}) = -(2\cdot\sqrt{\pi} +3)\sin{((\sqrt{\pi})^2 + 3\cdot \sqrt{\pi})} = -(2\sqrt{\pi} +3)\cdot(\sin{\pi}\cos{3\sqrt{\pi}} + \cos{\pi}\sin{3\sqrt{\pi}}) = $$

$$(2\sqrt{\pi} +3)\sin{3\sqrt{\pi}} \approx −5,38330241$$

3.\* Найти значение производной функции в точке:

$$f(x)= \frac{x^3 - x^2 - x - 1}{1 + 2x + 3x^2 - 4x^3}, x_0 = 0$$

$$f'(x)= \frac{(3x^2 - 2x - 1)(1 + 2x + 3x^2 - 4x^3)-(x^3 - x^2 - x - 1)(2 + 6x - 12x^2)}{(1 + 2x + 3x^2 - 4x^3)^2} = $$

$$f'(x) = -\frac{x^4 + 4x^3 +8x^2 -4x - 1}{(1 + 2x + 3x^2 - 4x^3)^2}$$

$$f'(0) = -\frac{- 1}{(1)^2} = 1$$

4. Найти угол наклона касательной к графику функции в точке:

$$f(x) = \sqrt{3x} \cdot \ln{x}, x_0 = 1$$

$$f'(x) = \sqrt{3}(\sqrt{x} \cdot \ln{x}) = \sqrt{3}\left(\frac{1}{2\sqrt{x}} \ln{x} + \sqrt{x} \frac{1}{x}\right) = \sqrt{3}\left(\frac{\ln{x}}{2\sqrt{x}}+ \frac{1}{\sqrt{x}}\right) = \sqrt{3}\left(\frac{\ln{(x)} + 2}{2\sqrt{x}}\right)$$

$$f'(1) = \sqrt{3}\left(\frac{\ln{(1)} + 2}{2\sqrt{1}}\right) =\sqrt{3}$$

$$\tan{\sqrt{3}} = \frac{\pi}{3} = 60^\circ$$
