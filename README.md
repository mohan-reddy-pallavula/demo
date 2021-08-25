# In this folder contains face demographics models ( age and gender prediction ) :

it contains three ipynb notebooks ,

1.caffe-model.ipynb-- It contains implementation of two caffe model ( one is age and another one is gender ) with help of MTCNN and Harrcascade models for face detection.

2.face-demographics(lower-resolution-images).ipynb -- it contains implementation of 

* specify the input image path is in good resolution or hd
* Downscale the image to 240P
* Apply a super resolution model ( EDSR Model ) to improve the resolution of image.
* Apply Bodypix model for getting face crops.
* After getting face crops in an upscaled image and pick the same face crops in lower resolution image(240P).
* Call the  betaface api , for face demographics by giving the face crops of both lower and higher resolution face crop images.
* Betaface api returns age and gender prediction , the save the results in an image showing like the below image.

3.microsoft-faceapi.ipynb -- it contains implementation of microsoft face-api 



