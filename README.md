# Face-Anonymization
Face Detection and Anoymization in Images using MTCNN model

Face recognition techniques improves at a steady rate with the recent deep learning technique developed and the access to large training dataset made available in the Internet. This project aims to be able to detect faces in images and apply censorship as an anonymization feature for privacy using deep learning. The deep learning that is used is Multi-task Cascaded Convolutional Neural Network (MTCNN), which contains three sub-networks together to learn to recognize human faces after several stages of decomposition and filtering.

Objective 1: To be able to detect faces in images.
Objective 2: To apply blur to the detected faces to anonymize it.

As we are using a pre-trained model, this project only needs to prepare the dataset to put into the model and evaluate it. The main flow of this project is
1. Performing face detection using the model
2. Extract face region of interest (ROI)
3. Apply blur to ROI and
4. Paste blurred ROI to original image.
