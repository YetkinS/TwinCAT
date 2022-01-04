# Water-tank system (Level Control)

In this sample project, a non-linear model of a water-tank system is controller with a discrete PI controller in real-time. The non-linear plant was linearized in Matlab, and controller gains were obtained. The plant non-linear model was exported from Simulink using C++ coder to the TwinCAT runtime environment. In addition, the controller gains can be tuned using the autotune function block.
