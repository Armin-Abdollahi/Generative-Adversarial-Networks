# Generative-Adversarial-Networks
Generative Adversarial Networks (GAN)

![R](https://github.com/Armin-Abdollahi/Generative-Adversarial-Networks/assets/103449830/0088a9df-9a25-4c24-b2ee-1ca314338912)

Generative Adversarial Networks (GAN) is a class of machine learning framework that is used for generative AI. It was first introduced by Ian Goodfellow and his colleagues in June 2014. In GAN, two neural networks compete with each other in a zero-sum game, where one agent’s gain is another agent’s loss. The two agents are called the generator and the discriminator. The generator learns to generate new data with the same statistics as the training set, while the discriminator learns to distinguish between real and fake data.

GANs have been used for various applications such as image generation, video generation, text-to-image synthesis, and more. The core idea of a GAN is based on the “indirect” training through the discriminator, another neural network that can tell how “realistic” the input seems, which itself is also being updated dynamically. This means that the generator is not trained to minimize the distance to a specific image but rather to fool the discriminator. This enables the model to learn in an unsupervised manner.
