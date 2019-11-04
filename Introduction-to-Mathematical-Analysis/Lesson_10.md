# Lesson 10
## “Ряды”

1. Исследовать ряд на сходимость, используя признак д’Аламбера:  
$\displaystyle \sum_{n=1}^{\infty} \frac{n^n}{(n!)^2}$  
$\displaystyle \lim_{n \to \infty} \frac{a_{n + 1}}{a_n} = \displaystyle \lim_{n \to \infty} \frac{(n + 1)^{n + 1}}{((n + 1)!)^2} : \frac{n^n}{(n!)^2} = \displaystyle \lim_{n \to \infty} \frac{(n +1)^{n + 1}}{(n + 1)^2 \cdot n^n} = \displaystyle \lim_{n \to \infty} \frac{\left (\frac{n +1}{n}\right)^n}{n + 1} = \displaystyle \lim_{n \to \infty} \frac{e}{n + 1} = 0 < 1$

2. Исследовать ряд на сходимость, используя радикальный признак Коши:  
$\displaystyle \sum_{n=1}^{\infty} \frac{n}{2^n}$  
$\displaystyle \lim_{n \to \infty} \sqrt[n]{a_n} = \displaystyle \lim_{n \to \infty} \sqrt[n]{\frac{n}{2^n}} =\displaystyle \lim_{n \to \infty} \frac{\sqrt[n]{n}}{2} = \frac{1}{2} < 1$  
$\displaystyle \lim_{n \to \infty} \frac{a_{n + 1}}{a_n} = \displaystyle \lim_{n \to \infty} \frac{n + 1}{2^{n + 1}} : \frac{n}{2^n} = \displaystyle \lim_{n \to \infty} \frac{n + 1}{2n} = \frac{1}{2} <1$  

3. Исследовать ряд на сходимость, используя признак Лейбница:  
$\displaystyle \sum_{n=1}^{\infty} \frac{(-1)^n}{n + \ln{n}}$  

$\begin{cases}
    \displaystyle \lim_{n \to \infty} |a_n| = 0 \\
    |a_{n + 1}| < |a_n| \\
    \displaystyle \sum_{n=1}^{\infty} \frac{1}{n + \ln{n}} \sim 0 \left( \frac{1}{n^1} \right) 
\end{cases}$

$\displaystyle \sum_{n=1}^{\infty} \frac{(-1)^n}{n + \ln{n}} \text{− сходится условно}$  

4. Исследовать ряд на сходимость, используя признак Раабе:  
$\displaystyle \sum_{n=1}^{\infty} \frac{3^n}{2^n}$  
$\displaystyle \lim_{n \to \infty} n \left( \frac{a_n}{a_{n + 1}} - 1 \right) = \displaystyle \lim_{n \to \infty} n \left( \frac{3^n}{2^n} : \frac{3^{n + 1}}{2^{n + 1}} - 1 \right) = \displaystyle \lim_{n \to \infty} n \left( - \frac{1}{3} \right) = -\infty < 1$   
$\displaystyle \lim_{n \to \infty} \frac{a_{n + 1}}{a_n} = \displaystyle \lim_{n \to \infty} \frac{3^{n + 1}}{2^{n + 1}} : \frac{3^n}{2^n} = \frac{3}{2} > 1$

5. Разложить функцию по Тейлору в единице:  
$f(x) = \ln{(16x^2)}$  
$\ln{(16x^2)} = \frac{\ln{16}}{0!}(x - 1)^0 + \frac{2}{1!}(x - 2)^1 - \frac{2}{2!}(x - 1)^2 + \frac{2 \cdot 2}{3!}(x - 1)^3 - \frac{2 \cdot 3!}{4!}(x - 1)^4 +\cdots = \ln{16} + 2 \displaystyle \sum_{n=1}^{\infty} (-1)^{n - 1} \frac{(x - 1)^n}{n}$  

$(\ln{(16x^2)})' = \frac{2}{x}$  
$(\ln{(16x^2)})'' = - \frac{2}{x^2}$  
$(\ln{(16x^2)})''' = \frac{2 \cdot 2}{x^3}$  
$(\ln{(16x^2)})^{IV} = - \frac{2 \cdot 2 \cdot 3}{x^4}$ 

6. \* Дана функция: $f(x) = x^2$  

a. Разложить функцию в ряд Фурье по косинусам на отрезке $x \in [-\pi; \pi]$  
b. Построить график функции и ее разложения.

a. $a_0 = \frac{1}{2\pi} \int\limits_{-\pi}^{\pi} f(x) {\mathrm dx} = \frac{1}{2\pi}\int\limits_{-\pi}^{\pi} x^2{\mathrm dx} = \frac{1}{2\pi} \left. \left( \frac{x^3}{3} \right)  \right|_{-\pi}^{\pi} = \frac{\pi^3}{6\pi} - \frac{(-\pi)^3}{6\pi} = \frac{2\pi^3}{6\pi} = \frac{\pi^2}{3}$  
$a_n = \frac{1}{\pi} \int\limits_{-\pi}^{\pi} f(x) \cos{(nx)}{\mathrm dx} = \frac{1}{\pi} \int\limits_{-\pi}^{\pi} x^2 \cos{(nx)} {\mathrm dx} = \left. \left( \frac{1}{\pi n} x^2 \sin{(nx)} \right)  \right|_{-\pi}^{\pi} - \left. \frac{2}{\pi n} \right|_{-\pi}^{\pi} x \sin{(nx)}{\mathrm dx} =$  

$\begin{array}{l}
    {\color{red}{U = x^2}} & {\color{red} {\implies {\mathrm dU} = 2x {\mathrm dx}}} \\  
    {\color{red}{{\mathrm dV} = \cos{(nx)}{\mathrm dx}}} & {\color{red} {\implies V = \frac{1}{n} \sin{(nx)}}}
\end{array}$  

$= - \frac{2}{\pi n} \int\limits_{-\pi}^{\pi} x \sin{(nx)}{\mathrm dx} = \left. \left( \frac{2}{\pi n^2} x \cos{(nx)} \right)  \right|_{-\pi}^{\pi} -\frac{2}{\pi n^2} \int\limits_{-\pi}^{\pi} \cos{(nx)}{\mathrm dx} =$

$\begin{array}{l}
    {\color{red}{U = x}} & {\color{red} {\implies {\mathrm dU} = {\mathrm dx}}} \\  
    {\color{red}{{\mathrm dV} = \sin{(nx)}{\mathrm dx}}} & {\color{red} {\implies V = - \frac{1}{n} \cos{(nx)}}}
\end{array}$  

$= \frac{2}{\pi n^2} \pi \cos{(\pi n)} - \frac{2}{\pi n^2} (- \pi) \cos{(\pi n)} = 4 \frac{(-1)^n}{n^2}$

$b_n = \frac{1}{\pi} \int\limits_{-\pi}^{\pi} f(x) \sin{(nx)}{\mathrm dx} = \frac{1}{\pi} \int\limits_{-\pi}^{\pi} x^2 \sin{(nx)}{\mathrm dx} = \left. \left( -\frac{1}{\pi n} x^2 \cos{(nx)} \right)  \right|_{-\pi}^{\pi} + \frac{2}{\pi n} \int\limits_{-\pi}^{\pi} x \cos{(nx)}{\mathrm dx} =$ 

$\begin{array}{l}
    {\color{red}{U = x^2}} & {\color{red} {\implies {\mathrm dU} = 2x{\mathrm dx}}} \\  
    {\color{red}{{\mathrm dV} = \sin{(nx)}{\mathrm dx}}} & {\color{red} {\implies V = - \frac{1}{n} \cos{(nx)}}}
\end{array}$  

$=\frac{2}{\pi n} \int\limits_{-\pi}^{\pi} x \cos{(nx)}{\mathrm dx} = \left. \left( \frac{2}{\pi n^2} x \sin{(nx)} \right)  \right|_{-\pi}^{\pi} - \frac{2}{\pi n^2} \int\limits_{-\pi}^{\pi} \sin{(nx)}{\mathrm dx} =$

$\begin{array}{l}
    {\color{red}{U = x}} & {\color{red} {\implies {\mathrm dU} = {\mathrm dx}}} \\  
    {\color{red}{{\mathrm dV} = \cos{(nx)}{\mathrm dx}}} & {\color{red} {\implies V =  \frac{1}{n} \sin{(nx)}}}
\end{array}$  

$= \left. \left( \frac{2}{\pi n^3} \cos{(nx)} \right)  \right|_{-\pi}^{\pi} = \frac{2}{\pi n^3} \cos{(n \pi)} - \frac{2}{\pi n^3} \cos{(n \pi)} = 0$

$x^2 = \frac{\pi^2}{3} \displaystyle \sum_{n=1}^{\infty} \left(  4 \frac{(-1)^n}{n^2} \cdot \cos{(nx) + 0 \cdot \sin{(nx)}}\right)$

b. 
<iframe src="https://www.desmos.com/calculator/fecqloafpm?embed" width="500px" height="500px" style="border: 1px solid #ccc" frameborder=0></iframe>
