---
title: สมมติฐานของรีมันน์
---

<figure style={{"maxWidth": "264px"}}>

![This plot of Riemann's zeta ( ζ) function (here with argument z) shows trivial zeros where ζ(z)=0, a pole where ζ(z) → ∞, the critical line of nontrivial zeros with Re(z) = 1/2 and density of absolute values.](https://pub-275e30003c354ac0862cc9839e0f952a.r2.dev/docs/math/Riemann_zeta_function_absolute_value.png)

<figcaption>

กราฟของฟังก์ชันซีตา ( $\zeta$) ของรีมันน์ (โดยมีตัวแปร $z$) แสดงจุดศูนย์แบบธรรมดา (trivial zeros) ที่ $\zeta(z)=0$ จุดเอกฐาน (pole) ที่ *ζ*(*z*) → $\infty$ เส้นวิกฤต (critical line) ของจุดศูนย์แบบไม่ธรรมดา (nontrivial zeros) ที่มี [Re(*z*)](https://en.wikipedia.org/wiki/Complex_numbers#Definition_and_basic_operations) = 1/2 และความหนาแน่นของค่าสัมบูรณ์

</figcaption>

</figure>
**สมมติฐานของรีมัน** (Riemann hypothesis) คือ [ข้อความคาดการณ์](https://en.wikipedia.org/wiki/conjecture) ที่ [ฟังก์ชันซีตาของรีมัน](./riemann_zeta_function.md) มี [ค่าศูนย์ของฟังก์ชัน](https://en.wikipedia.org/wiki/Root_of_a_function) เฉพาะที่ [จำนวนเต็มคู่](https://en.wikipedia.org/wiki/even_integer) เป็นลบ และ [จำนวนเชิงซ้อน](https://en.wikipedia.org/wiki/complex_number) ที่มี [ส่วนจริง](https://en.wikipedia.org/wiki/real_part) เท่ากับ $1/2$ หลายคนถือว่ามันคือปัญหาที่ยังไม่ได้รับการแก้ไขที่สำคัญที่สุดใน [คณิตศาสตร์บริสุทธิ์](https://en.wikipedia.org/wiki/pure_mathematics) Bombieri, Enrico (2000). *The Riemann Hypothesis – official problem description*. *สถาบันคณิตศาสตร์เคลย์* [The Riemann Hypothesis – official problem description](https://web.archive.org/web/20151222090027/http://www.claymath.org/sites/default/files/official_problem_description.pdf) มันมีความน่าสนใจมากใน [ทฤษฎีจำนวน](https://en.wikipedia.org/wiki/number_theory) เพราะมันนัยถึงผลลัพธ์เกี่ยวกับการกระจายตัวของ [จำนวนเฉพาะ](https://en.wikipedia.org/wiki/prime_numbers) มันถูกเสนอโดย [แบร์นฮาร์ท รีมัน](https://en.wikipedia.org/wiki/Bernhard_Riemann),[^1] ซึ่งมันถูกตั้งชื่อตามเขา ตามการสำรวจปี 2026 มีหลักฐานเชิงตัวเลขที่ท่วมท้นสำหรับสมมติฐานนี้ แต่ยังไม่มีการพิสูจน์ที่ทราบ.[^2]

สมมติฐานของรีมันและบางส่วนของคำทำนายทั่วไปของมัน รวมถึง [ข้อความคาดการณ์ของก็อลท์บัค](https://en.wikipedia.org/wiki/Goldbach%27s_conjecture) และ [ข้อความคาดการณ์ของจำนวนเฉพาะแฝด](https://en.wikipedia.org/wiki/twin_prime_conjecture) รวมอยู่ใน [ปัญหารายการที่แปดของดาวิท ฮิลเบิร์ท](https://en.wikipedia.org/wiki/Hilbert%27s_eighth_problem) ในรายการ [ปัญหาคณิตศาสตร์ที่ยังไม่ได้รับการแก้](https://en.wikipedia.org/wiki/Hilbert%27s_problems) ของ [ดาวิท ฮิลเบิร์ท](https://en.wikipedia.org/wiki/David_Hilbert); มันยังเป็นหนึ่งใน [ปัญหารางวัลมิลเลนเนียม](https://en.wikipedia.org/wiki/Millennium_Prize_Problems) ของ [สถาบันคณิตศาสตร์เคลย์](https://en.wikipedia.org/wiki/Clay_Mathematics_Institute) ซึ่งเสนอ [US$](https://en.wikipedia.org/wiki/US%24) 1 ล้านดอลลาร์สหรัฐสำหรับคำตอบของปัญหาใด ๆ ในรายการนี้ ชื่อเรียกนี้ยังถูกใช้สำหรับบางรูปแบบที่คล้ายคลึงกันอย่างใกล้ชิด บางส่วนได้รับการพิสูจน์แล้ว เช่น [สมมติฐานของรีมันสำหรับเส้นโค้งเหนือฟิลด์จำกัด](https://en.wikipedia.org/wiki/Riemann_hypothesis_for_curves_over_finite_fields) ซึ่งได้รับการพิสูจน์โดย [อันเดร เวย์ล์](https://en.wikipedia.org/wiki/Andr%C3%A9_Weil)

ฟังก์ชันซีตาของรีมัน $\zeta$ คือฟังก์ชัน(https://en.wikipedia.org/wiki/function_%28mathematics%29) ที่อาร์กิวเมนต์(https://en.wikipedia.org/wiki/Argument_of_a_function) ของมันอาจเป็นจำนวนเชิงซ้อนใดๆ ยกเว้น 1 และค่าของมันก็เป็นจำนวนเชิงซ้อนเช่นกัน มีศูนย์อยู่ที่จำนวนเต็มคู่ติดลบ; นั่นคือ $\zeta(s)=0$ เมื่อ $s$ เป็นหนึ่งใน $-2,-4,-6,\dots$ สิ่งเหล่านี้เรียกว่า *ศูนย์แบบธรรมดา* ฟังก์ชันซีตายังเป็นศูนย์สำหรับค่าอื่นๆ ของ $s$ ซึ่งเรียกว่า *ศูนย์แบบไม่ธรรมดา* สมมติฐานของรีมันเกี่ยวข้องกับตำแหน่งของศูนย์แบบไม่ธรรมดาดังกล่าว และระบุว่า:

> ส่วนจริงของศูนย์ที่ไม่สำคัญทุกศูนย์ของฟังก์ชันซีตาของรีมันคือ $\frac{1}{2}$

ดังนั้นสมมติฐานนี้จึงระบุว่าศูนย์ที่ไม่สำคัญทั้งหมดตั้งอยู่บน *เส้นวิกฤต* ซึ่งประกอบด้วยจำนวนเชิงซ้อน $\tfrac{1}{2}+it$ โดยที่ $t$ เป็นจำนวนจริน  และ $i$ เป็นหน่วยจินตภาพ 

## ฟังก์ชันซีตาของรีมันน์

**ฟังก์ชันซีตาของรีมัน** (Riemann zeta function) คือฟังก์ชันที่กำหนดสำหรับจำนวนเชิงซ้อน $s$ โดยมีส่วนจริงมากกว่า 1 ผ่าน [อนุกรม](https://en.wikipedia.org/wiki/infinite_series) [การลู่เข้าสัมบูรณ์](https://en.wikipedia.org/wiki/Absolute_convergence)

$$
\zeta(s) = \sum_{n=1}^\infty \frac{1}{n^s} = \frac{1}{1^s} + \frac{1}{2^s} + \frac{1}{3^s} + \cdots
$$

[เลอ็อนฮาร์ท อ็อยเลอร์](https://en.wikipedia.org/wiki/Leonhard_Euler) ได้พิจารณาอนุกรมนี้ในช่วงทศวรรษ 1730 สำหรับค่าจริงของ $s$ โดยร่วมกับคำตอบของเขากับ [ปัญหบาเซิล](https://en.wikipedia.org/wiki/Basel_problem) และเขายังได้พิสูจน์ว่าค่าของมันเท่ากับ [ผลคูณออยเลอร์](https://en.wikipedia.org/wiki/Euler_product) 

$$
\zeta(s) = \prod_{p \text{ prime}} \frac{1}{1-p^{-s}}= \frac{1}{1-2^{-s}}\cdot\frac{1}{1-3^{-s}}\cdot\frac{1}{1-5^{-s}}\cdot\frac{1}{1-7^{-s}} \cdots
$$

ซึ่งผลคูณอนันต์ นี้ขยายครอบคลุมถึงจำนวนเฉพาะ $p$ ทั้งหมด [^3]

สมมติฐานของรีมัน (Riemann hypothesis) กล่าวถึงศูนย์ที่อยู่ภายนอก [บริเวณของการลู่เข้า](https://en.wikipedia.org/wiki/region_of_convergence) ของอนุกรมนี้และผลคูณของออยเลอร์ เพื่อให้ความหมายกับสมมติฐานนี้ จำเป็นต้อง [ขยายเชิงวิเคราะห์](https://en.wikipedia.org/wiki/Analytic_continuation) ฟังก์ชันเพื่อให้ได้รูปแบบที่มีผลใช้ได้กับทุกจำนวนเชิงซ้อน $s$ เนื่องจากฟังก์ชันซีตาเป็น [ฟังก์ชันที่มีจุดเอกฐาน](https://en.wikipedia.org/wiki/meromorphic) การเลือกทุกวิธีในการดำเนินการขยายเชิงวิเคราะห์นี้จะนำไปสู่ผลลัพธ์เดียวกัน โดย [ทฤษฎีบทเอกลักษณ์](https://en.wikipedia.org/wiki/identity_theorem) ขั้นตอนแรกในการขยายนี้สังเกตว่าอนุกรมของฟังก์ชันซีตาและ [ฟังก์ชันอีตาของดรีเคล](https://en.wikipedia.org/wiki/Dirichlet_eta_function) สอดคล้องกับความสัมพันธ์

$$
\left(1-\frac{2}{2^s}\right)\zeta(s) = \eta(s) = \sum_{n=1}^\infty \frac{(-1)^{n+1}}{n^s} = \frac{1}{1^s} - \frac{1}{2^s} + \frac{1}{3^s} - \cdots,
$$

ภายในบริเวณของการลู่เข้าของอนุกรมทั้งสอง แต่อนุกรมของฟังก์ชันอีตาของดรีเคลทางด้านขวาจะลู่เข้านั้นไม่เพียงแต่เมื่อส่วนจริงของ $s$ มากกว่าหนึ่ง แต่โดยทั่วไปแล้วไม่ว่า $s$ จะมีส่วนจริงเป็นบวก ดังนั้น ฟังก์ชันซีตาจึงสามารถนิยามใหม่เป็น $\eta(s)/(1-2/2^s)$ ขยายมันจาก $\operatorname{Re}(s)>1$ ไปยังโดเมนที่ใหญ่กว่า $\operatorname{Re}(s)>0$ ยกเว้นจุดที่ $1-2/2^s$ เป็นศูนย์ นี่คือจุด $s = 1 + 2\pi in/\log 2$ ซึ่ง $n$ สามารถเป็นจำนวนเต็มที่ไม่เป็นศูนย์ใดๆ ได้; ฟังก์ชันซีตาสามารถขยายไปยังค่าเหล่านี้ได้ด้วยโดยการใช้ลิมิต (ดูบทความเกี่ยวกับ [ฟังก์ชันอีตาของดีรีเคล](https://en.wikipedia.org/wiki/Dirichlet_eta_function#Landau%27s_problem_with_%CE%B6%28s%29_%3D_%CE%B7%28s%29/0_and_solutions)) ให้ค่าจำกัดสำหรับทุกค่าของ $s$ ที่มีส่วนจริงเป็นบวก ยกเว้น [simple pole](https://en.wikipedia.org/wiki/simple_pole) ที่ $s = 1$

ในแถบ $0<\operatorname{Re}(s)<1$ การขยายของฟังก์ชันซีตาของรีมันนี้สอดคล้องกับ [สมการเชิงฟังก์ชัน](./riemann_zeta_function.md#สมการเชิงฟังก์ชันของรีมันน์)

$$
\zeta(s) = 2^s\pi^{s-1}\ \sin\left(\frac{\pi s}{2}\right)\ \Gamma(1-s)\ \zeta(1-s).
$$

จากนั้นสามารถนิยาม $\zeta(s)$ สำหรับจำนวนเชิงซ้อนที่ไม่เป็นศูนย์ที่เหลือทั้งหมด $s$ ( $\operatorname{Re}(s)\leq 0$ และ $s\neq 0$) โดยประยุกต์สมการนี้ภายนอกแถบ และให้ $\zeta(s)$ เท่ากับด้านขวาของสมการเสมอเมื่อ $s$ มีส่วนจริงที่ไม่เป็นบวก (และ $s\neq 0$)

หาก $s$ เป็นจำนวนคู่ติดลบ แล้ว $\zeta(s)=0$ เพราะตัวประกอบ $\sin(\pi s/2)$ หายไป; สิ่งเหล่านี้คือ *ศูนย์ที่เรียบง่าย* ของฟังก์ชันซีตา (หาก $s$ เป็นจำนวนคู่บวก ข้อโต้แย้งนี้ใช้ไม่ได้เพราะศูนย์ของฟังก์ชัน [sine](https://en.wikipedia.org/wiki/sine) ถูกหักล้างด้วยขั้วของฟังก์ชัน [ฟังก์ชันแกมมา](https://en.wikipedia.org/wiki/gamma_function) เมื่อมันรับค่าจำนวนติดลบเป็นอาร์กิวเมนต์)

ค่า [*ζ*(0) = −1/2](https://en.wikipedia.org/wiki/1_%2B_1_%2B_1_%2B_1_%2B_%E2%8B%AF) ไม่ได้กำหนดโดยสมการเชิงฟังก์ชัน แต่เป็นค่าลิมิตของ $\zeta(s)$ เมื่อ $s$ เข้าใกล้ศูนย์ สมการเชิงฟังก์ชันยังบ่งชี้ว่า ฟังก์ชันซีตา ไม่มีศูนย์ที่มีส่วนจริงเป็นลบนอกจากศูนย์แบบธรรมดา ดังนั้นศูนย์แบบไม่ธรรมดาทั้งหมดจึงอยู่ใน *critical strip* ซึ่ง $s$ มีส่วนจริงอยู่ระหว่าง 0 ถึง 1

<figure>

![Riemann zeta function along the critical line with Re(s) = 1/2. Real values are shown on the horizontal axis and imaginary values are on the vertical axis. Re(ζ(1/2 + it)), Im(ζ(1/2 + it)) is plotted with t ranging between −30 and 30.](https://pub-275e30003c354ac0862cc9839e0f952a.r2.dev/docs/math/ParametricZeta.svg.png)

<figcaption>

ฟังก์ชันซีตาของรีมัน (Riemann zeta function) ตามเส้นวิกฤตที่มี Re(*s*) = 1/2 ค่าจริงแสดงบนแกนแนวนอน และค่าจินตภาพแสดงบนแกนแนวตั้ง ค่า Re(*ζ*(1/2 + *it*)) และ Im(*ζ*(1/2 + *it*)) ถูกพล็อตโดยให้ *t* อยู่ในช่วงระหว่าง −30 ถึง 30.[^4]

</figcaption>

</figure>

<figure>

![3D animation showing critical strip (blue, where s has real part between 0 and 1), critical line (red, for real part of s equals 0.5) and zeros (cross between red and orange): [x,y,z] = [Re(ζ(r + it)), Im(ζ(r + it)), t] with 0.1≤ r≤ 0.9 and 1≤ t≤ 51.](https://pub-275e30003c354ac0862cc9839e0f952a.r2.dev/docs/math/Riemann3d_Re_0.1_to_0.9_Im_1_to_51.ogg.jpg)

<figcaption>

ภาพสามมิติแสดงแถบวิกฤต (สีน้ำเงิน, บริเวณที่ $s$ มีส่วนจริงอยู่ระหว่าง 0 และ 1), เส้นวิกฤต (สีแดง, สำหรับส่วนจริงของ $s$ เท่ากับ 0.5) และศูนย์ (เครื่องหมายกากบาทระหว่างสีแดงและสีส้ม): [*x*,*y*,*z*] = [Re(*ζ*(*r* + *it*)), Im(*ζ*(*r* + *it*)), *t*] โดยที่ $0.1\leq r\leq 0.9$ และ $1\leq t\leq 51$

</figcaption>

</figure>

<figure>

![The real part (red) and imaginary part (blue) of the Riemann zeta function ζ(s) along the critical line in the complex plane with real part Re(s)=1/2. The first nontrivial zeros, where ζ(s) equals zero, occur where both curves touch the horizontal x-axis, for complex numbers with imaginary parts equaling ± 14.135, ± 21.022 and ± 25.011.](https://pub-275e30003c354ac0862cc9839e0f952a.r2.dev/docs/math/RiemannCriticalLine.svg.png)

<figcaption>

**ส่วนจริง** (สีแดง) และ **ส่วนจินตภาพ** (สีน้ำเงิน) ของ ฟังก์ชันซีตาของรีมัน $\zeta(s)$ ตามเส้นวิกฤตใน [ระนาบเชิงซ้อน](https://en.wikipedia.org/wiki/complex_plane) โดยมีส่วนจริง $\operatorname{Re}(s)=1/2$ จุดศูนย์ [ที่ไม่สำคัญ](https://en.wikipedia.org/wiki/Triviality_%28mathematics%29) จุดแรก ซึ่ง $\zeta(s)$ มีค่าเท่ากับศูนย์ เกิดขึ้นที่จุดที่เส้นโค้งทั้งสองสัมผัสกับแกน $x$ แนวนอน สำหรับจำนวนเชิงซ้อนที่มีส่วนจินตภาพเท่ากับ $\pm 14.135$, $\pm 21.022$ และ $\pm 25.011$

</figcaption>

</figure>

## กำเนิด

> ... มีความเป็นไปได้สูงมากที่รากทั้งหมดจะเป็นจำนวนจริง อย่างไรก็ตาม ย่อมต้องการการพิสูจน์ที่เข้มงวดกว่านี้; แต่ฉันได้วางการค้นหาสิ่งนั้นไว้一旁ชั่วคราว หลังจากการพยายามอย่างเปล่าผลเพียงไม่กี่ครั้ง เนื่องจากมันดูเหมือนไม่จำเป็นสำหรับวัตถุประสงค์หลักของการศึกษาของฉันในขั้นต่อไป
>
> ... มีความเป็นไปได้สูงมากที่รากทั้งหมดจะเป็นจำนวนจริง แน่นอนว่าคนทั่วไปย่อมต้องการการพิสูจน์ที่เข้มงวดที่นี่; ฉันได้วางการค้นหาสิ่งนี้ไว้一旁ชั่วคราว หลังจากการพยายามอย่างเปล่าผลเพียงไม่กี่ครั้ง เนื่องจากมันดูเหมือนไม่จำเป็นสำหรับวัตถุประสงค์หลักของการศึกษาของฉันในขั้นต่อไป
>
> — *คำกล่าวของรีมันน์เกี่ยวกับสมมติฐานของรีมันน์ จาก Riemann, Bernhard (1859). Ueber die Anzahl der Primzahlen unter einer gegebenen Grösse. Monatsberichte der Berliner Akademie. [Ueber die Anzahl der Primzahlen unter einer gegebenen Grösse](http://www.maths.tcd.ie/pub/HistMath/People/Riemann/Zeta/).. (เขาได้กล่าวถึงรูปแบบหนึ่งของฟังก์ชันซีตา ที่มีการดัดแปลงในลักษณะที่เส้นจำนวนจริงจะถูกแมปไปยังเส้นวิกฤต)*
> เมื่อรีมันน์เสียชีวิต มีบันทึกหนึ่งฉบับถูกพบในเอกสารของเขา ซึ่งระบุว่า "คุณสมบัติของ *ζ*(*s*) (ฟังก์ชันที่เกี่ยวข้อง) นี้ถูกรายงานจากนิพจน์ของมัน ซึ่งอย่างไรก็ตาม ฉันไม่สามารถทำให้เรียบง่ายพอที่จะตีพิมพ์มันได้"
>
> เรายังคงไม่มีแนวคิดแม้แต่น้อยเกี่ยวกับนิพจน์นั้นอาจจะเป็นอะไรได้บ้าง เกี่ยวกับคุณสมบัติที่เขาได้กล่าวออกมาอย่างง่ายๆ นั้น มีเวลาผ่านไปประมาณสามสิบปีก่อนที่ฉันจะสามารถพิสูจน์ได้ทั้งหมดยกเว้นหนึ่งข้อ [สมมติฐานของรีมันน์เอง]
>
> — [ฌัก อดามาร์](https://en.wikipedia.org/wiki/Jacques_Hadamard), *จิตสำนึกของนักคณิตศาสตร์*

แรงจูงใจดั้งเดิมของรีมันน์ในการศึกษาฟังก์ชันซีตาและศูนย์ของมันคือปรากฏการณ์ของมันใน [สูตรชัดเจน](https://en.wikipedia.org/wiki/Explicit_formulae_%28L-function%29) ของเขาสำหรับ [จำนวนจำนวนเฉพาะ](https://en.wikipedia.org/wiki/prime-counting_function) $\pi(x)$ น้อยกว่าหรือเท่ากับจำนวนที่กำหนด $x$ ซึ่งเขาตีพิมพ์ในบทความปี 1859 "[On the Number of Primes Less Than a Given Magnitude](https://en.wikipedia.org/wiki/On_the_Number_of_Primes_Less_Than_a_Given_Magnitude)" สูตรของเขานั้นกำหนดในรูปของฟังก์ชันที่เกี่ยวข้อง

$$
\Pi(x) = \pi(x) + \frac{\pi(x^{1/2})}{2} +\frac{\pi(x^{1/3})}{3} + \frac{\pi(x^{1/4})}{4} + \frac{\pi(x^{1/5})}{5} +\frac{\pi(x^{1/6})}{6} +\cdots
$$

ซึ่งนับจำนวนจำนวนเฉพาะและกำลังของจำนวนเฉพาะจนถึง $x$ โดยนับกำลังของจำนวนเฉพาะ [prime power](https://en.wikipedia.org/wiki/prime_power) $p^n$ เป็น $1/n$ จำนวนของจำนวนเฉพาะสามารถกู้คืนได้จากฟังก์ชันนี้โดยใช้ [Möbius inversion formula](https://en.wikipedia.org/wiki/M%C3%B6bius_inversion_formula):

$$
\begin{align}
\pi(x) &= \sum_{n=1}^\infty \frac{\mu(n)} n \Pi(x^{1/n}) \\
       &= \Pi(x) -\frac{1}{2}\Pi(x^{1/2}) - \frac{1}{3}\Pi(x^{1/3}) - \frac{1}{5}\Pi(x^{1/5}) + \frac{1}{6} \Pi(x^{1/6}) -\cdots,
\end{align}
$$

ซึ่ง $\mu$ คือ [ฟังก์ชันมูบิอุส](https://en.wikipedia.org/wiki/M%C3%B6bius_function) สูตรของรีมันน์จึงเป็น

  $\Pi_0(x) = \operatorname{li}(x) - \sum_\rho \operatorname{li}(x^\rho) -\log 2 + \int_x^\infty\frac{dt}{t(t^2-1) \log t}$,

ซึ่งผลบวกนั้นเป็นผลบวกเหนือศูนย์ที่ไม่สำคัญ (nontrivial zeros) ของฟังก์ชันซีตา (zeta function) และที่ซึ่ง $\Pi_0$ เป็นเวอร์ชันที่ถูกดัดแปลงเล็กน้อยจาก $\Pi$ โดยแทนค่าของมันที่จุดของ [ความไม่ต่อเนื่อง](https://en.wikipedia.org/wiki/Discontinuity_%28mathematics%29) ด้วยค่าเฉลี่ยของขีดจำกัดบนและล่างของมัน:

$$
\Pi_0(x) = \lim_{\varepsilon \to 0}\frac{\Pi(x-\varepsilon) + \Pi(x+\varepsilon)}2.
$$

ผลรวมในสูตรของรีมันน์ไม่ได้ลู่เข้านอย่างสมบูรณ์ แต่สามารถคำนวณได้โดยการจัดลำดับศูนย์ $\rho$

$$
\operatorname{li}(x) = \int_0^x \frac{dt}{\log t}.
$$

พจน์ $\operatorname{li}(x^\rho)$ ที่เกี่ยวข้องกับศูนย์ของฟังก์ชันซีตาต้องการความระมัดระวังในการนิยาม เนื่องจาก $\operatorname{li}$ มีจุดกิ่งที่ 0 และ 1 และนิยามขึ้น (สำหรับ $x>1$) โดยการต่อเนื่องเชิงวิเคราะห์ในตัวแปรเชิงซ้อน $\rho$ ในบริเวณ $\operatorname{Re}(\rho)>0$; นั่นคือ พวกมันควรจะถูกพิจารณาเป็น [Ei](https://en.wikipedia.org/wiki/Exponential_integral)(*ρ* log *x*) พจน์อื่นๆ ก็สอดคล้องกับศูนย์เช่นกัน: พจน์หลัก $\operatorname{li}(x)$ มาจากขั้วที่ $s = 1$ ซึ่งถูกพิจารณาเป็นศูนย์ที่มีหลายหลาก $-1$ และพจน์เล็กๆ ที่เหลือมาจากรูปศูนย์ที่เรียบง่าย สำหรับกราฟของผลรวมของพจน์แรกๆ ของอนุกรมนี้ดูที่ Riesel, Hans; Göhl, Gunnar (1970). *Some calculations related to Riemann's prime number formula*. *Mathematics of Computation* **24**(112), 969–983. [MR0277489](https://mathscinet.ams.org/mathscinet-getitem?mr=MR0277489). [JSTOR 2004630](https://www.jstor.org/stable/2004630). doi:[10.2307/2004630](https://doi.org/10.2307/2004630). [Some calculations related to Riemann's prime number formula](https://www.ams.org/journals/mcom/1970-24-112/S0025-5718-1970-0277489-3/S0025-5718-1970-0277489-3.pdf). หรือ Zagier, Don (1977). *The first 50 million prime numbers*. *Math. Intelligencer* **1**, 7–19. [MR643810](https://mathscinet.ams.org/mathscinet-getitem?mr=MR643810). doi:[10.1007/BF03039306](https://doi.org/10.1007/BF03039306). [The first 50 million prime numbers](https://web.archive.org/web/20090327181245/http://modular.math.washington.edu/edu/2007/simuw07/misc/zagier-the_first_50_million_prime_numbers.pdf).

สูตรนี้ระบุว่าศูนย์ของฟังก์ชันซีตาของรีมันควบคุมการแกว่งกวัดของจำนวนเฉพาะรอบตำแหน่งที่ "คาดหวัง" ของพวกมัน รีมันรู้ว่าศูนย์ที่ไม่สำคัญ (non-trivial zeros) ของฟังก์ชันซีตาถูกกระจายแบบสมมาตรเกี่ยวกับเส้น $s = 1/2 + it$ และเขารู้ว่าศูนย์ที่ไม่สำคัญของมันทั้งหมดต้องอยู่ในช่วง $0\leq \operatorname{Re}(s)\leq 1$ เขาตรวจสอบว่าศูนย์บางตัวอยู่บนเส้นวิกฤตที่มีส่วนจริงเท่ากับ $1/2$ และเสนอว่าทั้งหมดทำเช่นนี้; นี่คือสมมติฐานของรีมัน

> ผลลัพธ์นี้ดึงดูดจินตนาการของนักคณิตศาสตร์ส่วนใหญ่เพราะเป็นเรื่องที่ไม่คาดคิด เชื่อมโยงสองสาขาที่ดูเหมือนไม่เกี่ยวข้องกันในคณิตศาสตร์; นั่นคือ [ทฤษฎีจำนวน](https://en.wikipedia.org/wiki/number_theory) ซึ่งเป็นการศึกษาสิ่งที่ไม่ต่อเนื่อง และ [การวิเคราะห์เชิงซ้อน](https://en.wikipedia.org/wiki/complex_analysis) ซึ่งเกี่ยวข้องกับกระบวนการต่อเนื่อง

## ผลกระทบ

การใช้ประโยชน์ในทางปฏิบัติของสมมติฐานของรีมันน์ (Riemann hypothesis) รวมถึงหลายข้อเสนอที่ทราบว่าเป็นจริงภายใต้สมมติฐานของรีมันน์ และบางข้อเสนอที่สามารถแสดงได้ว่าเทียบเท่ากับสมมติฐานของรีมันน์

### การกระจายของจำนวนเฉพาะ

[Riemann's explicit formula](https://en.wikipedia.org/wiki/Riemann%27s_explicit_formula) สำหรับ [จำนวนเฉพาะน้อยกว่าจำนวนที่กำหนด](https://en.wikipedia.org/wiki/prime-counting_function) ระบุว่า ในรูปของผลรวมเหนือศูนย์ของ ฟังก์ชันซีตาของรีมันน์ ขนาดของการแกว่งกวัดของจำนวนเฉพาะรอบตำแหน่งที่คาดหวังนั้นถูกควบคุมโดยส่วนจริงของศูนย์ของฟังก์ชันซีตา ในทางเฉพาะเจาะจง เทอมความคลาดเคลื่อนใน [ทฤษฎีบทจำนวนเฉพาะ](https://en.wikipedia.org/wiki/prime_number_theorem) มีความเกี่ยวข้องอย่างใกล้ชิดกับตำแหน่งของศูนย์ ตัวอย่างเช่น ถ้า $\beta$ คือ [ขอบเขตบน](https://en.wikipedia.org/wiki/upper_bound) ของส่วนจริงของศูนย์ แล้ว[^5]
โดยที่ $\pi(x)$ คือ ฟังก์ชันนับจำนวนเฉพาะ และ $\operatorname{li}(x)$ คือ ฟังก์ชันอินทิกรัลลอการิทึม
เป็นที่ทราบกันอยู่แล้วว่า $1/2\leq\beta\leq 1$ Ingham, A.E. (1932). *The Distribution of Prime Numbers*. *Cambridge University Press* **30**, 82.
<figure style={{"maxWidth": "308px"}}>

![Corrections to an estimate of the prime-counting function using zeros of the zeta function. The magnitude of the correction term is determined by the real part of the zero being added in the correction.](https://pub-275e30003c354ac0862cc9839e0f952a.r2.dev/docs/math/Riemann_Explicit_Formula.gif)

<figcaption>

การแก้ไขการประมาณค่าของ ฟังก์ชันนับจำนวนเฉพาะ โดยใช้ศูนย์ของ ฟังก์ชันซีตา ขนาดของพจน์การแก้ไขถูกกำหนดโดยส่วนจริงของศูนย์ที่ถูกเพิ่มเข้าไปในการแก้ไข

</figcaption>

</figure>
เฮล์เกอ ฟอน โคค (Helge von Koch) ได้พิสูจน์ว่าสมมติฐานของรีมัน (Riemann hypothesis) นำไปสู่ขอบเขตที่ดีที่สุดที่เป็นไปได้สำหรับความคลาดเคลื่อนของทฤษฎีบทจำนวนเฉพาะ (prime number theorem) [^6] ผลลัพธ์ที่แม่นยำของฟอน โคค ซึ่งมาจากโชห์นเฟลด์, โลเวลล์ (1976). *ขอบเขตที่คมชัดกว่าสำหรับฟังก์ชันเชบิเชฟ θ(x) และ ψ(x). II*. *คณิตศาสตร์ของการคำนวณ* **30**(134), 337–360. [MR0457374](https://mathscinet.ams.org/mathscinet-getitem?mr=MR0457374). [JSTOR 2005976](https://www.jstor.org/stable/2005976). doi:[10.2307/2005976](https://doi.org/10.2307/2005976)., กล่าวว่าสมมติฐานของรีมัน (Riemann hypothesis) นำไปสู่

:

$$
|\pi(x) - \operatorname{li}(x)| < \frac{1}{8\pi} \sqrt{x} \log(x)
$$

สำหรับทุก $x\geq 2657$ สโคลนเฟลด์, ลอเวลล์ (1976). *ขอบเขตที่คมชัดกว่าสำหรับฟังก์ชันเชบิเชฟ θ(x) และ ψ(x). II*. *คณิตศาสตร์ของการคำนวณ* **30**(134), 337–360. [MR0457374](https://mathscinet.ams.org/mathscinet-getitem?mr=MR0457374). [JSTOR 2005976](https://www.jstor.org/stable/2005976). doi:[10.2307/2005976](https://doi.org/10.2307/2005976). ยังแสดงให้เห็นว่าสมมติฐานของรีมันน์มีนัย

$$
|\psi(x) - x| < \frac{1}{8\pi} \sqrt{x} \log^2 x
$$

สำหรับทุก $x\geq 73.2$ โดยที่ $\psi(x)$ คือ [ฟังก์ชันที่สองของเชบิเชฟ](https://en.wikipedia.org/wiki/Chebyshev_function)

อาเดรียน ดึเดก[^7] ได้พิสูจน์ว่าสมมติฐานของรีมัน ([สมมติฐานของรีมัน](./riemann_hypothesis.md)) นั้นนัยสำคัญว่า สำหรับ $x \geq 2$ จะมีจำนวนเฉพาะ $p$ ที่สอดคล้องกับ
  $x - \frac{4}{\pi} \sqrt x \log x < p \leq x$.
ค่าคงที่ $4/\pi$ อาจลดลงเหลือ $1+\varepsilon$ ได้ก็ต่อเมื่อ $x$ มีค่ามากเพียงพอ นี่เป็นรูปแบบที่ชัดเจนของทฤษฎีบทของ [Cramér](https://en.wikipedia.org/wiki/Cram%C3%A9r)

### การเติบโตของฟังก์ชันเลขคณิต

สมมติฐานของรีมัน (Riemann hypothesis) บ่งชี้ขอบเขตที่เข้มแข็งต่อการเติบโตของฟังก์ชันเลขคณิตอื่นๆ อีกมากมาย นอกเหนือจากฟังก์ชันนับจำนวนเฉพาะข้างต้น

ตัวอย่างหนึ่งเกี่ยวข้องกับ [ฟังก์ชันมูบิอุส](https://en.wikipedia.org/wiki/M%C3%B6bius_function) *μ* คำกล่าวที่ว่าสมการ

$$
\frac{1}{\zeta(s)} = \sum_{n=1}^\infty \frac{\mu(n)}{n^s}
$$

เป็นจริงสำหรับทุก *s* ที่มีส่วนจริงมากกว่า 1/2 โดยที่ผลรวมทางด้านขวามีการลู่เข้า เทียบเท่ากับสมมติฐานของรีมัน จากสิ่งนี้เราสามารถสรุปได้เช่นกันว่าถ้า [ฟังก์ชันเมิร์ตส์](https://en.wikipedia.org/wiki/Mertens_function) ถูกนิยามโดย

$$
M(x) = \sum_{n \le x} \mu(n)
$$

ดังนั้นข้อกล่าวอ้างที่ว่า

$$
M(x) = O\left(x^{\frac{1}{2}+\varepsilon}\right)
$$

สำหรับทุกค่าบวก *ε* นั้นเทียบเท่ากับสมมติฐานของรีมัน ([J. E. Littlewood](https://en.wikipedia.org/wiki/John_Edensor_Littlewood), 1912; ดูตัวอย่างเช่น: ย่อหน้า 14.25 ใน Titchmarsh, Edward Charles (1986). *The theory of the Riemann zeta-function*. *The Clarendon Press Oxford University Press*. ISBN 978-0-19-853369-6. [MR882550](https://mathscinet.ams.org/mathscinet-getitem?mr=MR882550).). ดีเทอร์มิแนนตของเมทริกซ์ Redheffer ขนาด *n* เท่ากับ *M*(*n*) ดังนั้นสมมติฐานของรีมันจึงสามารถกล่าวได้ว่าเป็นเงื่อนไขเกี่ยวกับการเติบโตของดีเทอร์มิแนนตเหล่านี้ ผลลัพธ์ของ Littlewood ได้รับการปรับปรุงหลายครั้งนับตั้งแต่ตอนนั้น โดย เอ็ทมุนท์ ลันเดา,[^8] Edward Charles Titchmarsh,[^9] Helmut Maier และ Hugh Montgomery,[^10] และ Kannan Soundararajan.[^11] ผลลัพธ์ของ Soundararajan คือว่า โดยสมมติฐานของสมมติฐานของรีมัน

$$
M(x) = O\left(x^{1/2}\exp\left((\log x)^{1/2}(\log \log x)^{14}\right)\right).
$$

สมมติฐานของรีมัน (Riemann hypothesis) กำหนดขอบเขตที่ค่อนข้างแคบต่อการเติบโตของ *M* เนื่องจาก Odlyzko, A. M.; te Riele, H. J. J. (1985). *Disproof of the Mertens conjecture*. *Journal für die reine und angewandte Mathematik* **1985**(357), 138–160. [MR783538](https://mathscinet.ams.org/mathscinet-getitem?mr=MR783538). doi:[10.1515/crll.1985.357.138](https://doi.org/10.1515/crll.1985.357.138). [Disproof of the Mertens conjecture](https://archive.today/20120711011237/http://gdz.sub.uni-goettingen.de/no_cache/dms/load/img/?IDDOC=262633). ได้พิสูจน์ว่าข้อความคาดการณ์ของเมอร์เท็นส (Mertens conjecture) ซึ่งแข็งแกร่งกว่าเล็กน้อยนั้นเป็นเท็จ

$$
|M(x)| \le \sqrt x.
$$

ผลอีกอย่างหนึ่งที่สัมพันธ์กันอย่างใกล้ชิดนั้นเป็นผลงานของ Björner, Anders (2011) *A cell complex in number theory* *Advances in Applied Mathematics* **46**(1–4), 71–85. [arXiv:1101.5704](https://arxiv.org/abs/1101.5704). doi:[10.1016/j.aam.2010.09.007](https://doi.org/10.1016/j.aam.2010.09.007). ซึ่งระบุว่าสมมติฐานของรีมัน (Riemann hypothesis) นั้นเทียบเท่ากับการกล่าวถึงลักษณะของออยเลอร์ (Euler characteristic) ของคอมเพล็กซ์เชิงเดี่ยว (simplicial complex) ที่กำหนดโดยโครงตาข่ายของจำนวนเต็มภายใต้การหารลงตัวคือ $o(n^{1/2+\epsilon})$ สำหรับทุก $\epsilon>0$ (ดู [incidence algebra](https://en.wikipedia.org/wiki/incidence_algebra))

สมมติฐานของรีมัน (Riemann hypothesis) เป็นสมมูลกับข้อความคาดการณ์อื่นๆ หลายข้อเกี่ยวกับอัตราการเติบโตของฟังก์ชันเลขคณิตอื่นๆ นอกเหนือจาก *μ*(*n*) ตัวอย่างทั่วไปคือ [Robin's theorem](https://en.wikipedia.org/wiki/Robin%27s_theorem), Robin, G. (1984). *Grandes valeurs de la fonction somme des diviseurs et hypothèse de Riemann*. *Journal de Mathématiques Pures et Appliquées* **63**(2), 187–213. [MR774171](https://mathscinet.ams.org/mathscinet-getitem?mr=MR774171). ซึ่งระบุว่าถ้า *σ*(*n*) คือ [sigma function](https://en.wikipedia.org/wiki/divisor_function) ที่กำหนดโดย

$$
\sigma(n) = \sum_{d\mid n} d
$$

แล้ว

$$
\sigma(n) < e^\gamma n \log \log n
$$

สำหรับทุก *n* > 5040 [ก็ต่อเมื่อ](https://en.wikipedia.org/wiki/if_and_only_if) สมมติฐานของรีมันเป็นจริง โดยที่ *γ* คือ [ค่าคงตัวอ็อยเลอร์–มัสเกโรนี](https://en.wikipedia.org/wiki/Euler%E2%80%93Mascheroni_constant)

ขอบเขตที่เกี่ยวข้องถูกนำเสนอโดย [เจฟฟรีย์ ลาการาซ](https://en.wikipedia.org/wiki/Jeffrey_Lagarias) ในปี 2002 ซึ่งพิสูจน์ว่าสมมติฐานของรีมันเทียบเท่ากับข้อความที่ว่า:

$$
\sigma(n) < H_n + \log(H_n)e^{H_n}
$$

สำหรับทุก [จำนวนธรรมชาติ](https://en.wikipedia.org/wiki/natural_number) *n* > 1 โดยที่ $H_n$ คือ *n*th [จำนวนฮาร์มอนิก](https://en.wikipedia.org/wiki/harmonic_number)[^12]

สมมติฐานของรีมันน์ (Riemann hypothesis) ก็เป็นจริงก็ต่อเมื่ออสมการ (inequality)

$$
\frac{n}{\varphi (n)}<e^\gamma \log\log n+\frac{e^\gamma (4+\gamma-\log 4\pi)}{\sqrt{\log n}}
$$

เป็นจริงสำหรับทุก *n* ≥ 120569# โดยที่ *φ*(*n*) คือ [ฟังก์ชันออยเลอร์](https://en.wikipedia.org/wiki/Euler%27s_totient_function) และ 120569# คือ [ผลคูณของ](https://en.wikipedia.org/wiki/Primorial) 120569 จำนวนเฉพาะแรก Broughan, Kevin (2017). *สมการสมมติฐานของรีมัน*. *มหาวิทยาลัยเคมบริดจ์*. ISBN 978-1108290784, Corollary 5.35.

อีกตัวอย่างหนึ่งถูกค้นพบโดย [Jérôme Franel](https://en.wikipedia.org/wiki/J%C3%A9r%C3%B4me_Franel) และขยายผลโดย [Landau](https://en.wikipedia.org/wiki/Edmund_Landau) (ดู Franel, J.; Landau, E. (1924). *Les suites de Farey et le problème des nombres premiers" (Franel, 198–201); "Bemerkungen zu der vorstehenden Abhandlung von Herrn Franel (Landau, 202–206)*. *Göttinger Nachrichten*, 198–206.) สมมติฐานของรีมัน (riemann hypothesis) เทียบเท่ากับหลายข้อความที่แสดงว่าพจน์ของ [Farey sequence](https://en.wikipedia.org/wiki/Farey_sequence) มีระเบียบค่อนข้างสม่ำเสมอ หนึ่งในการเทียบเท่าดังกล่าวคือดังนี้: ถ้า *F*<sub>*n*</sub> คือลำดับของ Farey ของอันดับ *n* เริ่มต้นด้วย 1/*n* และไปจนถึง 1/1 แล้วข้ออ้างที่ว่าสำหรับทุก *ε* > 0

$$
\sum_{i=1}^m|F_n(i) - \tfrac{i}{m}| = O\left(n^{\frac{1}{2}+\epsilon}\right)
$$

เป็นสมมูลกับสมมติฐานของรีมันน์[1] ที่นี่

$$
m = \sum_{i=1}^n\varphi(i)
$$

คือจำนวนของพจน์ในลำดับแฟรีของอันดับ *n*

สำหรับตัวอย่างจาก [ทฤษฎีกรุป](https://en.wikipedia.org/wiki/group_theory) ถ้า *g*(*n*) คือ [Landau's function](https://en.wikipedia.org/wiki/Landau%27s_function) ที่กำหนดโดยลำดับสูงสุดของสมาชิกของ [symmetric group](https://en.wikipedia.org/wiki/symmetric_group) S<sub>*n*</sub> ของดีกรี *n* แล้ว Massias, J.-P.; Nicolas, Jean-Louis; Robin, G. (1988). *Évaluation asymptotique de l'ordre maximum d'un élément du groupe symétrique*. *Acta Arithmetica* **50**(3), 221–242. [MR960551](https://mathscinet.ams.org/mathscinet-getitem?mr=MR960551). doi:[10.4064/aa-50-3-221-242](https://doi.org/10.4064/aa-50-3-221-242). [Évaluation asymptotique de l'ordre maximum d'un élément du groupe symétrique](http://matwbn.icm.edu.pl/tresc.php?wyd=6&tom=50&jez=). ได้แสดงให้เห็นว่าสมมติฐานของรีมันเทียบเท่ากับขอบเขต

$$
\log g(n) < \sqrt{\operatorname{Li}^{-1}(n)}
$$

สำหรับทุก *n* ที่ใหญ่พอ

### สมมติฐานลินเดลอฟและการเติบโตของฟังก์ชันซีตา

สมมติฐานของรีมันน์มีผลที่อ่อนกว่าหลายอย่างเช่นกัน; อย่างหนึ่งคือ [สมมติฐานของลินเดลอฟ](https://en.wikipedia.org/wiki/Lindel%C3%B6f_hypothesis) เกี่ยวกับอัตราการเติบโตของฟังก์ชันซีตาบนเส้นวิกฤต ซึ่งระบุว่า สำหรับค่า *ε* > 0 ใดๆ

$$
\zeta\left(\frac{1}{2} + it\right) = O(t^\varepsilon),
$$

เมื่อ *t* → $\infty$.

สมมติฐานของรีมันยังบ่งชี้ขอบเขตที่ค่อนข้างคมชัดสำหรับอัตราการเติบโตของฟังก์ชันซีตาในบริเวณอื่นของแถบวิกฤต ตัวอย่างเช่น มันบ่งชี้ว่า

$$
e^\gamma\le \limsup_{t\rightarrow +\infty}\frac{|\zeta(1+it)|}{\log\log t}\le 2e^\gamma
$$

$$
\frac{6}{\pi^2}e^\gamma\le \limsup_{t\rightarrow +\infty}\frac{1/|\zeta(1+it)|}{\log\log t}\le \frac{12}{\pi^2}e^\gamma
$$

ดังนั้นอัตราการเติบโตของ *ζ*(1 + *it*) และส่วนกลับของมันจะทราบได้จนถึงปัจจัย 2. Titchmarsh, Edward Charles (1986). *The theory of the Riemann zeta-function*. *The Clarendon Press Oxford University Press*. ISBN 978-0-19-853369-6. [MR882550](https://mathscinet.ams.org/mathscinet-getitem?mr=MR882550).

### ข้อความคาดการณ์ช่องว่างจำนวนเฉพาะขนาดใหญ่

ทฤษฎีบทจำนวนเฉพาะ (prime number theorem) บ่งชี้ว่าโดยเฉลี่ยแล้ว ช่องว่างระหว่างจำนวนเฉพาะ *p* กับตัวถัดไปคือ log *p* อย่างไรก็ตาม ช่องว่างระหว่างจำนวนเฉพาะบางช่องอาจใหญ่กว่าค่าเฉลี่ยมาก ครามเมอร์พิสูจน์ว่าโดยสมมติฐานของรีมัน (Riemann hypothesis) ช่องว่างทุกช่องคือ *O*( $\sqrt{*p*}$ log *p*) นี่เป็นกรณีหนึ่งที่ขอบเขตที่ดีที่สุดที่สามารถพิสูจน์ได้โดยใช้สมมติฐานของรีมันนั้นอ่อนกว่าความจริงที่ดูเหมือนจะเป็นมาก: [ข้อความคาดการณ์ของครามเมอร์](https://en.wikipedia.org/wiki/Cram%C3%A9r%27s_conjecture) บ่งชี้ว่าช่องว่างทุกช่องคือ *O*((log *p*)<sup>2</sup>) ซึ่งแม้จะใหญ่กว่าช่องว่างเฉลี่ยแต่ก็เล็กกว่าขอบเขตที่สมมติฐานของรีมันบ่งชี้มาก หลักฐานเชิงตัวเลขสนับสนุนข้อความคาดการณ์ของครามเมอร์ นิโคลี ทอมัส อาร์. (1999). *New maximal prime gaps and first occurrences*. *Mathematics of Computation* **68**(227), 1311–1315. [MR1627813](https://mathscinet.ams.org/mathscinet-getitem?mr=MR1627813). [1999MaCom..68.1311N](https://ui.adsabs.harvard.edu/abs/1999MaCom..68.1311N). doi:[10.1090/S0025-5718-99-01065-0](https://doi.org/10.1090/S0025-5718-99-01065-0). [New maximal prime gaps and first occurrences](http://www.trnicely.net/gaps/gaps.html).

### เกณฑ์เชิงวิเคราะห์ที่เทียบเท่ากับสมมติฐานของรีมันน์

มีข้อความหลายประการที่เทียบเท่ากับสมมติฐานของรีมัน (Riemann hypothesis) ที่ถูกค้นพบ แต่จนถึงปัจจุบันไม่มีข้อใดนำไปสู่ความก้าวหน้าในการพิสูจน์ (หรือการหักล้าง) ได้มากเท่าใด ตัวอย่างที่เป็นลักษณะทั่วไปมีดังนี้ (ข้ออื่น ๆ เกี่ยวข้องกับ [ฟังก์ชันตัวหาร](https://en.wikipedia.org/wiki/Divisor_function#Growth_rate) *σ*(*n*)。)

เกณฑ์รีเซ (Riesz criterion) ซึ่งให้โดย Riesz, M. (1916). *Sur l'hypothèse de Riemann*. *Acta Mathematica* **40**, 185–190. doi:[10.1007/BF02418544](https://doi.org/10.1007/BF02418544) เพื่อระบุว่าขอบเขต

$$
-\sum_{k=1}^\infty \frac{(-x)^k}{(k-1)! \zeta(2k)}= O\left(x^{\frac{1}{4}+\epsilon}\right)
$$

เป็นจริงสำหรับทุก $\varepsilon > 0$ ก็ต่อเมื่อ สมมติฐานของรีมันน์ เป็นจริง ดูเพิ่มเติมที่ [เกณฑ์ของฮาร์ดี–ลิทเทิลวูด](https://en.wikipedia.org/wiki/Riesz_function#Hardy%E2%80%93Littlewood_criterion) 

นิลมัน, เบร์ทิล (1950). *On the One-Dimensional Translation Group and Semi-Group in Certain Function Spaces*. *University of Uppsala*. [MR0036444](https://mathscinet.ams.org/mathscinet-getitem?mr=MR0036444). ได้พิสูจน์ว่าสมมติฐานของรีมันน์เป็นจริงก็ต่อเมื่อพื้นที่ของฟังก์ชันที่มีรูปแบบ

$$
f(x) = \sum_{\nu=1}^nc_\nu\rho \left(\frac{\theta_\nu}{x} \right)
$$

โดยที่ *ρ*(*z*) คือส่วนเศษของ *z*, 0 ≤ *θ*<sub>*ν*</sub> ≤ 1, และ

$$
\sum_{\nu=1}^nc_\nu\theta_\nu=0,
$$

มีความหนาแน่นใน [ปริภูมิฮิลเบิร์ท *L*<sup>2</sup>(0,1)](https://en.wikipedia.org/wiki/Lp_space) ของฟังก์ชันที่อินทิเกรตกำลังสองได้บนช่วงหนึ่งหน่วย Beurling, Arne (1955). *A closure problem related to the Riemann zeta-function*. *Proceedings of the National Academy of Sciences of the United States of America* **41**(5), 312–314. [MR0070655](https://mathscinet.ams.org/mathscinet-getitem?mr=MR0070655). [1955PNAS...41..312B](https://ui.adsabs.harvard.edu/abs/1955PNAS...41..312B). [PMID 16589670](https://pubmed.ncbi.nlm.nih.gov/16589670/). [528084](https://www.ncbi.nlm.nih.gov/pmc/articles/528084/). doi:[10.1073/pnas.41.5.312](https://doi.org/10.1073/pnas.41.5.312). ขยายสิ่งนี้โดยแสดงว่า ฟังก์ชันซีตาไม่มีศูนย์ที่มีส่วนจริงมากกว่า 1/*p* ก็ต่อเมื่อพื้นที่ฟังก์ชันนี้มีความหนาแน่นใน *L<sup>p</sup>*(0,1) เกณฑ์ Nyman-Beurling นี้ได้รับการเสริมกำลังโดย Baez-Duarte[^13] ให้เป็นกรณีโดยที่ $\theta_\nu \in \{1/k\}_{k\geq 1}$

ราฟาแอล ซาเลม (1953). *Sur une proposition équivalente à l'hypothèse de Riemann*. *Les Comptes rendus de l'Académie des sciences* **236**, 1127–1128. [MR0053148](https://mathscinet.ams.org/mathscinet-getitem?mr=MR0053148). แสดงให้เห็นว่าสมมติฐานของรีมันเป็นจริงก็ต่อเมื่อ[สมการเชิงปริพันธ์](https://en.wikipedia.org/wiki/integral_equation)

$$
\int_0^\infty\frac{z^{-\sigma-1}\varphi(z)}{{e^{x/z}}+1}\,dz=0
$$

ไม่มีคำตอบที่มีขอบเขตที่ไม่เป็นศูนย์ $\varphi$ สำหรับ $1/2<\sigma <1$

[เกณฑ์ของไวล์](https://en.wikipedia.org/wiki/Weil%27s_criterion) คือข้อความที่ว่าความเป็นบวกของฟังก์ชันหนึ่งๆ เทียบเท่าสมมติฐานของรีมันน์ ซึ่งเกี่ยวข้องกันคือ [เกณฑ์ของลี](https://en.wikipedia.org/wiki/Li%27s_criterion) ข้อความที่ว่าความเป็นบวกของลำดับจำนวนหนึ่งๆ เทียบเท่าสมมติฐานของรีมันน์

พิสูจน์ว่าสมมติฐานของรีมันเทียบเท่ากับข้อความที่ว่า *ζ*′(*s*), อนุพันธ์ของ *ζ*(*s*), ไม่มีศูนย์ในแถบ

$$
0 < \Re(s) < \frac12.
$$

ว่า *ζ*(*s*) มีศูนย์แบบง่ายเพียงอย่างเดียวบนเส้นวิกฤต ก็เทียบเท่ากับอนุพันธ์ของมันที่ไม่มีศูนย์บนเส้นวิกฤต

ลำดับเฟรี (Farey sequence) ให้สมการสองแบบ เนื่องจาก [Jerome Franel](https://en.wikipedia.org/wiki/Jerome_Franel) และ [เอ็ทมุนท์ ลันเดา](https://en.wikipedia.org/wiki/Edmund_Landau) ในปี 1924

ค่าคงที่เดอ บรอยน์–นิวแมน (de Bruijn–Newman constant) ซึ่งเขียนแทนด้วย Λ และตั้งชื่อตาม นิโคลาส โกเวิร์ต เดอ บรอยน์ (Nicolaas Govert de Bruijn) และ ชาร์ลส์ เอ็ม. นิวแมน (Charles M. Newman) นั้น นิยามไว้ว่า
เป็นจำนวนจริงเพียงจำนวนเดียวที่ [ฟังก์ชัน](https://en.wikipedia.org/wiki/Function_%28mathematics%29)
  $H(\lambda, z):=\int_{0}^{\infty} e^{\lambda u^{2}} \Phi(u) \cos (z u)\, d u$,
คือพารามิเตอร์ด้วยตัวแปรจริง *λ* มีตัวแปรเชิงซ้อน *z* และนิยามโดยใช้ฟังก์ชันที่ลดลงแบบเอกซ์โพเนนเชียลยิ่งยวด
  $\Phi(u) = \sum_{n=1}^{\infty} (2\pi^2n^4e^{9u} - 3 \pi n^2 e^{5u} ) e^{-\pi n^2 e^{4u}}$,
มีศูนย์จริงเพียงอย่างเดียวก็ต่อเมื่อ *λ* ≥ Λ
สมมติฐานของรีมัน (Riemann hypothesis) คือสมการที่เทียบเท่ากับการอ้างว่าศูนย์ทั้งหมดของ *H*(0, *z*) เป็นจำนวนจริง ดังนั้นสมมติฐานของรีมันจึงเทียบเท่ากับข้อความคาดการณ์ที่ว่า Λ ≤ 0 แบรด รอดเจอร์ส (Brad Rodgers) และ [เทเรนซ์ เทา](https://en.wikipedia.org/wiki/Terence_Tao) ค้นพบว่าความเทียบเท่านี้คือ Λ = 0 โดยพิสูจน์ว่าศูนย์คือขอบเขตล่างของค่าคงที่ Rodgers, Brad; Tao, Terence (2020). *The de Bruijn–Newman constant is non-negative*. *Forum of Mathematics* **8**, e6, 62. [MR4089393](https://mathscinet.ams.org/mathscinet-getitem?mr=MR4089393). [arXiv:1801.05914](https://arxiv.org/abs/1801.05914). doi:[10.1017/fmp.2020.6](https://doi.org/10.1017/fmp.2020.6). การพิสูจน์ว่าศูนย์คือขอบเขตบนก็จะพิสูจน์สมมติฐานของรีมันเช่นกัน นิวแมน (Newman) ระบุว่าข้อความคาดการณ์นี้ (ซึ่งปัจจุบันเป็นทฤษฎีบท) "เป็นรูปแบบเชิงปริมาณของคำสอนที่ว่า สมมติฐานของรีมัน หากเป็นจริง ก็เป็นจริงเพียงเล็กน้อยเท่านั้น" Newman, C. M. (1976). *Fourier transforms with only real zeroes*. *Proceedings of the American Mathematical Society* **61**(2), 246–251. doi:[10.1090/S0002-9939-1976-0434982-5](https://doi.org/10.1090/S0002-9939-1976-0434982-5). ณ เดือนเมษายน ค.ศ. 2020 ขอบเขตบนคือ Λ ≤ 0.2 [(Platt & Trudgian 2021)](https://en.wikipedia.org/wiki/Riemann_hypothesis#CITEREFPlattTrudgian2021)

### ผลกระทบของสมมติฐานของรีมันน์แบบทั่วไป

หลายการประยุกต์ใช้ [สมมติฐานของรีมันแบบทั่วไป](https://en.wikipedia.org/wiki/generalized_Riemann_hypothesis) สำหรับ [อนุกรมดีริชเลต](https://en.wikipedia.org/wiki/Dirichlet_L-series) หรือ [ฟังก์ชันซีตาของฟิลด์จำนวน](https://en.wikipedia.org/wiki/Dedekind_zeta_function) แทนที่จะใช้เพียงสมมติฐานของรีมัน คุณสมบัติพื้นฐานหลายประการของ ฟังก์ชันซีตาของรีมัน สามารถสรุปขยายไปสู่อันุกรมดีริชเลตทั้งหมดได้อย่างง่ายดาย ดังนั้นจึงเป็นไปได้ว่าวิธีการหนึ่งที่จะพิสูจน์สมมติฐานของรีมันสำหรับ ฟังก์ชันซีตาของรีมัน จะทำงานได้สำหรับ สมมติฐานของรีมันแบบทั่วไปสำหรับ ฟังก์ชันดีริชเลตเช่นกัน ผลลัพธ์หลายอย่างที่ถูกพิสูจน์ครั้งแรกโดยใช้ สมมติฐานของรีมันแบบทั่วไป ได้รับการพิสูจน์แบบไม่มีเงื่อนไขในภายหลังโดยไม่ต้องใช้มัน แม้ว่าโดยปกติแล้วสิ่งเหล่านี้จะยากกว่ามาก ผลลัพธ์หลายอย่างในรายการต่อไปนี้มาจาก คอนราด, เค. (2010). *Consequences of the Riemann hypothesis*. [Consequences of the Riemann hypothesis](https://mathoverflow.net/q/17232)..
* ในปี 1913, [กรอนวาล](https://en.wikipedia.org/wiki/Thomas_Hakon_Gr%C3%B6nwall) แสดงให้เห็นว่า สมมติฐานของรีมันแบบทั่วไป บ่งชี้ว่า [รายการฟิลด์จำนวนเชิงซ้อนจินตภาพที่มีจำนวนคลาสเท่ากับ 1](https://en.wikipedia.org/wiki/class_number_problem) ของเกาส์ นั้นสมบูรณ์ แม้ว่าเบกเกอร์, สตาร์ก และไฮเกนเนอร์ จะให้การพิสูจน์แบบไม่มีเงื่อนไขของสิ่งนี้ในภายหลังโดยไม่ต้องใช้ สมมติฐานของรีมันแบบทั่วไป
* ในปี 1917, ฮาร์ดีและลิตเติลวูดแสดงให้เห็นว่า สมมติฐานของรีมันแบบทั่วไป บ่งชี้ถึง ข้อความคาดการณ์ ของเชบิเชฟที่ว่า

$$
\lim_{x\to 1^-} \sum_{p>2}(-1)^{(p+1)/2} x^p=+\infty,
$$

ซึ่งระบุว่าจำนวนเฉพาะที่เท่ากับ 3 mod 4 นั้นพบบ่อยกว่าจำนวนเฉพาะที่เท่ากับ 1 mod 4 ในบางความหมาย (สำหรับผลลัพธ์ที่เกี่ยวข้อง ดูที่ *[Prime number race](https://en.wikipedia.org/wiki/Prime_number_theorem#Prime_number_race)*.)
* ในปี 1923, Hardy และ Littlewood แสดงให้เห็นว่าสมมติฐานของรีมันแบบทั่วไป (generalized Riemann hypothesis) ล่วงเลยถึงรูปแบบอ่อนของ [ข้อความคาดการณ์ของก็อลท์บัค](https://en.wikipedia.org/wiki/Goldbach_conjecture) สำหรับจำนวนคี่: ว่าจำนวนคี่ทุกจำนวนที่มากพอจะเป็นผลบวกของจำนวนเฉพาะสามจำนวน แม้ว่าจะมีการพิสูจน์แบบไม่มีเงื่อนไขโดย Vinogradov ในปี 1937 ในปี 1997 [Deshouillers](https://en.wikipedia.org/wiki/Jean-Marc_Deshouillers), Effinger, [te Riele](https://en.wikipedia.org/wiki/Herman_te_Riele), และ Zinoviev แสดงให้เห็นว่าสมมติฐานของรีมันแบบทั่วไป (generalized Riemann hypothesis) ล่วงเลยถึงว่าจำนวนคี่ทุกจำนวนที่มากกว่า 5 เป็นผลบวกของจำนวนเฉพาะสามจำนวน ในปี 2013 [Harald Helfgott](https://en.wikipedia.org/wiki/Harald_Helfgott) พิสูจน์ข้อความคาดการณ์ของก็อลท์บัคแบบสามจำนวน (ternary Goldbach conjecture) โดยไม่ต้องพึ่งพา GRH ภายใต้การคำนวณอย่างกว้างขวางที่เสร็จสิ้นลงด้วยความช่วยเหลือของ David J. Platt
* ในปี 1934, Chowla แสดงให้เห็นว่าสมมติฐานของรีมันแบบทั่วไป (generalized Riemann hypothesis) ล่วงเลยถึงว่าจำนวนเฉพาะตัวแรกในลำดับเลขคณิต *a* mod *m* มีค่ามากที่สุดเท่ากับ *Km*<sup>2</sup>log(*m*)<sup>2</sup> สำหรับค่าคงที่ *K* ที่กำหนดไว้
* ในปี 1967, Hooley แสดงให้เห็นว่าสมมติฐานของรีมันแบบทั่วไป (generalized Riemann hypothesis) ล่วงเลยถึง [Artin's conjecture on primitive roots](https://en.wikipedia.org/wiki/Artin%27s_conjecture_on_primitive_roots).
* ในปี ค.ศ. 1973, Weinberger แสดงให้เห็นว่าสมมติฐานของรีมันแบบทั่วไป (generalized Riemann hypothesis) นั้นนัยสำคัญว่ารายการของจำนวน idoneal number ของออยเลอร์ [idoneal number](https://en.wikipedia.org/wiki/idoneal_number) นั้นสมบูรณ์
แสดงให้เห็นว่าสมมติฐานของรีมันแบบทั่วไปสำหรับฟังก์ชันซีตาของทุกฟิลด์จำนวนเชิงพีชคณิต (algebraic number fields) นั้นนัยสำคัญว่าฟิลด์จำนวนใดๆ ที่มีจำนวนชั้น (class number) เท่ากับ 1 จะเป็นฟิลด์จำนวนแบบยุคลิด (Euclidean) หรือเป็นฟิลด์จำนวนกำลังสองจินตภาพ (imaginary quadratic number field) ของ discriminant −19, −43, −67, หรือ −163
* ในปี ค.ศ. 1976, G. Miller แสดงให้เห็นว่าสมมติฐานของรีมันแบบทั่วไป (generalized Riemann hypothesis) นั้นนัยสำคัญว่าสามารถ [test if a number is prime](https://en.wikipedia.org/wiki/primality_test) ได้ในเวลาพหุนาม (polynomial time) ผ่าน [Miller test](https://en.wikipedia.org/wiki/Miller%E2%80%93Rabin_primality_test) ในปี ค.ศ. 2002, Manindra Agrawal, Neeraj Kayal และ Nitin Saxena ได้พิสูจน์ผลลัพธ์นี้โดยไม่มีเงื่อนไข (unconditionally) โดยใช้ [AKS primality test](https://en.wikipedia.org/wiki/AKS_primality_test)
อภิปรายว่าสมมติฐานของรีมันแบบทั่วไป (generalized Riemann hypothesis) สามารถนำมาใช้เพื่อให้ความประมาณที่คมชัดขึ้น (sharper estimates) สำหรับ discriminant และ class numbers ของฟิลด์จำนวน
* โอนะ, เคน; ซาวนดาราราจาน, เค. (ค.ศ. 1997). *รูปแบบกำลังสองสามตัวแปรของรามานุจัน*. *Inventiones Mathematicae* **130**(3), 415–454. [1997InMat.130..415O](https://ui.adsabs.harvard.edu/abs/1997InMat.130..415O). แสดงให้เห็นว่าสมมติฐานของรีมันแบบทั่วไป (generalized Riemann hypothesis) นำไปสู่ข้อความคาดการณ์ที่ว่า [รูปแบบกำลังสองอินทิกรัลของรามานุจัน](https://en.wikipedia.org/wiki/Ramanujan%27s_ternary_quadratic_form) *x*<sup>2</sup> + *y*<sup>2</sup> + 10*z*<sup>2</sup> สามารถแทนจำนวนเต็มทั้งหมดที่มันแทนในระดับท้องถิ่น (locally) ได้ โดยมีข้อยกเว้นเพียง 18 กรณีเท่านั้น
* ในปี ค.ศ. 2021, อเล็กซานเดอร์ (Alex) ดันน์ และ [แมกซิม รัดซิวิล](https://en.wikipedia.org/wiki/Maksym_Radziwill) พิสูจน์ [ข้อความคาดการณ์ของแพตเตอร์สัน](https://en.wikipedia.org/wiki/Patterson%27s_conjecture) เกี่ยวกับผลรวมเกาส์แบบลูกบาศก์ [Gauss sums](https://en.wikipedia.org/wiki/Gauss_sums) ภายใต้สมมติฐานของ GRH.[^14] [^15]

### หลักการกีดกันกลาง

ผลสืบเนื่องบางประการของสมมติฐานของรีมัน (RH) ก็เป็นผลสืบเนื่องของการปฏิเสธของมันเช่นกัน และจึงเป็นทฤษฎีบท ในการอภิปรายของ [Hecke, Deuring, Mordell, Heilbronn theorem](./riemann_hypothesis.md#ข้อความคาดการณ์ของเกาส์) Ireland, Kenneth; Rosen, Michael (1990). *A Classical Introduction to Modern Number Theory (Second edition)*. *Springer*. ISBN 0-387-97329-X, 359. กล่าวไว้ว่า

> วิธีการพิสูจน์ที่นี่นั้นมหัศจรรย์อย่างยิ่ง หากสมมติฐานของรีมันแบบทั่วไปเป็นจริง แล้วทฤษฎีบทนี้ก็เป็นจริง หากสมมติฐานของรีมันแบบทั่วไปเป็นเท็จ แล้วทฤษฎีบทนี้ก็เป็นจริง ดังนั้น ทฤษฎีบทนี้จึงเป็นจริง!!

ควรระมัดระวังในการทำความเข้าใจว่าหมายถึงอะไรเมื่อกล่าวว่าสมมติฐานของรีมันแบบทั่วไปเป็นเท็จ: ควรระบุให้ชัดเจนว่าคลาสใดของอนุกรมดีริชเล็ตที่มีตัวอย่างค้าน

#### ทฤษฎีบทของลิตเติลวูด

เรื่องนี้มีผลต่อเครื่องหมายของข้อผิดพลาดใน [ทฤษฎีบทจำนวนเฉพาะ](https://en.wikipedia.org/wiki/prime_number_theorem)
มีการคำนวณพบว่า $\pi$(*x*) \< li(*x*) สำหรับทุก *x* ≤ 10<sup>25</sup> (ดู [ตาราง](https://en.wikipedia.org/wiki/Prime_number_theorem#Table_of_%CF%80%28x%29%2C_x_/_log_x%2C_and_li%28x%29) นี้) และไม่มีค่าของ *x* ใดๆ ที่ทราบค่าซึ่งทำให้ $\pi$(*x*) > li(*x*)

ในปี 1914 ลิตเติ้ลวูดพิสูจน์ว่ามีความเป็นไปได้ที่จะมีค่าของ *x* ที่ใหญ่เท่าใดก็ได้สำหรับซึ่ง

$$
\pi(x)>\operatorname{li}(x) +\frac13\frac{\sqrt x}{\log x}\log\log\log x,
$$

และยังว่ามีค่าของ *x* ที่ใหญ่เท่าใดก็ได้ซึ่ง

$$
\pi(x)<\operatorname{li}(x) -\frac13\frac{\sqrt x}{\log x}\log\log\log x.
$$

ดังนั้นผลต่าง $\pi$(*x*) − li(*x*) จึงเปลี่ยนเครื่องหมายเป็นจำนวนครั้งอนันต์ [จำนวนสกีว](https://en.wikipedia.org/wiki/Skewes%27_number) เป็นค่าประมาณของค่าของ *x* ที่สอดคล้องกับการเปลี่ยนเครื่องหมายครั้งแรก

การพิสูจน์ของ Littlewood แบ่งออกเป็นสองกรณี: กรณีที่สมมติว่า RH เป็นเท็จ (ประมาณครึ่งหน้าของ Ingham, A.E. (1932). *The Distribution of Prime Numbers*. *Cambridge University Press* **30**, Chapt. V.) และกรณีที่สมมติว่า RH เป็นจริง (ประมาณสิบสองหน้า) Stanisław Knapowski ได้ทำต่อด้วยบทความเกี่ยวกับจำนวนครั้งที่ $\Delta(n)$ เปลี่ยนเครื่องหมายในช่วง $\Delta(n)$.[^16]

#### ข้อความคาดการณ์ของเกาส์

นี่คือ [ข้อความคาดการณ์](https://en.wikipedia.org/wiki/Class_number_problem) (กล่าวเป็นครั้งแรกในบทความ 303 ของ *[Disquisitiones Arithmeticae](https://en.wikipedia.org/wiki/Disquisitiones_Arithmeticae)*) ว่ามีสนามกำลังสองจินตภาพจำนวนจำกัดเท่านั้นที่มีเลขชั้นที่กำหนดให้ วิธีหนึ่งในการพิสูจน์สิ่งนี้คือการแสดงให้เห็นว่าเมื่อ discriminant $D → −∞$ เลขชั้น $h(D) → ∞$

ลำดับของทฤษฎีบทที่เกี่ยวข้องกับสมมติฐานของรีมันน์ต่อไปนี้ได้รับการบรรยายไว้ใน Ireland, Kenneth; Rosen, Michael (1990). *A Classical Introduction to Modern Number Theory (Second edition)*. *Springer*. ISBN 0-387-97329-X, 358–361.:
**ทฤษฎีบท (Hecke; 1918).** ให้ $D < 0$ เป็น discriminant ของ [สนามจำนวน](https://en.wikipedia.org/wiki/number_field) [กำลังสองจินตภาพ](https://en.wikipedia.org/wiki/quadratic_irrational_number) *K* สมมติสมมติฐานของรีมันน์แบบทั่วไปสำหรับ [*ฟังก์ชัน L*](https://en.wikipedia.org/wiki/L-function) ของตัวละคร Dirichlet ทั้งหมดที่เป็นกำลังสองจินตภาพ จะมีค่าคงที่สัมบูรณ์ *C* ซึ่ง

$$
h(D) > C\frac{\sqrt{|D|}}{\log |D|}.
$$

**ทฤษฎีบท (Deuring; 1933).** หากสมมติฐาน RH เป็นเท็จ แล้ว $h(D) > 1$ ถ้า $|D|$ มีค่ามากเพียงพอ
**ทฤษฎีบท (Mordell; 1934).** หากสมมติฐาน RH เป็นเท็จ แล้ว $h(D) → ∞$ เมื่อ $D → −∞$.
**ทฤษฎีบท (Heilbronn; 1934).** หากสมมติฐาน RH แบบทั่วไปเป็นเท็จสำหรับฟังก์ชัน *L* ของอักขระ Dirichlet แบบกำลังสองจินตภาพบางตัว แล้ว $h(D) → ∞$ เมื่อ $D → −∞$.

(ในผลงานของ Hecke และ Heilbronn มี [*L*-functions](https://en.wikipedia.org/wiki/L-function) ที่ปรากฏเพียงอย่างเดียวคือ那些ที่เชื่อมต่อกับอักขระกำลังสองจินตภาพ และมันมีไว้เพื่อ [*GRH is true*] หรือ [*GRH is false*] เท่านั้น; ความล้มเหลวของ GRH สำหรับ *L*-function ของอักขระ Dirichlet กำลังสาม จะหมายถึง GRH เป็นเท็จอย่างเคร่งครัด แต่ไม่ใช่รูปแบบของความล้มเหลวของ GRH ที่ Heilbronn มีในใจ ดังนั้นสมมติฐานของเขากว่าเพียงแค่ *GRH is false*.)

ในปี 1935 [Carl Siegel](https://en.wikipedia.org/wiki/Carl_Siegel) ได้เสริมผลลัพธ์โดยไม่ใช้ RH หรือ GRH ในทางใด ๆ.[^17] [^18]

#### การเติบโตของฟังก์ชันออยเลอร์

ในปี 1983 [J. L. Nicolas](https://en.wikipedia.org/wiki/Jean-Louis_Nicolas) ได้พิสูจน์ว่า

$$
\varphi(n) < e^{-\gamma}\frac  {n} {\log \log n}
$$

สำหรับจำนวน *n* ที่มากอนันต์ โดยที่ *φ*(*n*) คือ [ฟังก์ชันออยเลอร์](https://en.wikipedia.org/wiki/Euler%27s_totient_function) และ *γ* คือ [ค่าคงตัวอ็อยเลอร์–มัสเกโรนี](https://en.wikipedia.org/wiki/Euler%27s_constant) ริเบนบอยม์ระบุว่า: "วิธีการพิสูจน์น่าสนใจ เนื่องจากอสมการถูกแสดงออกครั้งแรกภายใต้สมมติฐานที่ว่าสมมติฐานของรีมันเป็นจริง และครั้งที่สองภายใต้สมมติฐานตรงกันข้าม" ริเบนบอยม์, ปาอูล (1996). *บันทึกสถิติจำนวนเฉพาะฉบับใหม่*. *สปริงเกอร์*. ISBN 0-387-94457-5, 320.

## การสรุปผลและการเปรียบเทียบ

### ทฤษฎีบทดีริชเลตและฟิลด์จำนวนอื่นๆ

สมมติฐานของรีมันสามารถสรุปผลได้โดยแทนที่ ฟังก์ชันซีตาของรีมัน ด้วย ฟังก์ชัน L โลก [L-function](https://en.wikipedia.org/wiki/L-function) ซึ่งมีความคล้ายคลึงกันอย่างเป็นทางการแต่มีความทั่วไปมากกว่า ในบริบทที่กว้างขึ้นนี้ คาดว่าศูนย์ที่ไม่สำคัญ (non-trivial zeros) ของ ฟังก์ชัน L โลก จะมีส่วนจริงเท่ากับ 1/2 เป็นข้อความคาดการณ์เหล่านี้มากกว่าสมมติฐานของรีมันแบบดั้งเดิมที่เกี่ยวกับ ฟังก์ชันซีตาของรีมัน เพียงฟังก์ชันเดียว ซึ่งอธิบายถึงความสำคัญที่แท้จริงของสมมติฐานของรีมัน ใน คณิตศาสตร์

สมมติฐานของรีมันแบบทั่วไป (generalized Riemann hypothesis)  ที่พบบ่อยที่สุดนั้นขยายสมมติฐานของรีมันไปยังฟังก์ชัน L ของดิริชเลตทั้งหมด  โดยเฉพาะอย่างยิ่งมันบ่งชี้ข้อความคาดการณ์ว่าซีเกล์ซีโร่  (ศูนย์ของฟังก์ชัน L ระหว่าง 1/2 และ 1) นั้นไม่มีอยู่จริง

สมมติฐานรีมันน์แบบขยาย (extended Riemann hypothesis) คือสมมติฐานที่ขยายสมมติฐานของรีมัน (Riemann hypothesis) ไปยังฟังก์ชันซีตาของเดเดคินด์ (Dedekind zeta function) ของสนามจำนวนเชิงพีชคณิต (algebraic number field) ทั้งหมด เนื่องจากฟังก์ชันซีตาของเดเดคินด์ (Dedekind zeta function) สำหรับส่วนขยายแบบอาบีเลียนของจำนวนตรรกยะสามารถแสดงออกมาเป็นผลคูณของฟังก์ชัน L ของดิริชเลต์ (Dirichlet L-functions) และขั้วที่เป็นไปได้เพียงอย่างเดียวคือที่ 1 สำหรับฟังก์ชันซีตาของรีมันน์ (Riemann zeta function) (ดังนั้นจึงไม่มีขั้วที่จะหักล้างศูนย์ที่ไม่สำคัญ) ดังนั้นสมมติฐานของรีมันน์ (Riemann hypothesis) ในรูปแบบนี้จึงนำไปสู่สมมติฐานของรีมันน์แบบทั่วไป (generalized Riemann hypothesis)

สมมติฐานของรีมัน (Riemann hypothesis) สามารถขยายไปยังฟังก์ชัน *L* ของ [Hecke character](https://en.wikipedia.org/wiki/Hecke_character) ของฟิลด์จำนวนได้ เนื่องจากฟังก์ชัน L ของ Dirichlet เป็นฟังก์ชัน L ของ Hecke สำหรับอักขระจำกัด ดังนั้นสมมติฐานนี้จึงนัยโดยตรงไปยังสมมติฐานของรีมันแบบทั่วไป ฟังก์ชันซีตาของ Dedekind สามารถแสดงออกมาเป็นผลคูณของฟังก์ชัน L ของ Hecke และขั้วที่เป็นไปได้เพียงอย่างเดียวของฟังก์ชัน L ของ Hecke อยู่ที่ 1 ดังนั้นรุ่นหนึ่งของสมมติฐานของรímานนี้จึงนัยไปยังรุ่นสำหรับฟังก์ชันซีตาของ Dedekind ด้วย

มีแนวทางสองแบบสำหรับการขยายสมมติฐานของรีมัน (Riemann hypothesis) ที่ดูเหมือนจะเป็นแนวทางที่กว้างที่สุด แนวทางแรกคือ [สมมติฐานของรีมันแบบใหญ่](https://en.wikipedia.org/wiki/grand_Riemann_hypothesis) ซึ่งขยายมันไปยัง [Automorphic L-function](https://en.wikipedia.org/wiki/Automorphic_L-function) ทั้งหมด เช่น [Mellin transform](https://en.wikipedia.org/wiki/Mellin_transform) ของ [Hecke eigenform](https://en.wikipedia.org/wiki/Hecke_eigenform) แนวทางที่สองคือสมมติฐานของรีมันสำหรับ [Selberg class](https://en.wikipedia.org/wiki/Selberg_class) ซึ่งขยายมันสำหรับฟังก์ชันที่สอดคล้องกับคุณสมบัติบางอย่าง (อย่างน้อยก็คาดเดาว่าสอดคล้องกับฟังก์ชันส่วนใหญ่ที่เรียกว่า *zeta functions* หรือ *L-functions*) มากกว่าฟังก์ชันที่กำหนดโดยสูตรโดยตรง แม้ว่าจะคาดกันว่า Selberg class ควรจะเท่ากับคลาสของ automorphic L-functions และดังนั้นแนวทางนี้ควรจะเทียบเท่ากัน แต่ปัญหานี้เองก็เป็นปัญหาที่ยังไม่ได้รับการแก้ไขและเป็นส่วนหนึ่งของ [Langlands program](https://en.wikipedia.org/wiki/Langlands_program) 

### ฟังก์ชันฟิลด์และฟังก์ชันซีตาของพันธุ์เหนือฟิลด์จำกัด

เอมีล อาร์ติน (Emil Artin) (1924). *Quadratische Körper im Gebiete der höheren Kongruenzen. II. Analytischer Teil*. *Mathematische Zeitschrift* **19**(1), 207–246. doi:[10.1007/BF01181075](https://doi.org/10.1007/BF01181075). ได้แนะนำ ฟังก์ชันซีตา ของ (quadratic) [function fields](https://en.wikipedia.org/wiki/Function_field_of_an_algebraic_variety) และเสนอ ข้อความคาดการณ์ หนึ่งฉบับที่เป็นแบบอย่างของ สมมติฐานของรีมัน สำหรับพวกมัน ซึ่งได้รับการพิสูจน์โดย ฮาสเซ ในกรณีที่มี genus เท่ากับ 1 และโดย เวย์, แอนเดร (André Weil) (1948). *Sur les courbes algébriques et les variétés qui s'en déduivent*. *Hermann et Cie., Paris*. [MR0027151](https://mathscinet.ams.org/mathscinet-getitem?mr=MR0027151). ในกรณีทั่วไป ตัวอย่างเช่น ข้อเท็จจริงที่ว่า ผลรวมเกาส์ (Gauss sum) ของอักขระกำลังสอง (quadratic character) ของ [finite field](https://en.wikipedia.org/wiki/finite_field) ที่มีขนาด *q* (โดยที่ *q* เป็นจำนวนคี่) มีค่าสัมบูรณ์เท่ากับ $\sqrt{q}$ นั้นเป็นกรณีหนึ่งของ สมมติฐานของรีมัน ในบริบทของ function field ซึ่งนำไปสู่ให้ เวย์, แอนเดร (André Weil) (1949). *Numbers of solutions of equations in finite fields*. *Bulletin of the American Mathematical Society* **55**(5), 497–508. [MR0029393](https://mathscinet.ams.org/mathscinet-getitem?mr=MR0029393). doi:[10.1090/S0002-9904-1949-09219-4](https://doi.org/10.1090/S0002-9904-1949-09219-4). เสนอ ข้อความคาดการณ์ ที่คล้ายคลึงกันสำหรับ [algebraic varieties](https://en.wikipedia.org/wiki/algebraic_variety) ทั้งหมด; ผลลัพธ์ที่ได้คือ [Weil conjectures](https://en.wikipedia.org/wiki/Weil_conjectures) ซึ่งได้รับการพิสูจน์โดย [Pierre Deligne](https://en.wikipedia.org/wiki/Pierre_Deligne).[^19]

### ฟังก์ชันซีตาเลขคณิตของสคีมาเลขคณิตและตัวประกอบ L ของมัน

ฟังก์ชันซีตาเลขคณิต (Arithmetic zeta function) [1](https://en.wikipedia.org/wiki/Arithmetic_zeta_function) เป็นการนิยามทั่วไปของฟังก์ชันซีตาของรีมันและฟังก์ชันซีตาของเดเดคินด์ รวมถึงฟังก์ชันซีตาของพันธุ์เหนือฟิลด์จำกัด ไปจนถึงทุกโครงสร้างเลขคณิตหรือโครงสร้างแบบจำกัดเหนือจำนวนเต็ม ฟังก์ชันซีตาเลขคณิตของโครงสร้างเลขคณิตแบบปกติที่เชื่อมต่อกันและมีมิติเท่ากัน (equidimensional) [2](https://en.wikipedia.org/wiki/equidimensionality) ซึ่งมีมิติของครอเนกเกอร์เท่ากับ *n* สามารถแยกตัวประกอบเป็นผลคูณของ L-แฟกเตอร์ที่นิยามอย่างเหมาะสมและแฟกเตอร์เสริม [3]([^20]) หากสมมติสมการเชิงฟังก์ชันและการต่อเนื่องแบบมีเมอโรมอร์ฟิก สมมติฐานของรีมันแบบทั่วไปสำหรับ L-แฟกเตอร์ระบุว่าศูนย์ของมันภายในแถบวิกฤต $\Re(s)\in (0,n)$ จะอยู่บนเส้นกลาง สอดคล้องกัน สมมติฐานของรีมันแบบทั่วไปสำหรับฟังก์ชันซีตาเลขคณิตของโครงสร้างเลขคณิตแบบปกติที่เชื่อมต่อกันและมีมิติเท่ากันระบุว่าศูนย์ของมันภายในแถบวิกฤตจะอยู่บนเส้นแนวตั้ง $\Re(s)=1/2,3/2,\dots,n-1/2$ และขั้วของมันภายในแถบวิกฤตจะอยู่บนเส้นแนวตั้ง $\Re(s)=1, 2, \dots,n-1$ สิ่งนี้เป็นที่ทราบกันสำหรับโครงสร้างในลักษณะเฉพาะที่เป็นบวกและสืบเนื่องจากปีแยร์ เดอลีน [4]([^21]) แต่ยังเหลือความไม่แน่นอนอย่างสมบูรณ์ในลักษณะเฉพาะเป็นศูนย์

### ฟังก์ชันซีตาของเซลเบิร์ก

Atle Selberg (1956). *การวิเคราะห์ฮาร์มอนิกและกลุ่มไม่ต่อเนื่องในปริภูมิรีมันเนียนแบบสมมาตรอ่อนที่มีประยุกต์ใช้กับอนุกรมดีริชเล็ต*. *J. Indian Math. Soc.* **20**, 47–87. [MR0088511](https://mathscinet.ams.org/mathscinet-getitem?mr=MR0088511). ได้แนะนำ [ฟังก์ชันซีตาของรีมัน](https://en.wikipedia.org/wiki/Selberg_zeta_function) ของพื้นผิวรีมันเนียน สิ่งเหล่านี้คล้ายกับ ฟังก์ชันซีตา ของรีมันน์: มี สมการเชิงฟังก์ชัน และ มี ผลคูณอนันต์ ที่คล้ายกับผลคูณของออยเลอร์ แต่เป็นการคูณเหนือจีโอเดสิกปิดแทนที่จะเป็นจำนวนเฉพาะ สูตรติดตามของเซลเบิร์ก(https://en.wikipedia.org/wiki/Selberg_trace_formula) คือสิ่งที่เปรียบเทียบกับฟังก์ชันเหล่านี้ของ สูตรชัดเจน(https://en.wikipedia.org/wiki/explicit_formula_%28L-function%29) ใน ทฤษฎีจำนวน เซลเบิร์กพิสูจน์ว่า ฟังก์ชันซีตาของเซลเบิร์ก สอดคล้องกับ สมมติฐานของรีมัน โดยส่วนจินตภาพของศูนย์ของฟังก์ชันเหล่านี้มีความสัมพันธ์กับ ค่าลักษณะเฉพาะ(https://en.wikipedia.org/wiki/eigenvalue) ของตัวดำเนินการลาปลาเชียนของพื้นผิวรีมันเนียน

### ฟังก์ชันซีตาของอิฮารา

ฟังก์ชันซีตาของอิฮาระ (Ihara zeta function) ของกราฟจำกัด เป็นแบบจำลองของฟังก์ชันซีตาของเซลเบิร์ก (Selberg zeta function) ซึ่งถูกนำเสนอครั้งแรกโดย ยะสุตะกะ อิฮาระ (Yasutaka Ihara) ในบริบทของกลุ่มเส้นตรงพิเศษ p-adic ขนาดสองคูณสองที่เป็นกลุ่มย่อยไม่ต่อเนื่อง ฟังก์ชันซีตาของอิฮาระของกราฟจำกัดแบบปกติ (regular finite graph) เป็นกราฟรามานุจัน (Ramanujan graph) ซึ่งเป็นแบบจำลองทางคณิตศาสตร์ของเครือข่ายการสื่อสารที่มีประสิทธิภาพ ก็ต่อเมื่อฟังก์ชันซีตาของอิฮาระของมันสอดคล้องกับสมมติฐานของรีมัน (Riemann hypothesis) แบบจำลองดังกล่าวได้ถูกชี้ให้เห็นโดย ที. ซุนาดะ (T. Sunada)

### ข้อความคาดการณ์ของคู่ของมอนทอกเกอร์

ฮิวจ์ แอล. มอนต์gomery (Hugh L. Montgomery) (1973). ทฤษฎีจำนวนเชิงวิเคราะห์ (Analytic number theory). อเมริกันแมทีเมติกัลโซไซตี (American Mathematical Society) **XXIV**, 181–193. [MR0337821](https://mathscinet.ams.org/mathscinet-getitem?mr=MR0337821). เสนอ [ข้อความคาดการณ์คู่](pair correlation conjecture) ว่า ฟังก์ชันสหสัมพันธ์ของศูนย์ของฟังก์ชันซีตา (zeta function) (ที่ปรับมาตรฐานให้เหมาะสม) ควรจะมีค่าเท่ากับฟังก์ชันสหสัมพันธ์ของค่าไอเกนของเมทริกซ์แอร์มิต (random hermitian matrix) ออดลยดโก, เอ. เอ็ม. (Odlyzko, A. M.) (1987). *On the distribution of spacings between zeros of the zeta function*. *Mathematics of Computation* **48**(177), 273–308. [MR866115](https://mathscinet.ams.org/mathscinet-getitem?mr=MR866115). [JSTOR 2007890](https://www.jstor.org/stable/2007890). doi:[10.2307/2007890](https://doi.org/10.2307/2007890). แสดงว่าข้อนี้นั้นได้รับการสนับสนุนจากการคำนวณเชิงตัวเลขขนาดใหญ่ของฟังก์ชันสหสัมพันธ์เหล่านี้

มอนต์gomery แสดงให้เห็นว่า (โดยสมมติสมมติฐานของรีมัน) อย่างน้อย 2/3 ของศูนย์ทั้งหมดเป็นแบบง่าย และข้อความคาดการณ์ที่เกี่ยวข้องคือ ศูนย์ทั้งหมดของฟังก์ชันซีตาเป็นแบบง่าย (หรือโดยทั่วไปแล้วไม่มีสมการเชิงเส้นจำนวนเต็มที่ไม่สำคัญระหว่างส่วนจินตภาพของพวกมัน) [Dedekind zeta function](https://en.wikipedia.org/wiki/Dedekind_zeta_function) ของฟิลด์จำนวนเชิงพีชคณิต ซึ่งเป็นการขยายฟังก์ชันซีตาของรีมัน มักจะมีศูนย์เชิงซ้อนหลายตัว Radziejewski, Maciej (2007). *Independence of Hecke zeta functions of finite order over normal fields*. *Transactions of the American Mathematical Society* **359**(5), 2383–2394. [MR2276625](https://mathscinet.ams.org/mathscinet-getitem?mr=MR2276625). doi:[10.1090/S0002-9947-06-04078-5](https://doi.org/10.1090/S0002-9947-06-04078-5). สาเหตุเช่นนี้คือ ฟังก์ชันซีตาของเดดเคินด์แยกตัวประกอบเป็นผลคูณของกำลังของ [Artin L-function](https://en.wikipedia.org/wiki/Artin_L-function) ดังนั้นศูนย์ของฟังก์ชัน Artin L-function บางครั้งจึงนำไปสู่ศูนย์หลายตัวของฟังก์ชันซีตาของเดดเคินด์ ตัวอย่างอื่น ๆ ของฟังก์ชันซีตาที่มีศูนย์หลายตัวคือ ฟังก์ชัน L ของ [เส้นโค้งเชิงวงรี](https://en.wikipedia.org/wiki/elliptic_curve) บางเส้น: สิ่งเหล่านี้สามารถมีศูนย์หลายตัวที่จุดจริงของเส้นวิกฤตของมัน; [Birch-Swinnerton-Dyer conjecture](https://en.wikipedia.org/wiki/Birch-Swinnerton-Dyer_conjecture) ทำนายว่า ความหลายของศูนย์นี้คืออันดับของ elliptic curve

### ฟังก์ชันซีตาอื่น ๆ

มีฟังก์ชันซีตาจำนวนมาก ที่มีสมมติฐานของรีมันในรูปแบบคล้ายกัน บางส่วนได้รับการพิสูจน์แล้ว ฟังก์ชันซีตาของฟิลด์ฟังก์ชัน มีสมมติฐานของรีมัน ซึ่งได้รับการพิสูจน์โดย Sheats, Jeffrey T. (1998). *The Riemann hypothesis for the Goss zeta function for F<sub>q</sub>[T]*. *Journal of Number Theory* **71**(1), 121–157. [MR1630979](https://mathscinet.ams.org/mathscinet-getitem?mr=MR1630979). [arXiv:math/9801158](https://arxiv.org/abs/math/9801158). doi:[10.1006/jnth.1998.2232](https://doi.org/10.1006/jnth.1998.2232).. [ข้อความคาดการณ์หลัก](https://en.wikipedia.org/wiki/Main_conjecture_of_Iwasawa_theory) ของ [ทฤษฎีไอวาซาว่า](https://en.wikipedia.org/wiki/Iwasawa_theory) ซึ่งได้รับการพิสูจน์โดย [Barry Mazur](https://en.wikipedia.org/wiki/Barry_Mazur) และ [แอนดรูว์ ไวลส์](https://en.wikipedia.org/wiki/Andrew_Wiles) สำหรับ [ฟิลด์ไซโคลโทมิก](https://en.wikipedia.org/wiki/cyclotomic_field) และ Wiles สำหรับ [ฟิลด์จริงอย่างสมบูรณ์](https://en.wikipedia.org/wiki/totally_real_number_field) ระบุศูนย์ของฟังก์ชัน *p*-adic *L*-function ให้ตรงกับค่าลักษณะเฉพาะของตัวดำเนินการ ดังนั้นจึงสามารถมองได้ว่าเป็นรูปแบบคล้ายกันของ [ข้อความคาดการณ์ฮิลเบิร์ต–โพไลอา](https://en.wikipedia.org/wiki/Hilbert%E2%80%93P%C3%B3lya_conjecture) สำหรับ [*p*-adic *L*-functions](https://en.wikipedia.org/wiki/p-adic_L-function) Wiles, Andrew (2000). *Mathematics: frontiers and perspectives*. *American Mathematical Society*, 329–342. ISBN 978-0-8218-2697-3. [MR1754786](https://mathscinet.ams.org/mathscinet-getitem?mr=MR1754786).

## หลักฐานการพยายามพิสูจน์

นักคณิตศาสตร์หลายท่านได้กล่าวถึงสมมติฐานของรีมัน แต่ไม่มีข้อใดในข้อลองของพวกเขาได้รับการยอมรับว่าเป็นการพิสูจน์ [Watkins (2021)](https://en.wikipedia.org/wiki/Riemann_hypothesis#CITEREFWatkins2021) ได้ระบุคำตอบที่ผิดบางประการไว้

### ทฤษฎีตัวดำเนินการ

ฮิลเบิร์ตและโพlya แนะนำว่าวิธีหนึ่งในการพิสูจน์สมมติฐานของรีมัน (riemann hypothesis) คือการหา [ตัวดำเนินการแบบ self-adjoint](https://en.wikipedia.org/wiki/self-adjoint_operator) ซึ่งจากสิ่งนี้จะทำให้สามารถสรุปเกี่ยวกับส่วนจริงของศูนย์ของ *ζ*(*s*) ได้เมื่อใช้เกณฑ์เกี่ยวกับค่า [eigenvalue](https://en.wikipedia.org/wiki/eigenvalue) ที่เป็นจำนวนจริง (real) บางการสนับสนุนสำหรับแนวคิดนี้มาจากฟังก์ชันซีตา (zeta) ที่คล้ายคลึงกันหลายแบบ Whose ศูนย์สอดคล้องกับ eigenvalue ของตัวดำเนินการบางตัว: ศูนย์ของฟังก์ชันซีตาของ variety เหนือฟิลด์จำกัดสอดคล้องกับ eigenvalue ของ [Frobenius element](https://en.wikipedia.org/wiki/Frobenius_element) บนกลุ่ม [étale cohomology](https://en.wikipedia.org/wiki/%C3%A9tale_cohomology), ศูนย์ของ [Selberg zeta function](https://en.wikipedia.org/wiki/Selberg_zeta_function) เป็น eigenvalue ของ [Laplacian operator](https://en.wikipedia.org/wiki/Laplacian_operator) ของพื้นผิวรีมันน์ (Riemann surface), และศูนย์ของ [p-adic zeta function](https://en.wikipedia.org/wiki/p-adic_zeta_function) สอดคล้องกับ eigenvector ของการกระทำของ Galois บนกลุ่ม [ideal class group](https://en.wikipedia.org/wiki/ideal_class_group)s.

โอดลิดโก, เอ. เอ็ม. (ค.ศ. 1987). *On the distribution of spacings between zeros of the zeta function*. *Mathematics of Computation* **48**(177), 273–308. [MR866115](https://mathscinet.ams.org/mathscinet-getitem?mr=MR866115). [JSTOR 2007890](https://www.jstor.org/stable/2007890). doi:[10.2307/2007890](https://doi.org/10.2307/2007890). แสดงให้เห็นว่าการกระจายตัวของศูนย์ของฟังก์ชันซีตาของรีมันมีคุณสมบัติทางสถิติบางอย่างร่วมกับค่าลักษณะเฉพาะของ [random matrices](https://en.wikipedia.org/wiki/random_matrices) ที่ถูกเลือกจาก [Gaussian unitary ensemble](https://en.wikipedia.org/wiki/Gaussian_unitary_ensemble) ซึ่งให้หลักฐานสนับสนุน [Hilbert–Pólya conjecture](https://en.wikipedia.org/wiki/Hilbert%E2%80%93P%C3%B3lya_conjecture) บางส่วน

ในปี 1999, [Michael Berry](https://en.wikipedia.org/wiki/Michael_Berry_%28physicist%29) และ [Jonathan Keating](https://en.wikipedia.org/wiki/Jonathan_Keating) ตั้งสมมติฐานว่ามีการควอนไทซ์ที่ไม่ทราบแน่ชัด $\hat H$ ของแฮมิลโทเนียนแบบคลาสสิก *H* = *xp* เพื่อที่ว่า

$$
\zeta (1/2+i\hat H) = 0
$$

และยิ่งไปกว่านั้นคือศูนย์ของรีมันน์ตรงกันกับสเปกตรัมของตัวดำเนินการ $1/2 + i \hat H$ ซึ่งต่างจาก [canonical quantization](https://en.wikipedia.org/wiki/canonical_quantization) ที่นำไปสู่ [หลักความไม่แน่นอน](https://en.wikipedia.org/wiki/Heisenberg_uncertainty_principle) $\sigma_x \sigma_p \geq \frac{\hbar}{2}$ และ [จำนวนธรรมชาติ](https://en.wikipedia.org/wiki/natural_numbers) เป็นสเปกตรัมของ [quantum harmonic oscillator](https://en.wikipedia.org/wiki/quantum_harmonic_oscillator) จุดสำคัญคือแฮมิลโทเนียนควรเป็นตัวดำเนินการแบบ self-adjoint เพื่อให้การควอนไทซ์เป็นการทำให้เป็นจริงของโปรแกรม Hilbert–Pólya ในบริบทที่เชื่อมโยงกับปัญหานี้เชิงกลศาสตร์ควอนตัม Berry และ Connes ได้เสนอว่าส่วนกลับของศักย์ของแฮมิลโทเนียนนั้นเชื่อมโยงกับ [half-derivative](https://en.wikipedia.org/wiki/half-derivative) ของฟังก์ชัน

$$
N(s)= \frac{1}{\pi}\operatorname{Arg}\xi(1/2+i\sqrt s)
$$

จากนั้น ในแนวทางของฮิลเบิร์ต-โพลียา

$$
V^{-1}(x) = \sqrt{4\pi} \frac{d^{1/2}N(x)}{dx^{1/2}}.
$$

สิ่งนี้ทำให้เกิดแฮมิลโทเนียน Whose eigenvalues are the square of the imaginary part of the Riemann zeros และทำให้ [functional determinant](https://en.wikipedia.org/wiki/functional_determinant) ของ [แฮมิลโทเนียน](https://en.wikipedia.org/wiki/Hamiltonian_operator) นี้เท่ากับ [Riemann Xi function](https://en.wikipedia.org/wiki/Riemann_Xi_function) พอดี ในความเป็นจริงแล้ว Riemann Xi function จะแปรผันตรงกับ functional determinant ([Hadamard product](https://en.wikipedia.org/wiki/Hadamard_product_%28matrices%29))

$$
\det(H+1/4+s(s-1))
$$

$$
\frac{\xi(s)}{\xi(0)}=\frac{\det(H+s(s-1)+1/4)}{\det(H+1/4)}.
$$

อย่างไรก็ตาม ตัวดำเนินการนี้ไม่มีความเป็นประโยชน์ในทางปฏิบัติ เนื่องจากมันรวมฟังก์ชันผกผัน (ฟังก์ชันโดยนัย) ของศักย์ แต่ไม่รวมศักย์เอง
การเปรียบเทียบแบบนัยกับสมมติฐานของรีมันเหนือ [ฟิลด์จำกัด](https://en.wikipedia.org/wiki/finite_field) ชี้ให้เห็นว่า ปริภูมิฮิลเบิร์ทที่มีเวกเตอร์ไอเกนที่สอดคล้องกับศูนย์อาจเป็นกลุ่มโคโฮโมโลยีอันดับแรก [กลุ่มโคโฮโมโลยี](https://en.wikipedia.org/wiki/cohomology_group) ของ [สเปกตรัม](https://en.wikipedia.org/wiki/spectrum_of_a_ring) Spec (*Z*) ของจำนวนเต็ม เดนิงเงอร์ คริสโตเฟอร์ (1998). *Proceedings of the International Congress of Mathematicians, Vol. I (Berlin, 1998)*. 163–186. [MR1648030](https://mathscinet.ams.org/mathscinet-getitem?mr=MR1648030). อธิบายบางส่วนของความพยายามในการค้นหาทฤษฎีโคโฮโมโลยีดังกล่าว เลอชต์แนม เอริค (2005). *Geometry, spectral theory, groups, and dynamics*. *Amer. Math. Soc.* **387**, 201–236. ISBN 978-0-8218-3710-8. [MR2180209](https://mathscinet.ams.org/mathscinet-getitem?mr=MR2180209). doi:[10.1090/conm/387/07243](https://doi.org/10.1090/conm/387/07243).

ดอน ซากิเออร์ (Don Zagier) (1981). *รูปแบบออโตมอร์ฟิก ทฤษฎีการแทนค่า และเลขคณิต (บอมเบย์, 1979)*. *สถาบันตาตาเพื่อการวิจัยพื้นฐาน, บอมเบย์* **10**, 275–301. [MR633666](https://mathscinet.ams.org/mathscinet-getitem?mr=MR633666). ได้สร้างพื้นที่ธรรมชาติของฟังก์ชันไม่แปรเปลี่ยนบนระนาบครึ่งบนที่มีค่าลักษณะเฉพาะภายใต้ตัวดำเนินการลาปลาซ ซึ่งสอดคล้องกับศูนย์ของฟังก์ชันซีตาของรีมัน—and ได้ระบุว่าในเหตุการณ์ที่เป็นไปไม่ได้มากว่าถ้าสามารถแสดงให้เห็นถึงการมีอยู่ของผลคูณภายในที่เป็นบวกแน่นอนที่เหมาะสมบนพื้นที่นี้ สมมติฐานของรีมันจะตามมา. ปีแยร์ การ์เตียร์ (P. Cartier) (1982). *การประชุมสัมมนาเกี่ยวกับทฤษฎีจำนวน ปารีส 1980–81 (ปารีส, 1980/1981)*. *บิร์คเฮอเซอร์ บอสตัน* **22**, 35–48. [MR693308](https://mathscinet.ams.org/mathscinet-getitem?mr=MR693308). ได้กล่าวถึงตัวอย่างที่เกี่ยวข้อง ซึ่งเนื่องจากบั๊กที่แปลกประหลาด โปรแกรมคอมพิวเตอร์ได้ระบุศูนย์ของฟังก์ชันซีตาของรีมันว่าเป็นค่าลักษณะเฉพาะของตัวดำเนินการ [ลาปลาซ](https://en.wikipedia.org/wiki/Laplacian_operator) เดียวกัน.

Schumayer, Daniel; Hutchinson, David A. W. (2011). *ฟิสิกส์ของสมมติฐานของรีมัน*. *Reviews of Modern Physics* **83**(2), 307–330. [arXiv:1101.3116](https://arxiv.org/abs/1101.3116). [2011RvMP...83..307S](https://ui.adsabs.harvard.edu/abs/2011RvMP...83..307S). doi:[10.1103/RevModPhys.83.307](https://doi.org/10.1103/RevModPhys.83.307). สำรวจบางส่วนของความพยายามในการสร้างแบบจำลองฟิสิกส์ที่เหมาะสมที่เกี่ยวข้องกับฟังก์ชันซีตาของรีมัน

### ทฤษฎีบทลี–หยาง

ทฤษฎีลี–หยาง (Lee–Yang theorem) ระบุว่าศูนย์ของฟังก์ชันพาร์ติชันบางประเภทในกลศาสตร์เชิงสถิติ ทั้งหมดตั้งอยู่บน "เส้นวิกฤต" โดยมีส่วนจริงเท่ากับ 0 และสิ่งนี้ได้นำไปสู่การคาดเดาบางอย่างเกี่ยวกับความสัมพันธ์กับสมมติฐานของรีมัน

### ผลลัพธ์ของทูราน

[พาล ทูราน](https://en.wikipedia.org/wiki/P%C3%A1l_Tur%C3%A1n) แสดงให้เห็นว่าถ้าฟังก์ชัน

$$
\sum_{n=1}^N n^{-s}
$$

ไม่มีศูนย์เมื่อส่วนจริงของ *s* มากกว่าหนึ่ง

$$
T(x) = \sum_{n\le x}\frac{\lambda(n)}{n}\ge 0\text{ for } x > 0,
$$

ที่ซึ่ง λ(*n*) คือ ฟังก์ชันลิอูวิลล์ [^22] ซึ่งกำหนดให้เท่ากับ (−1)<sup>*r*</sup> หาก *n* มีตัวประกอบจำนวนเฉพาะ *r* ตัว เขาแสดงให้เห็นว่าสิ่งนี้ย่อมส่งผลให้สมมติฐานของรีมันเป็นจริง แต่เฮเซลโกรฟ, ซี. บี. (1958). *การพิสูจน์ข้อผิดพลาดของข้อความคาดการณ์ของโพเลีย*. *Mathematika* **5**(2), 141–145. [MR0104638](https://mathscinet.ams.org/mathscinet-getitem?mr=MR0104638). doi:[10.1112/S0025579300001480](https://doi.org/10.1112/S0025579300001480). ได้พิสูจน์ว่า *T*(*x*) เป็นค่าลบสำหรับ *x* จำนวนมากอย่างไม่มีที่สิ้นสุด (และยังได้หักล้างข้อความคาดการณ์ที่เกี่ยวข้องอย่างใกล้ชิด [Pólya conjecture](https://en.wikipedia.org/wiki/P%C3%B3lya_conjecture)) และโบรวิน, ปีเตอร์; เฟอร์กูสัน, รอน; มอสซิงออฟ, ไมเคิล เจ. (2008). *การเปลี่ยนแปลงเครื่องหมายในผลรวมของฟังก์ชันลิอูวิลล์*. *Mathematics of Computation* **77**(263), 1681–1694. [MR2398787](https://mathscinet.ams.org/mathscinet-getitem?mr=MR2398787). [2008MaCom..77.1681B](https://ui.adsabs.harvard.edu/abs/2008MaCom..77.1681B). doi:[10.1090/S0025-5718-08-02036-X](https://doi.org/10.1090/S0025-5718-08-02036-X). ได้แสดงให้เห็นว่า *x* เล็กที่สุดที่มีลักษณะดังกล่าวคือ 72 185 376 951 205 สปีรา, โรเบิร์ต (1968). *ศูนย์ของส่วนย่อยของฟังก์ชันซีตา. II*. *Mathematics of Computation* **22**(101), 163–173. [MR0228456](https://mathscinet.ams.org/mathscinet-getitem?mr=MR0228456). [JSTOR 2004774](https://www.jstor.org/stable/2004774). doi:[10.2307/2004774](https://doi.org/10.2307/2004774). ได้แสดงให้เห็นโดยการคำนวณเชิงตัวเลขว่าอนุกรมดิริชเลต์  ด้านบนสำหรับ *N* = 19 มีศูนย์ที่มีส่วนจริงมากกว่า 1 ตูรานยังแสดงให้เห็นว่าสมมติฐานที่อ่อนกว่าเล็กน้อย การไม่มีอยู่ของศูนย์ที่มีส่วนจริงมากกว่า 1 + *N*<sup>−1/2+*ε*</sup> สำหรับ *N* ขนาดใหญ่ในอนุกรมดิริชเลต์ด้านบน ก็ย่อมส่งผลให้สมมติฐานของรีมันเป็นเช่นเดียวกัน แต่มอนต์โกเมอรี, ฮิวจ์ เออล. (1983). *การศึกษาในคณิตศาสตร์บริสุทธิ์. เพื่อรำลึกถึงพอล ตูราน*. *Birkhäuser*, 497–506. ISBN 978-3-7643-1288-6. [MR820245](). ได้แสดงให้เห็นว่าสำหรับ *N* ทั้งหมดที่มีขนาดมากเพียงพอ อนุกรมเหล่านี้จะมีศูนย์ที่มีส่วนจริงมากกว่า 1 + (log log *N*)/(4 log *N*) ดังนั้น ผลลัพธ์ของตูรานจึงเป็น [vacuously true]() และไม่สามารถช่วยพิสูจน์สมมติฐานของรีมันได้

### เรขาคณิตที่ไม่สลับที่

[Alain Connes](https://en.wikipedia.org/wiki/Alain_Connes) อธิบายความสัมพันธ์ระหว่างสมมติฐานของรีมันและเรขาคณิตแบบไม่สลับที่ และแสดงให้เห็นว่าแอนะล็อกที่เหมาะสมของสูตรติดตามของเซลเบิร์ก สำหรับการทำงานของกลุ่มคลาสอิเดิลบนพื้นที่คลาสอาเดิล จะนำไปสู่สมมติฐานของรีมัน บางส่วนของแนวคิดเหล่านี้ได้รับการขยายความใน Lapidus, Michel L. (2008). *In search of the Riemann zeros*. *American Mathematical Society*. ISBN 978-0-8218-4222-5. [MR2375028](https://mathscinet.ams.org/mathscinet-getitem?mr=MR2375028). doi:[10.1090/mbk/051](https://doi.org/10.1090/mbk/051). [^23]

### พื้นที่ฮิลเบิรทของฟังก์ชันทั้ง

[Louis de Branges](https://en.wikipedia.org/wiki/Louis_de_Branges_de_Bourcia) แสดงให้เห็นว่าสมมติฐานของรีมันจะตามมาจากเงื่อนไขความเป็นบวกต่อ [ปริภูมิฮิลเบิร์ท](https://en.wikipedia.org/wiki/Hilbert_space) ของฟังก์ชัน [entire function](https://en.wikipedia.org/wiki/entire_function)s.[^24]
อย่างไรก็ตาม Conrey, J. B.; Li, Xian-Jin (2000). *A note on some positivity conditions related to zeta and L-functions*. *International Mathematics Research Notices* **2000**(18), 929–940. [MR1792282](https://mathscinet.ams.org/mathscinet-getitem?mr=MR1792282). [arXiv:math/9812166](https://arxiv.org/abs/math/9812166). doi:[10.1155/S1073792800000489](https://doi.org/10.1155/S1073792800000489). แสดงให้เห็นว่าเงื่อนไขความเป็นบวกที่จำเป็นนั้นไม่ได้รับการยืนยัน แม้จะมีอุปสรรคนี้ de Branges ยังคงทำงานต่อในการพิสูจน์สมมติฐานของรีมันตามแนวทางเดียวกัน แต่สิ่งนี้ยังไม่ได้รับการยอมรับอย่างกว้างขวางโดยนักคณิตศาสตร์คนอื่น ๆ Sarnak, Peter (2005). *Problems of the Millennium: The Riemann Hypothesis (2004)*. *Clay Mathematics Institute*. [Problems of the Millennium: The Riemann Hypothesis (2004)](http://www.claymath.org/sites/default/files/sarnak_rh_0.pdf).

### ควอซีคริสตัล

สมมติฐานของรีมัน (Riemann hypothesis) บ่งชี้ว่า ศูนย์ของฟังก์ชันซีตา (zeta function) มีลักษณะเป็นควอซีคริสตัล(quasicrystal) ซึ่งเป็นการกระจายตัวที่มีจุดรองรับแบบไม่ต่อเนื่อง而其การแปลงฟูรีเย (Fourier transform) ก็มีจุดรองรับแบบไม่ต่อเนื่องเช่นกัน(https://en.wikipedia.org/wiki/Fourier_transform)
ไดสัน, ฟรีแมน (Dyson, Freeman) (2009). *นกและกบ* (Birds and frogs). *วารสารสมาคมคณิตศาสตร์อเมริกัน* (Notices of the American Mathematical Society) **56**(2), 212–223. [MR2483565](https://mathscinet.ams.org/mathscinet-getitem?mr=MR2483565). [นกและกบ](https://www.ams.org/notices/200902/rtx090200212p.pdf) แนะนำให้พยายามพิสูจน์สมมติฐานของรีมันโดยการจัดหมวดหมู่ หรืออย่างน้อยก็ศึกษา ควอซีคริสตัลแบบหนึ่งมิติ(https://en.wikipedia.org/wiki/quasicrystal)

### ฟังก์ชันซีตาเลขคณิตของแบบจำลองเส้นโค้งเชิงวงรีเหนือฟิลด์จำนวน

เมื่อพิจารณาจากการเปลี่ยนจากมิติทางเรขาคณิตหนึ่ง เช่น [สนามจำนวนเชิงพีชคณิต](https://en.wikipedia.org/wiki/algebraic_number_field) ไปสู่มิติทางเรขาคณิตสอง เช่น แบบจำลองปกติของ [เส้นโค้งเชิงวงรี](https://en.wikipedia.org/wiki/elliptic_curve) เหนือสนามจำนวน ส่วนที่เป็นสองมิติของสมมติฐานของรีมันแบบทั่วไปสำหรับ [ฟังก์ชันซีตาทางคณิตศาสตร์](https://en.wikipedia.org/wiki/arithmetic_zeta_function) ของแบบจำลองนั้นเกี่ยวข้องกับการศึกษาจุดขั้วของฟังก์ชันซีตา ในมิติหนึ่งการศึกษาอินทิกรัลซีตาใน [วิทยานิพนธ์ของเทต](https://en.wikipedia.org/wiki/Tate%27s_thesis) ไม่ได้นำไปสู่ข้อมูลสำคัญใหม่เกี่ยวกับสมมติฐานของรีมัน ตรงกันข้าม ในมิติสองผลงานของ [ไอวาน เฟเซนโก](https://en.wikipedia.org/wiki/Ivan_Fesenko) เกี่ยวกับการขยายวิทยานิพนธ์ของเทตในสองมิติรวมถึงการแสดงแทนแบบอินทิกรัลของอินทิกรัลซีตาที่มีความเกี่ยวข้องอย่างใกล้ชิดกับฟังก์ชันซีตา ในสถานการณ์ใหม่ที่ไม่สามารถเกิดขึ้นได้ในมิติหนึ่ง จุดขั้วของฟังก์ชันซีตาสามารถศึกษาได้ผ่านอินทิกรัลซีตาและกลุ่มอาเดิลที่เกี่ยวข้อง ข้อมความคาดการณ์ที่เกี่ยวข้องของ [ไอวาน เฟเซนโก](https://en.wikipedia.org/wiki/Ivan_Fesenko) เกี่ยวกับความเป็นบวกของอนุพันธ์อันดับสี่ของฟังก์ชันขอบที่เกี่ยวข้องกับอินทิกรัลซีตาโดยพื้นฐานแล้วบ่งชี้ส่วนที่เป็นจุดขั้วของสมมติฐานของรีมันแบบทั่วไป.[^25] ซุซูกิ มาซาโตชิ (2011). *ความเป็นบวกของฟังก์ชันบางประการที่เกี่ยวข้องกับการวิเคราะห์บนพื้นผิวเชิงวงรี*. *วารสารทฤษฎีจำนวน* **131**(10), 1770–1796. doi:[10.1016/j.jnt.2011.03.007](https://doi.org/10.1016/j.jnt.2011.03.007). ได้พิสูจน์ว่าข้อหลังร่วมกับสมมติฐานทางเทคนิคบางอย่าง บ่งชี้ข้อคาดการณ์ของเฟเซนโก

### ฟังก์ชันซิกมาหลายตัว

การพิสูจน์สมมติฐานของรีมันของเดลีนเหนือฟิลด์จำกัดใช้ฟังก์ชันซีตาของพันธุ์ผลคูณ Whose zeros and poles correspond to sums of zeros and poles of the original zeta function, in order to bound the real parts of the zeros of the original zeta function. โดยเปรียบเทียบกัน Kurokawa, Nobushige (1992). *Zeta functions in geometry (Tokyo, 1990)*. *Kinokuniya* **21**, 219–226. [MR1210791](https://mathscinet.ams.org/mathscinet-getitem?mr=MR1210791). ได้แนะนำฟังก์ชันซีตาหลายชั้น Whose zeros and poles correspond to sums of zeros and poles of the Riemann zeta function. เพื่อให้ลำดับลู่เข้าเขาจำกัดไว้ที่ผลรวมของศูนย์หรือขั้วทั้งหมดที่มีส่วนจินตภาพไม่เป็นลบ ดังนั้นจนถึงปัจจุบันขอบเขตที่ทราบเกี่ยวกับศูนย์และขั้วของฟังก์ชันซีตาหลายชั้นนั้นไม่แข็งแรงพอที่จะให้ค่าประมาณที่เป็นประโยชน์สำหรับศูนย์ของฟังก์ชันซีตาของรีมัน

## ตำแหน่งของศูนย์

### จำนวนศูนย์

สมการเชิงฟังก์ชัน (functional equation) เมื่อรวมกับ [หลักการของอาร์กิวเมนต์](https://en.wikipedia.org/wiki/argument_principle) (argument principle) บ่งชี้ว่า จำนวนศูนย์ของฟังก์ชันซีตา (zeta function) ที่มีส่วนจินตภาพอยู่ระหว่าง 0 และ *T* นั้นกำหนดโดย

$$
N(T)=\frac{1}{\pi}\mathop{\mathrm{Arg}}(\xi(s)) = \frac{1}{\pi}\mathop{\mathrm{Arg}}(\Gamma(\tfrac{s}{2})\pi^{-\frac{s}{2}}\zeta(s)s(s-1)/2)
$$

สำหรับ *s* = 1/2 + *iT* โดยที่อาร์กิวเมนต์ถูกนิยามโดยการเปลี่ยนแปลงอย่างต่อเนื่องตามเส้นตรงที่มี Im(*s*) = *T* โดยเริ่มจากอาร์กิวเมนต์ 0 ที่ ∞ + *iT* นี่คือผลรวมของพจน์ขนาดใหญ่แต่เป็นที่เข้าใจอย่างชัดเจน

$$
\frac{1}{\pi}\mathop{\mathrm{Arg}}(\Gamma(\tfrac{s}{2})\pi^{-s/2}s(s-1)/2) = \frac{T}{2\pi}\log\frac{T}{2\pi}-\frac{T}{2\pi} +7/8+O(1/T)
$$

และพจน์ขนาดเล็กแต่ค่อนข้างลึกลับ

$$
S(T) = \frac{1}{\pi}\mathop{\mathrm{Arg}}(\zeta(1/2+iT)) =O(\log T).
$$

ดังนั้นความหนาแน่นของศูนย์ที่มีส่วนจินตภาพใกล้เคียง *T* จึงประมาณ log(*T*)/(2 $\pi$) และฟังก์ชัน *S* อธิบายความเบี่ยงเบนเล็กน้อยจากค่านี้ ฟังก์ชัน *S*(*t*) กระโดดขึ้น 1 ที่แต่ละศูนย์ของฟังก์ชันซีตา และสำหรับ *t* ≥ 8 มันจะลดลง [monotonically](https://en.wikipedia.org/wiki/Monotonically_decreasing) ระหว่างศูนย์โดยมีอนุพันธ์ใกล้เคียง −log *t*

Trudgian, Timothy S. (2014). *ขอบเขตบนที่ปรับปรุงแล้วสำหรับอาร์กิวเมนต์ของฟังก์ชันซีตาของรีมันบนเส้นวิกฤต II*. *J. Number Theory* **134**, 280–292. [arXiv:1208.5846](https://arxiv.org/abs/1208.5846). doi:[10.1016/j.jnt.2013.07.017](https://doi.org/10.1016/j.jnt.2013.07.017). พิสูจน์ว่า ถ้า *T* > *e* แล้ว
  $|N(T) - \frac{T}{2\pi} \log{\frac{T}{2\pi e}}| \leq 0.112 \log T + 0.278 \log\log T + 3.385 + \frac{0.2}{T}$.

[คาราตซุบะ](https://en.wikipedia.org/wiki/Anatolii_Alexeevitch_Karatsuba) (ค.ศ. 1996) พิสูจน์ว่าช่วง (*T*, *T* + *H*] สำหรับ $H \ge T^{\frac{27}{82}+\varepsilon}$ นั้นมีจำนวนอย่างน้อย

$$
H(\log T)^{\frac{1}{3}}e^{-c\sqrt{\log\log T}}
$$

จุดที่ฟังก์ชัน *S*(*t*) เปลี่ยนเครื่องหมาย

Atle Selberg (1946). *ฟังก์ชันซีตาของรีมัน* **48**(5), 89–155. [MR0020594](https://mathscinet.ams.org/mathscinet-getitem?mr=MR0020594). แสดงให้เห็นว่าค่าเฉลี่ยของโมเมนต์ของกำลังคู่ของ *S* นั้นกำหนดโดย

$$
\int_0^T|S(t)|^{2k}dt = \frac{(2k)!}{k!(2\pi)^{2k}}T(\log \log T)^k + O(T(\log \log T)^{k-1/2}).
$$

สิ่งนี้ชี้ให้เห็นว่า *S*(*T*)/(log log *T*)<sup>1/2</sup> คล้ายกับตัวแปรสุ่มแบบเกาส์เซียน [Gaussian random variable](https://en.wikipedia.org/wiki/Gaussian_random_variable) ที่มีค่าเฉลี่ย 0 และความแปรปรวน 2 $\pi$<sup>2</sup> (Ghosh, Amit (1983). *On the Riemann zeta function—mean value theorems and the distribution of |S(T)|*. *J. Number Theory* **17**, 93–102. doi:[10.1016/0022-314X(83)90010-0](https://doi.org/10.1016/0022-314X%2883%2990010-0). ได้พิสูจน์ข้อเท็จจริงนี้)
โดยเฉพาะอย่างยิ่ง $|*S*(*T*)|$ มักจะอยู่ที่ประมาณ (log log *T*)<sup>1/2</sup> แต่บางครั้งก็มากกว่านั้นมาก ลำดับการเติบโตที่แน่นอนของ *S*(*T*) ยังไม่เป็นที่ทราบ มีการพัฒนาขอบเขตดั้งเดิมของรีมันน์ *S*(*T*) = *O*(log *T*) แบบไม่มีเงื่อนไขเพิ่มเข้ามาไม่ได้ แม้สมมติฐานของรีมันน์จะนัยถึงขอบเขตที่เล็กกว่าเล็กน้อย *S*(*T*) = *O*(log *T*/log log *T*) Titchmarsh, Edward Charles (1986). *The theory of the Riemann zeta-function*. *The Clarendon Press Oxford University Press*. ISBN 978-0-19-853369-6. [MR882550](https://mathscinet.ams.org/mathscinet-getitem?mr=MR882550) ลำดับขนาดที่แท้จริงอาจน้อยกว่านี้เล็กน้อย เนื่องจากฟังก์ชันสุ่มที่มีการกระจายตัวเช่นเดียวกับ *S*(*T*) มีแนวโน้มที่จะมีการเติบโตของลำดับประมาณ log(*T*)<sup>1/2</sup> ในทิศทางอื่น ๆ มันไม่สามารถเล็กเกินไป: Selberg, Atle (1946). *Contributions to the theory of the Riemann zeta-function*. *Arch. Math. Naturvid.* **48**(5), 89–155. [MR0020594](https://mathscinet.ams.org/mathscinet-getitem?mr=MR0020594) แสดงว่า *S*(*T*) ≠ *o*((log *T*)<sup>1/3</sup>/(log log *T*)<sup>7/3</sup>) และโดยสมมติฐานของรีมันน์ มอนต์gomery ได้แสดงว่า *S*(*T*) ≠ *o*((log *T*)<sup>1/2</sup>/(log log *T*)<sup>1/2</sup>)

การคำนวณเชิงตัวเลขยืนยันว่า *S* เติบโตช้ามาก: $|*S*(*T*)|$ \< 1 สำหรับ *T* \< 280, $|*S*(*T*)|$ \< 2 สำหรับ *T* \< 6800000, และค่าสูงสุดของ $|*S*(*T*)|$ ที่พบจนถึงปัจจุบันไม่ได้มากกว่า 3 มากนัก。 Odlyzko, Andrew (2002). *Zeros of the Riemann zeta function: Conjectures and computations*. [ศูนย์ของฟังก์ชันซีตาของรีมัน: ข้อความคาดการณ์และการคำนวณ](http://www.dtc.umn.edu/~odlyzko/talks/riemann-conjectures.pdf).

การประมาณค่าของรีมันน์ *S*(*T*) = *O*(log *T*) บ่งชี้ว่าช่องว่างระหว่างศูนย์มีขอบเขต และลีลวูดปรับปรุงสิ่งนี้เล็กน้อย โดยแสดงให้เห็นว่าช่องว่างระหว่างส่วนจินตภาพของพวกมันมีแนวโน้มที่จะเป็น 0

### ทฤษฎีบทของ Hadamard และ de la Vallée-Poussin

และ de la Vallée-Poussin, Ch.J. (1896). *Recherches analytiques sur la théorie des nombres premiers*. *Ann. Soc. Sci. Bruxelles* **20**, 183–256. ได้พิสูจน์อย่างอิสระว่าไม่มีจุดศูนย์ใด ๆ จะอยู่บนเส้น Re(*s*) = 1. เมื่อรวมกับสมการเชิงฟังก์ชันและข้อเท็จจริงที่ว่าไม่มีจุดศูนย์ที่มีส่วนจริงมากกว่า 1 สิ่งนี้แสดงให้เห็นว่าจุดศูนย์ที่ไม่สำคัญทั้งหมดต้องอยู่ในส่วนภายในของแถบวิกฤต 0 \< Re(*s*) \< 1. นี่เป็นขั้นตอนสำคัญในการพิสูจน์ทฤษฎีบทจำนวนเฉพาะ ของพวกเขาครั้งแรก

ทั้งการพิสูจน์ดั้งเดิมที่ฟังก์ชันซีตาไม่มีศูนย์ที่มีส่วนจริงเท่ากับ 1 ก็คล้ายกัน และขึ้นอยู่กับแสดงให้เห็นว่าถ้า *ζ*(1 + *it*) หายไป แล้ว *ζ*(1 + 2*it*) จะเป็นเอกฐาน ซึ่งไม่สามารถเป็นไปได้ วิธีหนึ่งในการทำสิ่งนี้คือการใช้อสมการ

$$
|\zeta(\sigma)^3\zeta(\sigma+it)^4\zeta(\sigma+2it)|\ge 1
$$

สำหรับ *σ* > 1, *t* เป็นจำนวนจริง และพิจารณาขีดจำกัดเมื่อ *σ* → 1 อสมการนี้เกิดขึ้นจากการพิจารณาส่วนจริงของลอการิทึมของผลคูณของออยเลอร์เพื่อให้เห็นว่า

$$
|\zeta(\sigma+it)| = \exp\Re\sum_{p^n}\frac{p^{-n(\sigma+it)}}{n}=\exp\sum_{p^n}\frac{p^{-n\sigma}\cos(t\log p^n)}{n},
$$

โดยที่ผลบวกนี้รวมทุกกำลังของจำนวนเฉพาะ $p^n$ ดังนั้น

$$
|\zeta(\sigma)^3\zeta(\sigma+it)^4\zeta(\sigma+2it)| = \exp\sum_{p^n}p^{-n\sigma}\frac{3+4\cos(t\log p^n)+\cos(2t\log p^n)}{n}
$$

ซึ่งมีค่าอย่างน้อย 1 เนื่องจากพจน์ทั้งหมดในผลบวกเป็นจำนวนบวก เนื่องจากอสมการ

$$
3+4\cos(\theta)+\cos(2\theta) = 2 (1+\cos(\theta))^2\ge0.
$$

### พื้นที่ที่ไม่มีศูนย์

การค้นหาด้วยคอมพิวเตอร์อย่างกว้างขวางที่สุดโดย Platt และ [Trudgian](https://en.wikipedia.org/wiki/Timothy_Trudgian) [(Platt & Trudgian 2021)](https://en.wikipedia.org/wiki/Riemann_hypothesis#CITEREFPlattTrudgian2021) เพื่อหาตัวอย่างที่ขัดแย้งกับสมมติฐานของรีมัน ได้ยืนยันสมมติฐานดังกล่าวสำหรับ $|*t*|$ ≤ $3.0001753328 \times 10^{12}$ นอกเหนือจากนั้น พื้นที่ที่ไม่มีศูนย์เป็นที่รู้จักในฐานะอสมการเกี่ยวกับ *σ* + *i t* ซึ่งอาจเป็นศูนย์ได้ รุ่นเก่าที่สุดมาจาก [De la Vallée-Poussin (1899–1900)](https://en.wikipedia.org/wiki/Riemann_hypothesis#CITEREFde_la_Vall%C3%A9e-Poussin1899%E2%80%931900) ซึ่งพิสูจน์ว่ามีพื้นที่ที่ไม่มีศูนย์ที่สอดคล้องกับ 1 − *σ* ≥ $*C*/log(*t*)$ สำหรับค่าคงที่บวก *C* บางค่า กล่าวอีกนัยหนึ่ง ศูนย์ไม่สามารถอยู่ใกล้เส้น *σ* = 1 ได้มาก: มีพื้นที่ที่ไม่มีศูนย์อยู่ใกล้เส้นนี้ การค้นพบนี้ได้ถูกขยายใหญ่ขึ้นโดยผู้เขียนหลายท่านโดยใช้วิธีการต่าง ๆ เช่น [Vinogradov's mean-value theorem](https://en.wikipedia.org/wiki/Vinogradov%27s_mean-value_theorem)

งานวิจัยล่าสุด[^26]ของ Mossinghoff, Trudgian และ Yang ซึ่งเผยแพร่ในเดือนธันวาคม 2022 ได้เสนอเขตที่ไม่มีศูนย์จำนวน 4 เขตที่ปรับปรุงผลลัพธ์ก่อนหน้าของ Kevin Ford จากปี 2002, ผลลัพธ์ของ Mossinghoff และ Trudgian เองจากปี 2015 และผลงานการปรับปรุงเล็กน้อยของ Pace Nielsen ต่อ Ford จากเดือนตุลาคม 2022:
เมื่อใดก็ตามที่ $|t| \geq 2$,
เมื่อใดก็ตามที่ $|t| \geq 3$ (เขตที่มีขนาดใหญ่ที่สุดที่ทราบในขอบเขต $3.0001753328 \cdot 10^{12} \leq |t| \leq \exp(64.1) \approx 6.89 \cdot 10^{27}$),
  $\sigma\ge 1 - \frac{0.04962 - \frac{0.0196}{1.15 + \log 3 + \frac{1}{6} \log t + \log\log t}}{0.685 + \log 3 + \frac{1}{6} \log t + 1.155 \cdot \log\log t}$ เมื่อใดก็ตามที่ $|t| \geq 1.88 \cdot 10^{14}$ (เขตที่มีขนาดใหญ่ที่สุดที่ทราบในขอบเขต $\exp(64.1) \leq |t| \leq \exp(1000) \approx 1.97 \cdot 10^{434}$) และ
เมื่อใดก็ตามที่ $|t| \geq \exp(1000)$ (เขตที่มีขนาดใหญ่ที่สุดภายในขอบเขตของมันเอง)

บทความนี้ยังนำเสนอการปรับปรุงเขตที่ไม่มีศูนย์รวมที่สอง ซึ่งขอบเขตของมันไม่เป็นที่ทราบ เนื่องจาก $|t|$ ถูกสมมติว่าเป็นเพียง "ใหญ่พอ" เพื่อรองรับข้อกำหนดของบทพิสูจน์ของบทความเท่านั้น ภูมิภาคนี้คือ
  $\sigma\ge 1-\frac{1}{48.1588(\log{|t|})^{2/3}(\log{\log{|t|}})^{1/3}}$.

## จุดศูนย์บนเส้นวิกฤต

Hardy, G. H. (1914). *ฟังก์ชันซีตาของรีมัน* [Sur les Zéros de la Fonction ζ(s) de Riemann](http://gallica.bnf.fr/ark:/12148/bpt6k3111d.image.f1014.langEN). *C. R. Acad. Sci. Paris* **158**, 1012–1014. and Hardy, G. H.; Littlewood, J. E. (1921). *The zeros of Riemann's zeta-function on the critical line*. *Math. Z.* **10**(3–4), 283–317. doi:[10.1007/BF01211614](https://doi.org/10.1007/BF01211614). [The zeros of Riemann's zeta-function on the critical line](https://zenodo.org/record/1447415). แสดงว่ามีศูนย์จำนวนอนันต์อยู่บนเส้นวิกฤต โดยพิจารณาโมเมนต์ของฟังก์ชันบางตัวที่เกี่ยวข้องกับฟังก์ชันซีตา Selberg, Atle (1942). *On the zeros of Riemann's zeta-function*. *SKR. Norske Vid. Akad. Oslo I.* **10**, 59 pp. [MR0010712](https://mathscinet.ams.org/mathscinet-getitem?mr=MR0010712). พิสูจน์ว่าอย่างน้อยสัดส่วนที่เป็นบวก (เล็กน้อย) ของศูนย์นั้นตั้งอยู่บนเส้นนั้น Levinson, N. (1974). *More than one-third of the zeros of Riemann's zeta function are on σ = 1/2*. *Advances in Mathematics* **13**(4), 383–436. [MR0564081](https://mathscinet.ams.org/mathscinet-getitem?mr=MR0564081). doi:[10.1016/0001-8708(74)90074-7](https://doi.org/10.1016/0001-8708%2874%2990074-7). ปรับปรุงสิ่งนี้ให้เหลือหนึ่งในสามของศูนย์โดยเชื่อมโยงศูนย์ของฟังก์ชันซีตาเข้ากับศูนย์ของอนุพันธ์ของมัน และ Conrey, J. B. (1989). *More than two fifths of the zeros of the Riemann zeta function are on the critical line*. *J. Reine Angew. Math.* **1989**(399), 1–26. [MR1004130](https://mathscinet.ams.org/mathscinet-getitem?mr=MR1004130). doi:[10.1515/crll.1989.399.1](https://doi.org/10.1515/crll.1989.399.1). [More than two fifths of the zeros of the Riemann zeta function are on the critical line](http://www.digizeitschriften.de/resolveppn/GDZPPN002206781). ปรับปรุงสิ่งนี้ต่อไปเป็นสองในห้า ในปี 2020 การประมาณการนี้ได้รับการขยายไปถึงห้าในสิบสอง (คือ 41.6%) โดย Pratt, Robles, [Zaharescu](https://en.wikipedia.org/wiki/Alexandru_Zaharescu) และ Zeindler[^27] โดยพิจารณาโมลไฟเออร์ที่ขยายออกซึ่งสามารถรองรับอนุพันธ์อันดับสูงกว่าของฟังก์ชันซีตาและผลรวม Kloosterman ที่เกี่ยวข้อง จนถึงจุดนี้ เกือบทุกการปรับปรุงเหนือครึ่งศตวรรษก่อนหน้าล้วนพึ่งพาการปรับปรุงวิธีการโมลไฟเคชันของ Levinson

ในเดือนสิงหาคม 2026 รุ่นวิจัยที่ยังไม่ได้เผยแพร่ของ [แอนโทรปิก](https://en.wikipedia.org/wiki/Anthropic)'s [แบบจำลองภาษาขนาดใหญ่](https://en.wikipedia.org/wiki/large_language_model) [Claude](https://en.wikipedia.org/wiki/Claude_%28AI%29) ที่ทำงานร่วมกับนักวิจัยมนุษย์อย่างมีปฏิสัมพันธ์ ได้พิสูจน์อย่างไม่มีเงื่อนไขว่าอย่างน้อยสองในสาม (66.6%) ของศูนย์ที่ไม่สำคัญ (non-trivial zeros) ของฟังก์ชันซีตาของรีมัน (Riemann zeta function) ตั้งอยู่บนเส้นวิกฤต.[^28] โดยใช้ตระกูลการทดสอบที่ปรับปรุงแล้ว ขอบเขตนี้ได้รับการปรับปรุงเป็น $\frac{3}{2} - \frac{1}{\sqrt{2}} \cot\left(\frac{1}{\sqrt{2}}\right) \approx 67.25\%$.[^29]

การพิสูจน์นี้บรรลุการกระโดดดังกล่าวโดยละทิ้งวิธีการของ [Levinson](https://en.wikipedia.org/wiki/Norman_Levinson) อย่างสิ้นเชิง แทนที่มันประสบความสำเร็จในการกำจัดสมมติฐานสมมติฐานของรีมันออกจากวิธีการจับคู่ความสัมพันธ์คู่ของ [Hugh Montgomery](https://en.wikipedia.org/wiki/Hugh_Montgomery_%28mathematician%29) ในปี 1973 ผ่านการตีความสูตรชัดเจนของไวล์[^29] เป็นเมทริกซ์แอร้มิตมิติจำกัดเหนือระบบฟังก์ชันทดสอบ (ระบบ Gabor) การพิสูจน์ได้จำกัดจำนวนคู่จุดศูนย์แบบออฟไลน์อย่างไม่มีเงื่อนไขผ่านเทคนิคพีชคณิตเชิงเส้น โดยเฉพาะกฎความเฉื่อยของซิลเวสเตอร์ และอสมการอันดับ-ร่องรอยที่ได้มาจากอสมการร่องรอยของฟอนนอยมันน์ แก่นตรรกะของการพิสูจน์ รวมถึงอสมการเมทริกซ์และพฤติกรรมเชิงซีมโทติกของร่องรอย ได้รับการตรวจสอบอย่างเป็นทางการโดยใช้ตัวพิสูจน์ทฤษฎีบท [Lean 4](https://en.wikipedia.org/wiki/Lean_%28proof_assistant%29)

ในเดือนกันยายน ค.ศ. 2026 Youness Lamzouri ได้ตีพิมพ์การพิสูจน์ที่สั้นลงและง่ายขึ้นสำหรับขอบเขตเดียวกัน Lamzouri หลีกเลี่ยงเครื่องมือทางเมทริกซ์ที่มีมิติจำกัดโดยสิ้นเชิงแทนที่จะใช้เทคนิคพีชคณิตเชิงเส้นด้วยการใช้ความไม่เท่าเทียมกันของ [ปริภูมิฮิลเบิร์ท](https://en.wikipedia.org/wiki/Hilbert_space) เพียงหนึ่งเดียวซึ่งตั้งอยู่บนพื้นฐานของ [ความไม่เท่าเทียมกันของเบสเซล](https://en.wikipedia.org/wiki/Bessel%27s_inequality) และ [การตั้งฉากแบบกราม–ชมิท](https://en.wikipedia.org/wiki/Gram%E2%80%93Schmidt_process)[^30]

ศูนย์ส่วนใหญ่ตั้งอยู่ใกล้กับเส้นวิกฤต (critical line) โดยที่ Bohr, H.; Landau, E. (1914). *Ein Satz über Dirichletsche Reihen mit Anwendung auf die ζ-Funktion und die L-Funktionen*. *Rendiconti del Circolo Matematico di Palermo* **37**(1), 269–272. doi:[10.1007/BF03014823](https://doi.org/10.1007/BF03014823). ได้แสดงให้เห็นว่า สำหรับค่า *ε* ที่เป็นบวกใดๆ จำนวนศูนย์ที่มีส่วนจริงอย่างน้อย 1/2+*ε* และส่วนจินตภาพอยู่ระหว่าง −*T* และ *T* คือ $O(T)$ เมื่อรวมกับข้อเท็จจริงที่ว่า ศูนย์ในแถบวิกฤตมีความสมมาตรเกี่ยวกับเส้นวิกฤต และจำนวนศูนย์ทั้งหมดในแถบวิกฤตคือ $\Theta(T\log T)$ [เกือบทั้งหมด](https://en.wikipedia.org/wiki/almost_all) ของศูนย์ที่ไม่สำคัญ (non-trivial zeros) จะอยู่ภายในระยะ *ε* จากเส้นวิกฤต Ivić, A. (1985). *The Riemann Zeta Function*. *John Wiley & Sons*. ISBN 978-0-471-80634-9. [MR0792089](https://mathscinet.ams.org/mathscinet-getitem?mr=MR0792089). ได้ให้หลายเวอร์ชันที่แม่นยำกว่าของผลลัพธ์นี้ ซึ่งเรียกว่า *zero density estimates* ที่จำกัดจำนวนศูนย์ในบริเวณที่มีส่วนจินตภาพไม่เกิน *T* และส่วนจริงอย่างน้อย 1/2 + *ε*

### ข้อความคาดการณ์ของฮาร์ดี–ลิตเติลวูด

ในปี 1914 [Godfrey Harold Hardy](https://en.wikipedia.org/wiki/G._H._Hardy) ได้พิสูจน์ว่า $\zeta\left(\tfrac{1}{2}+it\right)$ มีศูนย์จริงจำนวนอนันต์

ข้อความคาดการณ์สองข้อถัดไปของ [Hardy](https://en.wikipedia.org/wiki/G._H._Hardy) และ [John Edensor Littlewood](https://en.wikipedia.org/wiki/John_Edensor_Littlewood) เกี่ยวกับระยะห่างระหว่างศูนย์จริงของ $\zeta\left(\tfrac{1}{2}+it\right)$ และเกี่ยวกับความหนาแน่นของศูนย์ของ $\zeta\left(\tfrac{1}{2}+it\right)$ ในช่วง $(T,T+H]$ สำหรับ $T > 0$ ที่มากพอ และ $H = T^{a + \varepsilon}$ และด้วยค่าของ $a > 0$ ที่น้อยที่สุดเท่าที่เป็นไปได้ โดยที่ $\varepsilon > 0$ เป็นจำนวนที่น้อยมากตามอำเภอใจ เปิดสองทิศทางใหม่ในการศึกษาฟังก์ชันซีตาของรีมัน:
1. สำหรับทุก $\varepsilon > 0$ จะมีขอบเขตล่าง $T_0 = T_0(\varepsilon) > 0$ ซึ่งสำหรับ $T \geq T_0$ และ $H=T^{\tfrac{1}{4}+\varepsilon}$ ช่วง $(T,T+H]$ จะประกอบด้วยศูนย์ที่มีลำดับคี่ของฟังก์ชัน $\zeta\bigl(\tfrac{1}{2}+it\bigr)$

ให้ $N(T)$ เป็นจำนวนรวมของศูนย์จริง และ $N_0(T)$ เป็นจำนวนรวมของศูนย์ที่มีลำดับคี่ของฟังก์ชัน $~\zeta\left(\tfrac{1}{2}+it\right)~$ ที่อยู่ในช่วง $(0,T]$~
1. สำหรับทุก $\varepsilon > 0$ จะมี $T_0 = T_0(\varepsilon) > 0$ และค่า $c = c(\varepsilon) > 0$ บางค่า โดยที่สำหรับ $T \geq T_0$ และ $H=T^{\tfrac{1}{2}+\varepsilon}$ ความไม่เท่าเทียมกัน $N_0(T+H)-N_0(T) \geq c H$ เป็นจริง

### ข้อความคาดการณ์ของฟังก์ชันซีตาของเซลเบิร์ก

[Atle Selberg](https://en.wikipedia.org/wiki/Atle_Selberg) ได้ศึกษาปัญหาของ Hardy–Littlewood *2* และพิสูจน์ว่าสำหรับ *ε* > 0 จะมี $T_0 = T_0(\varepsilon) > 0$ และ *c* = *c*(*ε*) > 0 ซึ่งทำให้สำหรับ $T \geq T_0$ และ $H=T^{0.5+\varepsilon}$ อสมการ $N(T+H)-N(T) \geq cH\log T$ เป็นจริง.[^31] Selberg ข้อความคาดการณ์ว่าสิ่งนี้สามารถปรับปรุงให้แน่นขึ้นเป็น $H=T^{0.5}$ [Anatoly Karatsuba](https://en.wikipedia.org/wiki/Anatoly_Karatsuba) ได้พิสูจน์ว่าสำหรับ *ε* คงที่ซึ่งสอดคล้องกับเงื่อนไข 0 \< *ε* \< 0.001, *T* ที่ใหญ่พอ และ $H = T^{a+\varepsilon}$, $a = \tfrac{27}{82} = \tfrac{1}{3} -\tfrac{1}{246}$ ช่วง (*T*, *T*+*H*) จะประกอบด้วยศูนย์จริงอย่างน้อย *cH* log(*T*) ของ [ฟังก์ชันซีตาของรีมัน](./riemann_zeta_function.md) $\zeta\left(\tfrac{1}{2}+it\right)$ และดังนั้นจึงยืนยันข้อความคาดการณ์ของ Selberg.[^32] การประมาณค่าของ Selberg และ Karatsuba ไม่สามารถปรับปรุงได้ในแง่ของลำดับการเติบโตเมื่อ *T* → ∞

พิสูจน์ว่าข้อความคาดการณ์แบบหนึ่งของ Selberg conjecture ถือได้สำหรับช่วงเกือบทั้งหมด (*T*, *T*+*H*], $H = T^\varepsilon$ โดยที่ *ε* เป็นจำนวนบวกคงที่ที่เล็กเท่าใดก็ได้ ในวิธีของ Karatsuba ช่วยให้สามารถศึกษาจุดศูนย์ของฟังก์ชันซีตาของรีมันบนช่วง "supershort" ของเส้นวิกฤต นั่นคือ บนช่วง (*T*, *T*+*H*], ความยาว *H* ของซึ่งเติบโตช้ากว่าระดับใด ๆ แม้แต่ระดับ *T* ที่เล็กเท่าใดก็ได้เป็นพิเศษ เขาพิสูจน์ว่าสำหรับจำนวนที่กำหนดให้ *ε*, $\varepsilon_1$ ที่สอดคล้องกับเงื่อนไข $0<\varepsilon, \varepsilon_1<1$ ช่วงเกือบทั้งหมด (*T*, *T*+*H*] สำหรับ $H\ge\exp{\{(\log T)^\varepsilon\}}$ มีจุดศูนย์อย่างน้อย $H(\log T)^{1-\varepsilon_1}$ ของฟังก์ชัน $\zeta\left(\tfrac{1}{2}+it\right)$ การประมาณนี้ค่อนข้างใกล้เคียงกับหนึ่งที่ได้จากสมมติฐานของรีมัน

### การคำนวณเชิงตัวเลข

ฟังก์ชัน

$$
\pi^{-\frac{s}{2}}\Gamma(\tfrac{s}{2})\zeta(s)
$$

มีศูนย์เหมือนกับฟังก์ชันซีตาในแถบวิกฤต และเป็นจำนวนจริงบนเส้นวิกฤตเนื่องจากสมการเชิงฟังก์ชัน ดังนั้นจึงสามารถพิสูจน์การมีอยู่ของศูนย์ที่ตกเป๊ะๆ บนเส้นจริงระหว่างสองจุดได้โดยการตรวจสอบเชิงตัวเลขว่าฟังก์ชันมีเครื่องหมายตรงข้ามกันที่จุดเหล่านี้ โดยปกติแล้วคนเรามักจะเขียน

$$
\zeta(\tfrac{1}{2} +it) = Z(t)e^{-i\theta(t)}
$$

โดยที่ฟังก์ชัน [Z function](https://en.wikipedia.org/wiki/Z_function) ของฮาร์ดี และฟังก์ชัน [Riemann–Siegel theta function](https://en.wikipedia.org/wiki/Riemann%E2%80%93Siegel_theta_function) *θ* ถูกนิยามอย่างมีเอกลักษณ์จากสิ่งนี้และเงื่อนไขที่ว่าพวกมันเป็นฟังก์ชันจริงที่เรียบ (smooth) โดยมี *θ*(0) = 0
โดยการหาช่วงจำนวนมากที่ฟังก์ชัน *Z* เปลี่ยนเครื่องหมาย สามารถแสดงให้เห็นว่ามีศูนย์จำนวนมากอยู่บนเส้นวิกฤต (critical line) เพื่อตรวจสอบสมมติฐานของรีมันน์ (Riemann hypothesis) ไปจนถึงส่วนจินตภาพ [imaginary part](https://en.wikipedia.org/wiki/imaginary_part) *T* ของศูนย์หนึ่งๆ ก็ต้องตรวจสอบด้วยว่าไม่มีศูนย์เพิ่มเติมอยู่นอกเส้นนี้ในบริเวณนี้ ซึ่งสามารถทำได้โดยการคำนวณจำนวนศูนย์ทั้งหมดในบริเวณนั้นโดยใช้ [Turing's method](https://en.wikipedia.org/wiki/Turing%27s_method) และตรวจสอบว่าจำนวนนั้นเท่ากับจำนวนศูนย์ที่พบบนเส้นหรือไม่ สิ่งนี้ทำให้สามารถตรวจสอบสมมติฐานของรีมันน์ (Riemann hypothesis) ได้อย่างเป็นคอมพิวเตอร์ไปจนถึงค่า *T* ที่ต้องการใดๆ (โดยที่ศูนย์ทั้งหมดของฟังก์ชัน [zeta]() ในบริเวณนี้ต้องเป็นแบบง่าย (simple) และอยู่บนเส้นวิกฤต)[^33] [^34]

การคำนวณเหล่านี้ยังสามารถนำไปใช้ในการประมาณค่า $\pi(x)$ สำหรับช่วงจำกัดของ $x$ ได้ ตัวอย่างเช่น โดยใช้ผลลัพธ์ล่าสุดจากปี 2020 (ศูนย์ที่อยู่ที่ความสูง $3\times10^{12}$) ได้มีการแสดงให้เห็นว่า

$$
|\pi(x) - \operatorname{li}(x)| < \frac{1}{8\pi} \sqrt{x} \log(x), \qquad \text{for } 2657 \le x \le 1.101\times10^{26}.
$$

โดยทั่วไปแล้วอสมการนี้จะเป็นจริงก็ต่อเมื่อ
$ x \ge 2657 $ และ $ \frac{9.06}{\log{\log{x}}}\sqrt{\frac{x}{\log{x}}} \le T, $
โดยที่ $T$ คือค่าที่ทราบว่ามีค่ามากที่สุดซึ่งสมมติฐานของรีมันเป็นจริงสำหรับศูนย์ทั้งหมด $\rho$ ที่มี $\Im{\left (\rho  \right )}\in \left (0,T \right ]$.[^35]

การคำนวณบางส่วนของศูนย์ของฟังก์ชันซีตาของรีมันถูกแสดงไว้ด้านล่าง โดยที่ "ความสูง" ของศูนย์คือขนาดของส่วนจินตภาพของมัน และความสูงของศูนย์ที่ *n* ถูกแทนด้วย *γ<sub>n</sub>*. จนถึงปัจจุบัน ศูนย์ทั้งหมดที่ถูกตรวจสอบล้วนอยู่บนเส้นวิกฤตและเป็นศูนย์อย่างง่าย (ศูนย์หลายเท่าจะทำให้เกิดปัญหาสำหรับอัลกอริทึมในการค้นหาศูนย์ ซึ่งขึ้นอยู่กับ việc การค้นหาการเปลี่ยนเครื่องหมายระหว่างศูนย์) สำหรับตารางของศูนย์ ดูที่ Haselgrove, C. B.; Miller, J. C. P. (1960). *Tables of the Riemann zeta function*. *Cambridge University Press* **6**. [MR0117905](https://mathscinet.ams.org/mathscinet-getitem?mr=MR0117905). หรือ [(Odlyzko)](https://en.wikipedia.org/wiki/Riemann_hypothesis#CITEREFOdlyzko).
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

### จุดไวยากรณ์

**จุดแกรม** (Gram point) คือจุดบนเส้นวิกฤต 1/2 + *it* ที่ฟังก์ชันซีตาเป็นจำนวนจริงและไม่เป็นศูนย์ โดยใช้สูตรของฟังก์ชันซีตาบนเส้นวิกฤต *ζ*(1/2 + *it*) = *Z*(*t*)*e*<sup>−*iθ*(*t*)</sup> โดยที่ฟังก์ชันของฮาร์ดี, [*Z*](https://en.wikipedia.org/wiki/Z_function), เป็นจำนวนจริงสำหรับ *t* ที่เป็นจำนวนจริง และ *θ* คือ [ฟังก์ชันซีตาของรีมันน์–ซีเกล](https://en.wikipedia.org/wiki/Riemann%E2%80%93Siegel_theta_function) เราจะเห็นว่าซีตาเป็นจำนวนจริงเมื่อ sin(*θ*(*t*)) = 0 สิ่งนี้บ่งชี้ว่า *θ*(*t*) เป็นจำนวนเต็มเท่าของ $\pi$ ซึ่งทำให้สามารถคำนวณตำแหน่งของจุดแกรมได้ค่อนข้างง่ายโดยการกลับสูตรของ *θ* โดยปกติแล้วพวกมันจะถูกกำหนดหมายเลขเป็น *g<sub>n</sub>* สำหรับ *n* = 0, 1, ... โดยที่ *g<sub>n</sub>* คือคำตอบที่เป็นเอกลักษณ์ของ *θ*(*t*) = *n* $\pi$

**กฎของแกรม** (Gram's law) คือสิ่งที่แกรมสังเกตว่าโดยปกติจะมีศูนย์ของฟังก์ชันซีตา (zeta function) เพียงหนึ่งเดียวระหว่างจุดแกรม (Gram points) ใดๆ สองจุดที่ติดกัน; ฮัทชินสันเรียกการสังเกตนี้ว่า **[กฎของแกรม](https://en.wikipedia.org/wiki/Gram%27s_law)** มีข้อความอื่นที่เกี่ยวข้องกันอย่างใกล้ชิดอีกหลายข้อที่บางครั้งก็เรียกว่ากฎของแกรมเช่นกัน: เช่น (−1)<sup>*n*</sup>*Z*(*g<sub>n</sub>*) มักจะมีค่าเป็นบวก หรือ *Z*(*t*) มักจะมีเครื่องหมายตรงข้ามกันที่จุดแกรม (Gram points) ที่ติดกัน ส่วนส่วนจินตภาพ *γ<sub>n</sub>* ของศูนย์ไม่กี่ตัวแรก (เป็นสีน้ำเงิน) และจุดแกรม (Gram points) ตัวแรกไม่กี่ตัว *g<sub>n</sub>* นั้นแสดงไว้ในตารางต่อไปนี้
|   |   | *g*<sub>−1</sub> | *γ*<sub>1</sub> | *g*<sub>0</sub> | *γ*<sub>2</sub> | *g*<sub>1</sub> | *γ*<sub>3</sub> | *g*<sub>2</sub> | *γ*<sub>4</sub> | *g*<sub>3</sub> | *γ*<sub>5</sub> | *g*<sub>4</sub> | *γ*<sub>6</sub> | *g*<sub>5</sub> |
| --- | --- | --- | --- | --- | --- | --- | --- | --- | --- | --- | --- | --- | --- | --- |
| 0 | 3.436 | 9.667 | 14.135 | 17.846 | 21.022 | 23.170 | 25.011 | 27.670 | 30.425 | 31.718 | 32.935 | 35.467 | 37.586 | 38.999 |

<figure>

![This is a polar plot of the first 20 real values r_n of the zeta function along the critical line, ζ(1/2 + it), with t running from 0 to 50. The values of r_n in this range are the first 10 non-trivial Riemann zeta function zeros and the first 10 Gram points, each labeled by n. Fifty red points have been plotted between each r_n, and the zeros are projected onto concentric magenta rings scaled to show the relative distance between their values of t. Gram's law states that the curve usually crosses the real axis once between zeros.](https://pub-275e30003c354ac0862cc9839e0f952a.r2.dev/docs/math/RiemannZeta_Zeros.svg.png)

<figcaption>

นี่คือแผนภาพขั้วของค่าจริง 20 ค่าแรก *r<sub>n</sub>* ของฟังก์ชันซีตาของรีมัน ตามเส้นวิกฤต *ζ*(1/2 + *it*) โดยที่ *t* มีค่าตั้งแต่ 0 ถึง 50 ค่าของ *r<sub>n</sub>* ในช่วงนี้คือศูนย์ที่ไม่สำคัญ 10 ค่าแรก [ฟังก์ชันซีตาของรีมัน](./riemann_zeta_function.md) และจุดแกรม 10 ค่าแรก [Gram points](./riemann_hypothesis.md#จุดไวยากรณ์) ซึ่งแต่ละค่าถูกติดฉลากด้วย *n* จุดสีแดง 50 จุดถูกพล็อตระหว่างแต่ละ *r<sub>n</sub>* และศูนย์ถูกฉายลงบนวงแหวนสีม่วงแบบรัศมีรวมที่ปรับสเกลเพื่อแสดงความสัมพันธ์ของระยะห่างระหว่างค่าของ t ของพวกมัน
กฎของแกรมระบุว่าเส้นโค้งมักจะตัดแกนจริงหนึ่งครั้งระหว่างศูนย์

</figcaption>

</figure>

การล้มเหลวครั้งแรกของกฎของแกรมเกิดขึ้นที่ศูนย์ลำดับที่ 127 และจุดแกรม $g_{126}$ ซึ่งอยู่ในลำดับที่ "ผิด" 

| *g*<sub>124</sub> | *γ*<sub>126</sub> | *g*<sub>125</sub> | *g*<sub>126</sub> |
| --- | --- | --- | --- |
| *γ*<sub>127</sub> |   |   |   |
| --- | --- | --- | --- |
| *γ*<sub>128</sub> | *g*<sub>127</sub> | *γ*<sub>129</sub> | *g*<sub>128</sub> |
| 279.148 | 279.229 | 280.802 | 282.455 |
| 282.465 |   |   |   |
| --- | --- | --- | --- |
| 283.211 | 284.104 | 284.836 | 285.752 |

จุดแกรม (Gram point) *t* จะเรียกว่า "ดี" (good) ถ้าฟังก์ชันซีตา (zeta function) มีค่าเป็นบวกที่ 1/2 + *it* ดัชนีของจุดแกรม "ไม่ดี" (bad) ที่ฟังก์ชัน *Z* มีเครื่องหมาย "ผิด" (wrong) คือ 126, 134, 195, 211, ... [A114856](https://oeis.org/A114856)  *บล็อกแกรม* (Gram block) คือช่วงที่ถูกจำกัดด้วยจุดแกรม "ดี" (good) สองจุด โดยที่จุดแกรมทั้งหมดระหว่างจุดทั้งสองเป็นจุด "ไม่ดี" (bad) กฎของแกรม (Gram's law) ที่ปรับปรุงโดยโรสเซอร์ (Rosser, J. Barkley; Yohe, J. M.; Schoenfeld, Lowell) (1969) *Information Processing 68 (Proc. IFIP Congress, Edinburgh, 1968), Vol. 1: Mathematics, Software* *North-Holland*, 70–76. [MR0258245](https://mathscinet.ams.org/mathscinet-getitem?mr=MR0258245)  กล่าวว่า บล็อกแกรมมักจะมีจำนวนศูนย์ (zeros) ตามที่คาดไว้ (เท่ากับจำนวนช่วงแกรม) แม้ว่าช่วงแกรมบางช่วงภายในบล็อกอาจไม่มีศูนย์เดียวอย่างแม่นยำก็ตาม ตัวอย่างเช่น ช่วงที่ถูกจำกัดด้วย *g*<sub>125</sub> และ *g*<sub>127</sub> เป็นบล็อกแกรมที่มีจุดแกรม "ไม่ดี" (bad) เดียวคือ *g*<sub>126</sub> และประกอบด้วยจำนวนศูนย์ 2 ตามที่คาดไว้ แม้ว่าช่วงแกรมทั้งสองของมันจะไม่มีศูนย์เดียวอย่างแม่นยำทั้งคู่ โรสเซอร์และคณะ (Rosser et al.) ตรวจสอบแล้วว่าไม่มีข้อยกเว้นต่อกฎของโรสเซอร์ (Rosser's rule) ใน 3 ล้านศูนย์แรก แม้ว่าจะมีข้อยกเว้นต่อกฎของโรสเซอร์ (Rosser's rule) จำนวนอนันต์เมื่อพิจารณาฟังก์ชันซีตา (zeta function) ทั้งหมด

กฎของแกรมและกฎของโรสเซอร์ต่างก็ระบุว่าในบางความหมาย ศูนย์ไม่เบี่ยงเบนจากตำแหน่งที่คาดหวังไปไกลเกินไป ระยะห่างของศูนย์จากตำแหน่งที่คาดหวังนั้นถูกควบคุมโดยฟังก์ชัน *S* ที่นิยามไว้ข้างต้น ซึ่งเติบโตช้ามาก: ค่าเฉลี่ยของมันมีอันดับประมาณ (log log *T*)<sup>1/2</sup> ซึ่งถึงค่า 2 ก็ต่อเมื่อ T อยู่รอบๆ 10<sup>24</sup> สิ่งนี้หมายความว่าทั้งกฎทั้งสองถือได้ส่วนใหญ่ของเวลาสำหรับ *T* ขนาดเล็ก แต่ในที่สุดก็ล้มเหลวบ่อยครั้ง จริงๆ แล้ว Trudgian, Timothy (2011). *On the success and failure of Gram's Law and the Rosser Rule*. *Acta Arithmetica* **125**(3), 225–256. doi:[10.4064/aa148-3-2](https://doi.org/10.4064/aa148-3-2). แสดงให้เห็นว่าทั้งกฎของแกรมและกฎของโรสเซอร์ล้มเหลวในสัดส่วนที่เป็นบวกของกรณีต่างๆ เพื่อระบุเจาะจง คาดว่าในระยะยาว Hanga, Catalin (2020). *Random matrix models for Gram's law*. *University of York*. [Random matrix models for Gram's law](https://etheses.whiterose.ac.uk/27858/). จะได้ว่าโดยประมาณ 66% ศูนย์หนึ่งตัวถูกห่อหุ้มด้วยจุดแกรมสองจุดติดต่อกัน แต่ใน 17% ไม่มีศูนย์ใดๆ และใน 17% มีศูนย์สองตัวอยู่ในช่วงแกรมดังกล่าว

### ทฤษฎีเมทริกซ์สุ่มและเคออสเชิงควอนตัม

สมมติฐานของรีมัน (Riemann hypothesis) ระบุว่าสามารถตั้งคำถามได้ว่ากฎเกณฑ์แบบใดที่อาจควบคุมการกระจายของศูนย์ของฟังก์ชันซีตา (zeta function) บนเส้นวิกฤตได้ หนึ่งภาพที่เป็นสมมติฐานคือ ศูนย์วิกฤตของฟังก์ชันซีตา (critical zeros of the zeta function) มีพฤติกรรมทางสถิติคล้ายกับค่าลักษณะเฉพาะ (eigenvalues) ของเมทริกซ์แอร้มิต (Hermitian matrices) ขนาดใหญ่แบบสุ่ม [^37] ความคิดนี้เริ่มต้นจากผลงานของ [Hugh Montgomery][^38] เกี่ยวกับ [ข้อความคาดการณ์คู่](https://en.wikipedia.org/wiki/pair_correlation_conjecture) สำหรับศูนย์ของฟังก์ชันซีตา [^39] หลังจากปรับขนาดให้เหมาะสมเพื่อรองรับความหนาแน่นของศูนย์ที่เพิ่มขึ้นตามความสูง ฟังก์ชันคู่ที่คาดการณ์จะสอดคล้องกับค่าลักษณะเฉพาะ (eigenvalue) ใน [กลุ่มหน่วยเกาส์เซียน](https://en.wikipedia.org/wiki/Gaussian_unitary_ensemble) (GUE) ของทฤษฎีเมทริกซ์สุ่ม 

การเชื่อมโยงดังกล่าวได้รับการทดสอบเชิงตัวเลขโดย [Andrew Odlyzko](https://en.wikipedia.org/wiki/Andrew_Odlyzko) ซึ่งพบว่าสถิติการจัดเรียงของศูนย์ที่อยู่สูงบนเส้นวิกฤตสอดคล้องกับคำทำนายของทฤษฎีเมทริกซ์สุ่มแบบ GUE อย่างใกล้ชิด.[^40] [^41] ความสอดคล้องนี้ขยายผลไปเกินกว่าระยะห่างระหว่างเพื่อนบ้านที่ใกล้ที่สุดไปสู่ฟังก์ชันสหสัมพันธ์ที่สูงขึ้น และได้รับการยอมรับอย่างกว้างขวางว่าเป็นหลักฐานที่แข็งแรงว่าศูนย์ถูกจำลองด้วยสถิติท้องถิ่นแบบเดียวกับเมทริกซ์สุ่ม.[^42] [^43]

การเปรียบเทียบเมทริกซ์สุ่มยังมีความเกี่ยวข้องกับการคาดการณ์ของฮิลเบิร์ต–โพเลีย และแนวคิดจาก [quantum chaos](https://en.wikipedia.org/wiki/quantum_chaos) ในระบบควอนตัมที่วุ่นวาย ค่าลักษณะเฉพาะมักปฏิบัติตามสถิติของเมทริกซ์สุ่ม ดังนั้นการปรากฏของสถิติเดียวกันในศูนย์ของฟังก์ชันซีตาจึงสามารถตีความได้ว่าเป็นหลักฐานว่าพวกมันอาจเกิดจากตัวดำเนินการแบบ selfadjoint หรือจากระบบไดนามิกที่วุ่นวาย.[^44] [^45] สิ่งนี้ให้ภาพเชิงประจักษ์ว่าทำไมศูนย์เหล่านั้นอาจตั้งอยู่บนเส้นสเปกตรัม และทำไมระยะห่างระหว่างพวกมันจึงแสดงการผลักกันอย่างแรงแทนที่จะเป็นการกระจุกตัวแบบสุ่ม.[^46]

มุมมองนี้ได้รับการยอมรับโดย [Nicholas Katz](https://en.wikipedia.org/wiki/Nicholas_Katz) และ [Peter Sarnak](https://en.wikipedia.org/wiki/Peter_Sarnak) ซึ่งเสนอว่าตระกูลของ [L-function](https://en.wikipedia.org/wiki/L-function) มีประเภทสมมาตร ([สมมาตร](https://en.wikipedia.org/wiki/unitary_group)) ที่ถูกกำกับโดย [classical group](https://en.wikipedia.org/wiki/classical_group) แบบกะทัดรัด ([unitary](https://en.wikipedia.org/wiki/unitary_group), [orthogonal](https://en.wikipedia.org/wiki/orthogonal_group), หรือ [symplectic](https://en.wikipedia.org/wiki/symplectic_group)) และว่าความแจกแจงของศูนย์ระดับต่ำของพวกมันควรตรงกับกลุ่มตัวอย่างเมทริกซ์สุ่มที่สอดคล้องกัน.[^47] [^48] [^49] สำหรับ ฟังก์ชันซีตาของรีมัน กลุ่มตัวอย่างที่เกี่ยวข้องคือของกลุ่ม unitary group ทฤษฎีเมทริกซ์สุ่มยังนำไปสู่ข้อความคาดการณ์เกี่ยวกับการเติบโตของโมเมนต์ของ ฟังก์ชันซีตา บนเส้นวิกฤต โดยเฉพาะ [Jonathan Keating](https://en.wikipedia.org/wiki/Jonathan_Keating) และ [Nina Snaith](https://en.wikipedia.org/wiki/Nina_Snaith) ใช้ค่าเฉลี่ยเหนือเมทริกซ์ unitary แบบสุ่มเพื่อทำนายค่าคงที่หลักในสูตรโมเมนต์เชิงซีมโทติก เช่น

$$
\frac1T\int_0^T|\zeta(1/2 + it)|^{2k}\,dt
$$

เมื่อ $T\to\infty$ ข้อความคาดการณ์ของพวกเขากำหนดแยกตัวประกอบของเมทริกซ์แบบสุ่มสากลออกจากตัวประกอบของผลคูณออยเลอร์ [Euler product](https://en.wikipedia.org/wiki/Euler_product) และส่งอิทธิพลต่อผลงานภายหลังเกี่ยวกับโมเมนต์และอัตราส่วนของฟังก์ชัน L.[^50] [^51] [^52]

ทฤษฎีมัตริกซ์สุ่มและกลศาสตร์ควอนตัมที่วุ่นวายจึงเป็นกรอบแนวคิดเชิงประจักษ์ที่ล้อมรอบสมมติฐานของรีมัน แม้ว่าจะยังไม่มีหลักฐานยืนยันสมมติฐานนี้จากแนวทางนี้[^53]

## ข้อโต้แย้งสำหรับและต่อต้านสมมติฐานของรีมัน

บทความคณิตศาสตร์เกี่ยวกับสมมติฐานของรีมันมักแสดงออกอย่างระมัดระวังและไม่ยืนยันความจริงของมัน จากผู้เขียนที่แสดงความคิดเห็น ส่วนใหญ่เช่น รีมันน์ เบิร์นฮาร์ด (1859). *Ueber die Anzahl der Primzahlen unter einer gegebenen Grösse*. *Monatsberichte der Berliner Akademie*. [Ueber die Anzahl der Primzahlen unter einer gegebenen Grösse](http://www.maths.tcd.ie/pub/HistMath/People/Riemann/Zeta/). และ บอมบิเอรี เอนริโก (2000). *The Riemann Hypothesis – official problem description*. *Clay Mathematics Institute*. [The Riemann Hypothesis – official problem description](https://web.archive.org/web/20151222090027/http://www.claymath.org/sites/default/files/official_problem_description.pdf). นั้นบ่งชี้ว่าพวกเขาคาดหวัง (หรืออย่างน้อยก็หวัง) ว่าสมมติฐานนี้เป็นจริง ผู้เขียนเพียงไม่กี่คนที่แสดงข้อสงสัยอย่างจริงจังเกี่ยวกับสมมติฐานนี้ ได้แก่ อีวิค อเล็กซานดาร์ (2008). *The Riemann Hypothesis: A Resource for the Afficionado and Virtuoso Alike*. *Springer*, 131–160. ISBN 978-0-387-72125-5. [arXiv:math.NT/0311162](https://arxiv.org/abs/math.NT/0311162). ซึ่งระบุเหตุผลบางประการสำหรับความสงสัย และ ลิตเติลวูด เจ. อี. (1962). *The scientist speculates: an anthology of partly baked idea*. *Basic books*. ซึ่งระบุอย่างชัดเจนว่าเขาเชื่อว่ามันเป็นเท็จ ไม่มีหลักฐานสนับสนุน และไม่มีเหตุผลที่นึกออกได้เลยว่าทำไมมันถึงจะเป็นจริง ความเห็นพ้องต้องกันของบทความสำรวจ ( บอมบิเอรี เอนริโก (2000). *The Riemann Hypothesis – official problem description*. *Clay Mathematics Institute*. [The Riemann Hypothesis – official problem description](https://web.archive.org/web/20151222090027/http://www.claymath.org/sites/default/files/official_problem_description.pdf)., คอนรี เจ. บรียัน (2003). *The Riemann Hypothesis*. *Notices of the American Mathematical Society*, 341–353. [The Riemann Hypothesis](https://www.ams.org/notices/200303/fea-conrey-web.pdf)., และ ซาร์แนค ปีเตอร์ (2005). *Problems of the Millennium: The Riemann Hypothesis (2004)*. *Clay Mathematics Institute*. [Problems of the Millennium: The Riemann Hypothesis (2004)](http://www.claymath.org/sites/default/files/sarnak_rh_0.pdf).) คือหลักฐานสำหรับสมมติฐานนี้มีความแข็งแรงแต่ไม่ท่วมท้น ดังนั้นแม้ว่ามันจะเป็นจริงโดยมีความเป็นไปได้สูง แต่ก็มีความสงสัยที่สมเหตุสมผล

บางส่วนของข้อโต้แย้งทั้งสนับสนุนและคัดค้านสมมติฐานของรีมัน (Riemann hypothesis) ได้ถูกระบุโดย Conrey, J. Brian (2003). *The Riemann Hypothesis*. *Notices of the American Mathematical Society*, 341–353. [The Riemann Hypothesis](https://www.ams.org/notices/200303/fea-conrey-web.pdf)., Sarnak, Peter (2005). *Problems of the Millennium: The Riemann Hypothesis (2004)*. *Clay Mathematics Institute*. [Problems of the Millennium: The Riemann Hypothesis (2004)](http://www.claymath.org/sites/default/files/sarnak_rh_0.pdf)., และ Ivić, Aleksandar (2008). *The Riemann Hypothesis: A Resource for the Afficionado and Virtuoso Alike*. *Springer*, 131–160. ISBN 978-0-387-72125-5. [arXiv:math.NT/0311162](https://arxiv.org/abs/math.NT/0311162)., และรวมถึงรายการต่อไปนี้:
* มีหลายกรณีเทียบเท่าของสมมติฐานของรีมัน (Riemann hypothesis) ที่ได้รับการพิสูจน์แล้ว การพิสูจน์สมมติฐานของรีมันสำหรับพันธุ์ทางเรขาคณิตเหนือฟิลด์จำกัดโดย Deligne, Pierre (1974). *La conjecture de Weil. I*. *Publications Mathématiques de l'IHÉS* **43**, 273–307. [MR0340258](https://mathscinet.ams.org/mathscinet-getitem?mr=MR0340258). doi:[10.1007/BF02684373](https://doi.org/10.1007/BF02684373). [La conjecture de Weil. I](http://www.numdam.org/item?id=PMIHES_1974__43__273_0). อาจเป็นเหตุผลทางทฤษฎีที่แข็งแกร่งที่สุดในเชิงเดียวที่สนับสนุนสมมติฐานของรีมัน (Riemann hypothesis) สิ่งนี้ให้หลักฐานบางอย่างสำหรับข้อความคาดการณ์ (conjecture) ที่กว้างขึ้นว่า ฟังก์ชันซีตา (zeta functions) ทั้งหมดที่เกี่ยวข้องกับรูปแบบออโตมอร์ฟิก (automorphic) forms สอดคล้องกับสมมติฐานของรีมัน (Riemann hypothesis) ซึ่งรวมถึงสมมติฐานของรีมัน (Riemann hypothesis) แบบคลาสสิกในฐานะกรณีพิเศษ นอกจากนี้ ฟังก์ชันซีตาของเซลเบิร์ก (Selberg zeta function) สอดคล้องกับกรณีเทียบเท่าของสมมติฐานของรีมัน (Riemann hypothesis) และในบางแง่คล้ายกับฟังก์ชันซีตาของรีมัน (Riemann zeta function) โดยมีสมการเชิงฟังก์ชัน (functional equation) และการขยายผลคูณอนันต์ (infinite product expansion) ที่คล้ายกับการขยายผลคูณออยเลอร์ (Euler product expansion) แต่ก็มีความแตกต่างที่สำคัญบางประการเช่นกัน; ตัวอย่างเช่น พวกมันไม่ได้กำหนดโดยอนุกรมดีริชเลต์ (Dirichlet series) สมมติฐานของรีมัน (Riemann hypothesis) สำหรับฟังก์ชันซีตาของกอส (Goss zeta function) ได้รับการพิสูจน์โดย Sheats, Jeffrey T. (1998). *The Riemann hypothesis for the Goss zeta function for F<sub>q</sub>[T]*. *Journal of Number Theory* **71**(1), 121–157. [MR1630979](https://mathscinet.ams.org/mathscinet-getitem?mr=MR1630979). [arXiv:math/9801158](https://arxiv.org/abs/math/9801158). doi:[10.1006/jnth.1998.2232](https://doi.org/10.1006/jnth.1998.2232).. ในทางตรงกันข้ามกับตัวอย่างเชิงบวกเหล่านี้ ฟังก์ชันซีตาของเอพสไตน์ (Epstein zeta function) บางตัวไม่สอดคล้องกับสมมติฐานของรีมัน (Riemann hypothesis) แม้ว่าพวกมันจะมีจำนวนศูนย์เป็นอนันต์บนเส้นวิกฤต (critical line) Titchmarsh, Edward Charles (1986). *The theory of the Riemann zeta-function*. *The Clarendon Press Oxford University Press*. ISBN 978-0-19-853369-6. [MR882550](https://mathscinet.ams.org/mathscinet-getitem?mr=MR882550). ฟังก์ชันเหล่านี้คล้ายกับฟังก์ชันซีตาของรีมัน (Riemann zeta function) มาก และมีอนุกรมดีริชเลต์ (Dirichlet series expansion) และการขยายสมการเชิงฟังก์ชัน (functional equation) แต่ตัวที่ทราบกันดีว่าล้มเหลวในสมมติฐานของรีมัน (Riemann hypothesis) ไม่มีผลคูณออยเลอร์ (Euler product) และไม่ได้เกี่ยวข้องโดยตรงกับ [automorphic representation](https://en.wikipedia.org/wiki/automorphic_representation)s
* ในตอนแรก การตรวจสอบเชิงตัวเลขที่แสดงให้เห็นว่าศูนย์จำนวนมากตั้งอยู่บนเส้นดูเหมือนจะเป็นหลักฐานที่แข็งแกร่งสำหรับเรื่องนี้ แต่ทฤษฎีจำนวนเชิงวิเคราะห์มีข้อความคาดการณ์จำนวนมากที่ได้รับความสนับสนุนจากหลักฐานเชิงตัวเลขอย่างมีนัยสำคัญ แต่ท้ายที่สุดก็พิสูจน์แล้วว่าผิด ดู [จำนวนสกีว](https://en.wikipedia.org/wiki/Skewes_number) เป็นตัวอย่างที่เลื่องชื่อ ซึ่งข้อข้อยกเว้นแรกต่อข้อความคาดการณ์ที่เป็นไปได้ซึ่งเกี่ยวข้องกับสมมติฐานของรีมันนั้นน่าจะมีขึ้นประมาณ 10<sup>316</sup>; ตัวอย่างที่ขัดแย้งกับสมมติฐานของรีมันที่มีส่วนจินตภาพขนาดนี้จะเป็นไปไกลเกินกว่าที่จะคำนวณได้โดยใช้วิธีการโดยตรง ปัญหาอยู่ที่ว่าพฤติกรรมมักจะได้รับอิทธิพลจากฟังก์ชันที่เพิ่มขึ้นช้ามาก เช่น log log *T* ซึ่งมีความโน้มเอียงที่จะลู่เข้าไปสู่อนันต์ แต่เกิดขึ้นช้ามากจนไม่สามารถตรวจจับได้ด้วยการคำนวณ ฟังก์ชันดังกล่าวปรากฏในทฤษฎีของฟังก์ชันซีตาซึ่งควบคุมพฤติกรรมของศูนย์ของมัน; ตัวอย่างเช่น ฟังก์ชัน *S*(*T*) ด้านบนนี้มีขนาดเฉลี่ยประมาณ (log log *T*)<sup>1/2</sup> เมื่อ *S*(*T*) กระโดดอย่างน้อย 2 ที่ข้อขัดแย้งใดๆ ต่อสมมติฐานของรีมัน จึงคาดกันว่าข้อขัดแย้งใดๆ ต่อสมมติฐานของรีมันจะปรากฏขึ้นก็ต่อเมื่อ *S*(*T*) มีขนาดใหญ่เท่านั้น มันไม่เคยมีค่ามากกว่า 3 มากนักเท่าที่มีการคำนวณ แต่เป็นที่ทราบกันดีว่าไม่มีขอบเขต ซึ่งบ่งชี้ว่าการคำนวณอาจยังไม่ถึงบริเวณของพฤติกรรมทั่วไปของฟังก์ชันซีตา
นั้นตั้งอยู่บนพื้นฐานของการสังเกตว่าถ้า *μ*(*x*) เป็นลำดับสุ่มของ "1" และ "−1" แล้ว สำหรับทุก *ε* > 0 ผลรวมย่อย [partial sum](https://en.wikipedia.org/wiki/partial_sum)s

$$
M(x) = \sum_{n \le x} \mu(n)
$$

(ค่าของซึ่งคือตำแหน่งใน [การเดินแบบสุ่มอย่างง่าย](https://en.wikipedia.org/wiki/simple_random_walk)) สอดคล้องกับขอบเขต

$$
M(x) = O(x^{1/2+\varepsilon})
$$

ด้วย [ความน่าจะเป็น 1](https://en.wikipedia.org/wiki/Almost_surely) สมมติฐานของรีมัน (Riemann hypothesis) เทียบเท่าขอบเขตนี้สำหรับ [ฟังก์ชันมูบิอุส](https://en.wikipedia.org/wiki/M%C3%B6bius_function) μ และ [ฟังก์ชันเมอร์เทินส์](https://en.wikipedia.org/wiki/Mertens_function) *M* ที่ได้จากมันในแบบเดียวกัน ในคำอื่น ๆ สมมติฐานของรีมันเทียบเท่าในบางความหมายกับการบอกว่า *μ*(*x*) มีพฤติกรรมเหมือนลำดับสุ่มของการโยนเหรียญ เมื่อ *μ*(*x*) มีค่าไม่เป็นศูนย์เครื่องหมายของมันให้ [คู่](https://en.wikipedia.org/wiki/Parity_%28mathematics%29) ของจำนวนตัวประกอบที่เป็นจำนวนเฉพาะของ *x* ดังนั้นโดยทั่วไปแล้ว สมมติฐานของรีมันบอกว่าคู่ของจำนวนตัวประกอบที่เป็นจำนวนเฉพาะของจำนวนเต็มมีพฤติกรรมแบบสุ่ม การโต้แย้งแบบความน่าจะเป็นในทฤษฎีจำนวนมักให้คำตอบที่ถูกต้อง แต่มีแนวโน้มที่จะยากมากที่จะทำให้เป็นรูปธรรม และบางครั้งให้คำตอบที่ผิดสำหรับผลลัพธ์บางประการ เช่น [ทฤษฎีบทของไมเออร์](https://en.wikipedia.org/wiki/Maier%27s_theorem)
* การคำนวณใน Odlyzko, A. M. (1987). *On the distribution of spacings between zeros of the zeta function*. *Mathematics of Computation* **48**(177), 273–308. [MR866115](https://mathscinet.ams.org/mathscinet-getitem?mr=MR866115). [JSTOR 2007890](https://www.jstor.org/stable/2007890). doi:[10.2307/2007890](https://doi.org/10.2307/2007890) แสดงให้เห็นว่าศูนย์ของฟังก์ชันซีตา (zeta function) มีพฤติกรรมเหมือนค่าไอเกนของเมทริกซ์แอร์มิต (Hermitian matrix) แบบสุ่มมาก ซึ่งบ่งชี้ว่าพวกมันเป็นค่าไอเกนของตัวดำเนินการแบบ self-adjoint บางตัว ซึ่งจะทำให้สมมติฐานของรีมันเป็นจริง ทุกความพยายามที่จะหาตัวดำเนินการดังกล่าวล้วนล้มเหลว
มีทฤษฎีบทหลายทฤษฎีบท เช่น ข้อความคาดการณ์ของโกลด์แบคสำหรับจำนวนคี่ที่มีขนาดเพียงพอ ซึ่งได้รับการพิสูจน์ครั้งแรกโดยใช้สมมติฐานของรีมัน และต่อมาแสดงให้เห็นว่าเป็นจริงโดยไม่ต้องมีเงื่อนไข สิ่งนี้สามารถพิจารณาได้ว่าเป็นหลักฐานอ่อนสำหรับสมมติฐานของรีมัน เนื่องจากหลายอย่างจาก "คำทำนาย" ของมันเป็นเรื่องจริง
ปรากฏการณ์ของเลห์เมอร์ ซึ่งเลห์เมอร์, ด. เอช. (1956). *Extended computation of the Riemann zeta-function*. *Mathematika* **3**(2), 102–108. [MR0086083](https://mathscinet.ams.org/mathscinet-getitem?mr=MR0086083). doi:[10.1112/S0025579300001753](https://doi.org/10.1112/S0025579300001753) ที่ซึ่งศูนย์สองศูนย์อยู่ใกล้กันบางครั้ง เป็นเหตุผลที่มักถูกนำมาใช้เพื่อไม่เชื่อในสมมติฐานของรีมัน แต่เราคาดหวังว่าสิ่งนี้จะเกิดขึ้นเป็นครั้งคราวโดยบังเอิญแม้ว่าสมมติฐานของรีมันจะเป็นจริง และคำคำนวณของโอดลยซโกแนะนำว่าคู่ของศูนย์ที่อยู่ใกล้กันเกิดขึ้นบ่อยเพียงใดตามที่ [Montgomery's conjecture](https://en.wikipedia.org/wiki/Montgomery%27s_pair_correlation_conjecture) ทำนายไว้
[Patterson](https://en.wikipedia.org/wiki/Samuel_James_Patterson) แนะนำว่าเหตุผลที่น่าเชื่อถือที่สุดสำหรับสมมติฐานของรีมันสำหรับนักคณิตศาสตร์ส่วนใหญ่คือความหวังที่ว่าจำนวนเฉพาะจะกระจายตัวอย่างเป็นระเบียบมากที่สุดเท่าที่จะเป็นไปได้.[^54]

## หมายเหตุ


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

* เออร์มีล อาร์ติน (1924). *Quadratische Körper im Gebiete der höheren Kongruenzen. II. Analytischer Teil*. *Mathematische Zeitschrift* **19**(1), 207–246. doi:[10.1007/BF01181075](https://doi.org/10.1007/BF01181075).
* แรคบลุนด์, อาร์. เจ. (1914). *Sur les Zéros de la Fonction ζ(s) de Riemann*. *C. R. Acad. Sci. Paris* **158**, 1979–1981. [Sur les Zéros de la Fonction *ζ*(*s*) de Riemann](http://gallica.bnf.fr/ark:/12148/bpt6k3111d/f1983.image).
* เบอริง, อาร์เน (1955). *A closure problem related to the Riemann zeta-function*. *Proceedings of the National Academy of Sciences of the United States of America* **41**(5), 312–314. [MR0070655](https://mathscinet.ams.org/mathscinet-getitem?mr=MR0070655). [1955PNAS...41..312B](https://ui.adsabs.harvard.edu/abs/1955PNAS...41..312B). [PMID 16589670](https://pubmed.ncbi.nlm.nih.gov/16589670/). [528084](https://www.ncbi.nlm.nih.gov/pmc/articles/528084/). doi:[10.1073/pnas.41.5.312](https://doi.org/10.1073/pnas.41.5.312).
* เบริ, เอ็ม. วี.; คีตติ้ง, เจ. พี. (1999). *Supersymmetry and Trace Formulae: Chaos and Disorder*. *Plenum Press*, 355–367..
* บโยร์เนอร์, อันเดอร์ส (2011). *A cell complex in number theory*. *Advances in Applied Mathematics* **46**(1–4), 71–85. [arXiv:1101.5704](https://arxiv.org/abs/1101.5704). doi:[10.1016/j.aam.2010.09.007](https://doi.org/10.1016/j.aam.2010.09.007).
* บอร์, เอช.; แลนดอู, อี. (1914). *Ein Satz über Dirichletsche Reihen mit Anwendung auf die ζ-Funktion und die L-Funktionen*. *Rendiconti del Circolo Matematico di Palermo* **37**(1), 269–272. doi:[10.1007/BF03014823](https://doi.org/10.1007/BF03014823).
* Bombieri, Enrico (ค.ศ. 2000). *สมมติฐานของรีมัน – อธิบายปัญหาอย่างเป็นทางการ*. *สถาบันคณิตศาสตร์เคลย์*. [สมมติฐานของรีมัน – อธิบายปัญหาอย่างเป็นทางการ](https://web.archive.org/web/20151222090027/http://www.claymath.org/sites/default/files/official_problem_description.pdf). พิมพ์ซ้ำใน Borwein, Peter; Ferguson, Ron; Mossinghoff, Michael J. (ค.ศ. 2008). *การเปลี่ยนเครื่องหมายในผลบวกของฟังก์ชันลิอูวิลล์*. *คณิตศาสตร์ของการคำนวณ* **77**(263), 1681–1694. [MR2398787](https://mathscinet.ams.org/mathscinet-getitem?mr=MR2398787). [2008MaCom..77.1681B](https://ui.adsabs.harvard.edu/abs/2008MaCom..77.1681B). doi:[10.1090/S0025-5718-08-02036-X](https://doi.org/10.1090/S0025-5718-08-02036-X)..
* (ค.ศ. 2008). *สมมติฐานของรีมัน: แหล่งทรัพยากรสำหรับผู้ที่หลงใหลและผู้ที่เชี่ยวชาญ alike*. *Springer*. ISBN 978-0-387-72125-5. doi:[10.1007/978-0-387-72126-2](https://doi.org/10.1007/978-0-387-72126-2).
* Borwein, Peter; Ferguson, Ron; Mossinghoff, Michael J. (ค.ศ. 2008). *การเปลี่ยนเครื่องหมายในผลบวกของฟังก์ชันลิอูวิลล์*. *คณิตศาสตร์ของการคำนวณ* **77**(263), 1681–1694. [MR2398787](https://mathscinet.ams.org/mathscinet-getitem?mr=MR2398787). [2008MaCom..77.1681B](https://ui.adsabs.harvard.edu/abs/2008MaCom..77.1681B). doi:[10.1090/S0025-5718-08-02036-X](https://doi.org/10.1090/S0025-5718-08-02036-X).
* de Branges, Louis (ค.ศ. 1992). *การลู่เข้าของผลคูณของออยเลอร์*. *วารสารการวิเคราะห์เชิงฟังก์ชัน* **107**(1), 122–210. [MR1165869](https://mathscinet.ams.org/mathscinet-getitem?mr=MR1165869). doi:[10.1016/0022-1236(92)90103-P](https://doi.org/10.1016/0022-1236%2892%2990103-P).
* บราวแกน, เควิน (ค.ศ. 2017). *สมมูลของสมมติฐานของรีมัน*. *สำนักพิมพ์มหาวิทยาลัยเคมบริดจ์*. ISBN 978-1108290784.
* เบอร์ตัน, เดวิด เอ็ม. (ค.ศ. 2006). *ทฤษฎีจำนวนเบื้องต้น*. *บริษัทพิมพ์ตาตา แมกกราว-ฮิลล์ จำกัด*. ISBN 978-0-07-061607-3. [ทฤษฎีจำนวนเบื้องต้น](https://books.google.com/books?id=XMQjuoTqqRMC).
* การ์เตียร์, พี. (ค.ศ. 1982). *ประชุมสัมมนาเกี่ยวกับทฤษฎีจำนวน, ปารีส ค.ศ. 1980–81 (ปารีส, ค.ศ. 1980/1981)*. *บิร์คเฮอเซอร์ บอสตัน* **22**, 35–48. [MR693308](https://mathscinet.ams.org/mathscinet-getitem?mr=MR693308).
* คอนเนส, อลาน (ค.ศ. 1999). *สูตร Trace ในเรขาคณิตที่ไม่สลับที่และศูนย์ของฟังก์ชันซีตาของรีมัน*. *Selecta Mathematica* **5**(1), 29–106. [MR1694895](https://mathscinet.ams.org/mathscinet-getitem?mr=MR1694895). [arXiv:math/9811068](https://arxiv.org/abs/math/9811068). doi:[10.1007/s000290050042](https://doi.org/10.1007/s000290050042).
* คอนเนส, อลาน (ค.ศ. 2000). *คณิตศาสตร์: ขอบเขตและมุมมอง*. *สมาคมคณิตศาสตร์อเมริกัน*, 35–54. [MR1754766](https://mathscinet.ams.org/mathscinet-getitem?mr=MR1754766).
* คอนเนส, อลาน (ค.ศ. 2016). *ปัญหาที่ยังไม่ได้รับการแก้ไขในคณิตศาสตร์*. *สปริงเกอร์*, 225–257. ISBN 978-3-319-32160-8. [arXiv:1509.05576](https://arxiv.org/abs/1509.05576). doi:[10.1007/978-3-319-32162-2_5](https://doi.org/10.1007/978-3-319-32162-2_5).
* คอนเนส, อลาน (ค.ศ. 2026). *สมมติฐานของรีมัน: อดีต ปัจจุบัน และจดหมายผ่านกาลเวลา*. [arXiv:2602.04022](https://arxiv.org/abs/2602.04022).
* คอนรี, เจ. บี. (ค.ศ. 1989). *มากกว่าสองในห้าของศูนย์ของฟังก์ชันซีตาของรีมันน์อยู่บนเส้นวิกฤต*. *J. Reine Angew. Math.* **1989**(399), 1–26. [MR1004130](https://mathscinet.ams.org/mathscinet-getitem?mr=MR1004130). doi:[10.1515/crll.1989.399.1](https://doi.org/10.1515/crll.1989.399.1). [มากกว่าสองในห้าของศูนย์ของฟังก์ชันซีตาของรีมันน์อยู่บนเส้นวิกฤต](http://www.digizeitschriften.de/resolveppn/GDZPPN002206781).
* คอนรี, เจ. บรียัน (ค.ศ. 2003). *สมมติฐานของรีมันน์*. *Notices of the American Mathematical Society*, 341–353. [สมมติฐานของรีมันน์](https://www.ams.org/notices/200303/fea-conrey-web.pdf). พิมพ์ซ้ำใน Borwein, Peter; Ferguson, Ron; Mossinghoff, Michael J. (ค.ศ. 2008). *การเปลี่ยนเครื่องหมายในผลบวกของฟังก์ชัน Liouville*. *Mathematics of Computation* **77**(263), 1681–1694. [MR2398787](https://mathscinet.ams.org/mathscinet-getitem?mr=MR2398787). [2008MaCom..77.1681B](https://ui.adsabs.harvard.edu/abs/2008MaCom..77.1681B). doi:[10.1090/S0025-5718-08-02036-X](https://doi.org/10.1090/S0025-5718-08-02036-X)..
* คอนรี, เจ. บี.; ลี, เซียน-จิ้น (ค.ศ. 2000). *บันทึกเกี่ยวกับเงื่อนไขความเป็นบวกบางประการที่เกี่ยวข้องกับฟังก์ชันซีตาและ L-functions*. *International Mathematics Research Notices* **2000**(18), 929–940. [MR1792282](https://mathscinet.ams.org/mathscinet-getitem?mr=MR1792282). [arXiv:math/9812166](https://arxiv.org/abs/math/9812166). doi:[10.1155/S1073792800000489](https://doi.org/10.1155/S1073792800000489).
* เดลีน, ปีแยร์ (ค.ศ. 1974). *สมมติฐานของเรียมาน: ส่วนที่ 1*. *Publications Mathématiques de l'IHÉS* **43**, 273–307. [MR0340258](https://mathscinet.ams.org/mathscinet-getitem?mr=MR0340258). doi:[10.1007/BF02684373](https://doi.org/10.1007/BF02684373). [La conjecture de Weil. I](http://www.numdam.org/item?id=PMIHES_1974__43__273_0).
* เดลีน, ปีแยร์ (ค.ศ. 1980). *La conjecture de Weil : II*. *Publications Mathématiques de l'IHÉS* **52**, 137–252. doi:[10.1007/BF02684780](https://doi.org/10.1007/BF02684780). [La conjecture de Weil : II](http://www.numdam.org/item?id=PMIHES_1980__52__137_0).
* เดนิงเงอร์, คริสโตเฟอร์ (ค.ศ. 1998). *Proceedings of the International Congress of Mathematicians, Vol. I (Berlin, 1998)*. 163–186. [MR1648030](https://mathscinet.ams.org/mathscinet-getitem?mr=MR1648030).
* ดูเดก, แอเดรียน เอ. (21 ส.ค. 2014). *On the Riemann hypothesis and the difference between primes*. *International Journal of Number Theory* **11**(3), 771–778. [arXiv:1402.6417](https://arxiv.org/abs/1402.6417). [2014arXiv1402.6417D](https://ui.adsabs.harvard.edu/abs/2014arXiv1402.6417D). doi:[10.1142/S1793042115500426](https://doi.org/10.1142/S1793042115500426).
* ไดสัน, ฟรีแมน (ค.ศ. 2009). *Birds and frogs*. *Notices of the American Mathematical Society* **56**(2), 212–223. [MR2483565](https://mathscinet.ams.org/mathscinet-getitem?mr=MR2483565). [Birds and frogs](https://www.ams.org/notices/200902/rtx090200212p.pdf).
* เอ็ดเวิร์ดส์, เอช. เอ็ม. (ค.ศ. 1974). *ฟังก์ชันซีตาของรีมัน*. *ดอเวอร์ พับลิเคชันส*. ISBN 978-0-486-41740-0. [MR0466039](https://mathscinet.ams.org/mathscinet-getitem?mr=MR0466039).
* เฟเซนโก, ไอวาน (ค.ศ. 2010). *การวิเคราะห์บนสคีมเลขคณิต. II*. *วารสารทฤษฎีเค-ทฤษฎี* **5**(3), 437–557. doi:[10.1017/is010004028jkt103](https://doi.org/10.1017/is010004028jkt103).
* โฟร์ด, เควิน (ค.ศ. 2002). *อินทิกรัลของวินogradov และขอบเขตสำหรับฟังก์ชันซีตาของรีมัน*. *ประชุมวิชาการของสมาคมคณิตศาสตร์ลอนดอน* **85**(3), 565–633. [MR1936814](https://mathscinet.ams.org/mathscinet-getitem?mr=MR1936814). [arXiv:1910.08209](https://arxiv.org/abs/1910.08209). doi:[10.1112/S0024611502013655](https://doi.org/10.1112/S0024611502013655).
* คัทซ์, นิโคลัส เอ็ม.; ซาร์นาค, พี. (ค.ศ. 1999a). *ศูนย์ของฟังก์ชันซีตาและสมมาตร*. *วารสารสมาคมคณิตศาสตร์อเมริกัน* **36**, 1–26. doi:[10.1090/S0273-0979-99-00766-1](https://doi.org/10.1090/S0273-0979-99-00766-1)..
* คัทซ์, นิโคลัส เอ็ม.; ซาร์นาค, ปีเตอร์ (ค.ศ. 1999b). *เมทริกซ์สุ่ม, ค่าลักษณะเฉพาะของฟโรเบนียัส และโมโนดรอมี*. *สมาคมคณิตศาสตร์อเมริกัน* **45**.
* ฟรเนล, เจ.; แลนดอว์, อี. (ค.ศ. 1924). *Les suites de Farey et le problème des nombres premiers" (ฟรเนล, 198–201); "Bemerkungen zu der vorstehenden Abhandlung von Herrn Franel (แลนดอว์, 202–206)*. *ข่าวแห่งกอตติงเงิน*, 198–206.
* กอช, อามิต (ค.ศ. 1983). *เกี่ยวกับฟังก์ชันซีตาของรีมัน—ทฤษฎีบทค่าเฉลี่ยและการกระจายของ |S(T)|*. *วารสารทฤษฎีจำนวน* **17**, 93–102. doi:[10.1016/0022-314X(83)90010-0](https://doi.org/10.1016/0022-314X%2883%2990010-0).
ฟังก์ชันซีตาของรีมัน 10<sup>13</sup> ศูนย์แรก และการคำนวณศูนย์ที่ความสูงมาก*.[The 10<sup>13</sup> first zeros of the Riemann Zeta function, and zeros computation at very large height](http://numbers.computation.free.fr/Constants/Miscellaneous/zetazeros1e13-1e24.pdf).
* Gram, J. P. (1903). *Note sur les zéros de la fonction ζ(s) de Riemann*. *Acta Mathematica* **27**, 289–304. doi:[10.1007/BF02421310](https://doi.org/10.1007/BF02421310). [Note sur les zéros de la fonction *ζ*(*s*) de Riemann](https://zenodo.org/record/1930945).
พิมพ์ซ้ำใน Borwein, Peter; Ferguson, Ron; Mossinghoff, Michael J. (2008). *Sign changes in sums of the Liouville function*. *Mathematics of Computation* **77**(263), 1681–1694. [MR2398787](https://mathscinet.ams.org/mathscinet-getitem?mr=MR2398787). [2008MaCom..77.1681B](https://ui.adsabs.harvard.edu/abs/2008MaCom..77.1681B). doi:[10.1090/S0025-5718-08-02036-X](https://doi.org/10.1090/S0025-5718-08-02036-X)..
* Hanga, Catalin (2020). *Random matrix models for Gram's law*. *University of York*. [Random matrix models for Gram's law](https://etheses.whiterose.ac.uk/27858/).
* ฮาร์ดี, จี. เอช. (1914). *Sur les Zéros de la Fonction ζ(s) de Riemann*. *C. R. Acad. Sci. Paris* **158**, 1012–1014. [Sur les Zéros de la Fonction *ζ*(*s*) de Riemann](http://gallica.bnf.fr/ark:/12148/bpt6k3111d.image.f1014.langEN). พิมพ์ซ้ำใน Borwein, Peter; Ferguson, Ron; Mossinghoff, Michael J. (2008). *Sign changes in sums of the Liouville function*. *Mathematics of Computation* **77**(263), 1681–1694. [MR2398787](https://mathscinet.ams.org/mathscinet-getitem?mr=MR2398787). [2008MaCom..77.1681B](https://ui.adsabs.harvard.edu/abs/2008MaCom..77.1681B). doi:[10.1090/S0025-5718-08-02036-X](https://doi.org/10.1090/S0025-5718-08-02036-X)..
* ฮาร์ดี, จี. เอช.; ลิตเติลวูด, เจ. อี. (1921). *The zeros of Riemann's zeta-function on the critical line*. *Math. Z.* **10**(3–4), 283–317. doi:[10.1007/BF01211614](https://doi.org/10.1007/BF01211614). [The zeros of Riemann's zeta-function on the critical line](https://zenodo.org/record/1447415).
* เฮเซลโกรฟ, ซี. บี. (1958). *A disproof of a conjecture of Pólya*. *Mathematika* **5**(2), 141–145. [MR0104638](https://mathscinet.ams.org/mathscinet-getitem?mr=MR0104638). doi:[10.1112/S0025579300001480](https://doi.org/10.1112/S0025579300001480). พิมพ์ซ้ำใน Borwein, Peter; Ferguson, Ron; Mossinghoff, Michael J. (2008). *Sign changes in sums of the Liouville function*. *Mathematics of Computation* **77**(263), 1681–1694. [MR2398787](https://mathscinet.ams.org/mathscinet-getitem?mr=MR2398787). [2008MaCom..77.1681B](https://ui.adsabs.harvard.edu/abs/2008MaCom..77.1681B). doi:[10.1090/S0025-5718-08-02036-X](https://doi.org/10.1090/S0025-5718-08-02036-X)..
* Haselgrove, C. B.; Miller, J. C. P. (1960). *ฟังก์ชันซีตาของรีมัน*. *Cambridge University Press* **6**. [MR0117905](https://mathscinet.ams.org/mathscinet-getitem?mr=MR0117905).
* Hutchinson, J. I. (1925). *On the Roots of the Riemann Zeta-Function*. *Transactions of the American Mathematical Society* **27**(1), 49–60. [JSTOR 1989163](https://www.jstor.org/stable/1989163). doi:[10.2307/1989163](https://doi.org/10.2307/1989163).
* Ingham, A.E. (1932). *The Distribution of Prime Numbers*. *Cambridge University Press* **30**. Reprinted 1990, ISBN 978-0-521-39789-6, [MR 1074573](https://mathscinet.ams.org/mathscinet-getitem?mr=1074573)
* Ireland, Kenneth; Rosen, Michael (1990). *A Classical Introduction to Modern Number Theory (Second edition)*. *Springer*. ISBN 0-387-97329-X.
* Ivić, A. (1985). *The Riemann Zeta Function*. *John Wiley & Sons*. ISBN 978-0-471-80634-9. [MR0792089](https://mathscinet.ams.org/mathscinet-getitem?mr=MR0792089). (Reprinted by Dover 2003)
* Ivić, Aleksandar (2008). *The Riemann Hypothesis: A Resource for the Afficionado and Virtuoso Alike*. *Springer*, 131–160. ISBN 978-0-387-72125-5. [arXiv:math.NT/0311162](https://arxiv.org/abs/math.NT/0311162).
* Karatsuba, A. A. (1984a). *Zeros of the function ζ(s) on short intervals of the critical line*. *Izv. Akad. Nauk SSSR, Ser. Mat.* **48**(3), 569–584. [MR0747251](https://mathscinet.ams.org/mathscinet-getitem?mr=MR0747251).
*การกระจายของศูนย์ของฟังก์ชันซีตาของรีมัน ζ(1/2 + it)**. *Izv. Akad. Nauk SSSR, Ser. Mat.* **48**(6), 1214–1224. [MR0772113](https://mathscinet.ams.org/mathscinet-getitem?mr=MR0772113).
* Karatsuba, A. A. (1985). **ศูนย์ของฟังก์ชันซีตาของรีมันบนเส้นวิกฤต**. *Trudy Mat. Inst. Steklov.*, 167–178. [MR0804073](https://mathscinet.ams.org/mathscinet-getitem?mr=MR0804073).
* Karatsuba, A. A. (1992). **เกี่ยวกับจำนวนของศูนย์ของฟังก์ชันซีตาของรีมันที่อยู่ในช่วงสั้นเกือบทั้งหมดบนเส้นวิกฤต**. *Izv. Ross. Akad. Nauk, Ser. Mat.* **56**(2), 372–397. [MR1180378](https://mathscinet.ams.org/mathscinet-getitem?mr=MR1180378). [1993IzMat..40..353K](https://ui.adsabs.harvard.edu/abs/1993IzMat..40..353K). doi:[10.1070/IM1993v040n02ABEH002168](https://doi.org/10.1070/IM1993v040n02ABEH002168).
*ฟังก์ชันซีตาของรีมัน**. *Walter de Gruyter & Co.* **5**. ISBN 978-3-11-013170-3. [MR1183467](https://mathscinet.ams.org/mathscinet-getitem?mr=MR1183467). doi:[10.1515/9783110886146](https://doi.org/10.1515/9783110886146).
* Keating, Jonathan P.; Snaith, N. C. (2000a). **ทฤษฎีเมทริกซ์สุ่มและ ζ(1/2 + it)**. *Communications in Mathematical Physics* **214**(1), 57–89. [MR1794265](https://mathscinet.ams.org/mathscinet-getitem?mr=MR1794265). [2000CMaPh.214...57K](https://ui.adsabs.harvard.edu/abs/2000CMaPh.214...57K). doi:[10.1007/s002200000261](https://doi.org/10.1007/s002200000261).
* Keating, Jonathan P.; Snaith, N. C. (2000b). ทฤษฎีเมทริกซ์สุ่มและฟังก์ชันซีตาที่ $s = 1/2$. *Communications in Mathematical Physics* **214**(1), 91–100. [2000CMaPh.214...91K](https://ui.adsabs.harvard.edu/abs/2000CMaPh.214...91K). doi:[10.1007/s002200000262](https://doi.org/10.1007/s002200000262)..
เกี่ยวกับจุดเปลี่ยนเครื่องหมายของผลต่าง $\pi(x)-\operatorname{li} x$*. *Acta Arithmetica* **7**, 107–119. [MR133308](https://mathscinet.ams.org/mathscinet-getitem?mr=MR133308). doi:[10.4064/aa-7-2-107-119](https://doi.org/10.4064/aa-7-2-107-119).
ทฤษฎีจำนวน ระบบไดนามิก และกลศาสตร์เชิงสถิติ*. *Reviews in Mathematical Physics* **11**(8), 1027–1060. [MR1714352](https://mathscinet.ams.org/mathscinet-getitem?mr=MR1714352). [1999RvMaP..11.1027K](https://ui.adsabs.harvard.edu/abs/1999RvMaP..11.1027K). doi:[10.1142/S0129055X99000325](https://doi.org/10.1142/S0129055X99000325).
* von Koch, Niels Helge (1901). *Sur la distribution des nombres premiers*. *Acta Mathematica* **24**, 159–182. doi:[10.1007/BF02403071](https://doi.org/10.1007/BF02403071). [Sur la distribution des nombres premiers](https://zenodo.org/record/2347595).
* Kurokawa, Nobushige (1992). *ฟังก์ชันซีตาในเรขาคณิต (โตเกียว, 1990)*. *Kinokuniya* **21**, 219–226. [MR1210791](https://mathscinet.ams.org/mathscinet-getitem?mr=MR1210791).
ในการค้นหาจุดของรีมันน์*. *American Mathematical Society*. ISBN 978-0-8218-4222-5. [MR2375028](https://mathscinet.ams.org/mathscinet-getitem?mr=MR2375028). doi:[10.1090/mbk/051](https://doi.org/10.1090/mbk/051).
* [ฟังก์ชันซีตา](https://encyclopediaofmath.org/wiki/Z/z099260), *Encyclopedia of Mathematics*.
* เลห์เมอร์, ด. เอช. (1956). *การคำนวณขยายของฟังก์ชันซีตาของรีมัน*. *Mathematika* **3**(2), 102–108. [MR0086083](https://mathscinet.ams.org/mathscinet-getitem?mr=MR0086083). doi:[10.1112/S0025579300001753](https://doi.org/10.1112/S0025579300001753).
* เลอิกท์นาม, เอริก (2005). *เรขาคณิต ทฤษฎีสเปกตรัม กลุ่ม และพลวัต*. *Amer. Math. Soc.* **387**, 201–236. ISBN 978-0-8218-3710-8. [MR2180209](https://mathscinet.ams.org/mathscinet-getitem?mr=MR2180209). doi:[10.1090/conm/387/07243](https://doi.org/10.1090/conm/387/07243)..
* เลวินสัน, เอ็น. (1974). *มากกว่าหนึ่งในสามของจุดศูนย์ของฟังก์ชันซีตาของรีมันอยู่บน σ = 1/2*. *Advances in Mathematics* **13**(4), 383–436. [MR0564081](https://mathscinet.ams.org/mathscinet-getitem?mr=MR0564081). doi:[10.1016/0001-8708(74)90074-7](https://doi.org/10.1016/0001-8708%2874%2990074-7).
* ลิทเทิลวูด, เจ. อี. (1962). *นักวิทยาศาสตร์คาดเดา: รวบรวมแนวคิดที่ยังไม่สุกงอม*. *Basic books*.
* แวน เดอ ลูน, เจ.; เทอ รี้ล, เอช. จี. เจ.; วินเทอร์, ดี. ที. (1986). *เกี่ยวกับจุดศูนย์ของฟังก์ชันซีตาของรีมันในแถบวิกฤต. IV*. *Mathematics of Computation* **46**(174), 667–681. [MR829637](https://mathscinet.ams.org/mathscinet-getitem?mr=MR829637). [JSTOR 2008005](https://www.jstor.org/stable/2008005). doi:[10.2307/2008005](https://doi.org/10.2307/2008005).
* Massias, J.-P.; Nicolas, Jean-Louis; Robin, G. (1988). *Évaluation asymptotique de l'ordre maximum d'un élément du groupe symétrique*. *Acta Arithmetica* **50**(3), 221–242. [MR960551](https://mathscinet.ams.org/mathscinet-getitem?mr=MR960551). doi:[10.4064/aa-50-3-221-242](https://doi.org/10.4064/aa-50-3-221-242). [Évaluation asymptotique de l'ordre maximum d'un élément du groupe symétrique](http://matwbn.icm.edu.pl/tresc.php?wyd=6&tom=50&jez=).
*Mazur, Barry; Stein, William (2015). *Prime Numbers and the Riemann Hypothesis*. [Prime Numbers and the Riemann Hypothesis](http://wstein.org/rh/).
* Montgomery, Hugh L. (1973). *Analytic number theory*. *American Mathematical Society* **XXIV**, 181–193. [MR0337821](https://mathscinet.ams.org/mathscinet-getitem?mr=MR0337821). Reprinted in Borwein, Peter; Ferguson, Ron; Mossinghoff, Michael J. (2008). *Sign changes in sums of the Liouville function*. *Mathematics of Computation* **77**(263), 1681–1694. [MR2398787](https://mathscinet.ams.org/mathscinet-getitem?mr=MR2398787). [2008MaCom..77.1681B](https://ui.adsabs.harvard.edu/abs/2008MaCom..77.1681B). doi:[10.1090/S0025-5718-08-02036-X](https://doi.org/10.1090/S0025-5718-08-02036-X)..
* Montgomery, Hugh L. (1983). *Studies in pure mathematics. To the memory of Paul Turán*. *Birkhäuser*, 497–506. ISBN 978-3-7643-1288-6. [MR820245](https://mathscinet.ams.org/mathscinet-getitem?mr=MR820245).
การแปลงฟูรีเยในทฤษฎีจำนวน I. ทฤษฎีดั้งเดิม*. *มหาวิทยาลัยเคมบริดจ์* **97**. ISBN 978-0-521-84903-6
* Newman, C. M. (1976). *การแปลงฟูรีเยที่มีศูนย์เป็นจำนวนจริงเท่านั้น*. *ประชุมวิชาการของสมาคมคณิตศาสตร์อเมริกัน* **61**(2), 246–251. doi:[10.1090/S0002-9939-1976-0434982-5](https://doi.org/10.1090/S0002-9939-1976-0434982-5).,
ช่องว่างจำนวนเฉพาะสูงสุดใหม่และการปรากฏครั้งแรก*. *คณิตศาสตร์ของการคำนวณ* **68**(227), 1311–1315. [MR1627813](https://mathscinet.ams.org/mathscinet-getitem?mr=MR1627813). [1999MaCom..68.1311N](https://ui.adsabs.harvard.edu/abs/1999MaCom..68.1311N). doi:[10.1090/S0025-5718-99-01065-0](https://doi.org/10.1090/S0025-5718-99-01065-0). [New maximal prime gaps and first occurrences](http://www.trnicely.net/gaps/gaps.html)..
เกี่ยวกับกลุ่มและการกึ่งกลุ่มแบบแปลนในหนึ่งมิติในช่องว่างฟังก์ชันบางประเภท*. *มหาวิทยาลัยอุพพาลา*. [MR0036444](https://mathscinet.ams.org/mathscinet-getitem?mr=MR0036444).
* Odlyzko, A. M.; te Riele, H. J. J. (1985). *การพิสูจน์ข้อความคาดการณ์ของเมอร์เท็นส์*. *วารสารสำหรับคณิตศาสตร์บริสุทธิ์และประยุกต์* **1985**(357), 138–160. [MR783538](https://mathscinet.ams.org/mathscinet-getitem?mr=MR783538). doi:[10.1515/crll.1985.357.138](https://doi.org/10.1515/crll.1985.357.138). [Disproof of the Mertens conjecture](https://archive.today/20120711011237/http://gdz.sub.uni-goettingen.de/no_cache/dms/load/img/?IDDOC=262633).
* Odlyzko, A. M. (1987). *On the distribution of spacings between zeros of the zeta function*. *Mathematics of Computation* **48**(177), 273–308. [MR866115](https://mathscinet.ams.org/mathscinet-getitem?mr=MR866115). [JSTOR 2007890](https://www.jstor.org/stable/2007890). doi:[10.2307/2007890](https://doi.org/10.2307/2007890).
* Odlyzko, A. M. (1990). *Bounds for discriminants and related estimates for class numbers, regulators and zeros of zeta functions: a survey of recent results*. *Séminaire de Théorie des Nombres de Bordeaux* **2**(1), 119–141. [MR1061762](https://mathscinet.ams.org/mathscinet-getitem?mr=MR1061762). doi:[10.5802/jtnb.22](https://doi.org/10.5802/jtnb.22). [Bounds for discriminants and related estimates for class numbers, regulators and zeros of zeta functions: a survey of recent results](http://www.numdam.org/item?id=JTNB_1990__2_1_119_0).
หนังสือเล่มนี้ที่ยังไม่ได้ตีพิมพ์อธิบายการนำไปใช้ของอัลกอริทึมและอภิปรายผลลัพธ์โดยละเอียด
* Odlyzko, A. M. (1998). *The 10<sup>21</sup>st zero of the Riemann zeta function*. [The 10<sup>21</sup>st zero of the Riemann zeta function](http://www.dtc.umn.edu/~odlyzko/unpublished/zeta.10to21.pdf).
* โอนโอะ, เคน; ซาวนดาระอาจาน, เค. (ค.ศ. 1997). *รูปแบบกำลังสองแบบสามของรามานุจัน*. *Inventiones Mathematicae* **130**(3), 415–454. [1997InMat.130..415O](https://ui.adsabs.harvard.edu/abs/1997InMat.130..415O). doi:[10.1007/s002220050191](https://doi.org/10.1007/s002220050191).
* แพทเทอร์สัน, เอส. เจ. (ค.ศ. 1988). *บทนำสู่ทฤษฎีของฟังก์ชันซีตาของรีมัน*. *สำนักพิมพ์มหาวิทยาลัยเคมบริดจ์* **14**. ISBN 978-0-521-33535-5. [MR933558](https://mathscinet.ams.org/mathscinet-getitem?mr=MR933558). doi:[10.1017/CBO9780511623707](https://doi.org/10.1017/CBO9780511623707).
* พลาตต์, เดฟ; ทรุดจิกอัน, ทิโมธี (มกราคม ค.ศ. 2021). *สมมติฐานของรีมันเป็นจริงจนถึง 3·10<sup>12</sup>*. *วารสารสมาคมคณิตศาสตร์ลอนดอน* **53**(3), 792–797. [arXiv:2004.09765](https://arxiv.org/abs/2004.09765). doi:[10.1112/blms.12460](https://doi.org/10.1112/blms.12460).
* ราดเจเยฟสกี, มาซีเย (ค.ศ. 2007). *ความเป็นอิสระของฟังก์ชันซีตาของเฮคเกอที่มีลำดับจำกัดเหนือฟิลด์ปกติ*. *วารสารสมาคมคณิตศาสตร์อเมริกัน* **359**(5), 2383–2394. [MR2276625](https://mathscinet.ams.org/mathscinet-getitem?mr=MR2276625). doi:[10.1090/S0002-9947-06-04078-5](https://doi.org/10.1090/S0002-9947-06-04078-5).
* รีเบนบอยม์, พอลู (ค.ศ. 1996). *หนังสือบันทึกจำนวนเฉพาะเล่มใหม่*. *สปริงเกอร์*. ISBN 0-387-94457-5.
* รีมันน์, เบิร์นฮาร์ด (ค.ศ. 1859). *Ueber die Anzahl der Primzahlen unter einer gegebenen Grösse*. *Monatsberichte der Berliner Akademie*. [Ueber die Anzahl der Primzahlen unter einer gegebenen Grösse](http://www.maths.tcd.ie/pub/HistMath/People/Riemann/Zeta/).. ใน *Gesammelte Werke*, เทออบเนอร์, เลอปซิก (ค.ศ. 1892), พิมพ์ซ้ำโดย ดอเวอร์, นิวยอร์ก (ค.ศ. 1953). [ต้นฉบับเอกสาร](http://www.claymath.org/publications/riemanns-1859-manuscript/) (พร้อมการแปลเป็นภาษาอังกฤษ). พิมพ์ซ้ำใน รีเบนบอยม์, พอลู; เฟรเจอ, รอน; มอสซิงฮอฟฟ์, ไมเคิล เจ. (ค.ศ. 2008). *การเปลี่ยนเครื่องหมายในผลรวมของฟังก์ชันลิอูวิลล์*. *คณิตศาสตร์ของการคำนวณ* **77**(263), 1681–1694. [MR2398787](https://mathscinet.ams.org/mathscinet-getitem?mr=MR2398787). [2008MaCom..77.1681B](https://ui.adsabs.harvard.edu/abs/2008MaCom..77.1681B). doi:[10.1090/S0025-5718-08-02036-X](https://doi.org/10.1090/S0025-5718-08-02036-X). และ เอ็ดเวิร์ดส์, เอช. เอ็ม. (ค.ศ. 1974). *ฟังก์ชันซีตาของรีมัน*. *สำนักพิมพ์ดอเวอร์*. ISBN 978-0-486-41740-0. [MR0466039](https://mathscinet.ams.org/mathscinet-getitem?mr=MR0466039).
* Riesel, Hans; Göhl, Gunnar (1970). *การคำนวณบางประการที่เกี่ยวข้องกับสูตรจำนวนเฉพาะของรีมันน์*. *Mathematics of Computation* **24**(112), 969–983. [MR0277489](https://mathscinet.ams.org/mathscinet-getitem?mr=MR0277489). [JSTOR 2004630](https://www.jstor.org/stable/2004630). doi:[10.2307/2004630](https://doi.org/10.2307/2004630). [การคำนวณบางประการที่เกี่ยวข้องกับสูตรจำนวนเฉพาะของรีมันน์](https://www.ams.org/journals/mcom/1970-24-112/S0025-5718-1970-0277489-3/S0025-5718-1970-0277489-3.pdf).
* Riesz, M. (1916). *Sur l'hypothèse de Riemann*. *Acta Mathematica* **40**, 185–190. doi:[10.1007/BF02418544](https://doi.org/10.1007/BF02418544).
* Robin, G. (1984). *Grandes valeurs de la fonction somme des diviseurs et hypothèse de Riemann*. *Journal de Mathématiques Pures et Appliquées* **63**(2), 187–213. [MR774171](https://mathscinet.ams.org/mathscinet-getitem?mr=MR774171).
ดูเพิ่มเติม [ประกาศบนบล็อกของเทอเรนซ์](https://terrytao.wordpress.com/2018/01/19/the-de-bruijn-newman-constant-is-non-negativ/), 19 มกราคม 2018
* Rosser, J. Barkley; Yohe, J. M.; Schoenfeld, Lowell (1969). *Information Processing 68 (Proc. IFIP Congress, Edinburgh, 1968), Vol. 1: Mathematics, Software*. *North-Holland*, 70–76. [MR0258245](https://mathscinet.ams.org/mathscinet-getitem?mr=MR0258245).
* วอลเทอร์ รูดิน (มกราคม 1973). *Functional Analysis*. *McGraw-Hill*. ISBN 0-070-54225-2.
* ราฟาเอล ซาล์ม (1953). *Sur une proposition équivalente à l'hypothèse de Riemann*. *Les Comptes rendus de l'Académie des sciences* **236**, 1127–1128. [MR0053148](https://mathscinet.ams.org/mathscinet-getitem?mr=MR0053148).
* ปีเตอร์ ซาร์แนก (2005). *Problems of the Millennium: The Riemann Hypothesis (2004)*. *Clay Mathematics Institute*. [Problems of the Millennium: The Riemann Hypothesis (2004)](http://www.claymath.org/sites/default/files/sarnak_rh_0.pdf). พิมพ์ซ้ำใน Borwein, Peter; Ferguson, Ron; Mossinghoff, Michael J. (2008). *Sign changes in sums of the Liouville function*. *Mathematics of Computation* **77**(263), 1681–1694. [MR2398787](https://mathscinet.ams.org/mathscinet-getitem?mr=MR2398787). [2008MaCom..77.1681B](https://ui.adsabs.harvard.edu/abs/2008MaCom..77.1681B). doi:[10.1090/S0025-5718-08-02036-X](https://doi.org/10.1090/S0025-5718-08-02036-X)..
* โลเวลล์ โชห์นเฟลด์ (1976). *Sharper bounds for the Chebyshev functions θ(x) and ψ(x). II*. *Mathematics of Computation* **30**(134), 337–360. [MR0457374](https://mathscinet.ams.org/mathscinet-getitem?mr=MR0457374). [JSTOR 2005976](https://www.jstor.org/stable/2005976). doi:[10.2307/2005976](https://doi.org/10.2307/2005976).
* ดันเนล ชูมาเยอร์; เดวิด เอ. ว. ฮัทชินสัน (2011). *Physics of the Riemann Hypothesis*. *Reviews of Modern Physics* **83**(2), 307–330. [arXiv:1101.3116](https://arxiv.org/abs/1101.3116). [2011RvMP...83..307S](https://ui.adsabs.harvard.edu/abs/2011RvMP...83..307S). doi:[10.1103/RevModPhys.83.307](https://doi.org/10.1103/RevModPhys.83.307).
หน้า. [MR0010712](https://mathscinet.ams.org/mathscinet-getitem?mr=MR0010712).
* Selberg, Atle (1946). *Contributions to the theory of the Riemann zeta-function*. *Arch. Math. Naturvid.* **48**(5), 89–155. [MR0020594](https://mathscinet.ams.org/mathscinet-getitem?mr=MR0020594).
* Selberg, Atle (1956). *Harmonic analysis and discontinuous groups in weakly symmetric Riemannian spaces with applications to Dirichlet series*. *J. Indian Math. Soc.* **20**, 47–87. [MR0088511](https://mathscinet.ams.org/mathscinet-getitem?mr=MR0088511).
* Serre, Jean-Pierre (1969–1970). *Facteurs locaux des fonctions zeta des varietés algébriques (définitions et conjectures)*. *Séminaire Delange-Pisot-Poitou* **19**. [Facteurs locaux des fonctions zeta des varietés algébriques (définitions et conjectures)](https://eudml.org/doc/110758).
* Sheats, Jeffrey T. (1998). *The Riemann hypothesis for the Goss zeta function for F<sub>q</sub>[T]*. *Journal of Number Theory* **71**(1), 121–157. [MR1630979](https://mathscinet.ams.org/mathscinet-getitem?mr=MR1630979). [arXiv:math/9801158](https://arxiv.org/abs/math/9801158). doi:[10.1006/jnth.1998.2232](https://doi.org/10.1006/jnth.1998.2232).
พิมพ์ซ้ำใน Gesammelte Abhandlungen, Vol. 1. Berlin: Springer-Verlag, 1966. มีฉบับแปลได้ที่ Carl, Siegel (11 ตุลาคม 2018). *On Riemanns Nachlass for Analytic Number Theory*. [arXiv:1810.05198](https://arxiv.org/abs/1810.05198).
* Speiser, Andreas (1934). *ฟังก์ชันซีตาของรีมันในเชิงเรขาคณิต*. *Mathematische Annalen* **110**, 514–521. doi:[10.1007/BF01448042](https://doi.org/10.1007/BF01448042). [ฟังก์ชันซีตาของรีมันในเชิงเรขาคณิต](https://web.archive.org/web/20150627115412/http://gdz.sub.uni-goettingen.de/index.php?id=11&PPN=PPN235181684_0110&DMDID=DMDLOG_0032&L=1).
จุดศูนย์ของส่วนย่อยของฟังก์ชันซีตา. II*. *Mathematics of Computation* **22**(101), 163–173. [MR0228456](https://mathscinet.ams.org/mathscinet-getitem?mr=MR0228456). [JSTOR 2004774](https://www.jstor.org/stable/2004774). doi:[10.2307/2004774](https://doi.org/10.2307/2004774).
* Stein, William; Mazur, Barry (2007). *สมมติฐานของรีมันคืออะไร?*. [สมมติฐานของรีมันคืออะไร?](https://web.archive.org/web/20090327181331/http://modular.math.washington.edu/edu/2007/simuw07/notes/rh.pdf).
ความบวกของฟังก์ชันบางตัวที่เกี่ยวข้องกับการวิเคราะห์บนพื้นผิววงรี*. *Journal of Number Theory* **131**(10), 1770–1796. doi:[10.1016/j.jnt.2011.03.007](https://doi.org/10.1016/j.jnt.2011.03.007).
* Titchmarsh, Edward Charles (1935). *จุดศูนย์ของฟังก์ชันซีตาของรีมัน*. *Proceedings of the Royal Society of London. Series A, Mathematical and Physical Sciences* **151**(873), 234–255. [JSTOR 96545](https://www.jstor.org/stable/96545). [1935RSPSA.151..234T](https://ui.adsabs.harvard.edu/abs/1935RSPSA.151..234T). doi:[10.1098/rspa.1935.0146](https://doi.org/10.1098/rspa.1935.0146).
* Titchmarsh, Edward Charles (1936). *ฟังก์ชันซีตาของรีมัน*. *Proceedings of the Royal Society of London. Series A, Mathematical and Physical Sciences* **157**(891), 261–263. [arXiv:1004.4143](https://arxiv.org/abs/1004.4143). [JSTOR 96692](https://www.jstor.org/stable/96692). [1936RSPSA.157..261T](https://ui.adsabs.harvard.edu/abs/1936RSPSA.157..261T). doi:[10.1098/rspa.1936.0192](https://doi.org/10.1098/rspa.1936.0192).
* Titchmarsh, Edward Charles (1986). *ทฤษฎีของฟังก์ชันซีตาของรีมัน*. *The Clarendon Press Oxford University Press*. ISBN 978-0-19-853369-6. [MR882550](https://mathscinet.ams.org/mathscinet-getitem?mr=MR882550).
* Trudgian, Timothy S. (2014). *ขอบเขตบนที่ปรับปรุงแล้วสำหรับอาร์กิวเมนต์ของฟังก์ชันซีตาของรีมันบนเส้นวิกฤต II*. *J. Number Theory* **134**, 280–292. [arXiv:1208.5846](https://arxiv.org/abs/1208.5846). doi:[10.1016/j.jnt.2013.07.017](https://doi.org/10.1016/j.jnt.2013.07.017).
* Trudgian, Timothy (2011). *เกี่ยวกับความสำเร็จและความล้มเหลวของกฎของแกรมและกฎของโรสเซอร์*. *Acta Arithmetica* **125**(3), 225–256. doi:[10.4064/aa148-3-2](https://doi.org/10.4064/aa148-3-2).
เกี่ยวกับพหุนามไดริชเลต์โดยประมาณบางตัวในทฤษฎีของฟังก์ชันซีตาของรีมัน*. *Danske Vid. Selsk. Mat.-Fys. Medd.* **24**(17), 36. [MR0027305](https://mathscinet.ams.org/mathscinet-getitem?mr=MR0027305). พิมพ์ซ้ำใน Borwein, Peter; Ferguson, Ron; Mossinghoff, Michael J. (2008). *การเปลี่ยนเครื่องหมายในผลรวมของฟังก์ชันลิอูวิลล์*. *Mathematics of Computation* **77**(263), 1681–1694. [MR2398787](https://mathscinet.ams.org/mathscinet-getitem?mr=MR2398787). [2008MaCom..77.1681B](https://ui.adsabs.harvard.edu/abs/2008MaCom..77.1681B). doi:[10.1090/S0025-5718-08-02036-X](https://doi.org/10.1090/S0025-5718-08-02036-X).
* ทัวริง, แอลัน เอ็ม. (1953). *Some calculations of the Riemann zeta-function*. *Proceedings of the London Mathematical Society* **3**, 99–117. [MR0055785](https://mathscinet.ams.org/mathscinet-getitem?mr=MR0055785). doi:[10.1112/plms/s3-3.1.99](https://doi.org/10.1112/plms/s3-3.1.99).
* เดอ ลา วาลเล-ปูสซัน, ช.เจ. (1896). *Recherches analytiques sur la théorie des nombres premiers*. *Ann. Soc. Sci. Bruxelles* **20**, 183–256.
* เดอ ลา วาลเล-ปูสซัน, ช.เจ. (1899–1900). *Sur la fonction ζ(s) de Riemann et la nombre des nombres premiers inférieurs à une limite donnée*. *Mem. Couronnes Acad. Sci. Belg.* **59**(1). พิมพ์ซ้ำใน โบรว์น, ปีเตอร์; เฟรเจอรอน, รอน; มอสซิงโฮฟ, ไมเคิล เจ. (2008). *Sign changes in sums of the Liouville function*. *Mathematics of Computation* **77**(263), 1681–1694. [MR2398787](https://mathscinet.ams.org/mathscinet-getitem?mr=MR2398787). [2008MaCom..77.1681B](https://ui.adsabs.harvard.edu/abs/2008MaCom..77.1681B). doi:[10.1090/S0025-5718-08-02036-X](https://doi.org/10.1090/S0025-5718-08-02036-X)..
* เวย์, แอนเดร (1948). *Sur les courbes algébriques et les variétés qui s'en déduisent*. *Hermann et Cie., Paris*. [MR0027151](https://mathscinet.ams.org/mathscinet-getitem?mr=MR0027151).
* เวย์, แอนเดร (1949). *Numbers of solutions of equations in finite fields*. *Bulletin of the American Mathematical Society* **55**(5), 497–508. [MR0029393](https://mathscinet.ams.org/mathscinet-getitem?mr=MR0029393). doi:[10.1090/S0002-9904-1949-09219-4](https://doi.org/10.1090/S0002-9904-1949-09219-4). พิมพ์ซ้ำใน Oeuvres Scientifiques/Collected Papers by Andre Weil ISBN 0-387-90330-5
* Weinberger, Peter J. (1973). ทฤษฎีจำนวนเชิงวิเคราะห์ ( St. Louis Univ., 1972). Amer. Math. Soc. **24**, 321–332. [MR0337902](https://mathscinet.ams.org/mathscinet-getitem?mr=MR0337902).
* Wiles, Andrew (2000). คณิตศาสตร์: ขอบเขตและมุมมอง. American Mathematical Society, 329–342. ISBN 978-0-8218-2697-3. [MR1754786](https://mathscinet.ams.org/mathscinet-getitem?mr=MR1754786).
* Zagier, Don (1977). จำนวนเฉพาะ 50 ล้านตัวแรก. Math. Intelligencer **1**, 7–19. [MR643810](https://mathscinet.ams.org/mathscinet-getitem?mr=MR643810). doi:[10.1007/BF03039306](https://doi.org/10.1007/BF03039306). [จำนวนเฉพาะ 50 ล้านตัวแรก](https://web.archive.org/web/20090327181245/http://modular.math.washington.edu/edu/2007/simuw07/misc/zagier-the_first_50_million_prime_numbers.pdf).
* Zagier, Don (1981). รูปแบบออโตมอร์ฟิก ทฤษฎีการแทนค่า และเลขคณิต (Bombay, 1979). Tata Inst. Fundamental Res., Bombay **10**, 275–301. [MR633666](https://mathscinet.ams.org/mathscinet-getitem?mr=MR633666).

### นิทรรศการยอดนิยม

* ซาบบาห์, คาร์ล (ค.ศ. 2003a). *ปัญหาที่ยังไม่ได้รับการแก้ไขที่ยิ่งใหญ่ที่สุดในคณิตศาสตร์*. *ฟาร์ราร์, สตรอส และ จิรูซ์, นิวยอร์ก*. ISBN 978-0-374-25007-2. [MR1979664](https://mathscinet.ams.org/mathscinet-getitem?mr=MR1979664). [ปัญหาที่ยังไม่ได้รับการแก้ไขที่ยิ่งใหญ่ที่สุดในคณิตศาสตร์](https://archive.org/details/riemannhypothesi00sabb).
* ซาบบาห์, คาร์ล (ค.ศ. 2003b). *ศูนย์ของรีมัน*. *แอตแลนติก บุคส์, ลอนดอน*. ISBN 978-1-843-54101-1. [ศูนย์ของรีมัน](https://books.google.com/books?id=JesSAQAAMAAJ).
* ดู ซอโตย, มาร์คัส (ค.ศ. 2003). *ดนตรีของจำนวนเฉพาะ*. *ฮาร์เปอร์คอลลินส์ พับลิชเชอร์ส*. ISBN 978-0-06-621070-4. [MR2060134](https://mathscinet.ams.org/mathscinet-getitem?mr=MR2060134). [ดนตรีของจำนวนเฉพาะ](https://archive.org/details/musicofprimessea00dusa).
* ร็อกมอร์, ดัน (ค.ศ. 2005). *ล่าสมมติฐานของรีมัน*. *แพนธีออน บุคส์*. ISBN 978-0-375-42136-5. [MR2269393](https://mathscinet.ams.org/mathscinet-getitem?mr=MR2269393). [ล่าสมมติฐานของรีมัน](https://archive.org/details/stalkingriemannh00danr).
* เดอร์บีเชอร์, จอห์น (ค.ศ. 2003). *Prime Obsession*. *โจเซฟ เฮนรี พρες, วอชิงตัน, ดี.ซี*. ISBN 978-0-309-08549-6. [MR1968857](https://mathscinet.ams.org/mathscinet-getitem?mr=MR1968857).
* วอทกิ้นส์, แมทธิว (ค.ศ. 2015). *Mystery of the Prime Numbers*. *ไลเบอร์ลิส บุคส์*. ISBN 978-1782797814. [MR0000000](https://mathscinet.ams.org/mathscinet-getitem?mr=MR0000000).
* [เฟรนเคิล, เอ็ดเวิร์ด](https://en.wikipedia.org/wiki/Edward_Frenkel) (ค.ศ. 2014), [สมมติฐานของรีมัน](https://www.youtube.com/watch?v=d6c6uIyieoo) [Numberphile](https://en.wikipedia.org/wiki/Numberphile), 11 มี.ค. 2014 (วิดีโอ)
* Nahin, Paul J. (2021). *In Pursuit of Zeta-3: The World's Most Mysterious Unsolved Math Problem*. *Princeton University Press*. ISBN 978-0691206073.

หมายเหตุ: Derbyshire 2003, Rockmore 2005, Sabbagh 2003a, Sabbagh 2003b, Sautoy 2003, และ Watkins 2015 เป็นแบบที่ไม่ใช่ทางเทคนิค Edwards 1974, Patterson 1988, Borwein/Choi/Rooney/Weirathmueller 2008, Mazur/Stein 2015, Broughan 2017, และ Nahin 2021 ให้การแนะนำทางคณิตศาสตร์ Titchmarsh 1986, Ivić 1985, และ Karatsuba/Voronin 1992 เป็นแบบ [monograph](https://en.wikipedia.org/wiki/monograph) ขั้นสูง

## แหล่งข้อมูลภายนอก

*

* [สถาบันคณิตศาสตร์อเมริกัน](https://en.wikipedia.org/wiki/American_Institute_of_Mathematics), [สมมติฐานของรีมัน](http://www.aimath.org/WWN/rh/)
* [ฐานข้อมูลศูนย์](https://www.lmfdb.org/zeros/zeta/), 103 800 788 359 ศูนย์
* Apostol, Tom. *ศูนย์ของซีตาของ s อยู่ที่ไหน?*. [ศูนย์ของซีตาของ s อยู่ที่ไหน?](http://www.math.wisc.edu/~robbin/funnysongs.html#Zeta). บทกวีเกี่ยวกับสมมติฐานของรีมัน, [ร้อง](http://www.olimu.com/RIEMANN/Song.htm) โดย [จอห์น เดอร์ไบร์](https://en.wikipedia.org/wiki/John_Derbyshire).
* Borwein, Peter. *สมมติฐานของรีมัน*. [สมมติฐานของรีมัน](https://web.archive.org/web/20090327181245/http://oldweb.cecm.sfu.ca/~pborwein/COURSE/MATH08/LECTURE.pdf). (สไลด์สำหรับบรรยาย)
* Conrad, K. (2010). *ผลที่ตามมาจากสมมติฐานของรีมัน*. [ผลที่ตามมาจากสมมติฐานของรีมัน](https://mathoverflow.net/q/17232).
* Conrey, J. Brian; Farmer, David W. *ความเทียบเท่าของสมมติฐานของรีมัน*. [ความเทียบเท่าของสมมติฐานของรีมัน](https://web.archive.org/web/20100316235054/http://aimath.org/pl/rhequivalences).
การคำนวณศูนย์ของฟังก์ชันซีตา*. [การคำนวณศูนย์ของฟังก์ชันซีตา](http://numbers.computation.free.fr/Constants/Miscellaneous/zetazeroscompute.html). (ทบทวนสมมติฐาน GUE, ให้บรรณานุกรมอย่างกว้างขวางด้วย)
* Odlyzko, Andrew. *หน้าแรก*. [หน้าแรก](http://www.dtc.umn.edu/~odlyzko/). รวมถึง [บทความเกี่ยวกับศูนย์ของฟังก์ชันซีตา](http://www.dtc.umn.edu/~odlyzko/doc/zeta.html) และ [ตารางศูนย์ของฟังก์ชันซีตา](http://www.dtc.umn.edu/~odlyzko/zeta_tables/index.html)
* โอดลีดโก, แอนดรูว์ (2002). *ฟังก์ชันซีตาของรีมัน: ข้อความคาดการณ์และการคำนวณ*. [Zeros of the Riemann zeta function: Conjectures and computations](http://www.dtc.umn.edu/~odlyzko/talks/riemann-conjectures.pdf). สไลด์ของการบรรยาย
* เพ็ก, เอ็ด (2004). *ทริลเลียนของซีตา*. *Math Games website*. [Ten Trillion Zeta Zeros](https://web.archive.org/web/20041102173644/http://www.maa.org/editorial/mathgames/mathgames_10_18_04.html).. การอภิปรายเกี่ยวกับการคำนวณของกาวร์ดอน กซาเวียร์ ของจำนวนซีตาที่ไม่สำคัญสิบทริลเลียนตัวแรก
* รูบินสไตน์, ไมเคิล. *อัลกอริทึมสำหรับการสร้างซีตา*. [algorithm for generating the zeros](https://web.archive.org/web/20070427221654/http://pmmac03.math.uwaterloo.ca/~mrubinst/l_function_public/L.html)..
* ดู ซอโตย, มาร์คัส (2006). *จำนวนเฉพาะได้แต่งงานกัน*. *Seed Magazine*. [Prime Numbers Get Hitched](https://web.archive.org/web/20170922145127/http://seedmagazine.com/content/article/prime_numbers_get_hitched/).
* วอเทกส์, แมทธิว อาร์. (2021-02-27). *ข้อพิสูจน์ (หรือการหักล้าง) ที่เสนอของสมมติฐานของรีมัน*. [Proposed (dis)proofs of the Riemann Hypothesis](https://empslocal.ex.ac.uk/people/staff/mrwatkin//zeta/RHproofs.htm).
โครงการคอมพิวเตอร์แบบกระจายที่พยายามหักล้างสมมติฐานของรีมัน; ปิดตัวลงในเดือนพฤศจิกายน 2005
