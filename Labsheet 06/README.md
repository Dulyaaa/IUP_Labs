### Goal
* Apply custom made filters to images using cv2.filter2D( )
* Apply averaging filter using cv2.blur( ) or cv2.boxFilter( )
* Apply various low pass filters to smooth images (cv2.medianBlur( ) and cv2.GaussianBlur( ))
* Application of image blurring 

1. Image filtering using 2D convolution
A Low pass filter helps in removing noise, or blurring the image. OpenCV provides a function, 
cv2.filter2D(), to convolve a kernel with an image. As an example, we will try an averaging filter 
on an image. A 5x5 averaging filter kernel can be defined as follows:

K = 1/25 [all 1's of 5 by 5 metrics]

2. Image Averaging using Box Filter
Image averaging is done by convolving the image with a normalized box filter. It simply 
takes the average of all the pixels under kernel area and replaces the central element with this 
average. This is done by the function cv2.blur() or cv2.boxFilter().

3. Median Filtering and Gaussian Filtering
The function cv2.medianBlur() computes the median of all the pixels under the kernel 
window and the central pixel is replaced with this median value. This is highly effective in 
removing salt-and-pepper noise.

Create the code with a kernel of 3x3 size and apply cv2.medianBlur().
The above code can be modified for Gaussian blurring:
Gaussian filtering is highly effective in removing Gaussian noise from the image.

4. Application of image blurring

