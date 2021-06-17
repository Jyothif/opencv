# opencv(mini to major projects)

# cropping the image
<img src="https://github.com/Jyothif/opencv/blob/main/1.jpg">
### cropped image
<img src="https://github.com/Jyothif/opencv/blob/main/Cropped%20Image.jpg">




# Thresholding:
`Thresholding is used to simplify visual data for further analysis. In image processing, we need to pre-process the image data and get the important details. This technique is important to separate background image and foreground image. Image is colorful and it will contain 3 values ranging from 0-255 for every pixel. In thresholding, first,I have convert the image in gray-scale. So for a gray-scale image,only need 1 value for every pixel ranging from 0-255. By converting the image, I have reduced the data.`

<img src="https://github.com/Jyothif/opencv/blob/main/images/s2.PNG"><img src="https://github.com/Jyothif/opencv/blob/main/images/s6.PNG"><img src="https://github.com/Jyothif/opencv/blob/main/images/s5.PNG"><img src ="https://github.com/Jyothif/opencv/blob/main/images/s4.PNG">



# Edge Detection:
`This is technique used in edge detection for calculate the edges of the images`
- Thus edges sudden changes into sharpen or shiny edges which the makes image more clear
- Edge detection improves the images and improves the image quality to recognize
- `cv2.Canny()` is used to detect the edges of the images, most popular function to detect the edges.

<img src="https://github.com/Jyothif/opencv/blob/main/images/edge%20detection_images/E_O.PNG">

<img src="https://github.com/Jyothif/opencv/blob/main/images/edge%20detection_images/E_R.PNG">



# Blur the image:
They are four different types of functions available for blurring:
- `cv2.blur()`: this fucntion takes avrage of all pixels around that filter. it used for simple and fast blurring techniques.
- `cv2.GaussianBlur()`: GaussianBlur() is used for filtering and removing the noised and as well reduced the reduced the detials of the image,it is used in mainly in the image preprocessing steps in machine learning and Deep learning models.
- `cv2.medianBlur()`:it will takes the median of the neighboring pixels. mainly useful for digital image processing in an specific conditions.,it will take care about edges of the images.
- `cv2.bilateralFilter()`:sharp edges are saved and weak edges are deleted.

<><><><><>







##### projects are still coming on
