# RealTime FaceMask Detection 
RealTime FaceMask Detection  using TFOD

PRE- REQUISITE >>  Tensorflow Object Detection API should  have been installed.
installation document : https://tensorflow-object-detection-api-tutorial.readthedocs.io/en/latest/install.html

Collecting the images of Mask and No Mask using OpenCV >> here we are using OpenCv to capture the images with mask and no mask with the help of UUID  library it genarated the unique id for the images 

Prepare the image labels using LabelImg >> LabelImg is a graphical image annotation tool, using Labelimg i have labelled the mask and no mask images

Transfer Learning Using SSD MobileNet >> here we have to update the config file based on our custom model and train the custom model and should update the checkpoints after the training.

Realtime Detections using a webcam 

# Demo

![Screenshot (170)](https://user-images.githubusercontent.com/86067050/156971156-2cfcb517-4d9f-4e70-a08e-1e725d95ebf9.png)
![Screenshot (171)](https://user-images.githubusercontent.com/86067050/156971161-0358868f-df12-441b-9541-db5ce41b57c5.png)
