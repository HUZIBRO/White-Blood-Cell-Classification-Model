# White-Blood-Cell-Classification-Deep-Learning-Approach-for-Medical-Imaging


## 📌 Objective
Leverage computer vision and deep learning to automate the classification of white blood cell types from microscopic images—enhancing efficiency in medical diagnostics.

## 🧰 Tools & Libraries
Python

TensorFlow / Keras

OpenCV

Pandas, NumPy

Matplotlib

Scikit-learn

## 📂 Workflow Overview
### 📥 1. Data Loading & Preprocessing
Read image files using os and cv2

Resized all images to 64x64 for model consistency

Normalized pixel values for improved convergence

### 🔎 2. Data Exploration & Label Encoding
Visualized sample images for insight into class distribution

Converted categorical labels to one-hot encoded format using pandas and keras.utils.to_categorical

### 🔀 3. Train-Test Split
Used train_test_split to split data for training and validation

### 🧠 4. CNN Model Architecture
Implemented a Sequential CNN using:

Conv2D, MaxPooling2D, Dropout, Dense

Compiled with:

Loss: categorical_crossentropy

Optimizer: adam

### 📊 5. Model Training & Evaluation
Trained over multiple epochs

Visualized training accuracy and loss

Compared predictions vs. actual labels for performance review

### 💾 6. Model Saving & Inference
Saved trained model using tf.saved_model.save

Reloaded and used the model for prediction on test data

## ✅ Skills Demonstrated
Deep Learning & CNNs: Designing and training convolutional architectures

Computer Vision: Handling, preprocessing, and visualizing image data

Data Science Workflow: From data ingestion to model evaluation

TensorFlow/Keras Proficiency: Building, saving, and reusing models

Model Validation: Visualization and label comparison for classification accuracy
