# Vehicle-Dynamics-simulator
## Bicycle model
A real car has two front wheels, generating their own lateral force. For lateral dynamics analysis, which is important in motorsport, the two front wheels behave similarly enough so we treat them as one wheel. This is known as the bicycle model, where a 4 wheeled car transforms into a 2 wheeled car. Containing 2 DOFS (lateral velocity and yaw rate)

The model is derived from Newton's second law and validated through steady-state analysis and time-domain simulation. 

I built this for experience of what engineers do with simplified models to make decisions using vehicle dynamics before real, physical track testing.

## Key plots and findings
<img width="883" height="392" alt="image" src="https://github.com/user-attachments/assets/b0677412-149f-47d3-aeda-d0a90f6de4e1" />

## Tools used
Python, numPy, matplotlib, SciPy, pandas
