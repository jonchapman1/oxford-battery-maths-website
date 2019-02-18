+++
date = "2019-02-07"
short_text = "Valentin Sulzer, Jon Chapman and Colin Please have submitted a two-part paper to ECS on 'Faster Lead-Acid Battery Simulations from Porous-Electrode Theory'."
title = "Lead-acid papers"
[[authors]]
   name = "Valentin Sulzer"
   is_member = true
   link = "/sulzer"
+++

Valentin Sulzer, Jon Chapman and Colin Please have submitted a two-part paper to ECS on 'Faster Lead-Acid Battery Simulations from Porous-Electrode Theory', now available on ArXiv [[part I](https://arxiv.org/pdf/1902.01774.pdf), [part II](https://arxiv.org/pdf/1902.01774.pdf)].

## I. Physical Model

An isothermal porous-electrode model of a discharging lead-acid battery is presented, which includes an extension of concentrated-solution theory that accounts for excluded-volume effects, local pressure variation, and a detailed microscopic water balance. The approach accounts for three typically neglected physical phenomena: convection, pressure diffusion, and variation of liquid volume with state of charge. Rescaling of the governing equations uncovers a set of fundamental dimensionless parameters that control the battery's response. Total volume change during discharge and nonuniform pressure prove to be higher-order effects in cells where variations occur in just one spatial dimension. A numerical solution is developed and exploited to predict transient cell voltages and internal concentration profiles in response to a range of C-rates. The dependence of discharge capacity on C-rate deviates substantially from Peukert's simple power law: charge capacity is concentration-limited at low C-rates, and voltage-limited at high C-rates. The model is fit to experimental data, showing good agreement.

## II. Asymptotic Analysis

Electrochemical and equivalent-circuit modelling are the two most popular approaches to battery simulation, but the former is computationally expensive and the latter provides limited physical insight. A theoretical middle ground would be useful to support battery management, on-line diagnostics, and cell design. We analyse a thermodynamically consistent, isothermal porous-electrode model of a discharging lead-acid battery. Asymptotic analysis of this full model produces three reduced-order models, which relate the electrical behaviour to microscopic material properties, but simulate discharge at speeds approaching an equivalent circuit. A lumped-parameter model, which neglects spatial property variations, proves accurate for C-rates below 0.1C, while a spatially resolved higher-order solution retains accuracy up to 5C. The problem of parameter estimation is addressed by fitting experimental data with the reduced-order models.
