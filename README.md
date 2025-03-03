# Home Aassignment2
# CS5720 Neural Networks and Deep Learning - Home Assignment 2

## Student Information
Name: Kalyan Guntuka
Student ID : 700757036
Course: Neural Networks and Deep Learning


## Assignment Overview
This document provides the solutions for **Home Assignment 2**, covering Chapters 4 and 5 of the course. The assignment includes both theoretical explanations and Python implementations of deep learning concepts, including cloud computing, convolution operations, CNN feature extraction, and architecture comparisons.


## Solutions

### **1. Cloud Computing for Deep Learning**
#### **(a) Elasticity and Scalability in Cloud Computing**
- **Elasticity:** The ability of cloud computing resources to dynamically scale up or down based on demand, ensuring efficient resource utilization.
- **Scalability:** The capability to handle increasing workloads by adding more computing power (vertical scaling) or distributing the workload across multiple machines (horizontal scaling).

#### **(b) Comparison of Cloud Platforms**
- **AWS SageMaker:** Fully managed infrastructure for deep learning model training, automatic hyperparameter tuning, and easy deployment.
- **Google Vertex AI:** Offers built-in AutoML, supports TPUs, and provides an optimized environment for TensorFlow-based deep learning models.
- **Azure ML Studio:** Focuses on MLOps integration with Microsoft Azure services, provides a no-code model builder, and supports automated machine learning workflows.

---

### **2. Convolution Operations with Different Parameters**
- Implemented a **5×5 input matrix** and a **3×3 kernel**.
- Performed convolution operations with **different strides (1,2) and paddings (‘VALID’, ‘SAME’)**.
- Used **TensorFlow/Keras** for implementation.
- Printed the resulting **feature maps** for each configuration.

---

### **3. CNN Feature Extraction**
#### **(a) Edge Detection Using Sobel Filters**
- Applied **Sobel filters** using **OpenCV** to detect edges in both the x and y directions.
- Displayed the **original grayscale image** and the corresponding edge-detected images.

#### **(b) Max Pooling and Average Pooling**
- Created a **4×4 random matrix** as input.
- Applied **2×2 Max Pooling** and **2×2 Average Pooling** using **TensorFlow**.
- Printed the **original matrix**, the **max-pooled matrix**, and the **average-pooled matrix**.

---

### **4. Implementing and Comparing CNN Architectures**
#### **(a) AlexNet Implementation**
- Constructed a **simplified AlexNet model** using **TensorFlow/Keras**.
- Included multiple **Conv2D, MaxPooling, Fully Connected, and Dropout layers**.
- Printed the **model summary** to showcase the architecture.

#### **(b) Residual Block and ResNet-like Model**
- Implemented a **Residual Block** with **skip connections** to improve gradient flow.
- Built a **ResNet-like CNN model** with two residual blocks.
- Printed the **model summary** to visualize the network structure.


