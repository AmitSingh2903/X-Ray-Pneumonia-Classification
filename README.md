Project Title: X-ray Image Classification for Pneumonia and COVID Detection Using Deep Learning Methods

Project Description:

In this project, we aimed to develop a deep learning model for accurately classifying X-ray images as either pneumonia or COVID cases. 
The objective was to compare accuracy of different types of CNN, where we used two:; DenseNet and MobileNetV2 and acheived an accuracy of something close to 54.5% and later using feature scaling we were able to get something close to 85%.

To begin, we collected a dataset consisting of X-ray images from pneumonia and COVID cases. The dataset was preprocessed to ensure uniformity in size and format. We split the dataset into training and testing sets, preserving class distribution in each subset.

Initially, we trained the CNN models without feature scaling and obtained an accuracy of 54.44%. Recognizing the need for further improvement, we incorporated feature scaling techniques to enhance the performance of the models. Feature scaling helps to normalize the input data, making it more suitable for the learning process.

After applying feature scaling, we retrained the models using the updated datasets. The DenseNet CNN model achieved an impressive accuracy of 83.54%, showcasing a substantial improvement from the initial baseline. Additionally, we employed the MobileNetV2 architecture as an alternative approach to validate the results.

The combination of feature scaling and the utilization of advanced CNN architectures led to significant advancements in the accuracy of pneumonia and COVID detection from X-ray images. Our project demonstrates the efficacy of deep learning techniques in medical image analysis, specifically for the identification of respiratory diseases from X-ray scans.

Future work may involve exploring other preprocessing techniques, incorporating transfer learning, or applying ensemble methods to further enhance the model's performance and generalization capabilities. The developed model holds the potential for assisting medical professionals in early and accurate detection of pneumonia and COVID cases, contributing to improved patient care and decision-making.

Dataset Title: Chest X-ray Images for Pneumonia and COVID Classification

Data Description:

The dataset available at [insert URL: https://dataverse.harvard.edu/dataset.xhtml?persistentId=doi:10.7910/DVN/WNQ3GI] is a comprehensive collection of chest X-ray images specifically curated for pneumonia and COVID classification. The dataset serves as a valuable resource for researchers and practitioners working in the field of medical image analysis and deep learning.

The dataset consists of a diverse set of chest X-ray images acquired from multiple sources, encompassing various demographics, age groups, and geographical regions. The images were captured using digital radiography and stored in high-resolution formats, ensuring accurate representation of pathological conditions related to pneumonia and COVID.

Key Features of the Dataset:

-Data Format: The dataset comprises a collection of grayscale or RGB images in commonly used image file formats, such as JPEG or PNG.

-Image Labels: Each image in the dataset is annotated with binary labels indicating the presence or absence of pneumonia and COVID. The labels provide crucial information for training classification models.

-Class Distribution: The dataset maintains a balanced distribution between pneumonia and COVID cases, enabling effective training and evaluation of classification models.

-Metadata: Alongside the images, the dataset may include additional metadata, such as patient information (e.g., age, gender) and clinical findings, providing supplementary context for research and analysis.
Data Organization: The dataset is typically organized into subdirectories based on different categories, facilitating easy navigation and retrieval of images for specific research purposes.

Potential Use Cases:
The dataset can be employed for various tasks related to pneumonia and COVID classification, including but not limited to:

-Training and evaluating deep learning models for automatic detection of pneumonia and COVID cases from chest X-ray images.
-Conducting comparative studies between different deep learning architectures for pneumonia and COVID classification.
-Investigating the impact of various preprocessing techniques, feature extraction methods, or data augmentation strategies on model performance.
-Exploring the interpretability of deep learning models through visualization and saliency mapping techniques to identify key features associated with pneumonia and COVID.

Accessing and Citing the Dataset:
Researchers interested in utilizing this dataset can access it through the provided URL [insert URL: https://dataverse.harvard.edu/dataset.xhtml?persistentId=doi:10.7910/DVN/WNQ3GI]. When using this dataset in publications or research work, it is essential to properly acknowledge and cite the dataset using the appropriate citation provided by the dataset creators or the hosting platform.
