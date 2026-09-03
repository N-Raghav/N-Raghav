# Hi, I'm Raghav Nallaperumal
**MS Robotics Engineering @ WPI | Perception • Robot Learning • Sensor Fusion**

📧 [raghavnallaperumal753@gmail.com](mailto:raghavnallaperumal753@gmail.com)
🌐 [Portfolio](https://raghav-nallaperumal.vercel.app) | [LinkedIn](https://www.linkedin.com/in/raghav-nallaperumal/)

I build intelligent robotic systems that perceive, learn, and act in the real world. My work spans vision-based perception (MonoSense, VIO, NeRF), learning-based manipulation (deep RL, imitation learning), and real hardware deployment (Franka Panda, UR5e, Crazyflie).

## Current Research

Graduate Research Assistant, Aerial-robot Controls and Perception Lab (ACP Lab), WPI, advised by Dr. Guanrui Li. Building a monocular depth prediction network that generates information for reinforcement learning exploration policy, so a quadrotor can navigate unknown, maze-like environments without depending on information that isn't available once it's actually deployed.

## Recent Projects

🚗 **[MonoSense](https://github.com/N-Raghav/Mono-Sense)** – Autonomous driving perception pipeline: custom YOLO (0.564 mAP50 on BDD100K, 0.859 mAP50 on LISA traffic signs), DepthAnythingV2, FCOS3D 3D pose, UFLDv2 lane detection. 27,000 synthetic frames rendered across 13 scenes on a SLURM A30 cluster; a 1D Kalman filter cut lane projection variance 60% on curved roads.

🛸 **[Deep VIO](https://github.com/N-Raghav/Deep-Visual-Inertial-Odometry)** – 6 visual-inertial odometry approaches compared for UAVs, including MSCKF, a 15-state EKF, a DeepVO-style LSTM, and a cross-modal transformer. MSCKF reached 0.12m ATE RMSE over a 73m EuRoC trajectory (0.21% drift).

🤖 **[Imitation Learning](https://github.com/N-Raghav/Imitation-Learning-Agent)** – BC-Transformer vs Diffusion Policy for UR5e contact-rich block stacking, trained on 158 human teleoperation demos. BC-Transformer hit 100% rollout success by epoch 950; Diffusion Policy reached 80% by epoch 350 and stayed non-zero with as few as 5 demos.

🎮 **[Deep RL for Picking](https://github.com/N-Raghav/Reinforcement-Learning-for-Picking-Task)** – REINFORCE, A2C, and A3C built from scratch. A2C cut reward variance 29% versus REINFORCE (201.7 vs 175.3 mean reward); A3C reached 31% grasp success on a PyBullet Kuka arm.

📐 **[SfM + NeRF](https://github.com/N-Raghav/SfM-and-NeRF)** – 3D reconstruction from scratch: bundle adjustment cut reprojection error 36%, NeRF training reached 27.3 dB PSNR / 0.90 SSIM.

🚁 **[Quadrotor Control](https://github.com/N-Raghav/Drone-Control-Methods)** – PD and LQR control on a Crazyflie 2.0. System identification cut sim-to-real RMSE 83% (4.8mm to 0.8mm); LQR held hardware position error below 2cm.

## Tech Stack

**Languages:** Python, C++, CUDA, MATLAB
**Robotics:** ROS 2 (Humble), MoveIt 2, Nav2, Gazebo, PyBullet, robosuite, robomimic, Simulink
**Machine Learning:** PyTorch, Deep RL (A2C, A3C), Imitation Learning, Diffusion Policy, World Models
**Perception:** OpenCV, Kornia, YOLO, Depth Estimation, VIO, SLAM, Structure from Motion, NeRF, Camera Calibration
**Controls:** PID, LQR, MPC, EKF, System Identification, Trajectory Optimization
**Hardware:** Franka Emika Panda, UR5e, Crazyflie 2.0, Intel RealSense D435, Beckhoff TwinCAT PLC, NVIDIA Jetson Nano
**Tools:** Docker, Git, SLURM/HPC (A30), Blender, HM3D, Habitat-Sim

---
📊 **Seeking Full-Time Opportunities (Aug 2027)** in perception engineering, computer vision, robotics software, robot learning, or autonomy.
