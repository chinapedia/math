---
title: Siegel zero
---

In [mathematics](https://en.wikipedia.org/wiki/mathematics), more specifically in the field of [analytic number theory](https://en.wikipedia.org/wiki/analytic_number_theory), a **Landau–Siegel zero** or simply **Siegel zero**, also known as an **exceptional zero**,[^1] named after [Edmund Landau](https://en.wikipedia.org/wiki/Edmund_Landau) and [Carl Ludwig Siegel](https://en.wikipedia.org/wiki/Carl_Ludwig_Siegel), is a type of potential [counterexample](https://en.wikipedia.org/wiki/counterexample) to the [generalized Riemann hypothesis](https://en.wikipedia.org/wiki/generalized_Riemann_hypothesis), on the zeros of [Dirichlet L-function](https://en.wikipedia.org/wiki/Dirichlet_L-function)s associated to [quadratic number field](https://en.wikipedia.org/wiki/quadratic_number_field)s. Roughly speaking, these are possible zeros very near (in a quantifiable sense) to $s=1$.

## Motivation and definition

The way in which Siegel zeros appear in the theory of Dirichlet L-functions is as potential exceptions to the [classical zero-free regions](https://en.wikipedia.org/wiki/Dirichlet_L-function#Zeros), which can only occur when the L-function is associated to a real [Dirichlet character](https://en.wikipedia.org/wiki/Dirichlet_character).

### Real primitive Dirichlet characters

For an integer $q ≥ 1$, a **Dirichlet character** modulo $q$ is an [arithmetic function](https://en.wikipedia.org/wiki/arithmetic_function) $\chi\colon \mathbb{Z}\to\mathbb{C}$ satisfying the following properties:
* [Completely multiplicative](https://en.wikipedia.org/wiki/Completely_multiplicative): $\chi(mn) = \chi(m)\chi(n)$ for every $m$, $n$;
* [Periodic](https://en.wikipedia.org/wiki/Periodic_function): $\chi(n+q) = \chi(n)$ for every $n$;
* Support: $\chi(n) = 0$ [if and only if](https://en.wikipedia.org/wiki/if_and_only_if) $\mathrm{gcd}(n,q) > 1$.
That is, $χ$ is the lifting of a [homomorphism](https://en.wikipedia.org/wiki/homomorphism) $\widetilde{\chi}:(\mathbb{Z}/q\mathbb{Z})^{\times} \to \mathbb{C}^{*}$.

The **trivial** character is the character modulo 1, and the **principal** character modulo $q$, denoted $\chi_0~(\mathrm{mod}~q)$, is the lifting of the trivial homomorphism $(\mathbb{Z}/q\mathbb{Z})^{\times}\ni a \mapsto 1 \in \mathbb{C}^{*}$.

A character $\chi~(\mathrm{mod}~{q})$ is called **imprimitive** if there exists some integer $d\neq q$ with $d\mid q$ such that the induced homomorphism $\widetilde{\chi}\colon (\mathbb{Z}/q\mathbb{Z})^{\times} \to \mathbb{C}^{*}$ factors as
:

$$
(\mathbb{Z}/q\mathbb{Z})^{\times}\twoheadrightarrow (\mathbb{Z}/d\mathbb{Z})^{\times} \xrightarrow{\widetilde{\chi'}} \mathbb{C}^{*}
$$

for some character $\chi'~(\mathrm{mod}~{d})$; otherwise, $\chi~(\mathrm{mod}~{q})$ is called **primitive**.

A character $\chi$ is **real** (or **quadratic**) if it equals its [complex conjugate](https://en.wikipedia.org/wiki/complex_conjugate) $\overline{\chi}$ (defined as $\overline{\chi}(n) := \overline{\chi(n)}$), or equivalently if $\chi^2 = \chi_0$. The *real primitive Dirichlet characters* are in one-to-one correspondence with the [Kronecker symbol](https://en.wikipedia.org/wiki/Kronecker_symbol)s $(D|\,\cdot\,): \mathbb{Z} \to \{-1,0,1\}$ for $D\in\mathbb{Z}$ a [fundamental discriminant](https://en.wikipedia.org/wiki/fundamental_discriminant) (i.e., the discriminant of a [quadratic number field](https://en.wikipedia.org/wiki/quadratic_number_field)).[^2] One way to define $(D|\,\cdot\,)$ is as the completely multiplicative arithmetic function determined by (for $p$ prime):
:

$$
\bigg(\frac{D}{p}\bigg)=\begin{cases}1, &(p)\text{ splits in } \mathbb{Q}(\sqrt{D}), \\ -1, &(p)\text{ is inert } \cdots, \\ 0, &(p)\text{ ramifies } \cdots, \end{cases} \quad \bigg(\frac{D}{-1}\bigg) = \text{sign of } D.
$$

It is thus common to write $\chi_D := (D|\,\cdot\,)$, which are real primitive characters modulo $|D|$.

### Classical zero-free regions

The **Dirichlet L-function** associated to a character $\chi~(\mathrm{mod}~q)$ is defined as the [analytic continuation](https://en.wikipedia.org/wiki/analytic_continuation) of the [Dirichlet series](https://en.wikipedia.org/wiki/Dirichlet_series) $L(s,\chi) = \sum_{n\geq 1} \chi(n) n^{-s}$ defined for $\mathrm{Re}(s)>1$, where *s* is a [complex variable](https://en.wikipedia.org/wiki/complex_variable). For $\chi$ non-principal, this continuation is [entire](https://en.wikipedia.org/wiki/Entire_function); otherwise it has a [simple pole](https://en.wikipedia.org/wiki/Zeros_and_poles) of [residue](https://en.wikipedia.org/wiki/Residue_%28complex_analysis%29) $\prod_{p\mid q}(1-p^{-1})$ at $s = 1$ as its only singularity. For $\mathrm{Re}(s)>1$, Dirichlet L-functions can be expanded into an [Euler product](https://en.wikipedia.org/wiki/Euler_product) $L(s,\chi) = \prod_{p} (1 - \chi(p)p^{-s})^{-1}$, from where it follows that $L(s,\chi)$ has no zeros in this region. The [prime number theorem for arithmetic progressions](https://en.wikipedia.org/wiki/Prime_number_theorem#Prime_number_theorem_for_arithmetic_progressions) is equivalent (in a certain sense) to $L(1+it,\chi) \neq 0$ ( $\forall t\in\mathbb{R}$). Moreover, via the [functional equation](https://en.wikipedia.org/wiki/Dirichlet_L-function#Functional_equation), we can reflect these regions through $s\mapsto 1-s$ to conclude that, with the exception of negative integers of same parity as $χ$,[^3] all the other zeros of $L(s,\chi)$ must lie inside $\{0<\mathrm{Re}(s)<1\}$. This region is called the **critical strip**, and zeros in this region are called **non-trivial zeros**.

The classical theorem on zero-free regions (Grönwall,[^4] Landau,[^5] Titchmarsh[^6]) states that there exists an
effectively computable real number $A>0$ such that, writing $s=\sigma + it$ for the complex variable, the function $L(s,\chi)$ has no zeros in the region
:

$$
\sigma > 1 - \frac{A}{\log q + \log (|t|+2)}
$$

if $\chi~(\mathrm{mod}~q)$ is non-real. If $\chi$ is real, then there is at most one zero in this region, which must necessarily be *real* and *simple*. This possible zero is the so-called **Siegel zero**.

The [generalized Riemann hypothesis](https://en.wikipedia.org/wiki/generalized_Riemann_hypothesis) (GRH) claims that for every $\chi~(\mathrm{mod}~q)$, all the non-trivial zeros of $L(s,\chi)$ lie on the line $\mathrm{Re}(s)=\frac{1}{2}$.

### Defining "Siegel zeros"

The definition of Siegel zeros as presented ties it to the constant $A$ in the zero-free region. This often makes it tricky to deal with these objects, since in many situations the particular value of the constant $A$ is of little concern.[^1] Hence, it is usual to work with more definite statements, either asserting or denying, the existence of an *infinite* family of such zeros, such as in:
* **Conjecture** ("no Siegel zeros"): *If $\beta_D$* denotes the largest real zero of $L(s,\chi_D)$, then $1-\beta_D \gg \frac{1}{\log|D|}.$

The possibility of existence or non-existence of Siegel zeros has a large impact in closely related subjects of number theory, with the "no Siegel zeros" conjecture serving as a weaker (although powerful, and sometimes fully sufficient) substitute for GRH (see below for an example involving Siegel–Tatsuzawa's Theorem and the [idoneal number](https://en.wikipedia.org/wiki/idoneal_number) problem). An equivalent formulation of "no Siegel zeros" that does not reference zeros explicitly is the statement:
:

$$
\frac{L'}{L}(1,\chi_D) = O(\log|D|).
$$

The equivalence can be deduced for example by using the zero-free regions and classical estimates for the number of non-trivial zeros of $L(s,\chi)$ up to a certain height.[^7]

## Landau–Siegel estimates

The first breakthrough in dealing with these zeros came from Landau, who showed that there exists an effectively computable constant $B>0$ such that, for any $\chi_D$ and $\chi_{D'}$ real primitive characters to distinct moduli, if $\beta, \beta'$ are real zeros of $L(s,\chi_D), L(s,\chi_{D'})$ respectively, then
:

$$
\min\{\beta,\beta'\} < 1- \frac{B}{\log|DD'|}.
$$

This is saying that, if Siegel zeros exist, then they cannot be too numerous. The way this is proved is via a 'twisting' argument, which lifts the problem to the [Dedekind zeta function](https://en.wikipedia.org/wiki/Dedekind_zeta_function) of the [biquadratic field](https://en.wikipedia.org/wiki/biquadratic_field) $\mathbb{Q}(\sqrt{D},\sqrt{D'})$. This technique is still largely applied in modern works.

This 'repelling effect' (see [Deuring–Heilbronn phenomenon](https://en.wikipedia.org/wiki/Deuring%E2%80%93Heilbronn_phenomenon)), after more careful analysis, led Landau to his 1936 theorem,[^8] which states that for every $\varepsilon > 0$, there is $C(\varepsilon)\in\mathbb{R}_{+}$ such that, if $\beta$ is a real zero of $L(s,\chi_D)$, then $\beta < 1 - C(\varepsilon)|D|^{-\frac{3}{8} - \varepsilon}$. However, in the same year, in the same issue of the same journal, Siegel[^9] directly improved this estimate to
:

$$
\beta < 1 - C(\varepsilon)|D|^{-\varepsilon}.
$$

Both Landau's and Siegel's proofs provide no explicit way to calculate $C(\varepsilon)\in\mathbb{R}_{+}$, thus being instances of an [ineffective result](https://en.wikipedia.org/wiki/Effective_results_in_number_theory).

### Siegel–Tatsuzawa theorem

In 1951, [Tikao Tatsuzawa](https://en.wikipedia.org/wiki/Tikao_Tatsuzawa) proved an 'almost' effective version of Siegel's theorem,[^10] showing that for any fixed $0 < \varepsilon < \frac{1}{11.2}$, if $|D| > e^{1/\varepsilon}$ then
:

$$
L(1,\chi_D) > 0.655\varepsilon|D|^{-\varepsilon},
$$

*with the possible exception of at most one fundamental discriminant.* Using the 'almost effectivity' of this result, [P. J. Weinberger](https://en.wikipedia.org/wiki/Peter_J._Weinberger) (1973)[^11] showed that Euler's list of 65 [idoneal number](https://en.wikipedia.org/wiki/idoneal_number)s is complete except for at most two elements.[^12]

## Relation to quadratic fields

Siegel zeros often appear as more than an artificial issue in the argument for deducing zero-free regions, since zero-free region estimates enjoy deep connections to the arithmetic of quadratic fields. For instance, the identity $\zeta_{\mathbb{Q}(\sqrt{D})}(s) = \zeta(s) L(s,\chi_D)$ can be interpreted as an analytic formulation of [quadratic reciprocity](https://en.wikipedia.org/wiki/quadratic_reciprocity) (see [Artin reciprocity law §Statement in terms of L-functions](https://en.wikipedia.org/wiki/Artin_reciprocity_law#Statement_in_terms_of_L-functions)). The precise relation between the distribution of zeros near $s = 1$ and arithmetic comes from [Dirichlet's class number formula](https://en.wikipedia.org/wiki/Class_number_formula#Dirichlet_class_number_formula):
:

$$
L(1,\chi_D) =
\begin{cases} \dfrac{2 \pi}{w_D \sqrt{|D|}}  \, h(D), &\text{if } D < 0 \\[.5em]
\dfrac{\log\varepsilon_D}{\sqrt{D}}\, h(D), &\text{if } D > 0,
\end{cases}
$$

where:
* $h(D)$ is the [ideal class number](https://en.wikipedia.org/wiki/Ideal_class_group#Properties) of $\mathbb{Q}(\sqrt{D})$;
* $w_D$ is the number of [roots of unity](https://en.wikipedia.org/wiki/roots_of_unity) in $\mathbb{Q}(\sqrt{D})$ ( $D < 0$);
* $\varepsilon_D$ is the [fundamental unit](https://en.wikipedia.org/wiki/Fundamental_unit_%28number_theory%29) of $\mathbb{Q}(\sqrt{D})$ ( $D > 0$).
This way, estimates for the largest real zero of $L(s,\chi_D)$ can be translated into estimates for $L(1,\chi_D)$ (via, for example, the fact that $|L'(\sigma,\chi)| = O(\log^2 q)$ for $1-\frac{1}{\log q} \leq \sigma \leq 1$),[^13] which in turn become estimates for $h(D)$. Classical works in the subject treat these three quantities essentially interchangeably, although the case $D > 0$ brings additional complications related to the fundamental unit.

### Siegel zeros as 'quadratic phenomena'

There is a sense in which the difficulty associated to the phenomenon of Siegel zeros in general is entirely restricted to quadratic extensions. It is a consequence of the [Kronecker–Weber theorem](https://en.wikipedia.org/wiki/Kronecker%E2%80%93Weber_theorem), for example, that the [Dedekind zeta function](https://en.wikipedia.org/wiki/Dedekind_zeta_function) $\zeta_{K}(s) = \sum_{I\subseteq \mathfrak{O}_K} [\mathfrak{O}_K: I]^{-s}$ of an [abelian number field](https://en.wikipedia.org/wiki/Abelian_extension) $K/\mathbb{Q}$ can be written as a product of Dirichlet L-functions.[^14] Thus, if $\zeta_{K}(s)$ has a Siegel zero, there must be some subfield $F\subseteq K$ with $[F:\mathbb{Q}] = 2$ such that $\zeta_{F}(s)$ has a Siegel zero.

While for the non-abelian case $\zeta_{K}(s)$ can only be factored into more complicated [Artin L-function](https://en.wikipedia.org/wiki/Artin_L-function)s, the same is true:

* **Theorem** ([Stark](https://en.wikipedia.org/wiki/Harold_Stark), 1974)**.**[^15] Let $K/\mathbb{Q}$ be a number field of degree $n > 1$. There is a constant $c(n)$ ( $= 4$ if $K/\mathbb{Q}$ is normal, $= 4n!$ otherwise) such that, if there is a real $\beta$ in the range
:

$$
1 - \frac{c(n)}{\log|\Delta_K|} \leq \beta < 1
$$

:with $\zeta_K(\beta) = 0$, then there is a quadratic subfield $F\subseteq K$ such that $\zeta_{F}(\beta)=0$. Here, $\Delta_K$ is the [field discriminant](https://en.wikipedia.org/wiki/Discriminant_of_an_algebraic_number_field) of the extension $K/\mathbb{Q}$.

## "No Siegel zeros" for *D* \< 0

When dealing with quadratic fields, the case $D>0$ tends to be elusive due to the behaviour of the fundamental unit. Thus, it is common to treat the cases $D<0$ and $D>0$ separately. Much more is known for the negative discriminant case:

### Lower bounds for *h*(*D*)

In 1918, [Erich Hecke](https://en.wikipedia.org/wiki/Erich_Hecke) showed that "no Siegel zeros" for $D<0$ implies that $h(D) \gg \sqrt{|D|}(\log|D|)^{-1}$[^5] (see [Class number problem](https://en.wikipedia.org/wiki/Class_number_problem) for comparison). This can be extended to an equivalence, as it is a consequence of Theorem 3 in [Granville](https://en.wikipedia.org/wiki/Andrew_Granville)–[Stark](https://en.wikipedia.org/wiki/Harold_Stark) (2000):[^16]
:

$$
\text{“No Siegel zeros” for } D<0 \quad\iff\quad h(D) \gg \frac{\sqrt{|D|}}{\log|D|}\sum_{(a,b,c)} \frac{1}{a},
$$

where the summation runs over the [reduced](https://en.wikipedia.org/wiki/Binary_quadratic_form#Reduction_and_class_numbers) [binary quadratic form](https://en.wikipedia.org/wiki/binary_quadratic_form)s $ax^2 + bxy + cy^2$ of discriminant $D$. Using this, Granville and Stark showed that a certain uniform formulation of the [abc conjecture](https://en.wikipedia.org/wiki/abc_conjecture) for number fields implies "no Siegel zeros" for negative discriminants.

In 1976, [Dorian Goldfeld](https://en.wikipedia.org/wiki/Dorian_Goldfeld)[^17] proved the following unconditional, effective lower bound for $h(D)$:
:

$$
h(D) \gg \prod_{p\mid D} \bigg(1-\frac{2\sqrt{p}}{p+1}\bigg)\, \log|D|.
$$

### Complex multiplication

Another equivalence for "no Siegel zeros" for $D<0$ can be given in terms of [upper bounds](https://en.wikipedia.org/wiki/Upper_and_lower_bounds) for [heights](https://en.wikipedia.org/wiki/Height_function) of [singular moduli](https://en.wikipedia.org/wiki/Complex_multiplication#Singular_moduli):
:

$$
h(j(\tau_D)) \ll \log|D|,
$$

where:
* $h$ is the absolute [logarithmic naïve height](https://en.wikipedia.org/wiki/Height_function#Height_functions_in_Diophantine_geometry) for number fields;
* $j$ is the [j-invariant function](https://en.wikipedia.org/wiki/j-invariant);
* $\tau_D := (D+\sqrt{D})/2$.
The number $j(\tau_D)$ generates the [Hilbert class field](https://en.wikipedia.org/wiki/Hilbert_class_field) of $\mathbb{Q}(\sqrt{D})$, which is its maximal unramified abelian extension.[^18] This equivalence is a direct consequence of the results in Granville–Stark (2000),[^16] and can be seen in C. Táfula (2019).[^19]

A precise relation between heights and values of L-functions was obtained by [Pierre Colmez](https://en.wikipedia.org/wiki/Pierre_Colmez) (1993,[^20] 1998[^21]), who showed that, for an elliptic curve $E_D/\mathbb{C}$ with [complex multiplication](https://en.wikipedia.org/wiki/complex_multiplication) by $\mathbb{Z}[\tau_D]$, we have
:

$$
-2 h_{\mathrm{Fal}}(E_D) - \frac{1}{2} \log|D| = \frac{L'}{L}(0,\chi_D) + \log 2\pi,
$$

where $h_{\mathrm{Fal}}$ denotes the [Faltings height](https://en.wikipedia.org/wiki/Height_function#Height_functions_in_Diophantine_geometry).[^22] Using the identities $h_{\mathrm{Fal}}(E_D) = \frac{1}{12}h(j(\tau_D)) + O(\log h(j(\tau_D)))$[^23] and $\frac{L'}{L}(1,\chi_D) = -\frac{L'}{L}(0,\chi_D) - \log|D| + \log 2\pi + \gamma$,[^24] Colmez' theorem also provides a proof for the equivalence above.

## Consequences of Siegel zeros existing

Although the [generalized Riemann hypothesis](https://en.wikipedia.org/wiki/generalized_Riemann_hypothesis) is expected to be true, since the "no Siegel zeros" conjecture remains open, it is interesting to study what consequences such severe counterexamples to the GRH would imply. Another reason to study this possibility is that the proof of certain unconditional theorems require the division into two cases: first a proof assuming no Siegel zeros exist, then another assuming Siegel zeros do exist. A classical theorem of this type is [Linnik's theorem](https://en.wikipedia.org/wiki/Linnik%27s_theorem) on the smallest [prime in an arithmetic progression](https://en.wikipedia.org/wiki/Primes_in_arithmetic_progression).

The following are some examples of facts that follow from the existence of Siegel zeros.

### Infinitude of twin primes

A striking result in this direction is [Roger Heath-Brown](https://en.wikipedia.org/wiki/Roger_Heath-Brown)'s 1983 result[^25] which, following [Terence Tao](https://en.wikipedia.org/wiki/Terence_Tao),[^26] can be stated as follows:
* **Theorem** (Heath-Brown, 1983)**.** At least one of the following is true: *(1)* There are no Siegel zeros. (*2)* There are infinitely many [twin prime](https://en.wikipedia.org/wiki/twin_prime)s.

### Parity problem

The parity problem in [sieve theory](https://en.wikipedia.org/wiki/sieve_theory) roughly refers to the fact that sieving arguments are, generally speaking, unable to tell if an integer has an even or odd number of prime divisors. This leads to many upper bounds in sieve estimates, such as the one from the [linear sieve](https://en.wikipedia.org/wiki/linear_sieve)[^27] being off by a factor of 2 from the expected value. In 2020, [Granville](https://en.wikipedia.org/wiki/Andrew_Granville)[^28] showed that under the assumption of the existence of Siegel zeros, the general upper bounds for the problem of sieving intervals are optimal, meaning that the extra factor of 2 coming from the parity phenomenon would thus not be an artificial limitation of the method.

## See also

* [Generalized Riemann hypothesis](https://en.wikipedia.org/wiki/Generalized_Riemann_hypothesis)
* [Deuring–Heilbronn phenomenon](https://en.wikipedia.org/wiki/Deuring%E2%80%93Heilbronn_phenomenon)
* [Class number problem](https://en.wikipedia.org/wiki/Class_number_problem)
* [Brauer–Siegel theorem](https://en.wikipedia.org/wiki/Brauer%E2%80%93Siegel_theorem)
* [Siegel–Walfisz theorem](https://en.wikipedia.org/wiki/Siegel%E2%80%93Walfisz_theorem)

## References

<references/>

* Davenport, H. (1980). *Multiplicative Number Theory*. ISBN 978-1-4757-5929-7. doi:[10.1007/978-1-4757-5927-3](https://doi.org/10.1007/978-1-4757-5927-3). [Multiplicative Number Theory](https://link.springer.com/book/10.1007/978-1-4757-5927-3).
* Iwaniec, H. (2006). *Analytic Number Theory: Lectures given at the C.I.M.E. Summer School held in Cetraro, Italy, July 11–18, 2002*. *Springer* **1891**, 97–132. ISBN 978-3-540-36364-4. doi:[10.1007/978-3-540-36364-4_3](https://doi.org/10.1007/978-3-540-36364-4_3).
*Montgomery, H. L.; Vaughan, R. C. (2006). *Multiplicative Number Theory I: Classical Theory*. *Cambridge University Press*. ISBN 978-0-521-84903-6. [Multiplicative Number Theory I: Classical Theory](https://www.cambridge.org/core/books/multiplicative-number-theory-i/4E45519B26115AEEA4839C6C38206ACD).
* Zagier, D. B. (1981). *Zetafunktionen und quadratische Körper: Eine Einführung in die höhere Zahlentheorie*. *Springer-Verlag*. ISBN 978-3-540-10603-6. [Zetafunktionen und quadratische Körper: Eine Einführung in die höhere Zahlentheorie](https://www.springer.com/de/book/9783540106036).

## Notes

[^1]: See Iwaniec (2006).
[^2]: See Satz 4, §5 of Zagier (1981).
[^3]: $χ (mod q)$ is *even* if $χ(-1) = 1$, and *odd* if $χ(-1) = -1$.
[^4]: Grönwall, T. H. (1913). *Sur les séries de Dirichlet correspondant à des charactères complexes*. *Rendiconti di Palermo* **35**, 145–159. doi:[10.1007/BF03015596](https://doi.org/10.1007/BF03015596).
[^5]: Landau, E. (1918). *Über die Klassenzahl imaginär-quadratischer Zahlkörper*. *Göttinger Nachrichten*, 285–295.
[^6]: Titchmarsh, E. C. (1930). *A divisor problem*. *Rendiconti di Palermo* **54**, 414–429. doi:[10.1007/BF03021203](https://doi.org/10.1007/BF03021203).
[^7]: See Chapter 16 of Davenport (1980).
[^8]: Landau, E. (1936). *Bemerkungen zum Heilbronnschen Satz*. *Acta Arithmetica*, 1–18.
[^9]: Siegel, C. L. (1935). *Über die Klassenzahl quadratischer Zahlkörper*. *Acta Arithmetica* **1**(1), 83–86. doi:[10.4064/aa-1-1-83-86](https://doi.org/10.4064/aa-1-1-83-86). [Über die Klassenzahl quadratischer Zahlkörper](http://pldml.icm.edu.pl/pldml/element/bwmeta1.element.bwnjournal-article-aav1i1p83bwm?q=bwmeta1.element.bwnjournal-number-aa-1935-1-1;6).
[^10]: Tatuzawa, T. (1951). *On a theorem of Siegel*. *Japanese Journal of Mathematics* **21**, 163–178. doi:[10.4099/jjm1924.21.0_163](https://doi.org/10.4099/jjm1924.21.0_163).
[^11]: Weinberger, P. J. (1973). *Exponents of the class group of complex quadratic fields*. *Acta Arithmetica* **22**(2), 117–124. doi:[10.4064/aa-22-2-117-124](https://doi.org/10.4064/aa-22-2-117-124).
[^12]: Kani, Ernst (2011). *Idoneal numbers and some generalizations*. *Annales des Sciences Mathématiques du Québec* **35**. [Idoneal numbers and some generalizations](http://www.labmath.uqam.ca/~annales/volumes/35-2/PDF/197-227.pdf).
[^13]: See (11) in Chapter 14 of Davenport (1980).
[^14]: Theorem 10.5.25 in Cohen, H. (2007). *Number Theory: Volume II: Analytic and Modern Tools*. *Springer-Verlag*. ISBN 978-0-387-49893-5. [Number Theory: Volume II: Analytic and Modern Tools](https://www.springer.com/gp/book/9780387498935)..
[^15]: Lemma 8 in Stark, H. M. (1974-06-01). *Some effective cases of the Brauer-Siegel Theorem*. *Inventiones Mathematicae* **23**(2), 135–152. [1974InMat..23..135S](https://ui.adsabs.harvard.edu/abs/1974InMat..23..135S). doi:[10.1007/BF01405166](https://doi.org/10.1007/BF01405166).
[^16]: Granville, A.; Stark, H.M. (2000-03-01). *ABC implies no "Siegel zeros" for L-functions of characters with negative discriminant*. *Inventiones Mathematicae* **139**(3), 509–523. [2000InMat.139..509G](https://ui.adsabs.harvard.edu/abs/2000InMat.139..509G). doi:[10.1007/s002229900036](https://doi.org/10.1007/s002229900036).
[^17]: Goldfeld, Dorian M. (1976). *The class number of quadratic fields and the conjectures of Birch and Swinnerton-Dyer*. *Annali della Scuola Normale Superiore di Pisa - Classe di Scienze* **3**(4), 623–663. [The class number of quadratic fields and the conjectures of Birch and Swinnerton-Dyer](http://www.numdam.org/item/?id=ASNSP_1976_4_3_4_623_0).
[^18]: Theorem II.4.1 in Silverman, Joseph H. (1994). *Advanced topics in the arithmetic of elliptic curves*. *Springer-Verlag* **151**. ISBN 978-0-387-94325-1..
[^19]: Táfula, C. (2021). *On Landau–Siegel zeros and heights of singular moduli*. *Acta Arithmetica* **201**, 1–28. [arXiv:1911.07215](https://arxiv.org/abs/1911.07215). doi:[10.4064/aa191118-18-5](https://doi.org/10.4064/aa191118-18-5).
[^20]: Colmez, Pierre (1993). *Periodes des Variétés Abéliennes à Multiplication Complexe*. *Annals of Mathematics* **138**(3), 625–683. [JSTOR 2946559](https://www.jstor.org/stable/2946559). doi:[10.2307/2946559](https://doi.org/10.2307/2946559).
[^21]: Colmez, Pierre (1998-05-01). *Sur la hauteur de Faltings des variétés abéliennes à multiplication complexe*. *Compositio Mathematica* **111**(3), 359–369. doi:[10.1023/A:1000390105495](https://doi.org/10.1023/A%3A1000390105495). [Sur la hauteur de Faltings des variétés abéliennes à multiplication complexe](https://www.cambridge.org/core/journals/compositio-mathematica/article/sur-la-hauteur-de-faltings-des-varietes-abeliennes-a-multiplication-complexe/AE329EE32B7B61AB1A95B308EEC4B5B6).
[^22]: See the diagram in subsection 0.6 of Colmez (1993). There is small typo in the upper right corner of this diagram, that should instead read " $-2 h_{\mathrm{Fal}}(X) - \frac{1}{2}\log D$".
[^23]: Proposition 2.1, Chapter X of (1986). *Arithmetic Geometry*. *Springer-Verlag*. ISBN 978-0-387-96311-2. [Arithmetic Geometry](https://www.springer.com/gp/book/9780387963112).
[^24]: Consequence of the [functional equation](https://en.wikipedia.org/wiki/Dirichlet_L-function#Functional_equation), where $γ = 0.57721...$ is the [Euler–Mascheroni constant](https://en.wikipedia.org/wiki/Euler%E2%80%93Mascheroni_constant).
[^25]: Heath-Brown, D. R. (1983-09-01). *Prime Twins and Siegel Zeros*. *Proceedings of the London Mathematical Society* **s3-47**(2), 193–224. doi:[10.1112/plms/s3-47.2.193](https://doi.org/10.1112/plms/s3-47.2.193). [Prime Twins and Siegel Zeros](https://academic.oup.com/plms/article/s3-47/2/193/1524169).
[^26]: (2015-08-27). *Heath-Brown's theorem on prime twins and Siegel zeroes*. *What's new*. [Heath-Brown's theorem on prime twins and Siegel zeroes](https://terrytao.wordpress.com/2015/08/26/heath-browns-theorem-on-prime-twins-and-siegel-zeroes/).
[^27]: See Chapter 9 of Nathanson, Melvyn B. (1996). *Additive Number Theory The Classical Bases*. *Springer-Verlag*. ISBN 978-0-387-94656-6. [Additive Number Theory The Classical Bases](https://www.springer.com/gp/book/9780387946566).
[^28]: Granville, A. (2020). *Sieving intervals and Siegel zeros*. [arXiv:2010.01211](https://arxiv.org/abs/2010.01211).
