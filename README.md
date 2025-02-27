## Object detection 
> Final project for the Computer Vision course 

This project focuses on detecting traffic lights and road signs in driving scenes using the YOLOv5 object detection model by Ultralytics (Jocher, 2020). For this analysis, YOLOv5s was chosen as it offers a good balance between accuracy and training efficiency.

Additionally, the project includes reading the maximum allowed speed from detected speed limit signs. Two approaches were explored:
- Optical Character Recognition (OCR) to extract numeric speed values.
- Training YOLOv5 on a dataset with labels corresponding to specific speed limits.

These methods were compared to determine the most effective approach for accurate speed limit recognition.

*Project.ipynb* contains the main implementation of the project. 
