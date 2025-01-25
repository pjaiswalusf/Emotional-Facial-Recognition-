Project Description

This project focuses on building a deep learning-based Emotion Recognition System utilizing Transfer Learning with ResNet50 as the base model. The system classifies facial expressions into 8 emotion categories, including happiness, sadness, anger, surprise, fear, contempt, disgust, and neutrality.

Key highlights of the project include:
• Dataset Preprocessing:
	• Cleaned and visualized demographic data (age, gender, and country).
	• Processed and standardized a dataset of 152 images for emotion classification, expanded to 7752 samples using data augmentation techniques.
• Model Architecture:
	• Leveraged the ResNet50 pre-trained model for feature extraction.
	• Added fully connected layers for classification, including dropout for regularization.
	• Achieved a test accuracy of 95.6%.
• Training Process:
	• Implemented Early Stopping and Learning Rate Reduction for optimal training performance.
	• Achieved robust validation metrics with high precision, recall, and F1-scores across all emotion categories.
• Evaluation:
	• Confusion matrix and classification reports demonstrate model performance.
	• Plotted training and validation accuracy/loss curves to track progress.
• Deployment Preparation:
	• Developed inference pipelines to classify real-time images and visualize predictions.

This project demonstrates the power of transfer learning and data augmentation in enhancing model performance on small datasets. Explore the repository to view detailed code, visualizations, and results.