# Rubber
Rubber Dataset
You can download the rubber tree dataset from Baidu Netdisk by yourself through the shared file on Netdisk: RUBBER date
Link: https://pan.baidu.com/s/1sLIHYhcxILfY3-U_oP78dg Extraction code: 1eiy，
# Rubber Tree Point Cloud & Image Dataset
This dataset is constructed for **rubber tree individual segmentation, semantic recognition and 3D model training** based on UAV-LiDAR and optical image data collected from large rubber forest areas in Hainan, China.

# Data Content
- **3D Point Cloud Data**: In standard LAS format, covering complex forest scenes including fallen leaves, understory vegetation and intertwined rubber tree canopies.
- **High-Resolution Optical Images**: Top-view JPEG images of rubber tree canopies, used for visual annotation and 2D-3D fusion research.

# Preprocessing & Annotation
1. Point Cloud Preprocessing
   - Statistical Outlier Filtering for noise removal
   - Cloth Simulation Filtering (CSF) for ground/non-ground segmentation
   - DEM generation and height-difference calculation
   - Height & point density joint filtering to obtain clean rubber tree point clouds
2. **Manual Annotation**
   - Point clouds: 25 rubber trees manually denoised; each sample assigned **semantic label** and **instance label (tree ID)**
   - Images: Annotated via Labelme, with crown regions labeled and saved in JSON format; images uniformly resized to 224×224 pixels

# Dataset Partition
Total 36 regional subsets, split as:
- Training set: 23
- Validation set: 8
- Test set: 5

# Application Scenario
Suitable for deep learning model training and validation in rubber tree point cloud semantic segmentation, instance segmentation, single tree detection and forest structure parameter extraction.
