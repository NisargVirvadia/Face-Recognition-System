# Face-Recognition-System
Facial Recognition System using Machine Learning and Deep Learning

Our project's main goal was to accurately predict images from a dataset containing various student profiles, each assigned different class labels. To accomplish this task, we explored two different approaches, ultimately achieving a perfect 100% accuracy rate with Track 2.

In Track 1, we used traditional machine learning algorithms to handle the image prediction task. This meant applying classic techniques and methodologies from the field of machine learning to analyze and categorize the images based on their unique features and attributes.

On the flip side, Track 2 involved delving into the world of deep learning for image prediction. Here, we utilized cutting-edge neural network architectures and advanced techniques to train models capable of recognizing complex patterns and representations within the images, ultimately leading to highly precise predictions.

After thorough experimentation and evaluation, we discovered that Track 2, which leveraged deep learning methods, outperformed Track 1. This underscores the effectiveness and potential of deep learning approaches in tackling intricate image classification tasks.

Instructions to run the code-

provide the root path in the code as shown below-

root_path = "/content/drive/MyDrive/Colab Notebooks/COEN240_TA/data"
train_path = root_path + "/train"
grade_path = root_path + "/grade"


Summary-
1)After initial trials with various machine learning algorithms like KNN,SVM,Random Forest resulted in less accuracy, we shifted project towards a deep learning-based approach.
2)We switched to a deep learning approach.. We managed our data using Pytorch's dataset and dataloader. Then, we combined the VGGFace pre-trained model with an SVM classifier, simplifying feature extraction and training while leveraging existing feature representations
3)We serialized the trained model with Pickle for easy deployment and consistency across platforms.
4)GPU acceleration significantly speed up the training, enabling quick iterations and faster model convergence. We developed an API for efficient model inference, handling input data, feature extraction, prediction, and matching with filenames seamlessly for high accuracy throughout the process.


