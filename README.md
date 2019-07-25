

# KaggleCompetition01-GenerativeDogImages
In this competition, you’ll be training generative models to create images of dogs.

competition link:
https://www.kaggle.com/c/generative-dog-images

A generative adversarial network (GAN) is a class of machine learning system invented by Ian Goodfellow in 2014. Two neural networks compete with each other in a game. Given a training set, this technique learns to generate new data with the same statistics as the training set.

In this competition, you’ll be training generative models to create images of dogs. Only this time… there’s no ground truth data for you to predict. Here, you’ll submit the images and be scored based on how well those images are classified as dogs from pre-trained neural networks. 

Why dogs? We chose dogs because, well, who doesn’t love looking at photos of adorable pups? Moreover, dogs can be classified into many sub-categories (breed, color, size), making them ideal candidates for image generation.

Generative methods (in particular, GANs) are currently used in various places on Kaggle for data augmentation. Their potential is vast; they can learn to mimic any distribution of data across any domain: photographs, drawings, music, and prose. If successful, not only will you help advance the state of the art in generative image creation, but you’ll enable us to create more experiments across a variety of domains in the future.


MiFID

Submissions are evaluated on MiFID (Memorization-informed Fréchet Inception Distance), which is a modification from Fréchet Inception Distance (FID).

The smaller MiFID is, the better your generated images are.
