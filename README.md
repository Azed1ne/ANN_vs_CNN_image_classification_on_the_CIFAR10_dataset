# Image classification on the CIFAR-10 dataset
In this notebook, which is like an introduction to Deep Learning, I trained an ANN and a couple of CNN models to classify images of the **CIFAR-10**  dataset and compared their results.

The best CNN model I got on 10 epochs: 

- 83.60 % accuracy on the training set (50k images)
  
- **74.30 % accuracy** on average on the test set (10k images)

Meanwhile, the ANN model gave me about **52 % accuracy**.

**Conclusion:** CNN is better than ANN in image classification, which is a known fact.

## About the dataset
**CIFAR-10**  is an established computer-vision dataset used for object recognition. 
It is a subset of the 80 million tiny images dataset and consists of 60,000 32x32 colour images containing one of 10 object classes, with 6000 images per class. It was collected by Alex Krizhevsky, Vinod Nair, and Geoffrey Hinton.

This is how the images look like:

![image](https://github.com/Azed1ne/ANN_vs_CNN_image_classification_on_the_CIFAR10_dataset/assets/123888749/8bdbc3b8-b6c0-4517-9789-0cd0800ba316)

You can read more about it [here](https://www.cs.toronto.edu/~kriz/cifar.html)
