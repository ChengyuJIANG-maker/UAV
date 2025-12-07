Robust Control and Trajectory Planning for UAVs in Complex Environments
This project addresses the challenge of autonomous UAV navigation in complex low-altitude scenarios, such as highland mountainous regions. We propose an integrated framework combining robust control and intelligent trajectory planning. The system integrates an adaptive PID controller, Extended Kalman Filter (EKF)-based wind disturbance estimation, and an enhanced 26-neighborhood A* path planning algorithm, enabling high-precision trajectory tracking and real-time obstacle avoidance under strong winds, turbulence, vortexes, and randomly distributed obstacles.

Key Features:

🌪️ Multi-physics Simulation Environment: Models mean wind, Dryden turbulence, discrete vortexes, and sensor noise.
🧠 Adaptive Robust Control: Achieves a 57% reduction in average position error (0.20 m) compared to conventional PID and sliding-mode control.
🗺️ 3D Obstacle-Aware Path Planning: Supports 26-directional search, collinear pruning, and cubic spline smoothing for curvature-continuous, dynamically feasible trajectories.
🛠️ Modular Simulation Platform: GUI-based system for parameter tuning, interactive obstacle editing, and algorithm performance comparison.
This open-source project serves as a reliable prototype for real-world applications like low-altitude logistics, mountain agricultural delivery, and emergency response, and is also well-suited for academic teaching and research in flight control and autonomous navigation.
