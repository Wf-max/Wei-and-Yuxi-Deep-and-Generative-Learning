# Medical Image Classification for Disease Detection Using Neural Networks
# Abstract
This project aims to develop a deep learning model for medical image classification to assist in disease detection. Using a dataset of medical images, such as chest X-rays or histology slides, the project will train a convolutional neural network (CNN) to classify images into different categories (e.g., detecting pneumonia or identifying cancerous cells). The model will be trained using supervised learning techniques, leveraging labeled medical datasets to improve accuracy.The primary objective is to explore the potential of deep learning in automating medical diagnosis, reducing human error, and improving early disease detection. The final deliverable will include a trained model, performance evaluation metrics, and a report detailing the methodology and findings.
# Data Source
This dataset consists of 704 chest X-ray images that have been curated from two sources: the Montgomery County Chest X-ray Database (USA) and the Shenzhen Chest X-ray Database (China). The images are used for training and evaluating machine learning models for tuberculosis (TB) detection.The dataset contains both tuberculosis-positive and normal chest X-rays, along with demographic details such as gender, age, and county of origin. The images are accompanied by lung segmentation masks and clinical metadata, which makes the dataset highly suitable for deep learning applications in medical imaging.
# A list of packages required
- Python 3.8+
- PyTorch
- torchvision
- pandas
- scikit-learn
- matplotlib
- Pillow
# Summary
The goal of this project is to develop a deep learning model to detect tuberculosis (TB) from chest X-ray images.TB is a serious infectious disease that affects the lungs, and early detection is crucial for treatment and prevention.Traditional diagnosis methods can be time-consuming and require expert radiologists.This project aims to provide an automated solution that can assist in identifying TB using image processing and machine learning techniques.To achieve this, a convolutional neural network (CNN) model is trained on a dataset of chest X-ray images labeled as either "Normal" or "TB Positive."The images are preprocessed by converting them to grayscale, resizing them, and normalizing pixel values.The CNN architecture consists of multiple convolutional layers, max pooling, and dense layers to extract features and classify the images.The model is trained and evaluated, achieving an accuracy of 80% on test data.This system can support medical professionals by providing quick and reliable preliminary TB detection, reducing the burden on healthcare facilities.Future improvements may involve optimizing the model with more data, fine-tuning hyperparameters, and integrating it into a practical diagnostic tool for clinical use.
