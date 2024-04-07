## Introduction
This repository includes my implementations of optimal control algorithms such as LQR and MPC for non-linear systems. These were done as part of coursework in the graduate course: [16745 - Optimal Control and Reinforcement Learning](https://optimalcontrol.ri.cmu.edu/) at CMU Robotics Institute (Spring 2023). 

Jump to section: 
- [LQR for a Non-Linear Cartpole System](https://github.com/shivamtrip/robot-control/blob/main/README.md#lqr-for-a-non-linear-cartpole-system)
- [MPC for Optimal Rendezvous and Docking of a Spacecraft](https://github.com/shivamtrip/robot-control/edit/main/README.md#mpc-for-optimal-rendezvous-and-docking-of-a-spacecraft)

<br />

## LQR for a Non-Linear Cartpole System 
**Goals:** 
- Implement Infinite Horizon LQR (IHLQR) to stabilize a non-linear cartpole system about an unstable equilibrium point <br />
- Implement Time Varying LQR (TVLQR) to track a given swing-up trajectory for a non-linear cartpole system <br />
  
**Implementation:** [lqr_cartpole](lqr_cartpole/lqr_cartpole.ipynb)
 Infinite Horizon LQR (IHLQR) | Time Varying LQR (TVLQR)
:-------------------------:|:-------------------------:
<br /> <img src="https://github.com/shivamtrip/robot-control/assets/66013750/31ed393a-06cb-4784-abb0-ad50c415e344" width="400"> &nbsp; | <br /> <img src = "https://github.com/shivamtrip/robot-control/assets/66013750/d1fefc23-ec37-4bbb-9602-1107807ca1a9" width="400"> <br />

<br />

## MPC for Optimal Rendezvous and Docking of a Spacecraft
**Goal:** Implement Model Predictive Control (MPC) to optimally rendezvous and dock a spacecraft of given dynamics with the ISS <br />
**Implementation:** [mpc_spacecraft](mpc_spacecraft/mpc_spacecraft.ipynb)

 MPC for Spacecraft Rendezvous and Docking |  
:-------------------------:
<br /> <img src="https://github.com/shivamtrip/robot-control/assets/66013750/37b91a31-2c93-4afd-bb12-5ab7fb205cce" width="600"> |
