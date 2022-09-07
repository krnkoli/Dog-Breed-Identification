# Dog Breed Image Classifier

### 🐶 End-to-end Multil-class Dog Breed Classification

This notebook builds an end-to-end multi-class image classifier using TensorFlow 2.x and TensorFlow Hub.

**1. Problem**

Identifying the breed of a dog given an image of a dog.

When I'm sitting at the cafe and I take a photo of a dog, I want to know what breed of dog it is.

**2. Data**

The data we're using is from Kaggle's dog breed identification competition.

https://www.kaggle.com/c/dog-breed-identification/data

**3. Evaluation**
The evaluation is a file with prediction probabilities for each dog breed of each test image.

https://www.kaggle.com/c/dog-breed-identification/overview/evaluation

**4. Features**
Some information about the data:

We're dealing with images (unstructured data) so it's probably best we use deep learning/transfer learning.
There are 120 breeds of dogs (this means there are 120 different classes).
The list of breeds is as follows:

affenpinscher,
afghan_hound,
african_hunting_dog,
airedale,
american_staffordshire_terrier,
appenzeller,
australian_terrier,
basenji,
basset,
beagle, and many more.


There are around 10,000+ images in the training set (these images have labels).
There are around 10,000+ images in the test set (these images have no labels, because we'll want to predict them).


![Dawg Please 2](https://user-images.githubusercontent.com/100320688/188893741-9ca56476-b6f0-4c08-b326-8d2ce4fca0a5.png)
![Dawg Please 1](https://user-images.githubusercontent.com/100320688/188893157-6d9df6ab-3384-4baa-85dc-94bef541327e.png)

