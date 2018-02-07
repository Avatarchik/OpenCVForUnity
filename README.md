# OpenCV
### OpencvForUnity Step-by-step.

关于该插件的官方example，里面有非常丰富的实例，但是基础API讲解并没有，不太适合从unity转到opencv开发的新人。这个仓库主要通过收集网上的c++/python opencv文章/源码，API翻译，作为为unity所用的基础入门案例补充。

|order|theme|code|blog|
|---|---|---|---|
|1|图片裁切|√|√|
|2|图片拼接|√|√|
|3|灰度化、二值化|√|√|
|4|边缘检测（梯度）、滤波|√|√|
|5|模糊、锐化|√|√|
|6|反色|√|√|
|7|色度图|√|√|
|8|ROI|√|√|
|9|腐蚀、膨胀|√|√|
|10|直方图|√|×|
|n|透视|√|×|
|n|orb特征提取|√|×|
|n|轮廓图|×|×|

### 使用说明
这是一个在unity中使用OpenCV的入门参考，使用商业插件OpencvForUnity。为确保项目正常运行，请购买并导入最新版OpencvForUnity。项目通过一系列独立的例子，由浅入深一步步掌握opencv图片处理的方法。

### 注意事项
1. [官方参考资料](https://forum.unity.com/threads/released-opencv-for-unity.277080/)；
2. OpencvForUnity的API中，Mat类型兼容Opencv中的CvMat,IplImage,CvMatND类型；

### Bug?
1. Lut(src,lut,dst); //不执行？
2. Rect放在UnityEngine.UI.Image显示; //位置错误；
