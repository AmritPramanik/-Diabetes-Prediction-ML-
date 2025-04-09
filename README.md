# Diabetes Prediction Model

# 🎬 Bollywood Celebrity Predictor

A Python-based deep learning application that identifies the closest matching Bollywood celebrity from a given input image with a visible face. This project uses facial recognition and classification techniques to predict the most similar celebrity face from a pre-trained model.

---

## 📂 Dataset

The dataset is sourced from Kaggle:  
[Bollywood Celeb Localized Face Dataset](https://www.kaggle.com/datasets/sushilyadav1998/bollywood-celeb-localized-face-dataset)

---

## 📦 Packages Used

| Package       | Purpose                                      |
|---------------|----------------------------------------------|
| `Python`      | Core programming language                    |
| `NumPy`       | Numerical computations                       |
| `Pandas`      | Data manipulation and analysis               |
| `scikit-learn`| ML utilities (e.g., train/test split, etc.)  |
| `Jupyter`     | Development environment                      |

---

## 🔁 Process Workflow

1. **Load an Image**  
   Upload a picture (can be of yourself or any other face).

2. **Face Detection**  
   Use **MTCNN** (Multi-task Cascaded Convolutional Networks) to detect and extract faces from the image.

3. **Preprocessing**  
   Resize and normalize the face for input into the neural network.

4. **Model Prediction**  
   Load the face image into a pre-trained **ResNet-50** model.

5. **Output**  
   Display the Bollywood celebrity with the closest resemblance to the input image.

---

## 🧠 Model Details

- **Architecture:** ResNet-50  
- **Input Size:** 224x224 RGB  
- **Framework:** TensorFlow / Keras  
- **Face Detection:** MTCNN  
- **Training:** Pre-trained on Bollywood celeb face dataset from Kaggle

---

## 🚀 How to Run

1. Clone the repository:
   ```bash
   git clone https://github.com/yourusername/bollywood-celeb-predictor.git
   cd bollywood-celeb-predictor
