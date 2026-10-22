# 🐱🐶 CNN Cat and Dog Classifier

A Deep Learning project that classifies images as **Cats or Dogs** using a Convolutional Neural Network (CNN), TensorFlow, Keras, and Python.

## 📌 Project Overview

The goal of this project is to classify an input image into one of two categories: Cat or Dog.

The CNN model was trained previously. In this project, I loaded the trained model and used it to make predictions on test images without training the model again.

## 📂 Project Structure

```text
CNN-CAT-AND-DOG-CLASSIFIER/
├── CNN/
│   ├── cnn_imp.ipynb
│   └── requirements.txt
└── README.md
```

## 📊 Dataset

- **Source:** Kaggle
- **Task:** Binary image classification
- **Classes:** Cat and Dog
- **Image Size:** 150 × 150 pixels
- **Preprocessing:** Images are resized and normalized by dividing pixel values by 255.

The dataset contains separate training and testing images.

## 🧠 Model Details

- **Architecture:** Convolutional Neural Network (CNN)
- **Framework:** TensorFlow / Keras
- **Convolutional Layers:** 4
- **Activation Functions:** ReLU and Sigmoid
- **Pooling:** Max Pooling
- **Regularization:** Dropout
- **Optimizer:** Adam
- **Loss Function:** Binary Crossentropy
- **Output:** Cat or Dog prediction

## ⚙️ Technologies Used

- Python
- TensorFlow
- Keras
- NumPy
- Matplotlib
- Jupyter Notebook

## 🚀 How It Works

1. Load the previously trained CNN model.
2. Upload or select a test image.
3. Resize the image to 150 × 150 pixels.
4. Normalize pixel values to the range 0–1.
5. Pass the image to the model for prediction.
6. Display the predicted class and confidence score.

## ▶️ Run the Project

### 1. Clone the repository

```bash
git clone https://github.com/Prince01104/CNN-CAT-AND-DOG-CLASSIFIER.git
```

### 2. Open the project folder

```bash
cd CNN-CAT-AND-DOG-CLASSIFIER
```

### 3. Install dependencies

```bash
pip install -r CNN/requirements.txt
```

### 4. Open the notebook

Launch Jupyter Notebook and open `CNN/cnn_imp.ipynb`.

**Note:** The notebook uses a previously trained model for inference. The trained model file and dataset must be available at the paths specified in the notebook.

## 🎯 Key Learning Outcomes

- Understanding CNN architecture for image classification.
- Image preprocessing and normalization.
- Loading and using a pretrained Keras model.
- Making predictions on unseen images.
- Evaluating model predictions using test images.

## 👨‍💻 Author

**Prince Singh**

GitHub: [Prince01104](https://github.com/Prince01104)

---

⭐ If you find this project interesting, feel free to explore the repository.
