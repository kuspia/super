[![N|Solid](https://miro.medium.com/max/1408/1*2Y3467WK-pqjsUxf_oJGAA.png)](https://nodesource.com/products/nsolid)
# 3D perception using PointNet on FPGA
## _Week-1 Report_

**Kushagra Shukla**
**EYSIP Intern 2020-21**

Week-1 focuses on getting familiar with goal and objectives as well as necessary installations. We also focus on various technologies used for 3D scanning. CPP tutorials have been also covered under this week.

## Overview
- Work Done and Resources referred 
- Challenges and Solutions
- Tips (if any) to excel the project  

## Work Done and Resources referred

**Depth perception concept and various 3D scannig techniques:**
- How actually our eyes give the sense of depth [Monocular and Binocular cues]
- Understanding steroscopic vision and 3D cameras 
- Understanding Lidar and Point Cloud Data
>Check sense of depth calculation by eyes from [link1]
>Check for 3D scanning and 3D data reprsentations from [link4]
>Check Visualisation of Point Cloud data from [link5]

[link4]:<https://thegradient.pub/beyond-the-pixel-plane-sensing-and-learning-in-3d/>
[link5]:<https://www.youtube.com/watch?v=PL6wD8jczkE>


**PointNet and PCL**
- Understanding what is PointNet
- Understanding what is PCL and how it help us to process 3D data (Point Cloud Library)
> Check what is PointNet from [link2] 
> Check PointCloud Classification from PointNet [link6]
> Check about PCL library from its offcial site [link3]

[link6]:<https://www.youtube.com/watch?v=GGxpqfTvE8c>
[link1]: <https://www.youtube.com/watch?v=QGYQgoyJzbU>
[link2]: <https://www.youtube.com/watch?v=Cge-hot0Oc0>
[link3]:<https://pointclouds.org/>


**Concept of FPGA**
- Understanding what is FPGA and ASIC concept 
- The need of reprogramability of FPGA board
> Check to get familiar with FPGA from [link7]

[link7]:<https://www.youtube.com/watch?v=WY-F3knih7c>

**Necessary Installations**
- Installing PCL library to deal with 3D data

> Check for complete installation process from [link8]

[link8]:<https://github.com/PointCloudLibrary/pcl/issues/4462>

## Challenges and Solutions
1. Major challenges that we faced till now was to understand main objective of the project that was understood by referring the above resources and going through lot of articles about PCL as well as how 3D scanning is done and its importance.
2. The second challenge was to install PCL in Windows that was solved by [link8].
3. Understanding how we are going to port out project on FPGA and its mechanical design as well as training our model from PointNet.
> Still we are in stage to understand challenge 3.

## Tips (if any) to excel the project

We may try out PointNet++ or work with other extension files that may boost the outcomes.

