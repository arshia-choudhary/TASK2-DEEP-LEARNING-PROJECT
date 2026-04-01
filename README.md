# TASK2-DEEP-LEARNING-PROJECT : Image Classification using CNN (TensorFlow)

## Project Overview

    This project demonstrates the implementation of a **Deep Learning model for Image Classification** using a **Convolutional Neural Network (CNN)**. The model is trained on the handwritten digit dataset (MNIST) to classify images into one of ten categories (digits 0–9).
    
    The primary objective of this project is to build a functional deep learning model and visualize its performance using graphs such as accuracy and loss curves. This project showcases the complete workflow of a deep learning pipeline, including data preprocessing, model building, training, evaluation, and visualization.
    
    ---

## Key Features

    * Implementation of a **CNN (Convolutional Neural Network)**
    * Image classification using grayscale image data
    * Data preprocessing and normalization
    * Model training and validation
    * Visualization of model performance (accuracy & loss graphs)
    * Prediction on test data



## Technologies Used

    * Python
    * TensorFlow / Keras
    * NumPy
    * Matplotlib
  

## Project Structure

    ```id="a92kdl"
    deep_learning_project/
    │
    ├── dl_project.ipynb
    ├── requirements.txt
    └── README.md
    ```


## Dataset Information

    The model is trained on the **MNIST dataset**, which contains:
    
    * 60,000 training images
    * 10,000 testing images
    * Each image is 28x28 pixels (grayscale)
    * Labels range from 0 to 9
    
    This dataset is widely used as a benchmark for image classification tasks in deep learning.


## Project Workflow
    
    ### 1️⃣ Data Loading
    
    The dataset is loaded directly using TensorFlow’s built-in dataset module. This eliminates the need for manual data collection.
    
    ### 2️⃣ Data Preprocessing
    
    * Pixel values are normalized (scaled between 0 and 1)
    * Data is reshaped to fit CNN input requirements
    * Improves model performance and convergence
    
    ### 3️⃣ Model Building
    
    A CNN model is built using multiple layers:
    
    * Convolutional layers (feature extraction)
    * MaxPooling layers (dimensionality reduction)
    * Dense layers (classification)
    
    ### 4️⃣ Model Compilation
    
    The model is compiled using:
    
    * Optimizer: Adam
    * Loss Function: Sparse Categorical Crossentropy
    * Metric: Accuracy
    
    ### 5️⃣ Model Training
    
    The model is trained on training data for multiple epochs while validating performance on test data.
    
    ### 6️⃣ Model Evaluation
    
    The trained model is evaluated using test data to determine accuracy and loss.
    
    ### 7️⃣ Visualization
    
    Graphs are plotted to visualize:
    
    * Training vs Validation Accuracy
    * Training vs Validation Loss
    
    These graphs help in understanding model performance and detecting overfitting.
    
    ### 8️⃣ Prediction
    
    The model is used to predict labels for unseen test images and compare them with actual values.
    


## ▶️ How to Run the Project

    ### Step 1: Install Required Libraries
    
    ```bash id="c3k9wq"
    pip install tensorflow matplotlib numpy
    ```
    
    ---
    
    ### Step 2: Start Jupyter Notebook
    
    ```bash id="9g1krt"
    jupyter notebook
    ```
    
    ---
    
    ### Step 3: Open Notebook
    
    ```id="0k2zlp"
    dl_project.ipynb
    ```
    
    ---
    
    ### Step 4: Run All Cells
    
    * Use `Shift + Enter` to execute each cell
    * Wait for model training to complete
    
   

## 📊 Output

    After running the project, you will get:
    
    * Model accuracy (around 97–99%)
    * Accuracy graph (training vs validation)
    * Loss graph
    * Sample predictions


## Future Improvements

    * Use more complex datasets (CIFAR-10, ImageNet)
    * Add data augmentation
    * Implement dropout to reduce overfitting
    * Deploy model using Flask or FastAPI
    * Build a web interface for real-time predictions


## Conclusion

    This project successfully demonstrates how to build and train a **deep learning model for image classification** using TensorFlow. It highlights the importance of CNNs in computer vision tasks and provides a strong foundation for more advanced deep learning applications.



