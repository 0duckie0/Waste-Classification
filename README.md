This project is a deep learning-based waste classification system that categorizes waste into organic and recyclable classes using TensorFlow and Keras. The model is trained using a large dataset of waste images and leverages transfer learning with MobileNetV2 for improved accuracy.

📌 Features
Dataset Handling: Uses ImageDataGenerator for loading and preprocessing images.
Transfer Learning: Implements MobileNetV2 for feature extraction.
Binary Classification: Differentiates between organic and recyclable waste.
Visualization: Displays sample images from the dataset.
Model Training & Evaluation: Uses accuracy and loss metrics for assessment.
🛠 Tech Stack
Python
TensorFlow/Keras
NumPy & Matplotlib
📂 Dataset
The dataset consists of 50,154 images, categorized into two classes:

Organic Waste
Recyclable Waste
🚀 Model Architecture
Loads the dataset and applies rescaling.
Uses MobileNetV2 (pretrained weights) without the top layer.
Adds a Global Average Pooling layer.
Uses a final Dense layer with a sigmoid activation for binary classification.
📊 Training
Optimizer: Adam
Loss Function: Binary Cross-Entropy
Epochs: 2 (can be increased for better performance)
📌 Results
The model starts learning but may require hyperparameter tuning to improve accuracy.
📷 Sample Output
Below are some sample classified images:


🔧 Future Improvements
Increase the number of training epochs.
Fine-tune the MobileNetV2 model.
Use data augmentation for better generalization.
