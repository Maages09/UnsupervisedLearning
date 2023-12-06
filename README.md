#  Unsupervised_Learning.ipynb

## DESCRIPTION:
This Jupyter notebook script is designed for unsupervised learning using KMeans clustering. It focuses on processing and clustering images from a specified dataset.

## REQUIREMENTS:
- Python 3
- Libraries: os, cv2, numpy, matplotlib, scikit-learn

## FUNCTIONALITY:
1. The script sets the number of threads for OpenMP.
2. It specifies a path to a dataset containing images and annotations.
3. It includes a function 'load_data' to load and preprocess the images and annotations from the dataset.
4. Images are resized to a consistent size and converted into a NumPy array.
5. The data is then standardized using StandardScaler.
6. KMeans clustering is applied to the standardized image data.
7. The clusters are visualized using matplotlib.

## USAGE:
- Modify 'dataset_path' to the path of your image dataset.
- The number of clusters in KMeans can be adjusted by changing the 'n_clusters' variable.
- Execute the script in a Jupyter notebook environment.

## NOTE:
- Ensure the dataset path contains the correct format of images and annotations.
- The script is set up for a specific dataset structure and might require adjustments for different datasets.
