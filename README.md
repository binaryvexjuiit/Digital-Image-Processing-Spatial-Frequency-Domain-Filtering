Frequency Domain Filtering techniques are based on modifying the fourier transform of an image. In this technique - transform the image into frequency. It is used for smoothing and sharpening of image by removing the high or low frequency components. 
There are mainly 3 types of Frequency Domain filtering techniques but here only talking about smoothing and sharpening. 
Instead of doing convolution operation to each image pixel with a kernel matrix, Here transforming it into frequency, then mask it and removing high/low frequencies to make the image smoothing or sharpening.

Spatial Domain Filtering is used directly on pixels of an image. Mask or kernel is usually considered to be added in size so that it has specific center pixel. This mask is moved on the image such that the center of the mask traverses all the image pixels. 
It is commonly used to ‘clean up’ the output, removing aberration in the beam due to variations in the medium itself.There are many kinds of spatial filters, here use Smoothing or blurring filter and sharpening or edge detection filter. 

