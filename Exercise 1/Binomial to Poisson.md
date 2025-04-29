Let 
$$
p = \frac{\lambda}{n}
$$
such that
$$
\lim_{n \to \infty} \iff \lim_{p \to 0},
$$
and $np = \lambda$ remains fixed. Then:
$$
\begin{aligned}
\lim_{\substack{n \to\infty \\ p\to 0}} P_{\text{Binomial}}(X = s) 
&= \lim_{\substack{n \to\infty \\ p\to 0}} \binom{n}{s} p^s (1 - p)^{n - s} \\\\
&= \lim_{\substack{n \to\infty \\ p\to 0}} \frac{n!}{s!(n-s)!} \left(\frac{\lambda}{n}\right)^s \left(1 - \frac{\lambda}{n}\right)^{n-s} \\\\
&= \lim_{\substack{n \to\infty \\ p\to 0}} \frac{n(n-1)\dots(n-s+1)}{s!} \left(\frac{\lambda}{n}\right)^s \left(1 - \frac{\lambda}{n}\right)^{n-s} \\\\
&\approx \lim_{\substack{n \to\infty \\ p\to 0}} \frac{n^s}{s!} \left(\frac{\lambda}{n}\right)^s \left(1 - \frac{\lambda}{n}\right)^{n-s} \\\\
&= \lim_{\substack{n \to\infty \\ p\to 0}} \frac{\lambda^s}{s!} \left(1 - \frac{\lambda}{n}\right)^{n-s} \\\\
&= \lim_{\substack{n \to\infty \\ p\to 0}} \frac{\lambda^s}{s!} \left(1 - \frac{\lambda}{n}\right)^n \left(1 - \frac{\lambda}{n}\right)^{-s} \\\\
&= \frac{\lambda^s}{s!} e^{-\lambda}.
\end{aligned}
$$

So the binomial distribution converges to the Poisson distribution with parameter $\lambda$.