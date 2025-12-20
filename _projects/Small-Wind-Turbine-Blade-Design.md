---
layout: project
title: Small Wind Turbine Blade Design
description: Aerodynamic design, fabrication, and wind tunnel testing of a small-scale turbine blade
technologies: [MATLAB, Fusion 360, Wind Tunnel Testing, Additive Manufacturing]
image: /assets/images/turbine.png
---

## Project Overview
As part of MAE 4272: Fluids and Heat Transfer Laboratory at Cornell University, my team designed, fabricated, and experimentally evaluated a small-scale wind turbine blade. The objective was to maximize power production at a fixed angular velocity while operating under wind conditions described by a Weibull distribution. The design needed to satisfy strict geometric, structural, and operational constraints imposed by the laboratory wind tunnel and testing hardware.

## Design Process
Our blade design used a blended airfoil approach to balance structural strength and aerodynamic efficiency along the blade span. We selected a NACA 4412 airfoil near the root to handle higher bending loads and a NACA 6409 airfoil near the tip to improve lift-to-drag performance at higher local flow velocities. Using a blade element method implemented in MATLAB, we determined the chord distribution, twist profile, and airfoil transition locations. The final geometry consisted of nine smoothly blended cross sections and was modeled in CAD before being manufactured using stereolithography with Accura 25 resin.

## Testing and Analysis
The blades were tested in a wind tunnel across wind speeds ranging from 2.9 to 5.8 m/s. At each wind speed, torque was incrementally applied using a magnetic particle brake to generate full power curves. We collected torque, rotational speed, and wind speed data under steady-state conditions and used this data to calculate power output, power coefficient, and tip speed ratio. The results showed peak efficiency at a tip speed ratio of approximately six and identified an optimal operating angular velocity for the blade, providing insight into aerodynamic performance and mechanical losses.

## My Contribution
I contributed to the aerodynamic design and analysis of the blade, including airfoil selection, MATLAB-based blade element calculations, and interpretation of performance data. I also assisted with CAD modeling, experimental testing in the wind tunnel, and post-processing of experimental results to generate power curves and efficiency metrics.

## Figures
![Blade CAD model]({{ "/assets/images/blade_design.png" | relative_url }}){: style="width: 350px"}

![Blade CAD model]({{ "/assets/images/blade_cad.png" | relative_url }}){: style="width: 350px"}

![Power curves from experimental testing]({{ "/assets/images/power_curves.png" | relative_url }}){: style="width: 350px"}
