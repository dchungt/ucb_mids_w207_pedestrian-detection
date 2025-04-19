# Pedestrian Detection: ML Model Comparison

This project evaluates the effectiveness of various machine learning models—Logistic Regression, CNNs, and YOLO—for pedestrian detection using images from the Waymo Open Dataset. Our goal was to compare model performance on a real-world safety-critical application.

## Dataset

- 100 scenes from Waymo’s autonomous vehicle data
- 50 images per scene, filtered for pedestrian presence
- Sub-images (64×64) labeled based on pedestrian bounding box overlap
- Data augmentations: flips, rotations, resizing

## Models Evaluated

- **Logistic Regression:** Basic baseline with limited spatial awareness
- **CNN:** Improved performance with custom architecture and regularization
- **YOLOv5:** State-of-the-art object detector, fine-tuned on our dataset

## Key Results

| Model              | Accuracy | AUC    |
|--------------------|----------|--------|
| Logistic Regression| 0.68     | —      |
| CNN                | 0.82     | 0.84   |
| YOLO               | 0.98     | 0.93   |

## Data Access

Due to GitHub's size limits, datasets are available via Google Drive:
[Link to Google Drive](https://drive.google.com/drive/u/0/folders/12TF4XvG18DQhwnVzNyLXjmu1AWh_Blu9)

## Contributors

Daniel Chung, Gautam Sai Yarramreddy, Jacob Lu
