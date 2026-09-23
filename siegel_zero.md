---
title: ศูนย์ของซีเกิล
---

ใน [คณิตศาสตร์](https://en.wikipedia.org/wiki/mathematics) โดยเฉพาะในสาขา [ทฤษฎีจำนวนเชิงวิเคราะห์](https://en.wikipedia.org/wiki/analytic_number_theory) **Landau–Siegel zero** หรืออย่างง่ายคือ **Siegel zero** ซึ่งรู้จักกันในชื่อ **exceptional zero**[^1] ตั้งชื่อตาม [เอ็ทมุนท์ ลันเดา](https://en.wikipedia.org/wiki/Edmund_Landau) และ [Carl Ludwig Siegel](https://en.wikipedia.org/wiki/Carl_Ludwig_Siegel) เป็นประเภทของ [counterexample](https://en.wikipedia.org/wiki/counterexample) ที่เป็นไปได้ต่อ [generalized Riemann hypothesis](https://en.wikipedia.org/wiki/generalized_Riemann_hypothesis) เกี่ยวกับศูนย์ของ [Dirichlet L-function](https://en.wikipedia.org/wiki/Dirichlet_L-function)s ที่สัมพันธ์กับ [quadratic number field](https://en.wikipedia.org/wiki/quadratic_number_field)s โดยพูดอย่างกว้างๆ นี่คือศูนย์ที่เป็นไปได้ที่อยู่ใกล้ (ในแง่ที่วัดปริมาณได้) กับ $s=1$

## แรงจูงใจและการนิยาม

วิธีการที่ซีเกิลซีโรปรากฏในทฤษฎีฟังก์ชัน L ของดิริชเลต คือเป็นข้อยกเว้นที่เป็นไปได้ต่อ [บริเวณที่ไม่มีซีโรแบบดั้งเดิม](https://en.wikipedia.org/wiki/Dirichlet_L-function#Zeros) ซึ่งสามารถเกิดขึ้นได้ก็ต่อเมื่อฟังก์ชัน L นั้นสัมพันธ์กับ [อักขระของดิริชเลต](https://en.wikipedia.org/wiki/Dirichlet_character) เท่านั้น

### ตัวอักษร Dirichlet แบบดั้งเดิม

สำหรับจำนวนเต็ม $q ≥ 1$ **ฟังก์ชัน Dirichlet** modulo $q$ คือ [ฟังก์ชันเลขคณิต](https://en.wikipedia.org/wiki/arithmetic_function) $\chi\colon \mathbb{Z}\to\mathbb{C}$ ที่สอดคล้องกับคุณสมบัติดังต่อไปนี้:
* [คูณสมบูรณ์](https://en.wikipedia.org/wiki/Completely_multiplicative): $\chi(mn) = \chi(m)\chi(n)$ สำหรับทุก $m$, $n$;
* [เป็นคาบ](https://en.wikipedia.org/wiki/Periodic_function): $\chi(n+q) = \chi(n)$ สำหรับทุก $n$;
* พื้นที่รองรับ: $\chi(n) = 0$ [ก็ต่อเมื่อ](https://en.wikipedia.org/wiki/if_and_only_if) $\mathrm{gcd}(n,q) > 1$.
นั่นคือ $χ$ คือการยกระดับของ [โฮโมมอร์ฟิซึม](https://en.wikipedia.org/wiki/homomorphism) $\widetilde{\chi}:(\mathbb{Z}/q\mathbb{Z})^{\times} \to \mathbb{C}^{*}$.

**ตัวอักขระธรรมดา** (trivial character) คือตัวอักขระมอดุโล 1 และ **ตัวอักขระหลัก** (principal character) มอดุโล $q$ ซึ่งเขียนแทนด้วย $\chi_0~(\mathrm{mod}~q)$ คือการขยายของโฮโมมอร์ฟิซึมธรรมดา $(\mathbb{Z}/q\mathbb{Z})^{\times}\ni a \mapsto 1 \in \mathbb{C}^{*}$

อักขระ $\chi~(\mathrm{mod}~{q})$ เรียกว่า **imprimitive** ถ้ามีจำนวนเต็ม $d\neq q$ ซึ่ง $d\mid q$ ที่ทำให้โฮโมมอร์ฟิซึมที่เหนี่ยวนำ $\widetilde{\chi}\colon (\mathbb{Z}/q\mathbb{Z})^{\times} \to \mathbb{C}^{*}$ แยกตัวเป็น
ไม่มีเนื้อหาให้แปล เนื่องจากข้อความที่ส่งมาเป็นเครื่องหมายโคลน (: ) เท่านั้น

$$
(\mathbb{Z}/q\mathbb{Z})^{\times}\twoheadrightarrow (\mathbb{Z}/d\mathbb{Z})^{\times} \xrightarrow{\widetilde{\chi'}} \mathbb{C}^{*}
$$

สำหรับอักขระ $\chi'~(\mathrm{mod}~{d})$ ใด ๆ; ในกรณีอื่น ๆ $\chi~(\mathrm{mod}~{q})$ จะเรียกว่า **primitive**

อักขระ $\chi$ เป็น **real** (หรือ **quadratic**) หากมันเท่ากับ [สังยุค](https://en.wikipedia.org/wiki/complex_conjugate) ของมัน $\overline{\chi}$ (นิยามว่า $\overline{\chi}(n) := \overline{\chi(n)}$) หรือเทียบเท่าหาก $\chi^2 = \chi_0$ อักขระ Dirichlet แบบจริงที่เป็นพื้นฐาน (*real primitive Dirichlet characters*) มีการจับคู่แบบหนึ่งต่อหนึ่งกับสัญลักษณ์ [Kronecker](https://en.wikipedia.org/wiki/Kronecker_symbol) $(D|\,\cdot\,): \mathbb{Z} \to \{-1,0,1\}$ สำหรับ $D\in\mathbb{Z}$ ที่เป็น [fundamental discriminant](https://en.wikipedia.org/wiki/fundamental_discriminant) (กล่าวคือ discriminant ของ [quadratic number field](https://en.wikipedia.org/wiki/quadratic_number_field))[^2] วิธีหนึ่งในการนิยาม $(D|\,\cdot\,)$ คือฟังก์ชันเลขคณิตแบบคูณได้สมบูรณ์ที่กำหนดโดย (สำหรับ $p$ เป็นจำนวนเฉพาะ):
ไม่มีเนื้อหาให้แปล เนื่องจากคุณไม่ได้ระบุข้อความหรือลิงก์วิกิพีเดียภาษาอังกฤษที่ต้องการให้แปล

$$
\bigg(\frac{D}{p}\bigg)=\begin{cases}1, &(p)\text{ splits in } \mathbb{Q}(\sqrt{D}), \\ -1, &(p)\text{ is inert } \cdots, \\ 0, &(p)\text{ ramifies } \cdots, \end{cases} \quad \bigg(\frac{D}{-1}\bigg) = \text{sign of } D.
$$

ดังนั้นจึงนิยมเขียน $\chi_D := (D|\,\cdot\,)$ ซึ่งเป็นอักขระปฐมภูมิจริง modulo $|D|$

### พื้นที่ที่ไม่มีศูนย์แบบคลาสสิก

**ฟังก์ชัน L ของดิริชเลต** (Dirichlet L-function) ที่สัมพันธ์กับอักขระ $\chi~(\mathrm{mod}~q)$ ถูกนิยามว่าเป็น [การลู่เข้า](https://en.wikipedia.org/wiki/analytic_continuation) แบบวิเคราะห์ของ [อนุกรมดิริชเลต](https://en.wikipedia.org/wiki/Dirichlet_series) $L(s,\chi) = \sum_{n\geq 1} \chi(n) n^{-s}$ ที่นิยามไว้สำหรับ $\mathrm{Re}(s)>1$ โดยที่ *s* เป็น [ตัวแปรเชิงซ้อน](https://en.wikipedia.org/wiki/complex_variable) สำหรับ $\chi$ ที่ไม่ใช่จำนวนเฉพาะหลัก (non-principal) การลู่เข้านี้จะเป็น [ฟังก์ชันทั้งระนาบ](https://en.wikipedia.org/wiki/Entire_function) (entire); ในทางกลับกันมันจะมี [ขั้วอย่างง่าย](https://en.wikipedia.org/wiki/Zeros_and_poles) ของ [ค่าตกค้าง](https://en.wikipedia.org/wiki/Residue_%28complex_analysis%29) $\prod_{p\mid q}(1-p^{-1})$ ที่ $s = 1$ เป็นความผิดปกติเพียงอย่างเดียว สำหรับ $\mathrm{Re}(s)>1$ ฟังก์ชัน L ของดิริชเลตสามารถขยายออกมาเป็น [ผลคูณออยเลอร์](https://en.wikipedia.org/wiki/Euler_product) $L(s,\chi) = \prod_{p} (1 - \chi(p)p^{-s})^{-1}$ จากที่ซึ่งสามารถสรุปได้ว่า $L(s,\chi)$ ไม่มีศูนย์ในบริเวณนี้ [ทฤษฎีบทจำนวนเฉพาะสำหรับลำดับเลขคณิต](https://en.wikipedia.org/wiki/Prime_number_theorem#Prime_number_theorem_for_arithmetic_progressions) นั้นเทียบเท่า (ในบางความหมาย) กับ $L(1+it,\chi) \neq 0$ ( $\forall t\in\mathbb{R}$) นอกจากนี้ ผ่าน [สมการเชิงฟังก์ชัน](https://en.wikipedia.org/wiki/Dirichlet_L-function#Functional_equation) เราสามารถสะท้อนบริเวณเหล่านี้ผ่าน $s\mapsto 1-s$ เพื่อสรุปได้ว่า ยกเว้นจำนวนเต็มลบที่มีพาริตีเหมือน $χ$[^3] ศูนย์ทั้งหมดของ $L(s,\chi)$ จะต้องอยู่ใน $\{0<\mathrm{Re}(s)<1\}$ บริเวณนี้เรียกว่า **แถบวิกฤต** (critical strip) และศูนย์ในบริเวณนี้เรียกว่า **ศูนย์ที่ไม่สำคัญ** (non-trivial zeros)

ทฤษฎีบทคลาสสิกเกี่ยวกับบริเวณที่ไม่มีศูนย์ว่าง (Grönwall,[^4] Landau,[^5] Titchmarsh[^6]) ระบุว่า มี
จำนวนจริง $A>0$ ที่สามารถคำนวณได้โดยมีประสิทธิภาพ โดยที่เมื่อเขียนตัวแปรเชิงซ้อนเป็น $s=\sigma + it$ ฟังก์ชัน $L(s,\chi)$ จะไม่มีศูนย์อยู่ในบริเวณ
ไม่มีเนื้อหาให้แปลครับ เนื่องจากข้อความที่คุณให้มาคือเครื่องหมายสองจุด (: ) เท่านั้น ซึ่งไม่ใช่เนื้อหาจากวิกิพีเดียภาษาอังกฤษ

$$
\sigma > 1 - \frac{A}{\log q + \log (|t|+2)}
$$

ถ้า $\chi~(\mathrm{mod}~q)$ ไม่ใช่จำนวนจริง ถ้า $\chi$ เป็นจำนวนจริง แล้วจะมีศูนย์ในบริเวณนี้มากที่สุดหนึ่งจุด ซึ่งต้องเป็น *จำนวนจริง* และ *ง่าย* เสมอ ศูนย์ที่เป็นไปได้นี้เป็นที่รู้จักกันในชื่อ **Siegel zero**

สมมติฐานของรีมันแบบทั่วไป (GRH) อ้างว่า สำหรับทุก $\chi~(\mathrm{mod}~q)$ ศูนย์ที่ไม่สำคัญทั้งหมดของ $L(s,\chi)$ จะอยู่บนเส้น $\mathrm{Re}(s)=\frac{1}{2}$

### นิยาม "ศูนย์ของซีเกล"

นิยามของซีเกล零零 (Siegel zeros) ตามที่นำเสนอเชื่อมโยงกับค่าคงที่ $A$ ในบริเวณที่ไม่มีศูนย์ ซึ่งมักทำให้การจัดการกับวัตถุเหล่านี้เป็นเรื่องยุ่งยาก เนื่องจากในหลายสถานการณ์ ค่าเฉพาะของค่าคงที่ $A$ นั้นไม่สำคัญเท่าไร[^1] ดังนั้น จึงเป็นเรื่องปกติที่จะทำงานกับข้อความที่ชัดเจนยิ่งขึ้น ไม่ว่าจะเป็นการยืนยันหรือปฏิเสธการมีอยู่ของตระกูล*อนันต์*ของศูนย์ดังกล่าว เช่น ใน:
* **Conjecture** ("no Siegel zeros"): *ถ้า $\beta_D$* หมายถึงศูนย์จริงที่ใหญ่ที่สุดของ $L(s,\chi_D)$ แล้ว $1-\beta_D \gg \frac{1}{\log|D|}.$

ความเป็นไปได้ของการมีอยู่หรือไม่การมีอยู่ของ Siegel zeros มีผลกระทบอย่างมากในสาขาที่เกี่ยวข้องอย่างใกล้ชิดกับทฤษฎีจำนวน โดยข้อความคาดการณ์ "ไม่มี Siegel zeros" ทำหน้าที่เป็นทางเลือกที่อ่อนกว่า (แม้ว่าจะทรงพลังและบางครั้งก็เพียงพออย่างสมบูรณ์) แทน GRH (ดูด้านล่างสำหรับตัวอย่างที่เกี่ยวข้องกับทฤษฎีบท Siegel–Tatsuzawa และปัญหา [idoneal number](https://en.wikipedia.org/wiki/idoneal_number)) รูปแบบที่เทียบเท่าของ "ไม่มี Siegel zeros" ที่ไม่ได้กล่าวถึงศูนย์อย่างชัดเจนคือข้อความว่า:
ไม่มีเนื้อหาให้แปล เนื่องจากคุณไม่ได้ระบุข้อความภาษาอังกฤษที่ต้องการให้แปล

$$
\frac{L'}{L}(1,\chi_D) = O(\log|D|).
$$

สามารถสรุปความสมมูลนี้ได้ ตัวอย่างเช่น โดยการใช้บริเวณที่ไม่มีศูนย์และการประมาณแบบดั้งเดิมสำหรับจำนวนศูนย์ที่ไม่สำคัญของ $L(s,\chi)$ จนถึงระดับความสูงหนึ่งๆ.[^7]

## การประมาณค่าของแลนเดา–ซีเกิล

การก้าวกระโดดครั้งแรกว่ากับการจัดการกับศูนย์เหล่านี้มาจากแลนดาу ซึ่งแสดงให้เห็นว่ามีความคงที่ที่สามารถคำนวณได้อย่างมีประสิทธิภาพ $B>0$ ซึ่งทำให้ได้ผลลัพธ์ที่ว่า สำหรับ $\chi_D$ และ $\chi_{D'}$ เป็นอักขระปฐมภูมิจริงของมอดุลัสที่แตกต่างกัน ถ้า $\beta, \beta'$ เป็นศูนย์จริงของ $L(s,\chi_D), L(s,\chi_{D'})$ ตามลำดับ แล้ว
:

$$
\min\{\beta,\beta'\} < 1- \frac{B}{\log|DD'|}.
$$

กล่าวคือ หากมีซีโร่ของซีเกล (Siegel zeros) ก็ไม่สามารถมีจำนวนมากเกินไป วิธีการพิสูจน์นี้ใช้การโต้แย้งแบบ 'บิด' (twisting argument) ซึ่งยกระดับปัญหาไปยังฟังก์ชันซีตาของเดเดคินด์ (Dedekind zeta function) ของฟิลด์ไบควอดราติก (biquadratic field) $\mathbb{Q}(\sqrt{D},\sqrt{D'})$ เทคนิคนี้ยังคงถูกนำไปใช้กันอย่างกว้างขวางในงานสมัยใหม่

ปรากฏการณ์ 'การผลัก' (ดู [ปรากฏการณ์เดอริง–ไฮลอบรอน](https://en.wikipedia.org/wiki/Deuring%E2%80%93Heilbronn_phenomenon)) หลังจากวิเคราะห์อย่างละเอียดมากขึ้น นำแลนดาไปสู่ทฤษฎีบทปี 1936 ของเขา[^8] ซึ่งระบุว่า สำหรับทุก $\varepsilon > 0$ จะมี $C(\varepsilon)\in\mathbb{R}_{+}$ ที่ซึ่ง ถ้า $\beta$ เป็นศูนย์จริงของ $L(s,\chi_D)$ แล้ว $\beta < 1 - C(\varepsilon)|D|^{-\frac{3}{8} - \varepsilon}$ อย่างไรก็ตาม ในปีเดียวกัน ในฉบับเดียวกันของวารสารเดียวกัน เซียเกิล[^9] ได้ปรับปรุงการประมาณค่านี้โดยตรงไป
ไม่มีเนื้อหาให้แปล เนื่องจากข้อความที่ส่งมาเป็นเครื่องหมายโคลอน (: ) เท่านั้น

$$
\beta < 1 - C(\varepsilon)|D|^{-\varepsilon}.
$$

ทั้งการพิสูจน์ของ Landau และ Siegel ให้วิธีคำนวณ $C(\varepsilon)\in\mathbb{R}_{+}$ อย่างชัดเจนไม่ได้ จึงเป็นตัวอย่างของ [ผลที่ไม่ได้ผล](https://en.wikipedia.org/wiki/Effective_results_in_number_theory)

### ทฤษฎีบทซีเกิล-ทาสุซาว่า

ในปี 1951, [Tikao Tatsuzawa](https://en.wikipedia.org/wiki/Tikao_Tatsuzawa) พิสูจน์รูปแบบที่มีประสิทธิภาพ 'เกือบ' ของทฤษฎีบทของ Siegel,[^10] แสดงว่าสำหรับค่าคงที่ใด ๆ $0 < \varepsilon < \frac{1}{11.2}$ ถ้า $|D| > e^{1/\varepsilon}$ แล้ว
ไม่มีเนื้อหาให้แปล เนื่องจากข้อความที่ส่งมาเป็นเครื่องหมายสองจุด (: ) เท่านั้น

$$
L(1,\chi_D) > 0.655\varepsilon|D|^{-\varepsilon},
$$

*ยกเว้นการข้อยกเว้นที่เป็นไปได้ของดิสคริมิแนนต์พื้นฐานมากที่สุดหนึ่งตัว* โดยใช้ 'เกือบมีประสิทธิภาพ' ของผลลัพธ์นี้ [P. J. Weinberger](https://en.wikipedia.org/wiki/Peter_J._Weinberger) (1973)[^11] ได้แสดงว่ารายการของ 65 [จำนวน idoneal](https://en.wikipedia.org/wiki/idoneal_number) ของออยเลอร์นั้นสมบูรณ์ ยกเว้นมากที่สุดสององค์ประกอบ.[^12]

## ความสัมพันธ์กับฟิลด์กำลังสอง

**Siegel zeros** มักปรากฏเป็นปัญหาที่มากกว่าแค่เรื่องประดิษฐ์ในการโต้แย้งเพื่อหาเขตที่ไม่มีศูนย์ เนื่องจากประมาณการของเขตที่ไม่มีศูนย์มีความเชื่อมโยงอย่างลึกซึ้งกับเลขคณิตของฟิลด์กำลังสอง ตัวอย่างเช่น ความเท่าเทียมกัน $\zeta_{\mathbb{Q}(\sqrt{D})}(s) = \zeta(s) L(s,\chi_D)$ สามารถตีความได้ว่าเป็นรูปแบบการวิเคราะห์ของ [quadratic reciprocity](https://en.wikipedia.org/wiki/quadratic_reciprocity) (ดู [Artin reciprocity law §Statement in terms of L-functions](https://en.wikipedia.org/wiki/Artin_reciprocity_law#Statement_in_terms_of_L-functions)) ความสัมพันธ์ที่แม่นยำระหว่างการจัดเรียงของศูนย์ใกล้ $s = 1$ และเลขคณิตมาจาก [Dirichlet's class number formula](https://en.wikipedia.org/wiki/Class_number_formula#Dirichlet_class_number_formula):


$$
L(1,\chi_D) =
\begin{cases} \dfrac{2 \pi}{w_D \sqrt{|D|}}  \, h(D), &\text{if } D < 0 \\[.5em]
\dfrac{\log\varepsilon_D}{\sqrt{D}}\, h(D), &\text{if } D > 0,
\end{cases}
$$

โดยที่:
* $h(D)$ คือ [ideal class number](https://en.wikipedia.org/wiki/Ideal_class_group#Properties) ของ $\mathbb{Q}(\sqrt{D})$;
* $w_D$ คือจำนวน [รากของหนึ่ง](https://en.wikipedia.org/wiki/roots_of_unity) ใน $\mathbb{Q}(\sqrt{D})$ (เมื่อ $D < 0$);
* $\varepsilon_D$ คือ [fundamental unit](https://en.wikipedia.org/wiki/Fundamental_unit_%28number_theory%29) ของ $\mathbb{Q}(\sqrt{D})$ (เมื่อ $D > 0$).
ด้วยวิธีนี้ การประมาณค่าสำหรับศูนย์จริงที่ใหญ่ที่สุดของ $L(s,\chi_D)$ สามารถแปลเป็นการประมาณค่าสำหรับ $L(1,\chi_D)$ (ผ่านตัวอย่างเช่นข้อเท็จจริงที่ว่า $|L'(\sigma,\chi)| = O(\log^2 q)$ สำหรับ $1-\frac{1}{\log q} \leq \sigma \leq 1$),[^13] ซึ่งต่อมาก็กลายเป็นการประมาณค่าสำหรับ $h(D)$ งานคลาสสิกในสาขานี้ปฏิบัติกับปริมาณทั้งสามนี้โดยถือว่าสามารถสลับเปลี่ยนกันได้ แม้ว่าการกรณี $D > 0$ จะนำมาซึ่งความซับซ้อนเพิ่มเติมที่เกี่ยวข้องกับ [fundamental unit]

### จุดศูนย์ซีเกลในฐานะปรากฏการณ์กำลังสอง

มีความหมายหนึ่งซึ่งความยากลำบากที่เกี่ยวข้องกับปรากฏการณ์ของซีตา (Siegel zeros) โดยทั่วไปนั้นถูกจำกัดอยู่ในส่วนขยายกำลังสองอย่างสมบูรณ์ ตัวอย่างเช่น เป็นผลสืบเนื่องมาจาก [ทฤษฎีบทครอนเนกเกอร์–เวเบอร์](https://en.wikipedia.org/wiki/Kronecker%E2%80%93Weber_theorem) ที่ [ฟังก์ชันซีตาเดเดคินด์](https://en.wikipedia.org/wiki/Dedekind_zeta_function) $\zeta_{K}(s) = \sum_{I\subseteq \mathfrak{O}_K} [\mathfrak{O}_K: I]^{-s}$ ของ [ฟิลด์จำนวนอาบีเลียน](https://en.wikipedia.org/wiki/Abelian_extension) $K/\mathbb{Q}$ สามารถเขียนเป็นผลคูณของฟังก์ชัน L ของ Dirichlet ได้.[^14] ดังนั้น หาก $\zeta_{K}(s)$ มีซีตา (Siegel zero) ก็ต้องมีฟิลด์ย่อย $F\subseteq K$ ซึ่ง $[F:\mathbb{Q}] = 2$ โดยที่ $\zeta_{F}(s)$ มีซีตา (Siegel zero) ด้วย

ในขณะเดียวกัน สำหรับกรณีที่ไม่เป็นอาบีเลียน $\zeta_{K}(s)$ สามารถแยกตัวประกอบได้เฉพาะเป็นฟังก์ชัน L ของอาติน [Artin L-function](https://en.wikipedia.org/wiki/Artin_L-function) ที่ซับซ้อนกว่านี้เท่านั้น แต่ความจริงก็ยังคงเป็นเช่นนี้:

* **ทฤษฎีบท** ([Stark](https://en.wikipedia.org/wiki/Harold_Stark), 1974)[^15] ให้ $K/\mathbb{Q}$ เป็นฟิลด์จำนวนที่มีดีกรี $n > 1$ จะมีค่าคงที่ $c(n)$ ($= 4$ ถ้า $K/\mathbb{Q}$ เป็นฟิลด์ปกติ, $= 4n!$ มิฉะนั้น) ซึ่งถ้ามีจำนวนจริง $\beta$ ในช่วง
ไม่มีเนื้อหาให้แปล เนื่องจากข้อความที่ส่งมาเป็นเครื่องหมายสองจุด (: ) เท่านั้น

$$
1 - \frac{c(n)}{\log|\Delta_K|} \leq \beta < 1
$$

เมื่อ $\zeta_K(\beta) = 0$ แล้ว จะมีฟิลด์ย่อยกำลังสอง $F\subseteq K$ ซึ่งทำให้ $\zeta_{F}(\beta)=0$ ที่นี่ $\Delta_K$ คือ [field discriminant](https://en.wikipedia.org/wiki/Discriminant_of_an_algebraic_number_field) ของส่วนขยาย $K/\mathbb{Q}$

## "ไม่มีจุดซีเกล" สำหรับ *D* \< 0

เมื่อพิจารณาฟิลด์กำลังสอง กรณี $D>0$ มักจะเข้าใจยากเนื่องจากพฤติกรรมของหน่วยพื้นฐาน ดังนั้นจึงเป็นเรื่องปกติที่จะพิจารณากรณี $D<0$ และ $D>0$ แยกกัน มีข้อมูลมากกว่าสำหรับกรณี discriminant ลบ:

### ขอบเขตล่างสำหรับ *h*(*D*)

ในปี 1918, [Erich Hecke](https://en.wikipedia.org/wiki/Erich_Hecke) แสดงว่า "ไม่มี Siegel zeros" สำหรับ $D<0$ หมายความว่า $h(D) \gg \sqrt{|D|}(\log|D|)^{-1}$[^5] (ดู [Class number problem](https://en.wikipedia.org/wiki/Class_number_problem) เพื่อเปรียบเทียบ) สิ่งนี้สามารถขยายไปสู่ความสมมูล เนื่องจากเป็นผลมาจากทฤษฎีบท 3 ใน [Granville](https://en.wikipedia.org/wiki/Andrew_Granville)–[Stark](https://en.wikipedia.org/wiki/Harold_Stark) (2000):[^16]
ไม่มีเนื้อหาให้แปล เนื่องจากข้อความที่ส่งมาเป็นเครื่องหมายโคลอน (: ) เท่านั้น

$$
\text{“No Siegel zeros” for } D<0 \quad\iff\quad h(D) \gg \frac{\sqrt{|D|}}{\log|D|}\sum_{(a,b,c)} \frac{1}{a},
$$

ซึ่งผลบวกวิ่งผ่าน [รูปแบบกำลังสองแบบลดรูป](https://en.wikipedia.org/wiki/Binary_quadratic_form#Reduction_and_class_numbers) [รูปแบบกำลังสองแบบไบนารี](https://en.wikipedia.org/wiki/binary_quadratic_form) $ax^2 + bxy + cy^2$ ที่มีค่าแยก $D$ โดยใช้สิ่งนี้ Granville และ Stark แสดงให้เห็นว่ารูปแบบที่เป็นมาตรฐานอย่างสม่ำเสมอของ [ข้อความคาดการณ์ abc](https://en.wikipedia.org/wiki/abc_conjecture) สำหรับฟิลด์จำนวนนำไปสู่ "ไม่มีซีเกิลซีโร่" สำหรับค่าแยกที่เป็นลบ

ในปี 1976, [Dorian Goldfeld](https://en.wikipedia.org/wiki/Dorian_Goldfeld)[^17] ได้พิสูจน์ขอบเขตล่างที่มีประสิทธิภาพแบบไม่มีเงื่อนไขสำหรับ $h(D)$ ดังนี้:
:

$$
h(D) \gg \prod_{p\mid D} \bigg(1-\frac{2\sqrt{p}}{p+1}\bigg)\, \log|D|.
$$

### การคูณเชิงซ้อน

อีกความสมมูลหนึ่งสำหรับ "ไม่มีซีเกล์ซีโร่" สำหรับ $D<0$ สามารถให้ในรูปของ [ขอบเขตบน](https://en.wikipedia.org/wiki/Upper_and_lower_bounds) สำหรับ [ความสูง](https://en.wikipedia.org/wiki/Height_function) ของ [มอดูลัสเอกฐาน](https://en.wikipedia.org/wiki/Complex_multiplication#Singular_moduli):
:

$$
h(j(\tau_D)) \ll \log|D|,
$$

โดยที่:
* $h$ คือ [ความสูงลอการิทึมแบบง่าย](https://en.wikipedia.org/wiki/Height_function#Height_functions_in_Diophantine_geometry) สำหรับฟิลด์จำนวน;
* $j$ คือ [ฟังก์ชันค่าคงที่ j](https://en.wikipedia.org/wiki/j-invariant);
* $\tau_D := (D+\sqrt{D})/2$.
จำนวน $j(\tau_D)$ สร้าง [ฟิลด์คลาสฮิลเบิร์ต](https://en.wikipedia.org/wiki/Hilbert_class_field) ของ $\mathbb{Q}(\sqrt{D})$ ซึ่งเป็นการขยายอาบีเลียนที่ไม่มีการแตกกิ่งสูงสุดของมัน.[^18] ความสมมูลนี้เป็นการตามผลโดยตรงจากงานของ Granville–Stark (2000),[^16] และสามารถพบเห็นได้ใน C. Táfula (2019).[^19]

ความสัมพันธ์ที่แน่นอนระหว่างความสูงและค่าของฟังก์ชัน L ได้โดย [ปีแยร์ กอลแมซ](https://en.wikipedia.org/wiki/Pierre_Colmez) (1993,[^20] 1998[^21]) ซึ่งแสดงให้เห็นว่า สำหรับเส้นโค้งเชิงวงรี $E_D/\mathbb{C}$ ที่มี [complex multiplication](https://en.wikipedia.org/wiki/complex_multiplication) โดย $\mathbb{Z}[\tau_D]$ เรามี
ไม่มีเนื้อหาให้แปล

$$
-2 h_{\mathrm{Fal}}(E_D) - \frac{1}{2} \log|D| = \frac{L'}{L}(0,\chi_D) + \log 2\pi,
$$

โดยที่ $h_{\mathrm{Fal}}$ คือ [ความสูงของ Faltings](https://en.wikipedia.org/wiki/Height_function#Height_functions_in_Diophantine_geometry)[^22] โดยใช้เอกลักษณ์ $h_{\mathrm{Fal}}(E_D) = \frac{1}{12}h(j(\tau_D)) + O(\log h(j(\tau_D)))$[^23] และ $\frac{L'}{L}(1,\chi_D) = -\frac{L'}{L}(0,\chi_D) - \log|D| + \log 2\pi + \gamma$[^24] ทฤษฎีบทของ Colmez ยังให้หลักฐานสำหรับความสมมูลดังกล่าวด้วย

## ผลกระทบจากการมีอยู่ของศูนย์ของซีเกล

แม้ว่าสมมติฐานของรีมันแบบทั่วไป (generalized Riemann hypothesis) (https://en.wikipedia.org/wiki/generalized_Riemann_hypothesis) จะคาดว่าจะถูกต้อง แต่เนื่องจากข้อความคาดการณ์ "ไม่มีซีเกล_zeros" ยังไม่ได้รับการพิสูจน์ จึงน่าสนใจที่จะศึกษาว่าตัวอย่างที่ขัดแย้งอย่างรุนแรงกับ GRH จะส่งผลกระทบอะไรบ้าง อีกเหตุผลหนึ่งในการศึกษาความเป็นไปได้ดังกล่าวคือ การพิสูจน์ทฤษฎีบทบางประการที่ไม่ขึ้นกับเงื่อนไขต้องการการแบ่งออกเป็นสองกรณี: หนึ่งคือการพิสูจน์โดยสมมติว่าไม่มีซีเกล_zeros มีอยู่ แล้วตามด้วยการพิสูจน์โดยสมมติว่าซีเกล_zeros มีอยู่จริง ทฤษฎีบทแบบคลาสสิกประเภทนี้คือ [ทฤษฎีบทของลินนิค](https://en.wikipedia.org/wiki/Linnik%27s_theorem) เกี่ยวกับจำนวนเฉพาะที่น้อยที่สุดในลำดับเลขคณิต (https://en.wikipedia.org/wiki/Primes_in_arithmetic_progression)

ตัวอย่างต่อไปนี้คือข้อเท็จจริงบางประการที่ได้จากการมีอยู่ของซีเกล์ซีโร่

### จำนวนเฉพาะแฝดอนันต์

ผลลัพธ์ที่น่าทึ่งในทิศทางนี้คือผลลัพธ์ของ [Roger Heath-Brown](https://en.wikipedia.org/wiki/Roger_Heath-Brown) ในปี 1983[^25] ซึ่งตาม [เทเรนซ์ เทา](https://en.wikipedia.org/wiki/Terence_Tao),[^26] สามารถกล่าวได้ดังนี้:
* **ทฤษฎีบท** (Heath-Brown, 1983)**.** อย่างน้อยหนึ่งในข้อต่อไปนี้เป็นจริง: *(1)* ไม่มี Siegel zeros. (*2)* มีจำนวนเฉพาะแฝดจำนวนอนันต์

### ปัญหาความคู่

ปัญหาความคู่ใน [ทฤษฎีการร่อน](https://en.wikipedia.org/wiki/sieve_theory) นั้นโดยประมาณหมายถึงข้อเท็จจริงที่ว่าข้อโต้แย้งการร่อนโดยทั่วไปไม่สามารถบอกได้ว่าจำนวนเต็มหนึ่งมีตัวหารเฉพาะจำนวนคู่หรือคี่ This leads to many upper bounds in sieve estimates, such as the one from the [linear sieve](https://en.wikipedia.org/wiki/linear_sieve)[^27] being off by a factor of 2 from the expected value. In 2020, [Granville](https://en.wikipedia.org/wiki/Andrew_Granville)[^28] แสดงให้เห็นว่าภายใต้สมมติฐานของการมีอยู่ของ Siegel zeros ขอบเขตบนทั่วไปสำหรับปัญหาการร่อนช่วงต่างๆ นั้นเป็นค่าที่เหมาะสมที่สุด หมายความว่าปัจจัย 2 เพิ่มเติมที่เกิดจากปรากฏการณ์ความคู่จึงไม่ใช่ข้อจำกัดเทียมของวิธีการ

## ดูเพิ่มเติม

* สมมติฐานของรีมันน์ทั่วไป (https://en.wikipedia.org/wiki/Generalized_Riemann_hypothesis)
* ปรากฏการณ์เดือริง–ไฮล์บรอนน์ (https://en.wikipedia.org/wiki/Deuring%E2%80%93Heilbronn_phenomenon)
* ปัญหาจำนวนตัวหารชั้น (https://en.wikipedia.org/wiki/Class_number_problem)
* ทฤษฎีบทบราวเออร์–ซีเกิล (https://en.wikipedia.org/wiki/Brauer%E2%80%93Siegel_theorem)
* ทฤษฎีบทซีเกิล–วาลฟิส (https://en.wikipedia.org/wiki/Siegel%E2%80%93Walfisz_theorem)

## อ้างอิง

* ดavenport, H. (1980). *ทฤษฎีจำนวนเชิงวิเคราะห์*. ISBN 978-1-4757-5929-7. doi:[10.1007/978-1-4757-5927-3](https://doi.org/10.1007/978-1-4757-5927-3). [Multiplicative Number Theory](https://link.springer.com/book/10.1007/978-1-4757-5927-3).
* Iwaniec, H. (2006). *Analytic Number Theory: Lectures given at the C.I.M.E. Summer School held in Cetraro, Italy, July 11–18, 2002*. *Springer* **1891**, 97–132. ISBN 978-3-540-36364-4. doi:[10.1007/978-3-540-36364-4_3](https://doi.org/10.1007/978-3-540-36364-4_3).
* Montgomery, H. L.; Vaughan, R. C. (2006). *Multiplicative Number Theory I: Classical Theory*. *Cambridge University Press*. ISBN 978-0-521-84903-6. [Multiplicative Number Theory I: Classical Theory](https://www.cambridge.org/core/books/multiplicative-number-theory-i/4E45519B26115AEEA4839C6C38206ACD).
* Zagier, D. B. (1981). *Zetafunktionen und quadratische Körper: Eine Einführung in die höhere Zahlentheorie*. *Springer-Verlag*. ISBN 978-3-540-10603-6. [Zetafunktionen und quadratische Körper: Eine Einführung in die höhere Zahlentheorie](https://www.springer.com/de/book/9783540106036).

## หมายเหตุ

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
