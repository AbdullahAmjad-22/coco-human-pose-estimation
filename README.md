# COCO Human Pose Estimation Using PyTorch

# Overview
This project focuses on human pose estimation using PyTorch and
the COCO Keypoints dataset. The goal is to work with annotated
human images and train a model for human keypoint prediction.

# Technologies Used
- Python
- PyTorch
- torchvision
- NumPy
- PIL (Pillow)
- COCO Keypoints dataset

# Key Features
- Prepared image data and keypoint annotations for model training.
- Implemented a custom PyTorch Dataset class.
- Grouped annotations by image ID to associate images with
  their corresponding annotations.
- Loaded images and converted them into tensors.
- Processed human keypoints containing x-coordinate,
  y-coordinate, and visibility information.
- Validated bounding-box dimensions during data preparation.
- Trained a human pose-estimation model using the COCO dataset.

# Dataset
The project uses the COCO Keypoints dataset, which provides
images and annotations for human pose estimation.

The dataset is not included in this repository. Users must
obtain the appropriate COCO data files and configure the
dataset paths before running the notebook.

# Project Contents
- `coco_pose_estimation.ipynb` - Model training and
  dataset preparation notebook.

# How to Run
1. Open the notebook in Google Colab.
2. Configure the COCO dataset paths.
3. Install any required dependencies.
4. Run the notebook cells in order.

# Learning Outcomes
- Computer vision and human pose estimation.
- Working with annotated image datasets.
- Custom dataset creation using PyTorch.
- Image preprocessing and keypoint handling.
- Deep learning model training.

## Notes
This project was developed as a hands-on computer vision
and deep learning project.
