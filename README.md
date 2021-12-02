# Histogram Equalisation and Matching ⭐

An image histogram is a type of histogram that acts as a graphical representation of the tonal distribution in a digital image. It plots the number of pixels for each tonal value. By looking at the histogram for a specific image a viewer will be able to judge the entire tonal distribution at a glance. Image histograms are present on many modern digital cameras. Photographers can use them as an aid to show the distribution of tones captured, and whether image detail has been lost to blown-out highlights or blacked-out shadows. This is less useful when using a raw image format, as the dynamic range of the displayed image may only be an approximation to that in the raw file.

## Histogram 🔥

Histogram is a graphical representation of numerical data. It groups a number of data points into user specified ranges. In digital image processing, histograms represent the intensity distribution of an image. Buckets or bins of values are created that divide the entire range into a series of intervals and a rectangle is created over each bin corresponding to the number of cases for each bin, i.e. its frequency. The bins can be of equal as well as unequal sizes. If the bin sizes are unequal then the height of the rectangle created represents the area under the rectangle proportional to the frequency of cases in the bucket. Histograms can be used to estimate the probability density function of the data provided and in this case the total area of the histogram is always normalized to 1.

## Histogram Equalisation 🔥

Histogram Equalization is a method of computer image processing to adjust the contrast of the image using the histogram of the image. Histogram Equalization can be achieved by redistributing the most frequent intensity values present in the image's histogram. This process leads to the improvement in the overall contrast of the image. Histogram Equalization can be used for images with both dark and bright backgrounds but can lead to increasing the contrast of the background noise, since the process doesn't bifurcate noise and signal values. The method can be used to enhance low contrast images for better viewing ability like x-ray, thermal and satellite images. Histogram Equalization is a computationally efficient technique which in theory can be used to recover the original image if the equalization function is known. 

## Histogram Matching 🔥

Histogram Matching or Histogram Specification is the process of unifying the contrast level of the specified images (source and destination). The source image's histogram is transformed to match with the destination image's histogram. Histogran Equalization is a special case of histogram matching in which the destination image's histogram is uniformly distributed. Histogram Matching is used to remove intensity values providing little to no information about the image and thereby compressing the range of an image. This process enables that information only at specific intensity levels can be viewed and the source image's histogram can be matched to represent the destination image's histogram or predefined probability density functions like exponential, Rayleigh, Gaussian etc.


## Instructions to Run :runner:

* The dataset is being downloaded from the given hashed link. 

* To run, open the colab file and select the image using the slider given. Then run the corresponding cells to get the results.

## References and Credits 💳

1) Histogram Equalization
- https://en.wikipedia.org/wiki/Histogram_equalization
- https://en.wikipedia.org/wiki/Cumulative_distribution_function

2) Histogram Matching
- https://en.wikipedia.org/wiki/Histogram_matching
- http://paulbourke.net/miscellaneous/equalisation/
