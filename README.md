This is a **Traffic Sign Detection with SIFT (Scale-Invariant Feature Transform)**.

I'm using `OpenCV – 3.4.2.16` in `Python 3.7.10`.

#### Description

- We have a main_images folder that includes all traffic sign images to compare during matching. Also we have selected_images folder that include image we want to match in main_images folder.

- To run this code:

`python trrafic_sign_detection.py "main_images" "selected_images"`

- First parameter indicate main images folder path. Second parameter indicate selected images folder path that we want to find what is it.

- Selected image folder can contain one or more images.

- When python file is running, it shows the first image in selected image folder, and if the first image matches an image in the main folder, the image will show on screen, and its name is written on the image.
If the image is not matching any images in the main folder. Its name is not written on the image. This name is taking from the main folder images that matches in the selected images folder.
You can continue to see results by pushing any key button on your keyboard. 

-This code cotain SIFT algoritm to match features. The number of matching features between two images is printed in the console for every pair of images. If the number of features is more then 10,the code allow to match two images.
 You can change the threshold and see what kind of difference is happen in the number of matching features. 






