# Sample Data Description

Each dataset sample contains:

## Camera Data
- RGB image
- Resolution: 224 × 224 pixels
- Format: PNG

## LiDAR Data
- 3D point cloud
- Format: NumPy (.npy)
- Contains XYZ coordinates

## Labels
Each sample includes:

- Bounding Boxes
- Object Classes
- Segmentation Masks

## Example Sample Structure

sample_001/
 ├── image.png
 ├── lidar.npy
 ├── label.json

## Annotation Types

1. Bounding Boxes  
2. Segmentation Masks  
3. Object Class Labels
