# Visual-Localization Project
## Change log <br>
8/10  Cmake the KinectFusionLib for libs.Test Struct_From_Motion <br>
8/21   coding base on kinectFusionApp,aims to provide a image with a pose<br>
9/3  fixed the config bug.prepare to reinstall OpenCV Lib<br>
9/4  run the app based on KinectFusionLib,use the bundle fusion image instead of camera<br>
9/9  output mesh ply. one file for example upload to git.

**Bug log:**<br>
bug 1:app can't read all image<br>
not look like out of memory <br>
1,I test different images number,stop at similar position<br>
2,use log to find code in follow link<br>
https://github.com/chrdiller/KinectFusionLib/blob/master/src/pose_estimation.cpp
<img src="https://github.com/ICCD/Visual-Localization/blob/master/1781902426.jpg" width="480"  alt="图片加载失败"/><br>



## Prepare Data
**libKinectFusion:** Complie the KinectFusionLib in the Ubuntu14.04 ,upload the file to github <br>
**Bundle Fusion:**      Download the ply,jpg,pose.txt file from  [bundlefusion project](http://graphics.stanford.edu/projects/bundlefusion/index.html) <br>
 For example:<br>
 frame-000149.color.jpg: <br>
<img src="https://github.com/ICCD/Visual-Localization/blob/master/DataSet-example/frame-000149.color.jpg" width="480"  alt="图片加载失败"/>
<br>
scene.ply:(shotcut) <br>
<img src="https://github.com/ICCD/Visual-Localization/blob/master/DataSet-example/PLYshotcut.png" width="640"  alt="图片加载失败"/>
<br>
frame-000149.pose.txt <br>
  **4*4 Matrix**   <br><br>
frame-000149.depth.png
 ## Problem 
 How about the method of convert ply(or obj) to image
 the related code [shape_net_render](https://github.com/panmari/stanford-shapenet-renderer) with python <br>
 Next step :how to use GAN to create Image
 
 
