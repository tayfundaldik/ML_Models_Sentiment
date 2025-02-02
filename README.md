# 📌 Comparing Machine Learning Models for Sentiment Analysis  

## 🎯 Project Overview  
This project explores sentiment analysis on the **Kaggle 50K IMDb dataset**, comparing **traditional machine learning models** and **deep learning models**. The key goal is to analyze their performance across different dataset sizes.  

## 🛠️ Models Used  
### Traditional Machine Learning  
- Naïve Bayes  
- Support Vector Machine (SVM)  

### Deep Learning  
- Recurrent Neural Networks (RNN)  
- Convolutional Neural Networks (CNN)  
- Bidirectional Encoder Representations from Transformers (BERT)  

## 📊 Key Findings  
- **On 5,000 examples**: All models performed similarly (~93-95% accuracy).  
- **On 10,000 examples**: Deep learning models, especially **BERT**, started outperforming traditional ML methods.  
- **Conclusion**: **Traditional ML models work well for small datasets**, while deep learning is superior for larger datasets.  

## 🔄 Data Augmentation  
To improve model performance and handle data limitations, I **augmented 75% of the dataset** using techniques such as:  
- **Synonym replacement**   
- **Random word insertion and deletion**  

This helped increase data diversity and improve generalization.  

## 🔮 Future Work  
- Testing models on **larger datasets** to further analyze performance scaling.  
- Experimenting with **hyperparameter tuning** and **data augmentation** improvements.  
- Due to **hardware limitations**, larger experiments are currently postponed. 😅  

## Dataset
- Link:https://www.kaggle.com/datasets/lakshmi25npathi/imdb-dataset-of-50k-movie-reviews
