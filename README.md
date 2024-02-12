# Medical Image Segmentation with U-Net

Python code for medical image segmentation using U-Net architecture. This repository is organized into three modules, each serving a specific purpose in the segmentation process.

## Modules

### Module 1: Data Preprocessing and Slicing
- **Load** medical image volumes and masks (*NIfTI format*).
- **Normalize** image intensity and slice volumes.
- **Save** 2D slices as PNG images.

### Module 2: U-Net Model Training
- Implement U-Net for semantic segmentation.
- **TensorFlow** and **Keras** used for training.
- **Save** model checkpoints and allow continuation.
- Visualize training data with **niwidgets**.

### Module 3: Image Segmentation and 3D Mesh Generation
- Load trained U-Net model for predictions.
- Visualize original, scaled, and predicted slices.
- Generate 3D mesh with **marching cubes** algorithm.
- **Save** resulting mesh as STL file.

## Usage
1. Install dependencies: `pip install -r requirements.txt`
2. Execute modules based on your requirements.

## Dependencies
- **nibabel**
- **numpy**
- **matplotlib**
- **opencv-python**
- **tensorflow**
- **keras**
- **niwidgets**
- **scikit-image**
- **meshplot**
- **numpy-stl**

## Contribution
Contributions are welcome! Feel free to report issues or suggest improvements.
