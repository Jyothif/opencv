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

<img src="https://github.com/Jyothif/opencv/blob/main/images/blur_images/flower.jpg">
<img src="https://github.com/Jyothif/opencv/blob/main/images/blur_images/blur.PNG">
<img src="https://github.com/Jyothif/opencv/blob/main/images/blur_images/gaussianblur.PNG"><img src="https://github.com/Jyothif/opencv/blob/main/images/blur_images/median_blur.PNG"><img src="https://github.com/Jyothif/opencv/blob/main/images/blur_images/Bilateral%20Blur.PNG">


# Photo sketching

- The idea is to build an app that will take an image as input from the user and convert it into a pencil sketching, coding is completed deployment is under process.
<img src="https://github.com/Jyothif/opencv/blob/main/images/photo%20sketch/im1.PNG">
<img src="https://github.com/Jyothif/opencv/blob/main/images/photo%20sketch/im2.PNG"><img src="https://github.com/Jyothif/opencv/blob/main/images/photo%20sketch/im3.PNG"><img src="https://github.com/Jyothif/opencv/blob/main/images/photo%20sketch/im4.PNG">


## output photo

<img src="https://github.com/Jyothif/opencv/blob/main/images/photo%20sketch/im5.PNG">



# Extracting the text from image 
- pytesseract is actively used to extract the text from the image
- Just go this url link: https://github.com/UB-Mannheim/tesseract/wiki
- Install tesseract-ocr-w64-setup-v5.0.0-alpha.20210506.exe either 34 or 64 bit file.
- Add path to the environment varaibles path as: 'C:\Program Files\Tesseract-OCR\\tesseract.exe'
- Start exploring with text images coversion.

Snippets of GUI
<img src = "https://github.com/Jyothif/opencv/blob/main/images/extract/2.PNG"><img src="https://github.com/Jyothif/opencv/blob/main/images/extract/output.PNG">




##### projects are still coming on
