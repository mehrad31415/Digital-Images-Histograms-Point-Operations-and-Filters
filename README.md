# Digital-Images-Histograms-Point-Operations-and-Filters
This is a mini-project for the computer vision course in Spring 2022.

Digital Images, Histograms, Point Operations, and Filters (Spring 2022)

The exercise consists of three parts: part A about digital images in general, part B about histograms and point operators, and part C about filters.
The images used in the project are taken through my mobile phone. The project aims to answer the following questions:

A. Digital Images

1. Manipulate a color image by manipulating the R-, G-, and B-values. Show what happens if you alter only the R-values of all pixels, for example by halving these values or setting these values to zero. Also show what happens if you do this for both the R- and G-values at the same time.

2. Turn a color image into grayscale images using differently weighted sums of the R-, G-, and B-values and show the results. Discuss any noticeable differences.

3. Use a grayscale image and create a lower-resolution image of it with half the number of rows and half the number of columns. Replace each 2-by-2 cluster of pixels in the original image by a single pixel in the new lower-resolution image. Creatively explore different strategies for setting the value of the pixel in the new image based on the values of the four replaced pixels, and study how these strategies perform if the resolution is further reduced in the same manner. Show the sequences of reduced resolution images. Do you think that it is possible to design a successful strategy for reducing the resolution of color images?

B. Histograms and Point Operators

1. Find a (natural, so non-synthetic) grayscale image for which you expect the frequencies of the intensity values to be more or less uniform. Determine its histogram and cumulative histogram. Also invert the grayscale image.

2. Also find a grayscale image for which you expect a bias towards low intensity values a grayscale image for which you expect a bias towards high intensity values. We will refer to these images below as the dark and light image respectively. Determine the histogram and cumulative histogram for the dark and the light image.

3. Use the above dark and light grayscale images and perform histogram equalization on both. Show the resulting images, and their histograms and cumulative histograms.

4. Find an image in which the range of different pixel values is limited, so, in other words, in which the darkest pixel is relatively light, and the lightest pixel is relatively dark. Increase the brightness of the image and show the resulting image. Also increase the contrast and show the resulting image.

C. Filters

Note that all questions about filters require that you find a way to handle image borders. 

1. Apply a number of different 3 x 3 smoothing filters to a grayscale image and show
and compare the results.

2. Add noise to a grayscale image by randomly setting the intensity of a few hundred pixels to zero. Apply a 3 x 3 and a 5 x 5 median filter to repair the noisy image. Compare the resulting image to the noisy image and the original image. Then, add noise to the original grayscale image by randomly setting the intensity of a few hundred 2-by-2 clusters of pixels to zero. Again apply 3 x 3 and 5 x 5 median filters to repair the noisy image. Compare the resulting image to the noisy image and the original image.

3. Apply unsharp masking to sharpen a grayscale image and compare the result to the original image.
