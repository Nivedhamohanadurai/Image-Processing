# Image-Processing

Several techniques were developed to detect and segment the Brain tumor using several Segmentation algorithms such as Watershed Algorithm, K-means clustering. To identify the brain tumor, scanned MRI images are given as the input.

K-means, Thresholding and Watershed techniques put up to the partitioning of brain tumors. The segmentation of the image depends on the image being segmented into regions. Image segmentation is based on comparison quality. Those with Similarities are placed out into groups so that we could get the features and important information regarding the image.

## K-Means Clustering
K-Means Clustering groups the unlabeled dataset into different clusters. In K-means, K defines the number of pre-established clusters that need to be produced in the process, and if K=2, there will be two clusters, and for K=3, there will be three clusters, and so on. It allows us to cluster the data into different groups and to discover the categories of groups in the unlabeled dataset on its own without the need for any training. Each cluster is associated with a centroid. The main objective of this algorithm is to reduce the sum of distances between the data point and their corresponding clusters. The algorithm takes the dataset as input, and divides it into k-number of clusters, and repeats the process until it does not find the best clusters. The value of k should be prearranged in this algorithm.
## Thresholding
Threshold segmentation is based on a simple segmentation technique where we input an image called the grayscale image is first converted into a binary format using the binarization technique. This segmentation method is carried out on a threshold value that varies as per the features of the grayscale image while being converted into a binary image format. The selection of a threshold value for segmentation is the primary concern. Image utilizing histogram helps us in finding a single threshold value for the same. Image Utilizing Histogram is a sort of histogram that is based on a graphical representation for the tonal distribution in a advanced picture. The quantity of pixels for each tonal value is plotted on the histogram.
## Watershed Algorithm
Watershed segmentation is remarkable, compared to other plans of action for collecting image pixels based on their intensity. Pixels at the same intensity are combined, which eases the segmentation procedure so that we can separate a tumor from the image. Watershed is a scientific morphological working technique.

Here "sample_image" is the input MRI scan
