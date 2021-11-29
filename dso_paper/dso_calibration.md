### 相机参数标定
dso 采用的相机模型在传统单目针孔相机模型中加入了光度校准步骤

#### 几何校准    
小孔成像模型和畸变模型
#### 光度校准   
直接法是基于光度不变的假设，所以在真实环境中或是自动调节亮度的相机中，会造成较大误差，通过光度校准能有效提升整体精度<sub>[1]</sub>。  
$$I_i(x)=G(t_iV(x)B_i(x))$$  
其中$I_i$是被观测的图像像素光度,$B_i$是 irradiance 描述光




[1]J.  Engel,  V.  Usenko,  and  D.  Cremers,  “A  photometricallycalibrated  benchmark  for  monocular  visual  odometry,”arXiv:1607.02555, 2016.