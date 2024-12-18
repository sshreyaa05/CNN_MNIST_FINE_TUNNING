## CNN Fine-Tuning for Handwritten Digit Classification Using the MNIST Dataset
## Objective:
To apply transfer learning by fine-tuning a pre-trained Convolutional Neural Network (CNN) model on the MNIST dataset to classify handwritten digits with improved accuracy.
## Data:
The MNIST dataset consists of 28x28 grayscale images representing digits from 0 to 9. It contains 60,000 training images and 10,000 test images. The dataset was preprocessed by resizing the images to match the input size of the pre-trained CNN and normalizing pixel values. A pre-trained model was utilized, and fine-tuning involved selectively training a few layers to adapt the model to MNIST classification. Before fine-tuning, the test accuracy of the pre-trained model was 0.9919. After fine-tuning, the test accuracy improved to 0.9925, demonstrating the effectiveness of the fine-tuning approach.
## Conclusion:
The fine-tuning of a pre-trained CNN on the MNIST dataset improved the test accuracy from 0.9919 to 0.9925, showcasing the advantages of transfer learning. This approach reduced computational cost and training time while achieving competitive performance in classifying handwritten digits.
