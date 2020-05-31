- goal is to track ego motion and moving objects using VIO
- problem formulation
![](assets/df392c52.png)
- propagation
![](assets/c8fe9593.png)
- motion model
![](assets/2c484fce.png)
- update
![](assets/53631981.png)
![](assets/e2093001.png)
- noise model
![](assets/64be8248.png)
![](assets/0e7c7c59.png)
- since we may not know the suitable noise model, we need to use SKF
![](assets/a483ab09.png)
- since IMU is not drifting, even if we do not have accurate noise model, target tracking is still robust
![](assets/7069a654.png)
- conclusion
![](assets/9c3185d0.png)
- Q&A:
![](assets/996e0bd3.png)
![](assets/fc7ec4a8.png)
