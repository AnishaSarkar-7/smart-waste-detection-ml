# Smart Waste Identification and Segregation System

## 📌 Project Overview
This project focuses on classifying waste using deep learning techniques. The goal is to identify different categories of waste from images and demonstrate how machine learning can support waste management and sustainability initiatives.

The project was developed as a **model-based deep learning system** using Google Colab.



## 🧠 Models Used
The following models were trained and evaluated:

- Convolutional Neural Network (CNN)
- ResNet50
- VGG-16
- DenseNet121

To improve prediction reliability, a **hybrid ensemble model** was built using **majority voting**, which combines predictions from all individual models.



## ⚙️ Methodology
- Image preprocessing and resizing
- Training individual deep learning models
- Comparing model performance
- Building a hybrid ensemble using majority voting
- Evaluating results using standard classification metrics



## 📊 Performance
The hybrid ensemble model achieved an accuracy of **96.91%** on the validation dataset.

Model evaluation was performed using:
- Accuracy
- Precision
- Recall
- Confusion Matrix

The ensemble model showed more stable performance compared to individual models.



## 🛠 Technologies Used
- Python  
- TensorFlow / Keras  
- NumPy  
- scikit-learn  
- OpenCV 
- Google Colab  



## 📁 Project Type
Model-based Deep Learning Project (Notebook implementation)



## 🚀 How to Run
1. Clone or download the repository  
2. Install required dependencies using `requirements.txt`  
3. Open the notebook in Jupyter Notebook or Google Colab  
4. Run the cells step by step  



## 📌 Note
This project is developed for academic and learning purposes.  
The results are based on the dataset used and are not claimed as real-world deployment performance.
