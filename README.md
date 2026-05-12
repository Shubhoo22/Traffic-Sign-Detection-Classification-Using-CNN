# Traffic Sign Detection & Classification using CNN

A deep learning based Traffic Sign Detection and Classification system built using CNN, TensorFlow, and OpenCV.  
The model is trained on the German Traffic Sign Recognition Benchmark (GTSRB) dataset containing 43 traffic sign classes.

---

## Project Overview

This project uses Convolutional Neural Networks (CNN) to classify traffic signs from images.  
The system performs image preprocessing, augmentation, training, and prediction to accurately recognize traffic signs in real time.

---

## Features

- Traffic Sign Classification using CNN
- GTSRB Dataset (43 Classes)
- Image Preprocessing & Augmentation
- Model Training using TensorFlow/Keras
- Real-time Prediction Support
- Accuracy & Loss Visualization
- Confusion Matrix Evaluation
- OpenCV Integration

---

## Technologies Used

- Python
- TensorFlow
- Keras
- OpenCV
- NumPy
- Pandas
- Matplotlib
- Scikit-learn

---

## Dataset

Dataset Used:
German Traffic Sign Recognition Benchmark (GTSRB)

- Total Classes: 43
- Image-based Traffic Sign Dataset
- Publicly available for research purposes

---

## Model Architecture

The CNN model includes:

- Convolution Layers
- MaxPooling Layers
- Dropout Layers
- Fully Connected Dense Layers
- Softmax Activation

---

## Project Structure

```bash
Traffic-Sign-Detection-Classification-Using-CNN/
│
├── dataset/
├── model/
├── train.py
├── predict.py
├── requirements.txt
├── README.md
└── output/
```

---

## Installation

Clone the repository:

```bash
git clone https://github.com/Shubhoo22/Traffic-Sign-Detection-Classification-Using-CNN.git
```

Move into the project directory:

```bash
cd Traffic-Sign-Detection-Classification-Using-CNN
```

Install dependencies:

```bash
pip install -r requirements.txt
```

---

## Run the Project

Train the model:

```bash
python train.py
```

Run prediction:

```bash
python predict.py
```

---

## Results

- Achieved approximately 95% classification accuracy
- Improved model generalization using data augmentation
- Evaluated using confusion matrix and accuracy/loss curves

---

## Future Improvements

- Real-time webcam traffic sign detection
- Streamlit/Flask web deployment
- Transfer Learning using ResNet/MobileNet
- Model optimization for edge devices

---

## Author

Subham Mondal

GitHub:
https://github.com/Shubhoo22

---

## License

This project is intended for educational and learning purposes.