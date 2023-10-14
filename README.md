# CSE498R-Directed-Research---Tooth-Decay-Detection

Cavities, commonly known as tooth decay, are portions of the hard surface of teeth that 
have  been  irreversibly  damaged.  It  eventually  turns  into  tiny  gaps  or  holes.  It  can  cause 
infection, pain, and even tooth loss if not treated appropriately. For developing and 
underdeveloped  countries,  regular  dental  appointments  can  be  costly. The  purpose  of  this 
study was to develop and evaluate the performance of a tooth decay detection system that 
used  a  deep  learning  technique  based  on  a  convolutional  neural  network  (CNN)  to  detect 
tooth  decay  from  oral  photographs.  We  used  a  collection  of  233  pictures  of  teeth  with 
cavitation. The input was clear photos of affected teeth on a white background. The dataset 
was trained on three separate object detection models – YOLOv4, YOLOv5m, and YOLOv5s – 
after  some  pre-processing.  On  a  pre-trained  YOLOv4  model  (trained  in  MS  COCO  dataset), 
we used the transfer learning technique to detect dental decay and attained an accuracy of 
94.17  percent.  YOLOv5s  and  YOLOv5m,  on  the  other  hand,  were  trained  from  scratch  and 
had a 97.8% and 96.9% accuracy rate.