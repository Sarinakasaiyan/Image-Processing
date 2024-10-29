Image Processing 

[Image Quantization]

This code saves an image at different quality levels and then displays the saved images simultaneously. Its purpose is to show the impact of varying quality on the image.


<img width="1440" alt="Screenshot 1403-08-02 at 21 34 28" src="https://github.com/user-attachments/assets/bc6a9c62-9fd0-496d-bd67-b59534625aa3">




---



[Convert RGB Image To Binary]

This code reads an RGB image and converts it to grayscale. It then applies thresholding to convert the grayscale image into a binary image and displays both the input and output images side by side.





<img width="1440" alt="Screenshot 1403-08-02 at 21 35 05" src="https://github.com/user-attachments/assets/33415c4f-ea6e-461d-9093-340267568916">



---


[Cropped]

This code reads an image, crops a specified region, applies Gaussian blur to the cropped area, and saves the blurred image. It then displays the original, cropped, and blurred images side by side for comparison.

<img width="1440" alt="Screenshot 1403-08-02 at 22 32 56" src="https://github.com/user-attachments/assets/4870ca3c-753a-4d66-a862-d001844628e8">


---

[Upsampling]



This code reads an image and upsamples it by a factor of 2 using bilinear interpolation, improving its resolution. It then saves the upsampled image and displays both the original and upsampled images side by side, with axes visible for reference.





<img width="1440" alt="Upsampling" src="https://github.com/user-attachments/assets/12fa9038-a589-4623-ace8-52fae92cd62a">


---

[Downsampling]


The provided code reads an image, downsamples it by factors of 1/2 and 1/4 using OpenCV's `resize` function, and displays the original and downsampled images. It checks if the image is loaded successfully before processing, ensuring that resizing operations are performed on a valid image.



<img width="1440" alt="Screenshot 1403-08-03 at 03 02 55" src="https://github.com/user-attachments/assets/42c15155-8fbc-4c17-84d8-8362a7c25822">



---


[Change The Number Of Shades Of Gray]


This code loads an RGB image, converts it to grayscale, and normalizes it to two different levels (128 and 64 shades). Finally, it displays the original image alongside the two normalized grayscale images for comparison.



<img width="1440" alt="Change_The_Number_Of_Shades_Of_Gray" src="https://github.com/user-attachments/assets/2caa0eec-2148-4219-a7cb-7abab2fd080a">


---


[Negative]

This code reads a grayscale image and creates its negative, displaying both images. It also calculates and plots the histograms of the original and negative images to visualize the distribution of pixel intensities.


<img width="1440" alt="Negative Input" src="https://github.com/user-attachments/assets/bf834ba1-4d71-4414-9035-970c4a573884">




<img width="1440" alt="Negative output" src="https://github.com/user-attachments/assets/fc902cc7-74fc-4250-94d5-9b4498d48387">



---


[Adjust Intensity Values]


The code loads the original image and adjusts its color intensity using the `rescale_intensity` function. It then displays both the original and adjusted images side by side, with titles positioned below each image.



<img width="1440" alt="Adjust_Intensity_Values" src="https://github.com/user-attachments/assets/9ceedfab-2cdb-4146-a508-6050b810b9d2">


---


[Histogram Adjustment]


The code loads a grayscale image, calculates its histogram, performs histogram equalization to enhance contrast, and computes the histogram of the equalized image. It then visualizes both the original and equalized images along with their histograms in a 2x2 grid using Matplotlib.


<img width="1440" alt="Histogram-Adjustment" src="https://github.com/user-attachments/assets/871e24c6-200a-48d3-a533-681f5f6aff8f">

---

[Histogram Matching]


The code performs histogram manipulation on an image by applying a wide Gaussian distribution with a high `sigma` and a low center, resulting in significant changes to pixel intensities. This transformation produces a final image that can appear drastically brighter or darker, along with a histogram that reflects these alterations.


<img width="1440" alt="Histogram_Matching" src="https://github.com/user-attachments/assets/2e29d364-269d-461a-b507-bc8cc8a77071">


---


[Mean Filter]


This code adds Gaussian noise to the original image and then reduces that noise using a mean filter. Finally, it displays the original image, the noisy image, and the filtered image for comparison.


<img width="1440" alt="Mean_Filter" src="https://github.com/user-attachments/assets/59e25f42-71ee-4330-8a8c-d38078dbee93">


---


[Box Filter]

This code processes an input image using a box filter and displays both the original and the filtered images in separate subplots. It also checks for the existence of the file before loading the image to prevent errors.



<img width="1440" alt="Box Filter" src="https://github.com/user-attachments/assets/07bd0401-777c-42e9-97e5-43b02178b851">

---


[Median Filter]

This code adds Gaussian noise to an image and then reduces the noise using a median filter. Finally, it displays three images: the original image, the noisy image, and the filtered image side by side.

<img width="1440" alt="Median Filter" src="https://github.com/user-attachments/assets/2918cdae-c7e8-4179-97ea-c773e0f2c6f3">



---

[Min Filter]


This code reads an image from a file and adds salt-and-pepper noise to it. It then filters the noisy image using a min filter (using the erosion operator) and displays three images: the original, the noisy, and the filtered one.

<img width="1440" alt="Min_Filter" src="https://github.com/user-attachments/assets/d84734a3-7b06-4aa6-b32a-2db3c23f92a5">

---


[Max Filter]

The code reads an image, converts it to grayscale, and adds pepper noise to it. It then reduces the noise using a max filter and displays three images: the original, the noisy, and the filtered image.

<img width="1440" alt="Max_Filter" src="https://github.com/user-attachments/assets/de9d263f-f1ed-4492-ba92-aa0900736758">


---


[Gaussian Filter]

The provided code applies a Gaussian filter to an image using OpenCV to blur it. It reads the image, creates the Gaussian filter, applies it, and then displays both the original and blurred images.


 <img width="1440" alt="Gaussian Filter" src="https://github.com/user-attachments/assets/a860e265-2cba-4593-be4d-1874144ecc6d">

 <img width="1440" alt="Gaussian Filter output" src="https://github.com/user-attachments/assets/3012879f-c54b-4402-a86d-c60e8c58cabd">


---


[Edge Detection]


The code loads an image, converts it to grayscale, and applies various edge detection techniques (Canny, Laplacian, Sobel, and Roberts) to identify edges. It then visualizes the original image, grayscale image, and results of each edge detection method using Matplotlib subplots.

<img width="1440" alt="Edge Detection" src="https://github.com/user-attachments/assets/5ae6fc9f-c091-4024-9aa8-d3c03fe5270c">


<img width="1440" alt="EdgeDetection" src="https://github.com/user-attachments/assets/a3f52f6f-c318-434c-a92d-ea71c0420ea6">


<img width="1440" alt="Edge Detection output" src="https://github.com/user-attachments/assets/d141bb67-d6a0-4912-bfbb-61547d6c460f">



