# Global_Wheat_Detection-
Object detection for agricultural monitoring using Faster R-CNN and YOLOv5m6 on the Global Wheat Detection dataset. Developed for CS975 Deep Learning module.


# Global Wheat Head Detection Using Faster R-CNN and YOLOv5m6

This project focuses on object detection in agricultural settings, specifically identifying wheat heads using state-of-the-art deep learning models: Faster R-CNN and YOLOv5m6. The work was developed for the CS975 Deep Learning module and uses the Kaggle Global Wheat Detection dataset.

## 📌 Project Objectives

- Implement and evaluate two object detection models: Faster R-CNN and YOLOv5m6.
- Perform bounding box predictions on wheat head images.
- Compare performance based on accuracy, IoU, and detection speed.
- Visualize predictions to assess model precision and recall qualitatively.

## 🗂 Dataset

- **Source**: [Kaggle - Global Wheat Detection](https://www.kaggle.com/competitions/global-wheat-detection/)
- **Images**: High-resolution field images of wheat crops
- **Labels**: Bounding boxes for wheat heads (`x`, `y`, `width`, `height`)
- **Split**: Manual train-test split

## 🧠 Models Used

- **Faster R-CNN**: Region-based convolutional neural network with high accuracy
- **YOLOv5m6**: Real-time object detection model with fast inference time

## 🔧 Technologies & Tools

- Python
- PyTorch
- Albumentations (for data augmentation)
- OpenCV
- matplotlib
- YOLOv5 repo (via Ultralytics or local model inference)
- Google Colab / Kaggle Notebook

## 📈 Evaluation Metrics

- Mean Average Precision (mAP)
- Intersection over Union (IoU)
- Precision & Recall
- Inference time

## 🚀 How to Run

1. Download the Global Wheat Detection dataset from Kaggle.
2. Run the notebook cells in order (preferably in Kaggle/Colab).
3. Configure YOLO model paths and checkpoint files if running YOLOv5m6.
4. Evaluate and visualize the predictions.

## 👨‍💻 Author

- **Name**: Yash Dhakade  
- **University**: University of Strathclyde  

## 📌 License

This project is for academic and educational purposes only.

