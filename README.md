# Explainable AI for Medical Imaging Models

This project focuses on 2-D Convolutional Neural Networks leveraging Grad-CAM(Grad Class Activation Mapping function) to increase the transparency of Machine Learning models used for medical imaging. Currently, many are skeptical of ML models in healthcare because of the black-box nature of models. However, with tools such as Grad-CAM, we can gain a clearer understanding of why a model is indicating a certain output. In our case, it would be to see what regions of a CT/MRI scan indicate whether a patient has COVID, Viral Pneumonia, or a normal diagnosis. This could aid doctors in potentially finding abnormalities/nuances to medical cases. 

Future scope ideas for this would be to deploy it as a larger-scale web application and train the model on a larger dataset.

Resources Used:
- https://www.kaggle.com/datasets/pranavraikokte/covid19-image-dataset
- https://www.ncbi.nlm.nih.gov/pmc/articles/PMC7413068/
- https://www.tensorflow.org/tutorials/images/cnn
