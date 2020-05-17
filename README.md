# SR-CNN
Super resolution based on SRCNN using Keras (2.0)

<br>
Please refer to paper for more details on working https://arxiv.org/pdf/1501.00092v3.pdf
<br>
<b>Install require dependency</b><br>
pip install Pillow==2.2.2<br>
pip install tensorflow<br>

Image dataset was downloaded from google images, refer to link 
(https://www.pyimagesearch.com/2017/12/04/how-to-create-a-deep-learning-dataset-using-google-images/)<br>
Two architectures are implemented. <br>1. Expanded Super Resolution CNN (ESRCNN) <br>

This gave good results,<br>
![](Images/SRCNN.png)<br>
![](Images/ESRCNN.png)
<br>


<br>2. Denoiseing Super Resolution CNN (DSRCNN)<br>
This had better results than previous.
![](Images/DSRCNN.png)<br>
![](Images/DenoiseESRCNN.png)
<br>
Both the model was trained on 2000 images for 500 epochs.<br>

<b>Credits</b><br>
Architecture details - https://github.com/olgaliak/
