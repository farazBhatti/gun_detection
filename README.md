# Gun detection in images
This repository provides inference on detecting guns in images and videos. Object detection model has been trained on 600 plus images annotated with [LabelImg], for 80k epochs on Tesla K80 GPU provided by Google Colab for free. Training folder contains config file. This code is inspired by [EdjeElectronics]. F-1 score of this model is 0.86.

Inference:

[Download] and extract pre-trained model in the inference graph folder

Results on [video]:


![img1](https://github.com/farazBhatti/gun_detection/blob/master/result_images/img_1.png)
![img2](https://github.com/farazBhatti/gun_detection/blob/master/result_images/img_3.png)
![img3](https://github.com/farazBhatti/gun_detection/blob/master/result_images/img_2.png)






[Download]:https://drive.google.com/open?id=1MtnbWwyFNPTdxZiYoRdNOCKdsg9lst_X
[EdjeElectronics]:https://github.com/EdjeElectronics/TensorFlow-Object-Detection-API-Tutorial-Train-Multiple-Objects-Windows-10
[labelImg]:https://github.com/tzutalin/labelImg
[video]:https://www.youtube.com/watch?v=B-KTkCme9bU
