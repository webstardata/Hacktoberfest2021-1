
=======================================================

Article Title: <Basics of Image Processing>
Author Name: <Saloni Shukla>
Author Profile: <https://github.com/salonishukla206>
Date: <17-Oct-2021>

=======================================================

<       # Basics Of Image & Its Properties (Brief of Colorspace)
        ## Brightness & Contrast 
Brightness refers to the overall lightness or darkness of the image. 
Contrast is the difference in brightness between objects.
For example, a white rabbit running across a snowy field has poor contrast, while a black dog against the same white background has good contrast.
Variance measures how far each number in the set is from the mean and thus from every other number in the set.
Low variance or standard deviation means the pixel intensities are closer to the mean and high variance means the pixel intensities are far from mean.
Contrast is high for images with high standard deviation values
Brightness & Contrast Adjustments: 
Increasing the brightness makes every pixel in the image become lighter.
Increasing contrast makes the lighter area of image lighter, and dark areas become darkers
If contrast is low, then all of the pixels are a mid-shade of gray making the objects fade into each other.
  
          ## Sharpness & Resolution 
Sharpness refers to an image's overall clarity in terms of both focus and contrast
Increasing the sharpness control will actually add something called "edge enhancement," which can diminish the fine resolution in the image you're looking at. 
Edge Enhancement: This feature attempts to make the image look a little sharper. That sounds good, but oversharpening can also create artifacts. (Harsh-Visible lines on edges and around the object)
Camera resolution and image sharpness are also related to one another. The resolution involves the amount of detail in an image and, therefore, how sharp it can be.
Resolution is measured in megapixels. Generally, the more pixels, the more detail you’ll see

            ## Color Space 
A color space is a specific organization of colors. 
It supports reproducible representations of color 
It describes a color as a tuple of three components where it takes the value from 0 to 255.>
OpenCV by default reads images in BGR format.
            ## RGB 
RGB (Red, Green, Blue)  ----- Most Common out of 5 major color spaces.
(0 , 0 , 0 ) ------ Represents Black
(255, 255, 255) ----- Represents White
RGB is considered an “additive” color space, and colors can be imagined as being produced from shining quantities of red, blue, and green light onto a black background.

          ## LAB
L --- Lightness (Intensity)
A ---  color component ranging from Green to Magenta.
B ----  color component ranging from Blue to Yellow.


In RGB color space the color information is separated into three channels but the same three channels also encode brightness information.
In Lab color space, the L channel is independent of color information and encodes brightness only. The other two channels encode color.>
          
          ## HSV / HSL
HSV/HSL --- Hue, Saturation, and Brightness/Luminance
It is useful for identifying Contrast in images
They are used in Web Design related Softwares
Hue refers to a specific waveband in the visible spectrum.
Saturation (or 'chroma') defines the intensity of a hue
  >
