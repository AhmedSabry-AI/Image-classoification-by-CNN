This project builds a deep learning-based image classifier using TensorFlow and Keras to distinguish chest X-ray images as Covid, Normal, or Viral Pneumonia. The dataset is loaded from Kaggle, and images are visualized and preprocessed using Matplotlib, OS, and Keras utilities, with pixel values rescaled via ImageDataGenerator.

The model uses the Sequential API, stacking three convolutional layers (filters: 32, 64, 128) with MaxPooling2D, followed by flattening and two dense layers. The final layer uses softmax for classification. It’s compiled with the Adam optimizer and categorical cross-entropy loss.

Trained over 5 epochs, the model reaches 98% accuracy on training data and around 83% on validation, with performance visualized through loss and accuracy plots. Evaluation on test data confirms good generalization. The model also predicts individual X-ray images and is saved as an .h5 file for deployment.

💡 Key Skills and Tools Demonstrated
Deep Learning with TensorFlow and Keras

CNN Architecture: Convolution, MaxPooling, Dense, Flatten layers

Image Preprocessing: Rescaling, reshaping, and batch loading with ImageDataGenerator

Data Visualization: matplotlib.pyplot

Model Evaluation: Accuracy, loss plots, evaluate() function

Model Deployment Preparation: Saving the trained model

Image Classification Pipeline: Loading, preprocessing, prediction, and visualization

This project showcases proficiency in building and evaluating image classifiers using deep learning, a key skill in the computer vision domain.






