# AFSD-Process-Control
![afsd app](https://github.com/akshansh11/AFSD-Process-Control/assets/47514698/62879c29-5f63-45ab-9471-759c431a687c)

The AFSD Process Control Simulation application is designed to provide users with an interactive platform to simulate and visualize the control dynamics involved in the Additive Friction Stir Deposition (AFSD) process. The primary objective of this application is to help users understand how various control parameters influence the temperature and force during the AFSD process. By adjusting parameters such as proportional and integral gains for temperature and force, as well as desired temperature and force values, users can observe real-time changes in system behavior.

The simulation incorporates a feedback control loop where the temperature and force are adjusted based on the error between the desired and measured values. The app logs these values over time and presents them in a clear, graphical format, allowing users to see how changes in control parameters impact the stability and performance of the process.

Here are the names and descriptions of the control parameters for the AFSD Process Control Simulation:

*kp_T (Proportional Gain for Temperature Control): This parameter controls the proportional response of the system to temperature errors. A higher value means a stronger reaction to deviations from the desired temperature.

*ki_T (Integral Gain for Temperature Control): This parameter controls the integral response of the system to temperature errors. It helps eliminate steady-state errors by integrating past errors over time.

*kp_F (Proportional Gain for Force Control): This parameter controls the proportional response of the system to force errors. A higher value means a stronger reaction to deviations from the desired force.

*ki_F (Integral Gain for Force Control): This parameter controls the integral response of the system to force errors. It helps eliminate steady-state errors by integrating past errors over time.

*omega_nom (Nominal Spindle Speed): This is the nominal or average spindle speed (in RPM) around which the spindle speed will be adjusted during the process.

*omega_min (Minimum Spindle Speed): This is the minimum allowable spindle speed during the process.

*omega_max (Maximum Spindle Speed): This is the maximum allowable spindle speed during the process.

*zeta_nom (Nominal Damping Ratio): This is the nominal or average damping ratio used in the control system to manage the dynamics of the AFSD process.

*zeta_min (Minimum Damping Ratio): This is the minimum allowable damping ratio during the process.

*zeta_max (Maximum Damping Ratio): This is the maximum allowable damping ratio during the process.

*T_desired (Desired Temperature): This is the target temperature that the control system aims to maintain during the AFSD process.

*F_desired (Desired Force): This is the target force that the control system aims to maintain during the AFSD process.

*kf (Force Sensitivity Coefficient): This coefficient represents the sensitivity of the system's force response to changes in the control input. It is used to model the system dynamics and adjust the force accordingly.
App Link: https://afsd-process-control-9wjfgxeydxnbux8q58wjxo.streamlit.app/
