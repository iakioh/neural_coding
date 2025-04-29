$$
\begin{aligned}
E(x) & = & \sum_{k=0}^\infty k \cdot \frac{\lambda^{k}}{k!} e^{-\lambda} \\\\
& = &  e^{-\lambda} \sum_{k=1}^\infty \frac{\lambda^{k}}{(k - 1)!} \\\\
& = &  e^{-\lambda} \lambda \sum_{j=1}^\infty \frac{\lambda^{j}}{j!} \\\\
& = &  \lambda
\end{aligned}
$$

$$
Var(x) = E(x^2) - E(x)^2
$$
Since $x^2 = x(x-1) + x$ then $$Var(x) = E(x(x-1)) + E(x) - E(x)^2$$

$$
\begin{aligned}
E(x(x-1)) & = & \sum_{k=0}^\infty k(k-1) \cdot \frac{\lambda^{k}}{k!} e^{-\lambda} \\\\
& = &  e^{-\lambda} \sum_{k=2}^\infty \frac{\lambda^{k}}{(k - 2)!} \\\\
& = &  e^{-\lambda} \lambda^2 \sum_{j=1}^\infty \frac{\lambda^{j}}{j!} \\\\
& = &  \lambda^2
\end{aligned}
$$
Therefore
$$
Var(x) = \lambda^2 + \lambda - \lambda^2 = \lambda
$$