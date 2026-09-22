---
title: Riemann zeta function
---

<figure style={{"maxWidth": "250px"}}>

![The Riemann zeta function ζ(z) plotted with domain coloring](https://pub-275e30003c354ac0862cc9839e0f952a.r2.dev/docs/math/Cplot_zeta.svg.png)

<figcaption>

The Riemann zeta function $ζ(z)$ plotted with [domain coloring](https://en.wikipedia.org/wiki/domain_coloring)[^1]

</figcaption>

</figure>

<figure style={{"maxWidth": "200px"}}>

![The pole at z = 1 and two zeros on the critical line](https://pub-275e30003c354ac0862cc9839e0f952a.r2.dev/docs/math/Riemann-Zeta-Detail.png)

<figcaption>

The pole at $z = 1$ and two zeros on the critical line

</figcaption>

</figure>
The **Riemann zeta function** or **Euler–Riemann zeta function**, denoted by the lowercase [Greek letter](https://en.wikipedia.org/wiki/Greek_alphabet) $ζ$ ([zeta](https://en.wikipedia.org/wiki/zeta)), is a [mathematical function](https://en.wikipedia.org/wiki/function_%28mathematics%29) of a [complex variable](https://en.wikipedia.org/wiki/complex_variable) defined as

$$
\zeta(s) = \sum_{n=1}^\infty \frac{1}{n^s} = \frac{1}{1^s} + \frac{1}{2^s} + \frac{1}{3^s} + \cdots
$$

 for $\mathrm{Re}(s) > 1$, and its [analytic continuation](https://en.wikipedia.org/wiki/analytic_continuation) elsewhere.[^2]

The Riemann zeta function plays a pivotal role in [analytic number theory](https://en.wikipedia.org/wiki/analytic_number_theory) and has applications in [physics](https://en.wikipedia.org/wiki/physics), [probability theory](https://en.wikipedia.org/wiki/probability_theory), and applied [statistics](https://en.wikipedia.org/wiki/statistics).

[Leonhard Euler](https://en.wikipedia.org/wiki/Leonhard_Euler) first introduced and studied the function over the [reals](https://en.wikipedia.org/wiki/real_numbers) in the first half of the eighteenth century. [Bernhard Riemann](https://en.wikipedia.org/wiki/Bernhard_Riemann)'s 1859 article "[On the Number of Primes Less Than a Given Magnitude](https://en.wikipedia.org/wiki/On_the_Number_of_Primes_Less_Than_a_Given_Magnitude)" extended the Euler definition to a [complex](https://en.wikipedia.org/wiki/complex_number) variable, proved its [meromorphic](https://en.wikipedia.org/wiki/meromorphic) continuation and [functional equation](https://en.wikipedia.org/wiki/functional_equation), and established a relation between its [zeros](https://en.wikipedia.org/wiki/Root_of_a_function) and [the distribution of prime numbers](https://en.wikipedia.org/wiki/prime_number_theorem). This paper also contained the [Riemann hypothesis](https://en.wikipedia.org/wiki/Riemann_hypothesis), a [conjecture](https://en.wikipedia.org/wiki/conjecture) about the distribution of complex zeros of the Riemann zeta function that many mathematicians consider the most important unsolved problem in [pure mathematics](https://en.wikipedia.org/wiki/pure_mathematics).[^3]

The values of the Riemann zeta function at even positive integers were computed by Euler. The first of them, $ζ(2)$, provides a solution to the [Basel problem](https://en.wikipedia.org/wiki/Basel_problem). In 1979, [Roger Apéry](https://en.wikipedia.org/wiki/Roger_Ap%C3%A9ry) proved the irrationality of [ $ζ(3)$](https://en.wikipedia.org/wiki/Ap%C3%A9ry%27s_constant), and as a consequence, the number was named after him. The values at negative integer points, also found by Euler, are [rational number](https://en.wikipedia.org/wiki/rational_number)s and play an important role in the theory of [modular form](https://en.wikipedia.org/wiki/modular_form)s. [Many generalizations](https://en.wikipedia.org/wiki/List_of_zeta_functions) of the Riemann zeta function, such as [Dirichlet series](https://en.wikipedia.org/wiki/Dirichlet_series), [Dirichlet $L$-functions](https://en.wikipedia.org/wiki/Dirichlet_L-function) and [ $L$-functions](https://en.wikipedia.org/wiki/L-function), are known.

## Definition

<figure>

![Bernhard Riemann's article On the number of primes below a given magnitude](https://pub-275e30003c354ac0862cc9839e0f952a.r2.dev/docs/math/Ueber_die_Anzahl_der_Primzahlen_unter_einer_gegebenen_Gr%C3%B6sse.pdf.jpg)

<figcaption>

Bernhard Riemann's article *On the number of primes below a given magnitude*

</figcaption>

</figure>

The Riemann zeta function $ζ(s)$ is a function of a complex variable $s = σ + it$, where $σ$ and $t$ are real numbers. (The notation $s$, $σ$, and $t$ is used traditionally in the study of the zeta function, following Riemann.) When $Re(s) = σ > 1$, the function can be written as a converging summation or as an integral:

$$
\zeta(s) =\sum_{n=1}^\infty\frac{1}{n^s} = \frac{1}{\Gamma(s)} \int_0^\infty \frac{x ^ {s-1}}{e ^ x - 1} \, \mathrm{d}x\,,
$$

where

$$
\Gamma(s) = \int_0^\infty x^{s-1}\,e^{-x} \, \mathrm{d}x
$$

is the [gamma function](https://en.wikipedia.org/wiki/gamma_function). The Riemann zeta function is defined for other complex values via [analytic continuation](https://en.wikipedia.org/wiki/analytic_continuation) of the function defined for $σ > 1$.

[Leonhard Euler](https://en.wikipedia.org/wiki/Leonhard_Euler) considered the above series in 1740 for positive integer values of $s$, and later [Chebyshev](https://en.wikipedia.org/wiki/Chebyshev) extended the definition to $Re(s) > 1$.[^4]

The above series is a prototypical [Dirichlet series](https://en.wikipedia.org/wiki/Dirichlet_series) that [converges absolutely](https://en.wikipedia.org/wiki/absolute_convergence) to an [analytic function](https://en.wikipedia.org/wiki/analytic_function) for $s$ such that $σ > 1$ and [diverges](https://en.wikipedia.org/wiki/divergent_series) for all other values of $s$. Riemann showed that the function defined by the series on the half-plane of convergence can be continued analytically to all complex values $s ≠ 1$. For $s = 1$, the series is the [harmonic series](https://en.wikipedia.org/wiki/harmonic_series_%28mathematics%29) which diverges to $+∞$, and

$$
\lim_{s \to 1} (s - 1)\zeta(s) = 1.
$$

Thus the Riemann zeta function is a [meromorphic function](https://en.wikipedia.org/wiki/meromorphic_function) on the whole complex plane, which is [holomorphic](https://en.wikipedia.org/wiki/holomorphic_function) everywhere except for a [simple pole](https://en.wikipedia.org/wiki/simple_pole) at $s = 1$ with [residue](https://en.wikipedia.org/wiki/Residue_%28complex_analysis%29) $1$.

## Euler's product formula

In 1737, the connection between the zeta function and [prime number](https://en.wikipedia.org/wiki/prime_number)s was discovered by Euler, who [proved the identity](https://en.wikipedia.org/wiki/Proof_of_the_Euler_product_formula_for_the_Riemann_zeta_function)

$$
\sum_{n=1}^\infty\frac{1}{n^s} = \prod_{p \text{ prime}} \frac{1}{1-p^{-s}},
$$

where, by definition, the left hand side is $ζ(s)$ and the [infinite product](https://en.wikipedia.org/wiki/infinite_product) on the right hand side extends over all prime numbers $p$ (such expressions are called [Euler product](https://en.wikipedia.org/wiki/Euler_product)s):

$$
\prod_{p \text{ prime}} \frac{1}{1-p^{-s}} = \frac{1}{1-2^{-s}}\cdot\frac{1}{1-3^{-s}}\cdot\frac{1}{1-5^{-s}}\cdot\frac{1}{1-7^{-s}}\cdot\frac{1}{1-11^{-s}} \cdots \frac{1}{1-p^{-s}} \cdots
$$

Both sides of the Euler product formula converge for $Re(s) > 1$. The [proof of Euler's identity](https://en.wikipedia.org/wiki/Proof_of_the_Euler_product_formula_for_the_Riemann_zeta_function) uses only the formula for the [geometric series](https://en.wikipedia.org/wiki/geometric_series) and the [fundamental theorem of arithmetic](https://en.wikipedia.org/wiki/fundamental_theorem_of_arithmetic). Since the [harmonic series](https://en.wikipedia.org/wiki/harmonic_series_%28mathematics%29), obtained when $s = 1$, diverges, Euler's formula (which becomes $Π_p p/p − 1$) implies that there are [infinitely many primes](https://en.wikipedia.org/wiki/Euclid%27s_theorem).[^5] Since the logarithm of $p/(p − 1)$ is approximately $1/p$, the formula can also be used to prove the stronger result that the sum of the reciprocals of the primes is infinite. On the other hand, combining that with the [sieve of Eratosthenes](https://en.wikipedia.org/wiki/sieve_of_Eratosthenes) shows that the density of the set of primes within the set of positive integers is zero.

The Euler product formula can be used to calculate the [asymptotic probability](https://en.wikipedia.org/wiki/asymptotic_density) that $s$ randomly selected integers within a bound are set-wise [coprime](https://en.wikipedia.org/wiki/coprime). Intuitively, the probability that any single number is divisible by a prime (or any integer) $p$ is $1/p$. Hence the probability that $s$ numbers are all divisible by this prime is $1/p^{s}$, and the probability that at least one of them is *not* is $1 − 1/p^{s}$. Now, for distinct primes, these divisibility events are mutually independent because the candidate divisors are coprime (a number is divisible by coprime divisors $n$ and $m$ [if and only if](https://en.wikipedia.org/wiki/if_and_only_if) it is divisible by $nm$, an event which occurs with probability $1/(nm)$). Thus the asymptotic probability that $s$ numbers are coprime is given by a product over all primes,[^6]

$$
\prod_{p \text{ prime}} \left(1-\frac{1}{p^s}\right) = \left( \prod_{p \text{ prime}} \frac{1}{1-p^{-s}} \right)^{-1} = \frac{1}{\zeta(s)}.
$$

## Riemann's functional equation

This zeta function satisfies the [functional equation](https://en.wikipedia.org/wiki/functional_equation)

$$
\zeta(s) = 2^s \pi^{s-1}\ \sin\left( \frac{\pi s}{2} \right)\ \Gamma(1-s)\ \zeta(1-s)\ ,
$$

where $Γ(s)$ is the [gamma function](https://en.wikipedia.org/wiki/gamma_function). This is an equality of meromorphic functions valid on the whole [complex plane](https://en.wikipedia.org/wiki/complex_plane). The equation relates values of the Riemann zeta function at the points $s$ and $1 − s$, in particular relating even positive integers with odd negative integers. Owing to the zeros of the sine function, the functional equation implies that $ζ(s)$ has a simple zero at each even negative integer $s = −2n$, known as the **[trivial](https://en.wikipedia.org/wiki/Triviality_%28mathematics%29) zeros** of $ζ(s)$. When $s$ is an even positive integer, the product $\sin\left(\frac{\pi s}{2}\right)\Gamma(1-s)$ on the right is non-zero because $Γ(1 − s)$ has a simple [pole](https://en.wikipedia.org/wiki/pole_%28complex_analysis%29), which cancels the simple zero of the sine factor. When $s$ is $0$, the zero of the sine factor is cancelled by the simple pole of $ζ(1)$.

**Proof of Riemann's functional equation**

A proof of the functional equation proceeds as follows:
We observe that if $Re(s) > 0$, then

$$
\int_0^\infty x^{ \frac{1}{2} s - 1 } e^{-n^2\pi x}\ \mathrm dx\ =\ \frac{\ \Gamma\!\left( \frac{s}{2} \right)\ }{\ n^s\ \pi^{\frac{s}{2}}\ } ~.
$$

As a result, if $Re(s) > 1$ then

$$
\frac{\ \Gamma\!\left(\frac{s}{2}\right)\ \zeta(s)\ }{\ \pi^{ \frac{s}{2} }\ }\ =\ \sum_{n=1}^\infty\ \int_0^\infty\ x^{{s\over 2}-1}\ e^{-n^2 \pi x}\ \mathrm dx\ =\ \int_0^\infty x^{{s\over 2}-1} \sum_{n=1}^\infty e^{-n^2 \pi x}\ \mathrm dx\ ,
$$

with the inversion of the limiting processes justified by absolute convergence (hence the stricter requirement on $s$).

For convenience, let

$$
\psi(x)\ := \ \sum_{n=1}^\infty\ e^{-n^2 \pi x} ,
$$

which is a special case of the [theta function](https://en.wikipedia.org/wiki/theta_function).

Because $t \mapsto e^{-t^2 \pi x}$ and $t \mapsto \frac{1}{\sqrt{x}} e^{\frac{-t^2 \pi}{x}}$ are [Fourier transform pairs](https://en.wikipedia.org/wiki/Fourier_transform#Definition),[^7] then, by the [Poisson summation formula](https://en.wikipedia.org/wiki/Poisson_summation_formula), we have

$$
\sum_{n=-\infty}^\infty\ e^{ - n^2 \pi\ x }\ =\ \frac{ 1 }{\ \sqrt{x\ }\ }\ \sum_{n=-\infty}^\infty\ e^{ -\frac{\ n^2 \pi\ }{ x } }\ ,
$$

so that

$$
\ 2\ \psi(x) + 1\ =\ \frac{ 1 }{\ \sqrt{x\ }\ } \left(\ 2\ \psi\!\left( \frac{ 1 }{ x } \right) + 1\ \right) ~.
$$

Hence

$$
\pi^{ -\frac{s}{2} }\ \Gamma\!\left( \frac{s}{2} \right)\ \zeta(s)\ =\ \int_0^1\ x^{ \frac{s}{2} - 1 }\ \psi(x)\ \mathrm dx + \int_1^\infty x^{ \frac{s}{2} - 1 } \psi(x)\ \mathrm dx ~.
$$

The right side is equivalent to

$$
\int_0^1 x^{ \frac{s}{2} - 1 } \left( \frac{ 1 }{\ \sqrt{x\ }\ }\ \psi\!\left( \frac{1}{x} \right) + \frac{ 1 }{\ 2 \sqrt{x\ }\ } - \frac{ 1 }{ 2 }\ \right) \ \mathrm dx + \int_1^\infty x^{{s\over 2}-1} \psi(x)\ \mathrm dx
$$

or

$$
\frac{ 1 }{\ s - 1\ } - \frac{ 1 }{\ s\ } + \int_0^1\ x^{ \frac{s}{2} - \frac{3}{2}}\ \psi\!\left( \frac{ 1 }{\ x\ } \right)\ \mathrm dx + \int_1^\infty\ x^{ \frac{s}{2} - 1 }\ \psi(x)\ \mathrm dx
~.
$$

So

$$
\pi^{ -\frac{ s }{ 2 } }\ \Gamma\!\left( \frac{\ s\ }{ 2 } \right)\ \zeta(s)\ =\ \frac{ 1 }{\ s ( s - 1 )\ } + \int_1^\infty\ \left( x^{ -\frac{ s }{ 2 } - \frac{ 1 }{ 2 } } + x^{ \frac{ s }{ 2 } - 1 } \right)\ \psi(x)\ \mathrm dx
$$

which is convergent for all $s$, because $ψ(x) → 0$ more quickly than any power of $x$ for $x > 1$, so the integral converges. As the RHS remains the same if $s$ is replaced by $1 − s$,

$$
\frac{\ \Gamma\!\left(\ \frac{s}{2}\ \right)\ \zeta\!\left(\ s\ \right)\ }{\ \pi^{ \frac{s}{2}\ }\ }\ =\ \frac{\ \Gamma\!\left(\ \frac{1}{2} - \frac{s}{2}\ \right)\ \zeta\!\left(\ 1 - s\ \right)\ }{\ \pi^{ \frac{1}{2} - \frac{s}{2} }\ }
$$

which is the functional equation attributed to [Bernhard Riemann](https://en.wikipedia.org/wiki/Bernhard_Riemann).[^8]

The functional equation above can be obtained using both the [reflection formula](https://en.wikipedia.org/wiki/reflection_formula) and the [duplication formula](https://en.wikipedia.org/wiki/Multiplication_theorem#Gamma_function%E2%80%93Legendre_formula).

First collect terms of $π$:

$$
\Gamma\left(\frac{s}{2}\right)\zeta\left(s\right) = \Gamma\left(\frac{1}{2} - \frac{s}{2}\right)\zeta\left(1 - s\right)\pi^{s-\frac{1}{2}}
$$

Then multiply both sides by $Γ(1 − s/2)$ and use the reflection formula:

$$
\Gamma\left(1-\frac s2\right)\Gamma\left(\frac{s}{2}\right)\zeta\left(s\right) = \Gamma\left(1-\frac s2\right)\Gamma\left(\frac{1}{2} - \frac{s}{2}\right)\zeta\left(1 - s\right)\pi^{s-\frac{1}{2}}
$$

$$
\zeta\left(s\right) = \sin\left(\frac{\pi s}2\right)\Gamma\left(1-\frac s2\right)\Gamma\left(\frac{1}{2} - \frac{s}{2}\right)\zeta\left(1 - s\right)\pi^{s-\frac{3}{2}}
$$

Use the duplication formula with $z = (1 − s)/2$

$$
\zeta\left(s\right) = \sin\left(\frac{\pi s}2\right)2^{1-1+s}\sqrt{\pi}\Gamma\left(1-s\right)\zeta\left(1 - s\right)\pi^{s-\frac{3}{2}}
$$

so that

$$
\zeta\left(s\right) = \sin\left(\frac{\pi s}2\right)2^s\Gamma\left(1-s\right)\zeta\left(1 - s\right)\pi^{s-1}
$$

The functional equation was established by Riemann in his 1859 paper "[On the Number of Primes Less Than a Given Magnitude](https://en.wikipedia.org/wiki/On_the_Number_of_Primes_Less_Than_a_Given_Magnitude)" and used to construct the analytic continuation in the first place.

In the adelic formulation developed in [Tate's thesis](https://en.wikipedia.org/wiki/Tate%27s_thesis), the so-called Gamma factor
$\pi^{-s/2}\Gamma(s/2)$ is interpreted as the local zeta factor at the [Archimedean place](https://en.wikipedia.org/wiki/Archimedean_place).

## Riemann's xi function

Riemann also found a [symmetric](https://en.wikipedia.org/wiki/Symmetry) version of the functional equation by setting

$$
\xi(s) =\frac{s(s-1)}{2}\pi^{-\frac{s}{2}}\Gamma\left( \frac{s}{2} \right)\zeta(s) =  (s-1)\pi^{-\frac{s}{2}}\Gamma\left(\frac{s}{2}+1\right)\zeta(s)
$$

that satisfies:

$$
\xi(s) = \xi(1 - s) ~.
$$

The xi function is an [entire function](https://en.wikipedia.org/wiki/entire_function) whose zeros are exactly the non-trivial zeros of the Riemann zeta function.

Returning to the functional equation's derivation in the previous section, we have

$$
\xi(s) =\frac12 + \frac{s(s-1)}{2} \int_1^\infty \left(x^{-\frac{s}{2}-\frac{1}{2}} + x^{\frac{s}{2}-1}\right)\psi(x) dx,
$$

where

$$
\psi(x)=\sum_{n=1}^{\infty}e^{-\pi n^{2}x}.
$$

Using [integration by parts](https://en.wikipedia.org/wiki/integration_by_parts),

$$
\xi(s) =\frac12 - \left[\left(sx^{\frac{1-s}{2}} + (1-s)x^{\frac{s}{2}}\right)\psi(x)\right]_1^\infty + \int_1^\infty \left(sx^{\frac{1-s}{2}} + (1-s)x^{\frac{s}{2}}\right)\psi'(x) dx
$$

$$
\xi(s) =\frac12 + \psi(1) + \int_1^\infty \left(sx^{\frac{1-s}{2}} + (1-s)x^{\frac{s}{2}}\right)\psi'(x) dx
$$

Using integration by parts again with a factorization of $x^{3/2}$,

$$
\xi(s) =\frac12 + \psi(1) - 2\left[x^{\frac32}\psi'(x)\left(x^{\frac{s-1}{2}} + x^{-\frac{s}{2}}\right)\right]_1^\infty + 2\int_1^\infty \left(x^{\frac{s-1}{2}} + x^{-\frac{s}{2}}\right)\frac{d}{dx}\left[x^{\frac32}\psi'(x)\right] dx
$$

$$
\xi(s) =\frac12 +\psi(1) + 4\psi'(1) + 2\int_1^\infty \frac{d}{dx}\left[x^{\frac32}\psi'(x)\right]\left(x^{\frac{s-1}{2}} + x^{-\frac{s}{2}}\right) dx
$$

As $\frac12 +\psi(1) + 4\psi'(1)=0$,

$$
\xi(s) = 2\int_1^\infty \frac{d}{dx}\left[x^{\frac32}\psi'(x)\right]\left(x^{\frac{s-1}{2}} + x^{-\frac{s}{2}}\right) dx
$$

Remove a factor of $x^{−1/4}$ to make the exponents in the remainder opposites.

$$
\xi(s) = 2\int_1^\infty \frac{d}{dx}\left[x^{\frac32}\psi'(x)\right]x^{-\frac14}\left(x^{\frac{s-1/2}{2}} + x^{\frac{1/2-s}{2}}\right) dx
$$

Using the [hyperbolic functions](https://en.wikipedia.org/wiki/hyperbolic_functions), namely $cos(x) = cosh(ix)$, and letting $s = 1/2 + it$ gives

$$
\xi(s) = 4\int_1^\infty \frac{d}{dx}\left[x^{\frac32}\psi'(x)\right]x^{-\frac14}\cos\left(\frac{t}2\log x\right) dx
$$

and by separating the integral and using the [power series](https://en.wikipedia.org/wiki/power_series) for $cos$,

$$
\xi(s) = \sum_{n=0}^\infty a_{2n}t^{2n}
$$

which led Riemann to his famous hypothesis.

## Zeros, the critical line, and the Riemann hypothesis

<figure style={{"maxWidth": "308px"}}>

![The Riemann zeta function has no zeros to the right of σ = 1 or (apart from the trivial zeros) to the left of σ = 0 (nor can the zeros lie too close to those lines). Furthermore, the non-trivial zeros are symmetric about the real axis and the line σ = 1/2 and, according to the Riemann hypothesis, they all lie on the line σ = 1/2.](https://pub-275e30003c354ac0862cc9839e0f952a.r2.dev/docs/math/Zero-free_region_for_the_Riemann_zeta-function.svg.png)

<figcaption>

The Riemann zeta function has no zeros to the right of $σ = 1$ or (apart from the trivial zeros) to the left of $σ = 0$ (nor can the zeros lie too close to those lines). Furthermore, the non-trivial zeros are symmetric about the real axis and the line $σ = 1/2$ and, according to the [Riemann hypothesis](https://en.wikipedia.org/wiki/Riemann_hypothesis), they all lie on the line $σ = 1/2$.

</figcaption>

</figure>

<figure style={{"maxWidth": "300px"}}>

![This image shows a plot of the Riemann zeta function along the critical line for real values of t running from 0 to 34. The first five zeros in the critical strip are clearly visible as the place where the spirals pass through the origin.](https://pub-275e30003c354ac0862cc9839e0f952a.r2.dev/docs/math/Zeta_polar.svg.png)

<figcaption>

This image shows a plot of the Riemann zeta function along the critical line for real values of $t$ running from 0 to 34. The first five zeros in the critical strip are clearly visible as the place where the spirals pass through the origin.

</figcaption>

</figure>

<figure style={{"maxWidth": "300px"}}>

![The real part (red) and imaginary part (blue) of the Riemann zeta function along the critical line Re(s) = 1/2. The first non-trivial zeros can be seen at Im(s) = ±14.135, ±21.022 and ±25.011.](https://pub-275e30003c354ac0862cc9839e0f952a.r2.dev/docs/math/RiemannCriticalLine.svg.png)

<figcaption>

The real part (red) and imaginary part (blue) of the Riemann zeta function along the critical line $Re(s) = 1/2$. The first non-trivial zeros can be seen at $Im(s) =$ $±14.135$, $±21.022$ and $±25.011$.

</figcaption>

</figure>
The functional equation shows that the Riemann zeta function has zeros at $−2, −4, ...$. These are called the **trivial zeros**. They are trivial in the sense that their existence is relatively easy to prove, for example, from $sin(πs/2)$ being $0$ in the functional equation. The non-trivial zeros have captured far more attention because their distribution not only is far less understood but, more importantly, their study yields important results concerning prime numbers and related objects in number theory. It is known that any non-trivial zero lies in the open strip $\{s ∈ \mathbb{C}\}$, which is called the **critical strip**. The set $\{s ∈ \mathbb{C}\}$ is called the **critical line**. The [Riemann hypothesis](https://en.wikipedia.org/wiki/Riemann_hypothesis), considered one of the greatest unsolved problems in mathematics, asserts that all non-trivial zeros are on the critical line. In 1989, Conrey proved that more than 40% of the non-trivial zeros of the Riemann zeta function are on the critical line.[^9] This was improved to 41.7%,[^10] and then 67.2%.[^11] [^12]

For the Riemann zeta function on the critical line, see [ $Z$-function](https://en.wikipedia.org/wiki/Z_function).

| + First few nontrivial zeros[^13] [^14] |
| --- |
| Zero |
| --- |
| $1/2 ± 14.134725... i$ |
| $1/2 ± 21.022040... i$ |
| $1/2 ± 25.010858... i$ |
| $1/2 ± 30.424876... i$ |
| $1/2 ± 32.935062... i$ |
| $1/2 ± 37.586178... i$ |
| $1/2 ± 40.918719... i$ |

### Number of zeros in the critical strip

Let $N(T)$ be the number of zeros of $ζ(s)$ in the critical strip $0 < Re(s) < 1$, whose imaginary parts are in the interval $0 < Im(s) < T$.
[Timothy Trudgian](https://en.wikipedia.org/wiki/Timothy_Trudgian) proved that, if $T > e$, then[^15]
  $\left|N(T) - \frac{T}{2\pi} \log{\frac{T}{2\pi e}}\right| \leq 0.112 \log T + 0.278 \log\log T + 3.385 + \frac{0.2}{T}$.

### Hardy–Littlewood conjectures

In 1914, [G. H. Hardy](https://en.wikipedia.org/wiki/G._H._Hardy) proved that $ζ( 1/2 + it)$ has infinitely many real zeros.[^16] [^17]

Hardy and [J. E. Littlewood](https://en.wikipedia.org/wiki/John_Edensor_Littlewood) formulated two conjectures on the density and distance between the zeros of $ζ(1/2 + it)$ on intervals of large positive real numbers. In the following, $N(T)$ is the total number of real zeros and $N_0(T)$ the total number of zeros of odd order of the function $ζ(1/2 + it)$ lying in the interval $(0, T]$.

1. For any $ε > 0$, there exists a $T_0(ε) > 0$ such that when

$$
T \geq T_0(\varepsilon) \quad\text{ and }\quad H=T^{\frac14+\varepsilon},
$$

the interval $(T, T + H]$ contains a zero of odd order.

1. For any $ε > 0$, there exists a $T_0(ε) > 0$ and $c_ε > 0$ such that the inequality

$$
N_0(T+H)-N_0(T) \geq c_\varepsilon H
$$

holds when

$$
T \geq T_0(\varepsilon) \quad\text{ and }\quad H=T^{\frac12+\varepsilon}.
$$

These two conjectures opened up new directions in the investigation of the Riemann zeta function.

### Zero-free region

The location of the Riemann zeta function's zeros is of great importance in number theory. The [prime number theorem](https://en.wikipedia.org/wiki/prime_number_theorem) is equivalent to the fact that there are no zeros of the zeta function on the line $Re(s) = 1$.[^18] It is also known that zeros do not exist in certain regions slightly to the left of the line $Re(s) = 1$, known as zero-free regions. For instance, Korobov[^19] and Vinogradov[^20] independently showed via the [Vinogradov's mean-value theorem](https://en.wikipedia.org/wiki/Vinogradov%27s_mean-value_theorem) that for sufficiently large $|t|$, $ζ(σ + it) ≠ 0$ for

$$
\sigma \geq 1 - \frac{c}{(\log|t|)^{2/3 + \varepsilon}}
$$

for any $ε > 0$ and a number $c > 0$ depending on $ε$. Asymptotically, this is the largest known zero-free region for the zeta function.

Explicit zero-free regions are also known. Platt and Trudgian[^21]
verified computationally that $ζ(σ + it) ≠ 0$ if $σ ≠ 1/2$ and $|t| ≤ 3⋅10^{12}$. Mossinghoff, Trudgian and Yang proved[^22] that zeta has no zeros in the region

$$
\sigma\ge 1 - \frac{1}{5.558691\log|t|}
$$

for $|t| ≥ 2$, which is the largest known zero-free region in the critical strip for $3⋅10^{12} < |t| < exp(64.1) ≈ 7⋅10^{27}$ (for previous results see[^23]).
Yang[^24] showed that $ζ(σ + it) ≠ 0$ if
  $\sigma \geq 1 - \frac{\log\log|t|}{21.233\log|t|}$ and $|t| \geq 3$
which is the largest known zero-free region for $exp(170.2) < |t| < exp(4.8⋅10^5)$.
Bellotti proved[^25] (building on the work of Ford[^26]) the zero-free region
  $\sigma \ge 1 - \frac{1}{53.989(\log|t|)^{2/3}(\log\log|t|)^{1/3}}$ and $|t| \ge 3$.
This is the largest known zero-free region for fixed $|t| ≥ exp(4.8⋅10^5)$. Bellotti also showed that for sufficiently large $|t|$, the following better result is known: $ζ(σ + it) ≠ 0$ for

$$
\sigma \geq 1 - \frac{1}{48.0718(\log|t|)^{2/3}(\log\log|t|)^{1/3}}.
$$

The strongest result of this kind one can hope for is the truth of the Riemann hypothesis, which would have many profound [consequences](https://en.wikipedia.org/wiki/Riemann_hypothesis#Consequences) in the theory of numbers.

### Other results

It is known that there are infinitely many zeros on the critical line. [Littlewood](https://en.wikipedia.org/wiki/John_Edensor_Littlewood) showed that if the sequence ( $γ_n$) contains the imaginary parts of all zeros in the [upper half-plane](https://en.wikipedia.org/wiki/upper_half-plane) in ascending order, then

$$
\lim_{n\rightarrow\infty}\left(\gamma_{n+1}-\gamma_n\right)=0.
$$

The [critical line theorem](https://en.wikipedia.org/wiki/critical_line_theorem) asserts that a positive proportion of the nontrivial zeros lies on the critical line. (The Riemann hypothesis would imply that this proportion is $1$.)

In the critical strip, the zero with smallest non-negative imaginary part is $1/2 + 14.13472514... i$ ([A058303](https://oeis.org/A058303)). The fact that, for all complex $s ≠ 1$,

$$
\zeta(s)=\overline{\zeta(\overline{s})}
$$

implies that the zeros of the Riemann zeta function are symmetric about the real axis. Combining this symmetry with the functional equation, furthermore, one sees that the non-trivial zeros are symmetric about the critical line $Re(s) = 1/2$.

It is also known that no zeros lie on the line with real part $1$.

A large class of modified zeta functions exists that share the same non-trivial zeros as the Riemann zeta function, where modification means replacing the prime numbers in the Euler product by real numbers, which was shown in a [result by Grosswald and Schnitzer](https://en.wikipedia.org/wiki/Grosswald%E2%80%93Schnitzer_theorem).

## Specific values

For any positive even integer $2n$,

$$
\zeta(2n) = \frac{|{B_{2n}}|(2\pi)^{2n}}{2(2n)!},
$$

where $B_{2n}$ is the $(2n)$th [Bernoulli number](https://en.wikipedia.org/wiki/Bernoulli_number).
The demonstration of the particular value

$$
\zeta(2) = 1 + \frac{1}{2^2} + \frac{1}{3^2} + \cdots = \frac{\pi^2}{6}
$$

is known as the [Basel problem](https://en.wikipedia.org/wiki/Basel_problem). The reciprocal of this sum answers the question: 'What is the probability that two numbers selected from a uniform distribution from $1$ to $n$] are [coprime](https://en.wikipedia.org/wiki/coprime) as $n → ∞$?'[^27]

For odd positive integers, no such simple expression is known, although these values are thought to be related to the algebraic $K$-theory of the integers; see [Special values of $L$-functions](https://en.wikipedia.org/wiki/Special_values_of_L-functions).
The value

$$
\zeta(3) = 1 + \frac{1}{2^3} + \frac{1}{3^3} + \cdots = 1.202056903159594285399...
$$

is [Apéry's constant](https://en.wikipedia.org/wiki/Ap%C3%A9ry%27s_constant).

For nonpositive integers, the series does not converge, but via [analytic continuation](https://en.wikipedia.org/wiki/analytic_continuation) one can show that

$$
\zeta(-n)= -\frac{B_{n+1}}{n+1}
$$

for $n ≥ 0$ (using the convention that $B_1 = 1/2$).
In particular, $ζ$ vanishes at the negative even integers because $B_m = 0$ for all odd $m$ other than $1$. These are the so-called "trivial zeros" of the zeta function.
Another particular value is

$$
\zeta(-1) = -\tfrac{1}{12}
$$

This gives a pretext for assigning a finite value to the divergent series $1 + 2 + 3 + 4 + ⋯$, which has been used in certain contexts ([Ramanujan summation](https://en.wikipedia.org/wiki/Ramanujan_summation)) such as [string theory](https://en.wikipedia.org/wiki/string_theory).[^28] Analogously,

$$
\zeta(0) = -\tfrac{1}{2}
$$

can be viewed as assigning a finite result to the divergent series $1 + 1 + 1 + 1 + ⋯$.

The value

$$
\zeta\bigl(\tfrac12\bigr) = -1.46035450880958681288\ldots
$$

is employed in calculating kinetic boundary layer problems of linear kinetic equations.[^29] [^30]

Although

$$
\zeta(1) = 1 + \tfrac{1}{2} + \tfrac{1}{3} + \cdots
$$

diverges, its [Cauchy principal value](https://en.wikipedia.org/wiki/Cauchy_principal_value)

$$
\lim_{\varepsilon \to 0} \frac{\zeta(1+\varepsilon)+\zeta(1-\varepsilon)}{2}
$$

exists and is equal to the [Euler–Mascheroni constant](https://en.wikipedia.org/wiki/Euler%E2%80%93Mascheroni_constant) $γ = 0.5772...$.[^31]

Taking the limit $s → +∞$ through the real numbers, one obtains $ζ(+∞) = 1$. But at [complex infinity](https://en.wikipedia.org/wiki/complex_infinity) on the [Riemann sphere](https://en.wikipedia.org/wiki/Riemann_sphere) the zeta function has an [essential singularity](https://en.wikipedia.org/wiki/essential_singularity).[^2]

## Various properties

For sums involving the zeta function at integer and [half-integer](https://en.wikipedia.org/wiki/half-integer) values, see [rational zeta series](https://en.wikipedia.org/wiki/rational_zeta_series).

### Reciprocal

The reciprocal of the zeta function may be expressed as a [Dirichlet series](https://en.wikipedia.org/wiki/Dirichlet_series) over the [Möbius function](https://en.wikipedia.org/wiki/M%C3%B6bius_function) $μ(n)$:

$$
\frac{1}{\zeta(s)} = \sum_{n=1}^\infty \frac{\mu(n)}{n^s}
$$

for every complex number $s$ with real part greater than $1$. There are a number of similar relations involving various well-known [multiplicative function](https://en.wikipedia.org/wiki/multiplicative_function)s; these are given in the article on the [Dirichlet series](https://en.wikipedia.org/wiki/Dirichlet_series).

The Riemann hypothesis is equivalent to the claim that this expression is valid when the real part of $s$ is greater than $1/2$.

### Universality

The critical strip of the Riemann zeta function has the remarkable property of **universality**. This [zeta function universality](https://en.wikipedia.org/wiki/zeta_function_universality) states, roughly, that vertical translates of $\zeta(s)$ can uniformly approximate any nonvanishing holomorphic function on suitable compact subsets of the strip $1/2<\operatorname{Re}(s)<1$. Since holomorphic functions are very general, this property is quite remarkable. The first proof of universality was provided by [Sergei Mikhailovitch Voronin](https://en.wikipedia.org/wiki/Sergei_Mikhailovitch_Voronin) in 1975.[^32] More recent work has included [effective](https://en.wikipedia.org/wiki/Zeta_function_universality#Effective_universality) versions of Voronin's theorem[^33] and [extending](https://en.wikipedia.org/wiki/Zeta_function_universality#Universality_of_other_zeta_functions) it to [Dirichlet $L$-function](https://en.wikipedia.org/wiki/Dirichlet_L-function)s.[^34] [^35]

### Estimates of the maximum of the modulus of the zeta function

Let the functions $F(T; H)$ and $G(s_0; Δ)$ be defined by the equalities

$$
F(T;H) = \max_{|t-T|\le H}\left|\zeta\left(\tfrac{1}{2}+it\right)\right|,\qquad G(s_{0};\Delta) = \max_{|s-s_{0}|\le\Delta}|\zeta(s)|.
$$

Here $T$ is a sufficiently large positive number, $0 < H ≪ log log T$, $s_0 = σ_0 + iT$, $1/2 ≤ σ_0 ≤ 1$, $0 < Δ < 1/3$. Estimating the values $F$ and $G$ from below shows, how large (in modulus) values $ζ(s)$ can take on short intervals of the critical line or in small neighborhoods of points lying in the critical strip $0 ≤ Re(s) ≤ 1$.

The case $H ≫ log log T$ was studied by [Kanakanahalli Ramachandra](https://en.wikipedia.org/wiki/Kanakanahalli_Ramachandra); the case $Δ > c$, where $c$ is a sufficiently large constant, is trivial.

[Anatolii Karatsuba](https://en.wikipedia.org/wiki/Anatolii_Alexeevitch_Karatsuba) proved,[^36] [^37] in particular, that if the values $H$ and $Δ$ exceed certain sufficiently small constants, then the estimates

$$
F(T;H) \ge T^{- c_1},\qquad G(s_0; \Delta) \ge T^{-c_2},
$$

hold, where $c_1$ and $c_2$ are certain absolute constants.

### Argument of the Riemann zeta function

The function

$$
S(t) = \frac{1}{\pi}\arg{\zeta\left(\tfrac12+it\right)}
$$

is called the [argument](https://en.wikipedia.org/wiki/complex_argument) of the Riemann zeta function. Here $arg ζ(1/2 + it)$ is the increment of an arbitrary continuous branch of $arg ζ(s)$ along the broken line joining the points $2$, $2 + it$ and $1/2 + it$.

There are some theorems on properties of the function $S(t)$. Among those results[^38] [^39] are the [mean value theorems](https://en.wikipedia.org/wiki/Mean_value_theorems_for_definite_integrals) for $S(t)$ and its first integral

$$
S_1(t) = \int_0^t S(u) \, \mathrm{d}u
$$

on intervals of the real line, and also the theorem claiming that every interval $(T, T + H]$ for

$$
H \ge T^{\frac{27}{82}+\varepsilon}
$$

contains at least

$$
H\sqrt[3]{\ln T}e^{-c\sqrt{\ln\ln T}}
$$

points where the function $S(t)$ changes sign. Earlier similar results were obtained by [Atle Selberg](https://en.wikipedia.org/wiki/Atle_Selberg) for the case

$$
H\ge T^{\frac12+\varepsilon}.
$$

## Representations

### Dirichlet series

An extension of the area of convergence can be obtained by rearranging the original series.[^40] The series

$$
\zeta(s)=\frac{1}{s-1}\sum_{n=1}^\infty \left(\frac{n}{(n+1)^s}-\frac{n-s}{n^s}\right)
$$

converges for $Re(s) > 0$, while

$$
\zeta(s) =\frac{1}{s-1}\sum_{n=1}^\infty\frac{n(n+1)}{2}\left(\frac{2n+3+s}{(n+1)^{s+2}}-\frac{2n-1-s}{n^{s+2}}\right)
$$

converge even for $Re(s) > −1$. In this way, the area of convergence can be extended to $Re(s) > −k$ for any negative integer $−k$.

The recurrence connection is clearly visible from the expression valid for $Re(s) > −2$ enabling further expansion by integration by parts.

$$
\begin{aligned}
\zeta(s)= & 1+\frac{1}{s-1}-\frac{s}{2 !}[\zeta(s+1)-1] \\
- & \frac{s(s+1)}{3 !}[\zeta(s+2)-1] \\
& -\frac{s(s+1)(s+2)}{3 !} \sum_{n=1}^{\infty} \int_0^1 \frac{t^3 d t}{(n+t)^{s+3}}.
\end{aligned}
$$

This recurrence leads to this other series development that uses the [rising factorial](https://en.wikipedia.org/wiki/Pochhammer_symbol) and is valid for the entire complex plane [^40]

$$
\zeta(s) = \frac{s}{s-1} - \sum_{n=1}^\infty \bigl(\zeta(s+n)-1\bigr)\frac{s(s+1)\cdots(s+n-1)}{(n+1)!}.
$$

This can be used recursively to extend the Dirichlet series definition to all complex numbers.

The Riemann zeta function also appears in a form similar to the Mellin transform in an integral over the [Gauss–Kuzmin–Wirsing operator](https://en.wikipedia.org/wiki/Gauss%E2%80%93Kuzmin%E2%80%93Wirsing_operator) acting on $x^{s−1}$; that context gives rise to a series expansion in terms of the [falling factorial](https://en.wikipedia.org/wiki/falling_factorial).[^41]

### Mellin-type integrals

The [Mellin transform](https://en.wikipedia.org/wiki/Mellin_transform) of a function $f(x)$ is defined as[^42]

$$
\int_0^\infty f(x)x^s\, \frac{\mathrm{d}x}{x}
$$

in the region where the integral is defined. There are various expressions for the zeta function as Mellin transform-like integrals. If the real part of $s$ is greater than one, we have
  $\Gamma(s)\zeta(s) =\int_0^\infty\frac{x^{s-1}}{e^x-1} \,\mathrm{d}x \quad$ and $\quad\Gamma(s)\zeta(s) =\frac1{2s}\int_0^\infty\frac{x^{s}}{\cosh(x)-1} \,\mathrm{d}x ,$
where $Γ$ denotes the [gamma function](https://en.wikipedia.org/wiki/gamma_function). By modifying the [contour](https://en.wikipedia.org/wiki/Contour_integration), Riemann showed that

$$
2\sin(\pi s)\Gamma(s)\zeta(s) =i\oint_H \frac{(-x)^{s-1}}{e^x-1}\,\mathrm{d}x
$$

for all $s$[^43] (where $H$ denotes the [Hankel contour](https://en.wikipedia.org/wiki/Hankel_contour)).

We can also find expressions which relate to prime numbers and the [prime number theorem](https://en.wikipedia.org/wiki/prime_number_theorem). If $π(x)$ is the [prime-counting function](https://en.wikipedia.org/wiki/prime-counting_function), then

$$
\ln \zeta(s) = s \int_0^\infty \frac{\pi(x)}{x(x^s-1)}\,\mathrm{d}x,
$$

for values with $Re(s) > 1$.

A similar Mellin transform involves the Riemann function $J(x)$, which counts prime powers $p^n$ with a weight of $1/n$, so that

$$
J(x) = \sum \frac{\pi\left(x^\frac{1}{n}\right)}{n}.
$$

Now

$$
\ln \zeta(s) = s\int_0^\infty J(x)x^{-s-1}\,\mathrm{d}x.
$$

These expressions can be used to prove the prime number theorem by means of the inverse Mellin transform. Riemann's [prime-counting function](https://en.wikipedia.org/wiki/prime-counting_function) is easier to work with, and $π(x)$ can be recovered from it by [Möbius inversion](https://en.wikipedia.org/wiki/M%C3%B6bius_inversion_formula).

### Theta functions

The Riemann zeta function can be given by a Mellin transform[^44]

$$
2\pi^{-\frac{s}{2}}\Gamma\left(\frac{s}{2}\right)\zeta(s) = \int_0^\infty \bigl(\theta(it)-1\bigr)t^{\frac{s}{2}-1}\,\mathrm{d}t,
$$

in terms of [Jacobi's theta function](https://en.wikipedia.org/wiki/Theta_function)

$$
\theta(\tau)= \sum_{n=-\infty}^\infty e^{\pi i n^2\tau}.
$$

However, this integral only converges if the real part of $s$ is greater than $1$, but it can be regularized. This gives the following expression for the zeta function, which is well defined for all $s$ except $0$ and $1$:

$$
\pi^{-\frac{s}{2}}\Gamma\left(\frac{s}{2}\right)\zeta(s) = \frac{1}{s-1}-\frac{1}{s} +\frac{1}{2} \int_0^1 \left(\theta(it)-t^{-\frac12}\right)t^{\frac{s}{2}-1}\,\mathrm{d}t + \frac{1}{2}\int_1^\infty \bigl(\theta(it)-1\bigr)t^{\frac{s}{2}-1}\,\mathrm{d}t.
$$

### Laurent series

The Riemann zeta function is [meromorphic](https://en.wikipedia.org/wiki/meromorphic) with a single [pole](https://en.wikipedia.org/wiki/pole_%28complex_analysis%29) of order one at $s = 1$. It can therefore be expanded as a [Laurent series](https://en.wikipedia.org/wiki/Laurent_series) about $s = 1$; the series development is then[^45]

$$
\zeta(s)=\frac{1}{s-1}+\sum_{n=0}^\infty \frac{\gamma_n}{n!}(1-s)^n.
$$

The constants $γ_n$ here are called the [Stieltjes constants](https://en.wikipedia.org/wiki/Stieltjes_constants) and can be defined by the [limit](https://en.wikipedia.org/wiki/limit_of_a_sequence)

$$
\gamma_n = \lim_{m \rightarrow \infty}{\left(\left(\sum_{k = 1}^m \frac{(\ln k)^n}{k}\right) - \frac{(\ln m)^{n+1}}{n+1}\right)}.
$$

The constant term $γ_0$ is the [Euler–Mascheroni constant](https://en.wikipedia.org/wiki/Euler%E2%80%93Mascheroni_constant).

### Integral

For all $s ∈ \mathbb{C}$, $s ≠ 1$, the integral relation (cf. [Abel–Plana formula](https://en.wikipedia.org/wiki/Abel%E2%80%93Plana_formula))

$$
\zeta(s) = \frac{ 1 }{s - 1} + \frac{1}{2} + 2 \int_0^{\infty} \frac{\sin(s\arctan t) }{ \left(1 + t^2 \right)^{s/2} \left(e^{2\pi t} - 1\right)\ }\ \operatorname{d}t
$$

holds true, which may be used for a numerical evaluation of the zeta function.

### Hadamard product

On the basis of [Weierstrass's factorization theorem](https://en.wikipedia.org/wiki/Weierstrass_factorization_theorem), [Hadamard](https://en.wikipedia.org/wiki/Hadamard) gave the [infinite product](https://en.wikipedia.org/wiki/infinite_product) expansion

$$
\zeta(s) = \frac{e^{\left(\log(2\pi)-1-\frac{\gamma}{2}\right)s}}{2(s-1)\Gamma\left(1+\frac{s}{2}\right)} \prod_\rho \left(1 - \frac{s}{\rho} \right) e^\frac{s}{\rho},
$$

where the product is over the non-trivial zeros $ρ$ of $ζ$ and the letter $γ$ again denotes the [Euler–Mascheroni constant](https://en.wikipedia.org/wiki/Euler%E2%80%93Mascheroni_constant). A simpler [infinite product](https://en.wikipedia.org/wiki/infinite_product) expansion is

$$
\zeta(s) = \pi^\frac{s}{2} \frac{\prod_\rho \left(1 - \frac{s}{\rho} \right)}{2(s-1)\Gamma\left(1+\frac{s}{2}\right)}.
$$

This form clearly displays the simple pole at $s = 1$, the trivial zeros at $−2, −4,$... due to the gamma function term in the denominator, and the non-trivial zeros at $s = ρ$. (To ensure convergence in the latter formula, the product should be taken over "matching pairs" of zeros, i.e. the factors for a pair of zeros of the form $ρ$ and $1 − ρ$ should be combined.)

### Globally convergent series

A globally convergent series for the zeta function, valid for all complex numbers $s$ except $s = 1 + 2πi/ln 2 n$ for some integer $n$, was conjectured by [Konrad Knopp](https://en.wikipedia.org/wiki/Konrad_Knopp) in 1926 [^46] and proven by [Helmut Hasse](https://en.wikipedia.org/wiki/Helmut_Hasse) in 1930[^47] (cf. [Euler summation](https://en.wikipedia.org/wiki/Euler_summation)):

$$
\zeta(s)=\frac{1}{1-2^{1-s}} \sum_{n=0}^\infty \frac {1}{2^{n+1}} \sum_{k=0}^n \binom{n}{k} \frac{(-1)^k}{(k+1)^{s}}.
$$

The series appeared in an appendix to Hasse's paper, and was published for the second time by Jonathan Sondow in 1994.[^48]

Hasse also proved the globally converging series

$$
\zeta(s)=\frac 1{s-1}\sum_{n=0}^\infty \frac 1{n+1}\sum_{k=0}^n\binom {n}{k}\frac{(-1)^k}{(k+1)^{s-1}}
$$

in the same publication.[^47] Research by Iaroslav Blagouchine[^49] [^46]
has found that a similar, equivalent series was published by [Joseph Ser](https://en.wikipedia.org/wiki/Joseph_Ser) in 1926.[^50]

In 1997 K. Maślanka gave another globally convergent (except $s = 1$) series for the Riemann zeta function:

$$
\zeta (s)=\frac{1}{s-1}\sum_{k=0}^\infty \biggl(\prod_{i=1}^{k} (i-\frac{s}{2})\biggl) \frac{A_{k}}{k!}=
\frac{1}{s-1} \sum_{k=0}^\infty \biggl(1-\frac{s}{2}\biggl)_{k}
\frac{A_{k}}{k!}
$$

where real coefficients $A_k$ are given by:

$$
A_k=\sum_{j=0}^{k}(-1)^{j}\binom{k}{j}(2j+1)\zeta
(2j+2)=\sum_{j=0}^{k}\binom{k}{j}\frac{B_{2j+2}\pi ^{2j+2}}{\left(2\right) _{j}\left( \frac{1}{2}\right) _{j}}
$$

Here $B_n$ are the Bernoulli numbers and $(x)_k$ denotes the Pochhammer symbol.[^51] [^52]

Note that this representation of the zeta function is essentially an interpolation with nodes, where the nodes are points $s = 2, 4, 6, ...$, i.e. exactly those where the zeta values are precisely known, as Euler showed. A short proof of this representation of the zeta function follows from [Carlson's theorem](https://en.wikipedia.org/wiki/Carlson%27s_theorem).[^53]

The asymptotic behavior of the coefficients $A_{k}$ is rather curious: for growing $k$ values, we observe regular oscillations with a nearly exponentially decreasing amplitude and slowly decreasing frequency (roughly as $k^{-2/3}$). Using the saddle point method, we can show that

$$
A_{k}\sim \frac{4\pi ^{3/2}}{\sqrt{3\kappa }}\exp \biggl( -\frac{3\kappa }{2}+\frac{\pi ^{2}}{4\kappa }\biggl) \cos \biggl( \frac{4\pi }{3}-\frac{3\sqrt{3}
\kappa }{2}+\frac{\sqrt{3}\pi ^{2}}{4\kappa }\biggl)
$$

where $\kappa$ stands for:

$$
\kappa :=\sqrt[3]{\pi ^{2}k}
$$

(see [^54] for details).

On the basis of this representation, in 2003 Luis Báez-Duarte provided a new criterion for the Riemann hypothesis.[^55] [^56] [^57] Namely, if we define the coefficients $c_k$ as

$$
c_{k}:=\sum_{j=0}^{k}(-1)^{j}\binom{k}{j}\frac{1}{\zeta (2j+2)}
$$

then the Riemann hypothesis is equivalent to

$$
c_{k}=\mathcal{O}\left( k^{-3/4+\varepsilon }\right) \qquad (\forall\varepsilon >0)
$$

### Rapidly convergent series

[Peter Borwein](https://en.wikipedia.org/wiki/Peter_Borwein) developed an algorithm that applies [Chebyshev polynomial](https://en.wikipedia.org/wiki/Chebyshev_polynomial)s to the [Dirichlet eta function](https://en.wikipedia.org/wiki/Dirichlet_eta_function) to produce a [very rapidly convergent series suitable for high precision numerical calculations](https://en.wikipedia.org/wiki/Dirichlet_eta_function#Borwein%27s_method).[^58]

### Series representation at positive integers via the primorial

$$
\zeta(k)=\frac{2^k}{2^k-1}+\sum_{r=2}^\infty\frac{(p_{r-1}\#)^k}{J_k(p_r\#)}\qquad k=2,3,\ldots.
$$

Here $p_n\#$ is the [primorial](https://en.wikipedia.org/wiki/primorial) sequence and $J_k$ is [Jordan's totient function](https://en.wikipedia.org/wiki/Jordan%27s_totient_function).[^59]

### Series representation by the incomplete poly-Bernoulli numbers

The function $ζ$ can be represented, for $Re(s) > 1$, by the infinite series

$$
\zeta(s)=\sum_{n=0}^\infty B_{n,\ge2}^{(s)}\frac{(W_k(-1))^n}{n!},
$$

where $k ∈ \{−1, 0\}$, $W_k$ is the $k$th branch of the [Lambert $W$-function](https://en.wikipedia.org/wiki/Lambert_W_function), and $B^{(μ)}_{n,≥2}$ is an incomplete poly-Bernoulli number.[^60]

### Mellin transform of the Engel map

The function $g(x) = x(1 + \lfloor x^{−1} \rfloor) − 1$ is iterated to find the coefficients appearing in [Engel expansion](https://en.wikipedia.org/wiki/Engel_expansion)s.[^61]

The [Mellin transform](https://en.wikipedia.org/wiki/Mellin_transform) of the map $g(x)$ is related to the Riemann zeta function by the formula

$$
\begin{align}
    \int_0^1 g (x) x^{s - 1} \, dx & = \sum_{n = 1}^\infty
    \int_{\frac{1}{n + 1}}^{\frac{1}{n}} (x (n + 1) - 1) x^{s - 1} \, d x\\[6pt]
    & = \sum_{n = 1}^\infty \frac{n^{- s} (s - 1) + (n + 1)^{- s - 1} (n^2 + 2 n + 1) + n^{- s - 1} s - n^{1 - s}}{(s + 1) s (n + 1)}\\[6pt]
    & = \frac{\zeta (s + 1)}{s + 1} - \frac{1}{s (s + 1)}
  \end{align}
$$

### Stochastic representations

The [Brownian motion and Riemann zeta function](https://en.wikipedia.org/wiki/Brownian_motion_and_Riemann_zeta_function) are connected through the [moment-generating function](https://en.wikipedia.org/wiki/moment-generating_function)s of [stochastic process](https://en.wikipedia.org/wiki/stochastic_process)es derived from the [Brownian motion](https://en.wikipedia.org/wiki/Brownian_motion).[^62]

## Numerical algorithms

A classical algorithm, in use prior to about 1930, proceeds by applying the [Euler–Maclaurin formula](https://en.wikipedia.org/wiki/Euler%E2%80%93Maclaurin_formula) to obtain, for positive integers $n$ and $m$,

$$
\zeta(s) = \sum_{j=1}^{n-1}j^{-s} + \tfrac12 n^{-s} + \frac{n^{1-s}}{s-1} + \sum_{k=1}^m T_{k,n}(s) + E_{m,n}(s)
$$

where, letting $B_{2k}$ denote the indicated [Bernoulli number](https://en.wikipedia.org/wiki/Bernoulli_number),

$$
T_{k,n}(s) = \frac{B_{2k}}{(2k)!} n^{1-s-2k}\prod_{j=0}^{2k-2}(s+j)
$$

and the error satisfies

$$
|E_{m,n}(s)| < \left|\frac{s+2m+1}{\sigma + 2m + 1}T_{m+1,n}(s)\right|,
$$

with $σ = Re(s)$.[^63]

A modern numerical algorithm is the [Odlyzko–Schönhage algorithm](https://en.wikipedia.org/wiki/Odlyzko%E2%80%93Sch%C3%B6nhage_algorithm).

## Applications

The zeta function occurs in applied [statistics](https://en.wikipedia.org/wiki/statistics) including [Zipf's law](https://en.wikipedia.org/wiki/Zipf%27s_law), [Zipf–Mandelbrot law](https://en.wikipedia.org/wiki/Zipf%E2%80%93Mandelbrot_law), and [Lotka's law](https://en.wikipedia.org/wiki/Lotka%27s_law).

[Zeta function regularization](https://en.wikipedia.org/wiki/Zeta_function_regularization) is used as one possible means of [regularization](https://en.wikipedia.org/wiki/regularization_%28physics%29) of [divergent series](https://en.wikipedia.org/wiki/divergent_series) and [divergent integral](https://en.wikipedia.org/wiki/divergent_integral)s in [quantum field theory](https://en.wikipedia.org/wiki/quantum_field_theory). In one notable example, the Riemann zeta function shows up explicitly in one method of calculating the [Casimir effect](https://en.wikipedia.org/wiki/Casimir_effect). The zeta function is also useful for the analysis of [dynamical systems](https://en.wikipedia.org/wiki/dynamical_systems).[^64]

### Musical tuning

In the theory of [musical tuning](https://en.wikipedia.org/wiki/musical_tuning)s, the zeta function can be used to find [equal divisions of the octave](https://en.wikipedia.org/wiki/Equal_temperament) (EDOs) that closely approximate the intervals of the [harmonic series](https://en.wikipedia.org/wiki/Harmonic_series_%28music%29). For increasing values of $t \in \mathbb{R}$, the value of

$$
\left\vert \zeta \left( \frac{1}{2} + \frac{2\pi{i}}{\ln{(2)}}t \right) \right\vert
$$

peaks near integers that correspond to such EDOs.[^65] Examples include popular choices such as 12, 19, and 53.[^66]

### Infinite series

The zeta function evaluated at equidistant positive integers appears in infinite series representations of a number of constants.[^67]
*

$$
\sum_{n=2}^\infty\bigl(\zeta(n)-1\bigr) = 1
$$

In fact the even and odd terms give the two sums
*

$$
\sum_{n=1}^\infty\bigl(\zeta(2n)-1\bigr)=\frac{3}{4}
$$

and
*

$$
\sum_{n=1}^\infty\bigl(\zeta(2n+1)-1\bigr)=\frac{1}{4}
$$

Parametrized versions of the above sums are given by
*

$$
\sum_{n=1}^\infty(\zeta(2n)-1)\,t^{2n} = \frac{t^2}{t^2-1} + \frac{1}{2} \left(1- \pi t\cot(\pi t)\right)
$$

and
*

$$
\sum_{n=1}^\infty(\zeta(2n+1)-1)\,t^{2n} = \frac{t^2}{t^2-1} -\frac{1}{2}\left(\psi^0(t)+\psi^0(-t) \right) - \gamma
$$

with $|t| < 2$ and where $\psi$ and $\gamma$ are the [polygamma function](https://en.wikipedia.org/wiki/polygamma_function) and [Euler's constant](https://en.wikipedia.org/wiki/Euler%27s_constant), respectively, as well as
*

$$
\sum_{n=1}^\infty \frac{\zeta(2n)-1}{n}\,t^{2n} = \log\left(\dfrac{1-t^2}{\operatorname{sinc}(\pi\,t)}\right)
$$

all of which are continuous at $t=1$. Other sums include
*

$$
\sum_{n=2}^\infty\frac{\zeta(n)-1}{n} = 1-\gamma
$$

*

$$
\sum_{n=1}^\infty\frac{\zeta(2n)-1}{n} = \ln 2
$$

*

$$
\sum_{n=2}^\infty\frac{\zeta(n)-1}{n} \left(\left(\tfrac{3}{2}\right)^{n-1}-1\right) = \frac{1}{3} \ln \pi
$$

*

$$
\sum_{n=1}^\infty\bigl(\zeta(4n)-1\bigr) = \frac78-\frac{\pi}{4}\left(\frac{e^{2\pi}+1}{e^{2\pi}-1}\right)
$$

*

$$
\sum_{n=2}^\infty\frac{\zeta(n)-1}{n}\Im \bigl((1+i)^n-1-i^n\bigr) = \frac{\pi}{4}
$$

where $\Im$ denotes the [imaginary part](https://en.wikipedia.org/wiki/imaginary_part) of a complex number.

Another interesting series that relates to the [natural logarithm](https://en.wikipedia.org/wiki/natural_logarithm) of the [lemniscate constant](https://en.wikipedia.org/wiki/lemniscate_constant) is the following
*

$$
\sum_{n=2}^\infty\left[\frac{2(-1)^n\zeta(n)}{4^n n}-\frac{(-1)^n\zeta(n)}{2^n n} \right]= \ln \left( \frac{\varpi}{2\sqrt2} \right)
$$

There are yet more formulas in the article [Harmonic number.](https://en.wikipedia.org/wiki/Harmonic_number#Relation_to_the_Riemann_zeta_function)

## Generalizations

There are a number of related [zeta function](https://en.wikipedia.org/wiki/zeta_function)s that can be considered to be generalizations of the Riemann zeta function. These include the [Hurwitz zeta function](https://en.wikipedia.org/wiki/Hurwitz_zeta_function)

$$
\zeta(s,q) = \sum_{k=0}^\infty \frac{1}{(k+q)^s}
$$

(the convergent series representation was given by [Helmut Hasse](https://en.wikipedia.org/wiki/Helmut_Hasse) in 1930,[^47] cf. [Hurwitz zeta function](https://en.wikipedia.org/wiki/Hurwitz_zeta_function)), which coincides with the Riemann zeta function when $q = 1$ (the lower limit of summation in the Hurwitz zeta function is $0$, not $1$), the [Dirichlet $L$-functions](https://en.wikipedia.org/wiki/Dirichlet_L-function) and the [Dedekind zeta function](https://en.wikipedia.org/wiki/Dedekind_zeta_function). For other related functions see the articles [zeta function](https://en.wikipedia.org/wiki/zeta_function) and [ $L$-function](https://en.wikipedia.org/wiki/L-function).

The [polylogarithm](https://en.wikipedia.org/wiki/polylogarithm) is given by

$$
\operatorname{Li}_s(z) = \sum_{k=1}^\infty \frac{z^k}{k^s}
$$

which coincides with the Riemann zeta function when $z = 1$.
The [Clausen function](https://en.wikipedia.org/wiki/Clausen_function) $Cl_s(θ)$ can be chosen as the real or imaginary part of $Li_s(e^{iθ})$.

The [Lerch transcendent](https://en.wikipedia.org/wiki/Lerch_transcendent) is given by

$$
\Phi(z, s, q) = \sum_{k=0}^\infty\frac {z^k} {(k+q)^s}
$$

which coincides with the Riemann zeta function when $z = 1$ and $q = 1$ (the lower limit of summation in the Lerch transcendent is $0$, not $1$).

The [multiple zeta functions](https://en.wikipedia.org/wiki/multiple_zeta_functions) are defined by

$$
\zeta(s_1,s_2,\ldots,s_n) = \sum_{k_1>k_2>\cdots>k_n>0} {k_1}^{-s_1}{k_2}^{-s_2}\cdots {k_n}^{-s_n}.
$$

One can analytically continue these functions to the $n$-dimensional complex space. The special values taken by these functions at positive integer arguments are called [multiple zeta values](https://en.wikipedia.org/wiki/multiple_zeta_values) by number theorists and have been connected to many different branches in mathematics and physics.

## See also

* [1 + 2 + 3 + 4 + ···](https://en.wikipedia.org/wiki/1_%2B_2_%2B_3_%2B_4_%2B_%C2%B7%C2%B7%C2%B7)
* [Arithmetic zeta function](https://en.wikipedia.org/wiki/Arithmetic_zeta_function)
* [Generalized Riemann hypothesis](https://en.wikipedia.org/wiki/Generalized_Riemann_hypothesis)
* [Lehmer pair](https://en.wikipedia.org/wiki/Lehmer_pair)
* [Prime zeta function](https://en.wikipedia.org/wiki/Prime_zeta_function)
* [Renormalization](https://en.wikipedia.org/wiki/Renormalization)
* [Riemann–Siegel theta function](https://en.wikipedia.org/wiki/Riemann%E2%80%93Siegel_theta_function)
* [ZetaGrid](https://en.wikipedia.org/wiki/ZetaGrid)

## References

## Sources

* T.M. Apostol. [Zeta and Related Functions](https://dlmf.nist.gov/25), *NIST Digital Library of Mathematical Functions*.
* Borwein, Jonathan; Bradley, David M.; Crandall, Richard (2000). *Computational Strategies for the Riemann Zeta Function*. *J. Comput. Appl. Math.* **121**(1–2), 247–296. [2000JCoAM.121..247B](https://ui.adsabs.harvard.edu/abs/2000JCoAM.121..247B). doi:[10.1016/S0377-0427(00)00336-8](https://doi.org/10.1016/S0377-0427%2800%2900336-8).
* Cvijović, Djurdje; Klinowski, Jacek (2002). *Integral representations of the Riemann zeta function for odd-integer arguments*. *J. Comput. Appl. Math.* **142**(2), 435–439. [MR1906742](https://mathscinet.ams.org/mathscinet-getitem?mr=MR1906742). [2002JCoAM.142..435C](https://ui.adsabs.harvard.edu/abs/2002JCoAM.142..435C). doi:[10.1016/S0377-0427(02)00358-8](https://doi.org/10.1016/S0377-0427%2802%2900358-8).
* Cvijović, Djurdje; Klinowski, Jacek (1997). *Continued-fraction expansions for the Riemann zeta function and polylogarithms*. *Proc. Amer. Math. Soc.* **125**(9), 2543–2550. doi:[10.1090/S0002-9939-97-04102-6](https://doi.org/10.1090/S0002-9939-97-04102-6).
* Edwards, H.M. (1974). *Riemann's Zeta Function*. *Academic Press*. ISBN 0-486-41740-9. [Riemann's Zeta Function](https://archive.org/details/riemannszetafunc00edwa_0). Has an English translation of Riemann's paper.
* Hadamard, Jacques (1896). *Sur la distribution des zéros de la fonction ζ(s) et ses conséquences arithmétiques*. *Bulletin de la Société Mathématique de France* **14**, 199–220. doi:[10.24033/bsmf.545](https://doi.org/10.24033/bsmf.545).
* Hardy, G.H. (1949). *Divergent Series*. *Clarendon Press*.
* Hasse, Helmut (1930). *Ein Summierungsverfahren für die Riemannsche ζ-Reihe*. *Math. Z.* **32**, 458–464. [MR1545177](https://mathscinet.ams.org/mathscinet-getitem?mr=MR1545177). doi:[10.1007/BF01194645](https://doi.org/10.1007/BF01194645). (Globally convergent series expression.)
* Ivic, Aleksandar (1985). *The Riemann Zeta Function*. *John Wiley & Sons*. ISBN 0-471-80634-X.
*Motohashi, Y. (1997). *Spectral Theory of the Riemann Zeta-Function*. *Cambridge University Press*. ISBN 0-521-44520-5.
* Karatsuba, A.A.; Voronin, S.M. (1992). *The Riemann Zeta-Function*. *W. de Gruyter*.
* Montgomery, Hugh L.; Vaughan, Robert C. (2007). *Multiplicative Number Theory. I. Classical theory*. *Cambridge University Press* **97**. ISBN 978-0-521-84903-6.
* Newman, Donald J. (1998). *Analytic Number Theory*. *Springer-Verlag* **177**. ISBN 0-387-98308-2.
* Raoh, Guo (1996). *The distribution of the logarithmic derivative of the Riemann zeta function*. *Proceedings of the London Mathematical Society* **S3–72**, 1–27. doi:[10.1112/plms/s3-72.1.1](https://doi.org/10.1112/plms/s3-72.1.1).
* Riemann, Bernhard (1859). *Über die Anzahl der Primzahlen unter einer gegebenen Grösse*. *Monatsberichte der Berliner Akademie*. [Über die Anzahl der Primzahlen unter einer gegebenen Grösse](http://www.maths.tcd.ie/pub/HistMath/People/Riemann/Zeta/). Also available in Riemann, Bernhard (1953). *Gesammelte Werke*. *Dover (1953) / Teubner (1892)*.
* Sondow, Jonathan (1994). *Analytic continuation of Riemann's zeta function and values at negative integers via Euler's transformation of series*. *Proceedings of the American Mathematical Society* **120**(2), 421–424. doi:[10.1090/S0002-9939-1994-1172954-7](https://doi.org/10.1090/S0002-9939-1994-1172954-7). [Analytic continuation of Riemann's zeta function and values at negative integers via Euler's transformation of series](https://www.ams.org/journals/proc/1994-120-02/S0002-9939-1994-1172954-7/S0002-9939-1994-1172954-7.pdf).
* Titchmarsh, E.C. (1986). *The Theory of the Riemann Zeta Function*. *Oxford University Press*.
* Whittaker, E.T.; Watson, G.N. (1927). *A Course in Modern Analysis*. *Cambridge University Press*.
* Zhao, Jianqiang (1999). *Analytic continuation of multiple zeta functions*. *Proceedings of the American Mathematical Society* **128**(5), 1275–1283. [MR1670846](https://mathscinet.ams.org/mathscinet-getitem?mr=MR1670846). doi:[10.1090/S0002-9939-99-05398-8](https://doi.org/10.1090/S0002-9939-99-05398-8).

## External links

*
* [Zeta-function](https://encyclopediaofmath.org/wiki/Zeta-function), Encyclopedia of Mathematics.
* [Riemann Zeta Function, in Wolfram Mathworld](http://mathworld.wolfram.com/RiemannZetaFunction.html) — an explanation with a more mathematical approach
* [Tables of selected zeros](http://dtc.umn.edu/~odlyzko/zeta_tables) [Archived 17 May 2009](https://web.archive.org/web/20090517003700/http://dtc.umn.edu/~odlyzko/zeta_tables/)
* [Prime Numbers Get Hitched](https://web.archive.org/web/20080721030342/http://seedmagazine.com/news/2006/03/prime_numbers_get_hitched.php) A general, non-technical description of the significance of the zeta function in relation to prime numbers.
* [X-Ray of the Zeta Function](https://arxiv.org/abs/math/0309433v1) Visually oriented investigation of where zeta is real or purely imaginary.
* [Formulas and identities for the Riemann Zeta function](http://functions.wolfram.com/ZetaFunctionsandPolylogarithms/Zeta/) functions.wolfram.com
* [Riemann Zeta Function and Other Sums of Reciprocal Powers](http://www.math.sfu.ca/~cbm/aands/page_807.htm), section 23.2 of [Abramowitz and Stegun](https://en.wikipedia.org/wiki/Abramowitz_and_Stegun)
* Frenkel, Edward (11 March 2014). *Million Dollar Math Problem*. *Brady Haran*. [Million Dollar Math Problem](https://www.youtube.com/watch?v=d6c6uIyieoo).
* [Mellin transform and the functional equation of the Riemann Zeta function](https://combinatorialsums.risc.jku.at/papers/rfeq.pdf)—Computational examples of Mellin transform methods involving the Riemann Zeta Function
* [Visualizing the Riemann zeta function and analytic continuation](https://www.youtube.com/watch?v=sD0NjbwqlYw) a video from [3Blue1Brown](https://en.wikipedia.org/wiki/3Blue1Brown)

## Notes

[^1]: *Jupyter Notebook Viewer*. *Nbviewer.ipython.org*. [Jupyter Notebook Viewer](http://nbviewer.ipython.org/github/empet/Math/blob/master/DomainColoring.ipynb).
[^2]: Steuding, Jörn; Suriajaya, Ade Irma (2020-11-01). *Value-Distribution of the Riemann Zeta-Function Along Its Julia Lines*. *Computational Methods and Function Theory* **20**(3), 389–401. [arXiv:2007.14661](https://arxiv.org/abs/2007.14661). doi:[10.1007/s40315-020-00316-x](https://doi.org/10.1007/s40315-020-00316-x).
[^3]: Bombieri, Enrico. *The Riemann Hypothesis – official problem description*. *Clay Mathematics Institute*. [The Riemann Hypothesis – official problem description](http://www.claymath.org/sites/default/files/official_problem_description.pdf).
[^4]: Devlin, Keith (2002). *The Millennium Problems: The seven greatest unsolved mathematical puzzles of our time*. *Barnes & Noble*, 43–47. ISBN 978-0-7607-8659-8.
[^5]: Sandifer, Charles Edward (2007). *How Euler Did It*. *Mathematical Association of America*, 193. ISBN 978-0-88385-563-8.
[^6]: Mollin, Richard A. (2010). *Advanced Number Theory with Applications*. *CRC Press, Boca Raton, FL*, 220. ISBN 978-1-4200-8328-6. [MR2560324](https://mathscinet.ams.org/mathscinet-getitem?mr=MR2560324). [Advanced Number Theory with Applications](https://books.google.com/books?id=6I1setlljDYC&pg=PA220).
[^7]: Damm-Johnsenn, Håvard (2019). *Theta functions and their applications*. 5. [Theta functions and their applications](https://users.ox.ac.uk/~quee4127/theta.pdf).
[^8]: Titchmarsh, E.C. (1986). *The Theory of the Riemann Zeta Function*. *Oxford Science Publications*, 21–22. ISBN 0-19-853369-1.
[^9]: Conrey, J. B. (1989). *More than two fifths of the zeros of the Riemann zeta function are on the critical line*. *J. Reine Angew. Math.* **1989**(399), 1–26. [MR1004130](https://mathscinet.ams.org/mathscinet-getitem?mr=MR1004130). doi:[10.1515/crll.1989.399.1](https://doi.org/10.1515/crll.1989.399.1). [More than two fifths of the zeros of the Riemann zeta function are on the critical line](http://www.digizeitschriften.de/resolveppn/GDZPPN002206781).
[^10]: Pratt, Kyle; Robles, Nicolas; Zaharescu, Alexandru; Zeindler, Dirk (2020). *More than five-twelfths of the zeros of $\zeta$ are on the critical line*. *Research in the Mathematical Sciences* **7**. [arXiv:1802.10521](https://arxiv.org/abs/1802.10521). doi:[10.1007/s40687-019-0199-8](https://doi.org/10.1007/s40687-019-0199-8). [More than five-twelfths of the zeros of $\zeta$ are on the critical line](https://link.springer.com/article/10.1007/s40687-019-0199-8).
[^11]: Markman, Jon. *Claude Just Broke A Math Record That Stood For 37 Years*. [Claude Just Broke A Math Record That Stood For 37 Years](https://www.forbes.com/sites/jonmarkman/2026/08/13/claude-just-broke-a-math-record-that-stood-for-37-years/).
[^12]: ENGINEER, Chew Loong Nian-AI (13 August 2026). *Claude Cracked the 41.6% Wall on Riemann's Zeros — I Counted 138,069 and All Were on the Line*. [Claude Cracked the 41.6% Wall on Riemann's Zeros — I Counted 138,069 and All Were on the Line](https://medium.com/@chewloongnian/claude-cracked-the-41-6-wall-on-riemanns-zeros-i-counted-138-069-and-all-were-on-the-line-abd2d9fd2bdb).
[^13]: Eric Weisstein. *Riemann Zeta Function Zeros*. [Riemann Zeta Function Zeros](https://mathworld.wolfram.com/RiemannZetaFunctionZeros.html).
[^14]: The L-functions and Modular Forms Database. *Zeros of ζ(s)*. [Zeros of ζ(*s*)](https://www.lmfdb.org/zeros/zeta/).
[^15]: Trudgian, Timothy S. (2014). *An improved upper bound for the argument of the Riemann zeta function on the critical line II*. *J. Number Theory* **134**, 280–292. [arXiv:1208.5846](https://arxiv.org/abs/1208.5846). doi:[10.1016/j.jnt.2013.07.017](https://doi.org/10.1016/j.jnt.2013.07.017).
[^16]: Hardy, G.H. (1914). *Sur les zeros de la fonction ζ(s)*. *Comptes rendus de l'Académie des Sciences* **158**, 1012–1014.
[^17]: Hardy, G. H.; Fekete, M.; Littlewood, J. E. (1921-09-01). *The Zeros of Riemann's Zeta-Function on the Critical Line*. *Journal of the London Mathematical Society* **s1-1**, 15–19. doi:[10.1112/jlms/s1-1.1.15](https://doi.org/10.1112/jlms/s1-1.1.15). [The Zeros of Riemann's Zeta-Function on the Critical Line](https://zenodo.org/record/1447415).
[^18]: Diamond, Harold G. (1982). *Elementary methods in the study of the distribution of prime numbers*. *Bulletin of the American Mathematical Society* **7**(3), 553–589. [MR670132](https://mathscinet.ams.org/mathscinet-getitem?mr=MR670132). doi:[10.1090/S0273-0979-1982-15057-1](https://doi.org/10.1090/S0273-0979-1982-15057-1).
[^19]: Korobov, Nikolai Mikhailovich (1958). *Estimates of trigonometric sums and their applications*. *Usp. Mat. Nauk* **13**, 185–192.
[^20]: Vinogradov, I.M. (1958). *Eine neue Abschätzung der Funktion ζ(1 + it)*. *Russian. Izv. Akad. Nauk SSSR, Ser. Mat* **22**, 161–164.
[^21]: Platt, David; Trudgian, Timothy S. (2021). *The Riemann hypothesis is true up to 3⋅10<sup>12</sup>*. *Bulletin of the London Mathematical Society* **53**, 792–797. [arXiv:2004.09765](https://arxiv.org/abs/2004.09765). doi:[10.1112/blms.12460](https://doi.org/10.1112/blms.12460).
[^22]: Mossinghoff, Michael J.; Trudgian, Timothy S.; Yang, Andrew (2024). *Explicit zero-free regions for the Riemann zeta-function*. *Res. Number Theory* **10**. [arXiv:2212.06867](https://arxiv.org/abs/2212.06867). doi:[10.1007/s40993-023-00498-y](https://doi.org/10.1007/s40993-023-00498-y).
[^23]: Mossinghoff, Michael J.; Trudgian, Timothy S. (2015). *Nonnegative trigonometric polynomials and a zero-free region for the Riemann zeta-function*. *J. Number Theory* **157**, 329–349. [arXiv:1410.3926](https://arxiv.org/abs/1410.3926). doi:[10.1016/J.JNT.2015.05.010](https://doi.org/10.1016/J.JNT.2015.05.010).
[^24]: Yang, Andrew (2024). *Explicit bounds on $\zeta(s)$ in the critical strip and a zero-free region*. *J. Math. Anal. Appl.* **534**. [arXiv:2301.03165](https://arxiv.org/abs/2301.03165). doi:[10.1016/j.jmaa.2024.128124](https://doi.org/10.1016/j.jmaa.2024.128124).
[^25]: Bellotti, Chiara (2024). *Explicit bounds for the Riemann zeta function and a new zero-free region*. *J. Math. Anal. Appl.* **536**. [arXiv:2306.10680](https://arxiv.org/abs/2306.10680). doi:[10.1016/j.jmaa.2024.128249](https://doi.org/10.1016/j.jmaa.2024.128249).
[^26]: Ford, K. (2002). *Vinogradov's integral and bounds for the Riemann zeta function*. *Proc. London Math. Soc.* **85**(3), 565–633. [arXiv:1910.08209](https://arxiv.org/abs/1910.08209). doi:[10.1112/S0024611502013655](https://doi.org/10.1112/S0024611502013655).
[^27]: Ogilvy, C. S.; Anderson, J. T. (1988). *Excursions in Number Theory*. *Dover Publications*, 29–35. ISBN 0-486-25778-9.
[^28]: Polchinski, Joseph (1998). *An Introduction to the Bosonic String*. *Cambridge University Press* **I**, 22. ISBN 978-0-521-63303-1.
[^29]: Kainz, A. J.; Titulaer, U. M. (1992). *An accurate two-stream moment method for kinetic boundary layer problems of linear kinetic equations*. *J. Phys. A: Math. Gen.* **25**(7), 1855–1874. [1992JPhA...25.1855K](https://ui.adsabs.harvard.edu/abs/1992JPhA...25.1855K). doi:[10.1088/0305-4470/25/7/026](https://doi.org/10.1088/0305-4470/25/7/026).
[^30]: Further digits and references for this constant are available at [A059750](https://oeis.org/A059750).
[^31]: Sondow, Jonathan (1998). *An antisymmetric formula for Euler's constant*. *Mathematics Magazine* **71**(3), 219–220. doi:[10.1080/0025570X.1998.11996638](https://doi.org/10.1080/0025570X.1998.11996638). [An antisymmetric formula for Euler's constant](http://home.earthlink.net/~jsondow/id8.html).
[^32]: Voronin, S. M. (1975). *Theorem on the Universality of the Riemann Zeta Function*. *Izv. Akad. Nauk SSSR, Ser. Matem.* **39**, 475–486. Reprinted in *Math. USSR Izv.* (1975) **9**: 443–445.
[^33]: Ramūnas Garunkštis (2010). *Effective uniform approximation by the Riemann zeta-function*. *Publicacions Matemàtiques* **54**(1), 209–219. [JSTOR 43736941](https://www.jstor.org/stable/43736941). doi:[10.5565/PUBLMAT_54110_12](https://doi.org/10.5565/PUBLMAT_54110_12). [Effective uniform approximation by the Riemann zeta-function](http://ddd.uab.cat/record/52304).
[^34]: Bhaskar Bagchi (1982). *A Joint Universality Theorem for Dirichlet L-Functions*. *Mathematische Zeitschrift* **181**(3), 319–334. doi:[10.1007/bf01161980](https://doi.org/10.1007/bf01161980).
[^35]: Steuding, Jörn (2007). *Value-Distribution of L-Functions*. *Springer* **1877**, 19. ISBN 978-3-540-26526-9. [arXiv:1711.06671](https://arxiv.org/abs/1711.06671). doi:[10.1007/978-3-540-44822-8](https://doi.org/10.1007/978-3-540-44822-8).
[^36]: Karatsuba, A. A. (2001). *Lower bounds for the maximum modulus of ζ(s) in small domains of the critical strip*. *Mat. Zametki* **70**(5), 796–798.
[^37]: Karatsuba, A. A. (2004). *Lower bounds for the maximum modulus of the Riemann zeta function on short segments of the critical line*. *Izv. Ross. Akad. Nauk, Ser. Mat.* **68**(8), 99–104. [2004IzMat..68.1157K](https://ui.adsabs.harvard.edu/abs/2004IzMat..68.1157K). doi:[10.1070/IM2004v068n06ABEH000513](https://doi.org/10.1070/IM2004v068n06ABEH000513).
[^38]: Karatsuba, A. A. (1996). *Density theorem and the behavior of the argument of the Riemann zeta function*. *Mat. Zametki*, 448–449.
[^39]: Karatsuba, A. A. (1996). *On the function S(t)*. *Izv. Ross. Akad. Nauk, Ser. Mat.* **60**(5), 27–56.
[^40]: Knopp, Konrad (1947). *Theory of Functions, Part Two*. *New York, Dover publications*, [51–55](https://archive.org/details/in.ernet.dli.2015.212186/page/n57/mode/2up). [Theory of Functions, Part Two](https://archive.org/details/in.ernet.dli.2015.212186).
[^41]: *A series representation for the Riemann Zeta derived from the Gauss-Kuzmin-Wirsing Operator*. *Linas.org*. [A series representation for the Riemann Zeta derived from the Gauss-Kuzmin-Wirsing Operator](http://linas.org/math/poch-zeta.pdf).
[^42]: Riemann, Bernhard (1859). *On the number of primes less than a given magnitude*. *Monatsberichte der Königlich Preußischen Akademie der Wissenschaften zu Berlin*. translated and reprinted in Edwards, H. M. (1974). *Riemann's Zeta Function*. *Academic Press*. ISBN 0-12-232750-0.
[^43]: Trivial exceptions of values of $s$ that cause removable singularities are not taken into account throughout this article.
[^44]: Neukirch, Jürgen (1999). *Algebraic number theory*. *Springer*, 422. ISBN 3-540-65399-6.
[^45]: Hashimoto, Yasufumi; Iijima, Yasuyuki; Kurokawa, Nobushige; Wakayama, Masato (2004). *Euler's constants for the Selberg and the Dedekind zeta functions*. *Bulletin of the Belgian Mathematical Society, Simon Stevin* **11**(4), 493–516. [MR2115723](https://mathscinet.ams.org/mathscinet-getitem?mr=MR2115723). doi:[10.36045/bbms/1102689119](https://doi.org/10.36045/bbms/1102689119). [Euler's constants for the Selberg and the Dedekind zeta functions](https://projecteuclid.org/euclid.bbms/1102689119).
[^46]: Blagouchine, Iaroslav V. (2018). *Three Notes on Ser's and Hasse's Representations for the Zeta-functions*. *INTEGERS: The Electronic Journal of Combinatorial Number Theory* **18A**, 1–45. [arXiv:1606.02044](https://arxiv.org/abs/1606.02044). [2016arXiv160602044B](https://ui.adsabs.harvard.edu/abs/2016arXiv160602044B). doi:[10.5281/zenodo.10581385](https://doi.org/10.5281/zenodo.10581385). [Three Notes on Ser's and Hasse's Representations for the Zeta-functions](http://math.colgate.edu/~integers/vol18a.html).
[^47]: Hasse, Helmut (1930). *Ein Summierungsverfahren für die Riemannsche ζ-Reihe*. *Mathematische Zeitschrift* **32**(1), 458–464. doi:[10.1007/BF01194645](https://doi.org/10.1007/BF01194645).
[^48]: Sondow, Jonathan (1994). *Analytic continuation of Riemann's zeta function and values at negative integers via Euler's transformation of series*. *Proceedings of the American Mathematical Society* **120**(2), 421–424. doi:[10.1090/S0002-9939-1994-1172954-7](https://doi.org/10.1090/S0002-9939-1994-1172954-7). [Analytic continuation of Riemann's zeta function and values at negative integers via Euler's transformation of series](https://www.ams.org/journals/proc/1994-120-02/S0002-9939-1994-1172954-7/S0002-9939-1994-1172954-7.pdf).
[^49]: Blagouchine, Iaroslav V. (2016). *Expansions of generalized Euler's constants into the series of polynomials in $\pi$<sup>−2</sup> and into the formal enveloping series with rational coefficients only*. *Journal of Number Theory* **158**, 365–396. [arXiv:1501.00740](https://arxiv.org/abs/1501.00740). doi:[10.1016/j.jnt.2015.06.012](https://doi.org/10.1016/j.jnt.2015.06.012).
[^50]: Ser, Joseph (1926). *Sur une expression de la fonction ζ(s) de Riemann*. *Comptes rendus hebdomadaires des séances de l'Académie des Sciences* **182**, 1075–1077.
[^51]: Maślanka, Krzysztof (1997). *The Beauty of Nothingness*. *Acta Cosmologica* **XXIII-I**, 13–17.
[^52]: Báez-Duarte, Luis (2010). *On Maslanka's Representation for the Riemann Zeta Function*. *International Journal of Mathematics and Mathematical Sciences* **2010**, 1–9. [arXiv:math/0307214](https://arxiv.org/abs/math/0307214). doi:[10.1155/2010/714147](https://doi.org/10.1155/2010/714147).
[^53]: Flajolet, Philippe; Vepstas, Linas (2008). *On Differences of Zeta Values*. *Journal of Computational and Applied Mathematics* **220**(1–2 October), 58–73. [arXiv:math/0611332](https://arxiv.org/abs/math/0611332). [2008JCoAM.220...58F](https://ui.adsabs.harvard.edu/abs/2008JCoAM.220...58F). doi:[10.1016/j.cam.2007.07.040](https://doi.org/10.1016/j.cam.2007.07.040).
[^54]: Maślanka, Krzysztof; Koleżyński, Andrzej (2022). *The High Precision Numerical Calculation of Stieltjes Constants. Simple and Fast Algorithm*. *Computational Methods in Science and Technology* **28**(2), 47–59. [arXiv:2210.04609](https://arxiv.org/abs/2210.04609). doi:[10.12921/cmst.2022.0000014](https://doi.org/10.12921/cmst.2022.0000014).
[^55]: Báez-Duarte, Luis (2003). *A New Necessary and Sufficient Condition for the Riemann Hypothesis*. *Number Theory*. [arXiv:math/0307215](https://arxiv.org/abs/math/0307215). [2003math......7215B](https://ui.adsabs.harvard.edu/abs/2003math......7215B).
[^56]: Maślanka, Krzysztof (2006). *Báez-Duarte's Criterion for the Riemann Hypothesis and Rice's Integrals*. *Number Theory*. [arXiv:math/0603713v2](https://arxiv.org/abs/math/0603713v2). [2006math......3713M](https://ui.adsabs.harvard.edu/abs/2006math......3713M).
[^57]: Wolf, Marek (2014). *Some remarks on the Báez-Duarte criterion for the Riemann Hypothesis*. *Computational Methods in Science and Technology* **20**(2), 39–47. doi:[10.12921/cmst.2014.20.02.39-47](https://doi.org/10.12921/cmst.2014.20.02.39-47).
[^58]: Borwein, Peter (2000). *Constructive, Experimental, and Nonlinear Analysis*. *American Mathematical Society, on behalf of the Canadian Mathematical Society* **27**, 29–34. ISBN 978-0-8218-2167-1.
[^59]: Mező, István (2013). *The primorial and the Riemann zeta function*. *The American Mathematical Monthly* **120**(4), 321.
[^60]: Komatsu, Takao; Mező, István (2016). *Incomplete poly-Bernoulli numbers associated with incomplete Stirling numbers*. *Publicationes Mathematicae Debrecen* **88**(3–4), 357–368. [arXiv:1510.05799](https://arxiv.org/abs/1510.05799). doi:[10.5486/pmd.2016.7361](https://doi.org/10.5486/pmd.2016.7361).
[^61]: *A220335 – OEIS*. *oeis.org*. [A220335 – OEIS](http://oeis.org/A220335).
[^62]: Biane, Philippe; Pitman, Jim; Yor, Marc (2001). *Probability laws related to the Jacobi theta and Riemann zeta functions, and Brownian excursions*. *Bulletin of the American Mathematical Society* **38**(4), 435–465. doi:[10.1090/S0273-0979-01-00912-0](https://doi.org/10.1090/S0273-0979-01-00912-0). [Probability laws related to the Jacobi theta and Riemann zeta functions, and Brownian excursions](https://www.ams.org/journals/bull/2001-38-04/S0273-0979-01-00912-0/).
[^63]: Odlyzko, A. M.; Schönhage, A. (1988). *Fast algorithms for multiple evaluations of the Riemann zeta function*. *Trans. Amer. Math. Soc.* **309**(2), 797–809. [MR0961614](https://mathscinet.ams.org/mathscinet-getitem?mr=MR0961614). [JSTOR 2000939](https://www.jstor.org/stable/2000939). doi:[10.2307/2000939](https://doi.org/10.2307/2000939).
[^64]: *Work on spin-chains by A. Knauf, et al*. *Empslocal.ex.ac.uk*. [Work on spin-chains by A. Knauf, et al.](http://empslocal.ex.ac.uk/people/staff/mrwatkin/zeta/spinchains.htm).
[^65]: Gene Ward Smith. *Nearest integer to locations of increasingly large peaks of abs(zeta(0.5 + i×2×Pi/log(2)×t)) for increasing real t*. *The On-Line Encyclopedia of Integer Sequences*. [Nearest integer to locations of increasingly large peaks of abs(zeta(0.5 + i×2×Pi/log(2)×t)) for increasing real t](https://oeis.org/A117536).
[^66]: William A. Sethares (2005). *Tuning, Timbre, Spectrum, Scale*. *Springer-Verlag London*, 74.
[^67]: Most of the formulas in this section are from § 4 of J. M. Borwein et al. (2000)
