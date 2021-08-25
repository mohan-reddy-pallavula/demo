
# Various Tracking Models :

In this tracking part , it contains four folders 

1. Tradition-Tracking-Methods
 
   It contains the implementation of tradition tracking methods with help of opencv ,
* Boosting Tracker 
* MIL Tracker 
* KCF Tracker 
* CSRT Tracker 
* MedianFlow Tracker 
* TLD Tracker 
* MOOSE Tracker 
* GOTURN Tracker

### DeepSort

* for deepsort code , clone this repository ( https://github.com/haroonshakeel/yolov4_deepSort ) ,

* install required packages according to above specified repository , then consider three folders ( deep_sort ,model_data ,tools )


2. FasterRCNN+SSD

   It contains the implementation of fasterrcnn + ssd models for detection ,  with deepsort model for tracking.
   
   place deepsort three folders into FasterRCNN+SSD folder , then run the  fsrcnn-ssd-models(deepsort).ipynb .  
   
   It contains different fasterrcnn + ssd models using tensorflow object detection api .
   
3. yolo-family 

   It contains the implementation of different yolo models  for detection ,  with deepsort model for tracking.
   
   place deepsort three folders into yolo-family folder , then run the  yolo-family+deepsort.ipynb .  
   
   It contains different yolo models  like yolov3 ,yolov4 , yolov5.
   
 4. Fairmot Model 
 
    Used this repository for implementing fairmot model ( https://github.com/harsh2912/people-tracking )
    
    Made few changes to run on  cpu 
    
    Few changes in script file to save results to analyse.


   




