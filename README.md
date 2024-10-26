Image Processing 

[Image Quantization]

This code saves an image at different quality levels and then displays the saved images simultaneously. Its purpose is to show the impact of varying quality on the image.


<img width="1440" alt="Screenshot 1403-08-02 at 21 34 28" src="https://github.com/user-attachments/assets/bc6a9c62-9fd0-496d-bd67-b59534625aa3">








[Convert RGB Image To Binary]

This code reads an RGB image and converts it to grayscale. It then applies thresholding to convert the grayscale image into a binary image and displays both the input and output images side by side.





<img width="1440" alt="Screenshot 1403-08-02 at 21 35 05" src="https://github.com/user-attachments/assets/33415c4f-ea6e-461d-9093-340267568916">






[Cropped]

This code reads an image, crops a specified region, applies Gaussian blur to the cropped area, and saves the blurred image. It then displays the original, cropped, and blurred images side by side for comparison.

<img width="1440" alt="Screenshot 1403-08-02 at 22 32 56" src="https://github.com/user-attachments/assets/4870ca3c-753a-4d66-a862-d001844628e8">


[Upsampling]



This code reads an image and upsamples it by a factor of 2 using bilinear interpolation, improving its resolution. It then saves the upsampled image and displays both the original and upsampled images side by side, with axes visible for reference.






<img width="1440" alt="Upsampling" src="https://github.com/user-attachments/assets/12fa9038-a589-4623-ace8-52fae92cd62a">



[Downsampling]


The provided code reads an image, downsamples it by factors of 1/2 and 1/4 using OpenCV's `resize` function, and displays the original and downsampled images. It checks if the image is loaded successfully before processing, ensuring that resizing operations are performed on a valid image.



<img width="1440" alt="Screenshot 1403-08-03 at 03 02 55" src="https://github.com/user-attachments/assets/42c15155-8fbc-4c17-84d8-8362a7c25822">




[Change The Number Of Shades Of Gray]


This code loads an RGB image, converts it to grayscale, and normalizes it to two different levels (128 and 64 shades). Finally, it displays the original image alongside the two normalized grayscale images for comparison.



<img width="1440" alt="Change_The_Number_Of_Shades_Of_Gray" src="https://github.com/user-attachments/assets/2caa0eec-2148-4219-a7cb-7abab2fd080a">



[Negative]

This code reads a grayscale image and creates its negative, displaying both images. It also calculates and plots the histograms of the original and negative images to visualize the distribution of pixel intensities.


<img width="1440" alt="Negative Input" src="https://github.com/user-attachments/assets/bf834ba1-4d71-4414-9035-970c4a573884">




<img width="1440" alt="Negative output" src="https://github.com/user-attachments/assets/fc902cc7-74fc-4250-94d5-9b4498d48387">






[Adjust Intensity Values]


The code loads the original image and adjusts its color intensity using the `rescale_intensity` function. It then displays both the original and adjusted images side by side, with titles positioned below each image.



<img width="1440" alt="Adjust_Intensity_Values" src="https://github.com/user-attachments/assets/9ceedfab-2cdb-4146-a508-6050b810b9d2">




