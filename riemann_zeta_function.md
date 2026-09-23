---
title: ฟังก์ชันซีตาของรีมัน
---

<figure style={{"maxWidth": "250px"}}>

![The Riemann zeta function ζ(z) plotted with domain coloring](https://pub-275e30003c354ac0862cc9839e0f952a.r2.dev/docs/math/Cplot_zeta.svg.png)

<figcaption>

**ฟังก์ชันซีตาของรีมัน** (Riemann zeta function) $ζ(z)$ ที่พล็อตด้วย [การระบายสีโดเมน](https://en.wikipedia.org/wiki/domain_coloring)[^1]

</figcaption>

</figure>

<figure style={{"maxWidth": "200px"}}>

![The pole at z = 1 and two zeros on the critical line](https://pub-275e30003c354ac0862cc9839e0f952a.r2.dev/docs/math/Riemann-Zeta-Detail.png)

<figcaption>

ขั้วที่ $z = 1$ และศูนย์สองจุดบนเส้นวิกฤต

</figcaption>

</figure>
**ฟังก์ชันซีตาของรีมัน** หรือ **ฟังก์ชันซีตาของออยเลอร์–รีมัน** ซึ่งเขียนแทนด้วยตัวพิมพ์เล็ก [ตัวอักษรกรีก](https://en.wikipedia.org/wiki/Greek_alphabet) $ζ$ ([ซีตา](https://en.wikipedia.org/wiki/zeta)) เป็น [ฟังก์ชันทางคณิตศาสตร์](https://en.wikipedia.org/wiki/function_%28mathematics%29) ของ [ตัวแปรเชิงซ้อน](https://en.wikipedia.org/wiki/complex_variable) ที่นิยามว่า

$$
\zeta(s) = \sum_{n=1}^\infty \frac{1}{n^s} = \frac{1}{1^s} + \frac{1}{2^s} + \frac{1}{3^s} + \cdots
$$

สำหรับ $\mathrm{Re}(s) > 1$ และมีการต่อขยายเชิงวิเคราะห์ (analytic continuation) ที่อื่น ๆ.[^2]

**ฟังก์ชันซีตาของรีมัน** (Riemann zeta function) มีบทบาทสำคัญใน [ทฤษฎีจำนวนเชิงวิเคราะห์](https://en.wikipedia.org/wiki/analytic_number_theory) และมีประโยชน์ใน [ฟิสิกส์](https://en.wikipedia.org/wiki/physics), [ทฤษฎีความน่าจะเป็น](https://en.wikipedia.org/wiki/probability_theory), และ [สถิติศาสตร์](https://en.wikipedia.org/wiki/statistics) ที่ประยุกต์ใช้

[เลอ็อนฮาร์ท อ็อยเลอร์](https://en.wikipedia.org/wiki/Leonhard_Euler) เป็นผู้แนะนำและศึกษาฟังก์ชันดังกล่าวเหนือ [จำนวนจริง](https://en.wikipedia.org/wiki/real_numbers) ในครึ่งแรกของศตวรรษที่สิบแปด [แบร์นฮาร์ท รีมัน](https://en.wikipedia.org/wiki/Bernhard_Riemann) ได้ขยายนิยามของอ็อยเลอร์ไปสู่ตัวแปร [เชิงซ้อน](https://en.wikipedia.org/wiki/complex_number) ในบทความปี 1859 เรื่อง "[On the Number of Primes Less Than a Given Magnitude](https://en.wikipedia.org/wiki/On_the_Number_of_Primes_Less_Than_a_Given_Magnitude)" ซึ่งพิสูจน์การต่อขยายแบบ [meromorphic](https://en.wikipedia.org/wiki/meromorphic) และ [สมการเชิงฟังก์ชัน](https://en.wikipedia.org/wiki/functional_equation) และกำหนดความสัมพันธ์ระหว่าง [ค่าศูนย์ของฟังก์ชัน](https://en.wikipedia.org/wiki/Root_of_a_function) กับ [การกระจายตัวของจำนวนเฉพาะ](https://en.wikipedia.org/wiki/prime_number_theorem) บทความนี้ยังประกอบด้วย [สมมติฐานของรีมัน](https://en.wikipedia.org/wiki/Riemann_hypothesis) ซึ่งเป็น [ข้อความคาดการณ์](https://en.wikipedia.org/wiki/conjecture) เกี่ยวกับการกระจายตัวของค่าศูนย์เชิงซ้อนของฟังก์ชันซีตาของรีมัน ที่นักคณิตศาสตร์หลายคนถือว่าเป็นปัญหาที่ยังไม่ได้รับการแก้ไขที่สำคัญที่สุดใน [คณิตศาสตร์บริสุทธิ์](https://en.wikipedia.org/wiki/pure_mathematics)[^3]

**ฟังก์ชันซีตาของรีมัน** (Riemann zeta function) คือฟังก์ชันที่ค่าของมันที่จำนวนเต็มบวกคู่ถูกคำนวณโดยออยเลอร์ ค่าแรกคือ $ζ(2)$ ซึ่งให้คำตอบของ [ปัญหากาเซิล](https://en.wikipedia.org/wiki/Basel_problem) ในปี 1979 [โรเจอร์อาเพรี](https://en.wikipedia.org/wiki/Roger_Ap%C3%A9ry) พิสูจน์ว่า [ $ζ(3)$](https://en.wikipedia.org/wiki/Ap%C3%A9ry%27s_constant) เป็นจำนวนอตรรกยะ และเนื่องจากผลดังกล่าว จำนวนนี้จึงตั้งชื่อตามเขา ค่าที่จุดจำนวนเต็มลบ ซึ่งออยเลอร์ค้นพบเช่นกัน เป็น [จำนวนตรรกยะ](https://en.wikipedia.org/wiki/rational_number) และเล่นบทบาทสำคัญในทฤษฎีของ [รูปแบบมอดุลาร์](https://en.wikipedia.org/wiki/modular_form) [การสรุปทั่วไปหลายอย่าง](https://en.wikipedia.org/wiki/List_of_zeta_functions) ของฟังก์ชันซีตาของรีมัน เช่น [อนุกรมไดริชเล](https://en.wikipedia.org/wiki/Dirichlet_series) [ฟังก์ชัน $L$ ของไดริชเล](https://en.wikipedia.org/wiki/Dirichlet_L-function) และ [ฟังก์ชัน $L$](https://en.wikipedia.org/wiki/L-function) นั้นเป็นที่รู้จัก

## นิยาม

<figure>

![Bernhard Riemann's article On the number of primes below a given magnitude](https://pub-275e30003c354ac0862cc9839e0f952a.r2.dev/docs/math/Ueber_die_Anzahl_der_Primzahlen_unter_einer_gegebenen_Gr%C3%B6sse.pdf.jpg)

<figcaption>

**บทความของแบร์นฮาร์ท รีมันเรื่องจำนวนจำนวนเฉพาะที่น้อยกว่าขนาดที่กำหนด** (On the number of primes below a given magnitude) คือ……

</figcaption>

</figure>

ฟังก์ชันซีตาของรีมัน $ζ(s)$ คือฟังก์ชันของตัวแปรเชิงซ้อน $s = σ + it$ ซึ่ง $σ$ และ $t$ เป็นจำนวนจริน (สัญลักษณ์ $s$, $σ$, และ $t$ ถูกใช้แบบดั้งเดิมในการศึกษาฟังก์ชันซีตา ตามรีมันน์) เมื่อ $Re(s) = σ > 1$ ฟังก์ชันสามารถเขียนเป็นผลบวกที่ลู่เข้าหรือเป็นอินทิกรัลได้:

$$
\zeta(s) =\sum_{n=1}^\infty\frac{1}{n^s} = \frac{1}{\Gamma(s)} \int_0^\infty \frac{x ^ {s-1}}{e ^ x - 1} \, \mathrm{d}x\,,
$$

ที่

$$
\Gamma(s) = \int_0^\infty x^{s-1}\,e^{-x} \, \mathrm{d}x
$$

คือ [ฟังก์ชันแกมมา](https://en.wikipedia.org/wiki/gamma_function) ฟังก์ชันซิกมาของรีมันถูกนิยามสำหรับค่าเชิงซ้อนอื่นๆ ผ่าน [การวิเคราะห์เชิงซ้อน](https://en.wikipedia.org/wiki/analytic_continuation) ของฟังก์ชันที่นิยามสำหรับ $σ > 1$

[เลอ็อนฮาร์ท อ็อยเลอร์](https://en.wikipedia.org/wiki/Leonhard_Euler) พิจารณาระดับดังกล่าวในปี ค.ศ. 1740 สำหรับค่า $s$ ที่เป็นจำนวนเต็มบวก และต่อมา [เชบิเชฟ](https://en.wikipedia.org/wiki/Chebyshev) ขยายนิยามไปยัง $Re(s) > 1$.[^4]

อนุกรมข้างต้นเป็นอนุกรมไดริชเลต์  ที่ลู่เข้าสัมบูรณ์  ไปเป็นฟังก์ชันวิเคราะห์  สำหรับ $s$ ที่ทำให้ $σ > 1$ และลู่ออก  สำหรับค่าอื่น ๆ ของ $s$ ทั้งหมด ริมันน์แสดงว่าฟังก์ชันที่กำหนดโดยอนุกรมในระนาบครึ่งหนึ่งของจุดลู่เข้าสามารถขยายเชิงวิเคราะห์ไปยังค่าเชิงซ้อนทั้งหมด $s ≠ 1$ สำหรับ $s = 1$ อนุกรมคืออนุกรมฮาร์มอนิก  ซึ่งลู่ออกไปเป็น $+∞$ และ

$$
\lim_{s \to 1} (s - 1)\zeta(s) = 1.
$$

ดังนั้น ฟังก์ชันซีตาของรีมัน (Riemann zeta function) จึงเป็นฟังก์ชันที่มีขั้ว (meromorphic function) บนระนาบเชิงซ้อนทั้งระนาบ ซึ่ง [holomorphic](https://en.wikipedia.org/wiki/holomorphic_function) ทุกที่ ยกเว้นมี [simple pole](https://en.wikipedia.org/wiki/simple_pole) ที่ $s = 1$ โดยมี [residue](https://en.wikipedia.org/wiki/Residue_%28complex_analysis%29) เท่ากับ $1$

## สูตรผลคูณของออยเลอร์

ในปี ค.ศ. 1737 ออยเลอร์ได้ค้นพบความสัมพันธ์ระหว่างฟังก์ชันซีตาของรีมันกับจำนวนเฉพาะ ซึ่งเขาได้พิสูจน์เอกลักษณ์

$$
\sum_{n=1}^\infty\frac{1}{n^s} = \prod_{p \text{ prime}} \frac{1}{1-p^{-s}},
$$

โดยนิยามแล้ว ด้านซ้ายคือ $ζ(s)$ และผลคูณอนันต์ ด้านขวาขยายครอบคลุมจำนวนเฉพาะทั้งหมด $p$ (นิพจน์ลักษณะนี้เรียกว่า ผลคูณออยเลอร์):

$$
\prod_{p \text{ prime}} \frac{1}{1-p^{-s}} = \frac{1}{1-2^{-s}}\cdot\frac{1}{1-3^{-s}}\cdot\frac{1}{1-5^{-s}}\cdot\frac{1}{1-7^{-s}}\cdot\frac{1}{1-11^{-s}} \cdots \frac{1}{1-p^{-s}} \cdots
$$

ทั้งสองข้างของสูตรผลคูณของออยเลอร์ลู่เข้สำหรับ $Re(s) > 1$ การพิสูจน์ของ [เอกลักษณ์ของออยเลอร์](https://en.wikipedia.org/wiki/Proof_of_the_Euler_product_formula_for_the_Riemann_zeta_function) ใช้เพียงสูตรสำหรับ [อนุกรมเรขาคณิต](https://en.wikipedia.org/wiki/geometric_series) และ [ทฤษฎีบทหลักมูลของเลขคณิต](https://en.wikipedia.org/wiki/fundamental_theorem_of_arithmetic) เนื่องจาก [อนุกรมฮาร์มอนิก](https://en.wikipedia.org/wiki/harmonic_series_%28mathematics%29) ซึ่งได้มาเมื่อ $s = 1$ ล่อไป ดังนั้นสูตรของออยเลอร์ (ซึ่งกลายเป็น $Π_p p/p − 1$) จึงบ่งชี้ว่ามีความ [จำนวนเฉพาะจำนวนอนันต์](https://en.wikipedia.org/wiki/Euclid%27s_theorem) [^5] เนื่องจากลอการิทึมของ $p/(p − 1)$ มีค่าโดยประมาณเท่ากับ $1/p$ สูตรนี้จึงสามารถใช้พิสูจน์ผลลัพธ์ที่เข้มกว่านี้ได้ว่าผลรวมของส่วนกลับของจำนวนเฉพาะมีค่าอนันต์ ในทางกลับกัน การนำสิ่งนั้นมาผสมกับ [ตะแกรงของเอราทอสเทนีส](https://en.wikipedia.org/wiki/sieve_of_Eratosthenes) แสดงให้เห็นว่าความหนาแน่นของเซตของจำนวนเฉพาะภายในเซตของจำนวนเต็มบวกมีค่าเป็นศูนย์

สูตรผลคูณของออยเลอร์ (Euler product formula) สามารถนำมาใช้คำนวณความน่าจะเป็นเชิงเส้นกำกับ (asymptotic probability) ที่จำนวนเต็ม $s$ ตัวที่ถูกเลือกแบบสุ่มภายในขอบเขตหนึ่งจะเป็นจำนวนเฉพาะสัมพัทธ์ (coprime) ในเชิงประจักษ์ ความน่าจะเป็นที่จำนวนใดจำนวนหนึ่งจะหารด้วยจำนวนเฉพาะ (หรือจำนวนเต็มใดๆ) $p$ ลงตัวคือ $1/p$ ดังนั้น ความน่าจะเป็นที่จำนวน $s$ ตัวจะหารด้วยจำนวนเฉพาะนี้ลงตัวทั้งหมดคือ $1/p^{s}$ และความน่าจะเป็นที่อย่างน้อยหนึ่งตัวจะ *ไม่* หารลงตัวคือ $1 − 1/p^{s}$ ปัจจุบัน สำหรับจำนวนเฉพาะที่แตกต่างกัน เหตุการณ์การหารลงตัวเหล่านี้เป็นอิสระต่อกันอย่างสมบูรณ์ เนื่องจากตัวหารที่เป็นไปได้เป็นจำนวนเฉพาะสัมพัทธ์ (จำนวนหนึ่งจะหารด้วยตัวหารที่เป็นจำนวนเฉพาะสัมพัทธ์ $n$ และ $m$ [ก็ต่อเมื่อ](https://en.wikipedia.org/wiki/if_and_only_if) มันจะหารด้วย $nm$ ลงตัว เหตุการณ์ซึ่งเกิดขึ้นด้วยความน่าจะเป็น $1/(nm)$) ดังนั้น ความน่าจะเป็นเชิงเส้นกำกับที่จำนวน $s$ ตัวจะเป็นจำนวนเฉพาะสัมพัทธ์จึงกำหนดโดยผลคูณเหนือจำนวนเฉพาะทั้งหมด§F6 [^6]

$$
\prod_{p \text{ prime}} \left(1-\frac{1}{p^s}\right) = \left( \prod_{p \text{ prime}} \frac{1}{1-p^{-s}} \right)^{-1} = \frac{1}{\zeta(s)}.
$$

## สมการเชิงฟังก์ชันของรีมันน์

ฟังก์ชันซีตา (zeta function) นี้เป็นสมการเชิงฟังก์ชัน(https://en.wikipedia.org/wiki/functional_equation)

$$
\zeta(s) = 2^s \pi^{s-1}\ \sin\left( \frac{\pi s}{2} \right)\ \Gamma(1-s)\ \zeta(1-s)\ ,
$$

โดยที่ $Γ(s)$ คือ [ฟังก์ชันแกมมา](https://en.wikipedia.org/wiki/gamma_function) ซึ่งเป็นสมการเชิงฟังก์ชันของฟังก์ชันเมอโรมอร์ฟิกที่ถูกต้องบนระนาบเชิงซ้อนทั้งระนาบ [complex plane](https://en.wikipedia.org/wiki/complex_plane) สมการนี้เชื่อมโยงค่าของฟังก์ชันซีตาของรีมันที่จุด $s$ และ $1 − s$ โดยเฉพาะอย่างยิ่งเชื่อมโยงจำนวนเต็มบวกคู่กับจำนวนเต็มลบคี่ เนื่องจากศูนย์ของฟังก์ชันไซน์ สมการเชิงฟังก์ชันนี้จึงบ่งชี้ว่า $ζ(s)$ มีศูนย์อย่างง่ายที่จำนวนเต็มลบคู่แต่ละค่า $s = −2n$ ซึ่งรู้จักกันในชื่อ **[trivial](https://en.wikipedia.org/wiki/Triviality_%28mathematics%29) zeros** ของ $ζ(s)$ เมื่อ $s$ เป็นจำนวนเต็มบวกคู่ ผลคูณ $\sin\left(\frac{\pi s}{2}\right)\Gamma(1-s)$ ทางด้านขวาไม่เป็นศูนย์เพราะว่า $Γ(1 − s)$ มีขั้วอย่างง่าย [pole](https://en.wikipedia.org/wiki/pole_%28complex_analysis%29) ซึ่งหักล้างกับศูนย์อย่างง่ายของปัจจัยไซน์ เมื่อ $s$ เป็น $0$ ศูนย์ของปัจจัยไซน์ถูกหักล้างด้วยขั้วอย่างง่ายของ $ζ(1)$.

**หลักฐานของสมการเชิงฟังก์ชันของรีมันน์**

การพิสูจน์สมการเชิงฟังก์ชันดำเนินไปดังนี้:
เราสังเกตว่าถ้า $Re(s) > 0$ แล้ว

$$
\int_0^\infty x^{ \frac{1}{2} s - 1 } e^{-n^2\pi x}\ \mathrm dx\ =\ \frac{\ \Gamma\!\left( \frac{s}{2} \right)\ }{\ n^s\ \pi^{\frac{s}{2}}\ } ~.
$$

ดังนั้น หาก $Re(s) > 1$ แล้ว

$$
\frac{\ \Gamma\!\left(\frac{s}{2}\right)\ \zeta(s)\ }{\ \pi^{ \frac{s}{2} }\ }\ =\ \sum_{n=1}^\infty\ \int_0^\infty\ x^{{s\over 2}-1}\ e^{-n^2 \pi x}\ \mathrm dx\ =\ \int_0^\infty x^{{s\over 2}-1} \sum_{n=1}^\infty e^{-n^2 \pi x}\ \mathrm dx\ ,
$$

ด้วยการกลับด้านกระบวนการลิมิตที่ถูกพิสูจน์ความถูกต้องโดย การลู่เข้าสัมบูรณ์ (ดังนั้นข้อกำหนดที่เข้มงวดกว่าต่อ $s$)

เพื่อความสะดวก ให้

$$
\psi(x)\ := \ \sum_{n=1}^\infty\ e^{-n^2 \pi x} ,
$$

ซึ่งเป็นการกรณีพิเศษของ [ฟังก์ชันเธตา](https://en.wikipedia.org/wiki/theta_function)

เนื่องจาก $t \mapsto e^{-t^2 \pi x}$ และ $t \mapsto \frac{1}{\sqrt{x}} e^{\frac{-t^2 \pi}{x}}$ เป็นคู่ของการแปลงฟูรีย[^7] ดังนั้น ตามสูตรการรวมของปัวซง เราจึงมี

$$
\sum_{n=-\infty}^\infty\ e^{ - n^2 \pi\ x }\ =\ \frac{ 1 }{\ \sqrt{x\ }\ }\ \sum_{n=-\infty}^\infty\ e^{ -\frac{\ n^2 \pi\ }{ x } }\ ,
$$

เพื่อให้

$$
\ 2\ \psi(x) + 1\ =\ \frac{ 1 }{\ \sqrt{x\ }\ } \left(\ 2\ \psi\!\left( \frac{ 1 }{ x } \right) + 1\ \right) ~.
$$

ดังนั้น

$$
\pi^{ -\frac{s}{2} }\ \Gamma\!\left( \frac{s}{2} \right)\ \zeta(s)\ =\ \int_0^1\ x^{ \frac{s}{2} - 1 }\ \psi(x)\ \mathrm dx + \int_1^\infty x^{ \frac{s}{2} - 1 } \psi(x)\ \mathrm dx ~.
$$

ด้านขวานั้นเทียบเท่ากับ

$$
\int_0^1 x^{ \frac{s}{2} - 1 } \left( \frac{ 1 }{\ \sqrt{x\ }\ }\ \psi\!\left( \frac{1}{x} \right) + \frac{ 1 }{\ 2 \sqrt{x\ }\ } - \frac{ 1 }{ 2 }\ \right) \ \mathrm dx + \int_1^\infty x^{{s\over 2}-1} \psi(x)\ \mathrm dx
$$

หรือ

$$
\frac{ 1 }{\ s - 1\ } - \frac{ 1 }{\ s\ } + \int_0^1\ x^{ \frac{s}{2} - \frac{3}{2}}\ \psi\!\left( \frac{ 1 }{\ x\ } \right)\ \mathrm dx + \int_1^\infty\ x^{ \frac{s}{2} - 1 }\ \psi(x)\ \mathrm dx
~.
$$

ดังนั้น

$$
\pi^{ -\frac{ s }{ 2 } }\ \Gamma\!\left( \frac{\ s\ }{ 2 } \right)\ \zeta(s)\ =\ \frac{ 1 }{\ s ( s - 1 )\ } + \int_1^\infty\ \left( x^{ -\frac{ s }{ 2 } - \frac{ 1 }{ 2 } } + x^{ \frac{ s }{ 2 } - 1 } \right)\ \psi(x)\ \mathrm dx
$$

ซึ่งลู่เข้าสำหรับทุก $s$ เนื่องจาก $ψ(x) → 0$ เร็วกว่ากำลังใดๆ ของ $x$ สำหรับ $x > 1$ ดังนั้นอินทิกรัลจึงลู่เข้า เนื่องจากด้านขวายังคงเหมือนเดิมหากแทนที่ $s$ ด้วย $1 − s$

$$
\frac{\ \Gamma\!\left(\ \frac{s}{2}\ \right)\ \zeta\!\left(\ s\ \right)\ }{\ \pi^{ \frac{s}{2}\ }\ }\ =\ \frac{\ \Gamma\!\left(\ \frac{1}{2} - \frac{s}{2}\ \right)\ \zeta\!\left(\ 1 - s\ \right)\ }{\ \pi^{ \frac{1}{2} - \frac{s}{2} }\ }
$$

ซึ่งเป็นสมการเชิงฟังก์ชันที่归于 [แบร์นฮาร์ท รีมัน](https://en.wikipedia.org/wiki/Bernhard_Riemann)[^8]

สมการเชิงฟังก์ชันข้างต้นสามารถหาได้ทั้งจาก [สูตรการสะท้อน](https://en.wikipedia.org/wiki/reflection_formula) และ [duplication formula](https://en.wikipedia.org/wiki/Multiplication_theorem#Gamma_function%E2%80%93Legendre_formula)

รวบรวมพจน์ของ $π$:

$$
\Gamma\left(\frac{s}{2}\right)\zeta\left(s\right) = \Gamma\left(\frac{1}{2} - \frac{s}{2}\right)\zeta\left(1 - s\right)\pi^{s-\frac{1}{2}}
$$

จากนั้นคูณทั้งสองข้างด้วย $Γ(1 − s/2)$ และใช้สูตรการสะท้อน:

$$
\Gamma\left(1-\frac s2\right)\Gamma\left(\frac{s}{2}\right)\zeta\left(s\right) = \Gamma\left(1-\frac s2\right)\Gamma\left(\frac{1}{2} - \frac{s}{2}\right)\zeta\left(1 - s\right)\pi^{s-\frac{1}{2}}
$$

$$
\zeta\left(s\right) = \sin\left(\frac{\pi s}2\right)\Gamma\left(1-\frac s2\right)\Gamma\left(\frac{1}{2} - \frac{s}{2}\right)\zeta\left(1 - s\right)\pi^{s-\frac{3}{2}}
$$

ใช้สูตรการคูณซ้ำโดยให้ $z = (1 − s)/2$

$$
\zeta\left(s\right) = \sin\left(\frac{\pi s}2\right)2^{1-1+s}\sqrt{\pi}\Gamma\left(1-s\right)\zeta\left(1 - s\right)\pi^{s-\frac{3}{2}}
$$

เพื่อให้

$$
\zeta\left(s\right) = \sin\left(\frac{\pi s}2\right)2^s\Gamma\left(1-s\right)\zeta\left(1 - s\right)\pi^{s-1}
$$

สมการเชิงฟังก์ชัน (functional equation) ถูกสถาปนาโดยรีมันน์ (Riemann) ในบทความปี 1859 "[On the Number of Primes Less Than a Given Magnitude](https://en.wikipedia.org/wiki/On_the_Number_of_Primes_Less_Than_a_Given_Magnitude)" และถูกนำไปใช้เพื่อสร้างการต่อขยายเชิงวิเคราะห์ (analytic continuation) ในเบื้องต้น

ในการจัดรูปแบบแบบอะเดลิกที่พัฒนาขึ้นใน [วิทยานิพนธ์ของเทต](https://en.wikipedia.org/wiki/Tate%27s_thesis) ตัวประกอบแกมมาที่เรียกว่า
$\pi^{-s/2}\Gamma(s/2)$ ถือเป็นปัจจัยซีตาท้องถิ่นที่ [Archimedean place](https://en.wikipedia.org/wiki/Archimedean_place)

## ฟังก์ชันซิก้าของรีมันน์

รีมันน์ยังพบ [สมมาตร](https://en.wikipedia.org/wiki/Symmetry) ของสมการเชิงฟังก์ชันโดยตั้ง

$$
\xi(s) =\frac{s(s-1)}{2}\pi^{-\frac{s}{2}}\Gamma\left( \frac{s}{2} \right)\zeta(s) =  (s-1)\pi^{-\frac{s}{2}}\Gamma\left(\frac{s}{2}+1\right)\zeta(s)
$$

ที่สอดคล้องกับ:

$$
\xi(s) = \xi(1 - s) ~.
$$

ฟังก์ชันซิกมามีลักษณะเป็นฟังก์ชันทั้ง (entire function)(https://en.wikipedia.org/wiki/entire_function) ซึ่งศูนย์ของฟังก์ชันนี้คือศูนย์ที่ไม่สำคัญทั้งหมดของฟังก์ชันซีตาของรีมัน

เมื่อกลับไปที่การพิสูจน์สมการเชิงฟังก์ชันในบทก่อนหน้า เราจะได้

$$
\xi(s) =\frac12 + \frac{s(s-1)}{2} \int_1^\infty \left(x^{-\frac{s}{2}-\frac{1}{2}} + x^{\frac{s}{2}-1}\right)\psi(x) dx,
$$

ที่

$$
\psi(x)=\sum_{n=1}^{\infty}e^{-\pi n^{2}x}.
$$

การใช้ [**การหาปริพันธ์โดยการแยกส่วน**](https://en.wikipedia.org/wiki/integration_by_parts)

$$
\xi(s) =\frac12 - \left[\left(sx^{\frac{1-s}{2}} + (1-s)x^{\frac{s}{2}}\right)\psi(x)\right]_1^\infty + \int_1^\infty \left(sx^{\frac{1-s}{2}} + (1-s)x^{\frac{s}{2}}\right)\psi'(x) dx
$$

$$
\xi(s) =\frac12 + \psi(1) + \int_1^\infty \left(sx^{\frac{1-s}{2}} + (1-s)x^{\frac{s}{2}}\right)\psi'(x) dx
$$

ใช้การหาปริพันธ์โดยการแยกส่วนอีกครั้งพร้อมกับการแยกส่วนของ $x^{3/2}$

$$
\xi(s) =\frac12 + \psi(1) - 2\left[x^{\frac32}\psi'(x)\left(x^{\frac{s-1}{2}} + x^{-\frac{s}{2}}\right)\right]_1^\infty + 2\int_1^\infty \left(x^{\frac{s-1}{2}} + x^{-\frac{s}{2}}\right)\frac{d}{dx}\left[x^{\frac32}\psi'(x)\right] dx
$$

$$
\xi(s) =\frac12 +\psi(1) + 4\psi'(1) + 2\int_1^\infty \frac{d}{dx}\left[x^{\frac32}\psi'(x)\right]\left(x^{\frac{s-1}{2}} + x^{-\frac{s}{2}}\right) dx
$$

เนื่องจาก $\frac12 +\psi(1) + 4\psi'(1)=0$

$$
\xi(s) = 2\int_1^\infty \frac{d}{dx}\left[x^{\frac32}\psi'(x)\right]\left(x^{\frac{s-1}{2}} + x^{-\frac{s}{2}}\right) dx
$$

ลบตัวประกอบ $x^{−1/4}$ ออกเพื่อให้เลขชี้กำลังในเศษเหลือเป็นค่าตรงข้ามกัน

$$
\xi(s) = 2\int_1^\infty \frac{d}{dx}\left[x^{\frac32}\psi'(x)\right]x^{-\frac14}\left(x^{\frac{s-1/2}{2}} + x^{\frac{1/2-s}{2}}\right) dx
$$

โดยใช้ [ฟังก์ชันไฮเพอร์โบลิก](https://en.wikipedia.org/wiki/hyperbolic_functions) นั่นคือ $cos(x) = cosh(ix)$ และให้ $s = 1/2 + it$ จะได้

$$
\xi(s) = 4\int_1^\infty \frac{d}{dx}\left[x^{\frac32}\psi'(x)\right]x^{-\frac14}\cos\left(\frac{t}2\log x\right) dx
$$

และโดยการแยกอินทิกรัลและใช้ [อนุกรมกำลัง](https://en.wikipedia.org/wiki/power_series) สำหรับ $cos$

$$
\xi(s) = \sum_{n=0}^\infty a_{2n}t^{2n}
$$

ซึ่งนำไปสู่สมมติฐานที่มีชื่อเสียงของรีมันน์

## จุดศูนย์ เส้นวิกฤต และสมมติฐานของรีมันน์

<figure style={{"maxWidth": "308px"}}>

![The Riemann zeta function has no zeros to the right of σ = 1 or (apart from the trivial zeros) to the left of σ = 0 (nor can the zeros lie too close to those lines). Furthermore, the non-trivial zeros are symmetric about the real axis and the line σ = 1/2 and, according to the Riemann hypothesis, they all lie on the line σ = 1/2.](https://pub-275e30003c354ac0862cc9839e0f952a.r2.dev/docs/math/Zero-free_region_for_the_Riemann_zeta-function.svg.png)

<figcaption>

ฟังก์ชันซิกม่าของรีมันไม่มีศูนย์อยู่ทางขวาของ $σ = 1$ หรือ (ยกเว้นศูนย์แบบธรรมดา) อยู่ทางซ้ายของ $σ = 0$ (และศูนย์ก็ไม่สามารถอยู่ใกล้เส้นเหล่านั้นมากเกินไป) นอกจากนี้ ศูนย์แบบไม่ธรรมดาจะสมมาตรเกี่ยวกับแกนจริงและเส้น $σ = 1/2$ และตาม [สมมติฐานของรีมัน](https://en.wikipedia.org/wiki/Riemann_hypothesis) พวกมันทั้งหมดจะอยู่บนเส้น $σ = 1/2$

</figcaption>

</figure>

<figure style={{"maxWidth": "300px"}}>

![This image shows a plot of the Riemann zeta function along the critical line for real values of t running from 0 to 34. The first five zeros in the critical strip are clearly visible as the place where the spirals pass through the origin.](https://pub-275e30003c354ac0862cc9839e0f952a.r2.dev/docs/math/Zeta_polar.svg.png)

<figcaption>

ภาพนี้แสดงกราฟของฟังก์ชันซีตาของรีมัน (Riemann zeta function) ตามเส้นวิกฤตสำหรับค่าจริงของ $t$ ที่วิ่งตั้งแต่ 0 ถึง 34 จุดศูนย์ห้าจุดแรกในแถบวิกฤต (critical strip) สามารถมองเห็นได้ชัดเจนว่าเป็นสถานที่ที่เกลียวผ่านจุดกำเนิด

</figcaption>

</figure>

<figure style={{"maxWidth": "300px"}}>

![The real part (red) and imaginary part (blue) of the Riemann zeta function along the critical line Re(s) = 1/2. The first non-trivial zeros can be seen at Im(s) = ±14.135, ±21.022 and ±25.011.](https://pub-275e30003c354ac0862cc9839e0f952a.r2.dev/docs/math/RiemannCriticalLine.svg.png)

<figcaption>

**ส่วนจริง** (สีแดง) และ **ส่วนจินตภาพ** (สีน้ำเงิน) ของ **ฟังก์ชันซีตาของรีมัน** ตามเส้นวิกฤต $Re(s) = 1/2$ จุดศูนย์ที่ไม่สำคัญแรกสามารถมองเห็นได้ที่ $Im(s) =$ $±14.135$, $±21.022$ และ $±25.011$

</figcaption>

</figure>
สมการเชิงฟังก์ชันแสดงให้เห็นว่า ฟังก์ชันซีตาของรีมัน มีศูนย์ที่ $−2, −4, ...$ ซึ่งเรียกว่า **trivial zeros** (ศูนย์ธรรมดา) พวกมันถือว่าธรรมดาในแง่ที่ว่า การมีอยู่ของพวกมันสามารถพิสูจน์ได้ง่าย نسبัย ตัวอย่างเช่น จาก $sin(πs/2)$ ที่มีค่าเป็น $0$ ในสมการเชิงฟังก์ชัน ศูนย์ที่ไม่ธรรมดา (non-trivial zeros) ได้ดึงดูดความสนใจมากกว่ามาก เพราะการกระจายตัวของพวกมันไม่เพียงแต่เข้าใจได้ยากกว่ามาก แต่ยังสำคัญกว่านั้นคือ การศึกษาพวกมันให้ผลลัพธ์ที่สำคัญเกี่ยวกับจำนวนเฉพาะ (prime numbers) และวัตถุที่เกี่ยวข้องในทฤษฎีจำนวน (number theory) เป็นที่ทราบกันดีว่า ศูนย์ที่ไม่ธรรมดาใดๆ จะอยู่ในแถบเปิด $\{s ∈ \mathbb{C}\}$ ซึ่งเรียกว่า **critical strip** (แถบวิกฤต) เซต $\{s ∈ \mathbb{C}\}$ นี้เรียกว่า **critical line** (เส้นวิกฤต) [สมมติฐานของรีมัน](https://en.wikipedia.org/wiki/Riemann_hypothesis) ซึ่งถือเป็นหนึ่งในปัญหาที่ยังไม่ได้รับการแก้ไขที่ยิ่งใหญ่ที่สุดในคณิตศาสตร์ (mathematics) นั้น ยืนยันว่า ศูนย์ที่ไม่ธรรมดาทั้งหมดอยู่บนเส้นวิกฤต ใน ค.ศ. 1989, Conrey ได้พิสูจน์ว่า มากกว่า 40% ของศูนย์ที่ไม่ธรรมดาของฟังก์ชันซีตาของรีมัน อยู่บนเส้นวิกฤต.[^9] สิ่งนี้ได้รับการปรับปรุงเป็น 41.7%,[^10] และต่อมาเป็น 67.2%.[^11] [^12]

สำหรับฟังก์ชันซีสตาของรีมันบนเส้นวิกฤต ดูที่ [ฟังก์ชัน Z](https://en.wikipedia.org/wiki/Z_function)

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

### จำนวนศูนย์ในแถบวิกฤต

$N(T)$ คือจำนวนศูนย์ของ $ζ(s)$ ในแถบวิกฤต $0 < Re(s) < 1$ ซึ่งส่วนจินตภาพอยู่ในช่วง $0 < Im(s) < T$
ได้พิสูจน์ว่า ถ้า $T > e$ แล้ว[^15]
  $\left|N(T) - \frac{T}{2\pi} \log{\frac{T}{2\pi e}}\right| \leq 0.112 \log T + 0.278 \log\log T + 3.385 + \frac{0.2}{T}$.

### ข้อความคาดการณ์ฮาร์ดี–ลิตเติลวูด

ในปี 1914, [จี. เอช. ฮาร์ดี้](https://en.wikipedia.org/wiki/G._H._Hardy) ได้พิสูจน์ว่า $ζ( 1/2 + it)$ มีศูนย์จริงจำนวนอนันต์.[^16] [^17]

ฮาร์ดีและ [J. E. Littlewood](https://en.wikipedia.org/wiki/John_Edensor_Littlewood) ได้เสนอข้อความคาดการณ์สองข้อเกี่ยวกับความหนาแน่นและระยะห่างระหว่างศูนย์ของ $ζ(1/2 + it)$ บนช่วงของจำนวนจริงจริงที่เป็นบวกขนาดใหญ่ ในส่วนต่อไปนี้ $N(T)$ คือจำนวนรวมของจำนวนจริงจริง และ $N_0(T)$ คือจำนวนรวมของศูนย์ที่มีลำดับคี่ของฟังก์ชัน $ζ(1/2 + it)$ ที่อยู่ในช่วง $(0, T]$

1. สำหรับทุก $ε > 0$ จะมี $T_0(ε) > 0$ ซึ่งเมื่อ

$$
T \geq T_0(\varepsilon) \quad\text{ and }\quad H=T^{\frac14+\varepsilon},
$$

ช่วง $(T, T + H]$ มีศูนย์อันดับคี่

1. สำหรับทุก $ε > 0$ จะมี $T_0(ε) > 0$ และ $c_ε > 0$ ซึ่งทำให้ความไม่เท่าเทียม

$$
N_0(T+H)-N_0(T) \geq c_\varepsilon H
$$

เป็นจริงเมื่อ

$$
T \geq T_0(\varepsilon) \quad\text{ and }\quad H=T^{\frac12+\varepsilon}.
$$

ข้อความคาดการณ์ทั้งสองข้อนี้เปิดทางสู่ทิศทางใหม่ในการศึกษาฟังก์ชันซีตาของรีมัน

### พื้นที่ที่ไม่มีศูนย์

ตำแหน่งศูนย์ของฟังก์ชันซีตาของรีมัน (Riemann zeta function) มีความสำคัญอย่างยิ่งในทฤษฎีจำนวน (number theory) ทฤษฎีบทจำนวนเฉพาะ (prime number theorem) [^18] เทียบเท่ากับข้อเท็จจริงที่ว่าไม่มีศูนย์ของฟังก์ชันซีตาบนเส้น $Re(s) = 1$ [^19] นอกจากนี้ยังเป็นที่ทราบกันดีว่าศูนย์ไม่มีอยู่จริงในบางบริเวณที่อยู่ทางซ้ายของเส้น $Re(s) = 1$ เล็กน้อย ซึ่งเรียกว่าบริเวณที่ไม่มีศูนย์ (zero-free regions) ตัวอย่างเช่น โคโรบอฟ (Korobov) [^20] และ วินิโกรอดอฟ (Vinogradov) แสดงอย่างอิสระผ่านทฤษฎีบทค่าเฉลี่ยของวินิโกรอดอฟ (Vinogradov's mean-value theorem)  ว่าสำหรับ $|t|$ ที่ใหญ่พอ $ζ(σ + it) ≠ 0$ สำหรับ

$$
\sigma \geq 1 - \frac{c}{(\log|t|)^{2/3 + \varepsilon}}
$$

สำหรับทุก $ε > 0$ และจำนวน $c > 0$ ที่ขึ้นอยู่กับ $ε$ โดยประมาณแล้ว นี่คือบริเวณที่ทราบกันดีว่าไม่มีศูนย์ที่ใหญ่ที่สุดสำหรับฟังก์ชันซีตา

เขตปลอดศูนย์แบบชัดแจ้งก็เป็นที่รู้จักเช่นกัน Platt และ Trudgian[^21]
ตรวจสอบยืนยันด้วยวิธีคำนวณว่า $ζ(σ + it) ≠ 0$ ถ้า $σ ≠ 1/2$ และ $|t| ≤ 3⋅10^{12}$ [^22] Mossinghoff, Trudgian และ Yang พิสูจน์ว่าฟังก์ชันซีตาไม่มีจุดศูนย์ในบริเวณดังกล่าว

$$
\sigma\ge 1 - \frac{1}{5.558691\log|t|}
$$

สำหรับ $|t| ≥ 2$ ซึ่งคือบริเวณที่ไม่มีศูนย์ที่ทราบมาว่าใหญ่ที่สุดในแถบวิกฤตสำหรับ $3⋅10^{12} < |t| < exp(64.1) ≈ 7⋅10^{27}$ (สำหรับผลลัพธ์ก่อนหน้าดูที่[^23])
Yang[^24] แสดงให้เห็นว่า $ζ(σ + it) ≠ 0$ ถ้า
และ $|t| \geq 3$
ซึ่งคือบริเวณที่ไม่มีศูนย์ที่ทราบมาว่าใหญ่ที่สุดสำหรับ $exp(170.2) < |t| < exp(4.8⋅10^5)$
Bellotti พิสูจน์[^25] (โดยอาศัยงานของ Ford[^26]) บริเวณที่ไม่มีศูนย์
และ $|t| \ge 3$
นี่คือบริเวณที่ไม่มีศูนย์ที่ทราบมาว่าใหญ่ที่สุดสำหรับ $|t| ≥ exp(4.8⋅10^5)$ ที่กำหนดค่าไว้ Bellotti ยังแสดงให้เห็นว่าสำหรับ $|t|$ ที่ใหญ่พอ ผลลัพธ์ที่ดีกว่าต่อไปนี้เป็นที่ทราบ: $ζ(σ + it) ≠ 0$ สำหรับ

$$
\sigma \geq 1 - \frac{1}{48.0718(\log|t|)^{2/3}(\log\log|t|)^{1/3}}.
$$

ผลลัพธ์ที่ทรงพลังที่สุดในประเภทนี้ที่เราน่าจะหวังได้คือความจริงของสมมติฐานของรีมันน์ ซึ่งจะมีผลกระทบอย่างลึกซึ้งหลายประการ ในทฤษฎีจำนวน

### ผลลัพธ์อื่น ๆ

เป็นที่ทราบกันดีว่าศูนย์บนเส้นวิกฤติมีจำนวนอนันต์ [Littlewood](https://en.wikipedia.org/wiki/John_Edensor_Littlewood) แสดงให้เห็นว่าหากลำดับ ( $γ_n$) ประกอบด้วยส่วนจินตภาพของศูนย์ทั้งหมดใน [ครึ่งบนของระนาบเชิงซ้อน](https://en.wikipedia.org/wiki/upper_half-plane) เรียงจากน้อยไปมาก แล้ว

$$
\lim_{n\rightarrow\infty}\left(\gamma_{n+1}-\gamma_n\right)=0.
$$

**ทฤษฎีบทเส้นวิกฤต** (critical line theorem) ยืนยันว่าส่วนที่เป็นสัดส่วนบวกของศูนย์ที่ไม่สำคัญอยู่บนเส้นวิกฤต (สมมติฐานของรีมันจะบ่งชี้ว่าสัดส่วนนี้เท่ากับ $1$.)

ในแถบวิกฤต ศูนย์ที่มีส่วนจินตภาพที่ไม่เป็นลบและน้อยที่สุดคือ $1/2 + 14.13472514... i$ ([A058303](https://oeis.org/A058303)) ข้อเท็จจริงที่ว่า สำหรับทุกจำนวนเชิงซ้อน $s ≠ 1$

$$
\zeta(s)=\overline{\zeta(\overline{s})}
$$

ส่งผลให้ศูนย์ของฟังก์ชันซีตาของรีมันมีความสมมาตรเกี่ยวกับแกนจริง

ยังเป็นที่ทราบกันดีด้วยว่าไม่มีศูนย์ใดอยู่บนเส้นที่มีส่วนจริงเท่ากับ $1$

มีฟังก์ชันซีตาของรีมันที่ถูกดัดแปลงจำนวนมากที่มีศูนย์ที่ไม่สำคัญเหมือนกันกับฟังก์ชันซีตาของรีมัน โดยที่การดัดแปลงหมายถึงการแทนที่จำนวนเฉพาะในผลคูณของออยเลอร์ด้วยจำนวนจริง ซึ่งได้รับการพิสูจน์ใน [ผลงานโดย Grosswald และ Schnitzer](https://en.wikipedia.org/wiki/Grosswald%E2%80%93Schnitzer_theorem)

## ค่าเฉพาะ

สำหรับจำนวนเต็มคู่บวกใดๆ $2n$

$$
\zeta(2n) = \frac{|{B_{2n}}|(2\pi)^{2n}}{2(2n)!},
$$

โดยที่ $B_{2n}$ คือจำนวนแบร์นุลลีลำดับที่ $(2n)$ [จำนวนแบร์นุลลี](https://en.wikipedia.org/wiki/Bernoulli_number)
การสาธิตค่าเฉพาะ

$$
\zeta(2) = 1 + \frac{1}{2^2} + \frac{1}{3^2} + \cdots = \frac{\pi^2}{6}
$$

เป็นที่รู้จักกันในนาม [ปัญหบาเซิล](https://en.wikipedia.org/wiki/Basel_problem) ผลกลับของผลบวกนี้ตอบคำถามว่า: 'ความน่าจะเป็นที่จำนวนสองจำนวนที่เลือกจากการแจกแจงแบบสม่ำเสมอตั้งแต่ $1$ ถึง $n$] จะเป็น [จำนวนเฉพาะสัมพัทธ์](https://en.wikipedia.org/wiki/coprime) เมื่อ $n → ∞$?'[^27]

สำหรับจำนวนเต็มบวกคี่ ยังไม่มีสูตรอย่างง่ายที่ทราบกัน แม้ค่าเหล่านี้จะเชื่อว่ามีสัมพันธ์กับทฤษฎีพีชคณิต $K$ ของจำนวนเต็ม; ดูที่ [ค่าเฉพาะของฟังก์ชัน $L$](https://en.wikipedia.org/wiki/Special_values_of_L-functions).
ค่า

$$
\zeta(3) = 1 + \frac{1}{2^3} + \frac{1}{3^3} + \cdots = 1.202056903159594285399...
$$

คือ [ค่าคงที่ของ Apéry](https://en.wikipedia.org/wiki/Ap%C3%A9ry%27s_constant)

สำหรับจำนวนเต็มที่ไม่เป็นบวกอนุกรมนี้ไม่ลู่เข้า แต่ผ่านการวิเคราะห์เชิงซ้อน สามารถแสดงว่า

$$
\zeta(-n)= -\frac{B_{n+1}}{n+1}
$$

สำหรับ $n ≥ 0$ (โดยใช้ข้อตกลงที่ว่า $B_1 = 1/2$).
โดยเฉพาะ $ζ$ มีค่าเป็นศูนย์ที่จำนวนคู่ติดลบ เนื่องจาก $B_m = 0$ สำหรับทุก $m$ ที่คี่นอกจาก $1$. สิ่งเหล่านี้คือ "ศูนย์ธรรมดา" (trivial zeros) ของฟังก์ชันซีตา.
ค่าเฉพาะอีกค่าหนึ่งคือ

$$
\zeta(-1) = -\tfrac{1}{12}
$$

สิ่งนี้ให้ข้ออ้างในการกำหนดค่าจำกัดให้กับอนุกรมลู่ออก $1 + 2 + 3 + 4 + ⋯$ ซึ่งได้ถูกนำไปใช้ในบริบทบางประการ ([Ramanujan summation](https://en.wikipedia.org/wiki/Ramanujan_summation)) เช่น [ทฤษฎีสตริง](https://en.wikipedia.org/wiki/string_theory)[^28] ในทำนองเดียวกัน

$$
\zeta(0) = -\tfrac{1}{2}
$$

สามารถมองได้ว่าเป็นการกำหนดผลลัพธ์ที่มีจำนวนจำกัดให้กับอนุกรมลู่ออก $1 + 1 + 1 + 1 + ⋯$.

ค่า

$$
\zeta\bigl(\tfrac12\bigr) = -1.46035450880958681288\ldots
$$

ถูกนำมาใช้ในการคำนวณปัญหาชั้นขอบเขตจลนศาสตร์ของสมการจลนศาสตร์เชิงเส้น.[^29] [^30]

แม้ว่า

$$
\zeta(1) = 1 + \tfrac{1}{2} + \tfrac{1}{3} + \cdots
$$

ลู่ออก ค่าหลักของ Cauchy ของมันคือ [ค่าหลักของ Cauchy](https://en.wikipedia.org/wiki/Cauchy_principal_value)

$$
\lim_{\varepsilon \to 0} \frac{\zeta(1+\varepsilon)+\zeta(1-\varepsilon)}{2}
$$

มีอยู่จริงและเท่ากับค่าคงตัวอ็อยเลอร์–มัสเกโรนี [^31] $γ = 0.5772...$.

เมื่อพิจารณาขีดจำกัด $s → +∞$ ผ่านจำนวนจริง จะได้ $ζ(+∞) = 1$ แต่ที่ [complex infinity](https://en.wikipedia.org/wiki/complex_infinity) บน [Riemann sphere](https://en.wikipedia.org/wiki/Riemann_sphere) ฟังก์ชันซีตาจะมี [essential singularity](https://en.wikipedia.org/wiki/essential_singularity)[^2]

## คุณสมบัติต่างๆ

สำหรับผลรวมที่เกี่ยวข้องกับฟังก์ชันซีตาที่ค่าจำนวนเต็มและ [ครึ่งจำนวนเต็ม](https://en.wikipedia.org/wiki/half-integer) ดูที่ [อนุกรมซีตาตรรกยะ](https://en.wikipedia.org/wiki/rational_zeta_series)

### ความสัมพันธ์แบบกลับด้าน

ฟังก์ชันซีตาส่วนกลับสามารถแสดงเป็น [อนุกรมดีริชเลต์](https://en.wikipedia.org/wiki/Dirichlet_series) บน [ฟังก์ชันมูบิอุส](https://en.wikipedia.org/wiki/M%C3%B6bius_function) $μ(n)$:

$$
\frac{1}{\zeta(s)} = \sum_{n=1}^\infty \frac{\mu(n)}{n^s}
$$

สำหรับจำนวนเชิงซ้อนทุกตัว $s$ ที่มีส่วนจริงมากกว่า $1$ มีความสัมพันธ์หลายอย่างที่เกี่ยวข้องกับ ฟังก์ชันเชิงการคูณ (multiplicative function) ต่างๆ ที่รู้จักกันดี; สิ่งเหล่านี้ถูกนำเสนอในบทความเกี่ยวกับ [Dirichlet series](https://en.wikipedia.org/wiki/Dirichlet_series)

สมมติฐานของรีมันน์ (Riemann hypothesis) เทียบเท่ากับการอ้างว่านิพจน์นี้มีผลบังคับใช้เมื่อส่วนจริงของ $s$ มากกว่า $1/2$

### หลักสากล

**แถบวิกฤตของฟังก์ชันซีตาของรีมัน** (The critical strip of the Riemann zeta function) มีคุณสมบัติที่น่าทึ่งอย่างหนึ่งคือ **ความเป็นสากล** (universality) คุณสมบัติ [ความเป็นสากลของฟังก์ชันซีตา](https://en.wikipedia.org/wiki/zeta_function_universality) นี้กล่าวโดยสรุปว่า การเลื่อนในแนวตั้งของ $\zeta(s)$ สามารถประมาณฟังก์ชันโฮโลมอร์ฟิกที่ไม่เป็นศูนย์ใดๆ บนเซตคอมแพกต์ที่เหมาะสมภายในแถบ $1/2<\operatorname{Re}(s)<1$ ได้อย่างสม่ำเสมอ เนื่องจากฟังก์ชันโฮโลมอร์ฟิกมีความทั่วไปมาก คุณสมบัตินี้จึงน่าทึ่งอย่างยิ่ง หลักฐานแรกของการพิสูจน์ความเป็นสากลนั้นถูกนำเสนอโดย [เซอร์เกย์ มิไคโลวิช โวรอนิน](https://en.wikipedia.org/wiki/Sergei_Mikhailovitch_Voronin) ในปี 1975.[^32] งานล่าสุดได้รวมถึง [แบบที่มีประสิทธิภาพ](https://en.wikipedia.org/wiki/Zeta_function_universality#Effective_universality) ของทฤษฎีบทของวรอนิน[^33] และ [การขยาย](https://en.wikipedia.org/wiki/Zeta_function_universality#Universality_of_other_zeta_functions) ไปยัง [ฟังก์ชันดีริชเลต $L$](https://en.wikipedia.org/wiki/Dirichlet_L-function)[^34] [^35]

### การประมาณค่าสูงสุดของมอดุลัสของฟังก์ชันซีตา

ให้ฟังก์ชัน $F(T; H)$ และ $G(s_0; Δ)$ ถูกนิยามโดยความเท่าเทียม

$$
F(T;H) = \max_{|t-T|\le H}\left|\zeta\left(\tfrac{1}{2}+it\right)\right|,\qquad G(s_{0};\Delta) = \max_{|s-s_{0}|\le\Delta}|\zeta(s)|.
$$

ที่นี้ $T$ เป็นจำนวนบวกที่มีค่ามากเพียงพอ, $0 < H ≪ log log T$, $s_0 = σ_0 + iT$, $1/2 ≤ σ_0 ≤ 1$, $0 < Δ < 1/3$ การประมาณค่า $F$ และ $G$ จากด้านล่างแสดงให้เห็นว่าค่า $ζ(s)$ สามารถมีขนาดเท่าใด (ในค่าสัมบูรณ์) บนช่วงสั้นๆ ของเส้นวิกฤต หรือในบริเวณใกล้เคียงจุดที่ตกอยู่ในแถบวิกฤต $0 ≤ Re(s) ≤ 1$

กรณี $H ≫ log log T$ นั้นได้รับการศึกษาโดย [Kanakanahalli Ramachandra](https://en.wikipedia.org/wiki/Kanakanahalli_Ramachandra); กรณี $Δ > c$ ซึ่ง $c$ เป็นค่าคงที่ที่เพียงพอมากนั้นเป็นเรื่องง่าย

[อันอาโตลี คาร์ราซบูบา](https://en.wikipedia.org/wiki/Anatolii_Alexeevitch_Karatsuba) ได้พิสูจน์[^36] [^37] โดยเฉพาะว่า ถ้าค่า $H$ และ $Δ$ เกินค่าคงที่ที่เล็กมากเพียงพอแล้ว การประมาณค่า

$$
F(T;H) \ge T^{- c_1},\qquad G(s_0; \Delta) \ge T^{-c_2},
$$

คงไว้ โดยที่ $c_1$ และ $c_2$ เป็นค่าคงที่สัมบูรณ์บางค่า

### มุมของฟังก์ชันซีตาของรีมัน

ฟังก์ชัน

$$
S(t) = \frac{1}{\pi}\arg{\zeta\left(\tfrac12+it\right)}
$$

เรียกว่า [อาร์กิวเมนต์](https://en.wikipedia.org/wiki/complex_argument) ของ ฟังก์ชันซีตาของรีมัน ที่นี่ $arg ζ(1/2 + it)$ คือการเพิ่มขึ้นของสาขาต่อเนื่องใดๆ ของ $arg ζ(s)$ ตามเส้นหักที่เชื่อมจุด $2$, $2 + it$ และ $1/2 + it$

มีทฤษฎีบทบางประการเกี่ยวกับสมบัติของฟังก์ชัน $S(t)$ ในบรรดารายการผลลัพธ์[^38] [^39] นั้น ได้แก่ [mean value theorems](https://en.wikipedia.org/wiki/Mean_value_theorems_for_definite_integrals) สำหรับ $S(t)$ และอินทิกรัลอันดับแรกของมัน

$$
S_1(t) = \int_0^t S(u) \, \mathrm{d}u
$$

บนช่วงของเส้นจริง และรวมถึงทฤษฎีบทที่อ้างว่าช่วงทุกช่วง $(T, T + H]$ สำหรับ

$$
H \ge T^{\frac{27}{82}+\varepsilon}
$$

มีอย่างน้อย

$$
H\sqrt[3]{\ln T}e^{-c\sqrt{\ln\ln T}}
$$

จุดที่ฟังก์ชัน $S(t)$ เปลี่ยนเครื่องหมาย ผลลัพธ์ที่คล้ายกันก่อนหน้านี้ได้ถูกค้นพบโดย [Atle Selberg](https://en.wikipedia.org/wiki/Atle_Selberg) ในกรณี

$$
H\ge T^{\frac12+\varepsilon}.
$$

## การแสดงออก

### ร้อยคูณของ Dirichlet

การขยายพื้นที่ของการลู่เข้าสามารถทำได้โดยการจัดเรียงลำดับอนุกรมใหม่.[^40] อนุกรม

$$
\zeta(s)=\frac{1}{s-1}\sum_{n=1}^\infty \left(\frac{n}{(n+1)^s}-\frac{n-s}{n^s}\right)
$$

ลู่เข้าสำหรับ $Re(s) > 0$ ในขณะที่

$$
\zeta(s) =\frac{1}{s-1}\sum_{n=1}^\infty\frac{n(n+1)}{2}\left(\frac{2n+3+s}{(n+1)^{s+2}}-\frac{2n-1-s}{n^{s+2}}\right)
$$

ลู่เข้าแม้กระทั่งสำหรับ $Re(s) > −1$ ในวิธีนี้ พื้นที่ของการลู่เข้าสามารถขยายออกไปเป็น $Re(s) > −k$ สำหรับจำนวนเต็มลบใดๆ $−k$

การเชื่อมต่อแบบเวียนเกิดนั้นเห็นได้ชัดเจนจากนิพจน์ที่มีผลบังคับใช้สำหรับ $Re(s) > −2$ ซึ่งทำให้สามารถขยายต่อได้โดยการหาปริพันธ์โดยการแยกส่วน

$$
\begin{aligned}
\zeta(s)= & 1+\frac{1}{s-1}-\frac{s}{2 !}[\zeta(s+1)-1] \\
- & \frac{s(s+1)}{3 !}[\zeta(s+2)-1] \\
& -\frac{s(s+1)(s+2)}{3 !} \sum_{n=1}^{\infty} \int_0^1 \frac{t^3 d t}{(n+t)^{s+3}}.
\end{aligned}
$$

การเวียนซ้ำนี้ นำไปสู่การขยายอนุกรมอื่นที่ใช้ [แฟกทอเรียลแบบเพิ่มขึ้น](https://en.wikipedia.org/wiki/Pochhammer_symbol) และใช้ได้กับระนาบเชิงซ้อนทั้งหมด [^40]

$$
\zeta(s) = \frac{s}{s-1} - \sum_{n=1}^\infty \bigl(\zeta(s+n)-1\bigr)\frac{s(s+1)\cdots(s+n-1)}{(n+1)!}.
$$

สามารถนำไปใช้แบบเวียนเกิดเพื่อขยายนิยามอนุกรม Dirichlet ไปยังจำนวนเชิงซ้อนทั้งหมดได้

ฟังก์ชันซีตาของรีมันยังปรากฏในรูปที่คล้ายกับการแปลงเมลลิน ในอินทิกรัลเหนือ [ตัวดำเนินการเกาส์–คูซมิน–วีร์ซิง](https://en.wikipedia.org/wiki/Gauss%E2%80%93Kuzmin%E2%80%93Wirsing_operator) ที่กระทำต่อ $x^{s−1}$; บริบทนั้นนำไปสู่การขยายอนุกรมในรูปของ [แฟกทอเรียลดาล](https://en.wikipedia.org/wiki/falling_factorial)[^41]

### อินทิกรัลแบบเมลลิน

การแปลงเมลลิน (Mellin transform) ของฟังก์ชัน $f(x)$ ถูกนิยามว่า[^42]

$$
\int_0^\infty f(x)x^s\, \frac{\mathrm{d}x}{x}
$$

ในบริเวณที่อินทิกรัลนิยามไว้ มีนิพจน์ต่างๆ ของฟังก์ชันซีตาในรูปของอินทิกรัลคล้ายการแปลงเมลลิน หากส่วนจริงของ $s$ มากกว่าหนึ่ง เรามี
  $\Gamma(s)\zeta(s) =\int_0^\infty\frac{x^{s-1}}{e^x-1} \,\mathrm{d}x \quad$ และ $\quad\Gamma(s)\zeta(s) =\frac1{2s}\int_0^\infty\frac{x^{s}}{\cosh(x)-1} \,\mathrm{d}x ,$
โดยที่ $Γ$ หมายถึง [ฟังก์ชันแกมมา](https://en.wikipedia.org/wiki/gamma_function) โดยการปรับ [เส้นโค้ง](https://en.wikipedia.org/wiki/Contour_integration) ริมันน์ได้แสดงให้เห็นว่า

$$
2\sin(\pi s)\Gamma(s)\zeta(s) =i\oint_H \frac{(-x)^{s-1}}{e^x-1}\,\mathrm{d}x
$$

สำหรับทุก $s$[^43] (โดยที่ $H$ หมายถึง [เส้นโค้งฮันเคิล](https://en.wikipedia.org/wiki/Hankel_contour))

เราสามารถหาสูตรที่เกี่ยวข้องกับจำนวนเฉพาะและทฤษฎีบทจำนวนเฉพาะ ได้ ถ้า $π(x)$ คือ ฟังก์ชันนับจำนวนเฉพาะ แล้ว

$$
\ln \zeta(s) = s \int_0^\infty \frac{\pi(x)}{x(x^s-1)}\,\mathrm{d}x,
$$

สำหรับค่าที่มี $Re(s) > 1$.

การแปลงเมลลินที่คล้ายกันเกี่ยวข้องกับฟังก์ชันรีมันน์ $J(x)$ ซึ่งนับกำลังจำนวนเฉพาะ $p^n$ ด้วยน้ำหนัก $1/n$ ดังนั้น

$$
J(x) = \sum \frac{\pi\left(x^\frac{1}{n}\right)}{n}.
$$

ตอนนี้

$$
\ln \zeta(s) = s\int_0^\infty J(x)x^{-s-1}\,\mathrm{d}x.
$$

นิพจน์เหล่านี้สามารถนำมาใช้เพื่อพิสูจน์ทฤษฎีบทจำนวนเฉพาะ (prime number theorem) โดยอาศัยการแปลง Mellin แบบผกผัน ฟังก์ชันนับจำนวนเฉพาะ (prime-counting function) ของรีมันน์นั้นใช้งานง่ายกว่า และ $π(x)$ สามารถกู้คืนได้จากมันโดยใช้การกลับกลับของมูบิอุส (Möbius inversion)

### ฟังก์ชันเธตา

**ฟังก์ชันซีตาของรีมัน** (Riemann zeta function) สามารถกำหนดได้โดยแปลงเมลลิน[^44]

$$
2\pi^{-\frac{s}{2}}\Gamma\left(\frac{s}{2}\right)\zeta(s) = \int_0^\infty \bigl(\theta(it)-1\bigr)t^{\frac{s}{2}-1}\,\mathrm{d}t,
$$

ในแง่ของ [ฟังก์ชันธีตาของจาโคบี](https://en.wikipedia.org/wiki/Theta_function)

$$
\theta(\tau)= \sum_{n=-\infty}^\infty e^{\pi i n^2\tau}.
$$

อย่างไรก็ตาม อินทิกรัลนี้ลู่เข้ก็ต่อเมื่อส่วนจริงของ $s$ มากกว่า $1$ เท่านั้น แต่สามารถทำให้เป็นมาตรฐานได้ ซึ่งให้สมการสำหรับ ฟังก์ชันซีตา ดังนี้ ซึ่งนิยามได้ดีสำหรับทุกค่า $s$ ยกเว้น $0$ และ $1$:

$$
\pi^{-\frac{s}{2}}\Gamma\left(\frac{s}{2}\right)\zeta(s) = \frac{1}{s-1}-\frac{1}{s} +\frac{1}{2} \int_0^1 \left(\theta(it)-t^{-\frac12}\right)t^{\frac{s}{2}-1}\,\mathrm{d}t + \frac{1}{2}\int_1^\infty \bigl(\theta(it)-1\bigr)t^{\frac{s}{2}-1}\,\mathrm{d}t.
$$

### ลำดับลอรอง

ฟังก์ชันซีตาของรีมัน (Riemann zeta function) เป็นฟังก์ชันที่มีลักษณะเป็น meromorphic [^45] โดยมี [pole](https://en.wikipedia.org/wiki/pole_%28complex_analysis%29) เพียงจุดเดียวที่มีลำดับหนึ่ง ณ $s = 1$ ดังนั้นจึงสามารถขยายเป็น [Laurent series](https://en.wikipedia.org/wiki/Laurent_series) รอบ $s = 1$; การพัฒนาอนุกรมดังกล่าวจึงเป็น

$$
\zeta(s)=\frac{1}{s-1}+\sum_{n=0}^\infty \frac{\gamma_n}{n!}(1-s)^n.
$$

ค่าคงที่ $γ_n$ ในที่นี้เรียกว่า [ค่าคงที่ Stieltjes](https://en.wikipedia.org/wiki/Stieltjes_constants) และสามารถนิยามได้โดย [ลิมิต](https://en.wikipedia.org/wiki/limit_of_a_sequence) ของลำดับ

$$
\gamma_n = \lim_{m \rightarrow \infty}{\left(\left(\sum_{k = 1}^m \frac{(\ln k)^n}{k}\right) - \frac{(\ln m)^{n+1}}{n+1}\right)}.
$$

พจน์คงที่ $γ_0$ คือ [ค่าคงตัวอ็อยเลอร์–มัสเกโรนี](https://en.wikipedia.org/wiki/Euler%E2%80%93Mascheroni_constant)

### อินทิกรัล

สำหรับทุก $s ∈ \mathbb{C}$, $s ≠ 1$ ความสัมพันธ์เชิงปริพันธ์ (ดูสูตรอาเบล-ปลานา)

$$
\zeta(s) = \frac{ 1 }{s - 1} + \frac{1}{2} + 2 \int_0^{\infty} \frac{\sin(s\arctan t) }{ \left(1 + t^2 \right)^{s/2} \left(e^{2\pi t} - 1\right)\ }\ \operatorname{d}t
$$

เป็นจริง ซึ่งอาจใช้สำหรับการประเมินค่าเชิงตัวเลขของฟังก์ชันซีตา

### ผลคูณของ Hadamard

บนพื้นฐานของ [ทฤษฎีบทการแยกตัวประกอบของไวเออร์สตราส](https://en.wikipedia.org/wiki/Weierstrass_factorization_theorem) [Hadamar](https://en.wikipedia.org/wiki/Hadamard) ได้ให้การขยายแบบ [ผลคูณอนันต์](https://en.wikipedia.org/wiki/infinite_product)

$$
\zeta(s) = \frac{e^{\left(\log(2\pi)-1-\frac{\gamma}{2}\right)s}}{2(s-1)\Gamma\left(1+\frac{s}{2}\right)} \prod_\rho \left(1 - \frac{s}{\rho} \right) e^\frac{s}{\rho},
$$

ซึ่งผลคูณเป็นผลคูณเหนือศูนย์ที่ไม่สำคัญ $ρ$ ของ $ζ$ และตัวอักษร $γ$ ยังคงหมายถึง [ค่าคงตัวอ็อยเลอร์–มัสเกโรนี](https://en.wikipedia.org/wiki/Euler%E2%80%93Mascheroni_constant) อีกครั้ง การขยายแบบ [ผลคูณอนันต์](https://en.wikipedia.org/wiki/infinite_product) ที่เรียบง่ายกว่าคือ

$$
\zeta(s) = \pi^\frac{s}{2} \frac{\prod_\rho \left(1 - \frac{s}{\rho} \right)}{2(s-1)\Gamma\left(1+\frac{s}{2}\right)}.
$$

รูปแบบนี้แสดงขั้วอย่างง่าย (simple pole) ที่ $s = 1$ ศูนย์ที่ว่างเปล่า (trivial zeros) ที่ $−2, −4,$... เนื่องจากพจน์ฟังก์ชันแกมมา (gamma function) ในตัวส่วน และศูนย์ที่ไม่ใช่ศูนย์ที่ว่างเปล่า (non-trivial zeros) ที่ $s = ρ$ (เพื่อให้แน่ใจว่าการลู่เข้า (convergence) ในสูตรหลังนั้น ผลคูณควรจะถูกคำนวณจาก "คู่ที่ตรงกัน" ของศูนย์ กล่าวคือ ปัจจัยสำหรับคู่ของศูนย์ที่มีรูปแบบ $ρ$ และ $1 − ρ$ ควรจะถูกนำมารวมกัน) 

### ###อนุกรมลู่เข้าทั่วโลก

**อนุกรมที่ลู่เข้าทั่วโลกสำหรับฟังก์ชันซีตา** (zeta function) ซึ่งถูกต้องสำหรับจำนวนเชิงซ้อนทุกตัว $s$ ยกเว้น $s = 1 + 2πi/ln 2 n$ สำหรับจำนวนเต็ม $n$ บางตัวนั้น ถูกคาดเดาโดย [Konrad Knopp](https://en.wikipedia.org/wiki/Konrad_Knopp) ในปี 1926 [^46] และได้รับการพิสูจน์โดย [Helmut Hasse](https://en.wikipedia.org/wiki/Helmut_Hasse) ในปี 1930[^47] (ดูเพิ่มเติมที่ [Euler summation](https://en.wikipedia.org/wiki/Euler_summation)):

$$
\zeta(s)=\frac{1}{1-2^{1-s}} \sum_{n=0}^\infty \frac {1}{2^{n+1}} \sum_{k=0}^n \binom{n}{k} \frac{(-1)^k}{(k+1)^{s}}.
$$

อนุกรมปรากฏในภาคผนวกของบทความของ Hasse และได้รับการตีพิมพ์เป็นครั้งที่สองโดย Jonathan Sondow ในปี 1994.[^48]

ฮาสเซยังพิสูจน์อนุกรมที่ลู่เข้าทั่วโลก

$$
\zeta(s)=\frac 1{s-1}\sum_{n=0}^\infty \frac 1{n+1}\sum_{k=0}^n\binom {n}{k}\frac{(-1)^k}{(k+1)^{s-1}}
$$

ในวารสารฉบับเดียวกัน.[^47] การวิจัยโดย Iaroslav Blagouchine[^49] [^46]
พบว่าอนุกรมที่คล้ายกันและเทียบเท่ากันฉบับหนึ่งถูกตีพิมพ์โดย [Joseph Ser](https://en.wikipedia.org/wiki/Joseph_Ser) ในปี 1926.[^50]

ในปี 1997 K. Maślanka ได้เสนออนุกรมอีกชุดหนึ่งที่มีการลู่เข้าทั่วโลก (ยกเว้น $s = 1$) สำหรับฟังก์ชันซีตาของรีมัน:

$$
\zeta (s)=\frac{1}{s-1}\sum_{k=0}^\infty \biggl(\prod_{i=1}^{k} (i-\frac{s}{2})\biggl) \frac{A_{k}}{k!}=
\frac{1}{s-1} \sum_{k=0}^\infty \biggl(1-\frac{s}{2}\biggl)_{k}
\frac{A_{k}}{k!}
$$

โดยที่สัมประสิทธิ์จริง $A_k$ กำหนดให้ดังนี้:

$$
A_k=\sum_{j=0}^{k}(-1)^{j}\binom{k}{j}(2j+1)\zeta
(2j+2)=\sum_{j=0}^{k}\binom{k}{j}\frac{B_{2j+2}\pi ^{2j+2}}{\left(2\right) _{j}\left( \frac{1}{2}\right) _{j}}
$$

$B_n$ คือจำนวนแบร์นุลลี และ $(x)_k$ หมายถึงสัญลักษณ์โพชแฮมเมอร์.[^51] [^52]

โปรดทราบว่า การแสดงออกของฟังก์ชันซีตา (zeta function) แบบนี้เป็นการประมาณค่าแบบสอดแทรกที่มีจุดโหนด (nodes) ซึ่งจุดโหนดเหล่านี้คือจุด $s = 2, 4, 6, ...$ นั่นคือจุดที่ค่าของฟังก์ชันซีตาเป็นที่ทราบแน่นอนพอดี ตามที่ออยเลอร์ (Euler) ได้แสดงไว้ การพิสูจน์แบบย่อของการแสดงออกของฟังก์ชันซีตาแบบนี้สืบเนื่องมาจาก [ทฤษฎีบทของคาร์ลสัน](https://en.wikipedia.org/wiki/Carlson%27s_theorem)[^53]

พฤติกรรมเชิงซีมโทติกของสัมประสิทธิ์ $A_{k}$ นั้นน่าสนใจมาก: สำหรับค่า $k$ ที่เพิ่มขึ้น เราสังเกตการแกว่งกวัดอย่างสม่ำเสมอที่มีแอมพลิจูดลดลงแบบเอกซ์โพเนนเชียลโดยประมาณและมีความถี่ลดลงอย่างช้าๆ (โดยประมาณเท่ากับ $k^{-2/3}$) โดยใช้วิธีการจุดอาน เราสามารถแสดงว่า

$$
A_{k}\sim \frac{4\pi ^{3/2}}{\sqrt{3\kappa }}\exp \biggl( -\frac{3\kappa }{2}+\frac{\pi ^{2}}{4\kappa }\biggl) \cos \biggl( \frac{4\pi }{3}-\frac{3\sqrt{3}
\kappa }{2}+\frac{\sqrt{3}\pi ^{2}}{4\kappa }\biggl)
$$

ซึ่ง $\kappa$ หมายถึง:

$$
\kappa :=\sqrt[3]{\pi ^{2}k}
$$

(ดูรายละเอียดใน [^54])

บนพื้นฐานของการแสดงออกนี้ ใน ค.ศ. 2003 Luis Báez-Duarte ได้เสนอเกณฑ์ใหม่สำหรับสมมติฐานของรีมันน์.[^55] [^56] [^57] นั่นคือ หากเรานิยามสัมประสิทธิ์ $c_k$ ดังนี้

$$
c_{k}:=\sum_{j=0}^{k}(-1)^{j}\binom{k}{j}\frac{1}{\zeta (2j+2)}
$$

ดังนั้น สมมติฐานของรีมันน์ จึงเทียบเท่ากับ

$$
c_{k}=\mathcal{O}\left( k^{-3/4+\varepsilon }\right) \qquad (\forall\varepsilon >0)
$$

### ลำดับที่ลู่เข้าอย่างรวดเร็ว

[ปีเตอร์ บอร์ไวน์](https://en.wikipedia.org/wiki/Peter_Borwein) ได้พัฒนาอัลกอริทึมที่ใช้ [พหุนามเชบิเชฟ](https://en.wikipedia.org/wiki/Chebyshev_polynomial) นำมาใช้กับ [ฟังก์ชันอีตาของดีรีเคล](https://en.wikipedia.org/wiki/Dirichlet_eta_function) เพื่อสร้าง [อนุกรมที่ลู่เข้าอย่างรวดเร็วซึ่งเหมาะสำหรับการคำนวณเชิงตัวเลขที่มีความแม่นยำสูง](https://en.wikipedia.org/wiki/Dirichlet_eta_function#Borwein%27s_method)[^58]

### การแสดงออกเป็นอนุกรมที่จำนวนเต็มบวกผ่านไพรมอเรียล

$$
\zeta(k)=\frac{2^k}{2^k-1}+\sum_{r=2}^\infty\frac{(p_{r-1}\#)^k}{J_k(p_r\#)}\qquad k=2,3,\ldots.
$$

$J_k$ คือฟังก์ชันทอเทียนของจอร์แดน และ $p_n\#$ คือลำดับไพรมอเรียล [^59]

### การแทนอนุกรมด้วยจำนวนโพลีแบร์นุลลีที่ไม่สมบูรณ์

ฟังก์ชัน $ζ$ สามารถแสดงได้สำหรับ $Re(s) > 1$ โดยอนุกรม

$$
\zeta(s)=\sum_{n=0}^\infty B_{n,\ge2}^{(s)}\frac{(W_k(-1))^n}{n!},
$$

โดยที่ $k ∈ \{−1, 0\}$, $W_k$ คือสาขาที่ $k$ ของ [ฟังก์ชันแลมเบิร์ต $W$](https://en.wikipedia.org/wiki/Lambert_W_function) และ $B^{(μ)}_{n,≥2}$ คือจำนวนแบร์นุลลีพอลิที่ไม่สมบูรณ์.[^60]

### การแปลงเมลลินของแผนที่เอนเกิล

ฟังก์ชัน $g(x) = x(1 + \lfloor x^{−1} \rfloor) − 1$ ถูกนำมาทำซ้ำเพื่อหาค่าสัมประสิทธิ์ที่ปรากฏในการขยายแบบเอนเกิล[^61] 

การแปลงเมลลิน (Mellin transform) ของฟังก์ชัน $g(x)$ มีความสัมพันธ์กับ ฟังก์ชันซีตาของรีมัน (Riemann zeta function) ผ่านสูตร

$$
\begin{align}
    \int_0^1 g (x) x^{s - 1} \, dx & = \sum_{n = 1}^\infty
    \int_{\frac{1}{n + 1}}^{\frac{1}{n}} (x (n + 1) - 1) x^{s - 1} \, d x\\[6pt]
    & = \sum_{n = 1}^\infty \frac{n^{- s} (s - 1) + (n + 1)^{- s - 1} (n^2 + 2 n + 1) + n^{- s - 1} s - n^{1 - s}}{(s + 1) s (n + 1)}\\[6pt]
    & = \frac{\zeta (s + 1)}{s + 1} - \frac{1}{s (s + 1)}
  \end{align}
$$

### การแสดงออกแบบสุ่ม

การเคลื่อนที่แบบบราวน์ (Brownian motion) และ ฟังก์ชันซีตาของรีมัน (Riemann zeta function) เชื่อมต่อกันผ่าน ฟังก์ชันสร้างโมเมนต์ (moment-generating function) ของ กระบวนการสโตแคสติก (stochastic process) ที่ได้จาก การเคลื่อนที่แบบบราวน์ (Brownian motion) [^62]

## อัลกอริทึมเชิงตัวเลข

อัลกอริทึมแบบคลาสสิก ซึ่งมีการใช้งานก่อนประมาณปี 1930 ดำเนินการโดยการใช้ [สูตรออยเลอร์–มาคลอริน](https://en.wikipedia.org/wiki/Euler%E2%80%93Maclaurin_formula) เพื่อหาจำนวนเต็มบวก $n$ และ $m$

$$
\zeta(s) = \sum_{j=1}^{n-1}j^{-s} + \tfrac12 n^{-s} + \frac{n^{1-s}}{s-1} + \sum_{k=1}^m T_{k,n}(s) + E_{m,n}(s)
$$

โดยที่ $B_{2k}$ แทน [จำนวนแบร์นุลลี](https://en.wikipedia.org/wiki/Bernoulli_number)

$$
T_{k,n}(s) = \frac{B_{2k}}{(2k)!} n^{1-s-2k}\prod_{j=0}^{2k-2}(s+j)
$$

และข้อผิดพลาดสอดคล้อง

$$
|E_{m,n}(s)| < \left|\frac{s+2m+1}{\sigma + 2m + 1}T_{m+1,n}(s)\right|,
$$

โดยที่ $σ = Re(s)$.[^63]

อัลกอริทึมเชิงตัวเลขสมัยใหม่คือ [อัลกอริทึมโอดลีย์ซโก–ชönhage](https://en.wikipedia.org/wiki/Odlyzko%E2%80%93Sch%C3%B6nhage_algorithm) 

## การใช้งาน

ฟังก์ชันซีตา (zeta function) เกิดขึ้นในสถิติศาสตร์ประยุกต์ รวมถึง [กฎของ Zipf](https://en.wikipedia.org/wiki/Zipf%27s_law), [กฎ Zipf–Mandelbrot](https://en.wikipedia.org/wiki/Zipf%E2%80%93Mandelbrot_law), และ [กฎของ Lotka](https://en.wikipedia.org/wiki/Lotka%27s_law)।

**ฟังก์ชันซีตา** (Zeta function) เป็นวิธีการหนึ่งที่เป็นไปได้ในการ [ทำให้เป็นระเบียบ](https://en.wikipedia.org/wiki/regularization_%28physics%29) ของ [อนุกรมลู่ออก](https://en.wikipedia.org/wiki/divergent_series) และ [อินทิกรัลลู่ออก](https://en.wikipedia.org/wiki/divergent_integral) ใน [ทฤษฎีสนามควอนตัม](https://en.wikipedia.org/wiki/quantum_field_theory) ในตัวอย่างที่มีชื่อเสียงหนึ่ง ฟังก์ชันซีตาของรีมันปรากฏอย่างชัดเจนในวิธีการหนึ่งของการคำนวณ [ปรากฏการณ์แคสสิเมอร์](https://en.wikipedia.org/wiki/Casimir_effect) ฟังก์ชันซีตาก็มีประโยชน์สำหรับการวิเคราะห์ [ระบบไดนามิก](https://en.wikipedia.org/wiki/dynamical_systems) [^64]

### การปรับเสียงดนตรี

ในทฤษฎี [การปรับเสียงดนตรี](https://en.wikipedia.org/wiki/musical_tuning) ฟังก์ชันซีตาสามารถใช้หา [การแบ่งส่วนแปดเสียงเท่า](https://en.wikipedia.org/wiki/Equal_temperament) (EDOs) ที่ใกล้เคียงกับช่วงของ [อนุกรมฮาร์มอนิก](https://en.wikipedia.org/wiki/Harmonic_series_%28music%29) สำหรับค่าของ $t \in \mathbb{R}$ ที่เพิ่มขึ้น ค่าของ

$$
\left\vert \zeta \left( \frac{1}{2} + \frac{2\pi{i}}{\ln{(2)}}t \right) \right\vert
$$

ยอดสูงสุดที่อยู่ใกล้จำนวนเต็มซึ่งสอดคล้องกับ EDO ดังกล่าว.[^65] ตัวอย่างได้แก่ทางเลือกยอดนิยมเช่น 12, 19 และ 53.[^66]

### อนุกรม

ฟังก์ชันซีตาที่ประเมินค่าที่จำนวนเต็มบวกที่ห่างเท่ากันปรากฏอยู่ในการแสดงออกของอนุกรมของค่าคงที่หลายค่า[^67]
*

$$
\sum_{n=2}^\infty\bigl(\zeta(n)-1\bigr) = 1
$$

ในความเป็นจริง เทอมคู่และคี่ให้ผลบวกสองอย่าง
*

$$
\sum_{n=1}^\infty\bigl(\zeta(2n)-1\bigr)=\frac{3}{4}
$$

และ
*

$$
\sum_{n=1}^\infty\bigl(\zeta(2n+1)-1\bigr)=\frac{1}{4}
$$

รูปแบบที่ผ่านการกำหนดพารามิเตอร์ของผลบวกข้างต้นนั้นกำหนดโดย
*

$$
\sum_{n=1}^\infty(\zeta(2n)-1)\,t^{2n} = \frac{t^2}{t^2-1} + \frac{1}{2} \left(1- \pi t\cot(\pi t)\right)
$$

และ
*

$$
\sum_{n=1}^\infty(\zeta(2n+1)-1)\,t^{2n} = \frac{t^2}{t^2-1} -\frac{1}{2}\left(\psi^0(t)+\psi^0(-t) \right) - \gamma
$$

โดยมีเงื่อนไขว่า $|t| < 2$ และโดยที่ $\psi$ และ $\gamma$ คือ [ฟังก์ชันโพลีแกมมา](https://en.wikipedia.org/wiki/polygamma_function) และ [ค่าคงตัวอ็อยเลอร์–มัสเกโรนี](https://en.wikipedia.org/wiki/Euler%27s_constant) ตามลำดับ ตลอดจน
ไม่มีเนื้อหาให้แปล เนื่องจากข้อความที่ส่งมาเป็นเพียงเครื่องหมาย `*` ว่างเปล่า

$$
\sum_{n=1}^\infty \frac{\zeta(2n)-1}{n}\,t^{2n} = \log\left(\dfrac{1-t^2}{\operatorname{sinc}(\pi\,t)}\right)
$$

ทั้งหมดนี้ต่อเนื่องที่ $t=1$. ผลรวมอื่นๆ ได้แก่
*

$$
\sum_{n=2}^\infty\frac{\zeta(n)-1}{n} = 1-\gamma
$$

ไม่มีเนื้อหาให้แปลครับ เนื่องจากข้อความที่คุณให้มาคือเครื่องหมาย `*` เพียงอย่างเดียว ซึ่งไม่ใช่วิ基百科ภาษาอังกฤษหรือเนื้อหาที่สมบูรณ์ตามกฎที่กำหนด

$$
\sum_{n=1}^\infty\frac{\zeta(2n)-1}{n} = \ln 2
$$

*

$$
\sum_{n=2}^\infty\frac{\zeta(n)-1}{n} \left(\left(\tfrac{3}{2}\right)^{n-1}-1\right) = \frac{1}{3} \ln \pi
$$

ไม่มีเนื้อหาให้แปล

$$
\sum_{n=1}^\infty\bigl(\zeta(4n)-1\bigr) = \frac78-\frac{\pi}{4}\left(\frac{e^{2\pi}+1}{e^{2\pi}-1}\right)
$$

ไม่มีเนื้อหาให้แปล เนื่องจากข้อความที่ส่งมาเป็นเครื่องหมายดอกจัน (*) เท่านั้น

$$
\sum_{n=2}^\infty\frac{\zeta(n)-1}{n}\Im \bigl((1+i)^n-1-i^n\bigr) = \frac{\pi}{4}
$$

โดยที่ $\Im$ หมายถึง ส่วนจินตภาพ ของจำนวนเชิงซ้อน

อนุกรมที่น่าสนใจอีกอันหนึ่งที่สัมพันธ์กับลอการิทึมธรรมชาติของค่าคงที่เลมินิสเคต คือดังนี้
*

$$
\sum_{n=2}^\infty\left[\frac{2(-1)^n\zeta(n)}{4^n n}-\frac{(-1)^n\zeta(n)}{2^n n} \right]= \ln \left( \frac{\varpi}{2\sqrt2} \right)
$$

ยังมีสูตรอื่น ๆ อีกในบทความ [Harmonic number](https://en.wikipedia.org/wiki/Harmonic_number#Relation_to_the_Riemann_zeta_function) 

## การสรุปผล

มีฟังก์ชันซีตา (zeta function) หลายแบบที่เกี่ยวข้องกัน ซึ่งสามารถพิจารณาได้ว่าเป็นการขยายความของฟังก์ชันซีตาของรีมัน สิ่งเหล่านี้รวมถึงฟังก์ชันซีตาของฮิวริตซ์ (Hurwitz zeta function)

$$
\zeta(s,q) = \sum_{k=0}^\infty \frac{1}{(k+q)^s}
$$

การแทนอนุกรมลู่เข้ะที่ลู่เข้ะนี้ถูกเสนอโดย [Helmut Hasse](https://en.wikipedia.org/wiki/Helmut_Hasse) ในปี 1930,[^47] เปรียบเทียบดูได้ที่ [Hurwitz zeta function](https://en.wikipedia.org/wiki/Hurwitz_zeta_function) ซึ่งตรงกันกับ ฟังก์ชันซีตาของรีมัน เมื่อ $q = 1$ (ขีดจำกัดล่างของการรวมใน ฟังก์ชันซีตาของฮิวริตซ์ คือ $0$ ไม่ใช่ $1$) ฟังก์ชัน L ของดิริชเลต์ [Dirichlet $L$-functions](https://en.wikipedia.org/wiki/Dirichlet_L-function) และ ฟังก์ชันซีตาของเดเดคินด์ [Dedekind zeta function](https://en.wikipedia.org/wiki/Dedekind_zeta_function) สำหรับฟังก์ชันที่เกี่ยวข้องอื่นๆ ดูที่บทความ [zeta function](https://en.wikipedia.org/wiki/zeta_function) และ [ $L$-function](https://en.wikipedia.org/wiki/L-function)

ฟังก์ชันโพลีลอการิทึม(polylogarithm) กำหนดโดย

$$
\operatorname{Li}_s(z) = \sum_{k=1}^\infty \frac{z^k}{k^s}
$$

ซึ่งสอดคล้องกับ ฟังก์ชันซีตาของรีมัน เมื่อ $z = 1$.
ฟังก์ชัน [Clausen](https://en.wikipedia.org/wiki/Clausen_function) $Cl_s(θ)$ สามารถเลือกเป็นส่วนจริงหรือส่วนจินตภาพของ $Li_s(e^{iθ})$.

ฟังก์ชันทรานสเซนด์เลิร์ช (Lerch transcendent) กำหนดโดย

$$
\Phi(z, s, q) = \sum_{k=0}^\infty\frac {z^k} {(k+q)^s}
$$

ซึ่งตรงกับ ฟังก์ชันซีตาของรีมันน์ เมื่อ $z = 1$ และ $q = 1$ (ขีดจำกัดล่างของการรวมผลใน transcendent ของ Lerch คือ $0$ ไม่ใช่ $1$)

ฟังก์ชันซีตาหลายค่า (multiple zeta functions) (https://en.wikipedia.org/wiki/multiple_zeta_functions) ถูกนิยามโดย

$$
\zeta(s_1,s_2,\ldots,s_n) = \sum_{k_1>k_2>\cdots>k_n>0} {k_1}^{-s_1}{k_2}^{-s_2}\cdots {k_n}^{-s_n}.
$$

สามารถต่อฟังก์ชันเหล่านี้แบบวิเคราะห์ไปยังปริภูมิเชิงซ้อน $n$ มิติได้ ค่าเฉพาะที่ฟังก์ชันเหล่านี้รับเมื่อมีอาร์กิวเมนต์เป็นจำนวนเต็มบวกเรียกว่า [multiple zeta values](https://en.wikipedia.org/wiki/multiple_zeta_values) โดยนักทฤษฎีจำนวนและมีความเชื่อมโยงกับสาขาต่างๆ ใน คณิตศาสตร์ และ ฟิสิกส์ หลายสาขา

## ดูเพิ่มเติม

* [1 + 2 + 3 + 4 + ···](https://en.wikipedia.org/wiki/1_%2B_2_%2B_3_%2B_4_%2B_%C2%B7%C2%B7%C2%B7)
* [ฟังก์ชันซีตาทางคณิตศาสตร์](https://en.wikipedia.org/wiki/Arithmetic_zeta_function)
* [สมมติฐานของรีมันแบบทั่วไป](https://en.wikipedia.org/wiki/Generalized_Riemann_hypothesis)
* [คู่เลห์เมอร์](https://en.wikipedia.org/wiki/Lehmer_pair)
* [ฟังก์ชันซีตาของจำนวนเฉพาะ](https://en.wikipedia.org/wiki/Prime_zeta_function)
* [การปรับมาตรฐาน](https://en.wikipedia.org/wiki/Renormalization)
* [ฟังก์ชันซีตาของรีมัน–ซีเกิล](https://en.wikipedia.org/wiki/Riemann%E2%80%93Siegel_theta_function)
* [ZetaGrid](https://en.wikipedia.org/wiki/ZetaGrid)

## อ้างอิง

## แหล่งที่มา

* T.M. Apostol. [ฟังก์ชันซีตาของรีมันและฟังก์ชันที่เกี่ยวข้อง](https://dlmf.nist.gov/25), *NIST Digital Library of Mathematical Functions*.
* Borwein, Jonathan; Bradley, David M.; Crandall, Richard (2000). *Computational Strategies for the Riemann Zeta Function*. *J. Comput. Appl. Math.* **121**(1–2), 247–296. [2000JCoAM.121..247B](https://ui.adsabs.harvard.edu/abs/2000JCoAM.121..247B). doi:[10.1016/S0377-0427(00)00336-8](https://doi.org/10.1016/S0377-0427%2800%2900336-8).
* Cvijović, Djurdje; Klinowski, Jacek (2002). *Integral representations of the Riemann zeta function for odd-integer arguments*. *J. Comput. Appl. Math.* **142**(2), 435–439. [MR1906742](https://mathscinet.ams.org/mathscinet-getitem?mr=MR1906742). [2002JCoAM.142..435C](https://ui.adsabs.harvard.edu/abs/2002JCoAM.142..435C). doi:[10.1016/S0377-0427(02)00358-8](https://doi.org/10.1016/S0377-0427%2802%2900358-8).
* Cvijović, Djurdje; Klinowski, Jacek (1997). *Continued-fraction expansions for the Riemann zeta function and polylogarithms*. *Proc. Amer. Math. Soc.* **125**(9), 2543–2550. doi:[10.1090/S0002-9939-97-04102-6](https://doi.org/10.1090/S0002-9939-97-04102-6).
มีฉบับแปลเป็นภาษาอังกฤษของบทความของ Riemann.
* Hadamard, Jacques (1896). *Sur la distribution des zéros de la fonction ζ(s) et ses conséquences arithmétiques*. *Bulletin de la Société Mathématique de France* **14**, 199–220. doi:[10.24033/bsmf.545](https://doi.org/10.24033/bsmf.545).
อนุกรมลู่ออก*. *Clarendon Press*.
convergent series expression.)
* Ivic, Aleksandar (1985). *The Riemann Zeta Function*. *John Wiley & Sons*. ISBN 0-471-80634-X.
*Motohashi, Y. (1997). *Spectral Theory of the Riemann Zeta-Function*. *Cambridge University Press*. ISBN 0-521-44520-5.
* Karatsuba, A.A.; Voronin, S.M. (1992). *The Riemann Zeta-Function*. *W. de Gruyter*.
* Montgomery, Hugh L.; Vaughan, Robert C. (2007). *Multiplicative Number Theory. I. Classical theory*. *Cambridge University Press* **97**. ISBN 978-0-521-84903-6.
* Newman, Donald J. (1998). *Analytic Number Theory*. *Springer-Verlag* **177**. ISBN 0-387-98308-2.
* Raoh, Guo (1996). *The distribution of the logarithmic derivative of the Riemann zeta function*. *Proceedings of the London Mathematical Society* **S3–72**, 1–27. doi:[10.1112/plms/s3-72.1.1](https://doi.org/10.1112/plms/s3-72.1.1).
* Riemann, Bernhard (1859). *Über die Anzahl der Primzahlen unter einer gegebenen Grösse*. *Monatsberichte der Berliner Akademie*. [Über die Anzahl der Primzahlen unter einer gegebenen Grösse](http://www.maths.tcd.ie/pub/HistMath/People/Riemann/Zeta/). Also available in Riemann, Bernhard (1953). *Gesammelte Werke*. *Dover (1953) / Teubner (1892)*.
* Sondow, Jonathan (1994). *การลู่เข้าเชิงวิเคราะห์ของฟังก์ชันซีตาของรีมันและค่าที่จำนวนเต็มลบผ่านวิธีการแปลงอนุกรมของออยเลอร์*. *Proceedings of the American Mathematical Society* **120**(2), 421–424. doi:[10.1090/S0002-9939-1994-1172954-7](https://doi.org/10.1090/S0002-9939-1994-1172954-7). [การลู่เข้าเชิงวิเคราะห์ของฟังก์ชันซีตาของรีมันและค่าที่จำนวนเต็มลบผ่านวิธีการแปลงอนุกรมของออยเลอร์](https://www.ams.org/journals/proc/1994-120-02/S0002-9939-1994-1172954-7/S0002-9939-1994-1172954-7.pdf).
* Titchmarsh, E.C. (1986). *ทฤษฎีของฟังก์ชันซีตาของรีมัน*. *Oxford University Press*.
หลักสูตรการวิเคราะห์สมัยใหม่*. *Cambridge University Press*.
* Zhao, Jianqiang (1999). *การลู่เข้าเชิงวิเคราะห์ของฟังก์ชันซีตาหลายชั้น*. *Proceedings of the American Mathematical Society* **128**(5), 1275–1283. [MR1670846](https://mathscinet.ams.org/mathscinet-getitem?mr=MR1670846). doi:[10.1090/S0002-9939-99-05398-8](https://doi.org/10.1090/S0002-9939-99-05398-8).

## แหล่งข้อมูลภายนอก

*
* [ฟังก์ชันซีตา](https://encyclopediaofmath.org/wiki/Zeta-function), คณิตศาสตร์.
* [ฟังก์ชันซีตาของรีมัน, ใน Wolfram Mathworld](http://mathworld.wolfram.com/RiemannZetaFunction.html) — คำอธิบายที่มีแนวทางทางคณิตศาสตร์มากขึ้น
* [ตารางศูนย์ที่เลือก](http://dtc.umn.edu/~odlyzko/zeta_tables) [เก็บถาวร 17 พ.ค. 2009](https://web.archive.org/web/20090517003700/http://dtc.umn.edu/~odlyzko/zeta_tables/)
* [จำนวนเฉพาะได้แต่งงานกัน](https://web.archive.org/web/20080721030342/http://seedmagazine.com/news/2006/03/prime_numbers_get_hitched.php) คำอธิบายทั่วไปที่ไม่เป็นเทคนิคเกี่ยวกับความสำคัญของฟังก์ชันซีตาในความสัมพันธ์กับจำนวนเฉพาะ
* [ภาพรังสีของฟังก์ชันซีตา](https://arxiv.org/abs/math/0309433v1) การสำรวจที่เน้นภาพว่าซีตาเป็นจำนวนจริงหรือจำนวนจินตภาพล้วน
* [สูตรและเอกลักษณ์สำหรับฟังก์ชันซีตาของรีมัน](http://functions.wolfram.com/ZetaFunctionsandPolylogarithms/Zeta/) functions.wolfram.com
* ฟังก์ชันซีตาของรีมันและผลรวมกำลังกลับอื่นๆ (Riemann Zeta Function and Other Sums of Reciprocal Powers) ซึ่งเป็นส่วน 23.2 ของ [Abramowitz and Stegun]
* เอดเวิร์ด เฟรเนล (Edward Frenkel) (11 มีนาคม 2014). *ปัญหาทางคณิตศาสตร์มูลค่าหนึ่งล้านดอลลาร์* (Million Dollar Math Problem). *เบรดี้ ฮาราน* (Brady Haran). [ปัญหาทางคณิตศาสตร์มูลค่าหนึ่งล้านดอลลาร์](https://www.youtube.com/watch?v=d6c6uIyieoo).
* [การแปลงเม็ลลินและสมการเชิงฟังก์ชันของฟังก์ชันซีตาของรีมัน](https://combinatorialsums.risc.jku.at/papers/rfeq.pdf)—ตัวอย่างการคำนวณวิธีการแปลงเม็ลลินที่เกี่ยวข้องกับฟังก์ชันซีตาของรีมัน
* [การมองเห็นฟังก์ชันซีตาของรีมันและการต่อเนื่องเชิงวิเคราะห์](https://www.youtube.com/watch?v=sD0NjbwqlYw) วิดีโอจาก [3Blue1Brown](https://en.wikipedia.org/wiki/3Blue1Brown)

## หมายเหตุ

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
