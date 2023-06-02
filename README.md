# Cacao Disease Detection Model
Indonesia is a significant player in the global cocoa industry, being ranked third in terms of cocoa production. However, the cocoa industry in Indonesia has been struggling with decreased productivity, which is attributed to various factors. According to Ariningsih (2021), one of the biggest reasons for the decreased cocoa productivity is the lack of proper plant maintenance, coupled with pest and disease outbreaks that have affected the crops. As a result, the country has experienced a decline in cocoa production for three consecutive years, with a projected decrease of 0.97% in 2021 compared to the previous year (BPS, 2021).

To address this issue, it is essential to find solutions that can help improve cocoa productivity, quality, and disease control in Indonesia's cocoa industry. One possible solution is the development of a machine learning model that can identify and classify cocoa diseases for quicker detection and better prevention and treatment methods. This model can provide insights on cocoa diseases, enabling better understanding, and effective prevention measures.

According to research, crop diseases are the leading cause of significant crop losses worldwide, including cocoa (Savary et al., 2019). Early detection and management of disease outbreaks are crucial to preventing yield losses and ensuring productivity. By developing a machine learning model that can quickly and accurately detect cocoa diseases, farmers can take necessary steps to manage and control the spread of the disease before it causes significant losses.

Furthermore, by identifying and classifying cocoa diseases through machine learning models, experts can gather more accurate and comprehensive data that can improve our broader understanding of these diseases. This knowledge can inform the development of better prevention and control measures and strategies that can help ensure the sustainability and growth of the cocoa industry.

In conclusion, the development of a machine learning model that can identify and classify cocoa diseases can significantly improve the situation in Indonesia's cocoa industry, where disease outbreaks are a significant problem. By enabling prompt disease detection and prevention measures, such models have the potential to increase cocoa productivity, improve cocoa quality, and enhance the livelihoods of cocoa farmers.


# The goal
The main objective of this model is to accurately predict cocoa diseases using images that the model has never encountered before. To achieve this, the dataset is first divided into three parts: the training set, the validation set, and the test set. The training and validation sets are used to train and validate the model, while the test set is used to evaluate the performance of the model on previously unseen data.

During the training phase, the model is presented with a large number of images, each with a label indicating the type of cocoa disease present. The model uses these images and labels to learn how to recognize and differentiate between different types of cocoa diseases. The validation set is used to monitor the progress of the model during training, and to prevent overfitting by identifying when the model begins to focus too much on the training data at the expense of generalization.

Once the model has been trained, it is tested on the previously unseen test set to evaluate its effectiveness in accurately predicting cocoa diseases. The accuracy of the model on the test set is a measure of its ability to generalize to new and previously unseen data, and is a critical metric for assessing the reliability of the model in real-world scenarios.

Overall, this model represents a promising approach to predicting cocoa diseases and has the potential to improve the efficiency and productivity of cocoa farming by identifying and addressing diseases before they cause significant harm to crops. 


# Dataset
The dataset I use for this model is varies, but i use three dataset : 
1. Cacao Diseases by ZALDY JR. PAGADUAN https://www.kaggle.com/datasets/zaldyjr/cacao-diseases
2. Cocoa Diseases (YOLOv4) by SEBASTIAN SERRANO and Juan Felipe Heredia Gómez https://www.kaggle.com/datasets/serranosebas/enfermedades-cacao-yolov4
3. The combination of those two dataset that I upload in this github

# Photo Samples
![121](https://github.com/FadhilahBagas17/Portofolio/assets/100406260/dfc0bbb6-eff3-46b2-b9fc-f9094f44e636)


# Result
After creating multiple models for cacao disease detection, the model 'cocoa_disease_5' demonstrated the highest accuracy rate of 0.93. In comparison to the other models with accuracy rates ranging from 0.75 to 0.87, this particular model is significantly more accurate in predicting cacao disease.


# Accuracy
![image](https://github.com/FadhilahBagas17/Portofolio/assets/100406260/c6d7e6d5-8f10-49d5-86a9-3d0d6a32cd8e)
