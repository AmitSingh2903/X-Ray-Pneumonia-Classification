Project Title: X-ray Image Classification for Pneumonia and COVID Detection Using Deep Learning Methods

Project Description:

In this project, we aimed to develop a deep learning model for accurately classifying X-ray images as either pneumonia or COVID cases. 
The objective was to improve the initial model's performance of 54.44% accuracy and achieve significant enhancement through the implementation of feature scaling techniques.
We employed two state-of-the-art convolutional neural network (CNN) architectures, namely DenseNet and MobileNetV2, to accomplish this task.

To begin, we collected a dataset consisting of X-ray images from pneumonia and COVID cases. The dataset was preprocessed to ensure uniformity in size and format. We split the dataset into training and testing sets, preserving class distribution in each subset.

Initially, we trained the CNN models without feature scaling and obtained an accuracy of 54.44%. Recognizing the need for further improvement, we incorporated feature scaling techniques to enhance the performance of the models. Feature scaling helps to normalize the input data, making it more suitable for the learning process.

After applying feature scaling, we retrained the models using the updated datasets. The DenseNet CNN model achieved an impressive accuracy of 83.54%, showcasing a substantial improvement from the initial baseline. Additionally, we employed the MobileNetV2 architecture as an alternative approach to validate the results.

The combination of feature scaling and the utilization of advanced CNN architectures led to significant advancements in the accuracy of pneumonia and COVID detection from X-ray images. Our project demonstrates the efficacy of deep learning techniques in medical image analysis, specifically for the identification of respiratory diseases from X-ray scans.

Future work may involve exploring other preprocessing techniques, incorporating transfer learning, or applying ensemble methods to further enhance the model's performance and generalization capabilities. The developed model holds the potential for assisting medical professionals in early and accurate detection of pneumonia and COVID cases, contributing to improved patient care and decision-making.
