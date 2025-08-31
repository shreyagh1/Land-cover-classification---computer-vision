# Land-cover-classification---computer-vision
This is my first computer vision project. I used satellite images from EuroSAT dataset to perform simple land cover classification, separating vegetation, water, and urban areas. The project uses Python, OpenCV, and Jupyter Notebook with color thresholding and morphological operations. A starting point for exploring CV.

I wanted to start with something simple but meaningful, so I chose to work with satellite images for land cover classification.
The goal of this project is to classify different regions in a satellite image into categories such as:
-> Vegetation (green areas)
-> Water bodies (rivers, lakes, sea)
-> Urban/Soil (built-up or barren land)
I used Python, OpenCV, and Jupyter Notebook to:
- Load and preprocess satellite images.
- Apply color thresholding in HSV space to separate land cover types.
- Use morphological operations to clean up noise and make the classification maps smoother.
- Visualize results by comparing the original image with the classified map.
- Although this project uses a simple rule-based method, it helped me understand the basics of:
- Image preprocessing
- Segmentation using color ranges
- Post-processing masks to improve results
  In the future, I plan to extend it using clustering (K-means) and deep learning (CNNs) on larger satellite datasets.

  Dataset download link: https://www.kaggle.com/datasets/apollo2506/eurosat-dataset
