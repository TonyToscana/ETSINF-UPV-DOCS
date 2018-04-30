## Definición de derivada
$$
\LARGE y' = \lim_{h \to 0} \frac {f(h+x) - f(x)} {h}
$$

## Tabla de derivadas

| Función            | Derivada                                                     |
| :----------------- | :----------------------------------------------------------- |
| $\Large y = k$     | $\Large y' = 0$                                                     |
| $\Large y = x$            | $\Large y' = 1$                                                     |
| $\Large y = f(x)+g(x)$    | $\Large y' = f'(x)+g'(x)$                                           |
| $\Large y = k \cdot f(x)$ | $\Large y' = k \cdot f'(x)$                                         |
| $\Large y = x^n$          | $\Large y' = nx^{n-1}$                                              |
| $\Large y = e^x$          | $\Large y' = e^x$                                                   |
| $\Large y = a^x$          | $\Large y' = a^x \cdot \ln {a}$                                     |
| $\Large y = \ln{x}$       | $\Large y' = \frac 1 x$                                             |
| $\Large y = \log_a{x}$    | $\Large y' = \frac 1 x \cdot \log_a {e} = \frac {1} {x \cdot \ln a}$ |
| $\Large y = sen(x)$       | $\Large y' = cos(x)$                                                |
| $\Large y = cos(x)$       | $\Large y' = -sen(x)$                                               |

## Multiplicación y división

$$
\large Mult\!:\quad
\Large y = f(x) \cdot g(x) \to y' = f'(x) \cdot g(x) + f(x) \cdot g'(x) \\
\quad \\
\large Div\!:\quad
\Large y = \frac {f(x)} {g(x)} \to y' = \frac {f'(x) \cdot g(x) - f(x) \cdot g'(x)} {g(x)^2}
$$

<div style="page-break-after: always;"></div>

## Transformación a/de potencias

| A potencia                                     | De potencia                                     |
| ---------------------------------------------- | ----------------------------------------------- |
| $\LARGE \sqrt[n]{x^k} \to x^{k/n}$             | $\LARGE x^{k/n} \to \sqrt[n]{x^k}$              |
| $\LARGE \frac {1}{x^n} \to x^{-n}$             | $\LARGE x^{-n} \to \frac {1}{x^n}$              |
| $\LARGE \frac {1}{\sqrt[n]{x^k}} \to x^{-k/n}$ | $\LARGE x^{-k/n} \to \frac {1}{\sqrt[n]{x^n}} $ |

## Tabla de derivadas con regla de la cadena

| Función            | Derivada                                                     |
| :----------------- | :----------------------------------------------------------- |
| $\Large y = f(x)^n$       | $\Large y' = n \cdot f(x)^{n-1} \cdot f'(x)$              |
| $\Large y = e^{f(x)}$ | $\Large y' = e^{f(x)} \cdot f'(x)$                       |
| $\Large y = a^{f(x)}$     | $\Large y' = a^{f(x)} \cdot \ln {a}\cdot f'(x)$                    |
| $\Large y = \ln{f(x)}$    | $\Large y' = \frac {1} {f(x)} \cdot f'(x) = \frac {f'(x)} {f(x)}$   |
| $\Large y = \log_a{f(x)}$ | $\Large y' = \frac 1 {f(x)} \cdot \log_a {e} \cdot f'(x) = \frac {f'(x)} {f(x)} \cdot \log_a e$* |
| $\Large y = sen(f(x))$    | $\Large y' = cos(f(x)) \cdot f'(x)$                                 |
| $\Large y = cos(f(x))$    | $\Large y' = -sen(f(x)) \cdot f'(x)$                                |

*al igual que en la primera tabla, el $\log_a e$ lo podemos escribir como $\frac {1} {\ln{a}}$