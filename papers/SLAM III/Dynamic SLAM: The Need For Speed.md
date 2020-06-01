- goal is to model both static and dynamic objects in SLAM
- review: 1. treat dynamic objects as outliers 2. detect and track dynamic objects separately
![](assets/44f79f0f.png)
- approach
![](assets/3ba18455.png)
- the paper uses a feature based SLAM instead of object SLAM, since objet SLAM needs to have the 3D object models available
- the motion of the object in the world frame is expressed as the motion of the points
![](assets/b455bb80.png)
- factor graph
![](assets/189573ea.png)
- object velocity estimation
![](assets/98cb7621.png)
- feature tracking, optical flow is better  
![](assets/61d04aef.png)
- front end on virtual KITTI
![](assets/79bba5f2.png)
- results on KITTI
![](assets/d7e47112.png)
![](assets/270caa6d.png)
![](assets/118aec17.png)
- summary
![](assets/f87fd197.png)
