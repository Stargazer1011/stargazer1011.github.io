# Rocket Personal Projcet
2026-11-14
## What I hope to learn from this project
The goal of this project is to recreate UCSD SEDS's Moonshine rocket. 

I want to learn the skills of designing a rocket engine to hopefully get accepted into one of the rocketry clubs. 

## Objective 
Design everything of the rocket up until physically building the rocket. 
Including CEA (Chemical Equilibrium Analysis), CAD (Computer Aided Design), and CFD (Computational Fluid Dynamics).

## Parameters 
All the parameters are based on SEDS UCSD's Moonshine Block 1 engine.

| Parameters | Values |
| ---------- | ------ |
| Thrust | 550 lbF |
| Chamber Pressure | 500 PSI |
| Fuel | LOX/IPA (Isopropal Alcholol) |
| Chamber material | Stainless Steel |
| Ignition | Solid Ingiter |
| Cooling | Film Cooling |

## Build Log
You know that one meme of a fighter jet pilot reading a book that says "how to fly" while in the air? That was how I was feeling this entire time. 

To start I needed to do Chemical Equilibrium Analysis for the fuel I'm using the my target chamber pressure. 

I started out knowing nothing about CEA, thankfully I reached out to a friend who is in SEDS who pointed me in the right direction, and told me that there is a free [website](https://cearun.grc.nasa.gov/) developed by NASA that can do CEA for you. (thanks Zander!)
In addition to that, I also found a [website](https://spacha.github.io/How-to-Rocket/) that has a tutorial for how to build a simple rocket engine, so I used the equation provided in there in addition to the data outputted by CEA to calculate the nozzle size + combustion chamber size. (I had to look up some equations, for example the cross-sectional area of the nozzle throat is too complcated so I used a equation with C* in it: $A_t=\frac{\dot{m}C^*}{P_c}$ where $A_t$ is the throat cross-sectional area. $\dot{m}$ is the mass flow rate, and ${P_c}$ is the chamber pressure) 

