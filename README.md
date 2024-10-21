# Fashion-MNIST

**Problem**: This is a multi-class classification problem where classes 0 to 9 correspond to different types of fashion items: T-shirt/top, trousers, pullovers, dresses, coats, sandals, shirts, sneakers, bags, and ankle boots, respectively. The goal is to identify the optimal model for categorizing these items by comparing the performance of two different approaches.

---

### Solution Methods:

We applied two main approaches: a neural network-based solution (ANN and CNN models using TensorFlow Keras) and a hybrid approach combining CNN and a Vision Transformer using the PyTorch framework.

---

### **1. ANN and CNN Approaches (TensorFlow Keras)**

In this first approach, we utilized **Artificial Neural Networks (ANN)** and **Convolutional Neural Networks (CNN)** to solve the classification problem. Both models were built and trained using the TensorFlow Keras library. Below are the flowcharts representing these models, followed by their respective classification reports:

- **ANN Model Flowchart:**

   ![ANN Model](https://github.com/user-attachments/assets/1e1676e0-f787-42bb-ae23-eb58933f4782)

- **CNN Model Flowchart:**

   ![CNN Model](https://github.com/user-attachments/assets/9b87e38d-59bb-4410-b9bf-e0761a7e4db0)

---

### **2. Hybrid Approach: Compact Convolutional Transformer (CNN + Vision Transformer)**

For the second approach, we implemented a **Compact Convolutional Transformer (CCT)**, which combines a CNN with a Vision Transformer to further improve the precision of classification. Also one of the main takeaways from CCT model is that it works fantastic on small dataset wherease ViT works best in a much more larger dataset. This hybrid model was built using the PyTorch framework. Below is the flowchart of the CCT model:

- **CCT Model Flowchart:**

   ![CCT Model](https://github.com/user-attachments/assets/3b4033ba-9f6e-4560-bde4-0a51fc1000da)

---

In conclusion, the goal is to compare the performance of these models and identify which one performs best in the classification task.

---
