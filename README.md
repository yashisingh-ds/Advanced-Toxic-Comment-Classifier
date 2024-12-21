

# Advanced-Toxic-Comment-Classifier

📜 **Project Description**
 
The Toxic Comment Classifier is an Advanced machine-learning project developed to detect and categorize toxic content in user comments. By employing a multi-label classification strategy, it addresses the critical challenges faced by online platforms in identifying harmful language. Designed and implemented in a Jupyter Notebook environment, the project utilizes cutting-edge techniques for feature extraction and classification.
This advanced solution is deployed for real-time toxic comment detection, leveraging Convolutional Neural Networks (CNNs) and a Kaggle dataset to achieve an impressive accuracy of 95.31%. The workflow encompasses comprehensive preprocessing, feature extraction, and detailed evaluation, enabling effective identification of hate speech, harassment, and offensive language.

🎯**Objectives**

Build a robust classifier to accurately identify toxic comments across six predefined categories:
- **Toxic**  
- **Severe Toxic** 
- **Obscene**  
- **Threat**  
- **Insult**  
- **Identity Hate**
Applying advanced preprocessing techniques and machine learning techniques  to ensure high accuracy. Additionally, analyze and provide insights into the patterns and distribution of toxic content within the dataset.

🛠️ Tools and Technologies
- **Programming Language:** Python  
- **Development Environment:** Jupyter Notebook  
- **Libraries:** Pandas, NumPy, Matplotlib, Seaborn, Scikit-learn, TensorFlow  
- **Visualization Tools:** Matplotlib and Seaborn for in-depth exploratory data analysis (EDA).  

**🚀 Methodology**
The model was built using **Convolutional Neural Networks (CNN)** to detect toxic comments across six categories.  
- **Data Preprocessing**: Text was cleaned, tokenized, and padded to ensure uniform input for the CNN model.  
- **Feature Extraction**: An embedding layer was used to represent words as dense vectors, capturing semantic relationships.  
- **Model Architecture**: The CNN model consists of convolutional layers to extract features, followed by max-pooling for dimensionality reduction and a fully connected layer for classification.  
- **Training**: The model was trained using the **Adam optimizer** and **categorical cross-entropy** loss function.  
- **Evaluation**: The model achieved **95.31% accuracy** with additional metrics like precision, recall, and F1-score for balanced performance across all categories.

📈**Results**
The model’s performance was evaluated using multiple metrics to ensure high accuracy and reliability in detecting toxic comments across six categories. The key evaluation metrics are as follows:
- **Accuracy:** 95.31%
- **Precision:** 95.08%
- **Recall:** 95.31%
- **F1-Score:** 94.92%
  
**Confusion Matrix**
A Confusion Matrix was created to visually represent the model’s performance in classifying the toxic comments. The matrix shows how well the model distinguishes between the six predefined categories: Toxic, Severe Toxic, Obscene, Threat, Insult, and Identity Hate.
 ![Confusion Matrix](images/confusionmatrix.png)


