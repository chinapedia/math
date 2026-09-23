---
title: Riemann hypothesis
---

<figure style={{"maxWidth": "264px"}}>

![This plot of Riemann's zeta ( ζ) function (here with argument z) shows trivial zeros where ζ(z)=0, a pole where ζ(z) → ∞, the critical line of nontrivial zeros with Re(z) = 1/2 and density of absolute values.](https://pub-275e30003c354ac0862cc9839e0f952a.r2.dev/docs/math/Riemann_zeta_function_absolute_value.png)

<figcaption>

This plot of Riemann's zeta ( $\zeta$) function (here with argument $z$) shows trivial zeros where $\zeta(z)=0$, a pole where *ζ*(*z*) → $\infty$, the *critical line* of nontrivial zeros with [Re(*z*)](https://en.wikipedia.org/wiki/Complex_numbers#Definition_and_basic_operations) = 1/2 and density of absolute values.

</figcaption>

</figure>
In mathematics, the **Riemann hypothesis** is the [conjecture](https://en.wikipedia.org/wiki/conjecture) that the [Riemann zeta function](./riemann_zeta_function.md) has its [zeros](https://en.wikipedia.org/wiki/Root_of_a_function) only at the negative [even integer](https://en.wikipedia.org/wiki/even_integer)s and [complex number](https://en.wikipedia.org/wiki/complex_number)s with [real part](https://en.wikipedia.org/wiki/real_part) $1/2$. Many consider it to be the most important [unsolved problem](https://en.wikipedia.org/wiki/List_of_unsolved_problems_in_mathematics) in [pure mathematics](https://en.wikipedia.org/wiki/pure_mathematics). Bombieri, Enrico (2000). *The Riemann Hypothesis – official problem description*. *Clay Mathematics Institute*. [The Riemann Hypothesis – official problem description](https://web.archive.org/web/20151222090027/http://www.claymath.org/sites/default/files/official_problem_description.pdf). It is of great interest in [number theory](https://en.wikipedia.org/wiki/number_theory) because it implies results about the distribution of [prime numbers](https://en.wikipedia.org/wiki/prime_numbers). It was proposed by [Bernhard Riemann](https://en.wikipedia.org/wiki/Bernhard_Riemann),[^1] after whom it is named. According to a 2026 survey, there is overwhelming numerical evidence for the hypothesis, but no proof is known.[^2]

The Riemann hypothesis and some of its generalizations, along with [Goldbach's conjecture](./goldbachs_conjecture.md) and the [twin prime conjecture](https://en.wikipedia.org/wiki/twin_prime_conjecture), make up [Hilbert's eighth problem](https://en.wikipedia.org/wiki/Hilbert%27s_eighth_problem) in [David Hilbert](https://en.wikipedia.org/wiki/David_Hilbert)'s list of [twenty-three unsolved problems](https://en.wikipedia.org/wiki/Hilbert%27s_problems); it is also one of the [Millennium Prize Problems](https://en.wikipedia.org/wiki/Millennium_Prize_Problems) of the [Clay Mathematics Institute](https://en.wikipedia.org/wiki/Clay_Mathematics_Institute), which offers [US$](https://en.wikipedia.org/wiki/US%24)1 million for a solution to any of them. The name is also used for some closely related analogues, some of which have been proved, such as the [Riemann hypothesis for curves over finite fields](https://en.wikipedia.org/wiki/Riemann_hypothesis_for_curves_over_finite_fields), which was proved by [André Weil](https://en.wikipedia.org/wiki/Andr%C3%A9_Weil).

The Riemann zeta function $\zeta$ is a [function](https://en.wikipedia.org/wiki/function_%28mathematics%29) whose [argument](https://en.wikipedia.org/wiki/Argument_of_a_function) may be any complex number other than 1, and whose values are also complex. It has zeros at the negative even integers; that is, $\zeta(s)=0$ when $s$ is one of $-2,-4,-6,\dots$ These are called its *trivial zeros*. The zeta function is also zero for other values of $s$, which are called *nontrivial zeros*. The Riemann hypothesis is concerned with the locations of these nontrivial zeros, and states that:

> The real part of every nontrivial zero of the Riemann zeta function is $\frac{1}{2}$.

Thus, the hypothesis states that all the nontrivial zeros lie on the *critical line*, consisting of the complex numbers $\tfrac{1}{2}+it$ where $t$ is a [real number](https://en.wikipedia.org/wiki/real_number) and $i$ is the [imaginary unit](https://en.wikipedia.org/wiki/imaginary_unit).

## Riemann zeta function

The [Riemann zeta function](./riemann_zeta_function.md) is defined for complex $s$ with real part greater than 1 by the [absolutely convergent](https://en.wikipedia.org/wiki/Absolute_convergence) [infinite series](https://en.wikipedia.org/wiki/infinite_series)

$$
\zeta(s) = \sum_{n=1}^\infty \frac{1}{n^s} = \frac{1}{1^s} + \frac{1}{2^s} + \frac{1}{3^s} + \cdots
$$

[Leonhard Euler](https://en.wikipedia.org/wiki/Leonhard_Euler) considered this series in the 1730s for real values of $s$, in conjunction with his solution to the [Basel problem](https://en.wikipedia.org/wiki/Basel_problem). He also proved that it equals the [Euler product](https://en.wikipedia.org/wiki/Euler_product)

$$
\zeta(s) = \prod_{p \text{ prime}} \frac{1}{1-p^{-s}}= \frac{1}{1-2^{-s}}\cdot\frac{1}{1-3^{-s}}\cdot\frac{1}{1-5^{-s}}\cdot\frac{1}{1-7^{-s}} \cdots
$$

where the [infinite product](https://en.wikipedia.org/wiki/infinite_product) extends over all prime numbers $p$.[^3]

The Riemann hypothesis discusses zeros outside the [region of convergence](https://en.wikipedia.org/wiki/region_of_convergence) of this series and Euler product. To make sense of the hypothesis, it is necessary to [analytically continue](https://en.wikipedia.org/wiki/Analytic_continuation) the function to obtain a form that is valid for all complex $s$. Because the zeta function is [meromorphic](https://en.wikipedia.org/wiki/meromorphic), all choices of how to perform this analytic continuation will lead to the same result, by the [identity theorem](https://en.wikipedia.org/wiki/identity_theorem). A first step in this continuation observes that the series for the zeta function and the [Dirichlet eta function](https://en.wikipedia.org/wiki/Dirichlet_eta_function) satisfy the relation

$$
\left(1-\frac{2}{2^s}\right)\zeta(s) = \eta(s) = \sum_{n=1}^\infty \frac{(-1)^{n+1}}{n^s} = \frac{1}{1^s} - \frac{1}{2^s} + \frac{1}{3^s} - \cdots,
$$

within the region of convergence for both series. But the eta function series on the right converges not just when the real part of $s$ is greater than one, but more generally whenever $s$ has positive real part. Thus, the zeta function can be redefined as $\eta(s)/(1-2/2^s)$, extending it from $\operatorname{Re}(s)>1$ to the larger domain $\operatorname{Re}(s)>0$, except for the points where $1-2/2^s$ is zero. These are the points $s = 1 + 2\pi in/\log 2$, where $n$ can be any nonzero integer; the zeta function can be extended to these values too by taking limits (see the article on the [Dirichlet eta function](https://en.wikipedia.org/wiki/Dirichlet_eta_function#Landau%27s_problem_with_%CE%B6%28s%29_%3D_%CE%B7%28s%29/0_and_solutions)), giving a finite value for all values of $s$ with positive real part except the [simple pole](https://en.wikipedia.org/wiki/simple_pole) at $s = 1$.

In the strip $0<\operatorname{Re}(s)<1$ this extension of the zeta function satisfies the [functional equation](./riemann_zeta_function.md#riemanns-functional-equation)

$$
\zeta(s) = 2^s\pi^{s-1}\ \sin\left(\frac{\pi s}{2}\right)\ \Gamma(1-s)\ \zeta(1-s).
$$

One may then define $\zeta(s)$ for all remaining nonzero complex numbers $s$ ( $\operatorname{Re}(s)\leq 0$ and $s\neq 0$) by applying this equation outside the strip, and letting $\zeta(s)$ equal the right side of the equation whenever $s$ has non-positive real part (and $s\neq 0$).

If $s$ is a negative even integer, then $\zeta(s)=0$, because the factor $\sin(\pi s/2)$ vanishes; these are the zeta function's *trivial zeros*. (If $s$ is a positive even integer this argument does not apply because the zeros of the [sine](https://en.wikipedia.org/wiki/sine) function are canceled by the poles of the [gamma function](https://en.wikipedia.org/wiki/gamma_function) as it takes negative integer arguments.)

The value [*ζ*(0) = −1/2](https://en.wikipedia.org/wiki/1_%2B_1_%2B_1_%2B_1_%2B_%E2%8B%AF) is not determined by the functional equation, but is the limiting value of $\zeta(s)$ as $s$ approaches zero. The functional equation also implies that the zeta function has no zeros with negative real part other than the trivial zeros, so all nontrivial zeros lie in the *critical strip* where $s$ has real part between 0 and 1.

<figure>

![Riemann zeta function along the critical line with Re(s) = 1/2. Real values are shown on the horizontal axis and imaginary values are on the vertical axis. Re(ζ(1/2 + it)), Im(ζ(1/2 + it)) is plotted with t ranging between −30 and 30.](https://pub-275e30003c354ac0862cc9839e0f952a.r2.dev/docs/math/ParametricZeta.svg.png)

<figcaption>

Riemann zeta function along the critical line with Re(*s*) = 1/2. Real values are shown on the horizontal axis and imaginary values are on the vertical axis. Re(*ζ*(1/2 + *it*)), Im(*ζ*(1/2 + *it*)) is plotted with *t* ranging between −30 and 30.[^4]

</figcaption>

</figure>

<figure>

![3D animation showing critical strip (blue, where s has real part between 0 and 1), critical line (red, for real part of s equals 0.5) and zeros (cross between red and orange): [x,y,z] = [Re(ζ(r + it)), Im(ζ(r + it)), t] with 0.1≤ r≤ 0.9 and 1≤ t≤ 51.](https://pub-275e30003c354ac0862cc9839e0f952a.r2.dev/docs/math/Riemann3d_Re_0.1_to_0.9_Im_1_to_51.ogg.jpg)

<figcaption>

3D animation showing critical strip (blue, where $s$ has real part between 0 and 1), critical line (red, for real part of $s$ equals 0.5) and zeros (cross between red and orange): [*x*,*y*,*z*] = [Re(*ζ*(*r* + *it*)), Im(*ζ*(*r* + *it*)), *t*] with $0.1\leq r\leq 0.9$ and $1\leq t\leq 51$.

</figcaption>

</figure>

<figure>

![The real part (red) and imaginary part (blue) of the Riemann zeta function ζ(s) along the critical line in the complex plane with real part Re(s)=1/2. The first nontrivial zeros, where ζ(s) equals zero, occur where both curves touch the horizontal x-axis, for complex numbers with imaginary parts equaling ± 14.135, ± 21.022 and ± 25.011.](https://pub-275e30003c354ac0862cc9839e0f952a.r2.dev/docs/math/RiemannCriticalLine.svg.png)

<figcaption>

The real part (red) and imaginary part (blue) of the Riemann zeta function $\zeta(s)$ along the critical line in the [complex plane](https://en.wikipedia.org/wiki/complex_plane) with real part $\operatorname{Re}(s)=1/2$. The first [nontrivial](https://en.wikipedia.org/wiki/Triviality_%28mathematics%29) zeros, where $\zeta(s)$ equals zero, occur where both curves touch the horizontal $x$-axis, for complex numbers with imaginary parts equaling $\pm 14.135$, $\pm 21.022$ and $\pm 25.011$.

</figcaption>

</figure>

## Origin

> ... es ist sehr wahrscheinlich, dass alle Wurzeln reell sind. Hiervon wäre allerdings ein strenger Beweis zu wünschen; ich habe indess die Aufsuchung desselben nach einigen flüchtigen vergeblichen Versuchen vorläufig bei Seite gelassen, da er für den nächsten Zweck meiner Untersuchung entbehrlich schien.
>
> ... it is very probable that all roots are real. Of course one would wish for a rigorous proof here; I have for the time being, after some fleeting vain attempts, provisionally put aside the search for this, as it appears dispensable for the immediate objective of my investigation.
>
> — *Riemann's statement of the Riemann hypothesis, from Riemann, Bernhard (1859). *Ueber die Anzahl der Primzahlen unter einer gegebenen Grösse*. *Monatsberichte der Berliner Akademie*. [Ueber die Anzahl der Primzahlen unter einer gegebenen Grösse](http://www.maths.tcd.ie/pub/HistMath/People/Riemann/Zeta/).. (He was discussing a variant of the zeta function, modified in a way that the real line be mapped to the critical line.)*
> At the death of Riemann, a note was found among his papers, saying "These properties of *ζ*(*s*) (the function in question) are deduced from an expression of it which, however, I did not succeed in simplifying enough to publish it."
>
> We still have not the slightest idea of what the expression could be. As to the properties he simply enunciated, some thirty years elapsed before I was able to prove all of them but one [the Riemann Hypothesis itself].
>
> — [Jacques Hadamard](https://en.wikipedia.org/wiki/Jacques_Hadamard), *The Mathematician's Mind*

Riemann's original motivation for studying the zeta function and its zeros was their occurrence in his [explicit formula](https://en.wikipedia.org/wiki/Explicit_formulae_%28L-function%29) for the [number of primes](https://en.wikipedia.org/wiki/prime-counting_function) $\pi(x)$ less than or equal to a given number $x$, which he published in his 1859 paper "[On the Number of Primes Less Than a Given Magnitude](https://en.wikipedia.org/wiki/On_the_Number_of_Primes_Less_Than_a_Given_Magnitude)". His formula was given in terms of the related function

$$
\Pi(x) = \pi(x) + \frac{\pi(x^{1/2})}{2} +\frac{\pi(x^{1/3})}{3} + \frac{\pi(x^{1/4})}{4} + \frac{\pi(x^{1/5})}{5} +\frac{\pi(x^{1/6})}{6} +\cdots
$$

which counts the primes and prime powers up to $x$, counting a [prime power](https://en.wikipedia.org/wiki/prime_power) $p^n$ as $1/n$. The number of primes can be recovered from this function by using the [Möbius inversion formula](https://en.wikipedia.org/wiki/M%C3%B6bius_inversion_formula):

$$
\begin{align}
\pi(x) &= \sum_{n=1}^\infty \frac{\mu(n)} n \Pi(x^{1/n}) \\
       &= \Pi(x) -\frac{1}{2}\Pi(x^{1/2}) - \frac{1}{3}\Pi(x^{1/3}) - \frac{1}{5}\Pi(x^{1/5}) + \frac{1}{6} \Pi(x^{1/6}) -\cdots,
\end{align}
$$

where $\mu$ is the [Möbius function](https://en.wikipedia.org/wiki/M%C3%B6bius_function). Riemann's formula is then

  $\Pi_0(x) = \operatorname{li}(x) - \sum_\rho \operatorname{li}(x^\rho) -\log 2 + \int_x^\infty\frac{dt}{t(t^2-1) \log t}$,

where the sum is over the nontrivial zeros of the zeta function and where $\Pi_0$ is a slightly modified version of $\Pi$ that replaces its value at its points of [discontinuity](https://en.wikipedia.org/wiki/Discontinuity_%28mathematics%29) by the average of its upper and lower limits:

$$
\Pi_0(x) = \lim_{\varepsilon \to 0}\frac{\Pi(x-\varepsilon) + \Pi(x+\varepsilon)}2.
$$

The summation in Riemann's formula is not absolutely convergent, but may be evaluated by taking the zeros $\rho$ in order of the absolute value of their imaginary part. The function $\operatorname{li}$ occurring in the first term is the (unoffset) [logarithmic integral function](https://en.wikipedia.org/wiki/logarithmic_integral_function) given by the [Cauchy principal value](https://en.wikipedia.org/wiki/Cauchy_principal_value) of the divergent integral

$$
\operatorname{li}(x) = \int_0^x \frac{dt}{\log t}.
$$

The terms $\operatorname{li}(x^\rho)$ involving the zeros of the zeta function need some care in their definition as $\operatorname{li}$ has branch points at 0 and 1, and are defined (for $x>1$) by analytic continuation in the complex variable $\rho$ in the region $\operatorname{Re}(\rho)>0$; i.e., they should be considered as [Ei](https://en.wikipedia.org/wiki/Exponential_integral)(*ρ* log *x*). The other terms also correspond to zeros: the dominant term $\operatorname{li}(x)$ comes from the pole at $s = 1$, considered as a zero of multiplicity $-1$, and the remaining small terms come from the trivial zeros. For some graphs of the sums of the first few terms of this series see Riesel, Hans; Göhl, Gunnar (1970). *Some calculations related to Riemann's prime number formula*. *Mathematics of Computation* **24**(112), 969–983. [MR0277489](https://mathscinet.ams.org/mathscinet-getitem?mr=MR0277489). [JSTOR 2004630](https://www.jstor.org/stable/2004630). doi:[10.2307/2004630](https://doi.org/10.2307/2004630). [Some calculations related to Riemann's prime number formula](https://www.ams.org/journals/mcom/1970-24-112/S0025-5718-1970-0277489-3/S0025-5718-1970-0277489-3.pdf). or Zagier, Don (1977). *The first 50 million prime numbers*. *Math. Intelligencer* **1**, 7–19. [MR643810](https://mathscinet.ams.org/mathscinet-getitem?mr=MR643810). doi:[10.1007/BF03039306](https://doi.org/10.1007/BF03039306). [The first 50 million prime numbers](https://web.archive.org/web/20090327181245/http://modular.math.washington.edu/edu/2007/simuw07/misc/zagier-the_first_50_million_prime_numbers.pdf)..

This formula says that the zeros of the Riemann zeta function control the [oscillation](https://en.wikipedia.org/wiki/oscillation)s of primes around their "expected" positions. Riemann knew that the non-trivial zeros of the zeta function were symmetrically distributed about the line $s = 1/2 + it$, and he knew that all of its non-trivial zeros must lie in the range $0\leq \operatorname{Re}(s)\leq 1$. He checked that a few of the zeros lay on the critical line with real part $1/2$ and suggested that they all do; this is the Riemann hypothesis.

> The result has caught the imagination of most mathematicians because it is so unexpected, connecting two seemingly unrelated areas in mathematics; namely, [number theory](https://en.wikipedia.org/wiki/number_theory), which is the study of the discrete, and [complex analysis](https://en.wikipedia.org/wiki/complex_analysis), which deals with continuous processes.

## Consequences

The practical uses of the Riemann hypothesis include many propositions known to be true under the Riemann hypothesis, and some that can be shown to be equivalent to the Riemann hypothesis.

### Distribution of prime numbers

[Riemann's explicit formula](https://en.wikipedia.org/wiki/Riemann%27s_explicit_formula) for [the number of primes less than a given number](https://en.wikipedia.org/wiki/prime-counting_function) states that, in terms of a sum over the zeros of the Riemann zeta function, the magnitude of the oscillations of primes around their expected position is controlled by the real parts of the zeros of the zeta function. In particular, the error term in the [prime number theorem](https://en.wikipedia.org/wiki/prime_number_theorem) is closely related to the position of the zeros. For example, if $\beta$ is the [upper bound](https://en.wikipedia.org/wiki/upper_bound) of the real parts of the zeros, then[^5]
$\pi(x) - \operatorname{li}(x) = O\!\left( x^\beta \log x \right)$, where $\pi(x)$ is the [prime-counting function](https://en.wikipedia.org/wiki/prime-counting_function) and $\operatorname{li}(x)$ is the [logarithmic integral function](https://en.wikipedia.org/wiki/logarithmic_integral_function).
It is already known that $1/2\leq\beta\leq 1$. Ingham, A.E. (1932). *The Distribution of Prime Numbers*. *Cambridge University Press* **30**, 82.
<figure style={{"maxWidth": "308px"}}>

![Corrections to an estimate of the prime-counting function using zeros of the zeta function. The magnitude of the correction term is determined by the real part of the zero being added in the correction.](https://pub-275e30003c354ac0862cc9839e0f952a.r2.dev/docs/math/Riemann_Explicit_Formula.gif)

<figcaption>

Corrections to an [estimate](https://en.wikipedia.org/wiki/Prime-counting_function#Exact_form) of the prime-counting function using zeros of the zeta function. The magnitude of the correction term is determined by the real part of the zero being added in the correction.

</figcaption>

</figure>
[Helge von Koch](https://en.wikipedia.org/wiki/Helge_von_Koch) proved that the Riemann hypothesis implies the "best possible" bound for the error of the prime number theorem.[^6] A precise version of von Koch's result, due to Schoenfeld, Lowell (1976). *Sharper bounds for the Chebyshev functions θ(x) and ψ(x). II*. *Mathematics of Computation* **30**(134), 337–360. [MR0457374](https://mathscinet.ams.org/mathscinet-getitem?mr=MR0457374). [JSTOR 2005976](https://www.jstor.org/stable/2005976). doi:[10.2307/2005976](https://doi.org/10.2307/2005976)., says that the Riemann hypothesis implies

:

$$
|\pi(x) - \operatorname{li}(x)| < \frac{1}{8\pi} \sqrt{x} \log(x)
$$

for all $x\geq 2657$. Schoenfeld, Lowell (1976). *Sharper bounds for the Chebyshev functions θ(x) and ψ(x). II*. *Mathematics of Computation* **30**(134), 337–360. [MR0457374](https://mathscinet.ams.org/mathscinet-getitem?mr=MR0457374). [JSTOR 2005976](https://www.jstor.org/stable/2005976). doi:[10.2307/2005976](https://doi.org/10.2307/2005976). also showed that the Riemann hypothesis implies

$$
|\psi(x) - x| < \frac{1}{8\pi} \sqrt{x} \log^2 x
$$

for all $x\geq 73.2$, where $\psi(x)$ is [Chebyshev's second function](https://en.wikipedia.org/wiki/Chebyshev_function).

Adrian Dudek[^7] proved that the Riemann hypothesis implies that for $x \geq 2$, there is a prime $p$ satisfying
  $x - \frac{4}{\pi} \sqrt x \log x < p \leq x$.
The constant $4/\pi$ may be reduced to $1+\varepsilon$ provided that $x$ is taken to be sufficiently large. This is an explicit version of a theorem of [Cramér](https://en.wikipedia.org/wiki/Cram%C3%A9r).

### Growth of arithmetic functions

The Riemann hypothesis implies strong bounds on the growth of many other [arithmetic function](https://en.wikipedia.org/wiki/arithmetic_function)s, in addition to the primes counting function above.

One example involves the [Möbius function](https://en.wikipedia.org/wiki/M%C3%B6bius_function) *μ*. The statement that the equation

$$
\frac{1}{\zeta(s)} = \sum_{n=1}^\infty \frac{\mu(n)}{n^s}
$$

is valid for every *s* with real part greater than 1/2, with the sum on the right hand side converging, is equivalent to the Riemann hypothesis. From this we can also conclude that if the [Mertens function](https://en.wikipedia.org/wiki/Mertens_function) is defined by

$$
M(x) = \sum_{n \le x} \mu(n)
$$

then the claim that

$$
M(x) = O\left(x^{\frac{1}{2}+\varepsilon}\right)
$$

for every positive *ε* is equivalent to the Riemann hypothesis ([J. E. Littlewood](https://en.wikipedia.org/wiki/John_Edensor_Littlewood), 1912; see for instance: paragraph 14.25 in Titchmarsh, Edward Charles (1986). *The theory of the Riemann zeta-function*. *The Clarendon Press Oxford University Press*. ISBN 978-0-19-853369-6. [MR882550](https://mathscinet.ams.org/mathscinet-getitem?mr=MR882550).). The [determinant](https://en.wikipedia.org/wiki/determinant) of the order *n* [Redheffer matrix](https://en.wikipedia.org/wiki/Redheffer_matrix) is equal to *M*(*n*), so the Riemann hypothesis can also be stated as a condition on the growth of these determinants. Littlewood's result has been improved several times since then, by [Edmund Landau](https://en.wikipedia.org/wiki/Edmund_Landau),[^8] [Edward Charles Titchmarsh](https://en.wikipedia.org/wiki/Edward_Charles_Titchmarsh),[^9] Helmut Maier and [Hugh Montgomery](https://en.wikipedia.org/wiki/Hugh_Lowell_Montgomery),[^10] and [Kannan Soundararajan](https://en.wikipedia.org/wiki/Kannan_Soundararajan).[^11] Soundararajan's result is that, conditional on the Riemann hypothesis,

$$
M(x) = O\left(x^{1/2}\exp\left((\log x)^{1/2}(\log \log x)^{14}\right)\right).
$$

The Riemann hypothesis puts a rather tight bound on the growth of *M*, since Odlyzko, A. M.; te Riele, H. J. J. (1985). *Disproof of the Mertens conjecture*. *Journal für die reine und angewandte Mathematik* **1985**(357), 138–160. [MR783538](https://mathscinet.ams.org/mathscinet-getitem?mr=MR783538). doi:[10.1515/crll.1985.357.138](https://doi.org/10.1515/crll.1985.357.138). [Disproof of the Mertens conjecture](https://archive.today/20120711011237/http://gdz.sub.uni-goettingen.de/no_cache/dms/load/img/?IDDOC=262633). disproved the slightly stronger [Mertens conjecture](https://en.wikipedia.org/wiki/Mertens_conjecture)

$$
|M(x)| \le \sqrt x.
$$

Another closely related result is due to Björner, Anders (2011). *A cell complex in number theory*. *Advances in Applied Mathematics* **46**(1–4), 71–85. [arXiv:1101.5704](https://arxiv.org/abs/1101.5704). doi:[10.1016/j.aam.2010.09.007](https://doi.org/10.1016/j.aam.2010.09.007)., that the Riemann hypothesis is equivalent to the statement that the [Euler characteristic](https://en.wikipedia.org/wiki/Euler_characteristic) of the [simplicial complex](https://en.wikipedia.org/wiki/simplicial_complex) determined by the lattice of integers under divisibility is $o(n^{1/2+\epsilon})$ for all $\epsilon>0$ (see [incidence algebra](https://en.wikipedia.org/wiki/incidence_algebra)).

The Riemann hypothesis is equivalent to many other conjectures about the rate of growth of other arithmetic functions aside from *μ*(*n*). A typical example is [Robin's theorem](https://en.wikipedia.org/wiki/Robin%27s_theorem), Robin, G. (1984). *Grandes valeurs de la fonction somme des diviseurs et hypothèse de Riemann*. *Journal de Mathématiques Pures et Appliquées* **63**(2), 187–213. [MR774171](https://mathscinet.ams.org/mathscinet-getitem?mr=MR774171). which states that if *σ*(*n*) is the [sigma function](https://en.wikipedia.org/wiki/divisor_function), given by

$$
\sigma(n) = \sum_{d\mid n} d
$$

then

$$
\sigma(n) < e^\gamma n \log \log n
$$

for all *n* > 5040 [if and only if](https://en.wikipedia.org/wiki/if_and_only_if) the Riemann hypothesis is true, where *γ* is the [Euler–Mascheroni constant](https://en.wikipedia.org/wiki/Euler%E2%80%93Mascheroni_constant).

A related bound was given by [Jeffrey Lagarias](https://en.wikipedia.org/wiki/Jeffrey_Lagarias) in 2002, who proved that the Riemann hypothesis is equivalent to the statement that:

$$
\sigma(n) < H_n + \log(H_n)e^{H_n}
$$

for every [natural number](https://en.wikipedia.org/wiki/natural_number) *n* > 1, where $H_n$ is the *n*th [harmonic number](https://en.wikipedia.org/wiki/harmonic_number).[^12]

The Riemann hypothesis is also true if and only if the inequality

$$
\frac{n}{\varphi (n)}<e^\gamma \log\log n+\frac{e^\gamma (4+\gamma-\log 4\pi)}{\sqrt{\log n}}
$$

is true for all *n* ≥ 120569#, where *φ*(*n*) is [Euler's totient function](https://en.wikipedia.org/wiki/Euler%27s_totient_function) and 120569# is the [product of the first](https://en.wikipedia.org/wiki/Primorial) 120569 primes. Broughan, Kevin (2017). *Equivalents of the Riemann Hypothesis*. *Cambridge University Press*. ISBN 978-1108290784, Corollary 5.35.

Another example was found by [Jérôme Franel](https://en.wikipedia.org/wiki/J%C3%A9r%C3%B4me_Franel), and extended by [Landau](https://en.wikipedia.org/wiki/Edmund_Landau) (see Franel, J.; Landau, E. (1924). *Les suites de Farey et le problème des nombres premiers" (Franel, 198–201); "Bemerkungen zu der vorstehenden Abhandlung von Herrn Franel (Landau, 202–206)*. *Göttinger Nachrichten*, 198–206.). The Riemann hypothesis is equivalent to several statements showing that the terms of the [Farey sequence](https://en.wikipedia.org/wiki/Farey_sequence) are fairly regular. One such equivalence is as follows: if *F*<sub>*n*</sub> is the Farey sequence of order *n*, beginning with 1/*n* and up to 1/1, then the claim that for all *ε* > 0

$$
\sum_{i=1}^m|F_n(i) - \tfrac{i}{m}| = O\left(n^{\frac{1}{2}+\epsilon}\right)
$$

is equivalent to the Riemann hypothesis. Here

$$
m = \sum_{i=1}^n\varphi(i)
$$

is the number of terms in the Farey sequence of order *n*.

For an example from [group theory](https://en.wikipedia.org/wiki/group_theory), if *g*(*n*) is [Landau's function](https://en.wikipedia.org/wiki/Landau%27s_function) given by the maximal order of elements of the [symmetric group](https://en.wikipedia.org/wiki/symmetric_group) S<sub>*n*</sub> of degree *n*, then Massias, J.-P.; Nicolas, Jean-Louis; Robin, G. (1988). *Évaluation asymptotique de l'ordre maximum d'un élément du groupe symétrique*. *Acta Arithmetica* **50**(3), 221–242. [MR960551](https://mathscinet.ams.org/mathscinet-getitem?mr=MR960551). doi:[10.4064/aa-50-3-221-242](https://doi.org/10.4064/aa-50-3-221-242). [Évaluation asymptotique de l'ordre maximum d'un élément du groupe symétrique](http://matwbn.icm.edu.pl/tresc.php?wyd=6&tom=50&jez=). showed that the Riemann hypothesis is equivalent to the bound

$$
\log g(n) < \sqrt{\operatorname{Li}^{-1}(n)}
$$

for all sufficiently large *n*.

### Lindelöf hypothesis and growth of the zeta function

The Riemann hypothesis has various weaker consequences as well; one is the [Lindelöf hypothesis](https://en.wikipedia.org/wiki/Lindel%C3%B6f_hypothesis) on the rate of growth of the zeta function on the critical line, which says that, for any *ε* > 0,

$$
\zeta\left(\frac{1}{2} + it\right) = O(t^\varepsilon),
$$

as *t* → $\infty$.

The Riemann hypothesis also implies quite sharp bounds for the growth rate of the zeta function in other regions of the critical strip. For example, it implies that

$$
e^\gamma\le \limsup_{t\rightarrow +\infty}\frac{|\zeta(1+it)|}{\log\log t}\le 2e^\gamma
$$

$$
\frac{6}{\pi^2}e^\gamma\le \limsup_{t\rightarrow +\infty}\frac{1/|\zeta(1+it)|}{\log\log t}\le \frac{12}{\pi^2}e^\gamma
$$

so the growth rate of *ζ*(1 + *it*) and its inverse would be known up to a factor of 2. Titchmarsh, Edward Charles (1986). *The theory of the Riemann zeta-function*. *The Clarendon Press Oxford University Press*. ISBN 978-0-19-853369-6. [MR882550](https://mathscinet.ams.org/mathscinet-getitem?mr=MR882550).

### Large prime gap conjecture

The prime number theorem implies that on average, the [gap](https://en.wikipedia.org/wiki/prime_gap) between the prime *p* and its successor is log *p*. However, some gaps between primes may be much larger than the average. Cramér proved that, assuming the Riemann hypothesis, every gap is *O*( $\sqrt{*p*}$ log *p*). This is a case in which even the best bound that can be proved using the Riemann hypothesis is far weaker than what seems true: [Cramér's conjecture](https://en.wikipedia.org/wiki/Cram%C3%A9r%27s_conjecture) implies that every gap is *O*((log *p*)<sup>2</sup>), which, while larger than the average gap, is far smaller than the bound implied by the Riemann hypothesis. Numerical evidence supports Cramér's conjecture. Nicely, Thomas R. (1999). *New maximal prime gaps and first occurrences*. *Mathematics of Computation* **68**(227), 1311–1315. [MR1627813](https://mathscinet.ams.org/mathscinet-getitem?mr=MR1627813). [1999MaCom..68.1311N](https://ui.adsabs.harvard.edu/abs/1999MaCom..68.1311N). doi:[10.1090/S0025-5718-99-01065-0](https://doi.org/10.1090/S0025-5718-99-01065-0). [New maximal prime gaps and first occurrences](http://www.trnicely.net/gaps/gaps.html).

### Analytic criteria equivalent to the Riemann hypothesis

Many statements equivalent to the Riemann hypothesis have been found, though so far none of them have led to much progress in proving (or disproving) it. Some typical examples are as follows. (Others involve the [divisor function](https://en.wikipedia.org/wiki/Divisor_function#Growth_rate) *σ*(*n*).)

The [Riesz criterion](https://en.wikipedia.org/wiki/Riesz_criterion) was given by Riesz, M. (1916). *Sur l'hypothèse de Riemann*. *Acta Mathematica* **40**, 185–190. doi:[10.1007/BF02418544](https://doi.org/10.1007/BF02418544)., to the effect that the bound

$$
-\sum_{k=1}^\infty \frac{(-x)^k}{(k-1)! \zeta(2k)}= O\left(x^{\frac{1}{4}+\epsilon}\right)
$$

holds for all ε > 0 if and only if the Riemann hypothesis holds. See also the [Hardy–Littlewood criterion](https://en.wikipedia.org/wiki/Riesz_function#Hardy%E2%80%93Littlewood_criterion).

Nyman, Bertil (1950). *On the One-Dimensional Translation Group and Semi-Group in Certain Function Spaces*. *University of Uppsala*. [MR0036444](https://mathscinet.ams.org/mathscinet-getitem?mr=MR0036444). proved that the Riemann hypothesis is true if and only if the space of functions of the form

$$
f(x) = \sum_{\nu=1}^nc_\nu\rho \left(\frac{\theta_\nu}{x} \right)
$$

where *ρ*(*z*) is the fractional part of *z*, 0 ≤ *θ*<sub>*ν*</sub> ≤ 1, and

$$
\sum_{\nu=1}^nc_\nu\theta_\nu=0,
$$

is dense in the [Hilbert space *L*<sup>2</sup>(0,1)](https://en.wikipedia.org/wiki/Lp_space) of square-integrable functions on the unit interval. Beurling, Arne (1955). *A closure problem related to the Riemann zeta-function*. *Proceedings of the National Academy of Sciences of the United States of America* **41**(5), 312–314. [MR0070655](https://mathscinet.ams.org/mathscinet-getitem?mr=MR0070655). [1955PNAS...41..312B](https://ui.adsabs.harvard.edu/abs/1955PNAS...41..312B). [PMID 16589670](https://pubmed.ncbi.nlm.nih.gov/16589670/). [528084](https://www.ncbi.nlm.nih.gov/pmc/articles/528084/). doi:[10.1073/pnas.41.5.312](https://doi.org/10.1073/pnas.41.5.312). extended this by showing that the zeta function has no zeros with real part greater than 1/*p* if and only if this function space is dense in *L<sup>p</sup>*(0,1). This Nyman-Beurling criterion was strengthened by Baez-Duarte[^13] to the case where $\theta_\nu \in \{1/k\}_{k\geq 1}$.

Salem, Raphaël (1953). *Sur une proposition équivalente à l'hypothèse de Riemann*. *Les Comptes rendus de l'Académie des sciences* **236**, 1127–1128. [MR0053148](https://mathscinet.ams.org/mathscinet-getitem?mr=MR0053148). showed that the Riemann hypothesis is true if and only if the [integral equation](https://en.wikipedia.org/wiki/integral_equation)

$$
\int_0^\infty\frac{z^{-\sigma-1}\varphi(z)}{{e^{x/z}}+1}\,dz=0
$$

has no non-trivial bounded solutions $\varphi$ for $1/2<\sigma <1$.

[Weil's criterion](https://en.wikipedia.org/wiki/Weil%27s_criterion) is the statement that the positivity of a certain function is equivalent to the Riemann hypothesis. Related is [Li's criterion](https://en.wikipedia.org/wiki/Li%27s_criterion), a statement that the positivity of a certain sequence of numbers is equivalent to the Riemann hypothesis.

Speiser, Andreas (1934). *Geometrisches zur Riemannschen Zetafunktion*. *Mathematische Annalen* **110**, 514–521. doi:[10.1007/BF01448042](https://doi.org/10.1007/BF01448042). [Geometrisches zur Riemannschen Zetafunktion](https://web.archive.org/web/20150627115412/http://gdz.sub.uni-goettingen.de/index.php?id=11&PPN=PPN235181684_0110&DMDID=DMDLOG_0032&L=1). proved that the Riemann hypothesis is equivalent to the statement that *ζ*′(*s*), the derivative of *ζ*(*s*), has no zeros in the strip

$$
0 < \Re(s) < \frac12.
$$

That *ζ*(*s*) has only simple zeros on the critical line is equivalent to its derivative having no zeros on the critical line.

The [Farey sequence](https://en.wikipedia.org/wiki/Farey_sequence#Riemann_hypothesis) provides two equivalences, due to [Jerome Franel](https://en.wikipedia.org/wiki/Jerome_Franel) and [Edmund Landau](https://en.wikipedia.org/wiki/Edmund_Landau) in 1924.

The [de Bruijn–Newman constant](https://en.wikipedia.org/wiki/de_Bruijn%E2%80%93Newman_constant) denoted by Λ and named after [Nicolaas Govert de Bruijn](https://en.wikipedia.org/wiki/Nicolaas_Govert_de_Bruijn) and [Charles M. Newman](https://en.wikipedia.org/wiki/Charles_M._Newman), is defined
as the unique real number such that the [function](https://en.wikipedia.org/wiki/Function_%28mathematics%29)
  $H(\lambda, z):=\int_{0}^{\infty} e^{\lambda u^{2}} \Phi(u) \cos (z u)\, d u$,
that is parametrised by a real parameter *λ*, has a complex variable *z* and is defined using a super-exponentially decaying function
  $\Phi(u) = \sum_{n=1}^{\infty} (2\pi^2n^4e^{9u} - 3 \pi n^2 e^{5u} ) e^{-\pi n^2 e^{4u}}$,
has only real zeros if and only if *λ* ≥ Λ.
Since the Riemann hypothesis is equivalent to the claim that all the zeros of *H*(0, *z*) are real, the Riemann hypothesis is equivalent to the conjecture that Λ ≤ 0. Brad Rodgers and [Terence Tao](https://en.wikipedia.org/wiki/Terence_Tao) discovered the equivalence is actually Λ = 0 by proving zero to be the lower bound of the constant. Rodgers, Brad; Tao, Terence (2020). *The de Bruijn–Newman constant is non-negative*. *Forum of Mathematics* **8**, e6, 62. [MR4089393](https://mathscinet.ams.org/mathscinet-getitem?mr=MR4089393). [arXiv:1801.05914](https://arxiv.org/abs/1801.05914). doi:[10.1017/fmp.2020.6](https://doi.org/10.1017/fmp.2020.6). Proving zero is also the upper bound would therefore prove the Riemann hypothesis. Newman noted that this conjecture (now theorem) "is a quantitative version of the dictum that the Riemann hypothesis, if true, is only barely so." Newman, C. M. (1976). *Fourier transforms with only real zeroes*. *Proceedings of the American Mathematical Society* **61**(2), 246–251. doi:[10.1090/S0002-9939-1976-0434982-5](https://doi.org/10.1090/S0002-9939-1976-0434982-5). As of April 2020 the upper bound is Λ ≤ 0.2. [(Platt & Trudgian 2021)](https://en.wikipedia.org/wiki/Riemann_hypothesis#CITEREFPlattTrudgian2021)

### Consequences of the generalized Riemann hypothesis

Several applications use the [generalized Riemann hypothesis](https://en.wikipedia.org/wiki/generalized_Riemann_hypothesis) for [Dirichlet L-series](https://en.wikipedia.org/wiki/Dirichlet_L-series) or [zeta functions of number fields](https://en.wikipedia.org/wiki/Dedekind_zeta_function) rather than just the Riemann hypothesis. Many basic properties of the Riemann zeta function can easily be generalized to all Dirichlet L-series, so it is plausible that a method that proves the Riemann hypothesis for the Riemann zeta function would also work for the generalized Riemann hypothesis for Dirichlet L-functions. Several results first proved using the generalized Riemann hypothesis were later given unconditional proofs without using it, though these were usually much harder. Many of the consequences on the following list are taken from Conrad, K. (2010). *Consequences of the Riemann hypothesis*. [Consequences of the Riemann hypothesis](https://mathoverflow.net/q/17232)..
* In 1913, [Grönwall](https://en.wikipedia.org/wiki/Thomas_Hakon_Gr%C3%B6nwall) showed that the generalized Riemann hypothesis implies that Gauss's [list of imaginary quadratic fields with class number 1](https://en.wikipedia.org/wiki/class_number_problem) is complete, though Baker, Stark and Heegner later gave unconditional proofs of this without using the generalized Riemann hypothesis.
* In 1917, Hardy and Littlewood showed that the generalized Riemann hypothesis implies a conjecture of Chebyshev that

$$
\lim_{x\to 1^-} \sum_{p>2}(-1)^{(p+1)/2} x^p=+\infty,
$$

 which says that primes 3 mod 4 are more common than primes 1 mod 4 in some sense. (For related results, see *[Prime number race](https://en.wikipedia.org/wiki/Prime_number_theorem#Prime_number_race)*.)
* In 1923, Hardy and Littlewood showed that the generalized Riemann hypothesis implies a weak form of the [Goldbach conjecture](https://en.wikipedia.org/wiki/Goldbach_conjecture) for odd numbers: that every sufficiently large odd number is the sum of three primes, though in 1937 Vinogradov gave an unconditional proof. In 1997 [Deshouillers](https://en.wikipedia.org/wiki/Jean-Marc_Deshouillers), Effinger, [te Riele](https://en.wikipedia.org/wiki/Herman_te_Riele), and Zinoviev showed that the generalized Riemann hypothesis implies that every odd number greater than 5 is the sum of three primes. In 2013 [Harald Helfgott](https://en.wikipedia.org/wiki/Harald_Helfgott) proved the ternary Goldbach conjecture without the GRH dependence, subject to some extensive calculations completed with the help of David J. Platt.
* In 1934, Chowla showed that the generalized Riemann hypothesis implies that the first prime in the arithmetic progression *a* mod *m* is at most *Km*<sup>2</sup>log(*m*)<sup>2</sup> for some fixed constant *K*.
* In 1967, Hooley showed that the generalized Riemann hypothesis implies [Artin's conjecture on primitive roots](https://en.wikipedia.org/wiki/Artin%27s_conjecture_on_primitive_roots).
* In 1973, Weinberger showed that the generalized Riemann hypothesis implies that Euler's list of [idoneal number](https://en.wikipedia.org/wiki/idoneal_number)s is complete.
* Weinberger, Peter J. (1973). *Analytic number theory ( St. Louis Univ., 1972)*. *Amer. Math. Soc.* **24**, 321–332. [MR0337902](https://mathscinet.ams.org/mathscinet-getitem?mr=MR0337902). showed that the generalized Riemann hypothesis for the zeta functions of all algebraic number fields implies that any number field with class number 1 is either [Euclidean](https://en.wikipedia.org/wiki/Euclidean_domain) or an imaginary quadratic number field of [discriminant](https://en.wikipedia.org/wiki/discriminant_of_an_algebraic_number_field) −19, −43, −67, or −163.
* In 1976, G. Miller showed that the generalized Riemann hypothesis implies that one can [test if a number is prime](https://en.wikipedia.org/wiki/primality_test) in polynomial time via the [Miller test](https://en.wikipedia.org/wiki/Miller%E2%80%93Rabin_primality_test). In 2002, Manindra Agrawal, Neeraj Kayal and Nitin Saxena proved this result unconditionally using the [AKS primality test](https://en.wikipedia.org/wiki/AKS_primality_test).
* Odlyzko, A. M. (1990). *Bounds for discriminants and related estimates for class numbers, regulators and zeros of zeta functions: a survey of recent results*. *Séminaire de Théorie des Nombres de Bordeaux* **2**(1), 119–141. [MR1061762](https://mathscinet.ams.org/mathscinet-getitem?mr=MR1061762). doi:[10.5802/jtnb.22](https://doi.org/10.5802/jtnb.22). [Bounds for discriminants and related estimates for class numbers, regulators and zeros of zeta functions: a survey of recent results](http://www.numdam.org/item?id=JTNB_1990__2_1_119_0). discussed how the generalized Riemann hypothesis can be used to give sharper estimates for discriminants and class numbers of number fields.
* Ono, Ken; Soundararajan, K. (1997). *Ramanujan's ternary quadratic form*. *Inventiones Mathematicae* **130**(3), 415–454. [1997InMat.130..415O](https://ui.adsabs.harvard.edu/abs/1997InMat.130..415O). doi:[10.1007/s002220050191](https://doi.org/10.1007/s002220050191). showed that the generalized Riemann hypothesis implies that [Ramanujan's integral quadratic form](https://en.wikipedia.org/wiki/Ramanujan%27s_ternary_quadratic_form) *x*<sup>2</sup> + *y*<sup>2</sup> + 10*z*<sup>2</sup> represents all integers that it represents locally, with exactly 18 exceptions.
* In 2021, Alexander (Alex) Dunn and [Maksym Radziwill](https://en.wikipedia.org/wiki/Maksym_Radziwill) proved [Patterson's conjecture](https://en.wikipedia.org/wiki/Patterson%27s_conjecture) on cubic [Gauss sums](https://en.wikipedia.org/wiki/Gauss_sums), under the assumption of the GRH.[^14] [^15]

### Excluded middle

Some consequences of the RH are also consequences of its negation, and are thus theorems. In their discussion of the [Hecke, Deuring, Mordell, Heilbronn theorem](./riemann_hypothesis.md#gausss-class-number-conjecture), Ireland, Kenneth; Rosen, Michael (1990). *A Classical Introduction to Modern Number Theory (Second edition)*. *Springer*. ISBN 0-387-97329-X, 359. say

> The method of proof here is truly amazing. If the generalized Riemann hypothesis is true, then the theorem is true. If the generalized Riemann hypothesis is false, then the theorem is true. Thus, the theorem is true!!

Care should be taken to understand what is meant by saying the generalized Riemann hypothesis is false: one should specify exactly which class of Dirichlet series has a counterexample.

#### Littlewood's theorem

This concerns the sign of the error in the [prime number theorem](https://en.wikipedia.org/wiki/prime_number_theorem).
It has been computed that $\pi$(*x*) \< li(*x*) for all *x* ≤ 10<sup>25</sup> (see this [table](https://en.wikipedia.org/wiki/Prime_number_theorem#Table_of_%CF%80%28x%29%2C_x_/_log_x%2C_and_li%28x%29)), and no value of *x* is known for which $\pi$(*x*) > li(*x*).

In 1914, Littlewood proved that there are arbitrarily large values of *x* for which

$$
\pi(x)>\operatorname{li}(x) +\frac13\frac{\sqrt x}{\log x}\log\log\log x,
$$

and that there are also arbitrarily large values of *x* for which

$$
\pi(x)<\operatorname{li}(x) -\frac13\frac{\sqrt x}{\log x}\log\log\log x.
$$

Thus the difference $\pi$(*x*) − li(*x*) changes sign infinitely many times. [Skewes' number](https://en.wikipedia.org/wiki/Skewes%27_number) is an estimate of the value of *x* corresponding to the first sign change.

Littlewood's proof is divided into two cases: the RH is assumed false (about half a page of Ingham, A.E. (1932). *The Distribution of Prime Numbers*. *Cambridge University Press* **30**, Chapt. V.), and the RH is assumed true (about a dozen pages). Stanisław Knapowski followed this up with a paper on the number of times $\Delta(n)$ changes sign in the interval $\Delta(n)$.[^16]

#### Gauss's class number conjecture

This is the [conjecture](https://en.wikipedia.org/wiki/Class_number_problem) (first stated in article 303 of Gauss's *[Disquisitiones Arithmeticae](https://en.wikipedia.org/wiki/Disquisitiones_Arithmeticae)*) that there are only finitely many imaginary quadratic fields with a given class number. One way to prove it would be to show that as the discriminant $D → −∞$ the class number $h(D) → ∞$.

The following sequence of theorems involving the Riemann hypothesis is described in Ireland, Kenneth; Rosen, Michael (1990). *A Classical Introduction to Modern Number Theory (Second edition)*. *Springer*. ISBN 0-387-97329-X, 358–361.:
**Theorem (Hecke; 1918).** Let $D < 0$ be the discriminant of an imaginary [quadratic](https://en.wikipedia.org/wiki/quadratic_irrational_number) [number field](https://en.wikipedia.org/wiki/number_field) *K*. Assume the generalized Riemann hypothesis for [*L*-functions](https://en.wikipedia.org/wiki/L-function) of all imaginary quadratic Dirichlet characters. Then there is an absolute constant *C* such that

$$
h(D) > C\frac{\sqrt{|D|}}{\log |D|}.
$$

**Theorem (Deuring; 1933).** If the RH is false then $h(D) > 1$ if $|D|$ is sufficiently large.
**Theorem (Mordell; 1934).** If the RH is false then $h(D) → ∞$ as $D → −∞$.
**Theorem (Heilbronn; 1934).** If the generalized RH is false for the *L*-function of some imaginary quadratic Dirichlet character then $h(D) → ∞$ as $D → −∞$.

(In the work of Hecke and Heilbronn, the only [*L*-functions](https://en.wikipedia.org/wiki/L-function) that occur are those attached to imaginary quadratic characters, and it is only for those *L*-functions that *GRH is true* or *GRH is false* is intended; a failure of GRH for the *L*-function of a cubic Dirichlet character would, strictly speaking, mean GRH is false, but that was not the kind of failure of GRH that Heilbronn had in mind, so his assumption was more restricted than simply *GRH is false*.)

In 1935, [Carl Siegel](https://en.wikipedia.org/wiki/Carl_Siegel) strengthened the result without using RH or GRH in any way.[^17] [^18]

#### Growth of Euler's totient

In 1983 [J. L. Nicolas](https://en.wikipedia.org/wiki/Jean-Louis_Nicolas) proved that

$$
\varphi(n) < e^{-\gamma}\frac  {n} {\log \log n}
$$

for infinitely many *n*, where *φ*(*n*) is [Euler's totient function](https://en.wikipedia.org/wiki/Euler%27s_totient_function) and *γ* is [Euler's constant](https://en.wikipedia.org/wiki/Euler%27s_constant). Ribenboim remarks that: "The method of proof is interesting, in that the inequality is shown first under the assumption that the Riemann hypothesis is true, secondly under the contrary assumption." Ribenboim, Paulo (1996). *The New Book of Prime Number Records*. *Springer*. ISBN 0-387-94457-5, 320.

## Generalizations and analogs

### Dirichlet L-series and other number fields

The Riemann hypothesis can be generalized by replacing the Riemann zeta function by the formally similar, but much more general, global [L-function](https://en.wikipedia.org/wiki/L-function)s. In this broader setting, one expects the non-trivial zeros of the global *L*-functions to have real part 1/2. It is these conjectures, rather than the classical Riemann hypothesis only for the single Riemann zeta function, which account for the true importance of the Riemann hypothesis in mathematics.

The most common [generalized Riemann hypothesis](https://en.wikipedia.org/wiki/generalized_Riemann_hypothesis) extends the Riemann hypothesis to all [Dirichlet L-function](https://en.wikipedia.org/wiki/Dirichlet_L-function)s. In particular it implies the conjecture that [Siegel zero](./siegel_zero.md)s (zeros of *L*-functions between 1/2 and 1) do not exist.

The [extended Riemann hypothesis](https://en.wikipedia.org/wiki/extended_Riemann_hypothesis) extends the Riemann hypothesis to all [Dedekind zeta function](https://en.wikipedia.org/wiki/Dedekind_zeta_function)s of [algebraic number field](https://en.wikipedia.org/wiki/algebraic_number_field)s. Since Dedekind zeta function for abelian extension of the rationals can be expressed as product of Dirichlet L-functions and only possible pole is in 1 for Riemann zeta function (thus no pole can cancel nontrivial zero), this version of Riemann hypothesis implies generalized Riemann hypothesis.

The Riemann hypothesis can also be extended to the *L*-functions of [Hecke character](https://en.wikipedia.org/wiki/Hecke_character)s of number fields. Since Dirichlet L-functions are Hecke L-functions for finite characters, then this hypothesis directly implies generalized Riemann hypothesis. Dedekind zeta functions can be expressed as product of Hecke L-functions and only possible pole of Hecke L-function is at 1, then this version of Riemann Hypothesis implies also version for Dedekind zeta functions.

There are two approaches for extension of Riemann hypothesis that seem to be the most general. The [grand Riemann hypothesis](https://en.wikipedia.org/wiki/grand_Riemann_hypothesis) extends it to all [Automorphic L-function](https://en.wikipedia.org/wiki/Automorphic_L-function)s, such as [Mellin transform](https://en.wikipedia.org/wiki/Mellin_transform)s of [Hecke eigenform](https://en.wikipedia.org/wiki/Hecke_eigenform)s. The Riemann hypothesis for [Selberg class](https://en.wikipedia.org/wiki/Selberg_class) extends it rather for functions satisfying some properties (at least conjecturaly satisfied by most functions usually called *zeta functions* or *L-functions*) than for functions defined by direct formula. Though it is expected that Selberg class should be equal to class of automorphic L-functions, and thus this approaches should be equivalent, this is important open problem itself and part of [Langlands program](https://en.wikipedia.org/wiki/Langlands_program).

### Function fields and zeta functions of varieties over finite fields

Artin, Emil (1924). *Quadratische Körper im Gebiete der höheren Kongruenzen. II. Analytischer Teil*. *Mathematische Zeitschrift* **19**(1), 207–246. doi:[10.1007/BF01181075](https://doi.org/10.1007/BF01181075). introduced global zeta functions of (quadratic) [function fields](https://en.wikipedia.org/wiki/Function_field_of_an_algebraic_variety) and conjectured an analogue of the Riemann hypothesis for them, which has been proved by Hasse in the genus 1 case and by Weil, André (1948). *Sur les courbes algébriques et les variétés qui s'en déduisent*. *Hermann et Cie., Paris*. [MR0027151](https://mathscinet.ams.org/mathscinet-getitem?mr=MR0027151). in general. For instance, the fact that the [Gauss sum](https://en.wikipedia.org/wiki/quadratic_Gauss_sum), of the quadratic character of a [finite field](https://en.wikipedia.org/wiki/finite_field) of size *q* (with *q* odd), has absolute value $\sqrt{q}$ is actually an instance of the Riemann hypothesis in the function field setting. This led Weil, André (1949). *Numbers of solutions of equations in finite fields*. *Bulletin of the American Mathematical Society* **55**(5), 497–508. [MR0029393](https://mathscinet.ams.org/mathscinet-getitem?mr=MR0029393). doi:[10.1090/S0002-9904-1949-09219-4](https://doi.org/10.1090/S0002-9904-1949-09219-4). to conjecture a similar statement for all [algebraic varieties](https://en.wikipedia.org/wiki/algebraic_variety); the resulting [Weil conjectures](https://en.wikipedia.org/wiki/Weil_conjectures) were proved by [Pierre Deligne](https://en.wikipedia.org/wiki/Pierre_Deligne).[^19]

### Arithmetic zeta functions of arithmetic schemes and their L-factors

[Arithmetic zeta function](https://en.wikipedia.org/wiki/Arithmetic_zeta_function)s generalise the Riemann and Dedekind zeta functions as well as the zeta functions of varieties over finite fields to every arithmetic scheme or a scheme of finite type over integers. The arithmetic zeta function of a regular connected [equidimensional](https://en.wikipedia.org/wiki/equidimensionality) arithmetic scheme of Kronecker dimension *n* can be factorized into the product of appropriately defined L-factors and an auxiliary factor.[^20] Assuming a functional equation and meromorphic continuation, the generalized Riemann hypothesis for the L-factor states that its zeros inside the critical strip $\Re(s)\in (0,n)$ lie on the central line. Correspondingly, the generalized Riemann hypothesis for the arithmetic zeta function of a regular connected equidimensional arithmetic scheme states that its zeros inside the critical strip lie on vertical lines $\Re(s)=1/2,3/2,\dots,n-1/2$ and its poles inside the critical strip lie on vertical lines $\Re(s)=1, 2, \dots,n-1$. This is known for schemes in positive characteristic and follows from Pierre Deligne[^21], but remains entirely unknown in characteristic zero.

### Selberg zeta functions

Selberg, Atle (1956). *Harmonic analysis and discontinuous groups in weakly symmetric Riemannian spaces with applications to Dirichlet series*. *J. Indian Math. Soc.* **20**, 47–87. [MR0088511](https://mathscinet.ams.org/mathscinet-getitem?mr=MR0088511). introduced the [Selberg zeta function](https://en.wikipedia.org/wiki/Selberg_zeta_function) of a Riemann surface. These are similar to the Riemann zeta function: they have a functional equation, and an infinite product similar to the Euler product but taken over closed geodesics rather than primes. The [Selberg trace formula](https://en.wikipedia.org/wiki/Selberg_trace_formula) is the analogue for these functions of the [explicit formulas](https://en.wikipedia.org/wiki/explicit_formula_%28L-function%29) in prime number theory. Selberg proved that the Selberg zeta functions satisfy the analogue of the Riemann hypothesis, with the imaginary parts of their zeros related to the [eigenvalue](https://en.wikipedia.org/wiki/eigenvalue)s of the Laplacian operator of the Riemann surface.

### Ihara zeta functions

The [Ihara zeta function](https://en.wikipedia.org/wiki/Ihara_zeta_function) of a finite graph is an analogue of the [Selberg zeta function](https://en.wikipedia.org/wiki/Selberg_zeta_function), which was first introduced by [Yasutaka Ihara](https://en.wikipedia.org/wiki/Yasutaka_Ihara) in the context of discrete subgroups of the two-by-two p-adic special linear group. A regular finite graph is a [Ramanujan graph](https://en.wikipedia.org/wiki/Ramanujan_graph), a mathematical model of efficient communication networks, if and only if its Ihara zeta function satisfies the analogue of the Riemann hypothesis as was pointed out by [T. Sunada](https://en.wikipedia.org/wiki/Toshikazu_Sunada).

### Montgomery's pair correlation conjecture

Montgomery, Hugh L. (1973). *Analytic number theory*. *American Mathematical Society* **XXIV**, 181–193. [MR0337821](https://mathscinet.ams.org/mathscinet-getitem?mr=MR0337821). suggested the [pair correlation conjecture](https://en.wikipedia.org/wiki/pair_correlation_conjecture) that the correlation functions of the (suitably normalized) zeros of the zeta function should be the same as those of the eigenvalues of a [random hermitian matrix](https://en.wikipedia.org/wiki/Gaussian_unitary_ensemble). Odlyzko, A. M. (1987). *On the distribution of spacings between zeros of the zeta function*. *Mathematics of Computation* **48**(177), 273–308. [MR866115](https://mathscinet.ams.org/mathscinet-getitem?mr=MR866115). [JSTOR 2007890](https://www.jstor.org/stable/2007890). doi:[10.2307/2007890](https://doi.org/10.2307/2007890). showed that this is supported by large-scale numerical calculations of these correlation functions.

Montgomery showed that (assuming the Riemann hypothesis) at least 2/3 of all zeros are simple, and a related conjecture is that all zeros of the zeta function are simple (or more generally have no non-trivial integer linear relations between their imaginary parts). [Dedekind zeta function](https://en.wikipedia.org/wiki/Dedekind_zeta_function)s of algebraic number fields, which generalize the Riemann zeta function, often do have multiple complex zeros. Radziejewski, Maciej (2007). *Independence of Hecke zeta functions of finite order over normal fields*. *Transactions of the American Mathematical Society* **359**(5), 2383–2394. [MR2276625](https://mathscinet.ams.org/mathscinet-getitem?mr=MR2276625). doi:[10.1090/S0002-9947-06-04078-5](https://doi.org/10.1090/S0002-9947-06-04078-5). This is because the Dedekind zeta functions factorize as a product of powers of [Artin L-function](https://en.wikipedia.org/wiki/Artin_L-function)s, so zeros of Artin L-functions sometimes give rise to multiple zeros of Dedekind zeta functions. Other examples of zeta functions with multiple zeros are the L-functions of some [elliptic curve](https://en.wikipedia.org/wiki/elliptic_curve)s: these can have multiple zeros at the real point of their critical line; the [Birch-Swinnerton-Dyer conjecture](https://en.wikipedia.org/wiki/Birch-Swinnerton-Dyer_conjecture) predicts that the multiplicity of this zero is the rank of the elliptic curve.

### Other zeta functions

There are [many other examples](https://en.wikipedia.org/wiki/zeta_function) of zeta functions with analogues of the Riemann hypothesis, some of which have been proved. [Goss zeta function](https://en.wikipedia.org/wiki/Goss_zeta_function)s of function fields have a Riemann hypothesis, proved by Sheats, Jeffrey T. (1998). *The Riemann hypothesis for the Goss zeta function for F<sub>q</sub>[T]*. *Journal of Number Theory* **71**(1), 121–157. [MR1630979](https://mathscinet.ams.org/mathscinet-getitem?mr=MR1630979). [arXiv:math/9801158](https://arxiv.org/abs/math/9801158). doi:[10.1006/jnth.1998.2232](https://doi.org/10.1006/jnth.1998.2232).. [The main conjecture](https://en.wikipedia.org/wiki/Main_conjecture_of_Iwasawa_theory) of [Iwasawa theory](https://en.wikipedia.org/wiki/Iwasawa_theory), proved by [Barry Mazur](https://en.wikipedia.org/wiki/Barry_Mazur) and [Andrew Wiles](https://en.wikipedia.org/wiki/Andrew_Wiles) for [cyclotomic field](https://en.wikipedia.org/wiki/cyclotomic_field)s, and Wiles for [totally real fields](https://en.wikipedia.org/wiki/totally_real_number_field), identifies the zeros of a *p*-adic *L*-function with the eigenvalues of an operator, so can be thought of as an analogue of the [Hilbert–Pólya conjecture](https://en.wikipedia.org/wiki/Hilbert%E2%80%93P%C3%B3lya_conjecture) for [*p*-adic *L*-functions](https://en.wikipedia.org/wiki/p-adic_L-function). Wiles, Andrew (2000). *Mathematics: frontiers and perspectives*. *American Mathematical Society*, 329–342. ISBN 978-0-8218-2697-3. [MR1754786](https://mathscinet.ams.org/mathscinet-getitem?mr=MR1754786).

## Attempted proofs

Several mathematicians have addressed the Riemann hypothesis, but none of their attempts has yet been accepted as a proof. [Watkins (2021)](https://en.wikipedia.org/wiki/Riemann_hypothesis#CITEREFWatkins2021) lists some incorrect solutions.

### Operator theory

Hilbert and Pólya suggested that one way to derive the Riemann hypothesis would be to find a [self-adjoint operator](https://en.wikipedia.org/wiki/self-adjoint_operator), from the existence of which the statement on the real parts of the zeros of *ζ*(*s*) would follow when one applies the criterion on real [eigenvalue](https://en.wikipedia.org/wiki/eigenvalue)s. Some support for this idea comes from several analogues of the Riemann zeta functions whose zeros correspond to eigenvalues of some operator: the zeros of a zeta function of a variety over a finite field correspond to eigenvalues of a [Frobenius element](https://en.wikipedia.org/wiki/Frobenius_element) on an [étale cohomology](https://en.wikipedia.org/wiki/%C3%A9tale_cohomology) group, the zeros of a [Selberg zeta function](https://en.wikipedia.org/wiki/Selberg_zeta_function) are eigenvalues of a [Laplacian operator](https://en.wikipedia.org/wiki/Laplacian_operator) of a Riemann surface, and the zeros of a [p-adic zeta function](https://en.wikipedia.org/wiki/p-adic_zeta_function) correspond to eigenvectors of a Galois action on [ideal class group](https://en.wikipedia.org/wiki/ideal_class_group)s.

Odlyzko, A. M. (1987). *On the distribution of spacings between zeros of the zeta function*. *Mathematics of Computation* **48**(177), 273–308. [MR866115](https://mathscinet.ams.org/mathscinet-getitem?mr=MR866115). [JSTOR 2007890](https://www.jstor.org/stable/2007890). doi:[10.2307/2007890](https://doi.org/10.2307/2007890). showed that the distribution of the zeros of the Riemann zeta function shares some statistical properties with the eigenvalues of [random matrices](https://en.wikipedia.org/wiki/random_matrices) drawn from the [Gaussian unitary ensemble](https://en.wikipedia.org/wiki/Gaussian_unitary_ensemble). This gives some support to the [Hilbert–Pólya conjecture](https://en.wikipedia.org/wiki/Hilbert%E2%80%93P%C3%B3lya_conjecture).

In 1999, [Michael Berry](https://en.wikipedia.org/wiki/Michael_Berry_%28physicist%29) and [Jonathan Keating](https://en.wikipedia.org/wiki/Jonathan_Keating) conjectured that there is some unknown quantization $\hat H$ of the classical Hamiltonian *H* = *xp* so that

$$
\zeta (1/2+i\hat H) = 0
$$

and even more strongly, that the Riemann zeros coincide with the spectrum of the operator $1/2 + i \hat H$. This is in contrast to [canonical quantization](https://en.wikipedia.org/wiki/canonical_quantization), which leads to the [Heisenberg uncertainty principle](https://en.wikipedia.org/wiki/Heisenberg_uncertainty_principle) $\sigma_x \sigma_p \geq \frac{\hbar}{2}$ and the [natural numbers](https://en.wikipedia.org/wiki/natural_numbers) as spectrum of the [quantum harmonic oscillator](https://en.wikipedia.org/wiki/quantum_harmonic_oscillator). The crucial point is that the Hamiltonian should be a self-adjoint operator so that the quantization would be a realization of the Hilbert–Pólya program. In a connection with this quantum mechanical problem Berry and Connes had proposed that the inverse of the potential of the Hamiltonian is connected to the [half-derivative](https://en.wikipedia.org/wiki/half-derivative) of the function

$$
N(s)= \frac{1}{\pi}\operatorname{Arg}\xi(1/2+i\sqrt s)
$$

then, in Hilbert-Polya approach

$$
V^{-1}(x) = \sqrt{4\pi} \frac{d^{1/2}N(x)}{dx^{1/2}}.
$$

This yields a Hamiltonian whose eigenvalues are the square of the imaginary part of the Riemann zeros, and also that the [functional determinant](https://en.wikipedia.org/wiki/functional_determinant) of this [Hamiltonian operator](https://en.wikipedia.org/wiki/Hamiltonian_operator) is just the [Riemann Xi function](https://en.wikipedia.org/wiki/Riemann_Xi_function). In fact the Riemann Xi function would be proportional to the functional determinant ([Hadamard product](https://en.wikipedia.org/wiki/Hadamard_product_%28matrices%29))

$$
\det(H+1/4+s(s-1))
$$

$$
\frac{\xi(s)}{\xi(0)}=\frac{\det(H+s(s-1)+1/4)}{\det(H+1/4)}.
$$

However this operator is not useful in practice since it includes the inverse function (implicit function) of the potential but not the potential itself.
The analogy with the Riemann hypothesis over [finite field](https://en.wikipedia.org/wiki/finite_field)s suggests that the Hilbert space containing eigenvectors corresponding to the zeros might be some sort of first [cohomology group](https://en.wikipedia.org/wiki/cohomology_group) of the [spectrum](https://en.wikipedia.org/wiki/spectrum_of_a_ring) Spec (*Z*) of the integers. Deninger, Christopher (1998). *Proceedings of the International Congress of Mathematicians, Vol. I (Berlin, 1998)*. 163–186. [MR1648030](https://mathscinet.ams.org/mathscinet-getitem?mr=MR1648030). described some of the attempts to find such a cohomology theory. Leichtnam, Eric (2005). *Geometry, spectral theory, groups, and dynamics*. *Amer. Math. Soc.* **387**, 201–236. ISBN 978-0-8218-3710-8. [MR2180209](https://mathscinet.ams.org/mathscinet-getitem?mr=MR2180209). doi:[10.1090/conm/387/07243](https://doi.org/10.1090/conm/387/07243).

Zagier, Don (1981). *Automorphic forms, representation theory and arithmetic (Bombay, 1979)*. *Tata Inst. Fundamental Res., Bombay* **10**, 275–301. [MR633666](https://mathscinet.ams.org/mathscinet-getitem?mr=MR633666). constructed a natural space of invariant functions on the upper half plane that has eigenvalues under the Laplacian operator that correspond to zeros of the Riemann zeta function—and remarked that in the unlikely event that one could show the existence of a suitable positive definite inner product on this space, the Riemann hypothesis would follow. Cartier, P. (1982). *Seminar on Number Theory, Paris 1980–81 (Paris, 1980/1981)*. *Birkhäuser Boston* **22**, 35–48. [MR693308](https://mathscinet.ams.org/mathscinet-getitem?mr=MR693308). discussed a related example, where due to a bizarre bug a computer program listed zeros of the Riemann zeta function as eigenvalues of the same [Laplacian operator](https://en.wikipedia.org/wiki/Laplacian_operator).

Schumayer, Daniel; Hutchinson, David A. W. (2011). *Physics of the Riemann Hypothesis*. *Reviews of Modern Physics* **83**(2), 307–330. [arXiv:1101.3116](https://arxiv.org/abs/1101.3116). [2011RvMP...83..307S](https://ui.adsabs.harvard.edu/abs/2011RvMP...83..307S). doi:[10.1103/RevModPhys.83.307](https://doi.org/10.1103/RevModPhys.83.307). surveyed some of the attempts to construct a suitable physical model related to the Riemann zeta function.

### Lee–Yang theorem

The [Lee–Yang theorem](https://en.wikipedia.org/wiki/Lee%E2%80%93Yang_theorem) states that the zeros of certain [partition functions](https://en.wikipedia.org/wiki/Partition_function_%28statistical_mechanics%29) in [statistical mechanics](https://en.wikipedia.org/wiki/statistical_mechanics) all lie on a "critical line" with their real part equal to 0, and this has led to some speculation about a relationship with the Riemann hypothesis. Knauf, Andreas (1999). *Number theory, dynamical systems and statistical mechanics*. *Reviews in Mathematical Physics* **11**(8), 1027–1060. [MR1714352](https://mathscinet.ams.org/mathscinet-getitem?mr=MR1714352). [1999RvMaP..11.1027K](https://ui.adsabs.harvard.edu/abs/1999RvMaP..11.1027K). doi:[10.1142/S0129055X99000325](https://doi.org/10.1142/S0129055X99000325).

### Turán's result

[Pál Turán](https://en.wikipedia.org/wiki/P%C3%A1l_Tur%C3%A1n) showed that if the functions

$$
\sum_{n=1}^N n^{-s}
$$

have no zeros when the real part of *s* is greater than one then

$$
T(x) = \sum_{n\le x}\frac{\lambda(n)}{n}\ge 0\text{ for } x > 0,
$$

where λ(*n*) is the [Liouville function](https://en.wikipedia.org/wiki/Liouville_function) given by (−1)<sup>*r*</sup> if *n* has *r* prime factors.[^22] He showed that this in turn would imply that the Riemann hypothesis is true. But Haselgrove, C. B. (1958). *A disproof of a conjecture of Pólya*. *Mathematika* **5**(2), 141–145. [MR0104638](https://mathscinet.ams.org/mathscinet-getitem?mr=MR0104638). doi:[10.1112/S0025579300001480](https://doi.org/10.1112/S0025579300001480). proved that *T*(*x*) is negative for infinitely many *x* (and also disproved the closely related [Pólya conjecture](https://en.wikipedia.org/wiki/P%C3%B3lya_conjecture)), and Borwein, Peter; Ferguson, Ron; Mossinghoff, Michael J. (2008). *Sign changes in sums of the Liouville function*. *Mathematics of Computation* **77**(263), 1681–1694. [MR2398787](https://mathscinet.ams.org/mathscinet-getitem?mr=MR2398787). [2008MaCom..77.1681B](https://ui.adsabs.harvard.edu/abs/2008MaCom..77.1681B). doi:[10.1090/S0025-5718-08-02036-X](https://doi.org/10.1090/S0025-5718-08-02036-X). showed that the smallest such *x* is 72 185 376 951 205. Spira, Robert (1968). *Zeros of sections of the zeta function. II*. *Mathematics of Computation* **22**(101), 163–173. [MR0228456](https://mathscinet.ams.org/mathscinet-getitem?mr=MR0228456). [JSTOR 2004774](https://www.jstor.org/stable/2004774). doi:[10.2307/2004774](https://doi.org/10.2307/2004774). showed by numerical calculation that the finite [Dirichlet series](https://en.wikipedia.org/wiki/Dirichlet_series) above for *N* = 19 has a zero with real part greater than 1. Turán also showed that a somewhat weaker assumption, the nonexistence of zeros with real part greater than 1 + *N*<sup>−1/2+*ε*</sup> for large *N* in the finite Dirichlet series above, would also imply the Riemann hypothesis, but Montgomery, Hugh L. (1983). *Studies in pure mathematics. To the memory of Paul Turán*. *Birkhäuser*, 497–506. ISBN 978-3-7643-1288-6. [MR820245](https://mathscinet.ams.org/mathscinet-getitem?mr=MR820245). showed that for all sufficiently large *N* these series have zeros with real part greater than 1 + (log log *N*)/(4 log *N*). Therefore, Turán's result is [vacuously true](https://en.wikipedia.org/wiki/vacuous_truth) and cannot help prove the Riemann hypothesis.

### Noncommutative geometry

[Alain Connes](https://en.wikipedia.org/wiki/Alain_Connes) has described a relationship between the Riemann hypothesis and [noncommutative geometry](https://en.wikipedia.org/wiki/noncommutative_geometry), and showed that a suitable analog of the [Selberg trace formula](https://en.wikipedia.org/wiki/Selberg_trace_formula) for the action of the [idèle class group](https://en.wikipedia.org/wiki/id%C3%A8le_class_group) on the adèle class space would imply the Riemann hypothesis.[^23] Some of these ideas are elaborated in Lapidus, Michel L. (2008). *In search of the Riemann zeros*. *American Mathematical Society*. ISBN 978-0-8218-4222-5. [MR2375028](https://mathscinet.ams.org/mathscinet-getitem?mr=MR2375028). doi:[10.1090/mbk/051](https://doi.org/10.1090/mbk/051)..

### Hilbert spaces of entire functions

[Louis de Branges](https://en.wikipedia.org/wiki/Louis_de_Branges_de_Bourcia) showed that the Riemann hypothesis would follow from a positivity condition on a certain [Hilbert space](https://en.wikipedia.org/wiki/Hilbert_space) of [entire function](https://en.wikipedia.org/wiki/entire_function)s.[^24]
However Conrey, J. B.; Li, Xian-Jin (2000). *A note on some positivity conditions related to zeta and L-functions*. *International Mathematics Research Notices* **2000**(18), 929–940. [MR1792282](https://mathscinet.ams.org/mathscinet-getitem?mr=MR1792282). [arXiv:math/9812166](https://arxiv.org/abs/math/9812166). doi:[10.1155/S1073792800000489](https://doi.org/10.1155/S1073792800000489). showed that the necessary positivity conditions are not satisfied. Despite this obstacle, de Branges has continued to work on an attempted proof of the Riemann hypothesis along the same lines, but this has not been widely accepted by other mathematicians. Sarnak, Peter (2005). *Problems of the Millennium: The Riemann Hypothesis (2004)*. *Clay Mathematics Institute*. [Problems of the Millennium: The Riemann Hypothesis (2004)](http://www.claymath.org/sites/default/files/sarnak_rh_0.pdf).

### Quasicrystals

The Riemann hypothesis implies that the zeros of the zeta function form a [quasicrystal](https://en.wikipedia.org/wiki/quasicrystal), a distribution with discrete support whose [Fourier transform](https://en.wikipedia.org/wiki/Fourier_transform) also has discrete support.
Dyson, Freeman (2009). *Birds and frogs*. *Notices of the American Mathematical Society* **56**(2), 212–223. [MR2483565](https://mathscinet.ams.org/mathscinet-getitem?mr=MR2483565). [Birds and frogs](https://www.ams.org/notices/200902/rtx090200212p.pdf). suggested trying to prove the Riemann hypothesis by classifying, or at least studying, 1-dimensional quasicrystals.

### Arithmetic zeta functions of models of elliptic curves over number fields

When one goes from geometric dimension one, e.g. an [algebraic number field](https://en.wikipedia.org/wiki/algebraic_number_field), to geometric dimension two, e.g. a regular model of an [elliptic curve](https://en.wikipedia.org/wiki/elliptic_curve) over a number field, the two-dimensional part of the generalized Riemann hypothesis for the [arithmetic zeta function](https://en.wikipedia.org/wiki/arithmetic_zeta_function) of the model deals with the poles of the zeta function. In dimension one the study of the zeta integral in [Tate's thesis](https://en.wikipedia.org/wiki/Tate%27s_thesis) does not lead to new important information on the Riemann hypothesis. Contrary to this, in dimension two work of [Ivan Fesenko](https://en.wikipedia.org/wiki/Ivan_Fesenko) on two-dimensional generalisation of Tate's thesis includes an integral representation of a zeta integral closely related to the zeta function. In this new situation, not possible in dimension one, the poles of the zeta function can be studied via the zeta integral and associated adele groups. Related conjecture of [Ivan Fesenko](https://en.wikipedia.org/wiki/Ivan_Fesenko) on the positivity of the fourth derivative of a boundary function associated to the zeta integral essentially implies the pole part of the generalized Riemann hypothesis.[^25] Suzuki, Masatoshi (2011). *Positivity of certain functions associated with analysis on elliptic surfaces*. *Journal of Number Theory* **131**(10), 1770–1796. doi:[10.1016/j.jnt.2011.03.007](https://doi.org/10.1016/j.jnt.2011.03.007). proved that the latter, together with some technical assumptions, implies Fesenko's conjecture.

### Multiple zeta functions

Deligne's proof of the Riemann hypothesis over finite fields used the zeta functions of product varieties, whose zeros and poles correspond to sums of zeros and poles of the original zeta function, in order to bound the real parts of the zeros of the original zeta function. By analogy, Kurokawa, Nobushige (1992). *Zeta functions in geometry (Tokyo, 1990)*. *Kinokuniya* **21**, 219–226. [MR1210791](https://mathscinet.ams.org/mathscinet-getitem?mr=MR1210791). introduced multiple zeta functions whose zeros and poles correspond to sums of zeros and poles of the Riemann zeta function. To make the series converge he restricted to sums of zeros or poles all with non-negative imaginary part. So far, the known bounds on the zeros and poles of the multiple zeta functions are not strong enough to give useful estimates for the zeros of the Riemann zeta function.

## Location of the zeros

### Number of zeros

The functional equation combined with the [argument principle](https://en.wikipedia.org/wiki/argument_principle) implies that the number of zeros of the zeta function with imaginary part between 0 and *T* is given by

$$
N(T)=\frac{1}{\pi}\mathop{\mathrm{Arg}}(\xi(s)) = \frac{1}{\pi}\mathop{\mathrm{Arg}}(\Gamma(\tfrac{s}{2})\pi^{-\frac{s}{2}}\zeta(s)s(s-1)/2)
$$

for *s* = 1/2 + *iT*, where the argument is defined by varying it continuously along the line with Im(*s*) = *T*, starting with argument 0 at ∞ + *iT*. This is the sum of a large but well understood term

$$
\frac{1}{\pi}\mathop{\mathrm{Arg}}(\Gamma(\tfrac{s}{2})\pi^{-s/2}s(s-1)/2) = \frac{T}{2\pi}\log\frac{T}{2\pi}-\frac{T}{2\pi} +7/8+O(1/T)
$$

and a small but rather mysterious term

$$
S(T) = \frac{1}{\pi}\mathop{\mathrm{Arg}}(\zeta(1/2+iT)) =O(\log T).
$$

So the density of zeros with imaginary part near *T* is about log(*T*)/(2 $\pi$), and the function *S* describes the small deviations from this. The function *S*(*t*) jumps by 1 at each zero of the zeta function, and for *t* ≥ 8 it decreases [monotonically](https://en.wikipedia.org/wiki/Monotonically_decreasing) between zeros with derivative close to −log *t*.

Trudgian, Timothy S. (2014). *An improved upper bound for the argument of the Riemann zeta function on the critical line II*. *J. Number Theory* **134**, 280–292. [arXiv:1208.5846](https://arxiv.org/abs/1208.5846). doi:[10.1016/j.jnt.2013.07.017](https://doi.org/10.1016/j.jnt.2013.07.017). proved that, if *T* > *e*, then
  $|N(T) - \frac{T}{2\pi} \log{\frac{T}{2\pi e}}| \leq 0.112 \log T + 0.278 \log\log T + 3.385 + \frac{0.2}{T}$.

[Karatsuba](https://en.wikipedia.org/wiki/Anatolii_Alexeevitch_Karatsuba) (1996) proved that every interval (*T*, *T* + *H*] for $H \ge T^{\frac{27}{82}+\varepsilon}$ contains at least

$$
H(\log T)^{\frac{1}{3}}e^{-c\sqrt{\log\log T}}
$$

points where the function *S*(*t*) changes sign.

Selberg, Atle (1946). *Contributions to the theory of the Riemann zeta-function*. *Arch. Math. Naturvid.* **48**(5), 89–155. [MR0020594](https://mathscinet.ams.org/mathscinet-getitem?mr=MR0020594). showed that the average moments of even powers of *S* are given by

$$
\int_0^T|S(t)|^{2k}dt = \frac{(2k)!}{k!(2\pi)^{2k}}T(\log \log T)^k + O(T(\log \log T)^{k-1/2}).
$$

This suggests that *S*(*T*)/(log log *T*)<sup>1/2</sup> resembles a [Gaussian random variable](https://en.wikipedia.org/wiki/Gaussian_random_variable) with mean 0 and variance 2 $\pi$<sup>2</sup> (Ghosh, Amit (1983). *On the Riemann zeta function—mean value theorems and the distribution of |S(T)|*. *J. Number Theory* **17**, 93–102. doi:[10.1016/0022-314X(83)90010-0](https://doi.org/10.1016/0022-314X%2883%2990010-0). proved this fact).
In particular $|*S*(*T*)|$ is usually somewhere around (log log *T*)<sup>1/2</sup>, but occasionally much larger. The exact order of growth of *S*(*T*) is not known. There has been no unconditional improvement to Riemann's original bound *S*(*T*) = *O*(log *T*), though the Riemann hypothesis implies the slightly smaller bound *S*(*T*) = *O*(log *T*/log log *T*). Titchmarsh, Edward Charles (1986). *The theory of the Riemann zeta-function*. *The Clarendon Press Oxford University Press*. ISBN 978-0-19-853369-6. [MR882550](https://mathscinet.ams.org/mathscinet-getitem?mr=MR882550). The true order of magnitude may be somewhat less than this, as random functions with the same distribution as *S*(*T*) tend to have growth of order about log(*T*)<sup>1/2</sup>. In the other direction it cannot be too small: Selberg, Atle (1946). *Contributions to the theory of the Riemann zeta-function*. *Arch. Math. Naturvid.* **48**(5), 89–155. [MR0020594](https://mathscinet.ams.org/mathscinet-getitem?mr=MR0020594). showed that *S*(*T*) ≠ *o*((log *T*)<sup>1/3</sup>/(log log *T*)<sup>7/3</sup>), and assuming the Riemann hypothesis Montgomery showed that *S*(*T*) ≠ *o*((log *T*)<sup>1/2</sup>/(log log *T*)<sup>1/2</sup>).

Numerical calculations confirm that *S* grows very slowly: $|*S*(*T*)|$ \< 1 for *T* \< 280, $|*S*(*T*)|$ \< 2 for *T* \< 6800000, and the largest value of $|*S*(*T*)|$ found so far is not much larger than 3. Odlyzko, Andrew (2002). *Zeros of the Riemann zeta function: Conjectures and computations*. [Zeros of the Riemann zeta function: Conjectures and computations](http://www.dtc.umn.edu/~odlyzko/talks/riemann-conjectures.pdf).

Riemann's estimate *S*(*T*) = *O*(log *T*) implies that the gaps between zeros are bounded, and Littlewood improved this slightly, showing that the gaps between their imaginary parts tend to 0.

### Theorem of Hadamard and de la Vallée-Poussin

Hadamard, Jacques (1896). *Sur la distribution des zéros de la fonction ζ(s) et ses conséquences arithmétiques*. *Bulletin de la Société Mathématique de France* **14**, 199–220. doi:[10.24033/bsmf.545](https://doi.org/10.24033/bsmf.545). and de la Vallée-Poussin, Ch.J. (1896). *Recherches analytiques sur la théorie des nombres premiers*. *Ann. Soc. Sci. Bruxelles* **20**, 183–256. independently proved that no zeros could lie on the line Re(*s*) = 1. Together with the functional equation and the fact that there are no zeros with real part greater than 1, this showed that all non-trivial zeros must lie in the interior of the critical strip 0 \< Re(*s*) \< 1. This was a key step in their first proofs of the [prime number theorem](https://en.wikipedia.org/wiki/prime_number_theorem).

Both the original proofs that the zeta function has no zeros with real part 1 are similar, and depend on showing that if *ζ*(1 + *it*) vanishes, then *ζ*(1 + 2*it*) is singular, which is not possible. One way of doing this is by using the inequality

$$
|\zeta(\sigma)^3\zeta(\sigma+it)^4\zeta(\sigma+2it)|\ge 1
$$

for *σ* > 1, *t* real, and looking at the limit as *σ* → 1. This inequality follows by taking the real part of the log of the Euler product to see that

$$
|\zeta(\sigma+it)| = \exp\Re\sum_{p^n}\frac{p^{-n(\sigma+it)}}{n}=\exp\sum_{p^n}\frac{p^{-n\sigma}\cos(t\log p^n)}{n},
$$

where the sum is over all prime powers *p*<sup>*n*</sup>, so that

$$
|\zeta(\sigma)^3\zeta(\sigma+it)^4\zeta(\sigma+2it)| = \exp\sum_{p^n}p^{-n\sigma}\frac{3+4\cos(t\log p^n)+\cos(2t\log p^n)}{n}
$$

which is at least 1 because all the terms in the sum are positive, due to the inequality

$$
3+4\cos(\theta)+\cos(2\theta) = 2 (1+\cos(\theta))^2\ge0.
$$

### Zero-free regions

The most extensive computer search by Platt and [Trudgian](https://en.wikipedia.org/wiki/Timothy_Trudgian) [(Platt & Trudgian 2021)](https://en.wikipedia.org/wiki/Riemann_hypothesis#CITEREFPlattTrudgian2021) for counterexamples of the Riemann hypothesis has verified it for $|*t*|$ ≤ $3.0001753328 \times 10^{12}$. Beyond that zero-free regions are known as inequalities concerning *σ* + *i t*, which can be zeros. The oldest version is from [De la Vallée-Poussin (1899–1900)](https://en.wikipedia.org/wiki/Riemann_hypothesis#CITEREFde_la_Vall%C3%A9e-Poussin1899%E2%80%931900), who proved there is a region without zeros that satisfies 1 − *σ* ≥ $*C*/log(*t*)$ for some positive constant *C*. In other words, zeros cannot be too close to the line *σ* = 1: there is a zero-free region close to this line. This has been enlarged by several authors using methods such as [Vinogradov's mean-value theorem](https://en.wikipedia.org/wiki/Vinogradov%27s_mean-value_theorem).

The most recent paper[^26] by Mossinghoff, Trudgian and Yang is from December 2022 and provides four zero-free regions that improved the previous results of Kevin Ford from 2002, Mossinghoff and Trudgian themselves from 2015 and Pace Nielsen's slight improvement of Ford from October 2022:
  $\sigma\ge 1 - \frac{1}{5.558691 \log|t|}$ whenever $|t| \geq 2$,
  $\sigma\ge 1-\frac{1}{55.241(\log{|t|})^{2/3}(\log{\log{|t|}})^{1/3}}$ whenever $|t| \geq 3$ (largest known region in the bound $3.0001753328 \cdot 10^{12} \leq |t| \leq \exp(64.1) \approx 6.89 \cdot 10^{27}$),
  $\sigma\ge 1 - \frac{0.04962 - \frac{0.0196}{1.15 + \log 3 + \frac{1}{6} \log t + \log\log t}}{0.685 + \log 3 + \frac{1}{6} \log t + 1.155 \cdot \log\log t}$ whenever $|t| \geq 1.88 \cdot 10^{14}$ (largest known region in the bound $\exp(64.1) \leq |t| \leq \exp(1000) \approx 1.97 \cdot 10^{434}$) and
  $\sigma\ge 1-\frac{0.05035}{\frac{27}{164}(\log{|t|})+7.096}+\frac{0.0349}{(\frac{27}{164}(\log{|t|})+7.096)^2}$ whenever $|t| \geq \exp(1000)$ (largest known region in its own bound)

The paper also presents an improvement to the second zero-free region, whose bounds are unknown on account of $|t|$ being merely assumed to be "sufficiently large" to fulfill the requirements of the paper's proof. This region is
  $\sigma\ge 1-\frac{1}{48.1588(\log{|t|})^{2/3}(\log{\log{|t|}})^{1/3}}$.

## Zeros on the critical line

Hardy, G. H. (1914). *Sur les Zéros de la Fonction ζ(s) de Riemann*. *C. R. Acad. Sci. Paris* **158**, 1012–1014. [Sur les Zéros de la Fonction ζ(s) de Riemann](http://gallica.bnf.fr/ark:/12148/bpt6k3111d.image.f1014.langEN). and Hardy, G. H.; Littlewood, J. E. (1921). *The zeros of Riemann's zeta-function on the critical line*. *Math. Z.* **10**(3–4), 283–317. doi:[10.1007/BF01211614](https://doi.org/10.1007/BF01211614). [The zeros of Riemann's zeta-function on the critical line](https://zenodo.org/record/1447415). showed there are infinitely many zeros on the critical line, by considering moments of certain functions related to the zeta function. Selberg, Atle (1942). *On the zeros of Riemann's zeta-function*. *SKR. Norske Vid. Akad. Oslo I.* **10**, 59 pp. [MR0010712](https://mathscinet.ams.org/mathscinet-getitem?mr=MR0010712). proved that at least a (small) positive proportion of zeros lie on the line. Levinson, N. (1974). *More than one-third of the zeros of Riemann's zeta function are on σ = 1/2*. *Advances in Mathematics* **13**(4), 383–436. [MR0564081](https://mathscinet.ams.org/mathscinet-getitem?mr=MR0564081). doi:[10.1016/0001-8708(74)90074-7](https://doi.org/10.1016/0001-8708%2874%2990074-7). improved this to one-third of the zeros by relating the zeros of the zeta function to those of its derivative, and Conrey, J. B. (1989). *More than two fifths of the zeros of the Riemann zeta function are on the critical line*. *J. Reine Angew. Math.* **1989**(399), 1–26. [MR1004130](https://mathscinet.ams.org/mathscinet-getitem?mr=MR1004130). doi:[10.1515/crll.1989.399.1](https://doi.org/10.1515/crll.1989.399.1). [More than two fifths of the zeros of the Riemann zeta function are on the critical line](http://www.digizeitschriften.de/resolveppn/GDZPPN002206781). improved this further to two-fifths. In 2020, this estimate was extended to five-twelfths (i.e., 41.6%) by Pratt, Robles, [Zaharescu](https://en.wikipedia.org/wiki/Alexandru_Zaharescu) and Zeindler[^27] by considering extended mollifiers that can accommodate higher order derivatives of the zeta function and their associated Kloosterman sums. Until this point, almost all improvements over the previous half-century had relied on refinements of Levinson's mollification method.

In August 2026, an unreleased research version of the [Anthropic](https://en.wikipedia.org/wiki/Anthropic)'s [large language model](https://en.wikipedia.org/wiki/large_language_model) [Claude](https://en.wikipedia.org/wiki/Claude_%28AI%29) working interactively with human researchers, proved unconditionally that at least two-thirds (66.6%) of the non-trivial zeros of the Riemann zeta function lie on the critical line.[^28] Using an optimized test family, this bound was improved to $\frac{3}{2} - \frac{1}{\sqrt{2}} \cot\left(\frac{1}{\sqrt{2}}\right) \approx 67.25\%$.[^29]

The proof achieved this leap by entirely abandoning [Levinson](https://en.wikipedia.org/wiki/Norman_Levinson)'s method. Instead, it succeeded in stripping the Riemann hypothesis assumption from [Hugh Montgomery](https://en.wikipedia.org/wiki/Hugh_Montgomery_%28mathematician%29)'s 1973 pair-correlation method by interpreting Weil's [explicit formula](https://en.wikipedia.org/wiki/Explicit_formulae_%28L-function%29) as a finite-dimensional [Hermitian matrix](https://en.wikipedia.org/wiki/Hermitian_matrix) over a family of test functions (a Gabor system). The proof bounded the number of off-line zero pairs unconditionally through linear algebra techniques, specifically [Sylvester's law of inertia](https://en.wikipedia.org/wiki/Sylvester%27s_law_of_inertia) and a rank-trace inequality derived from [von Neumann's trace inequality](https://en.wikipedia.org/wiki/Von_Neumann%27s_trace_inequality). The logical core of the proof, including the matrix inequalities and trace asymptotics, was formally verified using the [Lean 4](https://en.wikipedia.org/wiki/Lean_%28proof_assistant%29) theorem prover.[^29]

In September 2026, Youness Lamzouri published a shorter and simpler proof of the same bounds. Lamzouri bypassed the finite-dimensional matrix apparatus entirely, replacing the linear algebra techniques with a single [Hilbert space](https://en.wikipedia.org/wiki/Hilbert_space) inequality based on [Bessel's inequality](https://en.wikipedia.org/wiki/Bessel%27s_inequality) and [Gram–Schmidt orthogonalization](https://en.wikipedia.org/wiki/Gram%E2%80%93Schmidt_process).[^30]

Most zeros lie close to the critical line. More precisely, Bohr, H.; Landau, E. (1914). *Ein Satz über Dirichletsche Reihen mit Anwendung auf die ζ-Funktion und die L-Funktionen*. *Rendiconti del Circolo Matematico di Palermo* **37**(1), 269–272. doi:[10.1007/BF03014823](https://doi.org/10.1007/BF03014823). showed that for any positive *ε*, the number of zeros with real part at least 1/2+*ε* and imaginary part at between −*T* and *T* is $O(T)$. Combined with the facts that zeros on the critical strip are symmetric about the critical line and that the total number of zeros in the critical strip is $\Theta(T\log T)$, [almost all](https://en.wikipedia.org/wiki/almost_all) non-trivial zeros are within a distance *ε* of the critical line. Ivić, A. (1985). *The Riemann Zeta Function*. *John Wiley & Sons*. ISBN 978-0-471-80634-9. [MR0792089](https://mathscinet.ams.org/mathscinet-getitem?mr=MR0792089). gives several more precise versions of this result, called *zero density estimates*, which bound the number of zeros in regions with imaginary part at most *T* and real part at least 1/2 + *ε*.

### Hardy–Littlewood conjectures

In 1914 [Godfrey Harold Hardy](https://en.wikipedia.org/wiki/G._H._Hardy) proved that $\zeta\left(\tfrac{1}{2}+it\right)$ has infinitely many real zeros.

The next two conjectures of [Hardy](https://en.wikipedia.org/wiki/G._H._Hardy) and [John Edensor Littlewood](https://en.wikipedia.org/wiki/John_Edensor_Littlewood) on the distance between real zeros of $\zeta\left(\tfrac{1}{2}+it\right)$ and on the density of zeros of $\zeta\left(\tfrac{1}{2}+it\right)$ on the interval $(T,T+H]$ for sufficiently large $T > 0$, and $H = T^{a + \varepsilon}$ and with as small as possible value of $a > 0$, where $\varepsilon > 0$ is an arbitrarily small number, open two new directions in the investigation of the Riemann zeta function:
1. For any $\varepsilon > 0$ there exists a lower bound $T_0 = T_0(\varepsilon) > 0$ such that for $T \geq T_0$ and $H=T^{\tfrac{1}{4}+\varepsilon}$ the interval $(T,T+H]$ contains a zero of odd order of the function $\zeta\bigl(\tfrac{1}{2}+it\bigr)$.

Let $N(T)$ be the total number of real zeros, and $N_0(T)$ be the total number of zeros of odd order of the function $~\zeta\left(\tfrac{1}{2}+it\right)~$ lying on the interval $(0,T]~$.
1.  For any $\varepsilon > 0$ there exists $T_0 = T_0(\varepsilon) > 0$ and some $c = c(\varepsilon) > 0$, such that for $T \geq T_0$ and $H=T^{\tfrac{1}{2}+\varepsilon}$ the inequality $N_0(T+H)-N_0(T) \geq c H$ is true.

### Selberg's zeta function conjecture

[Atle Selberg](https://en.wikipedia.org/wiki/Atle_Selberg) investigated the problem of Hardy–Littlewood *2* and proved that for any *ε* > 0 there exists such $T_0 = T_0(\varepsilon) > 0$ and *c* = *c*(*ε*) > 0, such that for $T \geq T_0$ and $H=T^{0.5+\varepsilon}$ the inequality $N(T+H)-N(T) \geq cH\log T$ is true.[^31] Selberg conjectured that this could be tightened to $H=T^{0.5}$. [Anatoly Karatsuba](https://en.wikipedia.org/wiki/Anatoly_Karatsuba) proved that for a fixed *ε* satisfying the condition 0 \< *ε* \< 0.001, a sufficiently large *T* and $H = T^{a+\varepsilon}$, $a = \tfrac{27}{82} = \tfrac{1}{3} -\tfrac{1}{246}$, the interval (*T*, *T*+*H*) contains at least *cH* log(*T*) real zeros of the [Riemann zeta function](./riemann_zeta_function.md) $\zeta\left(\tfrac{1}{2}+it\right)$ and therefore confirmed the Selberg conjecture.[^32] The estimates of Selberg and Karatsuba can not be improved in respect of the order of growth as *T* → ∞.

[Karatsuba (1992)](https://en.wikipedia.org/wiki/Riemann_hypothesis#CITEREFKaratsuba1992) proved that an analog of the Selberg conjecture holds for almost all intervals (*T*, *T*+*H*], $H = T^\varepsilon$, where *ε* is an arbitrarily small fixed positive number. The Karatsuba method permits to investigate zeros of the Riemann zeta function on "supershort" intervals of the critical line, that is, on the intervals (*T*, *T*+*H*], the length *H* of which grows slower than any, even arbitrarily small degree *T*. In particular, he proved that for any given numbers *ε*, $\varepsilon_1$ satisfying the conditions $0<\varepsilon, \varepsilon_1<1$ almost all intervals (*T*, *T*+*H*] for $H\ge\exp{\{(\log T)^\varepsilon\}}$ contain at least $H(\log T)^{1-\varepsilon_1}$ zeros of the function $\zeta\left(\tfrac{1}{2}+it\right)$. This estimate is quite close to the one that follows from the Riemann hypothesis.

### Numerical calculations

The function

$$
\pi^{-\frac{s}{2}}\Gamma(\tfrac{s}{2})\zeta(s)
$$

has the same zeros as the zeta function in the critical strip, and is real on the critical line because of the functional equation, so one can prove the existence of zeros exactly on the real line between two points by checking numerically that the function has opposite signs at these points. Usually one writes

$$
\zeta(\tfrac{1}{2} +it) = Z(t)e^{-i\theta(t)}
$$

where Hardy's [Z function](https://en.wikipedia.org/wiki/Z_function) and the [Riemann–Siegel theta function](https://en.wikipedia.org/wiki/Riemann%E2%80%93Siegel_theta_function) *θ* are uniquely defined by this and the condition that they are smooth real functions with *θ*(0) = 0.
By finding many intervals where the function *Z* changes sign one can show that there are many zeros on the critical line. To verify the Riemann hypothesis up to a given [imaginary part](https://en.wikipedia.org/wiki/imaginary_part) *T* of the zeros, one also has to check that there are no further zeros off the line in this region. This can be done by calculating the total number of zeros in the region using [Turing's method](https://en.wikipedia.org/wiki/Turing%27s_method) and checking that it is the same as the number of zeros found on the line. This allows one to verify the Riemann hypothesis computationally up to any desired value of *T* (provided all the zeros of the zeta function in this region are simple and on the critical line).[^33] [^34]

These calculations can also be used to estimate $\pi(x)$ for finite ranges of $x$. For example, using the latest result from 2020 (zeros up to height $3\times10^{12}$), it has been shown that

$$
|\pi(x) - \operatorname{li}(x)| < \frac{1}{8\pi} \sqrt{x} \log(x), \qquad \text{for } 2657 \le x \le 1.101\times10^{26}.
$$

In general, this inequality holds if
  $x \ge 2657$ and $\frac{9.06}{\log{\log{x}}}\sqrt{\frac{x}{\log{x}}} \le T,$
where $T$ is the largest known value such that the Riemann hypothesis is true for all zeros $\rho$ with $\Im{\left (\rho  \right )}\in \left (0,T \right ]$.[^35]

Some calculations of zeros of the zeta function are listed below, where the "height" of a zero is the magnitude of its imaginary part, and the height of the *n*th zero is denoted by *γ<sub>n</sub>*. So far all zeros that have been checked are on the critical line and are simple. (A multiple zero would cause problems for the zero finding algorithms, which depend on finding sign changes between zeros.) For tables of the zeros, see Haselgrove, C. B.; Miller, J. C. P. (1960). *Tables of the Riemann zeta function*. *Cambridge University Press* **6**. [MR0117905](https://mathscinet.ams.org/mathscinet-getitem?mr=MR0117905). or [(Odlyzko)](https://en.wikipedia.org/wiki/Riemann_hypothesis#CITEREFOdlyzko).
| Year | Number of zeros | Author |
| --- | --- | --- |
| 1859? | 3 | B. Riemann used the [Riemann–Siegel formula](https://en.wikipedia.org/wiki/Riemann%E2%80%93Siegel_formula) (unpublished, but reported in Siegel, C. L. (1932). *Über Riemanns Nachlaß zur analytischen Zahlentheorie*. *Quellen Studien zur Geschichte der Math. Astron. Und Phys. Abt. B: Studien 2*, 45–80.). |
| 1903 | 15 | J. P. Gram, J. P. (1903). *Note sur les zéros de la fonction ζ(s) de Riemann*. *Acta Mathematica* **27**, 289–304. doi:[10.1007/BF02421310](https://doi.org/10.1007/BF02421310). [Note sur les zéros de la fonction ζ(s) de Riemann](https://zenodo.org/record/1930945). used the [Euler–Maclaurin formula](https://en.wikipedia.org/wiki/Euler%E2%80%93Maclaurin_formula) and discovered [Gram's law](https://en.wikipedia.org/wiki/Gram%27s_law). He showed that all 10 zeros with imaginary part at most 50 range lie on the critical line with real part 1/2 by computing the sum of the inverse 10th powers of the roots he found. |
| 1914 | 79 (*γ<sub>n</sub>* ≤ 200) | R. J. Backlund, R. J. (1914). *Sur les Zéros de la Fonction ζ(s) de Riemann*. *C. R. Acad. Sci. Paris* **158**, 1979–1981. [Sur les Zéros de la Fonction ζ(s) de Riemann](http://gallica.bnf.fr/ark:/12148/bpt6k3111d/f1983.image). introduced a better method of checking all the zeros up to that point are on the line, by studying the argument *S*(*T*) of the zeta function. |
| 1925 | 138 (*γ<sub>n</sub>* ≤ 300) | J. I. Hutchinson, J. I. (1925). *On the Roots of the Riemann Zeta-Function*. *Transactions of the American Mathematical Society* **27**(1), 49–60. [JSTOR 1989163](https://www.jstor.org/stable/1989163). doi:[10.2307/1989163](https://doi.org/10.2307/1989163). found the first failure of Gram's law, at the Gram point *g*<sub>126</sub>. |
| 1935 | 195 | E. C. Titchmarsh, Edward Charles (1935). *The Zeros of the Riemann Zeta-Function*. *Proceedings of the Royal Society of London. Series A, Mathematical and Physical Sciences* **151**(873), 234–255. [JSTOR 96545](https://www.jstor.org/stable/96545). [1935RSPSA.151..234T](https://ui.adsabs.harvard.edu/abs/1935RSPSA.151..234T). doi:[10.1098/rspa.1935.0146](https://doi.org/10.1098/rspa.1935.0146). used the recently rediscovered [Riemann–Siegel formula](https://en.wikipedia.org/wiki/Riemann%E2%80%93Siegel_formula), which is much faster than Euler–Maclaurin summation. It takes about O(*T*<sup>3/2 + *ε*</sup>) steps to check zeros with imaginary part less than *T*, while the Euler–Maclaurin method takes about O(*T*<sup>2 + *ε*</sup>) steps. |
| 1936 | 1041 | E. C. Titchmarsh, Edward Charles (1936). *The Zeros of the Riemann Zeta-Function*. *Proceedings of the Royal Society of London. Series A, Mathematical and Physical Sciences* **157**(891), 261–263. [arXiv:1004.4143](https://arxiv.org/abs/1004.4143). [JSTOR 96692](https://www.jstor.org/stable/96692). [1936RSPSA.157..261T](https://ui.adsabs.harvard.edu/abs/1936RSPSA.157..261T). doi:[10.1098/rspa.1936.0192](https://doi.org/10.1098/rspa.1936.0192). and L. J. Comrie were the last to find zeros by hand. |
| 1953 | 1104 | A. M. Turing, Alan M. (1953). *Some calculations of the Riemann zeta-function*. *Proceedings of the London Mathematical Society* **3**, 99–117. [MR0055785](https://mathscinet.ams.org/mathscinet-getitem?mr=MR0055785). doi:[10.1112/plms/s3-3.1.99](https://doi.org/10.1112/plms/s3-3.1.99). found a more efficient way to check that all zeros up to some point are accounted for by the zeros on the line, by checking that *Z* has the correct sign at several consecutive Gram points and using the fact that *S*(*T*) has average value 0. This requires almost no extra work because the sign of *Z* at Gram points is already known from finding the zeros, and is still the usual method used. This was the first use of a digital computer to calculate the zeros. |
| 1956 | 15 000 | D. H. Lehmer, D. H. (1956). *Extended computation of the Riemann zeta-function*. *Mathematika* **3**(2), 102–108. [MR0086083](https://mathscinet.ams.org/mathscinet-getitem?mr=MR0086083). doi:[10.1112/S0025579300001753](https://doi.org/10.1112/S0025579300001753). discovered a few cases where the zeta function has zeros that are "only just" on the line: two zeros of the zeta function are so close together that it is unusually difficult to find a sign change between them. This is called "Lehmer's phenomenon", and first occurs at the zeros with imaginary parts 7005.063 and 7005.101, which differ by only .04 while the average gap between other zeros near this point is about 1. |
| 1956 | 25 000 | D. H. Lehmer |
| 1958 | 35 337 | N. A. Meller |
| 1966 | 250 000 | R. S. Lehman |
| 1968 | 3 500 000 | Rosser, J. Barkley; Yohe, J. M.; Schoenfeld, Lowell (1969). *Information Processing 68 (Proc. IFIP Congress, Edinburgh, 1968), Vol. 1: Mathematics, Software*. *North-Holland*, 70–76. [MR0258245](https://mathscinet.ams.org/mathscinet-getitem?mr=MR0258245). stated Rosser's rule (described below). |
| 1977 | 40 000 000 | [R. P. Brent](https://en.wikipedia.org/wiki/Richard_Brent_%28scientist%29%5C) |
| 1979 | 81 000 001 | R. P. Brent |
| 1982 | 200 000 001 | R. P. Brent, [J. van de Lune](https://en.wikipedia.org/wiki/Johan_van_de_Lune%5C), [H. J. J. te Riele](https://en.wikipedia.org/wiki/Herman_te_Riele%5C), D. T. Winter |
| 1983 | 300 000 001 | J. van de Lune, H. J. J. te Riele |
| 1986 | 1 500 000 001 | van de Lune, J.; te Riele, H. J. J.; Winter, D. T. (1986). *On the zeros of the Riemann zeta function in the critical strip. IV*. *Mathematics of Computation* **46**(174), 667–681. [MR829637](https://mathscinet.ams.org/mathscinet-getitem?mr=MR829637). [JSTOR 2008005](https://www.jstor.org/stable/2008005). doi:[10.2307/2008005](https://doi.org/10.2307/2008005). gave some statistical data about the zeros and give several graphs of *Z* at places where it has unusual behavior. |
| 1987 | A few of large (≈10<sup>12</sup>) height | Odlyzko, A. M. (1987). *On the distribution of spacings between zeros of the zeta function*. *Mathematics of Computation* **48**(177), 273–308. [MR866115](https://mathscinet.ams.org/mathscinet-getitem?mr=MR866115). [JSTOR 2007890](https://www.jstor.org/stable/2007890). doi:[10.2307/2007890](https://doi.org/10.2307/2007890). computed smaller numbers of zeros of much larger height, around 10<sup>12</sup>, to high precision to check [Montgomery's pair correlation conjecture](https://en.wikipedia.org/wiki/Montgomery%27s_pair_correlation_conjecture). |
| 1992 | A few of large (≈ $10^{20}$) height | Odlyzko, A. M. (1992). *The 10<sup>20</sup>-th zero of the Riemann zeta function and 175 million of its neighbors*. [The 10<sup>20</sup>-th zero of the Riemann zeta function and 175 million of its neighbors](http://www.dtc.umn.edu/~odlyzko/unpublished/zeta.10to20.1992.pdf). computed 175 million zeros of heights around $10^{20}$ and a few more of heights around 2 $e^{20}$, and gave an extensive discussion of the results. |
| 1998 | 10000 of large (≈ $10^{21}$) height | Odlyzko, A. M. (1998). *The 10<sup>21</sup>st zero of the Riemann zeta function*. [The 10<sup>21</sup>st zero of the Riemann zeta function](http://www.dtc.umn.edu/~odlyzko/unpublished/zeta.10to21.pdf). computed some zeros of height about $10^{21}$ |
| 2001 | $10^{10}$ | J. van de Lune (unpublished) |
| 2004 | ≈9 $e^{11}$[^36] | S. Wedeniwski ([ZetaGrid](https://en.wikipedia.org/wiki/ZetaGrid) distributed computing) |
| 2004 | $10^{13}$ and a few of large (up to ≈ $10^{24}$) heights | Xavier [Gourdon (2004)](https://en.wikipedia.org/wiki/Riemann_hypothesis#CITEREFGourdon2004) and Patrick Demichel used the [Odlyzko–Schönhage algorithm](https://en.wikipedia.org/wiki/Odlyzko%E2%80%93Sch%C3%B6nhage_algorithm). They also checked two billion zeros around heights *γ<sub>n</sub>* = $10^{13}$, $10^{14}$, ..., $10^{24}$. |
| 2020 | 1.2363 $e^{13}$ (*γ<sub>n</sub>* ≤ 3 $e^{12}$) | [Platt & Trudgian (2021)](https://en.wikipedia.org/wiki/Riemann_hypothesis#CITEREFPlattTrudgian2021). They also verified the work of [Gourdon (2004)](https://en.wikipedia.org/wiki/Riemann_hypothesis#CITEREFGourdon2004) and others. |

### Gram points

A [Gram point](https://en.wikipedia.org/wiki/Gram_point) is a point on the critical line 1/2 + *it* where the zeta function is real and non-zero. Using the expression for the zeta function on the critical line, *ζ*(1/2 + *it*) = *Z*(*t*)*e*<sup>−*iθ*(*t*)</sup>, where Hardy's function, [*Z*](https://en.wikipedia.org/wiki/Z_function), is real for real *t*, and *θ* is the [Riemann–Siegel theta function](https://en.wikipedia.org/wiki/Riemann%E2%80%93Siegel_theta_function), we see that zeta is real when sin(*θ*(*t*)) = 0. This implies that *θ*(*t*) is an integer multiple of $\pi$, which allows for the location of Gram points to be calculated fairly easily by inverting the formula for *θ*. They are usually numbered as *g<sub>n</sub>* for *n* = 0, 1, ..., where *g<sub>n</sub>* is the unique solution of *θ*(*t*) = *n* $\pi$.

Gram observed that there was often exactly one zero of the zeta function between any two consecutive Gram points; Hutchinson called this observation **[Gram's law](https://en.wikipedia.org/wiki/Gram%27s_law)**. There are several other closely related statements that are also sometimes called Gram's law: for example, (−1)<sup>*n*</sup>*Z*(*g<sub>n</sub>*) is usually positive, or *Z*(*t*) usually has opposite sign at consecutive Gram points. The imaginary parts *γ<sub>n</sub>* of the first few zeros (in blue) and the first few Gram points *g<sub>n</sub>* are given in the following table
|   |   | *g*<sub>−1</sub> | *γ*<sub>1</sub> | *g*<sub>0</sub> | *γ*<sub>2</sub> | *g*<sub>1</sub> | *γ*<sub>3</sub> | *g*<sub>2</sub> | *γ*<sub>4</sub> | *g*<sub>3</sub> | *γ*<sub>5</sub> | *g*<sub>4</sub> | *γ*<sub>6</sub> | *g*<sub>5</sub> |
| --- | --- | --- | --- | --- | --- | --- | --- | --- | --- | --- | --- | --- | --- | --- |
| 0 | 3.436 | 9.667 | 14.135 | 17.846 | 21.022 | 23.170 | 25.011 | 27.670 | 30.425 | 31.718 | 32.935 | 35.467 | 37.586 | 38.999 |

<figure>

![This is a polar plot of the first 20 real values r_n of the zeta function along the critical line, ζ(1/2 + it), with t running from 0 to 50. The values of r_n in this range are the first 10 non-trivial Riemann zeta function zeros and the first 10 Gram points, each labeled by n. Fifty red points have been plotted between each r_n, and the zeros are projected onto concentric magenta rings scaled to show the relative distance between their values of t. Gram's law states that the curve usually crosses the real axis once between zeros.](https://pub-275e30003c354ac0862cc9839e0f952a.r2.dev/docs/math/RiemannZeta_Zeros.svg.png)

<figcaption>

This is a polar plot of the first 20 real values *r<sub>n</sub>* of the zeta function along the critical line, *ζ*(1/2 + *it*), with *t* running from 0 to 50. The values of *r<sub>n</sub>* in this range are the first 10 non-trivial [Riemann zeta function](./riemann_zeta_function.md) zeros and the first 10 [Gram points](./riemann_hypothesis.md#gram-points), each labeled by *n*. Fifty red points have been plotted between each *r<sub>n</sub>*, and the zeros are projected onto concentric magenta rings scaled to show the relative distance between their values of t.
Gram's law states that the curve usually crosses the real axis once between zeros.

</figcaption>

</figure>

The first failure of Gram's law occurs at the 127th zero and the Gram point *g*<sub>126</sub>, which are in the "wrong" order.

| *g*<sub>124</sub> | *γ*<sub>126</sub> | *g*<sub>125</sub> | *g*<sub>126</sub> |
| --- | --- | --- | --- |
| *γ*<sub>127</sub> |   |   |   |
| --- | --- | --- | --- |
| *γ*<sub>128</sub> | *g*<sub>127</sub> | *γ*<sub>129</sub> | *g*<sub>128</sub> |
| 279.148 | 279.229 | 280.802 | 282.455 |
| 282.465 |   |   |   |
| --- | --- | --- | --- |
| 283.211 | 284.104 | 284.836 | 285.752 |

A Gram point *t* is called good if the zeta function is positive at 1/2 + *it*. The indices of the "bad" Gram points where *Z* has the "wrong" sign are 126, 134, 195, 211, ... [A114856](https://oeis.org/A114856). A *Gram block* is an interval bounded by two good Gram points such that all the Gram points between them are bad. A refinement of Gram's law called Rosser's rule due to Rosser, J. Barkley; Yohe, J. M.; Schoenfeld, Lowell (1969). *Information Processing 68 (Proc. IFIP Congress, Edinburgh, 1968), Vol. 1: Mathematics, Software*. *North-Holland*, 70–76. [MR0258245](https://mathscinet.ams.org/mathscinet-getitem?mr=MR0258245). says that Gram blocks often have the expected number of zeros in them (the same as the number of Gram intervals), even though some of the individual Gram intervals in the block may not have exactly one zero in them. For example, the interval bounded by *g*<sub>125</sub> and *g*<sub>127</sub> is a Gram block containing a unique bad Gram point *g*<sub>126</sub>, and contains the expected number 2 of zeros although neither of its two Gram intervals contains a unique zero. Rosser et al. checked that there were no exceptions to Rosser's rule in the first 3 million zeros, although there are infinitely many exceptions to Rosser's rule over the entire zeta function.

Gram's rule and Rosser's rule both say that in some sense zeros do not stray too far from their expected positions. The distance of a zero from its expected position is controlled by the function *S* defined above, which grows extremely slowly: its average value is of the order of (log log *T*)<sup>1/2</sup>, which only reaches 2 for T around 10<sup>24</sup>. This means that both rules hold most of the time for small *T* but eventually break down often. Indeed, Trudgian, Timothy (2011). *On the success and failure of Gram's Law and the Rosser Rule*. *Acta Arithmetica* **125**(3), 225–256. doi:[10.4064/aa148-3-2](https://doi.org/10.4064/aa148-3-2). showed that both Gram's law and Rosser's rule fail in a positive proportion of cases. To be specific, it is expected that in about 66% one zero is enclosed by two successive Gram points, but in 17% no zero and in 17% two zeros are in such a Gram-interval on the long run Hanga, Catalin (2020). *Random matrix models for Gram's law*. *University of York*. [Random matrix models for Gram's law](https://etheses.whiterose.ac.uk/27858/)..

### Random matrix theory and quantum chaos

Assuming the Riemann hypothesis one can ask what further regularities might govern the distribution of the zeros of the zeta function on the critical line. One conjectural picture is that the critical zeros of the zeta function behave statistically like the eigenvalues of large random [Hermitian matrices](https://en.wikipedia.org/wiki/Hermitian_matrix). The idea began with [Hugh Montgomery](https://en.wikipedia.org/wiki/Hugh_Montgomery_%28mathematician%29)'s work on the [pair correlation conjecture](https://en.wikipedia.org/wiki/pair_correlation_conjecture) for the zeros of the zeta function.[^37] After a suitable rescaling to account for the increasing density of zeros with height, the conjectured pair correlation function agrees with that of [eigenvalue](https://en.wikipedia.org/wiki/eigenvalue)s in the [Gaussian unitary ensemble](https://en.wikipedia.org/wiki/Gaussian_unitary_ensemble) (GUE) in random matrix theory.[^38] [^39]

The connection was tested numerically by [Andrew Odlyzko](https://en.wikipedia.org/wiki/Andrew_Odlyzko), who found that the spacing statistics of zeros high on the critical line agree closely with the predictions of GUE random matrix theory.[^40] [^41] The agreement extends beyond nearest-neighbor spacings to higher correlation functions, and is widely regarded as strong evidence that the zeros are modeled by the same local statistics as random matrices.[^42] [^43]

The random matrix analogy is also related to the Hilbert–Pólya conjecture, and to ideas from [quantum chaos](https://en.wikipedia.org/wiki/quantum_chaos). In quantum chaotic systems, eigenvalues often obey random matrix statistics, so the appearance of the same statistics in the zeros of the zeta function can be interpreted as evidence that they may arise from a selfadjoint operator or from a chaotic dynamical system.[^44] [^45] This gives a heuristic picture of why the zeros might lie on a spectral line and why their spacings exhibit strong repulsion rather than random clustering.[^46]

This viewpoint was adopted by [Nicholas Katz](https://en.wikipedia.org/wiki/Nicholas_Katz) and [Peter Sarnak](https://en.wikipedia.org/wiki/Peter_Sarnak), who proposed that families of [L-function](https://en.wikipedia.org/wiki/L-function)s have symmetry types governed by the compact [classical group](https://en.wikipedia.org/wiki/classical_group)s ([unitary](https://en.wikipedia.org/wiki/unitary_group), [orthogonal](https://en.wikipedia.org/wiki/orthogonal_group), or [symplectic](https://en.wikipedia.org/wiki/symplectic_group)), and that the distributions of their low-lying zeros should match the corresponding random-matrix ensembles.[^47] [^48] [^49] For the Riemann zeta function, the relevant ensemble is that of the unitary group. Random matrix theory has also led to conjectures about the growth of moments of the zeta function on the critical line. In particular, [Jonathan Keating](https://en.wikipedia.org/wiki/Jonathan_Keating) and [Nina Snaith](https://en.wikipedia.org/wiki/Nina_Snaith) used averages over random unitary matrices to predict the main constants in asymptotic moment formulas such as

$$
\frac1T\int_0^T|\zeta(1/2 + it)|^{2k}\,dt
$$

as $T\to\infty$. Their conjectures separate a universal random-matrix factor from an arithmetic [Euler product](https://en.wikipedia.org/wiki/Euler_product) factor, and have influenced later work on moments and ratios of L-functions.[^50] [^51] [^52]

Random matrix theory and quantum chaos are thus heuristic framework surrounding the Riemann hypothesis, even though no proof of the hypothesis is known from this approach.[^53]

## Arguments for and against the Riemann hypothesis

Mathematical papers about the Riemann hypothesis tend to be cautiously noncommittal about its truth. Of authors who express an opinion, most of them, such as Riemann, Bernhard (1859). *Ueber die Anzahl der Primzahlen unter einer gegebenen Grösse*. *Monatsberichte der Berliner Akademie*. [Ueber die Anzahl der Primzahlen unter einer gegebenen Grösse](http://www.maths.tcd.ie/pub/HistMath/People/Riemann/Zeta/). and Bombieri, Enrico (2000). *The Riemann Hypothesis – official problem description*. *Clay Mathematics Institute*. [The Riemann Hypothesis – official problem description](https://web.archive.org/web/20151222090027/http://www.claymath.org/sites/default/files/official_problem_description.pdf)., imply that they expect (or at least hope) that it is true. The few authors who express serious doubt about it include Ivić, Aleksandar (2008). *The Riemann Hypothesis: A Resource for the Afficionado and Virtuoso Alike*. *Springer*, 131–160. ISBN 978-0-387-72125-5. [arXiv:math.NT/0311162](https://arxiv.org/abs/math.NT/0311162)., who lists some reasons for skepticism, and Littlewood, J. E. (1962). *The scientist speculates: an anthology of partly baked idea*. *Basic books*., who flatly states that he believes it false, that there is no evidence for it and no imaginable reason it would be true. The consensus of the survey articles ( Bombieri, Enrico (2000). *The Riemann Hypothesis – official problem description*. *Clay Mathematics Institute*. [The Riemann Hypothesis – official problem description](https://web.archive.org/web/20151222090027/http://www.claymath.org/sites/default/files/official_problem_description.pdf)., Conrey, J. Brian (2003). *The Riemann Hypothesis*. *Notices of the American Mathematical Society*, 341–353. [The Riemann Hypothesis](https://www.ams.org/notices/200303/fea-conrey-web.pdf)., and Sarnak, Peter (2005). *Problems of the Millennium: The Riemann Hypothesis (2004)*. *Clay Mathematics Institute*. [Problems of the Millennium: The Riemann Hypothesis (2004)](http://www.claymath.org/sites/default/files/sarnak_rh_0.pdf).) is that the evidence for it is strong but not overwhelming, so that while it is probably true there is reasonable doubt.

Some of the arguments for and against the Riemann hypothesis are listed by Conrey, J. Brian (2003). *The Riemann Hypothesis*. *Notices of the American Mathematical Society*, 341–353. [The Riemann Hypothesis](https://www.ams.org/notices/200303/fea-conrey-web.pdf)., Sarnak, Peter (2005). *Problems of the Millennium: The Riemann Hypothesis (2004)*. *Clay Mathematics Institute*. [Problems of the Millennium: The Riemann Hypothesis (2004)](http://www.claymath.org/sites/default/files/sarnak_rh_0.pdf)., and Ivić, Aleksandar (2008). *The Riemann Hypothesis: A Resource for the Afficionado and Virtuoso Alike*. *Springer*, 131–160. ISBN 978-0-387-72125-5. [arXiv:math.NT/0311162](https://arxiv.org/abs/math.NT/0311162)., and include the following:
* Several analogues of the Riemann hypothesis have already been proved. The proof of the Riemann hypothesis for varieties over finite fields by Deligne, Pierre (1974). *La conjecture de Weil. I*. *Publications Mathématiques de l'IHÉS* **43**, 273–307. [MR0340258](https://mathscinet.ams.org/mathscinet-getitem?mr=MR0340258). doi:[10.1007/BF02684373](https://doi.org/10.1007/BF02684373). [La conjecture de Weil. I](http://www.numdam.org/item?id=PMIHES_1974__43__273_0). is possibly the single strongest theoretical reason in favor of the Riemann hypothesis. This provides some evidence for the more general conjecture that all zeta functions associated with [automorphic](https://en.wikipedia.org/wiki/Automorphic_form) forms satisfy a Riemann hypothesis, which includes the classical Riemann hypothesis as a special case. Similarly [Selberg zeta function](https://en.wikipedia.org/wiki/Selberg_zeta_function)s satisfy the analogue of the Riemann hypothesis, and are in some ways similar to the Riemann zeta function, having a functional equation and an infinite product expansion analogous to the Euler product expansion. But there are also some major differences; for example, they are not given by Dirichlet series. The Riemann hypothesis for the [Goss zeta function](https://en.wikipedia.org/wiki/Goss_zeta_function) was proved by Sheats, Jeffrey T. (1998). *The Riemann hypothesis for the Goss zeta function for F<sub>q</sub>[T]*. *Journal of Number Theory* **71**(1), 121–157. [MR1630979](https://mathscinet.ams.org/mathscinet-getitem?mr=MR1630979). [arXiv:math/9801158](https://arxiv.org/abs/math/9801158). doi:[10.1006/jnth.1998.2232](https://doi.org/10.1006/jnth.1998.2232).. In contrast to these positive examples, some [Epstein zeta function](https://en.wikipedia.org/wiki/Epstein_zeta_function)s do not satisfy the Riemann hypothesis even though they have an infinite number of zeros on the critical line. Titchmarsh, Edward Charles (1986). *The theory of the Riemann zeta-function*. *The Clarendon Press Oxford University Press*. ISBN 978-0-19-853369-6. [MR882550](https://mathscinet.ams.org/mathscinet-getitem?mr=MR882550). These functions are quite similar to the Riemann zeta function, and have a Dirichlet series expansion and a [functional equation](https://en.wikipedia.org/wiki/Functional_equation_%28L-function%29), but the ones known to fail the Riemann hypothesis do not have an [Euler product](https://en.wikipedia.org/wiki/Euler_product) and are not directly related to [automorphic representation](https://en.wikipedia.org/wiki/automorphic_representation)s.
* At first, the numerical verification that many zeros lie on the line seems strong evidence for it. But analytic number theory has had many conjectures supported by substantial numerical evidence that turned out to be false. See [Skewes number](https://en.wikipedia.org/wiki/Skewes_number) for a notorious example, where the first exception to a plausible conjecture related to the Riemann hypothesis probably occurs around 10<sup>316</sup>; a counterexample to the Riemann hypothesis with imaginary part this size would be far beyond anything that can currently be computed using a direct approach. The problem is that the behavior is often influenced by very slowly increasing functions such as log log *T*, that tend to infinity, but do so so slowly that this cannot be detected by computation. Such functions occur in the theory of the zeta function controlling the behavior of its zeros; for example the function *S*(*T*) above has average size around (log log *T*)<sup>1/2</sup>. As *S*(*T*) jumps by at least 2 at any counterexample to the Riemann hypothesis, one might expect any counterexamples to the Riemann hypothesis to start appearing only when *S*(*T*) becomes large. It is never much more than 3 as far as it has been calculated, but is known to be unbounded, suggesting that calculations may not have yet reached the region of typical behavior of the zeta function.
* [Denjoy](https://en.wikipedia.org/wiki/Arnaud_Denjoy)'s probabilistic argument for the Riemann hypothesis Edwards, H. M. (1974). *Riemann's Zeta Function*. *Dover Publications*. ISBN 978-0-486-41740-0. [MR0466039](https://mathscinet.ams.org/mathscinet-getitem?mr=MR0466039). is based on the observation that if *μ*(*x*) is a random sequence of "1"s and "−1"s then, for every *ε* > 0, the [partial sum](https://en.wikipedia.org/wiki/partial_sum)s

$$
M(x) = \sum_{n \le x} \mu(n)
$$

 (the values of which are positions in a [simple random walk](https://en.wikipedia.org/wiki/simple_random_walk)) satisfy the bound

$$
M(x) = O(x^{1/2+\varepsilon})
$$

 with [probability 1](https://en.wikipedia.org/wiki/Almost_surely). The Riemann hypothesis is equivalent to this bound for the [Möbius function](https://en.wikipedia.org/wiki/M%C3%B6bius_function) μ and the [Mertens function](https://en.wikipedia.org/wiki/Mertens_function) *M* derived in the same way from it. In other words, the Riemann hypothesis is in some sense equivalent to saying that *μ*(*x*) behaves like a random sequence of coin tosses. When *μ*(*x*) is nonzero its sign gives the [parity](https://en.wikipedia.org/wiki/Parity_%28mathematics%29) of the number of prime factors of *x*, so informally the Riemann hypothesis says that the parity of the number of prime factors of an integer behaves randomly. Such probabilistic arguments in number theory often give the right answer, but tend to be very hard to make rigorous, and occasionally give the wrong answer for some results, such as [Maier's theorem](https://en.wikipedia.org/wiki/Maier%27s_theorem).
* The calculations in Odlyzko, A. M. (1987). *On the distribution of spacings between zeros of the zeta function*. *Mathematics of Computation* **48**(177), 273–308. [MR866115](https://mathscinet.ams.org/mathscinet-getitem?mr=MR866115). [JSTOR 2007890](https://www.jstor.org/stable/2007890). doi:[10.2307/2007890](https://doi.org/10.2307/2007890). show that the zeros of the zeta function behave very much like the eigenvalues of a random [Hermitian matrix](https://en.wikipedia.org/wiki/Hermitian_matrix), suggesting that they are the eigenvalues of some self-adjoint operator, which would imply the Riemann hypothesis. All attempts to find such an operator have failed.
* There are several theorems, such as [Goldbach's weak conjecture](https://en.wikipedia.org/wiki/Goldbach%27s_weak_conjecture) for sufficiently large odd numbers, that were first proved using the generalized Riemann hypothesis, and later shown to be true unconditionally. This could be considered as weak evidence for the generalized Riemann hypothesis, as several of its "predictions" are true.
* [Lehmer's phenomenon](https://en.wikipedia.org/wiki/Lehmer_pair), Lehmer, D. H. (1956). *Extended computation of the Riemann zeta-function*. *Mathematika* **3**(2), 102–108. [MR0086083](https://mathscinet.ams.org/mathscinet-getitem?mr=MR0086083). doi:[10.1112/S0025579300001753](https://doi.org/10.1112/S0025579300001753). where two zeros are sometimes very close, is sometimes given as a reason to disbelieve the Riemann hypothesis. But one would expect this to happen occasionally by chance even if the Riemann hypothesis is true, and Odlyzko's calculations suggest that nearby pairs of zeros occur just as often as predicted by [Montgomery's conjecture](https://en.wikipedia.org/wiki/Montgomery%27s_pair_correlation_conjecture).
* [Patterson](https://en.wikipedia.org/wiki/Samuel_James_Patterson) suggests that the most compelling reason for the Riemann hypothesis for most mathematicians is the hope that primes are distributed as regularly as possible.[^54]

## Notes


[^1]: Riemann, Bernhard (1859). *Ueber die Anzahl der Primzahlen unter einer gegebenen Grösse*. *Monatsberichte der Berliner Akademie*. [Ueber die Anzahl der Primzahlen unter einer gegebenen Grösse](http://www.maths.tcd.ie/pub/HistMath/People/Riemann/Zeta/).
[^2]: Connes, Alain (2026). *The Riemann Hypothesis: Past, Present and a Letter Through Time*. [arXiv:2602.04022](https://arxiv.org/abs/2602.04022).
[^3]: Euler, Leonhard (1744). [Variae observationes circa series infinitas.](http://eulerarchive.maa.org/docs/originals/E072.pdf) *Commentarii academiae scientiarum Petropolitanae* 9, pp. 160–188, Theorems 7 and 8. In Theorem 7 Euler proves the formula in the special case $s=1$, and in Theorem 8 he proves it more generally. In the first corollary to his Theorem 7 he notes that $\zeta(1)=\log\infty$, and he makes use of this latter result in his Theorem 19, to show that the sum of the inverses of the prime numbers is $\log\log\infty$.
[^4]: Values for *ζ* can be found by calculating, e.g., *ζ*(1/2 − 30*i*).
[^5]: Ingham, A.E. (1932). *The Distribution of Prime Numbers*. *Cambridge University Press* **30**, Theorem 30, p. 83; Montgomery, Hugh L.; Vaughan, Robert C. (2007). *Multiplicative Number Theory I. Classical Theory*. *Cambridge University Press* **97**, p. 430.
[^6]: von Koch, Niels Helge (1901). *Sur la distribution des nombres premiers*. *Acta Mathematica* **24**, 159–182. doi:[10.1007/BF02403071](https://doi.org/10.1007/BF02403071). [Sur la distribution des nombres premiers](https://zenodo.org/records/2347595).
[^7]: Dudek, Adrian W. (2014). *On the Riemann hypothesis and the difference between primes*. *International Journal of Number Theory* **11**(3), 771–778. [arXiv:1402.6417](https://arxiv.org/abs/1402.6417). [2014arXiv1402.6417D](https://ui.adsabs.harvard.edu/abs/2014arXiv1402.6417D). doi:[10.1142/S1793042115500426](https://doi.org/10.1142/S1793042115500426).
[^8]: Landau, Edmund (1924). *Über die Möbiussche Funktion*. *Rend. Circ. Mat. Palermo* **48**(2), 277–280. doi:[10.1007/BF03014702](https://doi.org/10.1007/BF03014702).
[^9]: Titchmarsh, Edward Charles (1927). *A consequence of the Riemann hypothesis*. *J. London Math. Soc.* **2**(4), 247–254. doi:[10.1112/jlms/s1-2.4.247](https://doi.org/10.1112/jlms/s1-2.4.247).
[^10]: Maier, Helmut; Montgomery, Hugh (2009). *The sum of the Möbius function*. *Bull. London Math. Soc.* **41**(2), 213–226. doi:[10.1112/blms/bdn119](https://doi.org/10.1112/blms/bdn119).
[^11]: Soundararajan, Kannan (2009). *Partial sums of the Möbius function*. *J. Reine Angew. Math.* **2009**(631), 141–152. [arXiv:0705.0723](https://arxiv.org/abs/0705.0723). doi:[10.1515/CRELLE.2009.044](https://doi.org/10.1515/CRELLE.2009.044).
[^12]: Lagarias, Jeffrey C. (2002). *An elementary problem equivalent to the Riemann hypothesis*. *The American Mathematical Monthly* **109**(6), 534–543. [MR1908008](https://mathscinet.ams.org/mathscinet-getitem?mr=MR1908008). [arXiv:math/0008177](https://arxiv.org/abs/math/0008177). [JSTOR 2695443](https://www.jstor.org/stable/2695443). doi:[10.2307/2695443](https://doi.org/10.2307/2695443).
[^13]: Baez-Duarte, Luis (2005). *A general strong Nyman-Beurling criterion for the Riemann hypothesis*. *Publications de l'Institut Mathématique* **78**(92), 117–125. [arXiv:math/0505453](https://arxiv.org/abs/math/0505453). doi:[10.2298/PIM0578117B](https://doi.org/10.2298/PIM0578117B).
[^14]: (October 31, 2022). *Caltech Mathematicians Solve 19th Century Number Riddle*. *California Institute of Technology*. [Caltech Mathematicians Solve 19th Century Number Riddle](https://www.caltech.edu/about/news/caltech-mathematicians-solve-19th-century-number-riddle).
[^15]: Dunn, Alexander; Radziwiłł, Maksym (2021). *Bias in cubic Gauss sums: Patterson's conjecture*. [arXiv:2109.07463](https://arxiv.org/abs/2109.07463).
[^16]: Knapowski, S. (1962). *On sign-changes of the difference $\pi(x)-\operatorname{li} x$*. *Acta Arithmetica* **7**, 107–119. [MR133308](https://mathscinet.ams.org/mathscinet-getitem?mr=MR133308). doi:[10.4064/aa-7-2-107-119](https://doi.org/10.4064/aa-7-2-107-119).
[^17]: Goldfeld, Dorian (1985). *Gauss' class number problem for imaginary quadratic fields*. *Bulletin of the American Mathematical Society* **13**(1), 23–37. doi:[10.1090/S0273-0979-1985-15352-2](https://doi.org/10.1090/S0273-0979-1985-15352-2).
[^18]: Siegel, Carl (1935). *Über die Classenzahl quadratischer Zahlkörper*. *Acta Arithmetica* **1**(1), 83–86. doi:[10.4064/aa-1-1-83-86](https://doi.org/10.4064/aa-1-1-83-86). [Über die Classenzahl quadratischer Zahlkörper](https://eudml.org/doc/205054).
[^19]: Deligne, Pierre (1974). *La conjecture de Weil. I*. *Publications Mathématiques de l'IHÉS* **43**, 273–307. [MR0340258](https://mathscinet.ams.org/mathscinet-getitem?mr=MR0340258). doi:[10.1007/BF02684373](https://doi.org/10.1007/BF02684373). [La conjecture de Weil. I](http://www.numdam.org/item?id=PMIHES_1974__43__273_0).
[^20]: Serre, Jean-Pierre (1969–1970). *Facteurs locaux des fonctions zeta des varietés algébriques (définitions et conjectures)*. *Séminaire Delange-Pisot-Poitou* **19**. [Facteurs locaux des fonctions zeta des varietés algébriques (définitions et conjectures)](https://eudml.org/doc/110758).
[^21]: Deligne, Pierre (1974). *La conjecture de Weil. I*. *Publications Mathématiques de l'IHÉS* **43**, 273–307. [MR0340258](https://mathscinet.ams.org/mathscinet-getitem?mr=MR0340258). doi:[10.1007/BF02684373](https://doi.org/10.1007/BF02684373). [La conjecture de Weil. I](http://www.numdam.org/item?id=PMIHES_1974__43__273_0).
[^22]: Turán, Paul (1948). *On some approximative Dirichlet-polynomials in the theory of the zeta-function of Riemann*. *Danske Vid. Selsk. Mat.-Fys. Medd.* **24**(17), 36. [MR0027305](https://mathscinet.ams.org/mathscinet-getitem?mr=MR0027305).
[^23]: Connes, Alain (1999). *Trace formula in noncommutative geometry and the zeros of the Riemann zeta function*. *Selecta Mathematica* **5**(1), 29–106. [MR1694895](https://mathscinet.ams.org/mathscinet-getitem?mr=MR1694895). [arXiv:math/9811068](https://arxiv.org/abs/math/9811068). doi:[10.1007/s000290050042](https://doi.org/10.1007/s000290050042).
[^24]: de Branges, Louis (1992). *The convergence of Euler products*. *Journal of Functional Analysis* **107**(1), 122–210. [MR1165869](https://mathscinet.ams.org/mathscinet-getitem?mr=MR1165869). doi:[10.1016/0022-1236(92)90103-P](https://doi.org/10.1016/0022-1236%2892%2990103-P).
[^25]: Fesenko, Ivan (2010). *Analysis on arithmetic schemes. II*. *Journal of K-theory* **5**(3), 437–557. doi:[10.1017/is010004028jkt103](https://doi.org/10.1017/is010004028jkt103).
[^26]: Mossinghoff, Michael J.; Trudgian, Timothy S.; Yang, Andrew (2022-12-13). *Explicit zero-free regions for the Riemann zeta-function*. [arXiv:2212.06867](https://arxiv.org/abs/2212.06867).
[^27]: Pratt, Kyle; Robles, Nicolas; Zaharescu, Alexandru; Zeindler, Dirk (2020). *More than five-twelfths of the zeros of ζ are on the critical line*. *Res Math Sci* **7**. [arXiv:1802.10521](https://arxiv.org/abs/1802.10521). doi:[10.1007/s40687-019-0199-8](https://doi.org/10.1007/s40687-019-0199-8).
[^28]: (2026-08-10). *Learning more about Claude's mathematical capabilities*. *Home \ Anthropic*. [Learning more about Claude's mathematical capabilities](https://www.anthropic.com/research/riemann-zeta).
[^29]: Claude (August 10, 2026). *More Than Two Thirds of the Zeros of the Riemann Zeta Function Lie on the Critical Line*. *Anthropic*. [More Than Two Thirds of the Zeros of the Riemann Zeta Function Lie on the Critical Line](https://www-cdn.anthropic.com/564f962e60643842f5fcb4a17c9dbc8f608f1c37.pdf).
[^30]: Lamzouri, Youness (September 2026). *A new proof that more than 2/3 of the zeros of the Riemann zeta function are simple and on the critical line*. [arXiv:2609.02882](https://arxiv.org/abs/2609.02882).
[^31]: Selberg, Atle (1942). *On the zeros of Riemann's zeta-function*. *SKR. Norske Vid. Akad. Oslo I.* **10**, 59 pp. [MR0010712](https://mathscinet.ams.org/mathscinet-getitem?mr=MR0010712).
[^32]: Karatsuba, A. A. (1984a). *Zeros of the function ζ(s) on short intervals of the critical line*. *Izv. Akad. Nauk SSSR, Ser. Mat.* **48**(3), 569–584. [MR0747251](https://mathscinet.ams.org/mathscinet-getitem?mr=MR0747251).
[^33]: Hejhal, Dennis A.; Odlyzko, Andrew M.. *Alan Turing and the Riemann Zeta Function*. *University of Minnesota*. [Alan Turing and the Riemann Zeta Function](https://www-users.cse.umn.edu/~odlyzko/doc/turing.zeta.pdfhttps://www-users.cse.umn.edu/~odlyzko/doc/turing.zeta.pdfv).
[^34]: Yu, Matiyasevich (2020). *The Riemann Hypothesis in computer science*. *Theoretical Computer Science* **807**, 257–265. doi:[10.1016/j.tcs.2019.07.028](https://doi.org/10.1016/j.tcs.2019.07.028). [The Riemann Hypothesis in computer science](https://www.sciencedirect.com/science/article/pii/S0304397519304633).
[^35]: Johnston, Daniel R. (29 July 2022). *Improving bounds on prime counting functions by partial verification of the Riemann hypothesis*. *The Ramanujan Journal* **59**(4), 1307–1321. [arXiv:2109.02249](https://arxiv.org/abs/2109.02249). doi:[10.1007/s11139-022-00616-x](https://doi.org/10.1007/s11139-022-00616-x). [Improving bounds on prime counting functions by partial verification of the Riemann hypothesis](https://link.springer.com/article/10.1007/s11139-022-00616-x).
[^36]: Weisstein, Eric W. [Riemann Zeta Function Zeros](https://mathworld.wolfram.com/RiemannZetaFunctionZeros.html), MathWorld.: "ZetaGrid is a distributed computing project attempting to calculate as many zeros as possible. It had reached 1029.9 billion zeros as of Feb. 18, 2005."
[^37]: Montgomery, Hugh L. (1973). *Analytic number theory*. *American Mathematical Society* **XXIV**, 181–193. [MR0337821](https://mathscinet.ams.org/mathscinet-getitem?mr=MR0337821).
[^38]: Montgomery, Hugh L. (1973). *Analytic number theory*. *American Mathematical Society* **XXIV**, 181–193. [MR0337821](https://mathscinet.ams.org/mathscinet-getitem?mr=MR0337821).
[^39]: Connes, Alain (2026). *The Riemann Hypothesis: Past, Present and a Letter Through Time*. [arXiv:2602.04022](https://arxiv.org/abs/2602.04022).
[^40]: Odlyzko, A. M. (1987). *On the distribution of spacings between zeros of the zeta function*. *Mathematics of Computation* **48**(177), 273–308. [MR866115](https://mathscinet.ams.org/mathscinet-getitem?mr=MR866115). [JSTOR 2007890](https://www.jstor.org/stable/2007890). doi:[10.2307/2007890](https://doi.org/10.2307/2007890).
[^41]: Connes, Alain (2026). *The Riemann Hypothesis: Past, Present and a Letter Through Time*. [arXiv:2602.04022](https://arxiv.org/abs/2602.04022).
[^42]: Odlyzko, A. M. (1987). *On the distribution of spacings between zeros of the zeta function*. *Mathematics of Computation* **48**(177), 273–308. [MR866115](https://mathscinet.ams.org/mathscinet-getitem?mr=MR866115). [JSTOR 2007890](https://www.jstor.org/stable/2007890). doi:[10.2307/2007890](https://doi.org/10.2307/2007890).
[^43]: Connes, Alain (2026). *The Riemann Hypothesis: Past, Present and a Letter Through Time*. [arXiv:2602.04022](https://arxiv.org/abs/2602.04022).
[^44]: Berry, M. V.; Keating, J. P. (1999). *Supersymmetry and Trace Formulae: Chaos and Disorder*. *Plenum Press*, 355–367.
[^45]: Connes, Alain (2026). *The Riemann Hypothesis: Past, Present and a Letter Through Time*. [arXiv:2602.04022](https://arxiv.org/abs/2602.04022).
[^46]: Connes, Alain (2026). *The Riemann Hypothesis: Past, Present and a Letter Through Time*. [arXiv:2602.04022](https://arxiv.org/abs/2602.04022).
[^47]: Katz, Nicholas M.; Sarnak, P. (1999a). *Zeros of zeta functions and symmetry*. *Bulletin of the American Mathematical Society* **36**, 1–26. doi:[10.1090/S0273-0979-99-00766-1](https://doi.org/10.1090/S0273-0979-99-00766-1).
[^48]: Katz, Nicholas M.; Sarnak, Peter (1999b). *Random matrices, Frobenius eigenvalues, and monodromy*. *American Mathematical Society* **45**
[^49]: Connes, Alain (2026). *The Riemann Hypothesis: Past, Present and a Letter Through Time*. [arXiv:2602.04022](https://arxiv.org/abs/2602.04022).
[^50]: Keating, Jonathan P.; Snaith, N. C. (2000a). *Random matrix theory and ζ(1/2 + it)*. *Communications in Mathematical Physics* **214**(1), 57–89. [MR1794265](https://mathscinet.ams.org/mathscinet-getitem?mr=MR1794265). [2000CMaPh.214...57K](https://ui.adsabs.harvard.edu/abs/2000CMaPh.214...57K). doi:[10.1007/s002200000261](https://doi.org/10.1007/s002200000261).
[^51]: Keating, Jonathan P.; Snaith, N. C. (2000b). *Random matrix theory and L-functions at s = 1/2*. *Communications in Mathematical Physics* **214**(1), 91–100. [2000CMaPh.214...91K](https://ui.adsabs.harvard.edu/abs/2000CMaPh.214...91K). doi:[10.1007/s002200000262](https://doi.org/10.1007/s002200000262).
[^52]: Connes, Alain (2026). *The Riemann Hypothesis: Past, Present and a Letter Through Time*. [arXiv:2602.04022](https://arxiv.org/abs/2602.04022).
[^53]: Connes, Alain (2026). *The Riemann Hypothesis: Past, Present and a Letter Through Time*. [arXiv:2602.04022](https://arxiv.org/abs/2602.04022).
[^54]: p. 75: "One should probably add to this list the 'Platonic' reason that one expects the natural numbers to be the most perfect idea conceivable, and that this is only compatible with the primes being distributed in the most regular fashion possible ..."
## References

* Artin, Emil (1924). *Quadratische Körper im Gebiete der höheren Kongruenzen. II. Analytischer Teil*. *Mathematische Zeitschrift* **19**(1), 207–246. doi:[10.1007/BF01181075](https://doi.org/10.1007/BF01181075).
* Backlund, R. J. (1914). *Sur les Zéros de la Fonction ζ(s) de Riemann*. *C. R. Acad. Sci. Paris* **158**, 1979–1981. [Sur les Zéros de la Fonction *ζ*(*s*) de Riemann](http://gallica.bnf.fr/ark:/12148/bpt6k3111d/f1983.image).
* Beurling, Arne (1955). *A closure problem related to the Riemann zeta-function*. *Proceedings of the National Academy of Sciences of the United States of America* **41**(5), 312–314. [MR0070655](https://mathscinet.ams.org/mathscinet-getitem?mr=MR0070655). [1955PNAS...41..312B](https://ui.adsabs.harvard.edu/abs/1955PNAS...41..312B). [PMID 16589670](https://pubmed.ncbi.nlm.nih.gov/16589670/). [528084](https://www.ncbi.nlm.nih.gov/pmc/articles/528084/). doi:[10.1073/pnas.41.5.312](https://doi.org/10.1073/pnas.41.5.312).
* Berry, M. V.; Keating, J. P. (1999). *Supersymmetry and Trace Formulae: Chaos and Disorder*. *Plenum Press*, 355–367..
* Björner, Anders (2011). *A cell complex in number theory*. *Advances in Applied Mathematics* **46**(1–4), 71–85. [arXiv:1101.5704](https://arxiv.org/abs/1101.5704). doi:[10.1016/j.aam.2010.09.007](https://doi.org/10.1016/j.aam.2010.09.007).
* Bohr, H.; Landau, E. (1914). *Ein Satz über Dirichletsche Reihen mit Anwendung auf die ζ-Funktion und die L-Funktionen*. *Rendiconti del Circolo Matematico di Palermo* **37**(1), 269–272. doi:[10.1007/BF03014823](https://doi.org/10.1007/BF03014823).
* Bombieri, Enrico (2000). *The Riemann Hypothesis – official problem description*. *Clay Mathematics Institute*. [The Riemann Hypothesis – official problem description](https://web.archive.org/web/20151222090027/http://www.claymath.org/sites/default/files/official_problem_description.pdf). Reprinted in Borwein, Peter; Ferguson, Ron; Mossinghoff, Michael J. (2008). *Sign changes in sums of the Liouville function*. *Mathematics of Computation* **77**(263), 1681–1694. [MR2398787](https://mathscinet.ams.org/mathscinet-getitem?mr=MR2398787). [2008MaCom..77.1681B](https://ui.adsabs.harvard.edu/abs/2008MaCom..77.1681B). doi:[10.1090/S0025-5718-08-02036-X](https://doi.org/10.1090/S0025-5718-08-02036-X)..
* (2008). *The Riemann Hypothesis: A Resource for the Afficionado and Virtuoso Alike*. *Springer*. ISBN 978-0-387-72125-5. doi:[10.1007/978-0-387-72126-2](https://doi.org/10.1007/978-0-387-72126-2).
* Borwein, Peter; Ferguson, Ron; Mossinghoff, Michael J. (2008). *Sign changes in sums of the Liouville function*. *Mathematics of Computation* **77**(263), 1681–1694. [MR2398787](https://mathscinet.ams.org/mathscinet-getitem?mr=MR2398787). [2008MaCom..77.1681B](https://ui.adsabs.harvard.edu/abs/2008MaCom..77.1681B). doi:[10.1090/S0025-5718-08-02036-X](https://doi.org/10.1090/S0025-5718-08-02036-X).
* de Branges, Louis (1992). *The convergence of Euler products*. *Journal of Functional Analysis* **107**(1), 122–210. [MR1165869](https://mathscinet.ams.org/mathscinet-getitem?mr=MR1165869). doi:[10.1016/0022-1236(92)90103-P](https://doi.org/10.1016/0022-1236%2892%2990103-P).
* Broughan, Kevin (2017). *Equivalents of the Riemann Hypothesis*. *Cambridge University Press*. ISBN 978-1108290784.
* Burton, David M. (2006). *Elementary Number Theory*. *Tata McGraw-Hill Publishing Company Limited*. ISBN 978-0-07-061607-3. [Elementary Number Theory](https://books.google.com/books?id=XMQjuoTqqRMC).
* Cartier, P. (1982). *Seminar on Number Theory, Paris 1980–81 (Paris, 1980/1981)*. *Birkhäuser Boston* **22**, 35–48. [MR693308](https://mathscinet.ams.org/mathscinet-getitem?mr=MR693308).
* Connes, Alain (1999). *Trace formula in noncommutative geometry and the zeros of the Riemann zeta function*. *Selecta Mathematica* **5**(1), 29–106. [MR1694895](https://mathscinet.ams.org/mathscinet-getitem?mr=MR1694895). [arXiv:math/9811068](https://arxiv.org/abs/math/9811068). doi:[10.1007/s000290050042](https://doi.org/10.1007/s000290050042).
* Connes, Alain (2000). *Mathematics: frontiers and perspectives*. *American Mathematical Society*, 35–54. [MR1754766](https://mathscinet.ams.org/mathscinet-getitem?mr=MR1754766).
* Connes, Alain (2016). *Open Problems in Mathematics*. *Springer*, 225–257. ISBN 978-3-319-32160-8. [arXiv:1509.05576](https://arxiv.org/abs/1509.05576). doi:[10.1007/978-3-319-32162-2_5](https://doi.org/10.1007/978-3-319-32162-2_5).
* Connes, Alain (2026). *The Riemann Hypothesis: Past, Present and a Letter Through Time*. [arXiv:2602.04022](https://arxiv.org/abs/2602.04022).
* Conrey, J. B. (1989). *More than two fifths of the zeros of the Riemann zeta function are on the critical line*. *J. Reine Angew. Math.* **1989**(399), 1–26. [MR1004130](https://mathscinet.ams.org/mathscinet-getitem?mr=MR1004130). doi:[10.1515/crll.1989.399.1](https://doi.org/10.1515/crll.1989.399.1). [More than two fifths of the zeros of the Riemann zeta function are on the critical line](http://www.digizeitschriften.de/resolveppn/GDZPPN002206781).
* Conrey, J. Brian (2003). *The Riemann Hypothesis*. *Notices of the American Mathematical Society*, 341–353. [The Riemann Hypothesis](https://www.ams.org/notices/200303/fea-conrey-web.pdf). Reprinted in Borwein, Peter; Ferguson, Ron; Mossinghoff, Michael J. (2008). *Sign changes in sums of the Liouville function*. *Mathematics of Computation* **77**(263), 1681–1694. [MR2398787](https://mathscinet.ams.org/mathscinet-getitem?mr=MR2398787). [2008MaCom..77.1681B](https://ui.adsabs.harvard.edu/abs/2008MaCom..77.1681B). doi:[10.1090/S0025-5718-08-02036-X](https://doi.org/10.1090/S0025-5718-08-02036-X)..
* Conrey, J. B.; Li, Xian-Jin (2000). *A note on some positivity conditions related to zeta and L-functions*. *International Mathematics Research Notices* **2000**(18), 929–940. [MR1792282](https://mathscinet.ams.org/mathscinet-getitem?mr=MR1792282). [arXiv:math/9812166](https://arxiv.org/abs/math/9812166). doi:[10.1155/S1073792800000489](https://doi.org/10.1155/S1073792800000489).
* Deligne, Pierre (1974). *La conjecture de Weil. I*. *Publications Mathématiques de l'IHÉS* **43**, 273–307. [MR0340258](https://mathscinet.ams.org/mathscinet-getitem?mr=MR0340258). doi:[10.1007/BF02684373](https://doi.org/10.1007/BF02684373). [La conjecture de Weil. I](http://www.numdam.org/item?id=PMIHES_1974__43__273_0).
* Deligne, Pierre (1980). *La conjecture de Weil : II*. *Publications Mathématiques de l'IHÉS* **52**, 137–252. doi:[10.1007/BF02684780](https://doi.org/10.1007/BF02684780). [La conjecture de Weil : II](http://www.numdam.org/item?id=PMIHES_1980__52__137_0).
* Deninger, Christopher (1998). *Proceedings of the International Congress of Mathematicians, Vol. I (Berlin, 1998)*. 163–186. [MR1648030](https://mathscinet.ams.org/mathscinet-getitem?mr=MR1648030).
* Dudek, Adrian W. (2014-08-21). *On the Riemann hypothesis and the difference between primes*. *International Journal of Number Theory* **11**(3), 771–778. [arXiv:1402.6417](https://arxiv.org/abs/1402.6417). [2014arXiv1402.6417D](https://ui.adsabs.harvard.edu/abs/2014arXiv1402.6417D). doi:[10.1142/S1793042115500426](https://doi.org/10.1142/S1793042115500426).
* Dyson, Freeman (2009). *Birds and frogs*. *Notices of the American Mathematical Society* **56**(2), 212–223. [MR2483565](https://mathscinet.ams.org/mathscinet-getitem?mr=MR2483565). [Birds and frogs](https://www.ams.org/notices/200902/rtx090200212p.pdf).
* Edwards, H. M. (1974). *Riemann's Zeta Function*. *Dover Publications*. ISBN 978-0-486-41740-0. [MR0466039](https://mathscinet.ams.org/mathscinet-getitem?mr=MR0466039).
* Fesenko, Ivan (2010). *Analysis on arithmetic schemes. II*. *Journal of K-theory* **5**(3), 437–557. doi:[10.1017/is010004028jkt103](https://doi.org/10.1017/is010004028jkt103).
* Ford, Kevin (2002). *Vinogradov's integral and bounds for the Riemann zeta function*. *Proceedings of the London Mathematical Society* **85**(3), 565–633. [MR1936814](https://mathscinet.ams.org/mathscinet-getitem?mr=MR1936814). [arXiv:1910.08209](https://arxiv.org/abs/1910.08209). doi:[10.1112/S0024611502013655](https://doi.org/10.1112/S0024611502013655).
* Katz, Nicholas M.; Sarnak, P. (1999a). *Zeros of zeta functions and symmetry*. *Bulletin of the American Mathematical Society* **36**, 1–26. doi:[10.1090/S0273-0979-99-00766-1](https://doi.org/10.1090/S0273-0979-99-00766-1)..
* Katz, Nicholas M.; Sarnak, Peter (1999b). *Random matrices, Frobenius eigenvalues, and monodromy*. *American Mathematical Society* **45**.
* Franel, J.; Landau, E. (1924). *Les suites de Farey et le problème des nombres premiers" (Franel, 198–201); "Bemerkungen zu der vorstehenden Abhandlung von Herrn Franel (Landau, 202–206)*. *Göttinger Nachrichten*, 198–206.
* Ghosh, Amit (1983). *On the Riemann zeta function—mean value theorems and the distribution of |S(T)|*. *J. Number Theory* **17**, 93–102. doi:[10.1016/0022-314X(83)90010-0](https://doi.org/10.1016/0022-314X%2883%2990010-0).
* Gourdon, Xavier (2004). *The 10<sup>13</sup> first zeros of the Riemann Zeta function, and zeros computation at very large height*. [The 10<sup>13</sup> first zeros of the Riemann Zeta function, and zeros computation at very large height](http://numbers.computation.free.fr/Constants/Miscellaneous/zetazeros1e13-1e24.pdf).
* Gram, J. P. (1903). *Note sur les zéros de la fonction ζ(s) de Riemann*. *Acta Mathematica* **27**, 289–304. doi:[10.1007/BF02421310](https://doi.org/10.1007/BF02421310). [Note sur les zéros de la fonction *ζ*(*s*) de Riemann](https://zenodo.org/record/1930945).
* Hadamard, Jacques (1896). *Sur la distribution des zéros de la fonction ζ(s) et ses conséquences arithmétiques*. *Bulletin de la Société Mathématique de France* **14**, 199–220. doi:[10.24033/bsmf.545](https://doi.org/10.24033/bsmf.545). Reprinted in Borwein, Peter; Ferguson, Ron; Mossinghoff, Michael J. (2008). *Sign changes in sums of the Liouville function*. *Mathematics of Computation* **77**(263), 1681–1694. [MR2398787](https://mathscinet.ams.org/mathscinet-getitem?mr=MR2398787). [2008MaCom..77.1681B](https://ui.adsabs.harvard.edu/abs/2008MaCom..77.1681B). doi:[10.1090/S0025-5718-08-02036-X](https://doi.org/10.1090/S0025-5718-08-02036-X)..
* Hanga, Catalin (2020). *Random matrix models for Gram's law*. *University of York*. [Random matrix models for Gram's law](https://etheses.whiterose.ac.uk/27858/).
* Hardy, G. H. (1914). *Sur les Zéros de la Fonction ζ(s) de Riemann*. *C. R. Acad. Sci. Paris* **158**, 1012–1014. [Sur les Zéros de la Fonction *ζ*(*s*) de Riemann](http://gallica.bnf.fr/ark:/12148/bpt6k3111d.image.f1014.langEN). Reprinted in Borwein, Peter; Ferguson, Ron; Mossinghoff, Michael J. (2008). *Sign changes in sums of the Liouville function*. *Mathematics of Computation* **77**(263), 1681–1694. [MR2398787](https://mathscinet.ams.org/mathscinet-getitem?mr=MR2398787). [2008MaCom..77.1681B](https://ui.adsabs.harvard.edu/abs/2008MaCom..77.1681B). doi:[10.1090/S0025-5718-08-02036-X](https://doi.org/10.1090/S0025-5718-08-02036-X)..
* Hardy, G. H.; Littlewood, J. E. (1921). *The zeros of Riemann's zeta-function on the critical line*. *Math. Z.* **10**(3–4), 283–317. doi:[10.1007/BF01211614](https://doi.org/10.1007/BF01211614). [The zeros of Riemann's zeta-function on the critical line](https://zenodo.org/record/1447415).
* Haselgrove, C. B. (1958). *A disproof of a conjecture of Pólya*. *Mathematika* **5**(2), 141–145. [MR0104638](https://mathscinet.ams.org/mathscinet-getitem?mr=MR0104638). doi:[10.1112/S0025579300001480](https://doi.org/10.1112/S0025579300001480). Reprinted in Borwein, Peter; Ferguson, Ron; Mossinghoff, Michael J. (2008). *Sign changes in sums of the Liouville function*. *Mathematics of Computation* **77**(263), 1681–1694. [MR2398787](https://mathscinet.ams.org/mathscinet-getitem?mr=MR2398787). [2008MaCom..77.1681B](https://ui.adsabs.harvard.edu/abs/2008MaCom..77.1681B). doi:[10.1090/S0025-5718-08-02036-X](https://doi.org/10.1090/S0025-5718-08-02036-X)..
* Haselgrove, C. B.; Miller, J. C. P. (1960). *Tables of the Riemann zeta function*. *Cambridge University Press* **6**. [MR0117905](https://mathscinet.ams.org/mathscinet-getitem?mr=MR0117905).
* Hutchinson, J. I. (1925). *On the Roots of the Riemann Zeta-Function*. *Transactions of the American Mathematical Society* **27**(1), 49–60. [JSTOR 1989163](https://www.jstor.org/stable/1989163). doi:[10.2307/1989163](https://doi.org/10.2307/1989163).
* Ingham, A.E. (1932). *The Distribution of Prime Numbers*. *Cambridge University Press* **30**. Reprinted 1990, ISBN 978-0-521-39789-6, [MR 1074573](https://mathscinet.ams.org/mathscinet-getitem?mr=1074573)
* Ireland, Kenneth; Rosen, Michael (1990). *A Classical Introduction to Modern Number Theory (Second edition)*. *Springer*. ISBN 0-387-97329-X.
* Ivić, A. (1985). *The Riemann Zeta Function*. *John Wiley & Sons*. ISBN 978-0-471-80634-9. [MR0792089](https://mathscinet.ams.org/mathscinet-getitem?mr=MR0792089). (Reprinted by Dover 2003)
* Ivić, Aleksandar (2008). *The Riemann Hypothesis: A Resource for the Afficionado and Virtuoso Alike*. *Springer*, 131–160. ISBN 978-0-387-72125-5. [arXiv:math.NT/0311162](https://arxiv.org/abs/math.NT/0311162).
* Karatsuba, A. A. (1984a). *Zeros of the function ζ(s) on short intervals of the critical line*. *Izv. Akad. Nauk SSSR, Ser. Mat.* **48**(3), 569–584. [MR0747251](https://mathscinet.ams.org/mathscinet-getitem?mr=MR0747251).
* Karatsuba, A. A. (1984b). *Distribution of zeros of the function ζ(1/2 + it)*. *Izv. Akad. Nauk SSSR, Ser. Mat.* **48**(6), 1214–1224. [MR0772113](https://mathscinet.ams.org/mathscinet-getitem?mr=MR0772113).
* Karatsuba, A. A. (1985). *Zeros of the Riemann zeta-function on the critical line*. *Trudy Mat. Inst. Steklov.*, 167–178. [MR0804073](https://mathscinet.ams.org/mathscinet-getitem?mr=MR0804073).
* Karatsuba, A. A. (1992). *On the number of zeros of the Riemann zeta-function lying in almost all short intervals of the critical line*. *Izv. Ross. Akad. Nauk, Ser. Mat.* **56**(2), 372–397. [MR1180378](https://mathscinet.ams.org/mathscinet-getitem?mr=MR1180378). [1993IzMat..40..353K](https://ui.adsabs.harvard.edu/abs/1993IzMat..40..353K). doi:[10.1070/IM1993v040n02ABEH002168](https://doi.org/10.1070/IM1993v040n02ABEH002168).
* Karatsuba, A. A.; Voronin, S. M. (1992). *The Riemann zeta-function*. *Walter de Gruyter & Co.* **5**. ISBN 978-3-11-013170-3. [MR1183467](https://mathscinet.ams.org/mathscinet-getitem?mr=MR1183467). doi:[10.1515/9783110886146](https://doi.org/10.1515/9783110886146).
* Keating, Jonathan P.; Snaith, N. C. (2000a). *Random matrix theory and ζ(1/2 + it)*. *Communications in Mathematical Physics* **214**(1), 57–89. [MR1794265](https://mathscinet.ams.org/mathscinet-getitem?mr=MR1794265). [2000CMaPh.214...57K](https://ui.adsabs.harvard.edu/abs/2000CMaPh.214...57K). doi:[10.1007/s002200000261](https://doi.org/10.1007/s002200000261).
* Keating, Jonathan P.; Snaith, N. C. (2000b). *Random matrix theory and L-functions at s = 1/2*. *Communications in Mathematical Physics* **214**(1), 91–100. [2000CMaPh.214...91K](https://ui.adsabs.harvard.edu/abs/2000CMaPh.214...91K). doi:[10.1007/s002200000262](https://doi.org/10.1007/s002200000262)..
* Knapowski, S. (1962). *On sign-changes of the difference $\pi(x)-\operatorname{li} x$*. *Acta Arithmetica* **7**, 107–119. [MR133308](https://mathscinet.ams.org/mathscinet-getitem?mr=MR133308). doi:[10.4064/aa-7-2-107-119](https://doi.org/10.4064/aa-7-2-107-119).
* Knauf, Andreas (1999). *Number theory, dynamical systems and statistical mechanics*. *Reviews in Mathematical Physics* **11**(8), 1027–1060. [MR1714352](https://mathscinet.ams.org/mathscinet-getitem?mr=MR1714352). [1999RvMaP..11.1027K](https://ui.adsabs.harvard.edu/abs/1999RvMaP..11.1027K). doi:[10.1142/S0129055X99000325](https://doi.org/10.1142/S0129055X99000325).
* von Koch, Niels Helge (1901). *Sur la distribution des nombres premiers*. *Acta Mathematica* **24**, 159–182. doi:[10.1007/BF02403071](https://doi.org/10.1007/BF02403071). [Sur la distribution des nombres premiers](https://zenodo.org/record/2347595).
* Kurokawa, Nobushige (1992). *Zeta functions in geometry (Tokyo, 1990)*. *Kinokuniya* **21**, 219–226. [MR1210791](https://mathscinet.ams.org/mathscinet-getitem?mr=MR1210791).
* Lapidus, Michel L. (2008). *In search of the Riemann zeros*. *American Mathematical Society*. ISBN 978-0-8218-4222-5. [MR2375028](https://mathscinet.ams.org/mathscinet-getitem?mr=MR2375028). doi:[10.1090/mbk/051](https://doi.org/10.1090/mbk/051).
* [Zeta-function](https://encyclopediaofmath.org/wiki/Z/z099260), Encyclopedia of Mathematics.
* Lehmer, D. H. (1956). *Extended computation of the Riemann zeta-function*. *Mathematika* **3**(2), 102–108. [MR0086083](https://mathscinet.ams.org/mathscinet-getitem?mr=MR0086083). doi:[10.1112/S0025579300001753](https://doi.org/10.1112/S0025579300001753).
* Leichtnam, Eric (2005). *Geometry, spectral theory, groups, and dynamics*. *Amer. Math. Soc.* **387**, 201–236. ISBN 978-0-8218-3710-8. [MR2180209](https://mathscinet.ams.org/mathscinet-getitem?mr=MR2180209). doi:[10.1090/conm/387/07243](https://doi.org/10.1090/conm/387/07243)..
* Levinson, N. (1974). *More than one-third of the zeros of Riemann's zeta function are on σ = 1/2*. *Advances in Mathematics* **13**(4), 383–436. [MR0564081](https://mathscinet.ams.org/mathscinet-getitem?mr=MR0564081). doi:[10.1016/0001-8708(74)90074-7](https://doi.org/10.1016/0001-8708%2874%2990074-7).
* Littlewood, J. E. (1962). *The scientist speculates: an anthology of partly baked idea*. *Basic books*.
* van de Lune, J.; te Riele, H. J. J.; Winter, D. T. (1986). *On the zeros of the Riemann zeta function in the critical strip. IV*. *Mathematics of Computation* **46**(174), 667–681. [MR829637](https://mathscinet.ams.org/mathscinet-getitem?mr=MR829637). [JSTOR 2008005](https://www.jstor.org/stable/2008005). doi:[10.2307/2008005](https://doi.org/10.2307/2008005).
* Massias, J.-P.; Nicolas, Jean-Louis; Robin, G. (1988). *Évaluation asymptotique de l'ordre maximum d'un élément du groupe symétrique*. *Acta Arithmetica* **50**(3), 221–242. [MR960551](https://mathscinet.ams.org/mathscinet-getitem?mr=MR960551). doi:[10.4064/aa-50-3-221-242](https://doi.org/10.4064/aa-50-3-221-242). [Évaluation asymptotique de l'ordre maximum d'un élément du groupe symétrique](http://matwbn.icm.edu.pl/tresc.php?wyd=6&tom=50&jez=).
*Mazur, Barry; Stein, William (2015). *Prime Numbers and the Riemann Hypothesis*. [Prime Numbers and the Riemann Hypothesis](http://wstein.org/rh/).
* Montgomery, Hugh L. (1973). *Analytic number theory*. *American Mathematical Society* **XXIV**, 181–193. [MR0337821](https://mathscinet.ams.org/mathscinet-getitem?mr=MR0337821). Reprinted in Borwein, Peter; Ferguson, Ron; Mossinghoff, Michael J. (2008). *Sign changes in sums of the Liouville function*. *Mathematics of Computation* **77**(263), 1681–1694. [MR2398787](https://mathscinet.ams.org/mathscinet-getitem?mr=MR2398787). [2008MaCom..77.1681B](https://ui.adsabs.harvard.edu/abs/2008MaCom..77.1681B). doi:[10.1090/S0025-5718-08-02036-X](https://doi.org/10.1090/S0025-5718-08-02036-X)..
* Montgomery, Hugh L. (1983). *Studies in pure mathematics. To the memory of Paul Turán*. *Birkhäuser*, 497–506. ISBN 978-3-7643-1288-6. [MR820245](https://mathscinet.ams.org/mathscinet-getitem?mr=MR820245).
* Montgomery, Hugh L.; Vaughan, Robert C. (2007). *Multiplicative Number Theory I. Classical Theory*. *Cambridge University Press* **97**.ISBN 978-0-521-84903-6
* Newman, C. M. (1976). *Fourier transforms with only real zeroes*. *Proceedings of the American Mathematical Society* **61**(2), 246–251. doi:[10.1090/S0002-9939-1976-0434982-5](https://doi.org/10.1090/S0002-9939-1976-0434982-5).,
* Nicely, Thomas R. (1999). *New maximal prime gaps and first occurrences*. *Mathematics of Computation* **68**(227), 1311–1315. [MR1627813](https://mathscinet.ams.org/mathscinet-getitem?mr=MR1627813). [1999MaCom..68.1311N](https://ui.adsabs.harvard.edu/abs/1999MaCom..68.1311N). doi:[10.1090/S0025-5718-99-01065-0](https://doi.org/10.1090/S0025-5718-99-01065-0). [New maximal prime gaps and first occurrences](http://www.trnicely.net/gaps/gaps.html)..
* Nyman, Bertil (1950). *On the One-Dimensional Translation Group and Semi-Group in Certain Function Spaces*. *University of Uppsala*. [MR0036444](https://mathscinet.ams.org/mathscinet-getitem?mr=MR0036444).
* Odlyzko, A. M.; te Riele, H. J. J. (1985). *Disproof of the Mertens conjecture*. *Journal für die reine und angewandte Mathematik* **1985**(357), 138–160. [MR783538](https://mathscinet.ams.org/mathscinet-getitem?mr=MR783538). doi:[10.1515/crll.1985.357.138](https://doi.org/10.1515/crll.1985.357.138). [Disproof of the Mertens conjecture](https://archive.today/20120711011237/http://gdz.sub.uni-goettingen.de/no_cache/dms/load/img/?IDDOC=262633).
* Odlyzko, A. M. (1987). *On the distribution of spacings between zeros of the zeta function*. *Mathematics of Computation* **48**(177), 273–308. [MR866115](https://mathscinet.ams.org/mathscinet-getitem?mr=MR866115). [JSTOR 2007890](https://www.jstor.org/stable/2007890). doi:[10.2307/2007890](https://doi.org/10.2307/2007890).
* Odlyzko, A. M. (1990). *Bounds for discriminants and related estimates for class numbers, regulators and zeros of zeta functions: a survey of recent results*. *Séminaire de Théorie des Nombres de Bordeaux* **2**(1), 119–141. [MR1061762](https://mathscinet.ams.org/mathscinet-getitem?mr=MR1061762). doi:[10.5802/jtnb.22](https://doi.org/10.5802/jtnb.22). [Bounds for discriminants and related estimates for class numbers, regulators and zeros of zeta functions: a survey of recent results](http://www.numdam.org/item?id=JTNB_1990__2_1_119_0).
* Odlyzko, A. M. (1992). *The 10<sup>20</sup>-th zero of the Riemann zeta function and 175 million of its neighbors*. [The 10<sup>20</sup>-th zero of the Riemann zeta function and 175 million of its neighbors](http://www.dtc.umn.edu/~odlyzko/unpublished/zeta.10to20.1992.pdf). This unpublished book describes the implementation of the algorithm and discusses the results in detail.
* Odlyzko, A. M. (1998). *The 10<sup>21</sup>st zero of the Riemann zeta function*. [The 10<sup>21</sup>st zero of the Riemann zeta function](http://www.dtc.umn.edu/~odlyzko/unpublished/zeta.10to21.pdf).
* Ono, Ken; Soundararajan, K. (1997). *Ramanujan's ternary quadratic form*. *Inventiones Mathematicae* **130**(3), 415–454. [1997InMat.130..415O](https://ui.adsabs.harvard.edu/abs/1997InMat.130..415O). doi:[10.1007/s002220050191](https://doi.org/10.1007/s002220050191).
* Patterson, S. J. (1988). *An introduction to the theory of the Riemann zeta-function*. *Cambridge University Press* **14**. ISBN 978-0-521-33535-5. [MR933558](https://mathscinet.ams.org/mathscinet-getitem?mr=MR933558). doi:[10.1017/CBO9780511623707](https://doi.org/10.1017/CBO9780511623707).
* Platt, Dave; Trudgian, Timothy (January 2021). *The Riemann hypothesis is true up to 3·10<sup>12</sup>*. *Bulletin of the London Mathematical Society* **53**(3), 792–797. [arXiv:2004.09765](https://arxiv.org/abs/2004.09765). doi:[10.1112/blms.12460](https://doi.org/10.1112/blms.12460).
* Radziejewski, Maciej (2007). *Independence of Hecke zeta functions of finite order over normal fields*. *Transactions of the American Mathematical Society* **359**(5), 2383–2394. [MR2276625](https://mathscinet.ams.org/mathscinet-getitem?mr=MR2276625). doi:[10.1090/S0002-9947-06-04078-5](https://doi.org/10.1090/S0002-9947-06-04078-5).
* Ribenboim, Paulo (1996). *The New Book of Prime Number Records*. *Springer*. ISBN 0-387-94457-5.
* Riemann, Bernhard (1859). *Ueber die Anzahl der Primzahlen unter einer gegebenen Grösse*. *Monatsberichte der Berliner Akademie*. [Ueber die Anzahl der Primzahlen unter einer gegebenen Grösse](http://www.maths.tcd.ie/pub/HistMath/People/Riemann/Zeta/).. In *Gesammelte Werke*, Teubner, Leipzig (1892), Reprinted by Dover, New York (1953). [Original manuscript](http://www.claymath.org/publications/riemanns-1859-manuscript/) (with English translation). Reprinted in Borwein, Peter; Ferguson, Ron; Mossinghoff, Michael J. (2008). *Sign changes in sums of the Liouville function*. *Mathematics of Computation* **77**(263), 1681–1694. [MR2398787](https://mathscinet.ams.org/mathscinet-getitem?mr=MR2398787). [2008MaCom..77.1681B](https://ui.adsabs.harvard.edu/abs/2008MaCom..77.1681B). doi:[10.1090/S0025-5718-08-02036-X](https://doi.org/10.1090/S0025-5718-08-02036-X). and Edwards, H. M. (1974). *Riemann's Zeta Function*. *Dover Publications*. ISBN 978-0-486-41740-0. [MR0466039](https://mathscinet.ams.org/mathscinet-getitem?mr=MR0466039).
* Riesel, Hans; Göhl, Gunnar (1970). *Some calculations related to Riemann's prime number formula*. *Mathematics of Computation* **24**(112), 969–983. [MR0277489](https://mathscinet.ams.org/mathscinet-getitem?mr=MR0277489). [JSTOR 2004630](https://www.jstor.org/stable/2004630). doi:[10.2307/2004630](https://doi.org/10.2307/2004630). [Some calculations related to Riemann's prime number formula](https://www.ams.org/journals/mcom/1970-24-112/S0025-5718-1970-0277489-3/S0025-5718-1970-0277489-3.pdf).
* Riesz, M. (1916). *Sur l'hypothèse de Riemann*. *Acta Mathematica* **40**, 185–190. doi:[10.1007/BF02418544](https://doi.org/10.1007/BF02418544).
* Robin, G. (1984). *Grandes valeurs de la fonction somme des diviseurs et hypothèse de Riemann*. *Journal de Mathématiques Pures et Appliquées* **63**(2), 187–213. [MR774171](https://mathscinet.ams.org/mathscinet-getitem?mr=MR774171).
* Rodgers, Brad; Tao, Terence (2020). *The de Bruijn–Newman constant is non-negative*. *Forum of Mathematics* **8**, e6, 62. [MR4089393](https://mathscinet.ams.org/mathscinet-getitem?mr=MR4089393). [arXiv:1801.05914](https://arxiv.org/abs/1801.05914). doi:[10.1017/fmp.2020.6](https://doi.org/10.1017/fmp.2020.6).; see also [announcement on Tao's blog](https://terrytao.wordpress.com/2018/01/19/the-de-bruijn-newman-constant-is-non-negativ/), January 19, 2018
* Rosser, J. Barkley; Yohe, J. M.; Schoenfeld, Lowell (1969). *Information Processing 68 (Proc. IFIP Congress, Edinburgh, 1968), Vol. 1: Mathematics, Software*. *North-Holland*, 70–76. [MR0258245](https://mathscinet.ams.org/mathscinet-getitem?mr=MR0258245).
* Rudin, Walter (January 1973). *Functional Analysis*. *McGraw-Hill*. ISBN 0-070-54225-2.
* Salem, Raphaël (1953). *Sur une proposition équivalente à l'hypothèse de Riemann*. *Les Comptes rendus de l'Académie des sciences* **236**, 1127–1128. [MR0053148](https://mathscinet.ams.org/mathscinet-getitem?mr=MR0053148).
* Sarnak, Peter (2005). *Problems of the Millennium: The Riemann Hypothesis (2004)*. *Clay Mathematics Institute*. [Problems of the Millennium: The Riemann Hypothesis (2004)](http://www.claymath.org/sites/default/files/sarnak_rh_0.pdf). Reprinted in Borwein, Peter; Ferguson, Ron; Mossinghoff, Michael J. (2008). *Sign changes in sums of the Liouville function*. *Mathematics of Computation* **77**(263), 1681–1694. [MR2398787](https://mathscinet.ams.org/mathscinet-getitem?mr=MR2398787). [2008MaCom..77.1681B](https://ui.adsabs.harvard.edu/abs/2008MaCom..77.1681B). doi:[10.1090/S0025-5718-08-02036-X](https://doi.org/10.1090/S0025-5718-08-02036-X)..
* Schoenfeld, Lowell (1976). *Sharper bounds for the Chebyshev functions θ(x) and ψ(x). II*. *Mathematics of Computation* **30**(134), 337–360. [MR0457374](https://mathscinet.ams.org/mathscinet-getitem?mr=MR0457374). [JSTOR 2005976](https://www.jstor.org/stable/2005976). doi:[10.2307/2005976](https://doi.org/10.2307/2005976).
* Schumayer, Daniel; Hutchinson, David A. W. (2011). *Physics of the Riemann Hypothesis*. *Reviews of Modern Physics* **83**(2), 307–330. [arXiv:1101.3116](https://arxiv.org/abs/1101.3116). [2011RvMP...83..307S](https://ui.adsabs.harvard.edu/abs/2011RvMP...83..307S). doi:[10.1103/RevModPhys.83.307](https://doi.org/10.1103/RevModPhys.83.307).
* Selberg, Atle (1942). *On the zeros of Riemann's zeta-function*. *SKR. Norske Vid. Akad. Oslo I.* **10**, 59 pp. [MR0010712](https://mathscinet.ams.org/mathscinet-getitem?mr=MR0010712).
* Selberg, Atle (1946). *Contributions to the theory of the Riemann zeta-function*. *Arch. Math. Naturvid.* **48**(5), 89–155. [MR0020594](https://mathscinet.ams.org/mathscinet-getitem?mr=MR0020594).
* Selberg, Atle (1956). *Harmonic analysis and discontinuous groups in weakly symmetric Riemannian spaces with applications to Dirichlet series*. *J. Indian Math. Soc.* **20**, 47–87. [MR0088511](https://mathscinet.ams.org/mathscinet-getitem?mr=MR0088511).
* Serre, Jean-Pierre (1969–1970). *Facteurs locaux des fonctions zeta des varietés algébriques (définitions et conjectures)*. *Séminaire Delange-Pisot-Poitou* **19**. [Facteurs locaux des fonctions zeta des varietés algébriques (définitions et conjectures)](https://eudml.org/doc/110758).
* Sheats, Jeffrey T. (1998). *The Riemann hypothesis for the Goss zeta function for F<sub>q</sub>[T]*. *Journal of Number Theory* **71**(1), 121–157. [MR1630979](https://mathscinet.ams.org/mathscinet-getitem?mr=MR1630979). [arXiv:math/9801158](https://arxiv.org/abs/math/9801158). doi:[10.1006/jnth.1998.2232](https://doi.org/10.1006/jnth.1998.2232).
* Siegel, C. L. (1932). *Über Riemanns Nachlaß zur analytischen Zahlentheorie*. *Quellen Studien zur Geschichte der Math. Astron. Und Phys. Abt. B: Studien 2*, 45–80. Reprinted in Gesammelte Abhandlungen, Vol. 1. Berlin: Springer-Verlag, 1966. Translation availabke at Carl, Siegel (11 October 2018). *On Riemanns Nachlass for Analytic Number Theory*. [arXiv:1810.05198](https://arxiv.org/abs/1810.05198).
* Speiser, Andreas (1934). *Geometrisches zur Riemannschen Zetafunktion*. *Mathematische Annalen* **110**, 514–521. doi:[10.1007/BF01448042](https://doi.org/10.1007/BF01448042). [Geometrisches zur Riemannschen Zetafunktion](https://web.archive.org/web/20150627115412/http://gdz.sub.uni-goettingen.de/index.php?id=11&PPN=PPN235181684_0110&DMDID=DMDLOG_0032&L=1).
* Spira, Robert (1968). *Zeros of sections of the zeta function. II*. *Mathematics of Computation* **22**(101), 163–173. [MR0228456](https://mathscinet.ams.org/mathscinet-getitem?mr=MR0228456). [JSTOR 2004774](https://www.jstor.org/stable/2004774). doi:[10.2307/2004774](https://doi.org/10.2307/2004774).
* Stein, William; Mazur, Barry (2007). *What is Riemann's Hypothesis?*. [What is Riemann's Hypothesis?](https://web.archive.org/web/20090327181331/http://modular.math.washington.edu/edu/2007/simuw07/notes/rh.pdf).
* Suzuki, Masatoshi (2011). *Positivity of certain functions associated with analysis on elliptic surfaces*. *Journal of Number Theory* **131**(10), 1770–1796. doi:[10.1016/j.jnt.2011.03.007](https://doi.org/10.1016/j.jnt.2011.03.007).
* Titchmarsh, Edward Charles (1935). *The Zeros of the Riemann Zeta-Function*. *Proceedings of the Royal Society of London. Series A, Mathematical and Physical Sciences* **151**(873), 234–255. [JSTOR 96545](https://www.jstor.org/stable/96545). [1935RSPSA.151..234T](https://ui.adsabs.harvard.edu/abs/1935RSPSA.151..234T). doi:[10.1098/rspa.1935.0146](https://doi.org/10.1098/rspa.1935.0146).
* Titchmarsh, Edward Charles (1936). *The Zeros of the Riemann Zeta-Function*. *Proceedings of the Royal Society of London. Series A, Mathematical and Physical Sciences* **157**(891), 261–263. [arXiv:1004.4143](https://arxiv.org/abs/1004.4143). [JSTOR 96692](https://www.jstor.org/stable/96692). [1936RSPSA.157..261T](https://ui.adsabs.harvard.edu/abs/1936RSPSA.157..261T). doi:[10.1098/rspa.1936.0192](https://doi.org/10.1098/rspa.1936.0192).
* Titchmarsh, Edward Charles (1986). *The theory of the Riemann zeta-function*. *The Clarendon Press Oxford University Press*. ISBN 978-0-19-853369-6. [MR882550](https://mathscinet.ams.org/mathscinet-getitem?mr=MR882550).
* Trudgian, Timothy S. (2014). *An improved upper bound for the argument of the Riemann zeta function on the critical line II*. *J. Number Theory* **134**, 280–292. [arXiv:1208.5846](https://arxiv.org/abs/1208.5846). doi:[10.1016/j.jnt.2013.07.017](https://doi.org/10.1016/j.jnt.2013.07.017).
* Trudgian, Timothy (2011). *On the success and failure of Gram's Law and the Rosser Rule*. *Acta Arithmetica* **125**(3), 225–256. doi:[10.4064/aa148-3-2](https://doi.org/10.4064/aa148-3-2).
* Turán, Paul (1948). *On some approximative Dirichlet-polynomials in the theory of the zeta-function of Riemann*. *Danske Vid. Selsk. Mat.-Fys. Medd.* **24**(17), 36. [MR0027305](https://mathscinet.ams.org/mathscinet-getitem?mr=MR0027305). Reprinted in Borwein, Peter; Ferguson, Ron; Mossinghoff, Michael J. (2008). *Sign changes in sums of the Liouville function*. *Mathematics of Computation* **77**(263), 1681–1694. [MR2398787](https://mathscinet.ams.org/mathscinet-getitem?mr=MR2398787). [2008MaCom..77.1681B](https://ui.adsabs.harvard.edu/abs/2008MaCom..77.1681B). doi:[10.1090/S0025-5718-08-02036-X](https://doi.org/10.1090/S0025-5718-08-02036-X)..
* Turing, Alan M. (1953). *Some calculations of the Riemann zeta-function*. *Proceedings of the London Mathematical Society* **3**, 99–117. [MR0055785](https://mathscinet.ams.org/mathscinet-getitem?mr=MR0055785). doi:[10.1112/plms/s3-3.1.99](https://doi.org/10.1112/plms/s3-3.1.99).
* de la Vallée-Poussin, Ch.J. (1896). *Recherches analytiques sur la théorie des nombres premiers*. *Ann. Soc. Sci. Bruxelles* **20**, 183–256.
* de la Vallée-Poussin, Ch.J. (1899–1900). *Sur la fonction ζ(s) de Riemann et la nombre des nombres premiers inférieurs à une limite donnée*. *Mem. Couronnes Acad. Sci. Belg.* **59**(1). Reprinted in Borwein, Peter; Ferguson, Ron; Mossinghoff, Michael J. (2008). *Sign changes in sums of the Liouville function*. *Mathematics of Computation* **77**(263), 1681–1694. [MR2398787](https://mathscinet.ams.org/mathscinet-getitem?mr=MR2398787). [2008MaCom..77.1681B](https://ui.adsabs.harvard.edu/abs/2008MaCom..77.1681B). doi:[10.1090/S0025-5718-08-02036-X](https://doi.org/10.1090/S0025-5718-08-02036-X)..
* Weil, André (1948). *Sur les courbes algébriques et les variétés qui s'en déduisent*. *Hermann et Cie., Paris*. [MR0027151](https://mathscinet.ams.org/mathscinet-getitem?mr=MR0027151).
* Weil, André (1949). *Numbers of solutions of equations in finite fields*. *Bulletin of the American Mathematical Society* **55**(5), 497–508. [MR0029393](https://mathscinet.ams.org/mathscinet-getitem?mr=MR0029393). doi:[10.1090/S0002-9904-1949-09219-4](https://doi.org/10.1090/S0002-9904-1949-09219-4). Reprinted in Oeuvres Scientifiques/Collected Papers by Andre Weil ISBN 0-387-90330-5
* Weinberger, Peter J. (1973). *Analytic number theory ( St. Louis Univ., 1972)*. *Amer. Math. Soc.* **24**, 321–332. [MR0337902](https://mathscinet.ams.org/mathscinet-getitem?mr=MR0337902).
* Wiles, Andrew (2000). *Mathematics: frontiers and perspectives*. *American Mathematical Society*, 329–342. ISBN 978-0-8218-2697-3. [MR1754786](https://mathscinet.ams.org/mathscinet-getitem?mr=MR1754786).
* Zagier, Don (1977). *The first 50 million prime numbers*. *Math. Intelligencer* **1**, 7–19. [MR643810](https://mathscinet.ams.org/mathscinet-getitem?mr=MR643810). doi:[10.1007/BF03039306](https://doi.org/10.1007/BF03039306). [The first 50 million prime numbers](https://web.archive.org/web/20090327181245/http://modular.math.washington.edu/edu/2007/simuw07/misc/zagier-the_first_50_million_prime_numbers.pdf).
* Zagier, Don (1981). *Automorphic forms, representation theory and arithmetic (Bombay, 1979)*. *Tata Inst. Fundamental Res., Bombay* **10**, 275–301. [MR633666](https://mathscinet.ams.org/mathscinet-getitem?mr=MR633666).

### Popular expositions

* Sabbagh, Karl (2003a). *The greatest unsolved problem in mathematics*. *Farrar, Straus and Giroux, New York*. ISBN 978-0-374-25007-2. [MR1979664](https://mathscinet.ams.org/mathscinet-getitem?mr=MR1979664). [The greatest unsolved problem in mathematics](https://archive.org/details/riemannhypothesi00sabb).
* Sabbagh, Karl (2003b). *Dr. Riemann's zeros*. *Atlantic Books, London*. ISBN 978-1-843-54101-1. [Dr. Riemann's zeros](https://books.google.com/books?id=JesSAQAAMAAJ).
* du Sautoy, Marcus (2003). *The music of the primes*. *HarperCollins Publishers*. ISBN 978-0-06-621070-4. [MR2060134](https://mathscinet.ams.org/mathscinet-getitem?mr=MR2060134). [The music of the primes](https://archive.org/details/musicofprimessea00dusa).
* Rockmore, Dan (2005). *Stalking the Riemann hypothesis*. *Pantheon Books*. ISBN 978-0-375-42136-5. [MR2269393](https://mathscinet.ams.org/mathscinet-getitem?mr=MR2269393). [Stalking the Riemann hypothesis](https://archive.org/details/stalkingriemannh00danr).
* Derbyshire, John (2003). *Prime Obsession*. *Joseph Henry Press, Washington, DC*. ISBN 978-0-309-08549-6. [MR1968857](https://mathscinet.ams.org/mathscinet-getitem?mr=MR1968857).
* Watkins, Matthew (2015). *Mystery of the Prime Numbers*. *Liberalis Books*. ISBN 978-1782797814. [MR0000000](https://mathscinet.ams.org/mathscinet-getitem?mr=MR0000000).
* [Frenkel, Edward](https://en.wikipedia.org/wiki/Edward_Frenkel) (2014), [The Riemann Hypothesis](https://www.youtube.com/watch?v=d6c6uIyieoo) [Numberphile](https://en.wikipedia.org/wiki/Numberphile), Mar 11, 2014 (video)
* Nahin, Paul J. (2021). *In Pursuit of Zeta-3: The World's Most Mysterious Unsolved Math Problem*. *Princeton University Press*. ISBN 978-0691206073.

Note: Derbyshire 2003, Rockmore 2005, Sabbagh 2003a, Sabbagh 2003b, Sautoy 2003, and Watkins 2015 are non-technical. Edwards 1974, Patterson 1988, Borwein/Choi/Rooney/Weirathmueller 2008, Mazur/Stein 2015, Broughan 2017, and Nahin 2021 give mathematical introductions. Titchmarsh 1986, Ivić 1985, and Karatsuba/Voronin 1992 are advanced [monograph](https://en.wikipedia.org/wiki/monograph)s.

## External links

*

* [American Institute of Mathematics](https://en.wikipedia.org/wiki/American_Institute_of_Mathematics), [Riemann hypothesis](http://www.aimath.org/WWN/rh/)
* [Zeroes database](https://www.lmfdb.org/zeros/zeta/), 103 800 788 359 zeroes
* Apostol, Tom. *Where are the zeros of zeta of s?*. [Where are the zeros of zeta of s?](http://www.math.wisc.edu/~robbin/funnysongs.html#Zeta). Poem about the Riemann hypothesis, [sung](http://www.olimu.com/RIEMANN/Song.htm) by [John Derbyshire](https://en.wikipedia.org/wiki/John_Derbyshire).
* Borwein, Peter. *The Riemann Hypothesis*. [The Riemann Hypothesis](https://web.archive.org/web/20090327181245/http://oldweb.cecm.sfu.ca/~pborwein/COURSE/MATH08/LECTURE.pdf). (Slides for a lecture)
* Conrad, K. (2010). *Consequences of the Riemann hypothesis*. [Consequences of the Riemann hypothesis](https://mathoverflow.net/q/17232).
* Conrey, J. Brian; Farmer, David W. *Equivalences to the Riemann hypothesis*. [Equivalences to the Riemann hypothesis](https://web.archive.org/web/20100316235054/http://aimath.org/pl/rhequivalences).
* Gourdon, Xavier; Sebah, Pascal (2004). *Computation of zeros of the Zeta function*. [Computation of zeros of the Zeta function](http://numbers.computation.free.fr/Constants/Miscellaneous/zetazeroscompute.html). (Reviews the GUE hypothesis, provides an extensive bibliography as well).
* Odlyzko, Andrew. *Home page*. [Home page](http://www.dtc.umn.edu/~odlyzko/). including [papers on the zeros of the zeta function](http://www.dtc.umn.edu/~odlyzko/doc/zeta.html) and [tables of the zeros of the zeta function](http://www.dtc.umn.edu/~odlyzko/zeta_tables/index.html)
* Odlyzko, Andrew (2002). *Zeros of the Riemann zeta function: Conjectures and computations*. [Zeros of the Riemann zeta function: Conjectures and computations](http://www.dtc.umn.edu/~odlyzko/talks/riemann-conjectures.pdf). Slides of a talk
* Pegg, Ed (2004). *Ten Trillion Zeta Zeros*. *Math Games website*. [Ten Trillion Zeta Zeros](https://web.archive.org/web/20041102173644/http://www.maa.org/editorial/mathgames/mathgames_10_18_04.html).. A discussion of Xavier Gourdon's calculation of the first ten trillion non-trivial zeros
* Rubinstein, Michael. *algorithm for generating the zeros*. [algorithm for generating the zeros](https://web.archive.org/web/20070427221654/http://pmmac03.math.uwaterloo.ca/~mrubinst/l_function_public/L.html)..
* du Sautoy, Marcus (2006). *Prime Numbers Get Hitched*. *Seed Magazine*. [Prime Numbers Get Hitched](https://web.archive.org/web/20170922145127/http://seedmagazine.com/content/article/prime_numbers_get_hitched/).
* Watkins, Matthew R. (2021-02-27). *Proposed (dis)proofs of the Riemann Hypothesis*. [Proposed (dis)proofs of the Riemann Hypothesis](https://empslocal.ex.ac.uk/people/staff/mrwatkin//zeta/RHproofs.htm).
* *[Zetagrid](https://web.archive.org/web/20131005173705/http://www.zetagrid.net/)* (2002) A distributed computing project that attempted to disprove Riemann's hypothesis; closed in November 2005
