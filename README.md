# 🌲🔥 Forest Fire Detection Using Deep Learning

This project aims to detect forest fires automatically from images using a custom Convolutional Neural Network (CNN) model. With increasing wildfire incidents due to climate change, early detection is critical. This deep learning–based solution provides a fast, scalable, and intelligent way to predict fire outbreaks from visual data.

---

## 📌 Project Overview

Forest fires are among the most devastating natural disasters, threatening the environment, wildlife, and human settlements. Manual monitoring methods like satellite imagery and ground patrols are slow and resource-intensive. This project presents a deep learning-powered image classification system that can detect forest fires from images with high accuracy and deploys it as an interactive web application using **Streamlit**.

---

## 🚀 Features

- Automatically classifies images as **Fire** or **No Fire**
- Achieves **83% accuracy** on the test dataset
- Integrated with **Streamlit** for an interactive user interface
- Allows users to:
  - Upload custom images
  - View real-time predictions and confidence scores
  - Hear alert sounds for detected fires
  - Download prediction results as reports
  - Experience UI enhancements with animation (via `streamlit-lottie`)

---

## 🧠 Tech Stack & Libraries

| Tool / Library         | Purpose                                             |
|------------------------|-----------------------------------------------------|
| **Python**             | Core programming language for development           |
| **TensorFlow & Keras** | Model building and training (Deep Learning)         |
| **CNN**                | Custom neural network architecture for classification |
| **Google Colab**       | Cloud environment used for model training/testing   |
| **Kaggle**             | Source of wildfire image dataset                    |
| **NumPy & Pandas**     | Data manipulation and numerical operations          |
| **Matplotlib & Seaborn** | Visualization of training performance and confusion matrix |
| **Streamlit**          | Deployment of the interactive web application       |
| `streamlit-lottie` / `streamlit-extras` | For UI enhancements and animations |

---

## 📁 Project Structure

forest-fire-detection/
│
├── dataset/ # Fire and No Fire images
├── model/ # Saved model file (.h5)
├── app.py # Streamlit app script
├── training.ipynb # Model training notebook
├── utils.py # Helper functions (preprocessing, prediction, etc.)
├── requirements.txt # Required dependencies
└── README.md # Project overview


---

## 🛠️ How to Run

1. **Clone the repository:**
   ```bash
   git clone https://github.com/your-username/forest-fire-detection.git
   cd forest-fire-detection

📊 Model Performance
Training Accuracy: ~90%

Validation Accuracy: ~84%

Test Accuracy: 83%

Confusion matrix and performance plots are available in the notebook.

📷 Sample Predictions

| Image                     | Prediction | Confidence |
| ------------------------- | ---------- | ---------- |
| ![](examples/fire.jpg)    | Fire       | 94.6%      |
| ![](examples/no_fire.jpg) | No Fire    | 91.2%      |

🤝 Acknowledgments
Kaggle for providing the dataset

Google Colab for training support
