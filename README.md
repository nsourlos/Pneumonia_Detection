# pneumonia_detection
Udacity pneumonia detection from Chest-Xray Images - Data from Kaggle

Project Overview: 

In this project, you will apply the skills that you have acquired in this 2D medical imaging course to analyze data from the NIH Chest X-ray Dataset and train a CNN to classify a given chest x-ray for the presence or absence of pneumonia. This project will culminate in a model that can predict the presence of pneumonia with human radiologist-level accuracy that can be prepared for submission to the FDA for 510(k) clearance as software as a medical device. As part of the submission preparation, you will formally describe your model, the data that it was trained on, and a validation plan that meets FDA criteria.

You will be provided with the medical images with clinical labels for each image that were extracted from their accompanying radiology reports.

The project will include access to a GPU for fast training of deep learning architecture, as well as access to 112,000 chest x-rays with disease labels acquired from 30,000 patients.

Project Highlight

This project is designed to give you hands-on experience with 2D medical imaging data analysis and preparation of a medical imaging model for regulatory approval.
Upon completion of this project, you would be able to:
•	recommend appropriate imaging modalities for common clinical applications of 2D medical imaging
•	perform exploratory data analysis (EDA) on medical imaging data to inform model training and explain model performance
•	establish the appropriate ‘ground truth’ methodologies for training algorithms to label medical images
•	extract images from a DICOM dataset
•	train common CNN architectures to classify 2D medical images
•	translate outputs of medical imaging models for use by a clinician
•	plan necessary validations to prepare a medical imaging model for regulatory approval


This workspace contains:
•	EDA.ipynb: This is the file you will be performing the EDA.
•	Build and train model.ipynb: This is the file you will be building and training your model.
•	Inference.ipynb: This is the file you will be performing clinical workflow integration.
•	.dcm files: They are the test files to test the clinical workflow integration.
•	sample_labels.csv: This is the file that should be used to assess images in the pixel-level.
•	FDA_Submission_Template.md: This is the template for you to create the FDA submission. Please copy the template into your choice of editor. Finish the documentation, save it as a .pdf file, and upload.

You can download the data from the kaggle website and run it locally. You are STRONGLY recommended to complete the project using the Udacity workspace since the data is huge, and you will need GPU to accelerate the training process.

The paper used is: https://arxiv.org/pdf/1711.05225.pdf

The link to the data is: https://www.kaggle.com/nih-chest-xrays/data

