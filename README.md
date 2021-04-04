# Pneumonia Detection from Chest-Xray Images
Udacity project for AI in Healthcare - Data from Kaggle

## Project Overview: 

In this project, data will be analyzed from the NIH Chest X-ray Dataset and a CNN will be trained to classify a given chest x-ray for the presence or absence of pneumonia. This project will culminate in a model that can predict the presence of pneumonia with human radiologist-level accuracy that can be prepared for submission to the FDA for 510(k) clearance as software as a medical device. The model will be formally described, as well as the data that it was trained on, and the validation plan that meets FDA criteria.

The medical images with clinical labels for each image that were extracted from their accompanying radiology reports are also provided.

There are in total 112,000 chest x-rays with disease labels acquired from 30,000 patients.

## Project Highlight

This project GIVES hands-on experience with 2D medical imaging data analysis and preparation of a medical imaging model for regulatory approval.

Upon completion of this project, you would be able to:

* recommend appropriate imaging modalities for common clinical applications of 2D medical imaging
* perform exploratory data analysis (EDA) on medical imaging data to inform model training and explain model performance
* establish the appropriate ‘ground truth’ methodologies for training algorithms to label medical images
* extract images from a DICOM dataset
* train common CNN architectures to classify 2D medical images
* translate outputs of medical imaging models for use by a clinician
* plan necessary validations to prepare a medical imaging model for regulatory approval

The files contained in this repository are the following:

* EDA.ipynb: This is the file to perform the EDA.
* Build and train model.ipynb: This is the file used to build and train the model.
* Inference.ipynb: This is the file for performing clinical workflow integration.
* .dcm files: They are the test files to test the clinical workflow integration.
* sample_labels.csv: This is the file that should be used to assess images in the pixel-level.
* FDA_Submission_Template.md: This is the template to create the FDA submission. Please copy the template into your choice of editor.

For this project it is strongly encouraged the use of GPUs to accelerate the training process.

The paper used is: https://arxiv.org/pdf/1711.05225.pdf

The link to the data is: ht