This paper addresses the scale estmation in monocular SLAM. 

Drawbacks for VIO: 
- Biases are hard to estiamte, and any error in bias estimation will be double-integrated into the camera positions. Thus, IMU can cause the SLAM to diverge 
- Scale can only be observable via acceleration, but acceleration may be dangerous in cluttered environments 

Drawbacks for end to end pose regression: 
