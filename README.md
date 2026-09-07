# Vehicle-Dynamics-simulator🏎️
A Python-based vehicle dynamics simulator developed to investigate the lateral behaviour and handling characteristics of an F1-car🏎️📊
## About🔍
To investigate how vehicle parameters influence the handling behaviour of an F1 car, with focus on:
- Transient yaw response
- Understeer and oversteer
- Front/rear tyre balance
- Steady state behaviour
- Yaw rate gain
- Vehicle stability
## Notes ⚠️
At first I quantified a 20% reduction, however after changing some values I calculated a 35% reduction in steady state yaw gain
## Bicycle model🚴
A real car has two front wheels, generating their own lateral force. For lateral dynamics analysis, which is important in motorsport, the two front wheels behave similarly enough so we treat them as one wheel. This is known as the bicycle model, where a 4 wheeled car transforms into a 2 wheeled car. Containing 2 DOFS (lateral velocity and yaw rate)

The model is derived from Newton's second law and validated through steady-state analysis and time-domain simulation. 

I built this for experience of what engineers do with simplified models to make decisions using vehicle dynamics before real, physical track testing.
## Tools used💻
Python, numPy, matplotlib, SciPy
