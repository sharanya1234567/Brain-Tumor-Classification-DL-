Brain-Tumor-Classification-with-DL

This project presents an advanced deep learning-based system for brain tumor classification. By leveraging a pre-trained VGG19 convolutional neural network, TensorFlow, and Flask for deployment, the system offers a robust solution for healthcare professionals to efficiently identify brain tumors from MRI images.

🧠 Objective
The primary goal is to develop a reliable and user-friendly AI model to assist medical professionals in diagnosing and planning effective treatments for brain tumors. This involves:

High Accuracy Classification: Identifying tumor types using MRI scans.
Real-Time Deployment: Delivering predictions through an accessible web application powered by Flask.

🔍 Problem Statement
Brain tumor classification is crucial for determining appropriate treatments such as surgery, chemotherapy, or radiation. However, challenges include:

Limited high-quality datasets.
Variability in tumor shapes, sizes, and textures.
Need for rapid, accurate diagnosis to enable timely interventions.

📂 Dataset Description
Source: Kaggle
Categories:
No Tumor: Images without any brain tumor.
Tumor: Images indicating the presence of a brain tumor.
Data Distribution:
Training: 79.4%
Testing: 15%
Validation: 15%

⚙️ Model Architecture
Base Model: VGG19 (Transfer Learning).
Key Features:
Pre-trained weights for efficient feature extraction.
Fine-tuned layers for specific dataset adaptation.
Dense layers for precise classification.
Softmax layer for output probabilities.

🛠️ Key Techniques
Image Preprocessing:
Augmentation: Rotation, flipping, scaling.
Resizing to 224x224 pixels for VGG19 compatibility.
Normalization for optimized training.
Training Optimizations:
Early Stopping and Model Checkpoints.
Learning rate adjustments using SGD with momentum.

🚀 Deployment
The trained model is deployed using Flask, providing:

A lightweight and interactive web interface.
Real-time predictions from uploaded MRI images.
💡 Insights and Future Work
While the current model achieves moderate performance, further improvements such as enhanced dataset quality and fine-tuning can unlock its full potential in clinical applications.





