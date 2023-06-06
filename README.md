# basic-image-processing
Introduction 

Image enhancement is a technique used to improve an image's visual quality. The process involves adjusting various aspects of an image, such as brightness, contrast, sharpness, color balance, and saturation, to make it clearer, more detailed, and easier to interpret. Image enhancement is a critical step in many fields, including medical imaging, remote sensing, computer vision, and even in everyday photography.


Technique 1 - Median Filter


The median filter is the filtering technique used for noise removal from images and signals. The median filter is very crucial in the image processing field as it is well-known for the preservation of edges during noise removal.

Implementation;

1-	Add salt and paper, noise using imnoise (a.salt & pepper',0.3) Function, where 0.3 is the noise density.
2-	Inshow to plot the image with the title "Image with Slat & Pepper Noise"
3-	medfilt3(LI5,5,3]) to med filter the image in three dimensions.
4-	Imshow to plot the filtered image with the title "Filtered Image"

Code;

<img width="432" alt="image" src="https://github.com/ehdaaalmatrafi/basic-image-processing/assets/93643882/06bd56f5-0c5d-4f19-bfe6-b02a2a6db081">


Result;

From the noise image: 

![image](https://github.com/ehdaaalmatrafi/basic-image-processing/assets/93643882/2af5cb72-5096-4d72-bef4-cd5bb4ef7463)

We got the filtered image: 

![image](https://github.com/ehdaaalmatrafi/basic-image-processing/assets/93643882/387a5581-acce-4c2c-a1a9-cfedfaa9401d)
 
 
 

Technique 2 – Histogram equalization 

Histogram Equalization is a computer image processing technique used to improve contrast in images. It accomplishes this by effectively spreading out the most frequent intensity values, i.e. stretching out the intensity range of the image. This method usually increases the global contrast of images when its usable data is represented by close contrast values. This allows for areas of lower local contrast to gain a higher contrast.

Implementation;

1-	Generate the histogram first by using a loop to get the histogram of the image.
2-	normalize histogram by pdf=(1/(d(1)*d(2)))*Histog1 diving by total no. of pixels.
3-	Find the CDF of the PDF
4-	Getting the output histogram image. 


Code;

<img width="432" alt="image" src="https://github.com/ehdaaalmatrafi/basic-image-processing/assets/93643882/c81a2de2-50b1-4b8b-9658-2bd01672a331">
 
Result:

![image](https://github.com/ehdaaalmatrafi/basic-image-processing/assets/93643882/79ae993f-42aa-450c-9727-6a11df6b2a39)
 
 
![image](https://github.com/ehdaaalmatrafi/basic-image-processing/assets/93643882/a21132ac-c589-4385-a128-e1e1f0132ac3)
 
