# 🚗 Car Brand Classifier

An image classification model that identifies car brands using transfer learning with MobileNetV2.

## 📊 Project Overview

This project demonstrates the application of transfer learning for image classification. The model was trained to recognize different car brand logos using a pre-trained MobileNetV2 architecture fine-tuned on a custom dataset.

## 🛠️ Technologies Used

- **Python 3.x**
- **TensorFlow/Keras** - Deep learning framework
- **MobileNetV2** - Pre-trained CNN architecture
- **Google Colab** - Training environment with GPU acceleration
- **Kaggle API** - Dataset management

## 🎯 Model Architecture

- Base Model: MobileNetV2 (pre-trained on ImageNet)
- Custom layers: Global Average Pooling, Dense (128 units), Dropout (0.5)
- Output: 5 car brands classification
- Optimizer: Adam
- Loss Function: Sparse Categorical Crossentropy

## 📈 Results

- Achieved high training accuracy through transfer learning
- Model successfully classifies car brand logos
- Training completed in ~10 epochs

## 🚀 How to Run

1. Open the notebook in Google Colab
2. Upload your Kaggle API key when prompted
3. Run all cells sequentially
4. Upload car logo images to test predictions

## 📝 Key Learnings

- Implemented transfer learning using pre-trained models
- Handled image preprocessing and data augmentation
- Trained deep learning models using GPU acceleration
- Gained experience with TensorFlow/Keras API

## 🔗 Links

- [Google Colab Notebook](link-to-your-colab-if-you-share-it)
- [Dataset Source](https://www.kaggle.com/)

---

**Note:** This project was built as a learning exercise to explore computer vision and transfer learning techniques.
