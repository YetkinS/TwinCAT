# An alternative approach for sensor or actuator zero-span calibration

The idea is simple. The derivative of the input signal is equal to the change rate of the signal. If a significant positive increase occurs in the change rate of the signal, then that is the zero error. If a considerable negative decrease occurs in the signal, then that is the span error.

For example, when a valve is closed (0% opening) and starts to open, the signal's derivative will be close to zero. When a sudden increase occurs in the signal during valve opening (0% -> 100%), the change rate of the signal will increase, and this increment will be detected, so the zero error of the instrument will be found. 
