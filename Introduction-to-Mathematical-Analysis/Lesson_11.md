# Ряды. Интегралы.
## Вычислить интегралы.
1. $\displaystyle \int\frac{2x+3}{(x-2)(x+5)}\mathrm{d}x = \int\left(\frac{A}{x-2} + \frac{B}{x+5}\right)\mathrm{d}x=$

$\frac{A(x+5) + B(x-2)}{(x-2)(x+5)}=\frac{Ax+5A + Bx-2B}{(x-2)(x+5)}= \frac{x(A+B)+(5A - 2B)}{(x-2)(x+5)}$

$\begin{cases}
    A + B = 2 \\
    5A - 2B = 3
\end{cases}$

$\begin{cases}
    A = 1 \\
    B = 1
\end{cases}$

$\displaystyle \int\left(\frac{1}{x-2}+\frac{1}{x+5}\right)\mathrm{d}x = \ln|x-2| + \ln|x+5| + C$

2. $\displaystyle \int e^{2x}\cos{(3x)}\mathrm{d}x$

$U = e^{2x} \quad \mathrm{d}U = 2e^{2x}\mathrm{d}x$

$\mathrm{d}V = \cos{(3x)}\mathrm{d}x \quad V=\frac{1}{3}\sin{(3x)}$

$\displaystyle \int e^{2x}\cos{(3x)}\mathrm{d}x = \frac{1}{3}e^{2x}\sin{(3x)} - \frac{2}{3}\int e^{2x}\sin{(3x)}\mathrm{d}x$

$U = e^{2x} \quad \mathrm{d}U = 2e^{2x}\mathrm{d}x$

$\mathrm{d}V = \sin{(3x)}\mathrm{d}x \quad V=-\frac{1}{3}\cos{(3x)}$

$\displaystyle \int e^{2x}\cos{(3x)}\mathrm{d}x = \frac{1}{3}e^{2x}\sin{(3x)} + \frac{2}{9}e^{2x}\cos{(3x)}- \frac{4}{9}\int e^{2x}\cos{(3x)}\mathrm{d}x$

$\displaystyle \frac{13}{9}\int e^{2x}\cos{(3x)}\mathrm{d}x = \frac{e^{2x}\sin{(3x)}}{3} + \frac{2e^{2x}\cos{(3x)}}{9}$

$\displaystyle \int e^{2x}\cos{(3x)}\mathrm{d}x = \frac{e^{2x}\left(3\sin{(3x)} + 2\cos{(3x)}\right)}{13} + C$

3. $\displaystyle \int_0^{\ln{2}}xe^{-x}\mathrm{d}x$

$U = x \quad \mathrm{d}U = \mathrm{d}x$

$\mathrm{d}V = e^{-x}\mathrm{d}x \quad V=-e^{-x}$

$\displaystyle \int_0^{\ln{2}}xe^{-x}\mathrm{d}x = \left.(-xe^{-x})\right|_0^{\ln{2}}+ \int_0^{\ln{2}} e^{-x} \mathrm{d}x = -\ln{2} \cdot \frac{1}{2} + 0 \cdot 1 + \left.(-e^{-x})\right|_0^{\ln{2}} = - \frac{\ln{2}}{2} - \frac{1}{2} + 1 = \frac{1 - \ln{2}}{2} \approx 0.153$ 

4. \* Разложить функцию $y = e^x$ в ряд Маклорена, а также в ряд Фурье на отрезке $[-π; π]$ . Построить график функции и разложения.

*Ряд Маклорена*

График https://www.desmos.com/calculator/5qfn7xwdpq 

$f(x) = \displaystyle \sum_{n=0}^{\infty}\frac{f^{(n)}(0)}{n!}$

$e^x = \frac{e^0}{0!}x^0 + \frac{e^0}{1!}x^1 + \frac{e^0}{2!}x^2 + \dots = 1 + \frac{x}{1!} + \frac{x^2}{2!}+\dots = \displaystyle \sum_{n=0}^{\infty}\frac{x^n}{n!}$


<iframe src="https://www.desmos.com/calculator/x9wipqe6sx?embed" width="500px" height="500px" style="border: 1px solid #ccc" frameborder=0></iframe>

*Ряд Фурье*

$f(x) = a_0 + \displaystyle \sum_{n=1}^{\infty}(a_n\cos(nx) + b_n\sin(nx)), \text{на отрезке} [-\pi; \pi]$

$\displaystyle a_0 = \frac{1}{2\pi} \int_{-\pi}^{\pi}f(x)\mathrm{d}x$

$\displaystyle a_n = \frac{1}{\pi} \int_{-\pi}^{\pi}f(x)\cos(nx)\mathrm{d}x$

$\displaystyle b_n = \frac{1}{\pi} \int_{-\pi}^{\pi}f(x)\sin(nx)\mathrm{d}x$

$\displaystyle a_0 = \frac{1}{2\pi} \int_{-\pi}^{\pi}e^x\mathrm{d}x = \left.\frac{1}{2\pi} (e^x)\right|_{-\pi}^{\pi} = \frac{e^{\pi}}{2\pi} - \frac{e^{-\pi}}{2\pi} = \frac{e^{\pi} - e^{-\pi}}{2\pi}$

$\displaystyle a_n = \frac{1}{\pi} \int_{-\pi}^{\pi}e^x\cos(nx)\mathrm{d}x$

$U = e^x \quad \mathrm{d}U = e^x\mathrm{d}x$

$\mathrm{d}V = \cos(nx)\mathrm{d}x \quad V = \frac{1}{n}\sin(nx)$

$\displaystyle \frac{1}{\pi} \int_{-\pi}^{\pi}e^x\cos(nx)\mathrm{d}x = \left. \left( \frac{1}{\pi n} e^x \sin(nx)\right)\right|_{\pi}^{\pi} - \frac{1}{\pi n} \int_{-\pi}^{\pi}e^x\sin(nx)\mathrm{d}x = \left. \left( \frac{1}{\pi n^2} e^x \cos(nx) \right) \right|_{-\pi}^{\pi} - \frac{1}{\pi n^2} \int_{-\pi}^{\pi}e^x\cos(nx)\mathrm{d}x$

$U = e^x \quad \mathrm{d}U = e^x\mathrm{d}x$

$\mathrm{d}V = \sin(nx)\mathrm{d}x \quad V = - \frac{1}{n}\cos(nx)$

$\displaystyle \frac{1}{\pi} \int_{-\pi}^{\pi}e^x\cos(nx)\mathrm{d}x = \frac{(e^{\pi} - e^{-\pi})(-1)^n}{\pi(n^2 + 1)}$

$\displaystyle b_n = \frac{1}{\pi} \int_{-\pi}^{\pi}e^x\sin(nx)\mathrm{d}x$

$U = e^x \quad \mathrm{d}U = e^x\mathrm{d}x$

$\mathrm{d}V = \sin(nx)\mathrm{d}x \quad V = - \frac{1}{n}\cos(nx)$

$\displaystyle \frac{1}{\pi} \int_{-\pi}^{\pi}e^x\sin(nx)\mathrm{d}x = \left. \left( -\frac{1}{\pi n} e^x \cos(nx)\right)\right|_{\pi}^{\pi} + \frac{1}{\pi n} \int_{-\pi}^{\pi}e^x\cos(nx)\mathrm{d}x = \left. \left( -\frac{1}{\pi n} e^x \cos(nx) \right) \right|_{-\pi}^{\pi} + \left. \left( \frac{1}{\pi n^2} e^x \sin(nx) \right) \right|_{-\pi}^{\pi} - \frac{1}{\pi n^2} \int_{-\pi}^{\pi}e^x\sin(nx)\mathrm{d}x$

$U = e^x \quad \mathrm{d}U = e^x\mathrm{d}x$

$\mathrm{d}V = \cos(nx)\mathrm{d}x \quad V = \frac{1}{n}\sin(nx)$

$\displaystyle \frac{1}{\pi} \int_{-\pi}^{\pi}e^x\sin(nx)\mathrm{d}x = \frac{n(e^{- \pi} - e^{\pi})(-1)^n}{\pi(n^2 + 1)}$

$e^x = \frac{e^{\pi} - e^{-\pi}}{2\pi} + \displaystyle \sum_{n=1}^{\infty}\left(\frac{(e^{\pi} - e^{-\pi})(-1)^n}{\pi(n^2 + 1)} \cdot \cos(nx) + \frac{n(e^{- \pi} - e^{\pi})(-1)^n}{\pi(n^2 + 1)} \cdot \sin(nx)\right)$

<iframe src="https://www.desmos.com/calculator/ipnnluduwo?embed" width="500px" height="500px" style="border: 1px solid #ccc" frameborder=0></iframe>
