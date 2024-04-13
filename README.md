# 2DImageManipulator
This was a the final project for the Java-Course on Codecademy.
The scope of this project was to create a Java app which runs in the terminal and
is able to manipulate images via traversing arrays and 2d arrays changing the rgb values etc.

## This is the original project scope from the Codecademy-Website:

### 2D Arrays: Image Manipulation Project
In this project, you will be creating an application which is able to modify images as well as create new images using 2D arrays! The first section covers stretching the image horizontally, shrinking the image vertically, negating the color, applying a color filter, and inverting the image. The second section covers creating an image consisting of random pixels, placing a rectangle in the image, and using the method to randomly place many rectangles in the image.

#### Here is an overview about how images work in Java:

Images consist of pixels which are the individual points in the image containing some color. Each pixel has some red, green, blue, and alpha value which represents the amount of each of those colors in the pixel. The red, green, and blue values can be mixed to create all of the visible colors on your screen. The alpha value represents the transparency of the pixel (or how close the color of the pixel is to the background color of the image). A higher resolution image means that there are more pixels contained within it.

In Java, a loaded image is stored into a BufferedImage object. From this object, we can extract each pixel value and store it into a 2D array which we can manipulate. The pixel values are stored as ints because each pixel value in the BufferedImage object is represented by a hexadecimal value which contains the red, green, blue, and alpha components. The maximum value of any of the RGBA values is 255 and the minimum is 0. There are some methods provided for you in this project which handle the conversion between images and 2D arrays as well as extracting the R, G, B, and A values from a pixel. You will only need to implement methods which work with the 2D arrays.

Each of these methods is executable independently so you can select which methods you want to complete or you can complete all of them. You also may want to adjust the window sizes in the workspace to better see the code and the image. You can drag the window borders to adjust the size.

There are a lot of different parts to this project, so you may feel overwhelmed when first looking at it. Remember, the goal here is to practice using 2D arrays.
