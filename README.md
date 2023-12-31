# Kmeans-Clustering_Colors

```markdown
# Image Segmentation using K-Means Clustering

This is a Python script for performing image segmentation using K-Means clustering. The code utilizes libraries such as NumPy, OpenCV, Matplotlib, and scikit-learn's KMeans implementation to segment an input image into distinct color clusters.

## Getting Started

To run this code, you need to have Python and the required libraries installed on your system. You can install them using the following:

```bash
pip install numpy pandas matplotlib opencv-python-headless scikit-learn
```

## Usage

1. Download the `input_image.jpg` you want to segment and place it in the same directory as the script.

2. Open the Jupyter Notebook or Python environment, such as Google Colab.

3. Run the provided code in your Python environment. Make sure the input image is in the same directory.

4. The code will load the input image, perform K-Means clustering with 4 clusters, and display the segmented image.

## Code Explanation

- The input image is read using OpenCV, and its colors are converted from BGR to RGB.

- The image is flattened into a 2D array of RGB color values.

- K-Means clustering is applied to the flattened image data with 4 clusters.

- The script displays the cluster centers and labels, along with their respective inertias.

- A new image is generated by replacing each pixel's color with the color of its assigned cluster center.

- The segmented image is displayed.

## Results

The code will produce a segmented image with distinct color clusters, allowing you to visualize the segmented regions within the input image.

## License

This project is licensed under the MIT License. Feel free to use and modify the code according to your needs.

## Acknowledgments

- [NumPy](https://numpy.org/)
- [Pandas](https://pandas.pydata.org/)
- [Matplotlib](https://matplotlib.org/)
- [OpenCV](https://opencv.org/)
- [scikit-learn](https://scikit-learn.org/)

