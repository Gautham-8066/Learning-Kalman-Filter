# Learning-Kalman-Filter
A basic implementation of Kalman Filter to understand its working.

Kalman filter is a filter which is used to find the required measurements from the available measurements when the required measurement cannot be directly measured due to limitations of some kind.Additionally, it is the primary tool used to recover the 'true' signal when measurements are corrupted by noise, interference, or sensor inaccuracies.

I used a potentiometer to get a true value then using code,added random numbers to the true value.This represents a bad sensor.Then I fed this noisy value to the kalman filter.
For analyzing,all three values were plotted in the serial monitor.

In short I broke a signal on purpose, and then used the Kalman Filter to fix it😂
<img width="1906" height="1007" alt="image" src="https://github.com/user-attachments/assets/1e2aec52-791c-413b-b483-fb82dd25ade9" />
The Blue Line (Real Value)
The Orange Line(Real + Random Noise)
The Green Line(Output from filter)
https://github.com/user-attachments/assets/4f77ab25-4a7d-4c5b-b852-38438cc06ce6

