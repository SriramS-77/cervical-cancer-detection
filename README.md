# 🧬 Cervical Cancer Detection
Leukemia Cell Classification in Pap Smear Images Using Traditional Computer Vision & Deep Learning Techniques

## 📌 Overview
This project focuses on the automated detection of leukemia cells in cervical pap smear images using a blend of traditional computer vision techniques and deep learning models. It presents a comparative analysis of multiple preprocessing, feature extraction, and classification approaches to assess their impact on detection accuracy.

## 🧪 Dataset
**Dataset Used:** [Sipakmed](https://www.kaggle.com/datasets/prahladmehandiratta/cervical-cancer-largest-dataset-sipakmed)

Contains high-resolution images of single-cell pap smear slides used for classification.

## ⚙️ Preprocessing Techniques
- **Otsu's Thresholding**
- **Watershed Segmentation**

These strategies were tested to evaluate their effect on downstream classification performance.

## 🔍 Feature Extraction Methods
Five traditional feature extraction techniques were employed:

- **Histogram of Oriented Gradients (HOG)**
- **Scale-Invariant Feature Transform (SIFT)**
- **Local Binary Patterns (LBP)**
- **Oriented FAST and Rotated BRIEF (ORB)**
- **Gabor Filters**

## 🤖 Classification Models
Extracted features were fed into the following machine learning models:

- **Logistic Regression**
- **Random Forest**
- **Support Vector Machine (SVM)**
- **K-Nearest Neighbors (KNN)**

## 🧠 Deep Learning Models
To compare with traditional techniques, raw images were also classified using:

- **AlexNet**
- **VGG19**
- **ResNet**

## 📊 Evaluation Metrics
- **Accuracy**
- **Precision / Recall / F1-score**
- **Confusion Matrices**

All models were evaluated based on the metrics above to highlight performance strengths and weaknesses.

## 🔍 Key Findings
- Preprocessing significantly influences classification performance.
- Traditional feature extraction techniques still offer competitive accuracy.
- Deep learning models outperform in terms of generalization but require more data and compute.

## 📚 References
- [Sipakmed Dataset](https://www.kaggle.com/datasets/prahladmehandiratta/cervical-cancer-largest-dataset-sipakmed)
- [González, Rafael C., and Richard E. Woods. Digital Image Processing](https://books.google.co.in/books?hl=en&lr=&id=a62xQ2r_f8wC&oi=fnd&pg=PA19&dq=Gonz%C3%A1lez,+Rafael+C.,+and+Richard+E.+Woods.+Digital+Image+Processing&ots=3B3wS2kL1H&sig=JB_JUPaBGLH0MoPIpJN09gzPh6U&redir_esc=y#v=onepage&q=Gonz%C3%A1lez%2C%20Rafael%20C.%2C%20and%20Richard%20E.%20Woods.%20Digital%20Image%20Processing&f=false)
- [Simonyan, Karen, and Andrew Zisserman. Very Deep Convolutional Networks for Large-Scale Image Recognition](https://arxiv.org/abs/1409.1556)
- [M. E. Plissiti, A. Dimitrakopoulou-Strauss, and A. Charchanti,
”SIPaKMeD: A new dataset for feature and image based classification
of normal and pathological cervical cells in Pap smear images,” IEEE
Transactions on Medical Imaging , vol. 37, no. 3, pp. 799–805, Mar.
2018](https://ieeexplore.ieee.org/document/8451588)
- [R. Baig, J. Muhammad, S. Rasheed, et al., ”Detecting malignant
leukemia cells using microscopic blood smear images: a deep learning
approach,” Applied Sciences , vol. 12, no. 13, p. 6317, 2022](https://onlinelibrary.wiley.com/doi/full/10.1155/2021/9933481)
