# Image-Segmentation-using-Kmeans
K-Means Application : Image Segmentation
Image segmentation is the process of partitioning a digital image into multiple distinct regions containing each pixel with similar attributes i.e. classification of an image into different groups. There are different methods, and one of the most popular methods is the k-means clustering algorithm. K-Means clustering algorithm is an unsupervised algorithm, and it is used to segment the interest area from the background.

OBJECTIVE:
Take a bright colorful image (Eg: image having fruits in it) and implement image segmentation using K-Means. You can first try to implement K-Means on iris dataset to understand its working and then extend the same logic, using the image pixels as the data points. Hint: All the K centroids will represent a color and therefore, you can initialize all the pixels to belong to a cluster randomly and then start the training of the centroids

STEPS:
- Importing libraries
- Read the image file and convert it to NumPy Array
- Assign random labels to individual pixels
- Define function to generate the initial mean values from initial labels
- Update labels by comparing distances with previous mean values and generate new labels
- Generate new mean values from the updated labels
- Run the K-Means Algorithm and obtain the final labels and means
- Use the finally obtained mean and labels to segment the image
