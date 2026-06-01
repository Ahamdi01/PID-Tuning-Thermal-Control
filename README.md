# Comparative Analysis of PID Tuning Methods for Thermal Process Control Systems

## Overview
A comparative study of three PID tuning methods applied to a thermal process control system, 
simulated in MATLAB/Simulink. The goal was to identify the optimal tuning strategy based on 
system response characteristics including rise time, settling time, and overshoot.

## Tuning Methods Evaluated
- **Ziegler-Nichols** — Fast response but produced excessive overshoot
- **Cohen-Coon** — Led to system instability under thermal load conditions  
- **Takahashi** — Delivered the best overall performance, achieving optimal balance 
  between stability and response speed ✅

## Key Finding
The Takahashi method outperformed both Ziegler-Nichols and Cohen-Coon for this thermal 
system, providing stable control with acceptable response speed — making it the recommended 
tuning approach for similar thermal process applications.

## Tools Used
- MATLAB/Simulink
- Simscape (thermal modelling)

## Project Structure
## Results
See `/results` folder for step response plots comparing all three tuning methods.

## Author
**Ahamdi Ogiri Miracle**  
Electrical & Electronics Engineer  
[LinkedIn](https://www.linkedin.com/in/ahamdi-ogiri-30b416304)
