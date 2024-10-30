
<h2>1. Image Quantization</h2>

This code saves an image at different quality levels and then displays the saved images simultaneously. Its purpose is to show the impact of varying quality on the image.


<img width="1440" alt="Screenshot 1403-08-02 at 21 34 28" src="https://github.com/user-attachments/assets/bc6a9c62-9fd0-496d-bd67-b59534625aa3">




---



<h2>2. Convert RGB Image To Binary</h2>

This code reads an RGB image and converts it to grayscale. It then applies thresholding to convert the grayscale image into a binary image and displays both the input and output images side by side.





<img width="1440" alt="Screenshot 1403-08-02 at 21 35 05" src="https://github.com/user-attachments/assets/33415c4f-ea6e-461d-9093-340267568916">



---


<h2> 3. Cropped </h2>

This code reads an image, crops a specified region, applies Gaussian blur to the cropped area, and saves the blurred image. It then displays the original, cropped, and blurred images side by side for comparison.

<img width="1440" alt="Screenshot 1403-08-02 at 22 32 56" src="https://github.com/user-attachments/assets/4870ca3c-753a-4d66-a862-d001844628e8">


---

<h2> 4. Upsampling </h2>



This code reads an image and upsamples it by a factor of 2 using bilinear interpolation, improving its resolution. It then saves the upsampled image and displays both the original and upsampled images side by side, with axes visible for reference.





<img width="1440" alt="Upsampling" src="https://github.com/user-attachments/assets/12fa9038-a589-4623-ace8-52fae92cd62a">


---

<h2> 5. Downsampling </h2>


The provided code reads an image, downsamples it by factors of 1/2 and 1/4 using OpenCV's `resize` function, and displays the original and downsampled images. It checks if the image is loaded successfully before processing, ensuring that resizing operations are performed on a valid image.



<img width="1440" alt="Screenshot 1403-08-03 at 03 02 55" src="https://github.com/user-attachments/assets/42c15155-8fbc-4c17-84d8-8362a7c25822">



---


<h2> 6. Change The Number Of Shades Of Gray </h2>


This code loads an RGB image, converts it to grayscale, and normalizes it to two different levels (128 and 64 shades). Finally, it displays the original image alongside the two normalized grayscale images for comparison.



<img width="1440" alt="Change_The_Number_Of_Shades_Of_Gray" src="https://github.com/user-attachments/assets/2caa0eec-2148-4219-a7cb-7abab2fd080a">


---


<h2> 7. Negative </h2>

This code reads a grayscale image and creates its negative, displaying both images. It also calculates and plots the histograms of the original and negative images to visualize the distribution of pixel intensities.


<img width="1440" alt="Negative Input" src="https://github.com/user-attachments/assets/bf834ba1-4d71-4414-9035-970c4a573884">




<img width="1440" alt="Negative output" src="https://github.com/user-attachments/assets/fc902cc7-74fc-4250-94d5-9b4498d48387">



---


<h2> 8. Adjust Intensity Values </h2>


The code loads the original image and adjusts its color intensity using the `rescale_intensity` function. It then displays both the original and adjusted images side by side, with titles positioned below each image.



<img width="1440" alt="Adjust_Intensity_Values" src="https://github.com/user-attachments/assets/9ceedfab-2cdb-4146-a508-6050b810b9d2">


---


<h2> 9. Histogram Adjustment </h2>


The code loads a grayscale image, calculates its histogram, performs histogram equalization to enhance contrast, and computes the histogram of the equalized image. It then visualizes both the original and equalized images along with their histograms in a 2x2 grid using Matplotlib.


<img width="1440" alt="Histogram-Adjustment" src="https://github.com/user-attachments/assets/871e24c6-200a-48d3-a533-681f5f6aff8f">

---

<h2> 10. Histogram Matching </h2>


The code performs histogram manipulation on an image by applying a wide Gaussian distribution with a high `sigma` and a low center, resulting in significant changes to pixel intensities. This transformation produces a final image that can appear drastically brighter or darker, along with a histogram that reflects these alterations.


<img width="1440" alt="Histogram_Matching" src="https://github.com/user-attachments/assets/2e29d364-269d-461a-b507-bc8cc8a77071">


---


<h2> 11. Mean Filter </h2>


This code adds Gaussian noise to the original image and then reduces that noise using a mean filter. Finally, it displays the original image, the noisy image, and the filtered image for comparison.


<img width="1440" alt="Mean_Filter" src="https://github.com/user-attachments/assets/59e25f42-71ee-4330-8a8c-d38078dbee93">


---


<h2> 12. Box Filter </h2>

This code processes an input image using a box filter and displays both the original and the filtered images in separate subplots. It also checks for the existence of the file before loading the image to prevent errors.



<img width="1440" alt="Box Filter" src="https://github.com/user-attachments/assets/07bd0401-777c-42e9-97e5-43b02178b851">

---


<h2> 13. Median Filter </h2>

This code adds Gaussian noise to an image and then reduces the noise using a median filter. Finally, it displays three images: the original image, the noisy image, and the filtered image side by side.

<img width="1440" alt="Median Filter" src="https://github.com/user-attachments/assets/2918cdae-c7e8-4179-97ea-c773e0f2c6f3">



---

<h2> 14. Min Filter </h2>


This code reads an image from a file and adds salt-and-pepper noise to it. It then filters the noisy image using a min filter (using the erosion operator) and displays three images: the original, the noisy, and the filtered one.

<img width="1440" alt="Min_Filter" src="https://github.com/user-attachments/assets/d84734a3-7b06-4aa6-b32a-2db3c23f92a5">

---


<h2> 15. Max Filter </h2>

The code reads an image, converts it to grayscale, and adds pepper noise to it. It then reduces the noise using a max filter and displays three images: the original, the noisy, and the filtered image.

<img width="1440" alt="Max_Filter" src="https://github.com/user-attachments/assets/de9d263f-f1ed-4492-ba92-aa0900736758">


---


<h2> 16. Gaussian Filter </h2>

The provided code applies a Gaussian filter to an image using OpenCV to blur it. It reads the image, creates the Gaussian filter, applies it, and then displays both the original and blurred images.


 <img width="1440" alt="Gaussian Filter" src="https://github.com/user-attachments/assets/a860e265-2cba-4593-be4d-1874144ecc6d">

 <img width="1440" alt="Gaussian Filter output" src="https://github.com/user-attachments/assets/3012879f-c54b-4402-a86d-c60e8c58cabd">


---


<h2> 17. Edge Detection</h2>


The code loads an image, converts it to grayscale, and applies various edge detection techniques (Canny, Laplacian, Sobel, and Roberts) to identify edges. It then visualizes the original image, grayscale image, and results of each edge detection method using Matplotlib subplots.

<img width="1440" alt="Edge Detection" src="https://github.com/user-attachments/assets/5ae6fc9f-c091-4024-9aa8-d3c03fe5270c">


<img width="1440" alt="EdgeDetection" src="https://github.com/user-attachments/assets/a3f52f6f-c318-434c-a92d-ea71c0420ea6">


<img width="1440" alt="Edge Detection output" src="https://github.com/user-attachments/assets/d141bb67-d6a0-4912-bfbb-61547d6c460f">


---


<h2> 18. Add_Laplacian_To_Original_Image </h2>

The provided code converts an image to grayscale and applies a Laplacian filter for edge detection. It then displays the original image, the result of the Laplacian filter, and the image after adding the Laplacian result back to the original, illustrating the impact of edge detection on image details.

<img width="1440" alt="Add_Laplacian_To_Original_Image" src="https://github.com/user-attachments/assets/265631c9-4c66-4d9b-aa8b-c671ddb29ef1">


---

<h2> 19. Sharpening Filter</h2>


This code applies a sharpening filter to the loaded image and displays the result alongside the original image. The filter is defined using a 3x3 matrix that enhances edges and increases the details of the image.

<img width="1440" alt="Sharpening Filter" src="https://github.com/user-attachments/assets/a0929ba5-d3e6-409e-a050-224c07e209bf">


---

<h2> 20. Gaussian_Filter_In_Frequency_Domain </h2>


This code performs a Fourier transform on a grayscale image, visualizing both the original image and its frequency representation. It displays the Fourier transform, shifted Fourier transform, and the reconstructed image using appropriate magnitude calculations to ensure clarity and avoid loss of information.


<img width="1440" alt="Gaussian_Filter_In_Frequency_Domain" src="https://github.com/user-attachments/assets/8e2578c4-4a49-4e0f-818d-1c6db8383899">


<img width="1440" alt="Gaussian_Filter_In_Frequency_Domain output" src="https://github.com/user-attachments/assets/2c780e0e-55c1-432a-b24d-2215a91040b2">


