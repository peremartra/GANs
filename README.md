# GANs Tutorial
This is a brief introduction to Generative AI and GANs. Learn the principles of Generative AI undestanding how GANs work and their structure. 

The course takes us from the very basics of creating a GAN to building a small framework that facilitates the creation of more complex GANs capable of working with complex datasets.

If you want to get into the world of Generative AI and create your own models, understanding how GANs work and being able to create your own is essential. In just 4 chapters, we will explore a variety of ways to optimize our GANs, based on the famous GAN hacks by Soumith Chintala.

Each chapter is formed by a notebook and an article,  on TowardsAI, where I explain in more depth how the model was created.

## Creating our first optimized DCGAN.  

We create our first GAN, starting with a DCGAN. We use the MNIST dataset and focus on explaining how the GAN structure is formed and how the different models that compose it work.

* Notebook: [C1_GAN_Mnis1.ipynb](https://github.com/peremartra/GANs/blob/main/C1_GAN_MNIST1.ipynb).
* Article: https://pub.towardsai.net/creating-our-first-optimized-dcgan-12edde5e34c6

## How to make a GAN to generate color images. 

We switched to a new dataset to introduce color in the image generation process. We take advantage of this opportunity to introduce two functions that create the GAN structure depending on the parameters we pass to them. This way, we have a very fast way of creating GANs that can adapt to different problems. 

* Notebook: [C2_GAN_Cifar.ipynb].(https://github.com/peremartra/GANs/blob/main/C2_GAN_CIFAR.ipynb)
* Article: https://pub.towardsai.net/how-to-make-a-gan-to-generate-color-images-33d29f8a79c8

## How To Use TPUs in Kaggle / Google Colab To Train a GAN in the Blink of An Eye.

The complexity of the dataset used makes it necessary to accelerate the learning process. To achieve this, we use TPU, both on Google Colab and Kaggle, and parallel execution of the GAN code.
* Notebook: [C3_Faces_TPU.ipynb](https://github.com/peremartra/GANs/blob/main/C3_Faces_TPU.ipynb)
* Article: https://pub.towardsai.net/how-to-use-tpu-in-kaggle-google-colab-to-train-gan-in-the-blink-of-an-eye-328b78e3bc29

## A Beginner’s Guide to Building a Conditional GAN.

Time to create a conditional GAN that we can use to generate images of a certain type. To achieve this, we must create a non-sequential model, using the Keras functional API.
* Notebook: [C4_COND_GAN_MNIST.ipynb](https://github.com/peremartra/GANs/blob/main/C4_COND_GAN_MNIST.ipynb)
* Article: https://medium.com/towards-artificial-intelligence/a-beginners-guide-to-building-a-conditional-gan-d261e4d94882

The course is set up so that each notebook is more complicated and builds on the knowledge you've already learned.

I hope you enjoy it!
