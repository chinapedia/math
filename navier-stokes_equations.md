---
title: สมการนาเวียร์–สโตกส์
---

**สมการนาเวียร์–สโตกส์** (Navier–Stokes equations) อธิบายการเคลื่อนที่ของ [ของไหลหนืด](https://en.wikipedia.org/wiki/Viscosity) ระบบ [สมการเชิงอนุพันธ์ย่อย](https://en.wikipedia.org/wiki/Partial_differential_equation) ชุดนี้ตั้งชื่อตาม [Claude-Louis Navier](https://en.wikipedia.org/wiki/Claude-Louis_Navier) และ [George Gabriel Stokes](https://en.wikipedia.org/wiki/Sir_George_Stokes%2C_1st_Baronet) ผู้พัฒนาขึ้นในช่วงเวลาหลายทศวรรษของการทำงานอย่างก้าวหน้า ตั้งแต่ปี 1822 (นาเวียร์) ถึง 1842–1850 (สโตกส์) [Siméon Denis Poisson](https://en.wikipedia.org/wiki/Sim%C3%A9on_Denis_Poisson) บรรลุผลลัพธ์เดียวกันอย่างอิสระ[^1]

สมการนาเวียร์–สโตกส์ (Navier–Stokes equations) คือสมการที่แสดงสมดุลของ[โมเมนตัม](https://en.wikipedia.org/wiki/momentum)สำหรับ[ของไหลนิวโตเนียน](https://en.wikipedia.org/wiki/Newtonian_fluid) และใช้หลักการ[อนุรักษ์มวล](https://en.wikipedia.org/wiki/conservation_of_mass) บางครั้งสมการเหล่านี้จะประกอบด้วย[สมการสถานะ](https://en.wikipedia.org/wiki/equation_of_state)ที่เกี่ยวข้องกับ[แรงดัน](https://en.wikipedia.org/wiki/pressure) [อุณหภูมิ](https://en.wikipedia.org/wiki/temperature) และ[ความหนาแน่น](https://en.wikipedia.org/wiki/density)[^2] สมการเหล่านี้เกิดขึ้นจากการประยุกต์ใช้[กฎข้อที่สองของนิวตัน](https://en.wikipedia.org/wiki/Newton%27s_second_law)ต่อ[การเคลื่อนที่ของของไหล](https://en.wikipedia.org/wiki/Fluid_dynamics) พร้อมกับสมมติฐานว่า[ความเค้น](https://en.wikipedia.org/wiki/stress_%28mechanics%29)ในของไหลคือผลรวมของเทอมความหนืดแบบแพร่ (diffusing viscous term) ซึ่งแปรผันตรงกับ[เกรเดียนต์](https://en.wikipedia.org/wiki/gradient)ของความเร็ว และเทอมแรงดัน—ดังนั้นจึงอธิบายการไหลแบบหนืด (viscous flow) สมการนาเวียร์–สโตกส์เป็นการขยายผลของ[สมการออยเลอร์](https://en.wikipedia.org/wiki/Euler_equations_%28fluid_dynamics%29) ซึ่งพิจารณาเฉพาะ[การไหลแบบไม่มีความหนืด](https://en.wikipedia.org/wiki/inviscid_flow) เท่านั้น

สมการนาเวียร์–สโตกส์ (Navier–Stokes equations) มีความสำคัญทางวิทยาศาสตร์และวิศวกรรมอย่างมากเพราะสามารถใช้สร้างแบบจำลองสถานการณ์ที่หลากหลายได้ ในรูปแบบเต็มหรือแบบย่อ สมการเหล่านี้สามารถช่วยในการออกแบบ [อากาศยาน](https://en.wikipedia.org/wiki/Aircraft_design_process#Preliminary_design_phase) และรถยนต์ การศึกษา [การไหลของเลือด](https://en.wikipedia.org/wiki/Hemodynamics) การออกแบบ [โรงไฟฟ้า](https://en.wikipedia.org/wiki/power_station) การวิเคราะห์ [มลพิษ](https://en.wikipedia.org/wiki/pollution) และปัญหาอื่นๆ อีกมากมาย เมื่อรวมกับ [สมการของแมกซ์เวลล์](https://en.wikipedia.org/wiki/Maxwell%27s_equations) แล้ว จะประกอบเป็นพื้นฐานของ [แม่เหล็กไฮโดรไดนามิกส์](https://en.wikipedia.org/wiki/magnetohydrodynamics)

สมการนาเวียร์–สโตกส์ยังเป็นที่สนใจอย่างมากต่อ[คณิตศาสตร์บริสุทธิ์](https://en.wikipedia.org/wiki/pure_mathematics) ปัญหา[การมีอยู่และความเรียบของนาเวียร์–สโตกส์](https://en.wikipedia.org/wiki/Navier%E2%80%93Stokes_existence_and_smoothness) เกี่ยวข้องกับว่าสมการเหล่านี้มีคำตอบที่[เรียบ](https://en.wikipedia.org/wiki/Smoothness) (หมายถึงหาอนุพันธ์ได้ไม่จำกัดครั้ง) หรือมีขอบเขต ใน[ปริภูมิยูคลิดสามมิติ](https://en.wikipedia.org/wiki/Three-dimensional_space) หรือไม่ ตรงข้ามกับการล่มสลายที่คำตอบไม่มีขอบเขต นี่เป็นหนึ่งในเจ็ด[ปัญหารางวัลมิลเลนเนียม](https://en.wikipedia.org/wiki/Millennium_Prize_Problems) ซึ่งเป็นปัญหาคณิตศาสตร์เปิดที่สำคัญ โดย[สถาบันคณิตศาสตร์เคลย์](https://en.wikipedia.org/wiki/Clay_Mathematics_Institute) เสนอเงินรางวัล 1 ล้านดอลลาร์สหรัฐในปี 2000 สำหรับคำตอบที่ถูกต้อง[^3] [^4] ในเดือนกันยายน 2026 [OpenAI](https://en.wikipedia.org/wiki/OpenAI) ประกาศตัวอย่างค้านที่อ้างว่าหักล้างปัญหาการมีอยู่และความเรียบ การประกาศดังกล่าวตามมาด้วย[ข้อพิพาทเรื่องสิทธิ์](https://en.wikipedia.org/wiki/Navier%E2%80%93Stokes_priority_controversy) และตัวอย่างค้านที่อ้างนั้นยังไม่ได้รับการตรวจสอบยืนยันอย่างอิสระ[^5]

## ความเร็วของกระแสไหล

คำตอบของสมการคือ [ความเร็วการไหล](https://en.wikipedia.org/wiki/flow_velocity) เป็น [สนามเวกเตอร์](https://en.wikipedia.org/wiki/vector_field)—สำหรับทุกจุดใน [ของไหล](https://en.wikipedia.org/wiki/fluid) ที่ช่วงเวลาใด ๆ ในช่วงเวลา มันให้เวกเตอร์ที่ทิศทางและขนาดเป็นความเร็วของของไหลที่จุดนั้นในอวกาศและในเวลานั้น มันถูกศึกษาในสามมิติเชิงพื้นที่และหนึ่งมิติเวลา และแบบจำลองในมิติที่สูงกว่าถูกศึกษาทั้งในคณิตศาสตร์บริสุทธิ์และคณิตศาสตร์ประยุกต์ เมื่อคำนวณสนามความเร็วแล้ว ปริมาณอื่น ๆ ที่น่าสนใจ เช่น [ความดัน](https://en.wikipedia.org/wiki/pressure) หรือ [อุณหภูมิ](https://en.wikipedia.org/wiki/temperature) อาจหาได้โดยใช้ [สมการไดนามิก](https://en.wikipedia.org/wiki/dynamical_systems) และความสัมพันธ์ สิ่งนี้แตกต่างจากสิ่งที่ปกติเห็นใน [กลศาสตร์คลาสสิก](https://en.wikipedia.org/wiki/classical_mechanics) ซึ่งคำตอบมักเป็น [วิถี](https://en.wikipedia.org/wiki/trajectories) ของตำแหน่งของ [อนุภาค](https://en.wikipedia.org/wiki/particle) หรือการเบี่ยงเบนของ [สสารต่อเนื่อง](https://en.wikipedia.org/wiki/Continuum_%28theory%29) การศึกษาความเร็วแทนตำแหน่งมีความหมายมากกว่าสำหรับของไหล แม้ว่าเพื่อวัตถุประสงค์ในการแสดงภาพหนึ่งสามารถคำนวณ [วิถี](https://en.wikipedia.org/wiki/Streamlines%2C_streaklines%2C_and_pathlines) ต่าง ๆ ได้ โดยเฉพาะ [เส้นกระแส](https://en.wikipedia.org/wiki/Streamlines%2C_streaklines%2C_and_pathlines) ของสนามเวกเตอร์ ที่ตีความว่าเป็นความเร็วการไหล คือเส้นทางที่อนุภาคของของไหลไร้มวลจะเดินทาง เส้นทางเหล่านี้คือ [เส้นโค้งอินทิกรัล](https://en.wikipedia.org/wiki/integral_curve) ซึ่งอนุพันธ์ที่แต่ละจุดเท่ากับสนามเวกเตอร์ และพวกมันสามารถแสดงพฤติกรรมของสนามเวกเตอร์ ณ จุดเวลาหนึ่งได้ทางสายตา

## สมการต่อเนื่องทั่วไป

สมการโมเมนตัมของนาเวียร์–สโตกส์ สามารถได้มาในรูปเฉพาะของ [สมการโมเมนตัมของโคชี](https://en.wikipedia.org/wiki/Cauchy_momentum_equation) ซึ่งอยู่ในรูปการพาทั่วไปดังนี้:

$$
\frac{\mathrm{D} \mathbf{u}}{\mathrm{D} t} = \frac 1 \rho \nabla \cdot \boldsymbol{\sigma} + \mathbf{a}.
$$

เมื่อตั้ง [ความเค้นแบบ Cauchy](https://en.wikipedia.org/wiki/Cauchy_stress_tensor) $\boldsymbol{\sigma}$ ให้เป็นผลรวมของพจน์ความหนืด $\boldsymbol{\tau}$ (ความเค้นแบบ [เดวิเอตริก](https://en.wikipedia.org/wiki/deviatoric_stress)) และพจน์ความดัน $-p \mathbf{I}$ (ความเค้นแบบปริมาตร) เราจะได้ว่า:

โดยที่
* $\frac{\mathrm{D}}{\mathrm{D}t}$ คือ [อนุพันธ์เชิงวัสดุ](https://en.wikipedia.org/wiki/material_derivative) ซึ่งนิยามว่า $\frac{\partial}{\partial t} + \mathbf{u} \cdot \nabla$
* $\rho$ คือ ความหนาแน่น (มวล)
* $\mathbf{u}$ คือ ความเร็วของการไหล
* $\nabla \cdot \,$ คือ [ไดเวอร์เจนซ์](https://en.wikipedia.org/wiki/divergence)
* $p$ คือ [ความดัน](https://en.wikipedia.org/wiki/pressure)
* $t$ คือ [เวลา](https://en.wikipedia.org/wiki/time)
* $\boldsymbol{\tau}$ คือ [เทนเซอร์ความเค้นเบี่ยงเบน](https://en.wikipedia.org/wiki/Deviatoric_stress) ซึ่งมีอันดับ 2
* $\mathbf{a}$ แทน [ความเร่งเนื่องจากแรงภายนอก](https://en.wikipedia.org/wiki/body_force#acceleration) ที่กระทำต่อตัวกลางต่อเนื่อง เช่น [ความโน้มถ่วง](https://en.wikipedia.org/wiki/gravity), [ความเร่งเนื่องจากแรงเฉื่อย](https://en.wikipedia.org/wiki/Fictitious_force), [ความเร่งเนื่องจากไฟฟ้าสถิต](https://en.wikipedia.org/wiki/Coulomb%27s_law) และอื่นๆ

ในรูปนี้ จะเห็นได้ชัดว่าภายใต้สมมติฐานของของไหลที่ไม่มีความหนืด – ไม่มีแรงเฉือน – สมการของโคชีจะลดลงเป็น [สมการออยเลอร์](https://en.wikipedia.org/wiki/Euler_equations_%28fluid_dynamics%29)

โดยสมมติว่า [การอนุรักษ์มวล](https://en.wikipedia.org/wiki/conservation_of_mass) และใช้คุณสมบัติที่ทราบของ [ไดเวอร์เจนซ์](https://en.wikipedia.org/wiki/divergence) และ [เกรเดียนต์](https://en.wikipedia.org/wiki/gradient) เราสามารถใช้สมการ [ความต่อเนื่องของมวล](https://en.wikipedia.org/wiki/continuity_equation) ซึ่งแสดงมวลต่อหน่วยปริมาตรของของไหล [เนื้อเดียวกัน](https://en.wikipedia.org/wiki/homogenous) เทียบกับพื้นที่และเวลา (กล่าวคือ [อนุพันธ์เชิงวัสดุ](https://en.wikipedia.org/wiki/material_derivative) $\frac{\mathbf{D}}{\mathbf{Dt}}$) ของปริมาตรจำกัดใดๆ ( $\mathbf{V}$) เพื่อแสดงการเปลี่ยนแปลงความเร็วในสื่อของไหล:

$$
\begin{align}
& \frac{\mathbf{D}m}{\mathbf{Dt}} = \iiint\limits_V \left(\frac{ \mathbf{D}\rho}{\mathbf{Dt}} + \rho (\nabla \cdot \mathbf{u})\right) \, dV \\[5pt]
& \frac{\mathbf{D}\rho}{\mathbf{Dt}} + \rho (\nabla \cdot \mathbf{u} )=\frac{\partial\rho}{\partial t} + (\nabla \rho) \cdot \mathbf{u} + \rho(\nabla \cdot \mathbf{u})= \frac{\partial\rho}{\partial t} + \nabla\cdot(\rho \mathbf{u})= 0
\end{align}
$$

ที่
* $\frac{\mathrm{D}m}{\mathrm{D}t}$ คือ[อนุพันธ์เชิงวัสดุ](https://en.wikipedia.org/wiki/material_derivative)ของ[มวล](https://en.wikipedia.org/wiki/mass)ต่อหน่วยปริมาตร ([ความหนาแน่น](https://en.wikipedia.org/wiki/density), $\rho$),
* $\iiint \limits_V \bigl(F(x_1, x_2, x_3 ,t)\bigr) \, dV$ คือการดำเนินการทางคณิตศาสตร์สำหรับ[การอินทิเกรตตลอดปริมาตร](https://en.wikipedia.org/wiki/Volume_integral) ( $V$),
* $\frac{\partial }{\partial t}$ คือตัวดำเนินการทางคณิตศาสตร์ [อนุพันธ์ย่อย](https://en.wikipedia.org/wiki/partial_derivative)
* $\nabla \cdot \mathbf{u}\,$ คือ [การลู่เข้า](https://en.wikipedia.org/wiki/divergence) ของความเร็วการไหล ( $\mathbf{u}$) ซึ่งเป็น [สนามสเกลาร์](https://en.wikipedia.org/wiki/scalar_field)[^6]
* เกรเดียนต์ของ [ความหนาแน่น](https://en.wikipedia.org/wiki/density) ( $\rho$) ซึ่งคืออนุพันธ์เวกเตอร์ของ [สนามสเกลาร์](https://en.wikipedia.org/wiki/scalar_field) [^6] คือ $\nabla \rho \,$ [เกรเดียนต์](https://en.wikipedia.org/wiki/gradient)
เพื่อไปสู่รูปแบบการอนุรักษ์ของสมการการเคลื่อนที่ ซึ่งมักเขียนเป็นดังนี้:[^7]

โดยที่ $\otimes$ คือ [ผลคูณภายนอก](https://en.wikipedia.org/wiki/outer_product) ของความเร็วของการไหล ( $\mathbf{u}$):

$$
\mathbf u \otimes \mathbf u = \mathbf u \mathbf u^{\mathsf T}
$$

ด้านซ้ายของสมการอธิบายความเร่ง และอาจประกอบด้วยองค์ประกอบที่ขึ้นอยู่กับเวลาและองค์ประกอบพาหะ (รวมถึงผลของพิกัดที่ไม่เฉื่อยหากมีอยู่) ด้านขวาของสมการโดยเนื้อแท้แล้วเป็นการรวมกันของผลทางอุทกสถิต การกระจายตัวของความเค้นแบบเบี่ยงเบน และแรงภายนอก (เช่น แรงโน้มถ่วง)

สมการสมดุลที่ไม่ขึ้นกับสัมพัทธภาพ เช่น สมการนาเวียร์–สโตกส์ สามารถได้มาโดยเริ่มจากสมการโคชีและกำหนดเทนเซอร์ความเค้นผ่าน [ความสัมพันธ์เชิงโครงสร้าง](https://en.wikipedia.org/wiki/constitutive_relation) โดยการเขียนเทนเซอร์ความเค้นเฉือน (ความเค้นเฉือน) ในรูปของ [ความหนืด](https://en.wikipedia.org/wiki/viscosity) และเกรเดียนต์ของ [ความเร็ว](https://en.wikipedia.org/wiki/Shear_velocity) ของของไหล และโดยสมมติว่าความหนืดเป็นค่าคงที่ สมการโคชีข้างต้นจะนำไปสู่สมการนาเวียร์–สโตกส์ด้านล่าง

### ความเร่งแบบพา

<figure style={{"maxWidth": "132px"}}>

![An example of convection. Though the flow may be steady (time-independent), the fluid decelerates as it moves down the diverging duct (assuming incompressible or subsonic compressible flow), hence there is an acceleration happening over position.](https://pub-275e30003c354ac0862cc9839e0f952a.r2.dev/docs/math/ConvectiveAcceleration_vectorized.svg.png)

<figcaption>

ตัวอย่างของการพาความร้อน แม้ว่าการไหลอาจคงที่ (ไม่ขึ้นกับเวลา) แต่ของไหลจะชะลอตัวลงเมื่อเคลื่อนที่ผ่านท่อที่ขยายออก (โดยสมมติว่าเป็นการไหลแบบอัดตัวไม่ได้หรือการไหลแบบอัดตัวได้ที่มีความเร็วต่ำกว่าเสียง) ดังนั้นจึงเกิดการเร่งความเร็วในตำแหน่งหนึ่ง

</figcaption>

</figure>

คุณสมบัติที่สำคัญของสมการโคชี และโดยนัยแล้วสมการต่อเนื่องอื่นๆ (รวมถึงสมการออยเลอร์และสมการนาเวียร์–สโตกส์) คือการมีอยู่ของความเร่งพา: ผลของความเร่งของของไหลเทียบกับพื้นที่ ในขณะที่อนุภาคของไหลแต่ละตัวนั้นประสบความเร่งที่ขึ้นอยู่กับเวลาจริง แต่ความเร่งพาของสนามของไหลเป็นผลเชิงพื้นที่ ตัวอย่างหนึ่งคือของไหลเร่งความเร็วในหัวฉีด

## การไหลแบบบีบอัดได้

หมายเหตุ: ในที่นี้ เทนเซอร์ความเค้นเฉือน (deviatoric stress tensor) ถูกกำหนดสัญลักษณ์ว่า $\boldsymbol{\tau}$ เหมือนกับที่ใช้ใน [สมการต่อเนื่องทั่วไป](./navier-stokes_equations.md#general-continuum-equations) และใน [ส่วนการไหลแบบอัดตัวไม่ได้](./navier-stokes_equations.md#incompressible-flow)

สมการโมเมนตัมของนาเวียร์–สโตกส์แบบอัดตัวได้ (compressible momentum Navier–Stokes equation) เกิดขึ้นจากสมมติฐานต่อไปนี้เกี่ยวกับเทนเซอร์ความเค้นของโคชี:[^8]

<ul>
ความเค้นเป็น **[ภาวะคงรูปกาลิเลโอ](https://en.wikipedia.org/wiki/Galilean_invariance)**: มันไม่ได้ขึ้นอยู่กับความเร็วของการไหลโดยตรง แต่ขึ้นอยู่กับอนุพันธ์เชิงพื้นที่ของความเร็วของการไหลเท่านั้น ดังนั้นตัวแปรความเค้นคือเกรเดียนต์ของเทนเซอร์ $\nabla \mathbf{u}$ หรืออย่างง่ายกว่านั้นคือ [เทนเซอร์อัตราความเครียด](https://en.wikipedia.org/wiki/strain-rate_tensor): $\boldsymbol{\varepsilon}\left(\nabla \mathbf{u}\right) \equiv \frac{1}{2}\nabla \mathbf{u} + \frac{1}{2} \left(\nabla \mathbf{u}\right)^{\mathsf T}$
ความเค้นแบบ deviatoric เป็น **linear** ในตัวแปรนี้: $\boldsymbol{\sigma}(\boldsymbol \varepsilon) = -p \mathbf I + \mathbf{C} : \boldsymbol \varepsilon$ โดยที่ $p$ เป็นอิสระต่อเทนเซอร์อัตราการเปลี่ยนรูป $\mathbf{C}$ คือเทนเซอร์อันดับสี่ที่แสดงค่าคงที่ของสัดส่วน เรียกว่าความหนืดหรือ [เทนเซอร์ความยืดหยุ่น](https://en.wikipedia.org/wiki/elasticity_tensor) และ : คือ [ผลคูณจุดคู่](https://en.wikipedia.org/wiki/Dyadics#Double-dot_product)
ของไหลถูกสันนิษฐานให้เป็น [ไอโซทรอปี](https://en.wikipedia.org/wiki/isotropic) เช่นเดียวกับแก๊สและของเหลวอย่างง่าย และดังนั้น $\mathbf{C}$ จึงเป็นเทนเซอร์แบบ isotropic; นอกจากนี้ เนื่องจากเทนเซอร์ความเค้นแบบ deviatoric เป็นแบบสมมาตร ผ่าน [การแยกเฮล์มโฮลตซ์](https://en.wikipedia.org/wiki/Helmholtz_decomposition) จึงสามารถแสดงในรูปของสเกลาร์สองตัว [พารามิเตอร์ลาเม](https://en.wikipedia.org/wiki/Lam%C3%A9_parameters) คือ [ความหนืดที่สอง](https://en.wikipedia.org/wiki/second_viscosity) $\lambda$ และ [ความหนืดพลวัต](https://en.wikipedia.org/wiki/dynamic_viscosity) $\mu$ ตามที่เป็นปกติใน [ความยืดหยุ่นเชิงเส้น](https://en.wikipedia.org/wiki/linear_elasticity):

โดยที่ $\mathbf{I}$ คือ [เทนเซอร์เอกลักษณ์](https://en.wikipedia.org/wiki/Identity_matrix) และ $\operatorname{tr} (\boldsymbol \varepsilon)$ คือ [รอย](https://en.wikipedia.org/wiki/trace_%28linear_algebra%29) ของเทนเซอร์อัตราส่วนการเปลี่ยนรูป ดังนั้นการแยกส่วนนี้จึงสามารถนิยามได้ดังนี้:

$$
\boldsymbol \sigma = -p \mathbf I + \lambda (\nabla\cdot\mathbf{u}) \mathbf I + \mu \left(\nabla\mathbf{u} + ( \nabla\mathbf{u} )^\mathsf{T}\right).
$$

</ul>

เนื่องจาก [รอย](https://en.wikipedia.org/wiki/trace_%28linear_algebra%29) ของเทนเซอร์อัตราความเครียดในสามมิติคือ [ไดเวอร์เจนซ์](https://en.wikipedia.org/wiki/divergence) (กล่าวคือ อัตราการขยายตัว) ของการไหล:

$$
\operatorname{tr} (\boldsymbol \varepsilon) = \nabla\cdot\mathbf{u}.
$$

จากความสัมพันธ์นี้ และเนื่องจาก trace ของเทนเซอร์เอกลักษณ์ในสามมิติมีค่าเท่ากับสาม:

$$
\operatorname{tr} (\boldsymbol I) = 3.
$$

trace ของความเค้นเทนเซอร์ในสามมิติกลายเป็น:

$$
\operatorname{tr} (\boldsymbol \sigma ) = -3p + (3 \lambda + 2 \mu )\nabla\cdot\mathbf{u}.
$$

ดังนั้นโดยการแยกความเค้นออกเป็นส่วน **ไอโซโทรปิก** และ **เดวิเอทีริก** แบบที่นิยมใช้ในพลศาสตร์ของไหล:[^9]

$$
\boldsymbol \sigma = - \left[ p - \left(\lambda + \tfrac23 \mu\right) \left(\nabla\cdot\mathbf{u}\right) \right] \mathbf I + \mu \left(\nabla\mathbf{u} + \left( \nabla\mathbf{u} \right)^\mathsf{T} - \tfrac23 \left(\nabla\cdot\mathbf{u}\right)\mathbf I\right)
$$

การแนะนำ [ความหนืดมวล](https://en.wikipedia.org/wiki/volume_viscosity) $\zeta$,

$$
\zeta \equiv \lambda + \tfrac23 \mu ,
$$

เราจะได้สมการเชิงเส้น [สมการเชิงประกอบ](https://en.wikipedia.org/wiki/constitutive_equation) ในรูปแบบที่ใช้กันทั่วไปใน [อุณหพลศาสตร์ไฮดรอลิก](https://en.wikipedia.org/wiki/thermal_hydraulics):[^8]

ซึ่งสามารถจัดเรียงในรูปแบบมาตรฐานอื่นได้เช่นกัน:[^10]

$$
\boldsymbol \sigma = -p \mathbf I + \mu \left(\nabla\mathbf{u} + ( \nabla\mathbf{u} )^\mathsf{T}\right) + \left(\zeta - \tfrac 2 3 \mu \right) (\nabla\cdot\mathbf{u}) \mathbf I.
$$

โปรดทราบว่า ในกรณีอัดตัวได้ ความดันจะไม่เป็นสัดส่วนกับเทอม [ความเค้นไอโซโทรปิก](https://en.wikipedia.org/wiki/hydrostatic_stress) อีกต่อไป เนื่องจากมีเทอมความหนืดปริมาตรเพิ่มเติม:

$$
p = - \tfrac 1 3 \operatorname{tr} (\boldsymbol \sigma)  + \zeta (\nabla\cdot\mathbf{u})
$$

และ [ความเค้นเฉือน](https://en.wikipedia.org/wiki/deviatoric_stress_tensor) $\boldsymbol \sigma'$ ยังคงสอดคล้องกับเทนเซอร์ความเค้นเฉือน $\boldsymbol \tau$ (กล่าวคือ ความเค้นเฉือนในของไหลนิวโทเนียนไม่มีองค์ประกอบความเค้นปกติ) และมีพจน์ความสามารถในการอัดตัวเพิ่มเติมจากกรณีที่ไม่สามารถอัดตัวได้ ซึ่งแปรผันตรงกับความหนืดเฉือน:

$$
\boldsymbol \sigma' = \boldsymbol \tau = \mu \left[\nabla\mathbf{u} + ( \nabla\mathbf{u} )^\mathsf{T} - \tfrac23 (\nabla\cdot\mathbf{u})\mathbf I\right]
$$

ทั้งความหนืดปริมาตร $\zeta$ และความหนืดไดนามิก $\mu$ ไม่จำเป็นต้องเป็นค่าคงที่ – โดยทั่วไปแล้ว พวกมันขึ้นอยู่กับตัวแปรอุณหพลศาสตร์สองตัวหากของไหลประกอบด้วยสปีชีส์เคมีเพียงชนิดเดียว ตัวอย่างเช่น ความดันและอุณหภูมิ สมการใด ๆ ที่ทำให้ชัดเจนค่า [สัมประสิทธิ์การขนส่ง](https://en.wikipedia.org/wiki/transport_coefficient) หนึ่งค่าในตัวแปร [ตัวแปรอนุรักษ์](https://en.wikipedia.org/wiki/conservation_variable)s เรียกว่า [สมการสถานะ](https://en.wikipedia.org/wiki/equation_of_state)[^11]

สมการนาเวียร์–สโตกส์ที่กว้างที่สุดจะกลายเป็น

ในสัญกรณ์ดัชนี สมการสามารถเขียนเป็น[^12]

สมการที่สอดคล้องกันในรูปการอนุรักษ์สามารถหาได้โดยพิจารณาว่า เมื่อให้มวล [สมการความต่อเนื่อง](https://en.wikipedia.org/wiki/continuity_equation) ด้านซ้ายจะเทียบเท่า:

$$
\rho \frac{\mathrm{D} \mathbf{u}}{\mathrm{D} t} = \frac {\partial}{\partial t} (\rho \mathbf u) + \nabla \cdot (\rho \mathbf u \otimes \mathbf u)
$$

ให้สรุปในที่สุด:

นอกเหนือจากการขึ้นอยู่กับความดันและอุณหภูมิแล้ว สัมประสิทธิ์ความหนืดอันดับสองยังขึ้นอยู่กับกระบวนการด้วย นั่นคือ สัมประสิทธิ์ความหนืดอันดับสองไม่ใช่คุณสมบัติของวัสดุเพียงอย่างเดียว ตัวอย่างเช่น ในกรณีของคลื่นเสียงที่มีความถี่ที่กำหนดซึ่งอัดและขยายองค์ประกอบของของไหลไปมา สัมประสิทธิ์ความหนืดอันดับสองจะขึ้นอยู่กับความถี่ของคลื่น ความสัมพันธ์นี้เรียกว่า *dispersion* ในบางกรณี [ความหนืดที่สอง](https://en.wikipedia.org/wiki/volume_viscosity) $\zeta$ สามารถสมมติให้เป็นค่าคงที่ได้ ซึ่งในกรณีนี้ ผลของความหนืดปริมาตร $\zeta$ คือความดันเชิงกลไม่เทียบเท่ากับความดันทางอุณหพลศาสตร์ [ความดัน](https://en.wikipedia.org/wiki/pressure):[^13] ดังที่แสดงด้านล่าง

$$
\begin{align} &\nabla\cdot(\nabla\cdot \mathbf u)\mathbf I=\nabla (\nabla \cdot \mathbf u), \\ &\bar{p} \equiv p - \zeta \, \nabla \cdot \mathbf{u} ,\end{align}
$$

อย่างไรก็ตาม ความแตกต่างนี้มักถูกละเลยส่วนใหญ่ของเวลา (นั่นคือทุกครั้งที่เราไม่ได้จัดการกับกระบวนการเช่นการดูดกลืนเสียงและการลดทอนคลื่นกระแทก [^14] ซึ่งค่าสัมประสิทธิ์ความหนืดอันดับสองมีความสำคัญ) โดยการสมมติอย่างชัดเจนว่า $\zeta = 0$ การสมมติการกำหนด $\zeta = 0$ นี้เรียกว่า **Stokes hypothesis** [^15] ความถูกต้องของ Stokes hypothesis สามารถแสดงให้เห็นได้สำหรับแก๊สอะตอมเดี่ยวทั้งจากการทดลองและจากทฤษฎีจลน์ [^16] สำหรับแก๊สและของเหลวอื่นๆ Stokes hypothesis โดยทั่วไปไม่ถูกต้อง ด้วย Stokes hypothesis สมการ Navier–Stokes จะกลายเป็น

หากความหนืดไดนามิก $\mu$ และความหนืดเชิงปริมาตร $\zeta$ ถูกสมมติให้เป็นค่าคงที่ในอวกาศ สมการในรูปแบบการพาความร้อนสามารถทำให้เรียบง่ายยิ่งขึ้นได้ โดยการคำนวณไดเวอร์เจนซ์ของเทนเซอร์ความเค้น เนื่องจากไดเวอร์เจนซ์ของเทนเซอร์ $\nabla \mathbf{u}$ คือ $\nabla^2 \mathbf{u}$ และไดเวอร์เจนซ์ของเทนเซอร์ $\left(\nabla \mathbf{u}\right)^{\mathsf T}$ คือ $\nabla \left(\nabla \cdot \mathbf{u}\right)$ จึงได้สมการโมเมนตัมของนาเวียร์–สโตกส์แบบอัดตัวได้ในที่สุด:[^17]

โดยที่ $\frac{\mathrm{D}}{\mathrm{D}t}$ คือ [อนุพันธ์เชิงวัสดุ](https://en.wikipedia.org/wiki/material_derivative) $\nu=\frac \mu \rho$ คือความหนืดจลนศาสตร์แบบเฉือน [ความหนืดจลนศาสตร์](https://en.wikipedia.org/wiki/kinematic_viscosity) และ $\xi=\frac \zeta \rho$ คือความหนืดจลนศาสตร์แบบปริมาตร สมการด้านซ้ายมือมีการเปลี่ยนแปลงในรูปแบบการอนุรักษ์ของสมการโมเมนตัมของนาเวียร์–สโตกส์
โดยการนำตัวดำเนินการไปกระทำต่อความเร็วของไหลทางด้านซ้ายมือ จะได้ดังนี้:

พจน์ความเร่งแบบพาความร้อนสามารถเขียนเป็น

$$
\mathbf u\cdot\nabla\mathbf u = (\nabla\times\mathbf u)\times\mathbf u + \tfrac12\nabla\mathbf u^2,
$$

ซึ่งเวกเตอร์ $(\nabla \times \mathbf{u}) \times \mathbf{u}$ นี้รู้จักกันในชื่อ [เวกเตอร์แลมบ์](https://en.wikipedia.org/wiki/Lamb_vector)

สำหรับกรณีพิเศษของ [การไหลที่ไม่สามารถบีบอัดได้](https://en.wikipedia.org/wiki/incompressible_flow) ความดันจะจำกัดการไหลจนทำให้ปริมาตรของ [องค์ประกอบของของไหล](https://en.wikipedia.org/wiki/fluid_element) คงที่: [การไหลที่มีปริมาตรคงที่](https://en.wikipedia.org/wiki/isochoric_process) ซึ่งนำไปสู่สนามความเร็วที่เป็น [แบบไดเวอร์เจนซ์เป็นศูนย์](https://en.wikipedia.org/wiki/Solenoidal_vector_field) โดยมี $\nabla \cdot \mathbf{u} = 0$.[^18]

## การไหลแบบอัดไม่ได้

สมการโมเมนตัมของนาเวียร์–สโตกส์ที่ไม่สามารถอัดได้ (incompressible momentum Navier–Stokes equation) เกิดขึ้นจากสมมติฐานต่อไปนี้บนเทนเซอร์ความเค้นของโคชี:[^8]

<ul>
ความเค้นเป็น **[ภาวะคงรูปกาลิเลโอ](https://en.wikipedia.org/wiki/Galilean_invariance)**: มันไม่ได้ขึ้นอยู่กับความเร็วของการไหลโดยตรง แต่ขึ้นอยู่กับอนุพันธ์เชิงพื้นที่ของความเร็วของการไหลเท่านั้น ดังนั้นตัวแปรความเค้นจึงเป็นเทนเซอร์เกรเดียนต์ $\nabla \mathbf{u}$
ของไหลนั้นถือว่า [ไอโซทรอปี](https://en.wikipedia.org/wiki/isotropic) เช่นเดียวกับแก๊สและของเหลวอย่างง่าย และดังนั้น $\boldsymbol{\tau}$ จึงเป็นเทนเซอร์ไอโซโทรปิก; ยิ่งไปกว่านั้น เนื่องจากเทนเซอร์ความเค้นเฉือนสามารถแสดงออกในรูปของ [ความหนืดพลวัต](https://en.wikipedia.org/wiki/dynamic_viscosity) $\mu$:

ที่

$$
\boldsymbol{\varepsilon} = \tfrac{1}{2} \left( \mathbf{\nabla u} + \mathbf{\nabla u}^\mathsf{T} \right)
$$

คืออัตราการ-[เทนเซอร์ความเค้น](https://en.wikipedia.org/wiki/strain_tensor) ดังนั้นการแยกส่วนนี้จึงสามารถทำให้ชัดเจนได้ดังนี้:[^8]

</ul>

สมการเชิงประจักษ์นี้ยังเรียกว่า **[กฎความหนืดของนิวตัน](https://en.wikipedia.org/wiki/Newtonian_fluid#Newtonian_law_of_viscosity)** ด้วย
ความหนืดไดนามิก $μ$ ไม่จำเป็นต้องคงที่ – ในกระแสไหลที่ไม่สามารถอัดได้มันสามารถขึ้นอยู่กับความหนาแน่นและความดัน สมการใดก็ตามที่ทำให้ชัดเจนหนึ่งใน [สัมประสิทธิ์การขนส่ง](https://en.wikipedia.org/wiki/transport_coefficient) เหล่านี้ในตัวแปร [อนุรักษ์](https://en.wikipedia.org/wiki/conservative_variable) เรียกว่า [สมการสถานะ](https://en.wikipedia.org/wiki/equation_of_state)[^11]

การลู่ออกของความเค้นเฉือนในกรณีที่มีความหนืดสม่ำเสมอให้โดย:

$$
\nabla \cdot \boldsymbol \tau = 2 \mu \nabla \cdot \boldsymbol \varepsilon = \mu \nabla \cdot \left( \nabla\mathbf{u} + \nabla\mathbf{u} ^\mathsf{T} \right) = \mu \, \nabla^2 \mathbf{u}
$$

เพราะว่า $\nabla \cdot \mathbf{u} = 0$ สำหรับของไหลที่ไม่สามารถอัดได้

ความไม่สามารถบีบอัดได้ (Incompressibility) ตัดสินใจเรื่องความหนาแน่นและคลื่นความดัน เช่น เสียง หรือ [คลื่นกระแทก](https://en.wikipedia.org/wiki/shock_wave) ออก ดังนั้นการทำให้เรียบง่ายนี้จึงไม่เป็นที่นิยมหากปรากฏการณ์เหล่านี้มีความสำคัญ สมมติฐานของการไหลที่ไม่สามารถบีบอัดได้มักจะถูกต้องดีกับของไหลทั้งหมดที่ [เลขมัค](https://en.wikipedia.org/wiki/Mach_number) ต่ำ (เช่น สูงสุดประมาณเลขมัค 0.3) เช่น การจำลองลมอากาศที่อุณหภูมิปกติ.[^19] สมการนาเวียร์–สโตกส์ที่ไม่สามารถบีบอัดได้ (incompressible Navier–Stokes equations) จะเห็นภาพได้ดีที่สุดโดยการแบ่งแยกตามความหนาแน่น:[^20]

โดยที่ $\nu = \frac{\mu}{\rho}$ เรียกว่า [ความหนืดจลนศาสตร์](https://en.wikipedia.org/wiki/kinematic_viscosity)
โดยการแยกความเร็วของของไหลออกมา ก็ยังสามารถระบุได้ดังนี้:

หากความหนาแน่นมีค่าคงที่ตลอดทั้งโดเมนของของไหล หรือกล่าวอีกนัยหนึ่ง หากองค์ประกอบของของไหลทั้งหมดมีความหนาแน่นเท่ากัน $\rho$ แล้วเราจะได้

ซึ่ง $\frac{p}{\rho}$ เรียกว่าหน่วย [ความสูงของแรงดัน](https://en.wikipedia.org/wiki/pressure_head)

ในกระแสไหลอัดตัวไม่ได้ สนามความดันเป็นไปตาม [สมการพอยซง](https://en.wikipedia.org/wiki/Poisson_equation)

$$
\nabla^2 p = - \rho \frac{\partial u_i}{\partial x_k}\frac{\partial u_k}{\partial x_i} = - \rho \frac{\partial^2 u_iu_k}{\partial x_kx_i},
$$

ซึ่งได้มาจากการหาไดเวอร์เจนซ์ของสมการโมเมนตัม

ควรสังเกตความหมายของแต่ละพจน์อย่างละเอียด (เปรียบเทียบกับ [สมการโมเมนตัมของโคชี](https://en.wikipedia.org/wiki/Cauchy_momentum_equation)):

$$
\overbrace{
    \vphantom{\frac{}{}}
    \underbrace{
        \frac{\partial \mathbf{u}}{\partial t}
    }_{\text{Variation}}
    +
    \underbrace{
        \vphantom{\frac{}{}}
        (\mathbf{u} \cdot \nabla) \mathbf{u}
    }_{\begin{smallmatrix}
        \text{Convective}\\
        \text{acceleration}
    \end{smallmatrix}}
}^{\text{Inertia (per volume)}}
=
\overbrace{
    \vphantom{\frac{\partial}{\partial}}
    \underbrace{
        \vphantom{\frac{}{}}
        -\nabla w
    }_{\begin{smallmatrix}
            \text{Internal}\\
            \text{source}
        \end{smallmatrix}
    }
    +
    \underbrace{
        \vphantom{\frac{}{}}
        \nu \nabla^2 \mathbf{u}
    }_{\text{Diffusion}}
}^{\text{Divergence of stress}}
+
\underbrace{
    \vphantom{\frac{}{}}
    \mathbf{g}
}_{\begin{smallmatrix}
        \text{External}\\
        \text{source}
    \end{smallmatrix}}.
$$

พจน์อันดับสูงกว่านี้ ซึ่งก็คือการลู่ออกของแรงเฉือน [ความเค้นเฉือน](https://en.wikipedia.org/wiki/shear_stress) $\nabla \cdot \boldsymbol{\tau}$ นั้นลดลงอย่างง่ายเป็นพจน์ [ลาปลาเซียนเวกเตอร์](https://en.wikipedia.org/wiki/vector_Laplacian) $\mu \nabla^2 \mathbf{u}$.[^21] พจน์ลาปลาเชียนนี้สามารถตีความได้ว่าเป็นความแตกต่างระหว่างความเร็ว ณ จุดหนึ่งและความเร็วเฉลี่ยในปริมาตรรอบข้างขนาดเล็ก ซึ่งหมายความว่า – สำหรับของไหลนิวโตเนียน – ความหนืดทำงานเป็น *การแพร่ของโมเมนตัม* ในลักษณะที่คล้ายคลึงกับการ [การนำความร้อน](https://en.wikipedia.org/wiki/heat_conduction) มากทีเดียว แท้จริงแล้ว หากละเลยพจน์การพา (convection term) สมการนาเวียร์–สโตกส์แบบอัดตัวไม่ได้ (incompressible Navier–Stokes equations) จะนำไปสู่สมการ [สมการการแพร่](https://en.wikipedia.org/wiki/diffusion_equation) แบบเวกเตอร์ (กล่าวคือ [สมการสโตกส์](https://en.wikipedia.org/wiki/Stokes_flow)) แต่โดยทั่วไปแล้วพจน์การพาจะปรากฏอยู่ ดังนั้นสมการนาเวียร์–สโตกส์แบบอัดตัวไม่ได้จึงอยู่ในกลุ่มของสมการ [สมการการพา–การแพร่](https://en.wikipedia.org/wiki/convection%E2%80%93diffusion_equation)

ในกรณีทั่วไปของสนามภายนอกที่เป็น [สนามอนุรักษ์](https://en.wikipedia.org/wiki/conservative_field):

$$
\mathbf g = - \nabla \varphi
$$

โดยนิยาม [ความสูงของของเหลว](https://en.wikipedia.org/wiki/hydraulic_head):

$$
h \equiv w + \varphi
$$

ในที่สุดสามารถทำให้แหล่งกำเนิดทั้งหมดรวมเป็นพจน์เดียวได้ โดยได้สมการนาเวียร์–สโตกส์แบบอัดตัวไม่ได้ที่มีสนามภายนอกแบบอนุรักษ์:

$$
\frac{\partial \mathbf{u}}{\partial t} + (\mathbf{u} \cdot \nabla) \mathbf{u} - \nu \, \nabla^2 \mathbf{u} = - \nabla h.
$$

สมการนาเวียร์–สโตกส์ที่ไม่สามารถอัดตัวได้ซึ่งมีความหนาแน่นและความหนืดสม่ำเสมอและมีสนามภายนอกแบบอนุรักษ์นั้นคือ **สมการพื้นฐานของ [ชลศาสตร์](https://en.wikipedia.org/wiki/hydraulics)** พื้นที่สำหรับสมการเหล่านี้มักเป็น [ปริภูมิแบบยุคลิด](https://en.wikipedia.org/wiki/Euclidean_space) ที่มีมิติ 3 หรือต่ำกว่า ซึ่งโดยทั่วไปจะกำหนดกรอบอ้างอิงของ [พิกัดตั้งฉาก](https://en.wikipedia.org/wiki/orthogonal_coordinate) เพื่อทำให้ชัดเจนระบบของสมการอนุพันธ์ย่อยแบบสเกลาร์ที่จะแก้ ในระบบพิกัดตั้งฉาก 3 มิติมี 3 แบบ ได้แก่ [คาร์ทีเซียน](https://en.wikipedia.org/wiki/Cartesian_coordinate_system), [ทรงกระบอก](https://en.wikipedia.org/wiki/Cylindrical_coordinate_system), และ [ทรงกลม](https://en.wikipedia.org/wiki/Spherical_coordinate_system) การแสดงสมการเวกเตอร์นาเวียร์–สโตกส์ในระบบพิกัดคาร์ทีเซียนนั้นค่อนข้างตรงไปตรงมาและได้รับผลจากจำนวนมิติของอวกาศยุคลิดที่ใช้ไม่มากนัก และกรณีนี้ยังเกิดขึ้นกับพจน์อันดับแรก (เช่น การแปรผันและการพา) ในระบบพิกัดตั้งฉากที่ไม่ใช่แบบคาร์ทีเซียนด้วย แต่สำหรับพจน์อันดับสูงกว่า (สองพจน์ที่ได้จากการกระจายตัวของความเค้นเฉือนซึ่งทำให้สมการนาเวียร์–สโตกส์แตกต่างจากสมการออยเลอร์) จำเป็นต้องใช้ [แคลคูลัสเทนเซอร์](https://en.wikipedia.org/wiki/tensor_calculus) เพื่อหาการแสดงออกในระบบพิกัดตั้งฉากที่ไม่ใช่แบบคาร์ทีเซียน
กรณีพิเศษของสมการพื้นฐานของของไหลคือ [สมการแบร์นูลลี](https://en.wikipedia.org/wiki/Bernoulli%27s_equation)

สมการนาเวียร์–สโตกส์แบบอัดตัวไม่ได้เป็นแบบผสม คือผลรวมของสมการสองสมการที่ตั้งฉากกัน

$$
\begin{align}
\frac{\partial\mathbf{u}}{\partial t} &= \Pi^S\left(-(\mathbf{u}\cdot\nabla)\mathbf{u} + \nu\,\nabla^2\mathbf{u}\right) + \mathbf{f}^S \\
\rho^{-1}\,\nabla p &= \Pi^I\left(-(\mathbf{u}\cdot\nabla)\mathbf{u} + \nu\,\nabla^2\mathbf{u}\right) + \mathbf{f}^I
\end{align}
$$

โดยที่ $\Pi^S$ และ $\Pi^I$ เป็นตัวดำเนินการฉายแบบ solenoidal และ [ไม่มีการหมุน](https://en.wikipedia.org/wiki/Conservative_vector_field) ที่สอดคล้องกับ $\Pi^S + \Pi^I = 1$ และ $\mathbf{f}^S$ และ $\mathbf{f}^I$ เป็นส่วนที่ไม่อนุรักษ์และส่วนอนุรักษ์ของแรงภายนอกตามลำดับ ผลลัพธ์นี้ได้มาจาก [ทฤษฎีบทเฮล์มโฮลตซ์](https://en.wikipedia.org/wiki/Helmholtz_decomposition) (หรือที่รู้จักกันในชื่อทฤษฎีบทพื้นฐานของการคำนวณเวกเตอร์) สมการข้อแรกเป็นสมการควบคุมที่ไม่มีแรงดันสำหรับความเร็ว ในขณะที่สมการข้อสองสำหรับแรงดันเป็นฟังก์ชันของความเร็วและมีความเกี่ยวข้องกับสมการ Poisson ของแรงดัน

รูปแบบฟังก์ชันอย่างชัดเจนของตัวดำเนินการฉายใน 3 มิติพบได้จากทฤษฎีบทเฮล์มโฮลทซ์:

$$
\Pi^S\,\mathbf{F}(\mathbf{r}) = \frac{1}{4\pi}\nabla\times\int \frac{\nabla^\prime\times\mathbf{F}(\mathbf{r}')}{|\mathbf{r}-\mathbf{r}'|} \, \mathrm{d} V', \quad \Pi^I = 1-\Pi^S
$$

ด้วยโครงสร้างที่คล้ายกันใน 2 มิติ ดังนั้นสมการควบคุมจึงเป็น [สมการอินทิโกร-ดิฟเฟอเรนเชียล](https://en.wikipedia.org/wiki/integro-differential_equation) คล้ายกับ [กฎของคูลอมบ์](https://en.wikipedia.org/wiki/Coulomb%27s_law) และ [กฎของบิโอ-ซาวาร์ต](https://en.wikipedia.org/wiki/Biot%E2%80%93Savart_law) ซึ่งไม่สะดวกต่อการคำนวณเชิงตัวเลข

รูปแบบอ่อนหรือรูปแบบแปรผันที่เทียบเท่าของสมการ ซึ่งได้รับการพิสูจน์แล้วว่าให้ผลเฉลยความเร็วเดียวกันกับสมการนาเวียร์–สโตกส์ [^22] นั้นกำหนดโดย

$$
\left(\mathbf{w},\frac{\partial\mathbf{u}}{\partial t}\right) = -\bigl(\mathbf{w}, \left(\mathbf{u}\cdot\nabla\right)\mathbf{u}\bigr) - \nu \left(\nabla\mathbf{w}: \nabla\mathbf{u}\right) + \left(\mathbf{w}, \mathbf{f}^S\right)
$$

สำหรับฟังก์ชันทดสอบที่ไม่มีไดเวอร์เจนซ์ $\mathbf{w}$ ที่สอดคล้องกับเงื่อนไขขอบเขตที่เหมาะสม ที่นี่ การฉายภาพนั้นสำเร็จลงได้โดยอาศัยความเป็นตั้งฉากของพื้นที่ฟังก์ชันโซเลนอยดัลและฟังก์ชันไอโรเตชันัล รูปแบบไม่ต่อเนื่องของสิ่งนี้เหมาะสมอย่างยิ่งสำหรับการคำนวณด้วยวิธีไฟไนต์เอลิเมนต์ของกระแสไหลที่ไม่มีไดเวอร์เจนซ์ เนื่องจากเราจะเห็นได้ในบทถัดไป ที่นั่น ผู้คนจะสามารถจัดการกับคำถามที่ว่า "ทำอย่างไรจึงจะกำหนดปัญหาที่ขับเคลื่อนด้วยแรงดัน (Poiseuille) ด้วยสมการกำกับที่ไม่มีแรงดัน?"

การไม่มีแรงดันจากสมการความเร็วที่ควบคุมแสดงให้เห็นว่าสมการนี้ไม่ใช่สมการเชิงพลวัต แต่เป็นสมการจลนศาสตร์ที่เงื่อนไขการกระจายตัวเป็นศูนย์ทำหน้าที่เป็นสมการอนุรักษ์ ซึ่งดูเหมือนจะขัดแย้งกับคำกล่าวที่พบบ่อยที่ว่าความดันที่ไม่สามารถอัดได้บังคับเงื่อนไขการกระจายตัวเป็นศูนย์

### รูปแบบอ่อนของสมการนาเวียร์–สโตกส์ที่ไม่สามารถอัดตัวได้

#### รูปแบบเข้ม

พิจารณาสมการนาเวียร์–สโตกส์แบบไม่บีบอัดสำหรับ[ของไหลนิวตัน](https://en.wikipedia.org/wiki/Newtonian_fluid)ที่มีความหนาแน่นคงที่ $\rho$ ในโดเมน

$$
\Omega \subset \mathbb R^d \quad (d=2, 3)
$$

ด้วยขอบเขต

$$
\partial \Omega = \Gamma_D \cup \Gamma_N ,
$$

เป็นส่วนของขอบเขต $\Gamma_D$ และ $\Gamma_N$ ที่มีการใช้เงื่อนไข [ดิริชเลต์](https://en.wikipedia.org/wiki/Dirichlet_boundary_condition) และ [เงื่อนไขขอบเขตนิวแมน](https://en.wikipedia.org/wiki/Neumann_boundary_condition) ตามลำดับ (โดยที่ $\Gamma_D \cap \Gamma_N = \emptyset$):[^23]

$$
\begin{cases}
\rho \dfrac{\partial \mathbf{u}}{\partial t} + \rho (\mathbf{u} \cdot \nabla) \mathbf{u} - \nabla \cdot \boldsymbol{\sigma} (\mathbf{u}, p) = \mathbf{f} & \text{ in } \Omega \times (0, T) \\
\nabla \cdot \mathbf{u} = 0  & \text{ in } \Omega \times (0, T) \\
\mathbf{u} = \mathbf{g} & \text{ on } \Gamma_D \times (0, T) \\
 \boldsymbol{\sigma} (\mathbf{u}, p) \hat{\mathbf{n}} = \mathbf{h} & \text{ on } \Gamma_N \times (0, T) \\
\mathbf{u}(0)= \mathbf{u}_0 & \text{ in } \Omega \times \{ 0\}
\end{cases}
$$

$\mathbf{u}$ คือความเร็วของของไหล $p$ คือความดันของของไหล $\mathbf{f}$ คือพจน์แรงที่กำหนดให้ $\hat{\mathbf{n}}$ คือเวกเตอร์หน่วยปกติที่ชี้ไปด้านนอกต่อ $\Gamma_N$ และ $\boldsymbol{\sigma}(\mathbf{u}, p)$ คือ [เทนเซอร์ความเค้นหนืด](https://en.wikipedia.org/wiki/viscous_stress_tensor) ที่นิยามไว้ดังนี้:[^23]

$$
\boldsymbol{\sigma} (\mathbf{u}, p) = -p \mathbf{I} + 2 \mu \boldsymbol{\varepsilon}(\mathbf{u}).
$$

ให้ $\mu$ เป็นความหนืดพลวัตของของไหล, $\mathbf{I}$ เป็นเทนเซอร์เอกลักษณ์อันดับสอง [เทนเซอร์เอกลักษณ์](https://en.wikipedia.org/wiki/Identity_matrix) และ $\boldsymbol{\varepsilon}(\mathbf{u})$ เป็นเทนเซอร์อัตราการเปลี่ยนรูป [เทนเซอร์อัตราความเครียด](https://en.wikipedia.org/wiki/strain-rate_tensor) ที่นิยามไว้ดังนี้:[^23]

$$
\boldsymbol{\varepsilon} (\mathbf{u}) = \tfrac{1}{2} \left(\left( \nabla \mathbf{u} \right) + \left( \nabla \mathbf{u} \right)^\mathsf{T}\right).
$$

ฟังก์ชัน $\mathbf{g}$ และ $\mathbf{h}$ กำหนดข้อมูลขอบเขตแบบ Dirichlet และ Neumann ในขณะที่ $\mathbf{u}_0$ เป็น [เงื่อนไขเริ่มต้น](https://en.wikipedia.org/wiki/initial_condition) สมการข้อแรกคือสมการสมดุลโมเมนตัม ในขณะที่สมการข้อที่สองแสดงถึง [การอนุรักษ์มวล](https://en.wikipedia.org/wiki/conservation_of_mass) หรือ [สมการความต่อเนื่อง](https://en.wikipedia.org/wiki/continuity_equation)
โดยสมมติความหนืดไดนามิกคงที่ โดยใช้เอกลักษณ์แบบเวกเตอร์

$$
\nabla \cdot \left( \nabla \mathbf{f} \right)^\mathsf{T} = \nabla ( \nabla \cdot \mathbf{f} )
$$

และด้วยการใช้กฎการอนุรักษ์มวล การกระจายของเทนเซอร์ความเค้นรวมในสมการโมเมนตัมยังสามารถแสดงได้ดังนี้:[^23]

$$
\begin{align}
\nabla \cdot \boldsymbol{\sigma} (\mathbf{u}, p)
& = \nabla \cdot \left(-p \mathbf{I} + 2 \mu \boldsymbol{\varepsilon}(\mathbf{u}) \right) \\
& = - \nabla p + 2 \mu \nabla \cdot \boldsymbol{\varepsilon}(\mathbf{u}) \\
& = - \nabla p + 2 \mu \nabla \cdot \left [ \tfrac{1}{2} \left(\left(\nabla \mathbf{u} \right) + \left(\nabla \mathbf{u} \right)^\mathsf{T}\right) \right] \\
& = -\nabla p + \mu \left(\Delta \mathbf{u} + \nabla \cdot \left(\nabla \mathbf{u} \right)^\mathsf{T} \right) \\
& =  -\nabla p + \mu \bigl( \Delta \mathbf{u} + \nabla  \underbrace{(\nabla \cdot \mathbf{u})}_{=0} \bigr)
= -\nabla p + \mu \, \Delta \mathbf{u}.
\end{align}
$$

นอกจากนี้ โปรดสังเกตว่าเงื่อนไขขอบเขตแบบ Neumann สามารถจัดเรียงใหม่ได้ดังนี้:[^23]

$$
\boldsymbol{\sigma}(\mathbf{u}, p) \hat{\mathbf{n}} = \bigl(-p \mathbf{I} + 2 \mu \boldsymbol{\varepsilon}(\mathbf{u})\bigr)\hat{\mathbf{n}} = -p \hat{\mathbf{n}} + \mu \frac{\partial \boldsymbol u}{\partial \hat{\mathbf{n}}}.
$$

#### รูปแบบอ่อน

ในการหาค่ารูปแบบอ่อนของสมการนาเวียร์–สโตกส์ ก่อนอื่นให้พิจารณาสมการโมเมนตัม[^23]

$$
\rho \frac{\partial \mathbf{u}}{\partial t}  - \mu \Delta \mathbf{u} + \rho (\mathbf{u} \cdot \nabla) \mathbf{u} + \nabla p  = \mathbf{f}
$$

คูณด้วยฟังก์ชันทดสอบ $\mathbf{v}$ ซึ่งนิยามในปริภูมิที่เหมาะสม $V$ แล้วอินทิเกรตทั้งสองข้างเทียบกับโดเมน $\Omega$:[^23]

$$
\int \limits_\Omega \rho \frac{\partial \mathbf{u}}{\partial t}\cdot \mathbf{v}  - \int \limits_\Omega \mu \Delta \mathbf{u} \cdot \mathbf{v} + \int \limits_\Omega \rho (\mathbf{u} \cdot \nabla) \mathbf{u} \cdot \mathbf{v} + \int \limits_\Omega \nabla p \cdot \mathbf{v} = \int \limits_\Omega \mathbf{f} \cdot \mathbf{v}
$$

การอินทิเกรตตามส่วน (integrating by parts) เทอมการแพร่กระจายและเทอมความดัน และใช้ทฤษฎีบทของเกาส์:[^23]

$$
\begin{align}
-\int \limits_\Omega \mu \Delta \mathbf{u} \cdot \mathbf{v} &= \int \limits_\Omega \mu \nabla \mathbf{u} \cdot \nabla \mathbf{v} - \int \limits_{\partial \Omega} \mu \frac{\partial \mathbf{u}}{\partial \hat{\mathbf{n}}} \cdot \mathbf{v} \\
\int \limits_\Omega \nabla p \cdot \mathbf{v} &= -\int \limits_\Omega p \nabla \cdot \mathbf{v} + \int \limits_{\partial \Omega} p \mathbf{v} \cdot {\hat{\mathbf{n}}}
\end{align}
$$

โดยใช้ความสัมพันธ์เหล่านี้ จะได้:[^23]

$$
\int \limits_\Omega \rho \dfrac{\partial \mathbf{u}}{\partial t}\cdot \mathbf{v}
 + \int \limits_\Omega \mu \nabla \mathbf{u} \cdot \nabla \mathbf{v}
 + \int \limits_\Omega \rho (\mathbf{u} \cdot \nabla) \mathbf{u} \cdot \mathbf{v}
 - \int \limits_\Omega p \nabla \cdot \mathbf{v}
= \int \limits_\Omega \mathbf{f} \cdot \mathbf{v}
 + \int \limits_{\partial \Omega} \left ( \mu \frac{\partial \mathbf{u}}{\partial \hat{\mathbf{n}}} - p \hat{\mathbf{n}}\right) \cdot \mathbf{v}
 \quad \forall \mathbf{v} \in V.
$$

ในทำนองเดียวกัน สมการความต่อเนื่องถูกคูณด้วยฟังก์ชันทดสอบ $q$ ที่อยู่ในพื้นที่ $Q$ และทำการอินทิเกรตในโดเมน $\Omega$:[^23]

$$
\int \limits_\Omega q \nabla \cdot \mathbf{u} = 0. \quad \forall q \in Q.
$$

ฟังก์ชันพื้นที่ถูกเลือกดังนี้:

$$
\begin{align}
V = \left[H_0^1(\Omega) \right]^d &= \left\{ \mathbf{v} \in \left[H^1(\Omega)\right]^d: \quad \mathbf{v} = \mathbf{0} \text{ on } \Gamma_D \right\}, \\
Q &= L^2(\Omega)
\end{align}
$$

เมื่อพิจารณาว่าฟังก์ชันทดสอบ $\mathbf v$ มีค่าเป็นศูนย์ที่ขอบเขตแบบ Dirichlet และเมื่อพิจารณาเงื่อนไข Neumann อินทิกรัลบนขอบเขตสามารถจัดเรียงใหม่ได้ดังนี้:[^23]

$$
\int \limits_{\partial \Omega} \left ( \mu \frac{\partial \mathbf{u}}{\partial \hat{\mathbf{n}}} - p \hat{\mathbf{n}} \right) \cdot \mathbf{v}
=
\underbrace{
    \int \limits_{\Gamma_D} \left ( \mu \frac{\partial \mathbf{u}}{\partial \hat{\mathbf{n}}} - p \hat{\mathbf{n}} \right) \cdot \mathbf{v}
}_{ \mathbf{v} = \mathbf{0} \text{ on } \Gamma_D \ }
+
\int \limits_{\Gamma_N} \underbrace{ \vphantom{\int \limits_{\Gamma_N} }
    \left ( \mu \frac{\partial \mathbf{u}}{\partial \hat{\mathbf{n}}} - p \hat{\mathbf{n}} \right)
}_{= \mathbf{h} \text{ on } \Gamma_N} \cdot \mathbf{v}
=
\int \limits_{\Gamma_N} \mathbf{h} \cdot \mathbf{v}.
$$

เมื่อคำนึงถึงสิ่งนี้ [การเขียนแบบอ่อน](https://en.wikipedia.org/wiki/weak_formulation)ของสมการนาเวียร์–สโตกส์ จะแสดงออกมาดังนี้:[^23]

$$
\begin{align}
&\text{find } \mathbf{u} \in L^2 \left(\mathbb R^+\; \left[H^1(\Omega)\right]^d\right) \cap C^0\left(\mathbb R^+ \; \left[L^2(\Omega)\right]^d\right) \text{ such that: } \\[5pt]
&\quad\begin{cases}
\displaystyle \int \limits_{\Omega}\rho \dfrac{\partial \mathbf{u}}{\partial t}\cdot \mathbf{v} + \int  \limits_{\Omega} \mu \nabla \mathbf{u} \cdot \nabla \mathbf{v} + \int \limits_{\Omega} \rho (\mathbf{u} \cdot \nabla) \mathbf{u} \cdot \mathbf{v} - \int \limits_{\Omega} p \nabla \cdot \mathbf{v} = \int \limits_{\Omega}\mathbf{f} \cdot \mathbf{v} +  \int \limits_{\Gamma_N} \mathbf{h} \cdot \mathbf{v} \quad \forall \mathbf{v} \in V, \\
\displaystyle  \int \limits_{\Omega} q \nabla \cdot \mathbf{u} = 0 \quad \forall q \in Q.
\end{cases}\end{align}
$$

### ความเร็วแบบไม่ต่อเนื่อง

เมื่อมีการแบ่งส่วนโดเมนของปัญหาและนิยามฟังก์ชันฐาน [ฟังก์ชันฐาน](https://en.wikipedia.org/wiki/basis_function) บนโดเมนที่ถูกแบ่งส่วนนั้น รูปแบบไม่ต่อเนื่องของสมการควบคุมคือ

$$
\left(\mathbf{w}_i, \frac{\partial\mathbf{u}_j}{\partial t}\right) = -\bigl(\mathbf{w}_i, \left(\mathbf{u}\cdot\nabla\right)\mathbf{u}_j\bigr) - \nu\left(\nabla\mathbf{w}_i: \nabla\mathbf{u}_j\right) + \left(\mathbf{w}_i, \mathbf{f}^S\right).
$$

เป็นที่พึงปรารถนาที่จะเลือกฟังก์ชันฐานที่สะท้อนลักษณะสำคัญของกระแสไหลอัดตัวไม่ได้ – องค์ประกอบเหล่านั้นต้องไม่มีไดเวอร์เจนซ์ แม้ว่าความเร็วจะเป็นตัวแปรที่น่าสนใจ แต่ทฤษฎีของเฮล์มโฮลทซ์กำหนดว่าจำเป็นต้องมีฟังก์ชันกระแสหรือศักย์เวกเตอร์ นอกจากนี้ เพื่อกำหนดการไหลของของไหลในกรณีที่ไม่มีเกรเดียนต์ความดัน สามารถระบุความแตกต่างของค่าฟังก์ชันกระแสข้ามช่องทาง 2 มิติ หรือ [อินทิกรัลเส้น](https://en.wikipedia.org/wiki/line_integral) ขององค์ประกอบสัมผัสของศักย์เวกเตอร์รอบช่องทางใน 3 มิติ โดยที่การไหลถูกกำหนดโดย [ทฤษฎีบทของสโตกส์](https://en.wikipedia.org/wiki/Stokes%27_theorem) การอภิปรายจะจำกัดอยู่เฉพาะ 2 มิติในต่อไปนี้

เราจำกัดการอภิปรายเพิ่มเติมไปยังองค์ประกอบเฮอไมต์แบบต่อเนื่อง (continuous Hermite finite elements) ซึ่งต้องมีองศาอิสระของอนุพันธ์อันดับหนึ่งอย่างน้อยหนึ่งตัว ด้วยสิ่งนี้ ผู้คนสามารถสร้างองค์ประกอบสามเหลี่ยมและสี่เหลี่ยมผืนผ้าที่เป็นตัวเลือกจำนวนมากจากวรรณกรรมเรื่อง [การดัดแผ่น](https://en.wikipedia.org/wiki/Bending_of_plates) องค์ประกอบเหล่านี้มีอนุพันธ์เป็นองค์ประกอบของเกรเดียนต์ ใน 2D เกรเดียนต์และเคอร์ลของสเกลาร์นั้นตั้งฉากกันอย่างชัดเจน โดยกำหนดให้ตามนิพจน์

$$
\begin{align}
\nabla\varphi &= \left(\frac{\partial \varphi}{\partial x},\,\frac{\partial \varphi}{\partial y}\right)^\mathsf{T}, \\[5pt]
\nabla\times\varphi &= \left(\frac{\partial \varphi}{\partial y},\,-\frac{\partial \varphi}{\partial x}\right)^\mathsf{T}.
\end{align}
$$

การใช้อิเล็กเมนต์การดัดแผ่นต่อเนื่อง การสลับระดับอิสระของอนุพันธ์ และการเปลี่ยนเครื่องหมายของอันที่เหมาะสม ให้ตระกูลของอิเล็กเมนต์ฟังก์ชันกระแสไหลจำนวนมาก

การหาคิวลบขององค์ประกอบฟังก์ชันกระแสเชิงสเกลาร์ให้ผลลัพธ์เป็นองค์ประกอบความเร็วที่ไม่มีค่าไดเวอร์เจนซ์[^24] [^25] ข้อกำหนดที่ว่าองค์ประกอบฟังก์ชันกระแสต้องต่อเนื่องนั้น รับประกันว่าองค์ประกอบความเร็วในแนวตั้งฉากจะต่อเนื่องกันตลอดรอยต่อระหว่างองค์ประกอบ ซึ่งเป็นสิ่งจำเป็นเพียงอย่างเดียวสำหรับการทำให้ค่าไดเวอร์เจนซ์เป็นศูนย์บนรอยต่อเหล่านี้

เงื่อนไขขอบเขตนั้นง่ายต่อการนำไปใช้ ฟังก์ชันกระแสมีค่าคงที่บนพื้นผิวที่ไม่มีกระแสไหล โดยมีเงื่อนไขความเร็วแบบไม่ลื่นไถลบนพื้นผิว
ความแตกต่างของฟังก์ชันกระแสผ่านช่องทางเปิดกำหนดการไหล ไม่จำเป็นต้องมีเงื่อนไขขอบเขตบนขอบเขตเปิด แม้ว่าอาจใช้ค่าที่สอดคล้องกันกับปัญหาบางประเภทได้ ทั้งหมดนี้เป็นเงื่อนไขของ Dirichlet

สมการเชิงพีชคณิตที่จะแก้มีความง่ายในการจัดตั้ง แต่แน่นอนว่าเป็น [ไม่เชิงเส้น](./navier-stokes_equations.md#nonlinearity) จึงต้องการการวนซ้ำของสมการเชิงเส้น

การพิจารณาที่คล้ายกันนี้ใช้กับสามมิติ แต่การขยายจาก 2 มิติไม่ได้เกิดขึ้นทันที เนื่องจากธรรมชาติของศักย์ที่เป็นเวกเตอร์ และไม่มีความสัมพันธ์อย่างง่ายระหว่างเกรเดียนต์และเคิร์ล เหมือนที่เป็นกรณีใน 2 มิติ

### การกู้คืนความดัน

การกู้คืนความดันจากสนามความเร็วเป็นเรื่องง่าย สมการอ่อนแบบไม่ต่อเนื่องสำหรับเกรเดียนต์ความดันคือ

$$
(\mathbf{g}_i, \nabla p) = -\bigl(\mathbf{g}_i, \left(\mathbf{u}\cdot\nabla\right)\mathbf{u}_j\bigr) - \nu\left(\nabla\mathbf{g}_i: \nabla\mathbf{u}_j\right) + \left(\mathbf{g}_i, \mathbf{f}^I\right)
$$

โดยที่ฟังก์ชันทดสอบ/ฟังก์ชันน้ำหนักเป็นแบบไม่มีกระแสหมุนวน (irrotational) สามารถใช้เอลิเมนต์สเกลาร์แบบใดก็ได้ที่สอดคล้องกับเงื่อนไขนี้ อย่างไรก็ตาม สนามเกรเดียนต์ความดันอาจเป็นที่สนใจเช่นกัน ในกรณีนี้สามารถใช้เอลิเมนต์ Hermite แบบสเกลาร์สำหรับความดันได้ สำหรับฟังก์ชันทดสอบ/ฟังก์ชันน้ำหนัก $\mathbf{g}_i$ จะเลือกใช้เอลิเมนต์เวกเตอร์แบบไม่มีกระแสหมุนวนที่ได้จากเกรเดียนต์ของเอลิเมนต์ความดัน

## กรอบอ้างอิงที่ไม่เฉื่อย

กรอบอ้างอิงที่หมุนจะนำแรงเทียมบางประการที่น่าสนใจเข้ามาในสมการผ่านพจน์ [อนุพันธ์เชิงวัสดุ](https://en.wikipedia.org/wiki/material_derivative) พิจารณากรอบอ้างอิง [เฉื่อย](https://en.wikipedia.org/wiki/inertial_frame_of_reference) $K$ ที่อยู่นิ่ง และกรอบอ้างอิง [ไม่เฉื่อย](https://en.wikipedia.org/wiki/non-inertial_frame_of_reference) $K'$ ซึ่งกำลังเคลื่อนที่ด้วยความเร็ว $\mathbf{U}(t)$ และหมุนด้วยความเร็วเชิงมุม $\Omega(t)$ เทียบกับกรอบที่อยู่นิ่ง สมการนาเวียร์–สโตกส์ที่สังเกตจากกรอบที่ไม่เฉื่อยนั้นจะกลายเป็น

ที่นี่ $\mathbf{x}$ และ $\mathbf{u}$ วัดในกรอบที่ไม่เฉื่อย เทอมแรกในวงเล็บคือ [ความเร่งโคริโอลิส](https://en.wikipedia.org/wiki/Coriolis_acceleration) เทอมที่สองเกิดจาก [ความเร่งหนีศูนย์กลาง](https://en.wikipedia.org/wiki/centrifugal_force) เทอมที่สามเกิดจากความเร่งเชิงเส้นของ $K'$ เทียบกับ $K$ และเทอมที่สี่เกิดจากความเร่งเชิงมุมของ $K'$ เทียบกับ $K$

## สมการอื่นๆ

สมการนาเวียร์–สโตกส์ (Navier–Stokes equations) คือข้อความที่ระบุสมดุลของโมเมนตัมอย่างเคร่งครัด เพื่ออธิบายการไหลของของไหลอย่างสมบูรณ์ จำเป็นต้องมีข้อมูลเพิ่มมากขึ้น ขึ้นอยู่กับสมมติฐานที่ทำไว้ ข้อมูลเพิ่มเติมนี้สามารถรวมถึงข้อมูลขอบเขต ([ไม่ลื่น](https://en.wikipedia.org/wiki/no-slip_condition), [พื้นผิวความตึงผิว](https://en.wikipedia.org/wiki/capillary_surface), ฯลฯ), การอนุรักษ์มวล, [สมดุลของพลังงาน](https://en.wikipedia.org/wiki/First_law_of_thermodynamics_%28fluid_mechanics%29), และ/หรือ [สมการสถานะ](https://en.wikipedia.org/wiki/equation_of_state)

### สมการความต่อเนื่องของของไหลที่ไม่สามารถอัดได้

ไม่ว่าจะสมมติฐานเกี่ยวกับกระแสอย่างไร การกล่าวถึง [การอนุรักษ์มวล](https://en.wikipedia.org/wiki/conservation_of_mass) โดยทั่วไปก็มีความจำเป็น สิ่งนี้บรรลุได้ผ่านสมการ [ความต่อเนื่องของมวล](https://en.wikipedia.org/wiki/continuity_equation) ตามที่กล่าวไว้ข้างต้นในส่วน "สมการต่อเนื่องทั่วไป" ภายในบทความนี้ ดังนี้:

$$
\begin{align}
\frac{\mathbf{D}m}{{\mathbf{Dt}}}&={\iiint\limits_V}\left({\frac{\mathbf{D}\rho}{{\mathbf{Dt}}} + \rho (\nabla \cdot \mathbf{u})}\right)dV \\
\frac{\mathbf{D}\rho}{{\mathbf{Dt}}} + \rho (\nabla \cdot{\mathbf{u}})&=\frac{\partial\rho}{\partial t} + ({\nabla \rho}) \cdot{\mathbf{u}} + {\rho}(\nabla \cdot \mathbf{u})= \frac{\partial\rho}{\partial t} + \nabla\cdot({\rho \mathbf{u}})= 0
\end{align}
$$

สื่อของไหลซึ่งมีความหนาแน่น [ความหนาแน่น](https://en.wikipedia.org/wiki/density) คงที่ เรียกว่า [*ไม่บีบอัดได้*](https://en.wikipedia.org/wiki/Incompressible_flow) ดังนั้น อัตราการเปลี่ยนแปลงของ $\rho$ เทียบกับเวลา $\frac{\partial\rho}{\partial t}$ และ [เกรเดียนต์](https://en.wikipedia.org/wiki/gradient) ของความหนาแน่น $\nabla \rho$ จึงมีค่าเท่ากับศูนย์ ในกรณีนี้สมการความต่อเนื่องทั่วไป $\frac{\partial\rho}{\partial t} + \nabla\cdot({\rho \mathbf{u}})= 0$ จะลดรูปเป็น:

$$
\rho(\nabla{\cdot}{\mathbf{u}}) = 0
$$

นอกจากนี้ การสมมติว่า $\rho \neq 0$ หมายความว่า ด้านขวาของสมการ (ศูนย์) นั้นหารด้วย [ความหนาแน่น](https://en.wikipedia.org/wiki/density) $\rho$ ลงตัว ดังนั้น สมการความต่อเนื่องสำหรับ [ของไหลที่ไม่สามารถอัดแน่นได้](https://en.wikipedia.org/wiki/Incompressible_flow) จึงลดรูปลงไปอีกเป็น:

$$
(\nabla{\cdot{\mathbf{u}}}) = 0
$$

ความสัมพันธ์นี้ $(\nabla{\cdot{\mathbf{u}}}) = 0$ บ่งชี้ว่า [ไดเวอร์เจนซ์](https://en.wikipedia.org/wiki/divergence) ของเวกเตอร์ความเร็วการไหล [เวกเตอร์](https://en.wikipedia.org/wiki/Vector_field) $\mathbf{u}$ เท่ากับศูนย์ ซึ่งหมายความว่า สำหรับของไหลที่ไม่สามารถอัดแน่นได้ [ของไหลที่ไม่สามารถอัดได้](https://en.wikipedia.org/wiki/Incompressible_flow) สนามความเร็วการไหล [สนามความเร็วการไหล](https://en.wikipedia.org/wiki/Flow_velocity) เป็นสนามเวกเตอร์แบบโซเลนอยด์ [สนามเวกเตอร์โซลีนอยด์](https://en.wikipedia.org/wiki/solenoidal_vector_field) หรือสนามเวกเตอร์ที่ไม่มีไดเวอร์เจนซ์ [สนามเวกเตอร์ที่ไดเวอร์เจนซ์เป็นศูนย์](https://en.wikipedia.org/wiki/Divergence-free) โปรดทราบว่าความสัมพันธ์นี้สามารถขยายเพิ่มเติมได้เนื่องจากความโดดเด่นของมันด้วยตัวดำเนินการลาปลาซแบบเวกเตอร์ [ตัวดำเนินการลาปลาซเวกเตอร์](https://en.wikipedia.org/wiki/vector_Laplace_operator) $\nabla ^{2} \mathbf{u} =\nabla (\nabla \cdot \mathbf{u} )-\nabla \times (\nabla \times \mathbf{u} )$ และ [วอร์ติซิตี](https://en.wikipedia.org/wiki/vorticity) $\boldsymbol \omega = \nabla \times \mathbf{u}$ ซึ่งตอนนี้แสดงออกมาดังนี้ สำหรับของไหลที่ไม่สามารถอัดแน่นได้ [ของไหลที่ไม่สามารถอัดได้](https://en.wikipedia.org/wiki/Incompressible_flow):

$$
\nabla ^{2}\mathbf {u} = - \bigl(\nabla \times (\nabla \times \mathbf {u} )\bigr) = - (\nabla \times \boldsymbol \omega)
$$

## ฟังก์ชันกระแสของของไหล 2 มิติที่ไม่สามารถอัดได้

การหา [เคิร์ล](https://en.wikipedia.org/wiki/Curl_%28mathematics%29) ของสมการนาเวียร์–สโตกส์ที่ไม่สามารถอัดตัวได้ ทำให้เกิดผลในการกำจัดความดัน สิ่งนี้เห็นได้ชัดเจนเป็นพิเศษหากสมมติว่ามีการไหลแบบคาร์ทีเซียน 2 มิติ (เช่น ในกรณี 3 มิติที่เสื่อมสภาพโดยมี $u_z = 0$ และไม่มีสิ่งใดขึ้นอยู่กับ $z$) ซึ่งสมการจะลดลงเหลือ:

$$
\begin{align}
 \rho \left(\frac{\partial u_x}{\partial t} + u_x \frac{\partial u_x}{\partial x} + u_y \frac{\partial u_x}{\partial y}\right)
 &= -\frac{\partial p}{\partial x} + \mu \left(\frac{\partial^2 u_x}{\partial x^2} + \frac{\partial^2 u_x}{\partial y^2}\right) + \rho g_x \\
 \rho \left(\frac{\partial u_y}{\partial t} + u_x \frac{\partial u_y}{\partial x} + u_y \frac{\partial u_y}{\partial y}\right)
 &= -\frac{\partial p}{\partial y} + \mu \left(\frac{\partial^2 u_y}{\partial x^2} + \frac{\partial^2 u_y}{\partial y^2}\right) + \rho g_y.
\end{align}
$$

การหาอนุพันธ์ของสมการแรกเทียบกับ $y$ และสมการที่สองเทียบกับ $x$ แล้วนำสมการที่ได้มาลบกัน จะทำให้แรงดันและแรง [อนุรักษ์](https://en.wikipedia.org/wiki/conservative_force) หายไป
สำหรับของไหลอัดตัวไม่ได้ นิยาม [ฟังก์ชันกระแส](https://en.wikipedia.org/wiki/stream_function) $\psi$ ผ่าน

$$
u_x = \frac{\partial \psi}{\partial y}; \quad u_y = -\frac{\partial \psi}{\partial x}
$$

นำไปสู่ความต่อเนื่องของมวลที่สอดคล้องกับเงื่อนไขโดยไม่มีเงื่อนไข (โดยกำหนดให้ฟังก์ชันกระแสไหลเป็นความต่อเนื่อง) และจากนั้นสมการอนุรักษ์โมเมนตัมแบบนิวตัน 2 มิติที่ไม่สามารถอัดแน่นได้และการอนุรักษ์มวลจะรวมกันเป็นสมการเดียว:

$$
\frac{\partial}{\partial t}\left(\nabla^2 \psi\right) + \frac{\partial \psi}{\partial y} \frac{\partial}{\partial x}\left(\nabla^2 \psi\right) - \frac{\partial \psi}{\partial x} \frac{\partial}{\partial y}\left(\nabla^2 \psi\right) = \nu \nabla^4 \psi
$$

ซึ่ง $\nabla^4$ คือ[ตัวดำเนินการไบฮาร์มอนิก](https://en.wikipedia.org/wiki/biharmonic_operator)สองมิติ และ $\nu$ คือ[ความหนืดจลนศาสตร์](https://en.wikipedia.org/wiki/kinematic_viscosity) โดย $\nu = \frac{\mu}{\rho}$ เราสามารถแสดงสิ่งนี้ได้อย่างกระชับโดยใช้[ดีเทอร์มิแนนตของเจคอบีอัน](https://en.wikipedia.org/wiki/Jacobian_matrix_and_determinant):

$$
\frac{\partial}{\partial t}\left(\nabla^2 \psi\right) + \frac{\partial\left(\psi, \nabla^2\psi \right)}{\partial(y,x)} = \nu \nabla^4 \psi.
$$

สมการเดียวนี้ร่วมกับเงื่อนไขขอบเขตที่เหมาะสมอธิบายการไหลของของไหล 2 มิติ โดยพิจารณาเฉพาะความหนืดจลนศาสตร์เป็นพารามิเตอร์ โปรดทราบว่าสมการสำหรับ [การไหลแบบคืบ](https://en.wikipedia.org/wiki/creeping_flow) จะได้มาเมื่อสมมติว่าด้านซ้ายเป็นศูนย์

In [สมมาตรตามแกน](https://en.wikipedia.org/wiki/axisymmetric) flow ฟังก์ชันศักย์กระแสอีกแบบหนึ่ง ซึ่งเรียกว่า [ฟังก์ชันกระแสสโตกส์](https://en.wikipedia.org/wiki/Stokes_stream_function) สามารถนำมาใช้เพื่ออธิบายองค์ประกอบความเร็วของการไหลแบบอัดตัวไม่ได้ด้วยฟังก์ชัน [สเกลาร์](https://en.wikipedia.org/wiki/scalar_%28mathematics%29) เพียงหนึ่งฟังก์ชัน

สมการนาเวียร์–สโตกส์แบบอัดตัวไม่ได้ (incompressible Navier–Stokes equation) คือ [สมการเชิงอนุพันธ์พีชคณิต](https://en.wikipedia.org/wiki/differential_algebraic_equation) ซึ่งมีลักษณะที่ไม่สะดวกคือไม่มีกลไกที่ชัดเจนสำหรับการนำความดันไปข้างหน้าในเวลา ดังนั้นจึงมีการทุ่มเทความพยายามอย่างมากเพื่อขจัดความดันออกจากกระบวนการคำนวณทั้งหมดหรือบางส่วน การกำหนดฟังก์ชันกระแส (stream function formulation) จะขจัดความดันออกไปได้ แต่ทำได้เพียงในสองมิติและต้องแลกกับการแนะนำอนุพันธ์อันดับสูงกว่าและการกำจัดความเร็วซึ่งเป็นตัวแปรหลักที่สนใจ

## คุณสมบัติ

### ความไม่เชิงเส้น

สมการนาเวียร์–สโตกส์ (Navier–Stokes equations) คือ[สมการเชิงอนุพันธ์ย่อย](https://en.wikipedia.org/wiki/partial_differential_equations)แบบ[ไม่เชิงเส้น](https://en.wikipedia.org/wiki/Nonlinearity) ในกรณีทั่วไป และดังนั้นจึงยังคงเป็นสมการดังกล่าวในเกือบทุกสถานการณ์จริง[^26] [^27] ในบางกรณี เช่น การไหลในหนึ่งมิติและ[การไหลแบบสโตกส์](https://en.wikipedia.org/wiki/Stokes_flow) (หรือการไหลแบบคืบ) สมการสามารถลดรูปเป็นสมการเชิงเส้นได้ ความไม่เชิงเส้นทำให้ปัญหาส่วนใหญ่ยากหรือเป็นไปไม่ได้ที่จะแก้ และเป็นสาเหตุหลักของ[ความปั่นป่วน](https://en.wikipedia.org/wiki/turbulence) ที่สมการแบบจำลองนั้นอธิบาย

ความไม่เป็นเชิงเส้นเกิดจาก[การเร่งความเร็วแบบพาความร้อน](https://en.wikipedia.org/wiki/convective)[^28] ซึ่งเป็นการเร่งความเร็วที่เกี่ยวข้องกับการเปลี่ยนแปลงของความเร็วตามตำแหน่ง ดังนั้นการไหลแบบพาความร้อนไม่ว่าจะเป็นแบบปั่นป่วนหรือไม่ก็ตาม จะมีความไม่เป็นเชิงเส้นเกี่ยวข้อง ตัวอย่างของการไหลแบบพาความร้อนแต่เป็นแบบ[ลามินาร์](https://en.wikipedia.org/wiki/laminar_flow) (ไม่ปั่นป่วน) ก็คือ การไหลของของเหลวที่มีความหนืด (เช่น น้ำมัน) ผ่าน[หัวฉีด](https://en.wikipedia.org/wiki/nozzle)แบบลู่เข้าขนาดเล็ก การไหลดังกล่าวไม่ว่าจะสามารถแก้สมการได้อย่างแม่นยำหรือไม่ ก็สามารถศึกษาและเข้าใจได้อย่างละเอียดและรอบคอบ

### ความปั่นป่วน

[ความปั่นป่วน](https://en.wikipedia.org/wiki/Turbulence) คือพฤติกรรมที่เปลี่ยนแปลงตามเวลาซึ่งมี[ความยุ่งเหยิง](https://en.wikipedia.org/wiki/Chaos_theory)ที่พบในกระแสของไหลจำนวนมาก โดยทั่วไปเชื่อว่าเกิดจาก[ความเฉื่อย](https://en.wikipedia.org/wiki/inertia)ของของไหลโดยรวม: จุดสูงสุดของการเร่งความเร็วที่เปลี่ยนแปลงตามเวลาและการเร่งความเร็วแบบพา; ดังนั้นกระแสที่ผลของความเฉื่อยมีน้อยจึงมีแนวโน้มที่จะเป็นแบบลามินาร์ ([เลขเรย์โนลด์ส](https://en.wikipedia.org/wiki/Reynolds_number)วัดว่ากระแสได้รับผลกระทบจากความเฉื่อยมากน้อยเพียงใด) โดยเชื่อว่าสมการนาเวียร์–สโตกส์อธิบายความปั่นป่วนได้อย่างถูกต้อง แต่ยังไม่ทราบด้วยความแน่นอน[^29]

การแก้สมการนาเวียร์–สโตกส์เชิงตัวเลขสำหรับการไหลแบบปั่นป่วนนั้นยากมาก และเนื่องจากมีสเกลความยาวของการผสมที่แตกต่างกันอย่างมีนัยสำคัญที่เกี่ยวข้องกับการไหลแบบปั่นป่วน การหาคำตอบที่เสถียรของสิ่งนี้จึงต้องการความละเอียดของตาข่ายที่ละเอียดมากจนทำให้เวลาในการคำนวณไม่สามารถทำได้ในทางปฏิบัติสำหรับการคำนวณหรือ [การจำลองเชิงตัวเลขโดยตรง](https://en.wikipedia.org/wiki/direct_numerical_simulation) การพยายามแก้การไหลแบบปั่นป่วนโดยใช้ตัวแก้แบบลามินาร์มักจะนำไปสู่คำตอบที่ไม่คงที่ตามเวลา ซึ่งล้มเหลวในการลู่เข้าอย่างเหมาะสม เพื่อแก้ปัญหานี้ สมการที่หาค่าเฉลี่ยตามเวลา เช่น [สมการนาเวียร์–สโตกส์ที่หาค่าเฉลี่ยตามรีนอลด์ส](https://en.wikipedia.org/wiki/Reynolds-averaged_Navier%E2%80%93Stokes_equations) (RANS) ซึ่งเสริมด้วยแบบจำลองความปั่นป่วน ถูกนำมาใช้ในแอปพลิเคชัน [พลศาสตร์ของไหลเชิงคำนวณ](https://en.wikipedia.org/wiki/computational_fluid_dynamics) (CFD) เมื่อสร้างแบบจำลองการไหลแบบปั่นป่วน แบบจำลองบางตัวรวมถึงแบบจำลอง [Spalart–Allmaras](https://en.wikipedia.org/wiki/Spalart%E2%80%93Allmaras_turbulence_model), [ $k$– $ω$](https://en.wikipedia.org/wiki/k-omega_turbulence_model), [ $k$– $ε$](https://en.wikipedia.org/wiki/turbulence_kinetic_energy), และ [SST](https://en.wikipedia.org/wiki/SST_%28Menter%27s_Shear_Stress_Transport%29) ซึ่งเพิ่มสมการเพิ่มเติมหลายอย่างเพื่อทำให้สมการ RANS ปิดสมบูรณ์ [การจำลองกระแสวนขนาดใหญ่](https://en.wikipedia.org/wiki/Large_eddy_simulation) (LES) ยังสามารถใช้เพื่อแก้สมการเหล่านี้เชิงตัวเลขได้ด้วย แนวทางนี้ใช้ทรัพยากรการคำนวณมากกว่า—ทั้งในแง่ของเวลาและในหน่วยความจำของคอมพิวเตอร์—กว่า RANS แต่ให้ผลลัพธ์ที่ดีกว่าเพราะมันแก้ปัญหาขนาดใหญ่ของความปั่นป่วนอย่างชัดเจน

### ความเหมาะสม

พร้อมสมการเสริม (เช่น การอนุรักษ์มวล) และเงื่อนไขขอบเขตที่จัดวางอย่างเหมาะสม สมการนาเวียร์–สโตกส์ ดูเหมือนจะจำลองการเคลื่อนที่ของของไหลได้อย่างแม่นยำ; แม้กระทั่งการไหลแบบปั่นป่วนก็ดูเหมือน (โดยเฉลี่ย) จะสอดคล้องกับการสังเกตการณ์ในโลกแห่งความเป็นจริง

สมการนาเวียร์–สโตกส์ (Navier–Stokes equations) ถือว่าของไหลที่กำลังศึกษาอยู่เป็น [สสารต่อเนื่อง](https://en.wikipedia.org/wiki/Continuum_mechanics) (สามารถแบ่งย่อยได้ไม่สิ้นสุดและไม่ประกอบด้วยอนุภาคเช่นอะตอมหรือโมเลกุล) และไม่ได้เคลื่อนที่ด้วยความเร็ว [สัมพัทธภาพ](https://en.wikipedia.org/wiki/Relativistic_velocity) ที่ระดับขนาดที่เล็กมากหรือภายใต้สภาวะสุดขั้ว ของไหลจริงที่ประกอบด้วยโมเลกุลแบบไม่ต่อเนื่องจะสร้างผลลัพธ์ที่แตกต่างจากของไหลแบบต่อเนื่องที่ถูกจำลองโดยสมการนาเวียร์–สโตกส์ ตัวอย่างเช่น [ความตึงผิว](https://en.wikipedia.org/wiki/capillarity) ของชั้นภายในในของไหลปรากฏขึ้นในกระแสไหลที่มีความชันสูง.[^30] สำหรับ [เลขคานูเดน](https://en.wikipedia.org/wiki/Knudsen_number) ของปัญหาที่มีค่ามาก [สมการโบลต์ซมันน์](https://en.wikipedia.org/wiki/Boltzmann_equation) อาจเป็นทางเลือกที่เหมาะสม.[^31] หากทำไม่ได้ ก็อาจต้องพึ่งพา [พลวัตโมเลกุล](https://en.wikipedia.org/wiki/molecular_dynamics) หรือวิธีการผสมผสานต่างๆ.[^32]

อีกข้อจำกัดอย่างหนึ่งคือธรรมชาติที่ซับซ้อนของสมการเหล่านั้น มีสูตรที่ได้รับการทดสอบมาอย่างยาวนานสำหรับตระกูลของของไหลที่พบบ่อย แต่การนำสมการนาเวียร์–สโตกส์ไปใช้กับตระกูลของของไหลที่ไม่ค่อยพบบ่อยมักจะทำให้เกิดสูตรที่ซับซ้อนมากและมักนำไปสู่ปัญหาการวิจัยที่ยังไม่มีคำตอบ ด้วยเหตุนี้ สมการเหล่านี้จึงมักถูกเขียนขึ้นสำหรับ [ของไหลนิวโตเนียน](https://en.wikipedia.org/wiki/Newtonian_fluid) ซึ่งแบบจำลองความหนืดเป็น [เชิงเส้น](https://en.wikipedia.org/wiki/linear); แบบจำลองทั่วไปอย่างแท้จริงสำหรับการไหลของของไหลชนิดอื่น (เช่น เลือด) นั้นไม่มีอยู่จริง.[^33]

## การนำไปใช้กับปัญหาเฉพาะ

สมการนาเวียร์–สโตกส์ แม้จะเขียนออกมาอย่างชัดเจนสำหรับของไหลเฉพาะก็ตาม มีลักษณะค่อนข้างเป็นนามธรรมโดยทั่วไป และการนำไปประยุกต์ใช้อย่างถูกต้องกับปัญหาเฉพาะอาจมีความหลากหลายมาก สาเหตุส่วนหนึ่งเป็นเพราะมีปัญหาจำนวนมากที่มีความหลากหลายซึ่งสามารถสร้างแบบจำลองได้ ตั้งแต่อย่างง่ายอย่างการกระจายความดันสถิต ไปจนถึงอย่างซับซ้อนอย่าง[การไหลหลายเฟส](https://en.wikipedia.org/wiki/multiphase_flow) ที่ขับเคลื่อนโดย[แรงตึงผิว](https://en.wikipedia.org/wiki/surface_tension)

โดยทั่วไป การนำไปใช้กับปัญหาเฉพาะจะเริ่มจากสมมติฐานบางประการเกี่ยวกับการไหลและการกำหนดเงื่อนไขเริ่มต้น/เงื่อนไขขอบเขต ซึ่งอาจตามด้วยการวิเคราะห์ขนาด [การวิเคราะห์สเกล](https://en.wikipedia.org/wiki/Scale_analysis_%28mathematics%29) เพื่อลดความซับซ้อนของปัญหาต่อไป

<figure style={{"maxWidth": "132px"}}>

![Visualization of (a) parallel flow and (b) radial flow](https://pub-275e30003c354ac0862cc9839e0f952a.r2.dev/docs/math/NSConvection_vectorial.svg.png)

<figcaption>

ภาพแสดง **(a)** การไหลแบบขนาน และ **(b)** การไหลแบบรัศมี

</figcaption>

</figure>

### การไหลแบบขนาน

สมมติว่ามีการไหลแบบคงที่ ขนานกัน มีหนึ่งมิติ และถูกขับเคลื่อนด้วยแรงดันโดยไม่มีพาความร้อนระหว่างแผ่นขนานกัน ปัญหาขอบเขตแบบปรับขนาด (ไม่มีมิติ) [ปัญหาขอบเขต](https://en.wikipedia.org/wiki/boundary_value_problem) ที่ได้คือ:

$$
\frac{\mathrm{d}^2 u}{\mathrm{d} y^2} = -1; \quad u(0) = u(1) = 0.
$$

เงื่อนไขขอบเขตคือ [เงื่อนไขไม่ไถล](https://en.wikipedia.org/wiki/no_slip_condition) ปัญหาข้อนี้สามารถแก้ได้ง่ายสำหรับสนามการไหล:

$$
u(y) = \frac{y - y^2}{2}.
$$

จากจุดนี้ไป สามารถหาปริมาณที่น่าสนใจอื่นๆ ได้ง่ายขึ้น เช่น แรงต้านความหนืดหรืออัตราการไหลสุทธิ

### ไหลแบบรัศมี

ปัญหาอาจเกิดขึ้นเมื่อปัญหานั้นซับซ้อนขึ้นเล็กน้อย การบิดเบือนที่ดูเหมือนเรียบง่ายของการไหลแบบขนานข้างต้นคือ *การไหลแบบรัศมี* ระหว่างแผ่นขนาน ซึ่งเกี่ยวข้องกับการพาความร้อนและดังนั้นจึงมีความไม่เป็นเชิงเส้น สนามความเร็วสามารถแสดงได้ด้วยฟังก์ชัน $f(z)$ ที่ต้องสอดคล้องกับ:

$$
\frac{\mathrm{d}^2 f}{\mathrm{d} z^2} + R f^2 = -1; \quad f(-1) = f(1) = 0.
$$

[สมการเชิงอนุพันธ์สามัญ](https://en.wikipedia.org/wiki/ordinary_differential_equation)[^34] คือสิ่งที่ได้เมื่อเขียนสมการนาเวียร์–สโตกส์ (Navier–Stokes equations) และใช้สมมติฐานการไหล (flow assumptions) (นอกจากนี้ยังแก้หาความชันความดัน (pressure gradient) ด้วย) เทอม[ไม่เชิงเส้น](https://en.wikipedia.org/wiki/Nonlinearity)[^34] ทำให้เป็นปัญหาที่ยากมากในการแก้เชิงวิเคราะห์ (อาจหาผลเฉลยแบบ[นัย](https://en.wikipedia.org/wiki/Implicit_function)ยาวๆ ได้ซึ่งเกี่ยวข้องกับ[อินทิกรัลวงรี](https://en.wikipedia.org/wiki/elliptic_integral) และ[รากของพหุนามกำลังสาม](https://en.wikipedia.org/wiki/Cubic_formula)) ปัญหาเกี่ยวกับความเป็นจริงของการมีอยู่ของผลเฉลยเกิดขึ้นเมื่อ $R > 1.41$ (โดยประมาณ; สิ่งนี้ไม่ใช่[รากที่สองของ 2](https://en.wikipedia.org/wiki/square_root_of_2)) พารามิเตอร์ $R$ คือเลขเรย์โนลด์ส โดยมีสเกลที่เลือกอย่างเหมาะสม นี่เป็นตัวอย่างของการที่สมมติฐานการไหลสูญเสียความเหมาะสม และเป็นตัวอย่างของความยากในการไหลที่มีเลขเรย์โนลด์สสูง

### การพาความร้อน

รูปแบบการพาความร้อนแบบธรรมชาติชนิดหนึ่งที่สามารถอธิบายได้ด้วยสมการนาเวียร์–สโตกส์ คือ [การพาความร้อนแบบเรย์เลห์–เบนาร์](https://en.wikipedia.org/wiki/Rayleigh%E2%80%93B%C3%A9nard_convection) เป็นหนึ่งในปรากฏการณ์การพาความร้อนที่ถูกศึกษาอย่างแพร่หลายมากที่สุด เนื่องจากสามารถเข้าถึงได้ทั้งในเชิงทฤษฎีและการทดลอง

## วิธีแก้ที่แน่นอนของสมการนาเวียร์–สโตกส์

มีคำตอบที่แน่นอนบางประการของสมการนาเวียร์–สโตกส์ (Navier–Stokes equations) ที่ปรากฏอยู่ ตัวอย่างของกรณีเสื่อมสภาพ—โดยที่พจน์ไม่เชิงเส้นในสมการนาเวียร์–สโตกส์มีค่าเท่ากับศูนย์—ได้แก่ [การไหลแบบปัวซอยย์](https://en.wikipedia.org/wiki/Hagen-Poiseuille_equation), [การไหลแบบคูเอตต์](https://en.wikipedia.org/wiki/Couette_flow) และชั้นขอบเขตสโตกส์แบบแกว่งกวัด [ชั้นขอบเขตสโตกส์](https://en.wikipedia.org/wiki/Stokes_boundary_layer) แต่ยังมีตัวอย่างที่น่าสนใจยิ่งขึ้น ซึ่งเป็นการแก้สมการไม่เชิงเส้นแบบสมบูรณ์ที่มีอยู่ เช่น [การไหลแบบเจฟฟรีย์–ฮาเมล](https://en.wikipedia.org/wiki/Jeffery%E2%80%93Hamel_flow), [การไหลแบบหมุนวนฟอน คาร์มาน](https://en.wikipedia.org/wiki/Von_K%C3%A1rm%C3%A1n_swirling_flow), [การไหลที่จุดหยุดนิ่ง](https://en.wikipedia.org/wiki/stagnation_point_flow), [เจ็ตลันเดา–สไควร์](https://en.wikipedia.org/wiki/Landau%E2%80%93Squire_jet) และ [วอร์เท็กซ์เทย์เลอร์–กรีน](https://en.wikipedia.org/wiki/Taylor%E2%80%93Green_vortex)[^35] [^36] [^37] สามารถกำหนด[คำตอบแบบคล้ายตัวเอง](https://en.wikipedia.org/wiki/Self-similar_solution)ตามเวลา ของสมการนาเวียร์–สโตกส์แบบอัดตัวไม่ได้ในสามมิติในระบบพิกัดคาร์ทีเซียน ได้ด้วยความช่วยเหลือของ[ฟังก์ชันคัมเมอร์](https://en.wikipedia.org/wiki/Kummer%27s_function)ที่มีอาร์กิวเมนต์เป็นกำลังสอง[^38] สำหรับสมการนาเวียร์–สโตกส์แบบอัดตัวได้ คำตอบแบบคล้ายตัวเองตามเวลาจะเป็น[ฟังก์ชันวิทแทคเกอร์](https://en.wikipedia.org/wiki/Whittaker_function)อีกเช่นกันที่มีอาร์กิวเมนต์เป็นกำลังสองเมื่อใช้ [โพลีทรอปิก](https://en.wikipedia.org/wiki/Polytrope) [สมการสถานะ](https://en.wikipedia.org/wiki/equation_of_state) เป็นเงื่อนไขปิด[^39] โปรดทราบว่าความมีอยู่ของคำตอบที่แน่นอนเหล่านี้ไม่ได้หมายความว่าพวกมันจะเสถียร: ความปั่นป่วนอาจเกิดขึ้นที่เลขเรย์โนลด์สที่สูงกว่า

ภายใต้สมมติฐานเพิ่มเติม ส่วนประกอบต่างๆ สามารถแยกออกจากกันได้.[^40]

### คำตอบของกระแสวนในสถานะคงที่สามมิติ

<figure style={{"maxWidth": "250px"}}>

![Wire model of flow lines along a Hopf fibration](https://pub-275e30003c354ac0862cc9839e0f952a.r2.dev/docs/math/Hopfkeyrings.jpg)

<figcaption>

แบบจำลองเส้นลวดของเส้นทางการไหลตาม [การไฟเบรชันฮอปฟ์](https://en.wikipedia.org/wiki/Hopf_fibration)

</figcaption>

</figure>
ตัวอย่างสถานะคงที่ที่ไม่มีเอกฐานเกิดขึ้นจากการพิจารณาการไหลตามเส้นของ [การไฟเบรชันฮอปฟ์](https://en.wikipedia.org/wiki/Hopf_fibration) ให้ $r$ เป็นรัศมีคงที่ของขดลวดภายใน ชุดหนึ่งของการเฉลยกำหนดโดย:[^41]

$$
\begin{align}
\rho(x, y, z) &= \frac{3B}{r^2 + x^2 + y^2 + z^2} \\
p(x, y, z) &= \frac{-A^2B}{\left(r^2 + x^2 + y^2 + z^2\right)^3} \\
\mathbf{u}(x, y, z) &= \frac{A}{\left(r^2 + x^2 + y^2 + z^2\right)^2}\begin{pmatrix} 2(-ry + xz) \\ 2(rx + yz) \\ r^2 - x^2 - y^2 + z^2 \end{pmatrix} \\
g &= 0 \\
\mu &= 0
\end{align}
$$

สำหรับค่าคงที่ใดๆ $A$ และ $B$ นี่คือคำตอบในก๊าซที่ไม่มีความหนืด (ของไหลที่บีบอัดได้) ซึ่งความหนาแน่น ความเร็ว และความดันจะลดลงเป็นศูนย์เมื่ออยู่ห่างจากจุดกำเนิด (โปรดทราบว่านี่ไม่ใช่คำตอบของปัญหาพันปีของ Clay เพราะสิ่งนั้นหมายถึงของไหลที่ไม่สามารถบีบอัดได้โดยที่ $\rho$ เป็นค่าคงที่ และสิ่งนี้ก็ไม่เกี่ยวข้องกับความเป็นเอกลักษณ์ของสมการนาเวียร์–สโตกส์ (Navier–Stokes equations) ในด้านคุณสมบัติใดๆ [ความปั่นป่วน](https://en.wikipedia.org/wiki/turbulence) ด้วย) นอกจากนี้ยังควรชี้ให้เห็นว่าองค์ประกอบของเวกเตอร์ความเร็วนั้นตรงกับพารามิเตอร์จาก [สี่เหลี่ยมผืนผ้าแบบพิทาโกรัส](https://en.wikipedia.org/wiki/Pythagorean_quadruple) อย่างแม่นยำ การเลือกความหนาแน่นและความดันอื่นๆ ก็เป็นไปได้ด้วยสนามความเร็วเดียวกัน:

### คำตอบคาบสามมิติที่มีความหนืด

ตัวอย่างของคำตอบที่มีความหนืดแบบเต็มสามมิติที่เป็นคาบสองตัวอย่างนั้นได้บรรยายไว้แล้ว.[^42]
คำตอบเหล่านี้ถูกนิยามบน[ทอรัส](https://en.wikipedia.org/wiki/torus)สามมิติ $\mathbb{T}^3 = \mathbb{R}^3/{L\mathbb{Z}^3}$ และถูกกำหนดลักษณะโดย[ความเฮลิซิตี](https://en.wikipedia.org/wiki/hydrodynamical_helicity)ที่เป็นบวกและลบตามลำดับ
คำตอบที่มีความเฮลิซิตีเป็นบวกนั้นกำหนดให้ดังนี้:

$$
\begin{align}
u_x &= \frac{4 \sqrt{2}}{3 \sqrt{3}} \, U_0 \left[\, \sin\left(k x - \frac\pi 3\right) \cos\left(k y + \frac\pi 3\right) \sin\left(k z + \frac\pi 2\right) - \cos\left(k z - \frac\pi 3\right) \sin\left(k x + \frac\pi 3\right) \sin\left(k y + \frac\pi 2\right) \,\right]  e^{-3 \nu k^2 t} \\
u_y &= \frac{4 \sqrt{2}}{3 \sqrt{3}} \, U_0 \left[\, \sin\left(k y - \frac\pi 3\right) \cos\left(k z + \frac\pi 3\right) \sin\left(k x + \frac\pi 2\right) - \cos\left(k x - \frac\pi 3\right) \sin\left(k y + \frac\pi 3\right) \sin\left(k z +\frac\pi 2\right) \,\right]  e^{-3 \nu k^2 t} \\
u_z &= \frac{4 \sqrt{2}}{3 \sqrt{3}} \, U_0 \left[\, \sin\left(k z - \frac\pi 3\right) \cos\left(k x + \frac\pi 3\right) \sin\left(k y + \frac\pi 2\right) - \cos\left(k y - \frac\pi 3\right) \sin\left(k z + \frac\pi 3\right) \sin\left(k x + \frac\pi 2\right) \,\right]  e^{-3 \nu k^2 t}
\end{align}
$$

โดยที่ $k = 2 \pi/L$ คือเลขคลื่น และองค์ประกอบของความเร็วถูกทำให้เป็นมาตรฐานเพื่อให้พลังงานจลน์เฉลี่ยต่อหน่วยมวลเท่ากับ $U_0^2/2$ ที่ $t = 0$
สนามความดันได้มาจากสนามความเร็วเป็น $p = p_0 - \rho_0 \| \boldsymbol{u} \|^2/2$ (โดยที่ $p_0$ และ $\rho_0$ เป็นค่าอ้างอิงสำหรับสนามความดันและสนามความหนาแน่นตามลำดับ)
เนื่องจากทั้งคำตอบทั้งสองอยู่ในชั้นของ [การไหลแบบเบลทรามี](https://en.wikipedia.org/wiki/Beltrami_flow) สนามความหมุนจึงขนานกับความเร็วและสำหรับกรณีที่มีเฮลิซิตีเป็นบวกจะได้เป็น $\omega =\sqrt{3} \, k \, \boldsymbol{u}$
คำตอบเหล่านี้สามารถพิจารณาได้ว่าเป็นการขยายผลในสามมิติของ [วอร์เท็กซ์เทย์เลอร์–กรีน](https://en.wikipedia.org/wiki/Taylor%E2%80%93Green_vortex) แบบคลาสสิกในสองมิติ

### ประกาศของ OpenAI

วันที่ 8 กันยายน 2026 บริษัท [ปัญญาประดิษฐ์](https://en.wikipedia.org/wiki/artificial_intelligence) ชื่อ [OpenAI](https://en.wikipedia.org/wiki/OpenAI) ได้ประกาศว่าพวกเขาได้แก้ [ปัญหารางวัลมิลเลนเนียม](https://en.wikipedia.org/wiki/Millennium_Prize_Problems) เกี่ยวกับ [การมีอยู่และความเรียบของสมการนาเวียร์–สโตกส์แบบอัดไม่ได้](https://en.wikipedia.org/wiki/Navier%E2%80%93Stokes_existence_and_smoothness) equations ใน [ปริภูมิยูคลิดสามมิติ](https://en.wikipedia.org/wiki/Three-dimensional_space)[^43] [^44] OpenAI ระบุว่าคำตอบของปัญหานี้ซึ่งเป็นการยกตัวอย่างค้านที่อ้างถึงข้อความ C และ D ของข้อความปัญหา[^45] นั้นถูกพัฒนาโดยนักวิจัยของพวกเขาโดยใช้ [เอเจนต์](https://en.wikipedia.org/wiki/AI_agent) ที่ประสานงานกันจำนวน多达 10,000 ตัวที่รัน [แบบจำลองแนวหน้า](https://en.wikipedia.org/wiki/frontier_model) ภายใน พร้อมกับมีการทำให้เป็นรูปธรรมใน [Lean](https://en.wikipedia.org/wiki/Lean_%28proof_assistant%29) proof assistant การอ้างสิทธิ์นี้ยังไม่ได้รับการยืนยันโดยนักคณิตศาสตร์ภายนอกหรือสถาบันคณิตศาสตร์เคลย์ ในขณะที่ OpenAI ระบุว่าพวกเขาจะไม่อ้างสิทธิ์รางวัล Millennium Prize การประกาศครั้งนี้มาพร้อมกับ [ข้อพิพาทเรื่องสิทธิ์](https://en.wikipedia.org/wiki/Scientific_priority) กับ [Levent Alpöge](https://en.wikipedia.org/wiki/Levent_Alp%C3%B6ge) (ซึ่งทำงานในบริษัท AI คู่แข่ง [แอนโทรปิก](https://en.wikipedia.org/wiki/Anthropic)) และ [Tristan Buckmaster](https://en.wikipedia.org/wiki/Tristan_Buckmaster) ซึ่งได้หาผลที่เกี่ยวข้องกันอย่างใกล้ชิดชุดหนึ่งเกี่ยวกับ [สมการออยเลอร์](https://en.wikipedia.org/wiki/Euler_equations_%28fluid_dynamics%29)[^46] [^47] วิธีการที่ใช้ในการสร้างคำตอบที่อ้างสิทธิ์นั้นสร้างขึ้นจากวิธีการที่พัฒนาโดย Diego Córdoba และ Luis Martínez Zoroa ในปี 2023[^48] เพื่อพิสูจน์ปรากฏการณ์ blowup ในสมการของของไหลที่เกี่ยวข้อง[^49]

## แผนภาพไวลด์

**แผนภาพไวล์ด** (Wyld diagrams) คือกราฟบัญชี [กราฟ](https://en.wikipedia.org/wiki/Graph_%28discrete_mathematics%29) ที่สอดคล้องกับสมการนาเวียร์–สโตกส์ ผ่าน [การขยายแบบรบกวน](https://en.wikipedia.org/wiki/perturbation_theory) ของ [กลศาสตร์ต่อเนื่อง](https://en.wikipedia.org/wiki/continuum_mechanics) คล้ายกับแผนภาพ [ไฟน์แมน](https://en.wikipedia.org/wiki/Feynman_diagram) ใน [ทฤษฎีสนามควอนตัม](https://en.wikipedia.org/wiki/quantum_field_theory) แผนภาพเหล่านี้เป็นการขยายเทคนิคของ [มสตีสลาฟ เคลิดช](https://en.wikipedia.org/wiki/Mstislav_Keldysh) สำหรับกระบวนการที่ไม่อยู่ในสมดุลในพลศาสตร์ของไหล กล่าวโดยย่อ แผนภาพเหล่านี้มอบ [กราฟ](https://en.wikipedia.org/wiki/graph_theory) ให้กับปรากฏการณ์ [ปั่นป่วน](https://en.wikipedia.org/wiki/turbulence) (มักเป็น) ในของไหลปั่นป่วนโดยอนุญาตให้ [อนุภาคของไหลที่สัมพันธ์กัน](https://en.wikipedia.org/wiki/correlation_function) และ [มีอันตรกิริยา](https://en.wikipedia.org/wiki/stochastic_processes) ปฏิบัติตาม [กระบวนการสโตแคสติก](https://en.wikipedia.org/wiki/stochastic_processes) ที่สัมพันธ์กับ [ฟังก์ชัน](https://en.wikipedia.org/wiki/function_%28mathematics%29) [กึ่งสุ่ม](https://en.wikipedia.org/wiki/pseudo-random) ใน [การแจกแจงความน่าจะเป็น](https://en.wikipedia.org/wiki/probability_distribution)[^50]

## การแสดงออกใน 3 มิติ

โปรดทราบว่า สูตรในส่วนนี้ใช้สัญลักษณ์บรรทัดเดียวสำหรับอนุพันธ์ย่อย โดยตัวอย่างเช่น $\partial_x u$ หมายถึงอนุพันธ์ย่อยของ $u$ เทียบกับ $x$ และ $\partial_y^2 f_\theta$ หมายถึงอนุพันธ์ย่อยอันดับสองของ $f_\theta$ เทียบกับ $y$

งานวิจัยปี 2022 ให้วิธีแก้สมการนาเวียร์–สโตกส์ (Navier-Stokes equation) ที่ประหยัดกว่า มีพลวัตและเกิดซ้ำ สำหรับของไหลปั่นป่วน 3 มิติ[^51] ในช่วงเวลาสั้น ๆ ที่เหมาะสม พลวัตของของไหลปั่นป่วนเป็นแบบกำหนดได้

### พิกัดคาร์ทีเซียน

จากแบบทั่วไปของสมการนาเวียร์–สโตกส์ โดยขยายเวกเตอร์ความเร็วเป็น $\mathbf{u} = (u_x, u_y, u_z)$ ซึ่งบางครั้งเรียกตามลำดับว่า $u$, $v$, $w$ เราสามารถเขียนสมการเวกเตอร์ออกมาอย่างชัดเจนได้

$$
\begin{align}
 x:\ &\rho \left({\partial_t u_x} + u_x \, {\partial_x u_x} + u_y \, {\partial_y u_x} + u_z \, {\partial_z u_x}\right) \\
 &\quad= -\partial_x p + \mu \left({\partial_x^2 u_x} + {\partial_y^2 u_x} + {\partial_z^2 u_x}\right) + \frac{1}{3} \mu \  \partial_x \left( {\partial_x u_x} + {\partial_y u_y} + {\partial_z u_z} \right) + \rho g_x \\
\end{align}
$$

$$
\begin{align}
 y:\ &\rho \left({\partial_t u_y} + u_x {\partial_x u_y} + u_y {\partial_y u_y} + u_z {\partial_z u_y}\right) \\
 &\quad= -{\partial_y p} + \mu \left({\partial_x^2 u_y} + {\partial_y^2 u_y} + {\partial_z^2 u_y}\right) + \frac{1}{3} \mu \  \partial_y \left( {\partial_x u_x} + {\partial_y u_y} + {\partial_z u_z} \right) + \rho g_y \\
\end{align}
$$

$$
\begin{align}
 z:\ &\rho \left({\partial_t u_z} + u_x {\partial_x u_z} + u_y {\partial_y u_z} + u_z {\partial_z u_z}\right) \\
 &\quad= -{\partial_z p} + \mu \left({\partial_x^2 u_z} + {\partial_y^2 u_z} + {\partial_z^2 u_z}\right) + \frac{1}{3} \mu \  \partial_z \left( {\partial_x u_x} + {\partial_y u_y} + {\partial_z u_z} \right) + \rho g_z.
\end{align}
$$

โปรดทราบว่าแรงโน้มถ่วงได้รับการพิจารณาว่าเป็นแรงภายนอก และค่าของ $g_x$, $g_y$, $g_z$ จะขึ้นอยู่กับทิศทางของแรงโน้มถ่วงเทียบกับระบบพิกัดที่เลือก

สมการความต่อเนื่องมีดังนี้:

$$
\partial_t \rho + \partial_x (\rho u_x) + \partial_y (\rho u_y) + \partial_z (\rho u_z) = 0.
$$

เมื่อการไหลเป็นของไหลอัดตัวไม่ได้ $\rho$ จะไม่เปลี่ยนแปลงสำหรับอนุภาคของไหลใดๆ และอนุพันธ์เชิงวัสดุ [อนุพันธ์เชิงวัสดุ](https://en.wikipedia.org/wiki/material_derivative) ของมันจะหายไป: $\frac{\mathrm{D} \rho}{\mathrm{D}t} = 0$ สมการความต่อเนื่องถูกลดลงเป็น:

$$
\partial_x u_x + \partial_y u_y + \partial_z u_z = 0.
$$

ดังนั้น สำหรับรูปแบบของสมการนาเวียร์–สโตกส์ที่ไม่สามารถอัดตัวได้ ส่วนที่สองของเทอมความหนืดจะหายไป (ดู [การไหลแบบอัดตัวไม่ได้](https://en.wikipedia.org/wiki/Incompressible_flow))

ระบบสมการสี่สมการนี้ประกอบเป็นรูปแบบที่ใช้บ่อยที่สุดและมีการศึกษามากที่สุด แม้ว่าจะกะทัดรัดกว่าการแสดงออกอื่น ๆ เมื่อเทียบกันแล้ว แต่ระบบนี้ยังคงเป็นระบบ [สมการเชิงอนุพันธ์ย่อย](https://en.wikipedia.org/wiki/partial_differential_equations) แบบ [ไม่เชิงเส้น](https://en.wikipedia.org/wiki/Nonlinearity) ซึ่งการหาคำตอบทำได้ยาก

### พิกัดทรงกระบอก

การเปลี่ยนตัวแปรในสมการคาร์ทีเซียนจะให้สมการโมเมนตัมสำหรับ $r$, $\phi$, และ $z$[^19] [^52]

$$
\begin{align}
 r:\ & \rho \left({\partial_t u_r} + u_r {\partial_r u_r} + \frac{u_\varphi}{r} {\partial_\varphi u_r} + u_z {\partial_z u_r} - \frac{u_\varphi^2}{r}\right) \\
 &\quad = -{\partial_r p} \\
 &\qquad  + \mu \left(\frac{1}{r} \partial_r \left(r {\partial_r u_r}\right) +
                      \frac{1}{r^2} {\partial_\varphi^2 u_r} + {\partial_z^2 u_r} - \frac{u_r}{r^2} -
                      \frac{2}{r^2} {\partial_\varphi u_\varphi} \right) \\
 &\qquad  + \frac{1}{3}\mu \partial_r \left( \frac{1}{r} {\partial_r\left(r u_r\right)} + \frac{1}{r} {\partial_\varphi u_\varphi} + {\partial_z u_z} \right) \\
 &\qquad  + \rho g_r \\[8px]
\end{align}
$$

$$
\begin{align}
 \varphi:\ & \rho \left({\partial_t u_\varphi} + u_r {\partial_r u_\varphi} +
 \frac{u_\varphi}{r} {\partial_\varphi u_\varphi} + u_z {\partial_z u_\varphi} + \frac{u_r u_\varphi}{r} \right) \\
 &\quad = -\frac{1}{r} {\partial_\varphi p} \\
 &\qquad  + \mu \left(\frac{1}{r} \  \partial_r \left(r {\partial_r u_\varphi}\right)
                    + \frac{1}{r^2} {\partial_\varphi^2 u_{\varphi}}
                    + {\partial_z^2 u_{\varphi}} - \frac{u_\varphi}{r^2} + \frac{2}{r^2} {\partial_\varphi u_r}\right) \\
 &\qquad  + \frac{1}{3}\mu \frac{1}{r} \partial_\varphi \left( \frac{1}{r} {\partial_r\left(r u_r\right)} + \frac{1}{r} {\partial_\varphi u_\varphi} + {\partial_z u_z} \right) \\
 &\qquad  + \rho g_\varphi \\[8px]
\end{align}
$$

$$
\begin{align}
 z:\ & \rho \left({\partial_t u_z} + u_r {\partial_r u_z} + \frac{u_\varphi}{r} {\partial_\varphi u_z} +
 u_z {\partial_z u_z}\right) \\
 &\quad = -{\partial_z p} \\
 &\qquad  + \mu \left(\frac{1}{r} \partial_r \left(r {\partial_r u_z}\right)
                    + \frac{1}{r^2} {\partial_\varphi^2 u_z} + {\partial_z^2 u_z}\right) \\
 &\qquad  + \frac{1}{3}\mu \partial_z \left( \frac{1}{r} {\partial_r \left(r u_r\right)}
                                           + \frac{1}{r} {\partial_\varphi u_\varphi} + {\partial_z u_z} \right) \\
 &\qquad  + \rho g_z.
\end{align}
$$

องค์ประกอบความโน้มถ่วงโดยทั่วไปจะไม่ใช่ค่าคงที่ แต่สำหรับการใช้งานส่วนใหญ่แล้ว จะเลือกพิกัดให้ องค์ประกอบความโน้มถ่วงเป็นค่าคงที่ หรือสมมติว่าความโน้มถ่วงถูกต้านทานโดยสนามความดัน (เช่น การไหลในท่อแนวนอนจะได้รับการพิจารณาตามปกติโดยไม่มีแรงโน้มถ่วงและไม่มีเกรเดียนต์ความดันในแนวตั้ง) สมการความต่อเนื่องคือ:

$$
{\partial_t\rho} + \frac{1}{r} \partial_r \left(\rho r u_r\right) + \frac{1}{r} {\partial_\varphi \left(\rho u_\varphi\right)} + {\partial_z \left(\rho u_z\right)} = 0.
$$

การแสดงผลแบบทรงกระบอกของสมการนาเวียร์–สโตกส์ที่ไม่สามารถอัดได้ (incompressible Navier–Stokes equations) นี้เป็นรูปแบบที่พบเห็นได้รองลงมา (อันดับแรกคือแบบคาร์ทีเซียนข้างต้น)¹ เลือกใช้พิกัดทรงกระบอกเพื่อใช้ประโยชน์จากสมมาตร² เพื่อให้ส่วนประกอบของความเร็วสามารถหายไป³ กรณีที่พบบ่อยมากคือกระแสไหลสมมาตรตามแกน (axisymmetric flow) โดยสมมติว่าไม่มีความเร็วสัมผัส ( $u_\phi = 0$) และปริมาณที่เหลือเป็นอิสระจาก $\phi$⁴:

$$
\begin{align}
 \rho \left({\partial_t u_r} + u_r {\partial_r u_r} + u_z {\partial_z u_r}\right)
 &= -{\partial_r p} + \mu \left(\frac{1}{r} \partial_r \left(r {\partial_r u_r}\right) +
 {\partial_z^2 u_r} - \frac{u_r}{r^2}\right) + \rho g_r \\
 \rho \left({\partial_t u_z} + u_r {\partial_r u_z} + u_z {\partial_z u_z}\right)
 &= -{\partial_z p} + \mu \left(\frac{1}{r} \partial_r \left(r {\partial_r u_z}\right) +
 {\partial_z^2 u_z}\right) + \rho g_z \\
 \frac{1}{r} \partial_r\left(r u_r\right) + {\partial_z u_z} &= 0.
\end{align}
$$

### พิกัดทรงกลม

ใน[ระบบพิกัดทรงกลม](https://en.wikipedia.org/wiki/spherical_coordinates) สมการโมเมนตัมของ $r$, $\phi$, และ $\theta$ คือ[^19] (โปรดสังเกตธรรมเนียมที่ใช้: $\theta$ คือมุมขั้ว หรือ[โคแลติจูด](https://en.wikipedia.org/wiki/colatitude),[^53] $0 \leq \theta \leq \pi$):

$$
\begin{align}
 r:\ &\rho \left({\partial_t u_r} + u_r {\partial_r u_r} + \frac{u_\varphi}{r \sin\theta} {\partial_\varphi u_r} +
 \frac{u_\theta}{r} {\partial_\theta u_r} - \frac{u_\varphi^2 + u_\theta^2}{r}\right) \\
 &\quad = -{\partial_r p} \\
 &\qquad  + \mu \left(\frac{1}{r^2} \partial_r \left(r^2 {\partial_r u_r}\right) + \frac{1}{r^2 \sin^2\theta} {\partial_\varphi^2 u_r} + \frac{1}{r^2 \sin\theta} \partial_\theta \left(\sin\theta {\partial_\theta u_r}\right) - 2\frac{u_r + {\partial_\theta u_\theta} + u_\theta \cot\theta}{r^2} - \frac{2}{r^2 \sin\theta} {\partial_\varphi u_\varphi} \right) \\
 &\qquad  + \frac{1}{3}\mu \partial_r \left( \frac{1}{r^2} \partial_r\left(r^2 u_r\right) + \frac{1}{r \sin\theta} \partial_\theta \left( u_\theta\sin\theta \right) + \frac{1}{r\sin\theta} {\partial_\varphi u_\varphi} \right) \\
 &\qquad  + \rho g_r \\[8px]
\end{align}
$$

$$
\begin{align}
 \varphi:\ &\rho \left({\partial_t u_\varphi} + u_r {\partial_r u_\varphi} +
 \frac{u_\varphi}{r \sin\theta} {\partial_\varphi u_\varphi} + \frac{u_\theta}{r} {\partial_\theta u_\varphi} +
 \frac{u_r u_\varphi + u_\varphi u_\theta \cot\theta}{r}\right) \\
 &\quad = -\frac{1}{r \sin\theta} {\partial_\varphi p} \\
 &\qquad  + \mu \left(\frac{1}{r^2} \partial_r \left(r^2 {\partial_r u_\varphi}\right) + \frac{1}{r^2 \sin^2\theta} {\partial_\varphi^2 u_\varphi} + \frac{1}{r^2 \sin\theta} \partial_\theta \left(\sin\theta {\partial_\theta u_\varphi}\right) + \frac{2 \sin\theta {\partial_\varphi u_r} + 2 \cos\theta {\partial_\varphi u_\theta} - u_\varphi}{r^2 \sin^2\theta} \right) \\
 &\qquad  + \frac{1}{3}\mu\frac{1}{r \sin\theta} \partial_\varphi \left( \frac{1}{r^2} \partial_r \left(r^2 u_r\right) + \frac{1}{r \sin\theta} \partial_\theta \left( u_\theta\sin\theta \right) + \frac{1}{r\sin\theta} {\partial_\varphi u_\varphi} \right) \\
 &\qquad  + \rho g_\varphi \\[8px]
\end{align}
$$

$$
\begin{align}
 \theta:\ &\rho \left({\partial_t u_\theta} + u_r {\partial_r u_\theta} +
 \frac{u_\varphi}{r \sin\theta} {\partial_\varphi u_\theta} +
 \frac{u_\theta}{r} {\partial_\theta u_\theta} + \frac{u_r u_\theta - u_\varphi^2 \cot\theta}{r}\right) \\
 &\quad = -\frac{1}{r} {\partial_\theta p} \\
 &\qquad  + \mu \left(\frac{1}{r^2} \partial_r \left(r^2 {\partial_r u_\theta}\right) + \frac{1}{r^2 \sin^2\theta} {\partial_\varphi^2 u_\theta} + \frac{1}{r^2 \sin\theta} \partial_\theta \left(\sin\theta {\partial_\theta u_\theta}\right) + \frac{2}{r^2} {\partial_\theta u_r} - \frac{u_\theta + 2 \cos\theta {\partial_\varphi u_\varphi}}{r^2 \sin^2\theta} \right) \\
 &\qquad  + \frac{1}{3}\mu\frac{1}{r} \partial_\theta \left( \frac{1}{r^2} \partial_r \left(r^2 u_r\right) + \frac{1}{r \sin\theta} \partial_\theta  \left( u_\theta\sin\theta \right) + \frac{1}{r\sin\theta} {\partial_\varphi u_\varphi} \right) \\
 &\qquad  + \rho g_\theta.
\end{align}
$$

ความต่อเนื่องของมวลจะอ่านว่า:

$$
{\partial_t \rho} + \frac{1}{r^2} \partial_r \left(\rho r^2 u_r\right) + \frac{1}{r \sin\theta}{\partial_\varphi (\rho u_\varphi)} + \frac{1}{r \sin\theta} \partial_\theta \left(\sin\theta \rho u_\theta\right) = 0.
$$

สมการเหล่านี้อาจถูกระบุให้กระชับขึ้น (เล็กน้อย) ได้โดยตัวอย่างเช่น การแยกตัวประกอบ $\frac{1}{r^2}$ ออกจากพจน์ความหนืด อย่างไรก็ตาม การทำเช่นนั้นจะเปลี่ยนโครงสร้างของลาปลาเชียนและปริมาณอื่นๆ อย่างไม่พึงประสงค์

## ดูเพิ่มเติม

* [สมการเซนต์-เวอานแตง](https://en.wikipedia.org/wiki/Saint_Venant_equation)
* [ทฤษฎีชาปแมน–เอนสโก](https://en.wikipedia.org/wiki/Chapman%E2%80%93Enskog_theory)
* [สมการChurchill–Bernstein](https://en.wikipedia.org/wiki/Churchill%E2%80%93Bernstein_equation)
* [ปรากฏการณ์Coandă](https://en.wikipedia.org/wiki/Coand%C4%83_effect)
* [วิธีการแก้ไขความดัน](https://en.wikipedia.org/wiki/Pressure-correction_method)
* [สมการพื้นฐาน](https://en.wikipedia.org/wiki/Primitive_equations)
* [ทฤษฎีบทการขนส่งของReynolds](https://en.wikipedia.org/wiki/Reynolds_transport_theorem)

## หมายเหตุ


[^1]: Kline, Morris (1972). *Mathematical Thought from Ancient to Modern Times*. *Oxford University Press*. ISBN 0-19-506136-5.
[^2]: McLean, Doug (2012). *Understanding Aerodynamics: Arguing from the Real Physics*. *John Wiley & Sons*, 13–78. ISBN 978-1-119-96751-4.
[^3]: (March 27, 2017). *Millennium Prize Problems—Navier–Stokes Equation*. *Clay Mathematics Institute*. [Millennium Prize Problems—Navier–Stokes Equation](http://www.claymath.org/millennium-problems/navier%E2%80%93stokes-equation).
[^4]: Fefferman, Charles L.. *Existence and smoothness of the Navier–Stokes equation*. *Clay Mathematics Institute*. [Existence and smoothness of the Navier–Stokes equation](http://www.claymath.org/sites/default/files/navierstokes.pdf).
[^5]: (8 September 2026). *OpenAI says it cracked 90-year-old maths problem in 88 hours*. *BBC News*. [OpenAI says it cracked 90-year-old maths problem in 88 hours](https://www.bbc.co.uk/news/articles/cy7zygy3rl2o).
[^6]: Refer to the mathematical operator [del](https://en.wikipedia.org/wiki/del) represented by the nabla ( $\nabla$) symbol.
[^7]: Batchelor, G. K. (1967). *An Introduction to Fluid Dynamics*. *Cambridge University Press*. ISBN 978-0-521-66396-0, 137 & 142.
[^8]: Batchelor, G. K. (1967). *An Introduction to Fluid Dynamics*. *Cambridge University Press*. ISBN 978-0-521-66396-0, 142–148.
[^9]: Chorin, Alexandre E.; Marsden, Jerrold E. (1993). *A Mathematical Introduction to Fluid Mechanics*. 33.
[^10]: Bird, Stewart, Lightfoot, Transport Phenomena, 1st ed., 1960, eq. (3.2-11a).
[^11]: Batchelor, G. K. (1967). *An Introduction to Fluid Dynamics*. *Cambridge University Press*. ISBN 978-0-521-66396-0, 165.
[^12]: Landau, Lev Davidovich, and Evgenii Mikhailovich Lifshitz. Fluid mechanics: Landau And Lifshitz: course of theoretical physics, Volume 6. Vol. 6. Elsevier, 2013.
[^13]: Landau, L. D.; Lifshitz, E. M. (1987). *Fluid mechanics*. *Pergamon Press* **[Course of Theoretical Physics](https://en.wikipedia.org/wiki/Course_of_Theoretical_Physics) Volume 6**. ISBN 978-0-08-033932-0, 44–45, 196.
[^14]: White, Frank M. (2006). *Viscous Fluid Flow*. *McGraw-Hill*. ISBN 978-0-07-124493-0, 67.
[^15]: Stokes, G. G. (1845). On the theories of the internal friction of fluids in motion, and of the equilibrium and motion of elastic solids.
[^16]: Vincenti, Walter G.; Kruger, Charles H. (1965). *Introduction to Physical Gas Dynamics*. *Wiley*.
[^17]: Batchelor, G. K. (1967). *An Introduction to Fluid Dynamics*. *Cambridge University Press*. ISBN 978-0-521-66396-0, 147 & 154.
[^18]: Batchelor, G. K. (1967). *An Introduction to Fluid Dynamics*. *Cambridge University Press*. ISBN 978-0-521-66396-0, 75.
[^19]: Acheson, D. J. (1990). *Elementary Fluid Dynamics*. *Oxford University Press*. ISBN 978-0-19-859679-0. [Elementary Fluid Dynamics](https://books.google.com/books?id=IGfDBAAAQBAJ).
[^20]: Abdulkadirov, Ruslan; Lyakhov, Pavel (2022-02-22). *Estimates of Mild Solutions of Navier–Stokes Equations in Weak Herz-Type Besov–Morrey Spaces*. *Mathematics* **10**(5), 680. doi:[10.3390/math10050680](https://doi.org/10.3390/math10050680).
[^21]: Batchelor, G. K. (1967). *An Introduction to Fluid Dynamics*. *Cambridge University Press*. ISBN 978-0-521-66396-0, 21 & 147.
[^22]: Temam, Roger (2001). *Navier–Stokes Equations, Theory and Numerical Analysis*. *AMS Chelsea*, 107–112..
[^23]: Quarteroni, Alfio (2014-04-25). *Numerical models for differential problems*. *Springer*. ISBN 978-88-470-5522-3.
[^24]: Holdeman, J. T. (2010). *A Hermite finite element method for incompressible fluid flow*. *Int. J. Numer. Methods Fluids* **64**(4), 376–408. [2010IJNMF..64..376H](https://ui.adsabs.harvard.edu/abs/2010IJNMF..64..376H). doi:[10.1002/fld.2154](https://doi.org/10.1002/fld.2154)..
[^25]: Holdeman, J. T.; Kim, J. W. (2010). *Computation of incompressible thermal flows using Hermite finite elements*. *Comput. Meth. Appl. Mech. Eng.* **199**(49–52), 3297–3304. [2010CMAME.199.3297H](https://ui.adsabs.harvard.edu/abs/2010CMAME.199.3297H). doi:[10.1016/j.cma.2010.06.036](https://doi.org/10.1016/j.cma.2010.06.036)..
[^26]: Potter, M.; Wiggert, D. C. (2008). *Fluid Mechanics*. *McGraw-Hill*. ISBN 978-0-07-148781-8.
[^27]: Aris, R. (1989). *Vectors, Tensors, and the basic Equations of Fluid Mechanics*. *Dover Publications*. ISBN 0-486-66110-5.
[^28]: Parker, C. B. (1994). *McGraw Hill Encyclopaedia of Physics*. *McGraw-Hill*. ISBN 0-07-051400-3.
[^29]: Encyclopaedia of Physics (2nd Edition), [Rita G. Lerner](https://en.wikipedia.org/wiki/Rita_G._Lerner), G. L. Trigg, VHC publishers, 1991, ISBN 3-527-26954-1 (Verlagsgesellschaft), ISBN 0-89573-752-3 (VHC Inc.).
[^30]: Gorban, A. N.; Karlin, I. V. (2016). *Beyond Navier–Stokes equations: capillarity of ideal gas*. *Contemporary Physics* **58**(1), 70–90. [arXiv:1702.00831](https://arxiv.org/abs/1702.00831). [2017ConPh..58...70G](https://ui.adsabs.harvard.edu/abs/2017ConPh..58...70G). doi:[10.1080/00107514.2016.1256123](https://doi.org/10.1080/00107514.2016.1256123). [Beyond Navier–Stokes equations: capillarity of ideal gas](https://www.researchgate.net/publication/310825466)..
[^31]: Cercignani, C. (2002). *Handbook of mathematical fluid dynamics*. *North-Holland* **1**, 1–70. ISBN 978-0-444-50330-5.
[^32]: Nie, X. B.; Chen, S. Y.; Robbins, M. O. (2004). *A continuum and molecular dynamics hybrid method for micro-and nano-fluid flow*. *Journal of Fluid Mechanics* **500**, 55–64. [2004JFM...500...55N](https://ui.adsabs.harvard.edu/abs/2004JFM...500...55N). doi:[10.1017/S0022112003007225](https://doi.org/10.1017/S0022112003007225). [A continuum and molecular dynamics hybrid method for micro-and nano-fluid flow](https://www.cambridge.org/core/journals/journal-of-fluid-mechanics/article/a-continuum-and-molecular-dynamics-hybrid-method-for-micro-and-nano-fluid-flow/BE0D4513A0F90F844CD21D64F6D3F9EF)..
[^33]: Öttinger, H. C. (2012). *Stochastic processes in polymeric fluids*. *Springer Science & Business Media*. ISBN 978-3-540-58353-0. doi:[10.1007/978-3-642-58290-5](https://doi.org/10.1007/978-3-642-58290-5)..
[^34]: Shah, Tasneem Mohammad (1972). *Analysis of the multigrid method*. *NASA Sti/Recon Technical Report N* **91**, 23418. [1989STIN...9123418S](https://ui.adsabs.harvard.edu/abs/1989STIN...9123418S).
[^35]: Wang, C. Y. (1991). *Exact solutions of the steady-state Navier–Stokes equations*. *Annual Review of Fluid Mechanics* **23**, 159–177. [1991AnRFM..23..159W](https://ui.adsabs.harvard.edu/abs/1991AnRFM..23..159W). doi:[10.1146/annurev.fl.23.010191.001111](https://doi.org/10.1146/annurev.fl.23.010191.001111)..
[^36]: Landau, L. D.; Lifshitz, E. M. (1987). *Fluid mechanics*. *Pergamon Press* **[Course of Theoretical Physics](https://en.wikipedia.org/wiki/Course_of_Theoretical_Physics) Volume 6**. ISBN 978-0-08-033932-0, 75–88.
[^37]: Ethier, C. R.; Steinman, D. A. (1994). *Exact fully 3D Navier–Stokes solutions for benchmarking*. *International Journal for Numerical Methods in Fluids* **19**(5), 369–375. [1994IJNMF..19..369E](https://ui.adsabs.harvard.edu/abs/1994IJNMF..19..369E). doi:[10.1002/fld.1650190502](https://doi.org/10.1002/fld.1650190502)..
[^38]: Barna, I. F. (2011). *Self-Similar Solutions of Three-Dimensional Navier–Stokes Equation*. *Communications in Theoretical Physics* **56**(4), 745–750. [arXiv:1102.5504](https://arxiv.org/abs/1102.5504). [2011CoTPh..56..745I](https://ui.adsabs.harvard.edu/abs/2011CoTPh..56..745I). doi:[10.1088/0253-6102/56/4/25](https://doi.org/10.1088/0253-6102/56/4/25). [Self-Similar Solutions of Three-Dimensional Navier–Stokes Equation](https://iopscience.iop.org/article/10.1088/0253-6102/56/4/25).
[^39]: Barna, I. F.; Mátyás, L. (2014). *Analytic solutions for the three-dimensional compressible Navier-Stokes equation*. *Fluid Dynamics Research* **46**(5). [arXiv:1309.0703](https://arxiv.org/abs/1309.0703). [2014FlDyR..46e5508B](https://ui.adsabs.harvard.edu/abs/2014FlDyR..46e5508B). doi:[10.1088/0169-5983/46/5/055508](https://doi.org/10.1088/0169-5983/46/5/055508). [Analytic solutions for the three-dimensional compressible Navier-Stokes equation](https://iopscience.iop.org/article/10.1088/0169-5983/46/5/055508).
[^40]: *Navier Stokes Equations*. *www.claudino.webs.com*. [Navier Stokes Equations](http://www.claudino.webs.com/Navier%20Stokes%20Equations.pps).
[^41]: Kamchatno, A. M. (1982). *Topological solitons in magnetohydrodynamics*. *Soviet Journal of Experimental and Theoretical Physics* **55**(1), 69. [1982JETP...55...69K](https://ui.adsabs.harvard.edu/abs/1982JETP...55...69K). [Topological solitons in magnetohydrodynamics](http://www.jetp.ac.ru/cgi-bin/dn/e_055_01_0069.pdf)..
[^42]: Antuono, M. (2020). *Tri-periodic fully three-dimensional analytic solutions for the Navier–Stokes equations*. *Journal of Fluid Mechanics* **890**. [2020JFM...890A..23A](https://ui.adsabs.harvard.edu/abs/2020JFM...890A..23A). doi:[10.1017/jfm.2020.126](https://doi.org/10.1017/jfm.2020.126)..
[^43]: (2026-09-08). *On the Navier–Stokes Millennium Prize Problem*. *OpenAI*. [On the Navier–Stokes Millennium Prize Problem](https://openai.com/index/navier-stokes-solution/).
[^44]: Metz, Cade (8 September 2026). *OpenAI Says It Has Cracked One of Math's 'Millennium Problems'*. *The New York Times*. [OpenAI Says It Has Cracked One of Math's 'Millennium Problems'](https://www.nytimes.com/2026/09/08/science/openai-proof-millennium-problem.html).
[^45]: Fefferman, Charles L. (2006). *Existence and Smoothness of the Navier-Stokes Equation*. *The Millennium Prize Problems*, 57–67. [Existence and Smoothness of the Navier-Stokes Equation](https://www.claymath.org/wp-content/uploads/2022/06/navierstokes.pdf).
[^46]: (2026-09-08). *OpenAI Claims Blockbuster Math Breakthrough amid Swirl of Controversy*. *Scientific American*. [OpenAI Claims Blockbuster Math Breakthrough amid Swirl of Controversy](https://www.scientificamerican.com/article/openai-claims-blockbuster-math-breakthrough-amid-swirl-of-controversy/).
[^47]: (2026-09-08). *OpenAI's historic math solution overshadowed by credit controversy*. *Axios*. [OpenAI's historic math solution overshadowed by credit controversy](https://www.axios.com/2026/09/08/openai-math-solution-navier-stokes-credit).
[^48]: Córdoba, Diego; Martínez-Zoroa, Luis (2023). *Blow-up for the incompressible 3D-Euler equations with uniform $C^{1,1/2−ε} ∩ L^2$ force*. [arXiv:2309.08495](https://arxiv.org/abs/2309.08495).
[^49]: (8 September 2026). *AI Has Solved One of Math's $1 Million Millennium Prize Problems*. [AI Has Solved One of Math's $1 Million Millennium Prize Problems](https://www.quantamagazine.org/ai-has-solved-one-of-maths-1-million-millennium-prize-problems-20260908/).
[^50]: McComb, W. D. (2008). *Renormalization methods: A guide for beginners*. *Oxford University Press*, 121–128. ISBN 978-0-19-923652-7..
[^51]: Georgia Institute of Technology (August 29, 2022). *Physicists uncover new dynamical framework for turbulence*. *Proceedings of the National Academy of Sciences of the United States of America* **119**(34). [PMID 35984901](https://pubmed.ncbi.nlm.nih.gov/35984901/). [9407532](https://www.ncbi.nlm.nih.gov/pmc/articles/9407532/). doi:[10.1073/pnas.2120665119](https://doi.org/10.1073/pnas.2120665119). [Physicists uncover new dynamical framework for turbulence](https://phys.org/news/2022-08-physicists-uncover-dynamical-framework-turbulence.amp).
[^52]: de' Michieli Vitturi, Mattia. *Navier–Stokes equations in cylindrical coordinates*. [Navier–Stokes equations in cylindrical coordinates](https://demichie.github.io/NS_cylindrical).
[^53]: Weisstein (2005-10-26). *Spherical Coordinates*. *MathWorld*. [Spherical Coordinates](http://mathworld.wolfram.com/SphericalCoordinates.html)..
## เอกสารอ้างอิง

* Acheson, D. J. (1990). *คณิตศาสตร์พลศาสตร์ของไหลเบื้องต้น*. *มหาวิทยาลัยออกซฟอร์ด*. ISBN 978-0-19-859679-0. [คณิตศาสตร์พลศาสตร์ของไหลเบื้องต้น](https://books.google.com/books?id=IGfDBAAAQBAJ).
* Batchelor, G. K. (1967). *การแนะนำพลศาสตร์ของไหล*. *มหาวิทยาลัยเคมบริดจ์*. ISBN 978-0-521-66396-0.
* Currie, I. G. (1974). *กลศาสตร์พื้นฐานของของไหล*. *แมกโกรว์-ฮิลล์*. ISBN 978-0-07-015000-3.
* [V. Girault](https://en.wikipedia.org/wiki/Vivette_Girault) และ P. A. Raviart. *วิธีการใช้เอลิเมนต์จำกัดสำหรับสมการนาเวียร์–สโตกส์: ทฤษฎีและอัลกอริทึม*. ซีรีส์คณิตศาสตร์เชิงคำนวณสปริงเกอร์. สปริงเกอร์-เวอร์ลาจ, 1986
* Landau, L. D.; Lifshitz, E. M. (1987). *กลศาสตร์ของไหล*. *เพอร์กามอนเพรส* ***[หลักสูตรฟิสิกส์เชิงทฤษฎี](https://en.wikipedia.org/wiki/Course_of_Theoretical_Physics)* เล่ม 6**. ISBN 978-0-08-033932-0.
* Polyanin, A. D.; Kutepov, A. M.; Vyazmin, A. V.; Kazenin, D. A. (2002). *อุทกพลศาสตร์ การถ่ายโอนมวลและความร้อนในวิศวกรรมเคมี*. *เทย์เลอร์ & ฟรานซิส, ลอนดอน*. ISBN 978-0-415-27237-7.
* Rhyming, Inge L. (1991). *พลศาสตร์ของไหล*. *สำนักพิมพ์โพลีเทคนิคและมหาวิทยาลัยโรมานด์*.
* Smits, Alexander J. (2014), *บทนำเชิงฟิสิกส์สู่กลศาสตร์ของไหล*, ไวเลย์, ISBN 0-47-1253499
* Temam, Roger (1984): *สมการนาเวียร์–สโตกส์: ทฤษฎีและการวิเคราะห์เชิงตัวเลข*, ACM Chelsea Publishing, ISBN 978-0-8218-2737-6
* [Milne-Thomson, L.M.](https://en.wikipedia.org/wiki/L._M._Milne-Thomson), [C.B.E](https://en.wikipedia.org/wiki/Order_of_the_British_Empire) (1962), *อุทกพลศาสตร์เชิงทฤษฎี*, แมคมิลแลน & คัมปะนี ลิมิเต็ด
* Tartar, L (2006), *บทนำสู่สมการนาเวียร์–สโตกส์และสมุทรศาสตร์*, Springer ISBN 3-540-35743-2
* [Birkhoff, Garrett](https://en.wikipedia.org/wiki/Garrett_Birkhoff) (1960) *อุทกพลศาสตร์*, สำนักพิมพ์มหาวิทยาลัยพรินซ์ตัน
* Campos, D. (บรรณาธิการ) (2017) *คู่มือสมการนาเวียร์–สโตกส์: ทฤษฎีและการวิเคราะห์เชิงประยุกต์*, Nova Science Publisher ISBN 978-1-53610-292-5
* [Döring, C.E.](https://en.wikipedia.org/wiki/Charles_R._Doering) และ J.D. Gibbon, J.D. (1995) *Applied analysis of the Navier-Stokes equations,* Cambridge University Press, ISBN 0-521-44557-4
* [Basset, Alfred Barnard](https://en.wikipedia.org/wiki/Alfred_Barnard_Basset) (1888) *อุทกพลศาสตร์ เล่มที่ 1 และ 2*, Cambridge: Delighton, Bell and Company
* Fox, R. W.; McDonald, A. T.; และ Pritchard, P. J. (2004) *Introduction to Fluid Mechanics*, John Wiley and Sons, ISBN 0-471-20231-2
* Foias, C.; Mainley, O.; Rosa, R.; และ Temam, R. (2004) *Navier–Stokes Equations and Turbulence*, Cambridge University Press, ISBN 0-521-36032-3
* [Lions, P-L](https://en.wikipedia.org/wiki/Pierre-Louis_Lions). (1998) *หัวข้อคณิตศาสตร์ในกลศาสตร์ของไหล* เล่มที่ 1 และ 2, Clarendon Press, ISBN 0-19-851488-3
* Deville, M. O. และ Gatski, T. B. (2012) *Mathematical Modeling for Complex Fluids and Flows,* Springer, ISBN 978-3-642-25294-5
* Kochin, N. E.; Kibel, I. A.; และ Roze, N. V. (1964) *ชลศาสตร์เชิงทฤษฎี*, John Wiley & Sons, Limited
* [Lamb, Horace](https://en.wikipedia.org/wiki/Horace_Lamb) (1879) *อุทกพลศาสตร์*, สำนักพิมพ์มหาวิทยาลัยเคมบริดจ์
* White, Frank M. (2006). *การไหลของของเหลวหนืด*. *แมกโกรว์-ฮิลล์*. ISBN 978-0-07-124493-0.

## แหล่งข้อมูลภายนอก

* [การอธิบายอย่างง่ายของสมการนาเวียร์–สโตกส์](https://web.archive.org/web/20171129091339/http://www.allstar.fiu.edu/aero/Flow2.htm)
* [รูปแบบไม่คงที่สามมิติของสมการนาเวียร์–สโตกส์](https://www.grc.nasa.gov/www/k-12/airplane/nseqs.html) ศูนย์วิจัยกลเลน, NASA
