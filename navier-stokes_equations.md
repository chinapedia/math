---
title: Navier–Stokes equations
---

The **Navier–Stokes equations** describe the motion of [viscous](https://en.wikipedia.org/wiki/Viscosity) fluids. This system of [partial differential equations](https://en.wikipedia.org/wiki/Partial_differential_equation) was named after [Claude-Louis Navier](https://en.wikipedia.org/wiki/Claude-Louis_Navier) and [George Gabriel Stokes](https://en.wikipedia.org/wiki/Sir_George_Stokes%2C_1st_Baronet), who developed them over a few decades of progressive work, from 1822 (Navier) to 1842–1850 (Stokes). [Siméon Denis Poisson](https://en.wikipedia.org/wiki/Sim%C3%A9on_Denis_Poisson) independently achieved the same results.[^1]

The Navier–Stokes equations mathematically express [momentum](https://en.wikipedia.org/wiki/momentum) balance for [Newtonian fluid](https://en.wikipedia.org/wiki/Newtonian_fluid)s and make use of the [conservation of mass](https://en.wikipedia.org/wiki/conservation_of_mass). They are sometimes accompanied by an [equation of state](https://en.wikipedia.org/wiki/equation_of_state) relating [pressure](https://en.wikipedia.org/wiki/pressure), [temperature](https://en.wikipedia.org/wiki/temperature) and [density](https://en.wikipedia.org/wiki/density).[^2] They arise from applying [Newton's second law](https://en.wikipedia.org/wiki/Newton%27s_second_law) to [fluid motion](https://en.wikipedia.org/wiki/Fluid_dynamics), together with the assumption that the [stress](https://en.wikipedia.org/wiki/stress_%28mechanics%29) in the fluid is the sum of a diffusing viscous term (proportional to the [gradient](https://en.wikipedia.org/wiki/gradient) of velocity) and a pressure term—hence describing *viscous flow*. The Navier–Stokes equations generalize the [Euler equations](https://en.wikipedia.org/wiki/Euler_equations_%28fluid_dynamics%29) which only consider [inviscid flow](https://en.wikipedia.org/wiki/inviscid_flow).

The Navier–Stokes equations are of great scientific and engineering interest because they may be used to model a wide variety of scenarios. In their full or simplified forms, they can assist in the design of [aircraft](https://en.wikipedia.org/wiki/Aircraft_design_process#Preliminary_design_phase) and cars, the study of [blood flow](https://en.wikipedia.org/wiki/Hemodynamics), the design of [power station](https://en.wikipedia.org/wiki/power_station)s, the analysis of [pollution](https://en.wikipedia.org/wiki/pollution), and many other problems. Coupled with [Maxwell's equations](https://en.wikipedia.org/wiki/Maxwell%27s_equations), they comprise the fundamentals of [magnetohydrodynamics](https://en.wikipedia.org/wiki/magnetohydrodynamics).

The Navier–Stokes equations are also of great interest to [pure mathematics](https://en.wikipedia.org/wiki/pure_mathematics). The [Navier–Stokes existence and smoothness](https://en.wikipedia.org/wiki/Navier%E2%80%93Stokes_existence_and_smoothness) problem concerns whether they have [smooth](https://en.wikipedia.org/wiki/Smoothness) (meaning infinitely differentiable) or bounded solutions in [three-dimensional Euclidean space](https://en.wikipedia.org/wiki/Three-dimensional_space), as opposed to a breakdown with unbounded solutions. This is one of seven [Millennium Prize Problems](https://en.wikipedia.org/wiki/Millennium_Prize_Problems), notable open mathematics problems for which the [Clay Mathematics Institute](https://en.wikipedia.org/wiki/Clay_Mathematics_Institute) offered $1 million prizes in 2000 for correct solutions.[^3] [^4] In September 2026, [OpenAI](https://en.wikipedia.org/wiki/OpenAI) announced a claimed counterexample to the existence and smoothness problem. The announcement was followed by a [priority dispute](https://en.wikipedia.org/wiki/Navier%E2%80%93Stokes_priority_controversy), and the claimed counterexample has yet to be independently verified.[^5]

## Flow velocity

The solution of the equations is a [flow velocity](https://en.wikipedia.org/wiki/flow_velocity). It is a [vector field](https://en.wikipedia.org/wiki/vector_field)—to every point in a [fluid](https://en.wikipedia.org/wiki/fluid), at any moment in a time interval, it gives a vector whose direction and magnitude are those of the velocity of the fluid at that point in space and at that moment in time. It is studied in three spatial dimensions and one time dimension, and higher-dimensional analogues are studied in both pure and applied mathematics. Once the velocity field is calculated, other quantities of interest, such as [pressure](https://en.wikipedia.org/wiki/pressure) or [temperature](https://en.wikipedia.org/wiki/temperature), may be found using [dynamical equations](https://en.wikipedia.org/wiki/dynamical_systems) and relations. This is different from what one normally sees in [classical mechanics](https://en.wikipedia.org/wiki/classical_mechanics), where solutions are typically [trajectories](https://en.wikipedia.org/wiki/trajectories) of the position of a [particle](https://en.wikipedia.org/wiki/particle) or deflection of a [continuum](https://en.wikipedia.org/wiki/Continuum_%28theory%29). Studying velocity instead of position makes more sense for a fluid, although for visualization purposes, one can compute various [trajectories](https://en.wikipedia.org/wiki/Streamlines%2C_streaklines%2C_and_pathlines). In particular, the [streamlines](https://en.wikipedia.org/wiki/Streamlines%2C_streaklines%2C_and_pathlines) of a vector field, interpreted as flow velocity, are the paths along which a massless fluid particle would travel. These paths are the [integral curves](https://en.wikipedia.org/wiki/integral_curve) whose derivative at each point is equal to the vector field, and they can represent visually the behavior of the vector field at a point in time.

## General continuum equations

The Navier–Stokes momentum equation can be derived as a particular form of the [Cauchy momentum equation](https://en.wikipedia.org/wiki/Cauchy_momentum_equation), whose general convective form is:

$$
\frac{\mathrm{D} \mathbf{u}}{\mathrm{D} t} = \frac 1 \rho \nabla \cdot \boldsymbol{\sigma} + \mathbf{a}.
$$

By setting the [Cauchy stress tensor](https://en.wikipedia.org/wiki/Cauchy_stress_tensor) $\boldsymbol{\sigma}$ to be the sum of a viscosity term $\boldsymbol{\tau}$ (the [deviatoric stress](https://en.wikipedia.org/wiki/deviatoric_stress)) and a pressure term $-p \mathbf{I}$ (volumetric stress), we arrive at:

where
* $\frac{\mathrm{D}}{\mathrm{D}t}$ is the [material derivative](https://en.wikipedia.org/wiki/material_derivative), defined as $\frac{\partial}{\partial t} + \mathbf{u} \cdot \nabla$,
* $\rho$ is the (mass) density,
* $\mathbf{u}$ is the flow velocity,
* $\nabla \cdot \,$ is the [divergence](https://en.wikipedia.org/wiki/divergence),
* $p$ is the [pressure](https://en.wikipedia.org/wiki/pressure),
* $t$ is [time](https://en.wikipedia.org/wiki/time),
* $\boldsymbol{\tau}$ is the [deviatoric stress tensor](https://en.wikipedia.org/wiki/Deviatoric_stress), which has order 2,
* $\mathbf{a}$ represents [body acceleration](https://en.wikipedia.org/wiki/body_force#acceleration)s acting on the continuum, for example [gravity](https://en.wikipedia.org/wiki/gravity), [inertial accelerations](https://en.wikipedia.org/wiki/Fictitious_force), [electrostatic accelerations](https://en.wikipedia.org/wiki/Coulomb%27s_law), and so on.

In this form, it is apparent that in the assumption of an inviscid fluid – no deviatoric stress – Cauchy equations reduce to the [Euler equations](https://en.wikipedia.org/wiki/Euler_equations_%28fluid_dynamics%29).

Assuming [conservation of mass](https://en.wikipedia.org/wiki/conservation_of_mass), with the known properties of [divergence](https://en.wikipedia.org/wiki/divergence) and [gradient](https://en.wikipedia.org/wiki/gradient) we can use the mass [continuity equation](https://en.wikipedia.org/wiki/continuity_equation), which represents the mass per unit volume of a [homogenous](https://en.wikipedia.org/wiki/homogenous) fluid with respect to space and time (i.e., [material derivative](https://en.wikipedia.org/wiki/material_derivative) $\frac{\mathbf{D}}{\mathbf{Dt}}$) of any finite volume ( $\mathbf{V}$) to represent the change of velocity in fluid media:

$$
\begin{align}
& \frac{\mathbf{D}m}{\mathbf{Dt}} = \iiint\limits_V \left(\frac{ \mathbf{D}\rho}{\mathbf{Dt}} + \rho (\nabla \cdot \mathbf{u})\right) \, dV \\[5pt]
& \frac{\mathbf{D}\rho}{\mathbf{Dt}} + \rho (\nabla \cdot \mathbf{u} )=\frac{\partial\rho}{\partial t} + (\nabla \rho) \cdot \mathbf{u} + \rho(\nabla \cdot \mathbf{u})= \frac{\partial\rho}{\partial t} + \nabla\cdot(\rho \mathbf{u})= 0
\end{align}
$$

where
* $\frac{\mathrm{D}m}{\mathrm{D}t}$ is the [material derivative](https://en.wikipedia.org/wiki/material_derivative) of [mass](https://en.wikipedia.org/wiki/mass) per unit volume ([density](https://en.wikipedia.org/wiki/density), $\rho$),
* $\iiint \limits_V \bigl(F(x_1, x_2, x_3 ,t)\bigr) \, dV$ is the mathematical operation for the [integration throughout the volume](https://en.wikipedia.org/wiki/Volume_integral) ( $V$),
* $\frac{\partial }{\partial t}$ is the [partial derivative](https://en.wikipedia.org/wiki/partial_derivative) mathematical operator,
* $\nabla \cdot \mathbf{u}\,$ is the [divergence](https://en.wikipedia.org/wiki/divergence) of the flow velocity ( $\mathbf{u}$), which is a [scalar field](https://en.wikipedia.org/wiki/scalar_field),[^6]
* $\nabla \rho \,$ is the [gradient](https://en.wikipedia.org/wiki/gradient) of [density](https://en.wikipedia.org/wiki/density) ( $\rho$), which is the vector derivative of a [scalar field](https://en.wikipedia.org/wiki/scalar_field),[^6]
to arrive at the conservation form of the equations of motion. This is often written:[^7]

where $\otimes$ is the [outer product](https://en.wikipedia.org/wiki/outer_product) of the flow velocity ( $\mathbf{u}$):

$$
\mathbf u \otimes \mathbf u = \mathbf u \mathbf u^{\mathsf T}
$$

The left side of the equation describes acceleration, and may be composed of time-dependent and convective components (also the effects of non-inertial coordinates if present). The right side of the equation is in effect a summation of hydrostatic effects, the divergence of deviatoric stress and body forces (such as gravity).

All non-relativistic balance equations, such as the Navier–Stokes equations, can be derived by beginning with the Cauchy equations and specifying the stress tensor through a [constitutive relation](https://en.wikipedia.org/wiki/constitutive_relation). By expressing the deviatoric (shear) stress tensor in terms of [viscosity](https://en.wikipedia.org/wiki/viscosity) and the fluid [velocity](https://en.wikipedia.org/wiki/Shear_velocity) gradient, and assuming constant viscosity, the above Cauchy equations will lead to the Navier–Stokes equations below.

### Convective acceleration

<figure style={{"maxWidth": "132px"}}>

![An example of convection. Though the flow may be steady (time-independent), the fluid decelerates as it moves down the diverging duct (assuming incompressible or subsonic compressible flow), hence there is an acceleration happening over position.](https://pub-275e30003c354ac0862cc9839e0f952a.r2.dev/docs/math/ConvectiveAcceleration_vectorized.svg.png)

<figcaption>

An example of convection. Though the flow may be steady (time-independent), the fluid decelerates as it moves down the diverging duct (assuming incompressible or subsonic compressible flow), hence there is an acceleration happening over position.

</figcaption>

</figure>

A significant feature of the Cauchy equation and consequently all other continuum equations (including Euler and Navier–Stokes) is the presence of convective acceleration: the effect of acceleration of a flow with respect to space. While individual fluid particles indeed experience time-dependent acceleration, the convective acceleration of the flow field is a spatial effect, one example being fluid speeding up in a nozzle.

## Compressible flow

Remark: here, the deviatoric stress tensor is denoted $\boldsymbol{\tau}$ as it was in the [general continuum equations](./navier-stokes_equations.md#general-continuum-equations) and in the [incompressible flow section](./navier-stokes_equations.md#incompressible-flow).

The compressible momentum Navier–Stokes equation results from the following assumptions on the Cauchy stress tensor:[^8]

<ul>
the stress is **[Galilean invariant](https://en.wikipedia.org/wiki/Galilean_invariance)**: it does not depend directly on the flow velocity, but only on spatial derivatives of the flow velocity. So the stress variable is the tensor gradient $\nabla \mathbf{u}$, or more simply the [rate-of-strain tensor](https://en.wikipedia.org/wiki/strain-rate_tensor): $\boldsymbol{\varepsilon}\left(\nabla \mathbf{u}\right) \equiv \frac{1}{2}\nabla \mathbf{u} + \frac{1}{2} \left(\nabla \mathbf{u}\right)^{\mathsf T}$
the deviatoric stress is **linear** in this variable: $\boldsymbol{\sigma}(\boldsymbol \varepsilon) = -p \mathbf I + \mathbf{C} : \boldsymbol \varepsilon$, where $p$ is independent on the strain rate tensor, $\mathbf{C}$ is the fourth-order tensor representing the constant of proportionality, called the viscosity or [elasticity tensor](https://en.wikipedia.org/wiki/elasticity_tensor), and : is the [double-dot product](https://en.wikipedia.org/wiki/Dyadics#Double-dot_product).
the fluid is assumed to be [isotropic](https://en.wikipedia.org/wiki/isotropic), as with gases and simple liquids, and consequently $\mathbf{C}$ is an isotropic tensor; furthermore, since the deviatoric stress tensor is symmetric, by [Helmholtz decomposition](https://en.wikipedia.org/wiki/Helmholtz_decomposition) it can be expressed in terms of two scalar [Lamé parameters](https://en.wikipedia.org/wiki/Lam%C3%A9_parameters), the [second viscosity](https://en.wikipedia.org/wiki/second_viscosity) $\lambda$ and the [dynamic viscosity](https://en.wikipedia.org/wiki/dynamic_viscosity) $\mu$, as it is usual in [linear elasticity](https://en.wikipedia.org/wiki/linear_elasticity):

where $\mathbf{I}$ is the [identity tensor](https://en.wikipedia.org/wiki/Identity_matrix), and $\operatorname{tr} (\boldsymbol \varepsilon)$ is the [trace](https://en.wikipedia.org/wiki/trace_%28linear_algebra%29) of the rate-of-strain tensor. So this decomposition can be explicitly defined as:

$$
\boldsymbol \sigma = -p \mathbf I + \lambda (\nabla\cdot\mathbf{u}) \mathbf I + \mu \left(\nabla\mathbf{u} + ( \nabla\mathbf{u} )^\mathsf{T}\right).
$$

</ul>

Since the [trace](https://en.wikipedia.org/wiki/trace_%28linear_algebra%29) of the rate-of-strain tensor in three dimensions is the [divergence](https://en.wikipedia.org/wiki/divergence) (i.e. rate of expansion) of the flow:

$$
\operatorname{tr} (\boldsymbol \varepsilon) = \nabla\cdot\mathbf{u}.
$$

Given this relation, and since the trace of the identity tensor in three dimensions is three:

$$
\operatorname{tr} (\boldsymbol I) = 3.
$$

the trace of the stress tensor in three dimensions becomes:

$$
\operatorname{tr} (\boldsymbol \sigma ) = -3p + (3 \lambda + 2 \mu )\nabla\cdot\mathbf{u}.
$$

So by alternatively decomposing the stress tensor into **isotropic** and **deviatoric** parts, as usual in fluid dynamics:[^9]

$$
\boldsymbol \sigma = - \left[ p - \left(\lambda + \tfrac23 \mu\right) \left(\nabla\cdot\mathbf{u}\right) \right] \mathbf I + \mu \left(\nabla\mathbf{u} + \left( \nabla\mathbf{u} \right)^\mathsf{T} - \tfrac23 \left(\nabla\cdot\mathbf{u}\right)\mathbf I\right)
$$

Introducing the [bulk viscosity](https://en.wikipedia.org/wiki/volume_viscosity) $\zeta$,

$$
\zeta \equiv \lambda + \tfrac23 \mu ,
$$

we arrive at the linear [constitutive equation](https://en.wikipedia.org/wiki/constitutive_equation) in the form usually employed in [thermal hydraulics](https://en.wikipedia.org/wiki/thermal_hydraulics):[^8]

which can also be arranged in the other usual form:[^10]

$$
\boldsymbol \sigma = -p \mathbf I + \mu \left(\nabla\mathbf{u} + ( \nabla\mathbf{u} )^\mathsf{T}\right) + \left(\zeta - \tfrac 2 3 \mu \right) (\nabla\cdot\mathbf{u}) \mathbf I.
$$

Note that in the compressible case the pressure is no more proportional to the [isotropic stress](https://en.wikipedia.org/wiki/hydrostatic_stress) term, since there is the additional bulk viscosity term:

$$
p = - \tfrac 1 3 \operatorname{tr} (\boldsymbol \sigma)  + \zeta (\nabla\cdot\mathbf{u})
$$

and the [deviatoric stress tensor](https://en.wikipedia.org/wiki/deviatoric_stress_tensor) $\boldsymbol \sigma'$ is still coincident with the shear stress tensor $\boldsymbol \tau$ (i.e. the deviatoric stress in a Newtonian fluid has no normal stress components), and it has a compressibility term in addition to the incompressible case, which is proportional to the shear viscosity:

$$
\boldsymbol \sigma' = \boldsymbol \tau = \mu \left[\nabla\mathbf{u} + ( \nabla\mathbf{u} )^\mathsf{T} - \tfrac23 (\nabla\cdot\mathbf{u})\mathbf I\right]
$$

Both bulk viscosity $\zeta$ and dynamic viscosity $\mu$ need not be constant – in general, they depend on two thermodynamics variables if the fluid contains a single chemical species, say for example, pressure and temperature. Any equation that makes explicit one of these [transport coefficient](https://en.wikipedia.org/wiki/transport_coefficient) in the [conservation variable](https://en.wikipedia.org/wiki/conservation_variable)s is called an [equation of state](https://en.wikipedia.org/wiki/equation_of_state).[^11]

The most general of the Navier–Stokes equations become

in index notation, the equation can be written as[^12]

The corresponding equation in conservation form can be obtained by considering that, given the mass [continuity equation](https://en.wikipedia.org/wiki/continuity_equation), the left side is equivalent to:

$$
\rho \frac{\mathrm{D} \mathbf{u}}{\mathrm{D} t} = \frac {\partial}{\partial t} (\rho \mathbf u) + \nabla \cdot (\rho \mathbf u \otimes \mathbf u)
$$

to give finally:

Apart from its dependence of pressure and temperature, the second viscosity coefficient also depends on the process, that is to say, the second viscosity coefficient is not just a material property. Example: in the case of a sound wave with a definitive frequency that alternatively compresses and expands a fluid element, the second viscosity coefficient depends on the frequency of the wave. This dependence is called the *dispersion*. In some cases, the [second viscosity](https://en.wikipedia.org/wiki/volume_viscosity) $\zeta$ can be assumed to be constant in which case, the effect of the volume viscosity $\zeta$ is that the mechanical pressure is not equivalent to the thermodynamic [pressure](https://en.wikipedia.org/wiki/pressure):[^13] as demonstrated below.

$$
\begin{align} &\nabla\cdot(\nabla\cdot \mathbf u)\mathbf I=\nabla (\nabla \cdot \mathbf u), \\ &\bar{p} \equiv p - \zeta \, \nabla \cdot \mathbf{u} ,\end{align}
$$

However, this difference is usually neglected most of the time (that is whenever we are not dealing with processes such as sound absorption and attenuation of shock waves,[^14] where second viscosity coefficient becomes important) by explicitly assuming $\zeta = 0$. The assumption of setting $\zeta = 0$ is called as the **Stokes hypothesis**.[^15] The validity of Stokes hypothesis can be demonstrated for monoatomic gas both experimentally and from the kinetic theory;[^16] for other gases and liquids, Stokes hypothesis is generally incorrect. With the Stokes hypothesis, the Navier–Stokes equations become

If the dynamic $\mu$ and bulk $\zeta$ viscosities are assumed to be uniform in space, the equations in convective form can be simplified further. By computing the divergence of the stress tensor, since the divergence of tensor $\nabla \mathbf{u}$ is $\nabla^2 \mathbf{u}$ and the divergence of tensor $\left(\nabla \mathbf{u}\right)^{\mathsf T}$ is $\nabla \left(\nabla \cdot \mathbf{u}\right)$, one finally arrives to the compressible Navier–Stokes momentum equation:[^17]

where $\frac{\mathrm{D}}{\mathrm{D}t}$ is the [material derivative](https://en.wikipedia.org/wiki/material_derivative). $\nu=\frac \mu \rho$ is the shear [kinematic viscosity](https://en.wikipedia.org/wiki/kinematic_viscosity) and $\xi=\frac \zeta \rho$ is the bulk kinematic viscosity. The left-hand side changes in the conservation form of the Navier–Stokes momentum equation.
By bringing the operator on the flow velocity on the left side, one also has:

The convective acceleration term can also be written as

$$
\mathbf u\cdot\nabla\mathbf u = (\nabla\times\mathbf u)\times\mathbf u + \tfrac12\nabla\mathbf u^2,
$$

where the vector $(\nabla \times \mathbf{u}) \times \mathbf{u}$ is known as the [Lamb vector](https://en.wikipedia.org/wiki/Lamb_vector).

For the special case of an [incompressible flow](https://en.wikipedia.org/wiki/incompressible_flow), the pressure constrains the flow so that the volume of [fluid element](https://en.wikipedia.org/wiki/fluid_element)s is constant: [isochoric flow](https://en.wikipedia.org/wiki/isochoric_process) resulting in a [solenoidal](https://en.wikipedia.org/wiki/Solenoidal_vector_field) velocity field with $\nabla \cdot \mathbf{u} = 0$.[^18]

## Incompressible flow

The incompressible momentum Navier–Stokes equation results from the following assumptions on the Cauchy stress tensor:[^8]

<ul>
the stress is **[Galilean invariant](https://en.wikipedia.org/wiki/Galilean_invariance)**: it does not depend directly on the flow velocity, but only on spatial derivatives of the flow velocity. So the stress variable is the tensor gradient $\nabla \mathbf{u}$.
the fluid is assumed to be [isotropic](https://en.wikipedia.org/wiki/isotropic), as with gases and simple liquids, and consequently $\boldsymbol{\tau}$ is an isotropic tensor; furthermore, since the deviatoric stress tensor can be expressed in terms of the [dynamic viscosity](https://en.wikipedia.org/wiki/dynamic_viscosity) $\mu$:

where

$$
\boldsymbol{\varepsilon} = \tfrac{1}{2} \left( \mathbf{\nabla u} + \mathbf{\nabla u}^\mathsf{T} \right)
$$

is the rate-of-[strain tensor](https://en.wikipedia.org/wiki/strain_tensor). So this decomposition can be made explicit as:[^8]

</ul>

This constitutive equation is also called the **[Newtonian law of viscosity](https://en.wikipedia.org/wiki/Newtonian_fluid#Newtonian_law_of_viscosity)**.
Dynamic viscosity $μ$ need not be constant – in incompressible flows it can depend on density and on pressure. Any equation that makes explicit one of these [transport coefficient](https://en.wikipedia.org/wiki/transport_coefficient) in the [conservative variable](https://en.wikipedia.org/wiki/conservative_variable)s is called an [equation of state](https://en.wikipedia.org/wiki/equation_of_state).[^11]

The divergence of the deviatoric stress in case of uniform viscosity is given by:

$$
\nabla \cdot \boldsymbol \tau = 2 \mu \nabla \cdot \boldsymbol \varepsilon = \mu \nabla \cdot \left( \nabla\mathbf{u} + \nabla\mathbf{u} ^\mathsf{T} \right) = \mu \, \nabla^2 \mathbf{u}
$$

because $\nabla \cdot \mathbf{u} = 0$ for an incompressible fluid.

Incompressibility rules out density and pressure waves like sound or [shock wave](https://en.wikipedia.org/wiki/shock_wave)s, so this simplification is not useful if these phenomena are of interest. The incompressible flow assumption typically holds well with all fluids at low [Mach number](https://en.wikipedia.org/wiki/Mach_number)s (say up to about Mach 0.3), such as for modelling air winds at normal temperatures.[^19] the incompressible Navier–Stokes equations are best visualized by dividing for the density:[^20]

where $\nu = \frac{\mu}{\rho}$ is called the [kinematic viscosity](https://en.wikipedia.org/wiki/kinematic_viscosity).
By isolating the fluid velocity, one can also state:

If the density is constant throughout the fluid domain, or, in other words, if all fluid elements have the same density, $\rho$, then we have

where $\frac{p}{\rho}$ is called the unit [pressure head](https://en.wikipedia.org/wiki/pressure_head).

In incompressible flows, the pressure field satisfies the [Poisson equation](https://en.wikipedia.org/wiki/Poisson_equation),

$$
\nabla^2 p = - \rho \frac{\partial u_i}{\partial x_k}\frac{\partial u_k}{\partial x_i} = - \rho \frac{\partial^2 u_iu_k}{\partial x_kx_i},
$$

which is obtained by taking the divergence of the momentum equations.

It is well worth observing the meaning of each term (compare to the [Cauchy momentum equation](https://en.wikipedia.org/wiki/Cauchy_momentum_equation)):

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

The higher-order term, namely the [shear stress](https://en.wikipedia.org/wiki/shear_stress) divergence $\nabla \cdot \boldsymbol{\tau}$, has simply reduced to the [vector Laplacian](https://en.wikipedia.org/wiki/vector_Laplacian) term $\mu \nabla^2 \mathbf{u}$.[^21] This Laplacian term can be interpreted as the difference between the velocity at a point and the mean velocity in a small surrounding volume. This implies that – for a Newtonian fluid – viscosity operates as a *diffusion of momentum*, in much the same way as the [heat conduction](https://en.wikipedia.org/wiki/heat_conduction). In fact neglecting the convection term, incompressible Navier–Stokes equations lead to a vector [diffusion equation](https://en.wikipedia.org/wiki/diffusion_equation) (namely [Stokes equations](https://en.wikipedia.org/wiki/Stokes_flow)), but in general the convection term is present, so incompressible Navier–Stokes equations belong to the class of [convection–diffusion equation](https://en.wikipedia.org/wiki/convection%E2%80%93diffusion_equation)s.

In the usual case of an external field being a [conservative field](https://en.wikipedia.org/wiki/conservative_field):

$$
\mathbf g = - \nabla \varphi
$$

by defining the [hydraulic head](https://en.wikipedia.org/wiki/hydraulic_head):

$$
h \equiv w + \varphi
$$

one can finally condense the whole source in one term, arriving to the incompressible Navier–Stokes equation with conservative external field:

$$
\frac{\partial \mathbf{u}}{\partial t} + (\mathbf{u} \cdot \nabla) \mathbf{u} - \nu \, \nabla^2 \mathbf{u} = - \nabla h.
$$

The incompressible Navier–Stokes equations with uniform density and viscosity and conservative external field is the **fundamental equation of [hydraulics](https://en.wikipedia.org/wiki/hydraulics)**. The domain for these equations is commonly a 3 or fewer dimensional [Euclidean space](https://en.wikipedia.org/wiki/Euclidean_space), for which an [orthogonal coordinate](https://en.wikipedia.org/wiki/orthogonal_coordinate) reference frame is usually set to explicit the system of scalar partial differential equations to be solved. In 3-dimensional orthogonal coordinate systems are 3: [Cartesian](https://en.wikipedia.org/wiki/Cartesian_coordinate_system), [cylindrical](https://en.wikipedia.org/wiki/Cylindrical_coordinate_system), and [spherical](https://en.wikipedia.org/wiki/Spherical_coordinate_system). Expressing the Navier–Stokes vector equation in Cartesian coordinates is quite straightforward and not much influenced by the number of dimensions of the euclidean space employed, and this is the case also for the first-order terms (like the variation and convection ones) also in non-cartesian orthogonal coordinate systems. But for the higher order terms (the two coming from the divergence of the deviatoric stress that distinguish Navier–Stokes equations from Euler equations) some [tensor calculus](https://en.wikipedia.org/wiki/tensor_calculus) is required for deducing an expression in non-cartesian orthogonal coordinate systems.
A special case of the fundamental equation of hydraulics is the [Bernoulli's equation](https://en.wikipedia.org/wiki/Bernoulli%27s_equation).

The incompressible Navier–Stokes equation is composite, the sum of two orthogonal equations,

$$
\begin{align}
\frac{\partial\mathbf{u}}{\partial t} &= \Pi^S\left(-(\mathbf{u}\cdot\nabla)\mathbf{u} + \nu\,\nabla^2\mathbf{u}\right) + \mathbf{f}^S \\
\rho^{-1}\,\nabla p &= \Pi^I\left(-(\mathbf{u}\cdot\nabla)\mathbf{u} + \nu\,\nabla^2\mathbf{u}\right) + \mathbf{f}^I
\end{align}
$$

where $\Pi^S$ and $\Pi^I$ are solenoidal and [irrotational](https://en.wikipedia.org/wiki/Conservative_vector_field) projection operators satisfying $\Pi^S + \Pi^I = 1$, and $\mathbf{f}^S$ and $\mathbf{f}^I$ are the non-conservative and conservative parts of the body force. This result follows from the [Helmholtz theorem](https://en.wikipedia.org/wiki/Helmholtz_decomposition) (also known as the fundamental theorem of vector calculus). The first equation is a pressureless governing equation for the velocity, while the second equation for the pressure is a functional of the velocity and is related to the pressure Poisson equation.

The explicit functional form of the projection operator in 3D is found from the Helmholtz theorem:

$$
\Pi^S\,\mathbf{F}(\mathbf{r}) = \frac{1}{4\pi}\nabla\times\int \frac{\nabla^\prime\times\mathbf{F}(\mathbf{r}')}{|\mathbf{r}-\mathbf{r}'|} \, \mathrm{d} V', \quad \Pi^I = 1-\Pi^S
$$

with a similar structure in 2D. Thus the governing equation is an [integro-differential equation](https://en.wikipedia.org/wiki/integro-differential_equation) similar to [Coulomb's](https://en.wikipedia.org/wiki/Coulomb%27s_law) and [Biot–Savart's law](https://en.wikipedia.org/wiki/Biot%E2%80%93Savart_law), not convenient for numerical computation.

An equivalent weak or variational form of the equation, proved to produce the same velocity solution as the Navier–Stokes equation,[^22] is given by,

$$
\left(\mathbf{w},\frac{\partial\mathbf{u}}{\partial t}\right) = -\bigl(\mathbf{w}, \left(\mathbf{u}\cdot\nabla\right)\mathbf{u}\bigr) - \nu \left(\nabla\mathbf{w}: \nabla\mathbf{u}\right) + \left(\mathbf{w}, \mathbf{f}^S\right)
$$

for divergence-free test functions $\mathbf{w}$ satisfying appropriate boundary conditions. Here, the projections are accomplished by the orthogonality of the solenoidal and irrotational function spaces. The discrete form of this is eminently suited to finite element computation of divergence-free flow, as we shall see in the next section. There, one will be able to address the question, "How does one specify pressure-driven (Poiseuille) problems with a pressureless governing equation?".

The absence of pressure forces from the governing velocity equation demonstrates that the equation is not a dynamic one, but rather a kinematic equation where the divergence-free condition serves the role of a conservation equation. This would seem to refute the frequent statements that the incompressible pressure enforces the divergence-free condition.

### Weak form of the incompressible Navier–Stokes equations

#### Strong form

Consider the incompressible Navier–Stokes equations for a [Newtonian fluid](https://en.wikipedia.org/wiki/Newtonian_fluid) of constant density $\rho$ in a domain

$$
\Omega \subset \mathbb R^d \quad (d=2, 3)
$$

with boundary

$$
\partial \Omega = \Gamma_D \cup \Gamma_N ,
$$

being $\Gamma_D$ and $\Gamma_N$ portions of the boundary where respectively a [Dirichlet](https://en.wikipedia.org/wiki/Dirichlet_boundary_condition) and a [Neumann boundary condition](https://en.wikipedia.org/wiki/Neumann_boundary_condition) is applied ( $\Gamma_D \cap \Gamma_N = \emptyset$):[^23]

$$
\begin{cases}
\rho \dfrac{\partial \mathbf{u}}{\partial t} + \rho (\mathbf{u} \cdot \nabla) \mathbf{u} - \nabla \cdot \boldsymbol{\sigma} (\mathbf{u}, p) = \mathbf{f} & \text{ in } \Omega \times (0, T) \\
\nabla \cdot \mathbf{u} = 0  & \text{ in } \Omega \times (0, T) \\
\mathbf{u} = \mathbf{g} & \text{ on } \Gamma_D \times (0, T) \\
 \boldsymbol{\sigma} (\mathbf{u}, p) \hat{\mathbf{n}} = \mathbf{h} & \text{ on } \Gamma_N \times (0, T) \\
\mathbf{u}(0)= \mathbf{u}_0 & \text{ in } \Omega \times \{ 0\}
\end{cases}
$$

$\mathbf{u}$ is the fluid velocity, $p$ the fluid pressure, $\mathbf{f}$ a given forcing term, $\hat{\mathbf{n}}$ the outward directed unit normal vector to $\Gamma_N$, and $\boldsymbol{\sigma}(\mathbf{u}, p)$ the [viscous stress tensor](https://en.wikipedia.org/wiki/viscous_stress_tensor) defined as:[^23]

$$
\boldsymbol{\sigma} (\mathbf{u}, p) = -p \mathbf{I} + 2 \mu \boldsymbol{\varepsilon}(\mathbf{u}).
$$

Let $\mu$ be the dynamic viscosity of the fluid, $\mathbf{I}$ the second-order [identity tensor](https://en.wikipedia.org/wiki/Identity_matrix) and $\boldsymbol{\varepsilon}(\mathbf{u})$ the [strain-rate tensor](https://en.wikipedia.org/wiki/strain-rate_tensor) defined as:[^23]

$$
\boldsymbol{\varepsilon} (\mathbf{u}) = \tfrac{1}{2} \left(\left( \nabla \mathbf{u} \right) + \left( \nabla \mathbf{u} \right)^\mathsf{T}\right).
$$

The functions $\mathbf{g}$ and $\mathbf{h}$ are given Dirichlet and Neumann boundary data, while $\mathbf{u}_0$ is the [initial condition](https://en.wikipedia.org/wiki/initial_condition). The first equation is the momentum balance equation, while the second represents the [mass conservation](https://en.wikipedia.org/wiki/conservation_of_mass), namely the [continuity equation](https://en.wikipedia.org/wiki/continuity_equation).
Assuming constant dynamic viscosity, using the vectorial identity

$$
\nabla \cdot \left( \nabla \mathbf{f} \right)^\mathsf{T} = \nabla ( \nabla \cdot \mathbf{f} )
$$

and exploiting mass conservation, the divergence of the total stress tensor in the momentum equation can also be expressed as:[^23]

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

Moreover, note that the Neumann boundary conditions can be rearranged as:[^23]

$$
\boldsymbol{\sigma}(\mathbf{u}, p) \hat{\mathbf{n}} = \bigl(-p \mathbf{I} + 2 \mu \boldsymbol{\varepsilon}(\mathbf{u})\bigr)\hat{\mathbf{n}} = -p \hat{\mathbf{n}} + \mu \frac{\partial \boldsymbol u}{\partial \hat{\mathbf{n}}}.
$$

#### Weak form

In order to find the weak form of the Navier–Stokes equations, firstly, consider the momentum equation[^23]

$$
\rho \frac{\partial \mathbf{u}}{\partial t}  - \mu \Delta \mathbf{u} + \rho (\mathbf{u} \cdot \nabla) \mathbf{u} + \nabla p  = \mathbf{f}
$$

multiply it for a test function $\mathbf{v}$, defined in a suitable space $V$, and integrate both members with respect to the domain $\Omega$:[^23]

$$
\int \limits_\Omega \rho \frac{\partial \mathbf{u}}{\partial t}\cdot \mathbf{v}  - \int \limits_\Omega \mu \Delta \mathbf{u} \cdot \mathbf{v} + \int \limits_\Omega \rho (\mathbf{u} \cdot \nabla) \mathbf{u} \cdot \mathbf{v} + \int \limits_\Omega \nabla p \cdot \mathbf{v} = \int \limits_\Omega \mathbf{f} \cdot \mathbf{v}
$$

Counter-integrating by parts the diffusive and the pressure terms and by using Gauss's theorem:[^23]

$$
\begin{align}
-\int \limits_\Omega \mu \Delta \mathbf{u} \cdot \mathbf{v} &= \int \limits_\Omega \mu \nabla \mathbf{u} \cdot \nabla \mathbf{v} - \int \limits_{\partial \Omega} \mu \frac{\partial \mathbf{u}}{\partial \hat{\mathbf{n}}} \cdot \mathbf{v} \\
\int \limits_\Omega \nabla p \cdot \mathbf{v} &= -\int \limits_\Omega p \nabla \cdot \mathbf{v} + \int \limits_{\partial \Omega} p \mathbf{v} \cdot {\hat{\mathbf{n}}}
\end{align}
$$

Using these relations, one gets:[^23]

$$
\int \limits_\Omega \rho \dfrac{\partial \mathbf{u}}{\partial t}\cdot \mathbf{v}
 + \int \limits_\Omega \mu \nabla \mathbf{u} \cdot \nabla \mathbf{v}
 + \int \limits_\Omega \rho (\mathbf{u} \cdot \nabla) \mathbf{u} \cdot \mathbf{v}
 - \int \limits_\Omega p \nabla \cdot \mathbf{v}
= \int \limits_\Omega \mathbf{f} \cdot \mathbf{v}
 + \int \limits_{\partial \Omega} \left ( \mu \frac{\partial \mathbf{u}}{\partial \hat{\mathbf{n}}} - p \hat{\mathbf{n}}\right) \cdot \mathbf{v}
 \quad \forall \mathbf{v} \in V.
$$

In the same fashion, the continuity equation is multiplied for a test function $q$ belonging to a space $Q$ and integrated in the domain $\Omega$:[^23]

$$
\int \limits_\Omega q \nabla \cdot \mathbf{u} = 0. \quad \forall q \in Q.
$$

The space functions are chosen as follows:

$$
\begin{align}
V = \left[H_0^1(\Omega) \right]^d &= \left\{ \mathbf{v} \in \left[H^1(\Omega)\right]^d: \quad \mathbf{v} = \mathbf{0} \text{ on } \Gamma_D \right\}, \\
Q &= L^2(\Omega)
\end{align}
$$

Considering that the test function $\mathbf v$ vanishes on the Dirichlet boundary and considering the Neumann condition, the integral on the boundary can be rearranged as:[^23]

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

Having this in mind, the [weak formulation](https://en.wikipedia.org/wiki/weak_formulation) of the Navier–Stokes equations is expressed as:[^23]

$$
\begin{align}
&\text{find } \mathbf{u} \in L^2 \left(\mathbb R^+\; \left[H^1(\Omega)\right]^d\right) \cap C^0\left(\mathbb R^+ \; \left[L^2(\Omega)\right]^d\right) \text{ such that: } \\[5pt]
&\quad\begin{cases}
\displaystyle \int \limits_{\Omega}\rho \dfrac{\partial \mathbf{u}}{\partial t}\cdot \mathbf{v} + \int  \limits_{\Omega} \mu \nabla \mathbf{u} \cdot \nabla \mathbf{v} + \int \limits_{\Omega} \rho (\mathbf{u} \cdot \nabla) \mathbf{u} \cdot \mathbf{v} - \int \limits_{\Omega} p \nabla \cdot \mathbf{v} = \int \limits_{\Omega}\mathbf{f} \cdot \mathbf{v} +  \int \limits_{\Gamma_N} \mathbf{h} \cdot \mathbf{v} \quad \forall \mathbf{v} \in V, \\
\displaystyle  \int \limits_{\Omega} q \nabla \cdot \mathbf{u} = 0 \quad \forall q \in Q.
\end{cases}\end{align}
$$

### Discrete velocity

With partitioning of the problem domain and defining [basis function](https://en.wikipedia.org/wiki/basis_function)s on the partitioned domain, the discrete form of the governing equation is

$$
\left(\mathbf{w}_i, \frac{\partial\mathbf{u}_j}{\partial t}\right) = -\bigl(\mathbf{w}_i, \left(\mathbf{u}\cdot\nabla\right)\mathbf{u}_j\bigr) - \nu\left(\nabla\mathbf{w}_i: \nabla\mathbf{u}_j\right) + \left(\mathbf{w}_i, \mathbf{f}^S\right).
$$

It is desirable to choose basis functions that reflect the essential feature of incompressible flow – the elements must be divergence-free. While the velocity is the variable of interest, the existence of the stream function or vector potential is necessary by the Helmholtz theorem. Further, to determine fluid flow in the absence of a pressure gradient, one can specify the difference of stream function values across a 2D channel, or the [line integral](https://en.wikipedia.org/wiki/line_integral) of the tangential component of the vector potential around the channel in 3D, the flow being given by [Stokes' theorem](https://en.wikipedia.org/wiki/Stokes%27_theorem). Discussion will be restricted to 2D in the following.

We further restrict discussion to continuous Hermite finite elements which have at least first-derivative degrees-of-freedom. With this, one can draw a large number of candidate triangular and rectangular elements from the [plate-bending](https://en.wikipedia.org/wiki/Bending_of_plates) literature. These elements have derivatives as components of the gradient. In 2D, the gradient and curl of a scalar are clearly orthogonal, given by the expressions,

$$
\begin{align}
\nabla\varphi &= \left(\frac{\partial \varphi}{\partial x},\,\frac{\partial \varphi}{\partial y}\right)^\mathsf{T}, \\[5pt]
\nabla\times\varphi &= \left(\frac{\partial \varphi}{\partial y},\,-\frac{\partial \varphi}{\partial x}\right)^\mathsf{T}.
\end{align}
$$

Adopting continuous plate-bending elements, interchanging the derivative degrees-of-freedom and changing the sign of the appropriate one gives many families of stream function elements.

Taking the curl of the scalar stream function elements gives divergence-free velocity elements.[^24] [^25] The requirement that the stream function elements be continuous assures that the normal component of the velocity is continuous across element interfaces, all that is necessary for vanishing divergence on these interfaces.

Boundary conditions are simple to apply. The stream function is constant on no-flow surfaces, with no-slip velocity conditions on surfaces.
Stream function differences across open channels determine the flow. No boundary conditions are necessary on open boundaries, though consistent values may be used with some problems. These are all Dirichlet conditions.

The algebraic equations to be solved are simple to set up, but of course are [non-linear](./navier-stokes_equations.md#nonlinearity), requiring iteration of the linearized equations.

Similar considerations apply to three-dimensions, but extension from 2D is not immediate because of the vector nature of the potential, and there exists no simple relation between the gradient and the curl as was the case in 2D.

### Pressure recovery

Recovering pressure from the velocity field is easy. The discrete weak equation for the pressure gradient is,

$$
(\mathbf{g}_i, \nabla p) = -\bigl(\mathbf{g}_i, \left(\mathbf{u}\cdot\nabla\right)\mathbf{u}_j\bigr) - \nu\left(\nabla\mathbf{g}_i: \nabla\mathbf{u}_j\right) + \left(\mathbf{g}_i, \mathbf{f}^I\right)
$$

where the test/weight functions are irrotational. Any conforming scalar finite element may be used. However, the pressure gradient field may also be of interest. In this case, one can use scalar Hermite elements for the pressure. For the test/weight functions $\mathbf{g}_i$ one would choose the irrotational vector elements obtained from the gradient of the pressure element.

## Non-inertial frame of reference

The rotating frame of reference introduces some interesting pseudo-forces into the equations through the [material derivative](https://en.wikipedia.org/wiki/material_derivative) term. Consider a stationary [inertial frame of reference](https://en.wikipedia.org/wiki/inertial_frame_of_reference) $K$ , and a [non-inertial frame of reference](https://en.wikipedia.org/wiki/non-inertial_frame_of_reference) $K'$, which is translating with velocity $\mathbf{U}(t)$ and rotating with angular velocity $\Omega(t)$ with respect to the stationary frame. The Navier–Stokes equation observed from the non-inertial frame then becomes

Here $\mathbf{x}$ and $\mathbf{u}$ are measured in the non-inertial frame. The first term in the parenthesis represents [Coriolis acceleration](https://en.wikipedia.org/wiki/Coriolis_acceleration), the second term is due to [centrifugal acceleration](https://en.wikipedia.org/wiki/centrifugal_force), the third is due to the linear acceleration of $K'$ with respect to $K$ and the fourth term is due to the angular acceleration of $K'$ with respect to $K$.

## Other equations

The Navier–Stokes equations are strictly a statement of the balance of momentum. To fully describe fluid flow, more information is needed, how much depending on the assumptions made. This additional information may include boundary data ([no-slip](https://en.wikipedia.org/wiki/no-slip_condition), [capillary surface](https://en.wikipedia.org/wiki/capillary_surface), etc.), conservation of mass, [balance of energy](https://en.wikipedia.org/wiki/First_law_of_thermodynamics_%28fluid_mechanics%29), and/or an [equation of state](https://en.wikipedia.org/wiki/equation_of_state).

### Continuity equation for incompressible fluid

Regardless of the flow assumptions, a statement of the [conservation of mass](https://en.wikipedia.org/wiki/conservation_of_mass) is generally necessary. This is achieved through the mass [continuity equation](https://en.wikipedia.org/wiki/continuity_equation), as discussed above in the "General continuum equations" within this article, as follows:

$$
\begin{align}
\frac{\mathbf{D}m}{{\mathbf{Dt}}}&={\iiint\limits_V}\left({\frac{\mathbf{D}\rho}{{\mathbf{Dt}}} + \rho (\nabla \cdot \mathbf{u})}\right)dV \\
\frac{\mathbf{D}\rho}{{\mathbf{Dt}}} + \rho (\nabla \cdot{\mathbf{u}})&=\frac{\partial\rho}{\partial t} + ({\nabla \rho}) \cdot{\mathbf{u}} + {\rho}(\nabla \cdot \mathbf{u})= \frac{\partial\rho}{\partial t} + \nabla\cdot({\rho \mathbf{u}})= 0
\end{align}
$$

A fluid media for which the [density](https://en.wikipedia.org/wiki/density) $\rho$ is constant is called [*incompressible*](https://en.wikipedia.org/wiki/Incompressible_flow). Therefore, the rate of change of $\rho$ with respect to time $\frac{\partial\rho}{\partial t}$ and the [gradient](https://en.wikipedia.org/wiki/gradient) of density $\nabla \rho$ are equal to zero. In this case the general equation of continuity, $\frac{\partial\rho}{\partial t} + \nabla\cdot({\rho \mathbf{u}})= 0$, reduces to:

$$
\rho(\nabla{\cdot}{\mathbf{u}}) = 0
$$

 Furthermore, assuming that $\rho \neq 0$ means that the right-hand side of the equation (zero) is divisible by [density](https://en.wikipedia.org/wiki/density) $\rho$. Therefore, the continuity equation for an [incompressible fluid](https://en.wikipedia.org/wiki/Incompressible_flow) reduces further to:

$$
(\nabla{\cdot{\mathbf{u}}}) = 0
$$

This relationship, $(\nabla{\cdot{\mathbf{u}}}) = 0$, identifies that the [divergence](https://en.wikipedia.org/wiki/divergence) of the flow velocity [vector](https://en.wikipedia.org/wiki/Vector_field) $\mathbf{u}$ is equal to zero, which means that for an [incompressible fluid](https://en.wikipedia.org/wiki/Incompressible_flow) the [flow velocity field](https://en.wikipedia.org/wiki/Flow_velocity) is a [solenoidal vector field](https://en.wikipedia.org/wiki/solenoidal_vector_field) or a [divergence-free vector field](https://en.wikipedia.org/wiki/Divergence-free). Note that this relationship can be expanded upon due to its uniqueness with the [vector Laplace operator](https://en.wikipedia.org/wiki/vector_Laplace_operator) $\nabla ^{2} \mathbf{u} =\nabla (\nabla \cdot \mathbf{u} )-\nabla \times (\nabla \times \mathbf{u} )$, and [vorticity](https://en.wikipedia.org/wiki/vorticity) $\boldsymbol \omega = \nabla \times \mathbf{u}$ which is now expressed like so, for an [incompressible fluid](https://en.wikipedia.org/wiki/Incompressible_flow):

$$
\nabla ^{2}\mathbf {u} = - \bigl(\nabla \times (\nabla \times \mathbf {u} )\bigr) = - (\nabla \times \boldsymbol \omega)
$$

## Stream function for incompressible 2D fluid

Taking the [curl](https://en.wikipedia.org/wiki/Curl_%28mathematics%29) of the incompressible Navier–Stokes equation results in the elimination of pressure. This is especially easy to see if 2D Cartesian flow is assumed (like in the degenerate 3D case with $u_z = 0$ and no dependence of anything on $z$), where the equations reduce to:

$$
\begin{align}
 \rho \left(\frac{\partial u_x}{\partial t} + u_x \frac{\partial u_x}{\partial x} + u_y \frac{\partial u_x}{\partial y}\right)
 &= -\frac{\partial p}{\partial x} + \mu \left(\frac{\partial^2 u_x}{\partial x^2} + \frac{\partial^2 u_x}{\partial y^2}\right) + \rho g_x \\
 \rho \left(\frac{\partial u_y}{\partial t} + u_x \frac{\partial u_y}{\partial x} + u_y \frac{\partial u_y}{\partial y}\right)
 &= -\frac{\partial p}{\partial y} + \mu \left(\frac{\partial^2 u_y}{\partial x^2} + \frac{\partial^2 u_y}{\partial y^2}\right) + \rho g_y.
\end{align}
$$

Differentiating the first with respect to $y$, the second with respect to $x$ and subtracting the resulting equations will eliminate pressure and any [conservative force](https://en.wikipedia.org/wiki/conservative_force).
For incompressible flow, defining the [stream function](https://en.wikipedia.org/wiki/stream_function) $\psi$ through

$$
u_x = \frac{\partial \psi}{\partial y}; \quad u_y = -\frac{\partial \psi}{\partial x}
$$

results in mass continuity being unconditionally satisfied (given the stream function is continuous), and then incompressible Newtonian 2D momentum and mass conservation condense into one equation:

$$
\frac{\partial}{\partial t}\left(\nabla^2 \psi\right) + \frac{\partial \psi}{\partial y} \frac{\partial}{\partial x}\left(\nabla^2 \psi\right) - \frac{\partial \psi}{\partial x} \frac{\partial}{\partial y}\left(\nabla^2 \psi\right) = \nu \nabla^4 \psi
$$

where $\nabla^4$ is the 2D [biharmonic operator](https://en.wikipedia.org/wiki/biharmonic_operator) and $\nu$ is the [kinematic viscosity](https://en.wikipedia.org/wiki/kinematic_viscosity), $\nu = \frac{\mu}{\rho}$. We can also express this compactly using the [Jacobian determinant](https://en.wikipedia.org/wiki/Jacobian_matrix_and_determinant):

$$
\frac{\partial}{\partial t}\left(\nabla^2 \psi\right) + \frac{\partial\left(\psi, \nabla^2\psi \right)}{\partial(y,x)} = \nu \nabla^4 \psi.
$$

This single equation together with appropriate boundary conditions describes 2D fluid flow, taking only kinematic viscosity as a parameter. Note that the equation for [creeping flow](https://en.wikipedia.org/wiki/creeping_flow) results when the left side is assumed zero.

In [axisymmetric](https://en.wikipedia.org/wiki/axisymmetric) flow another stream function formulation, called the [Stokes stream function](https://en.wikipedia.org/wiki/Stokes_stream_function), can be used to describe the velocity components of an incompressible flow with one [scalar](https://en.wikipedia.org/wiki/scalar_%28mathematics%29) function.

The incompressible Navier–Stokes equation is a [differential algebraic equation](https://en.wikipedia.org/wiki/differential_algebraic_equation), having the inconvenient feature that there is no explicit mechanism for advancing the pressure in time. Consequently, much effort has been expended to eliminate the pressure from all or part of the computational process. The stream function formulation eliminates the pressure but only in two dimensions and at the expense of introducing higher derivatives and elimination of the velocity, which is the primary variable of interest.

## Properties

### Nonlinearity

The Navier–Stokes equations are [nonlinear](https://en.wikipedia.org/wiki/Nonlinearity) [partial differential equations](https://en.wikipedia.org/wiki/partial_differential_equations) in the general case and so remain in almost every real situation.[^26] [^27] In some cases, such as one-dimensional flow and [Stokes flow](https://en.wikipedia.org/wiki/Stokes_flow) (or creeping flow), the equations can be simplified to linear equations. The nonlinearity makes most problems difficult or impossible to solve and is the main contributor to the [turbulence](https://en.wikipedia.org/wiki/turbulence) that the equations model.

The nonlinearity is due to [convective](https://en.wikipedia.org/wiki/convective) acceleration, which is an acceleration associated with the change in velocity over position. Hence, any convective flow, whether turbulent or not, will involve nonlinearity. An example of convective but [laminar](https://en.wikipedia.org/wiki/laminar_flow) (nonturbulent) flow would be the passage of a viscous fluid (for example, oil) through a small converging [nozzle](https://en.wikipedia.org/wiki/nozzle). Such flows, whether exactly solvable or not, can often be thoroughly studied and understood.[^28]

### Turbulence

[Turbulence](https://en.wikipedia.org/wiki/Turbulence) is the time-dependent [chaotic](https://en.wikipedia.org/wiki/Chaos_theory) behaviour seen in many fluid flows. It is generally believed that it is due to the [inertia](https://en.wikipedia.org/wiki/inertia) of the fluid as a whole: the culmination of time-dependent and convective acceleration; hence flows where inertial effects are small tend to be laminar (the [Reynolds number](https://en.wikipedia.org/wiki/Reynolds_number) quantifies how much the flow is affected by inertia). It is believed, though not known with certainty, that the Navier–Stokes equations describe turbulence properly.[^29]

The numerical solution of the Navier–Stokes equations for turbulent flow is extremely difficult, and due to the significantly different mixing-length scales that are involved in turbulent flow, the stable solution of this requires such a fine mesh resolution that the computational time becomes significantly infeasible for calculation or [direct numerical simulation](https://en.wikipedia.org/wiki/direct_numerical_simulation). Attempts to solve turbulent flow using a laminar solver typically result in a time-unsteady solution, which fails to converge appropriately. To counter this, time-averaged equations such as the [Reynolds-averaged Navier–Stokes equations](https://en.wikipedia.org/wiki/Reynolds-averaged_Navier%E2%80%93Stokes_equations) (RANS), supplemented with turbulence models, are used in practical [computational fluid dynamics](https://en.wikipedia.org/wiki/computational_fluid_dynamics) (CFD) applications when modeling turbulent flows. Some models include the [Spalart–Allmaras](https://en.wikipedia.org/wiki/Spalart%E2%80%93Allmaras_turbulence_model), [ $k$– $ω$](https://en.wikipedia.org/wiki/k-omega_turbulence_model), [ $k$– $ε$](https://en.wikipedia.org/wiki/turbulence_kinetic_energy), and [SST](https://en.wikipedia.org/wiki/SST_%28Menter%27s_Shear_Stress_Transport%29) models, which add a variety of additional equations to bring closure to the RANS equations. [Large eddy simulation](https://en.wikipedia.org/wiki/Large_eddy_simulation) (LES) can also be used to solve these equations numerically. This approach is computationally more expensive—in time and in computer memory—than RANS, but produces better results because it explicitly resolves the larger turbulent scales.

### Applicability

Together with supplemental equations (for example, conservation of mass) and well-formulated boundary conditions, the Navier–Stokes equations seem to model fluid motion accurately; even turbulent flows seem (on average) to agree with real world observations.

The Navier–Stokes equations assume that the fluid being studied is a [continuum](https://en.wikipedia.org/wiki/Continuum_mechanics) (it is infinitely divisible and not composed of particles such as atoms or molecules), and is not moving at [relativistic velocities](https://en.wikipedia.org/wiki/Relativistic_velocity). At very small scales or under extreme conditions, real fluids made out of discrete molecules will produce results different from the continuous fluids modeled by the Navier–Stokes equations. For example, [capillarity](https://en.wikipedia.org/wiki/capillarity) of internal layers in fluids appears for flow with high gradients.[^30] For large [Knudsen number](https://en.wikipedia.org/wiki/Knudsen_number) of the problem, the [Boltzmann equation](https://en.wikipedia.org/wiki/Boltzmann_equation) may be a suitable replacement.[^31] Failing that, one may have to resort to [molecular dynamics](https://en.wikipedia.org/wiki/molecular_dynamics) or various hybrid methods.[^32]

Another limitation is simply the complicated nature of the equations. Time-tested formulations exist for common fluid families, but the application of the Navier–Stokes equations to less common families tends to result in very complicated formulations and often to open research problems. For this reason, these equations are usually written for [Newtonian fluid](https://en.wikipedia.org/wiki/Newtonian_fluid)s where the viscosity model is [linear](https://en.wikipedia.org/wiki/linear); truly general models for the flow of other kinds of fluids (such as blood) do not exist.[^33]

## Application to specific problems

The Navier–Stokes equations, even when written explicitly for specific fluids, are rather generic in nature and their proper application to specific problems can be very diverse. This is partly because there is an enormous variety of problems that may be modeled, ranging from as simple as the distribution of static pressure to as complicated as [multiphase flow](https://en.wikipedia.org/wiki/multiphase_flow) driven by [surface tension](https://en.wikipedia.org/wiki/surface_tension).

Generally, application to specific problems begins with some flow assumptions and initial/boundary condition formulation, this may be followed by [scale analysis](https://en.wikipedia.org/wiki/Scale_analysis_%28mathematics%29) to further simplify the problem.

<figure style={{"maxWidth": "132px"}}>

![Visualization of (a) parallel flow and (b) radial flow](https://pub-275e30003c354ac0862cc9839e0f952a.r2.dev/docs/math/NSConvection_vectorial.svg.png)

<figcaption>

Visualization of **(a)** parallel flow and **(b)** radial flow

</figcaption>

</figure>

### Parallel flow

Assume steady, parallel, one-dimensional, non-convective pressure-driven flow between parallel plates, the resulting scaled (dimensionless) [boundary value problem](https://en.wikipedia.org/wiki/boundary_value_problem) is:

$$
\frac{\mathrm{d}^2 u}{\mathrm{d} y^2} = -1; \quad u(0) = u(1) = 0.
$$

The boundary condition is the [no slip condition](https://en.wikipedia.org/wiki/no_slip_condition). This problem is easily solved for the flow field:

$$
u(y) = \frac{y - y^2}{2}.
$$

From this point onward, more quantities of interest can be easily obtained, such as viscous drag force or net flow rate.

### Radial flow

Difficulties may arise when the problem becomes slightly more complicated. A seemingly modest twist on the parallel flow above would be the *radial* flow between parallel plates; this involves convection and thus non-linearity. The velocity field may be represented by a function $f(z)$ that must satisfy:

$$
\frac{\mathrm{d}^2 f}{\mathrm{d} z^2} + R f^2 = -1; \quad f(-1) = f(1) = 0.
$$

This [ordinary differential equation](https://en.wikipedia.org/wiki/ordinary_differential_equation) is what is obtained when the Navier–Stokes equations are written and the flow assumptions applied (additionally, the pressure gradient is solved for). The [nonlinear](https://en.wikipedia.org/wiki/Nonlinearity) term makes this a very difficult problem to solve analytically (a lengthy [implicit](https://en.wikipedia.org/wiki/Implicit_function) solution may be found which involves [elliptic integral](https://en.wikipedia.org/wiki/elliptic_integral)s and [roots of cubic polynomials](https://en.wikipedia.org/wiki/Cubic_formula)). Issues with the actual existence of solutions arise for $R > 1.41$ (approximately; this is not [square root of 2](https://en.wikipedia.org/wiki/square_root_of_2)), the parameter $R$ being the Reynolds number with appropriately chosen scales.[^34] This is an example of flow assumptions losing their applicability, and an example of the difficulty in "high" Reynolds number flows.[^34]

### Convection

A type of natural convection that can be described by the Navier–Stokes equation is the [Rayleigh–Bénard convection](https://en.wikipedia.org/wiki/Rayleigh%E2%80%93B%C3%A9nard_convection). It is one of the most commonly studied convection phenomena because of its analytical and experimental accessibility.

## Exact solutions of the Navier–Stokes equations

Some exact solutions to the Navier–Stokes equations exist. Examples of degenerate cases—with the non-linear terms in the Navier–Stokes equations equal to zero—are [Poiseuille flow](https://en.wikipedia.org/wiki/Hagen-Poiseuille_equation), [Couette flow](https://en.wikipedia.org/wiki/Couette_flow) and the oscillatory [Stokes boundary layer](https://en.wikipedia.org/wiki/Stokes_boundary_layer). But also, more interesting examples, solutions to the full non-linear equations, exist, such as [Jeffery–Hamel flow](https://en.wikipedia.org/wiki/Jeffery%E2%80%93Hamel_flow), [Von Kármán swirling flow](https://en.wikipedia.org/wiki/Von_K%C3%A1rm%C3%A1n_swirling_flow), [stagnation point flow](https://en.wikipedia.org/wiki/stagnation_point_flow), [Landau–Squire jet](https://en.wikipedia.org/wiki/Landau%E2%80%93Squire_jet), and [Taylor–Green vortex](https://en.wikipedia.org/wiki/Taylor%E2%80%93Green_vortex).[^35] [^36] [^37] Time-dependent [self-similar](https://en.wikipedia.org/wiki/Self-similar_solution) solutions of the three-dimensional non-compressible Navier–Stokes equations in Cartesian coordinate can be given with the help of the [Kummer's function](https://en.wikipedia.org/wiki/Kummer%27s_function)s with quadratic arguments.[^38] For the compressible Navier–Stokes equations the time-dependent self-similar solutions are however the [Whittaker function](https://en.wikipedia.org/wiki/Whittaker_function)s again with quadratic arguments when the [polytropic](https://en.wikipedia.org/wiki/Polytrope) [equation of state](https://en.wikipedia.org/wiki/equation_of_state) is used as a closing condition.[^39] Note that the existence of these exact solutions does not imply they are stable: turbulence may develop at higher Reynolds numbers.

Under additional assumptions, the component parts can be separated.[^40]

### A three-dimensional steady-state vortex solution

<figure style={{"maxWidth": "250px"}}>

![Wire model of flow lines along a Hopf fibration](https://pub-275e30003c354ac0862cc9839e0f952a.r2.dev/docs/math/Hopfkeyrings.jpg)

<figcaption>

Wire model of flow lines along a [Hopf fibration](https://en.wikipedia.org/wiki/Hopf_fibration)

</figcaption>

</figure>
A steady-state example with no singularities comes from considering the flow along the lines of a [Hopf fibration](https://en.wikipedia.org/wiki/Hopf_fibration). Let $r$ be a constant radius of the inner coil. One set of solutions is given by:[^41]

$$
\begin{align}
\rho(x, y, z) &= \frac{3B}{r^2 + x^2 + y^2 + z^2} \\
p(x, y, z) &= \frac{-A^2B}{\left(r^2 + x^2 + y^2 + z^2\right)^3} \\
\mathbf{u}(x, y, z) &= \frac{A}{\left(r^2 + x^2 + y^2 + z^2\right)^2}\begin{pmatrix} 2(-ry + xz) \\ 2(rx + yz) \\ r^2 - x^2 - y^2 + z^2 \end{pmatrix} \\
g &= 0 \\
\mu &= 0
\end{align}
$$

for arbitrary constants $A$ and $B$. This is a solution in a non-viscous gas (compressible fluid) whose density, velocities and pressure goes to zero far from the origin. (Note this is not a solution to the Clay Millennium problem because that refers to incompressible fluids where $\rho$ is a constant, and neither does it deal with the uniqueness of the Navier–Stokes equations with respect to any [turbulence](https://en.wikipedia.org/wiki/turbulence) properties.) It is also worth pointing out that the components of the velocity vector are exactly those from the [Pythagorean quadruple](https://en.wikipedia.org/wiki/Pythagorean_quadruple) parametrization. Other choices of density and pressure are possible with the same velocity field:

### Viscous three-dimensional periodic solutions

Two examples of periodic fully-three-dimensional viscous solutions are described in.[^42]
These solutions are defined on a three-dimensional [torus](https://en.wikipedia.org/wiki/torus) $\mathbb{T}^3 = \mathbb{R}^3/{L\mathbb{Z}^3}$ and are characterized by positive and negative [helicity](https://en.wikipedia.org/wiki/hydrodynamical_helicity) respectively.
The solution with positive helicity is given by:

$$
\begin{align}
u_x &= \frac{4 \sqrt{2}}{3 \sqrt{3}} \, U_0 \left[\, \sin\left(k x - \frac\pi 3\right) \cos\left(k y + \frac\pi 3\right) \sin\left(k z + \frac\pi 2\right) - \cos\left(k z - \frac\pi 3\right) \sin\left(k x + \frac\pi 3\right) \sin\left(k y + \frac\pi 2\right) \,\right]  e^{-3 \nu k^2 t} \\
u_y &= \frac{4 \sqrt{2}}{3 \sqrt{3}} \, U_0 \left[\, \sin\left(k y - \frac\pi 3\right) \cos\left(k z + \frac\pi 3\right) \sin\left(k x + \frac\pi 2\right) - \cos\left(k x - \frac\pi 3\right) \sin\left(k y + \frac\pi 3\right) \sin\left(k z +\frac\pi 2\right) \,\right]  e^{-3 \nu k^2 t} \\
u_z &= \frac{4 \sqrt{2}}{3 \sqrt{3}} \, U_0 \left[\, \sin\left(k z - \frac\pi 3\right) \cos\left(k x + \frac\pi 3\right) \sin\left(k y + \frac\pi 2\right) - \cos\left(k y - \frac\pi 3\right) \sin\left(k z + \frac\pi 3\right) \sin\left(k x + \frac\pi 2\right) \,\right]  e^{-3 \nu k^2 t}
\end{align}
$$

where $k = 2 \pi/L$ is the wave number and the velocity components are normalized so that the average kinetic energy per unit of mass is $U_0^2/2$ at $t = 0$.
The pressure field is obtained from the velocity field as $p = p_0 - \rho_0 \| \boldsymbol{u} \|^2/2$ (where $p_0$ and $\rho_0$ are reference values for the pressure and density fields respectively).
Since both the solutions belong to the class of [Beltrami flow](https://en.wikipedia.org/wiki/Beltrami_flow), the vorticity field is parallel to the velocity and, for the case with positive helicity, is given by $\omega =\sqrt{3} \, k \, \boldsymbol{u}$.
These solutions can be regarded as a generalization in three dimensions of the classic two-dimensional [Taylor–Green vortex](https://en.wikipedia.org/wiki/Taylor%E2%80%93Green_vortex).

### OpenAI announcement

On 8 September 2026, [artificial intelligence](https://en.wikipedia.org/wiki/artificial_intelligence) company [OpenAI](https://en.wikipedia.org/wiki/OpenAI) announced it had solved the [Millennium Prize Problem](https://en.wikipedia.org/wiki/Millennium_Prize_Problems) on [the existence and smoothness of the incompressible Navier–Stokes](https://en.wikipedia.org/wiki/Navier%E2%80%93Stokes_existence_and_smoothness) equations in [three-dimensional Euclidean space](https://en.wikipedia.org/wiki/Three-dimensional_space).[^43] [^44] OpenAI stated that the solution to the problem, a counterexample that refers to statements C and D of the problem statement,[^45] was developed by its researchers using as many as 10,000 coordinated [agents](https://en.wikipedia.org/wiki/AI_agent) running an internal [frontier model](https://en.wikipedia.org/wiki/frontier_model), along with a formalization in the [Lean](https://en.wikipedia.org/wiki/Lean_%28proof_assistant%29) proof assistant. The claim has not been verified by external mathematicians or the Clay Mathematics Institute, while OpenAI stated it would not claim the Millennium Prize. The announcement was accompanied by a [priority dispute](https://en.wikipedia.org/wiki/Scientific_priority) with [Levent Alpöge](https://en.wikipedia.org/wiki/Levent_Alp%C3%B6ge) (employed at rival AI company [Anthropic](https://en.wikipedia.org/wiki/Anthropic)) and [Tristan Buckmaster](https://en.wikipedia.org/wiki/Tristan_Buckmaster), who had derived a set of closely related results on the [Euler equations](https://en.wikipedia.org/wiki/Euler_equations_%28fluid_dynamics%29).[^46] [^47] The method used to generate the claimed solution built upon a method developed by Diego Córdoba and Luis Martínez Zoroa in 2023[^48] to prove blowup phenomena in related fluid equations.[^49]

## Wyld diagrams

**Wyld diagrams** are bookkeeping [graphs](https://en.wikipedia.org/wiki/Graph_%28discrete_mathematics%29) that correspond to the Navier–Stokes equations via a [perturbation expansion](https://en.wikipedia.org/wiki/perturbation_theory) of the fundamental [continuum mechanics](https://en.wikipedia.org/wiki/continuum_mechanics). Similar to the [Feynman diagram](https://en.wikipedia.org/wiki/Feynman_diagram)s in [quantum field theory](https://en.wikipedia.org/wiki/quantum_field_theory), these diagrams are an extension of [Mstislav Keldysh](https://en.wikipedia.org/wiki/Mstislav_Keldysh)'s technique for nonequilibrium processes in fluid dynamics. In other words, these diagrams assign [graphs](https://en.wikipedia.org/wiki/graph_theory) to the (often) [turbulent](https://en.wikipedia.org/wiki/turbulence) phenomena in turbulent fluids by allowing [correlated](https://en.wikipedia.org/wiki/correlation_function) and interacting fluid particles to obey [stochastic processes](https://en.wikipedia.org/wiki/stochastic_processes) associated to [pseudo-random](https://en.wikipedia.org/wiki/pseudo-random) [functions](https://en.wikipedia.org/wiki/function_%28mathematics%29) in [probability distribution](https://en.wikipedia.org/wiki/probability_distribution)s.[^50]

## Representations in 3D

Note that the formulas in this section make use of the single-line notation for partial derivatives, where, e.g. $\partial_x u$ means the partial derivative of $u$ with respect to $x$, and $\partial_y^2 f_\theta$ means the second-order partial derivative of $f_\theta$ with respect to $y$.

A 2022 paper provides a less costly, dynamical and recurrent solution of the Navier-Stokes equation for 3D turbulent fluid flows. On suitably short time scales, the dynamics of turbulence is deterministic.[^51]

### Cartesian coordinates

From the general form of the Navier–Stokes, with the velocity vector expanded as $\mathbf{u} = (u_x, u_y, u_z)$, sometimes respectively named $u$, $v$, $w$, we may write the vector equation explicitly,

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

Note that gravity has been accounted for as a body force, and the values of $g_x$, $g_y$, $g_z$ will depend on the orientation of gravity with respect to the chosen set of coordinates.

The continuity equation reads:

$$
\partial_t \rho + \partial_x (\rho u_x) + \partial_y (\rho u_y) + \partial_z (\rho u_z) = 0.
$$

When the flow is incompressible, $\rho$ does not change for any fluid particle, and its [material derivative](https://en.wikipedia.org/wiki/material_derivative) vanishes: $\frac{\mathrm{D} \rho}{\mathrm{D}t} = 0$. The continuity equation is reduced to:

$$
\partial_x u_x + \partial_y u_y + \partial_z u_z = 0.
$$

Thus, for the incompressible version of the Navier–Stokes equation the second part of the viscous terms fall away (see [Incompressible flow](https://en.wikipedia.org/wiki/Incompressible_flow)).

This system of four equations comprises the most commonly used and studied form. Though comparatively more compact than other representations, this is still a [nonlinear](https://en.wikipedia.org/wiki/Nonlinearity) system of [partial differential equations](https://en.wikipedia.org/wiki/partial_differential_equations) for which solutions are difficult to obtain.

### Cylindrical coordinates

A change of variables on the Cartesian equations will yield[^19] the following momentum equations for $r$, $\phi$, and $z$[^52]

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

The gravity components will generally not be constants, however for most applications either the coordinates are chosen so that the gravity components are constant or else it is assumed that gravity is counteracted by a pressure field (for example, flow in horizontal pipe is treated normally without gravity and without a vertical pressure gradient). The continuity equation is:

$$
{\partial_t\rho} + \frac{1}{r} \partial_r \left(\rho r u_r\right) + \frac{1}{r} {\partial_\varphi \left(\rho u_\varphi\right)} + {\partial_z \left(\rho u_z\right)} = 0.
$$

This cylindrical representation of the incompressible Navier–Stokes equations is the second most commonly seen (the first being Cartesian above). Cylindrical coordinates are chosen to take advantage of symmetry, so that a velocity component can disappear. A very common case is axisymmetric flow with the assumption of no tangential velocity ( $u_\phi = 0$), and the remaining quantities are independent of $\phi$:

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

### Spherical coordinates

In [spherical coordinates](https://en.wikipedia.org/wiki/spherical_coordinates), the $r$, $\phi$, and $\theta$ momentum equations are[^19] (note the convention used: $\theta$ is polar angle, or [colatitude](https://en.wikipedia.org/wiki/colatitude),[^53] $0 \leq \theta \leq \pi$):

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

Mass continuity will read:

$$
{\partial_t \rho} + \frac{1}{r^2} \partial_r \left(\rho r^2 u_r\right) + \frac{1}{r \sin\theta}{\partial_\varphi (\rho u_\varphi)} + \frac{1}{r \sin\theta} \partial_\theta \left(\sin\theta \rho u_\theta\right) = 0.
$$

These equations could be (slightly) compacted by, for example, factoring $\frac{1}{r^2}$ from the viscous terms. However, doing so would undesirably alter the structure of the Laplacian and other quantities.

## See also

* [Saint Venant equation](https://en.wikipedia.org/wiki/Saint_Venant_equation)
* [Chapman–Enskog theory](https://en.wikipedia.org/wiki/Chapman%E2%80%93Enskog_theory)
* [Churchill–Bernstein equation](https://en.wikipedia.org/wiki/Churchill%E2%80%93Bernstein_equation)
* [Coandă effect](https://en.wikipedia.org/wiki/Coand%C4%83_effect)
* [Pressure-correction method](https://en.wikipedia.org/wiki/Pressure-correction_method)
* [Primitive equations](https://en.wikipedia.org/wiki/Primitive_equations)
* [Reynolds transport theorem](https://en.wikipedia.org/wiki/Reynolds_transport_theorem)

## Notes


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
## General references

* Acheson, D. J. (1990). *Elementary Fluid Dynamics*. *Oxford University Press*. ISBN 978-0-19-859679-0. [Elementary Fluid Dynamics](https://books.google.com/books?id=IGfDBAAAQBAJ).
* Batchelor, G. K. (1967). *An Introduction to Fluid Dynamics*. *Cambridge University Press*. ISBN 978-0-521-66396-0.
* Currie, I. G. (1974). *Fundamental Mechanics of Fluids*. *McGraw-Hill*. ISBN 978-0-07-015000-3.
* [V. Girault](https://en.wikipedia.org/wiki/Vivette_Girault) and P. A. Raviart. *Finite Element Methods for Navier–Stokes Equations: Theory and Algorithms*. Springer Series in Computational Mathematics. Springer-Verlag, 1986
* Landau, L. D.; Lifshitz, E. M. (1987). *Fluid mechanics*. *Pergamon Press* ***[Course of Theoretical Physics](https://en.wikipedia.org/wiki/Course_of_Theoretical_Physics)* Volume 6**. ISBN 978-0-08-033932-0.
* Polyanin, A. D.; Kutepov, A. M.; Vyazmin, A. V.; Kazenin, D. A. (2002). *Hydrodynamics, Mass and Heat Transfer in Chemical Engineering*. *Taylor & Francis, London*. ISBN 978-0-415-27237-7.
* Rhyming, Inge L. (1991). *Dynamique des fluides*. *Presses polytechniques et universitaires romandes*.
* Smits, Alexander J. (2014), *A Physical Introduction to Fluid Mechanics*, Wiley, ISBN 0-47-1253499
* Temam, Roger (1984): *Navier–Stokes Equations: Theory and Numerical Analysis*, ACM Chelsea Publishing, ISBN 978-0-8218-2737-6
* [Milne-Thomson, L.M.](https://en.wikipedia.org/wiki/L._M._Milne-Thomson), [C.B.E](https://en.wikipedia.org/wiki/Order_of_the_British_Empire) (1962), *Theoretical Hydrodynamics*, Macmillan & Company Limited
* Tartar, L (2006), *An Introduction to Navier Stokes Equation and Oceanography,* Springer ISBN 3-540-35743-2
* [Birkhoff, Garrett](https://en.wikipedia.org/wiki/Garrett_Birkhoff) (1960)*, Hydrodynamics,* Princeton University Press
* Campos, D. (editor) (2017) *Handbook on Navier-Stokes Equations Theory and Applied Analysis*, Nova Science Publisher ISBN 978-1-53610-292-5
* [Döring, C.E.](https://en.wikipedia.org/wiki/Charles_R._Doering) and J.D. Gibbon, J.D. (1995) *Applied analysis of the Navier-Stokes equations,* Cambridge University Press, ISBN 0-521-44557-4
* [Basset, Alfred Barnard](https://en.wikipedia.org/wiki/Alfred_Barnard_Basset) (1888) *Hydrodynamics Volume I and II,* Cambridge: Delighton, Bell and Company
* Fox, R. W.; McDonald, A. T.; and Pritchard, P. J. (2004) *Introduction to Fluid Mechanics*, John Wiley and Sons, ISBN 0-471-20231-2
* Foias, C.; Mainley, O.; Rosa, R.; and Temam, R. (2004) *Navier–Stokes Equations and Turbulence*, Cambridge University Press, ISBN 0-521-36032-3
* [Lions, P-L](https://en.wikipedia.org/wiki/Pierre-Louis_Lions). (1998) *Mathematical Topics in Fluid Mechanics* Volume 1 and 2, Clarendon Press, ISBN 0-19-851488-3
* Deville, M. O. and Gatski, T. B. (2012) *Mathematical Modeling for Complex Fluids and Flows,* Springer, ISBN 978-3-642-25294-5
* Kochin, N. E.; Kibel, I. A.; and Roze, N. V. (1964) *Theoretical Hydromechanics,* John Wiley & Sons, Limited
* [Lamb, Horace](https://en.wikipedia.org/wiki/Horace_Lamb) (1879) *Hydrodynamics,* Cambridge University Press
* White, Frank M. (2006). *Viscous Fluid Flow*. *McGraw-Hill*. ISBN 978-0-07-124493-0.

## External links

* [Simplified derivation of the Navier–Stokes equations](https://web.archive.org/web/20171129091339/http://www.allstar.fiu.edu/aero/Flow2.htm)
* [Three-dimensional unsteady form of the Navier–Stokes equations](https://www.grc.nasa.gov/www/k-12/airplane/nseqs.html) Glenn Research Center, NASA
