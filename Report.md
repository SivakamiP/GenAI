# GenAI
## Project Aim
The objective of this project was to develop a Deep Convolutional Generative Adversarial Network (DCGAN) for generating high-quality, realistic anime face images. The project leveraged advanced deep learning techniques to explore the potential of Generative Adversarial Networks (GANs) in image synthesis. The primary goals included:

### 1. Dataset Preparation: 
- Using an existing dataset of anime face images, preprocess the data to ensure suitability for GAN training. This involved resizing images, normalizing pixel values, and augmenting the dataset to improve training stability.
### 2. Model Development: Designing and implementing:
- A Generator to create synthetic anime images from random noise.
- A Discriminator to differentiate between real and generated images.
### 3. Training the GAN: 
- Using the adversarial learning paradigm, train the generator and discriminator iteratively, improving the realism of generated images while challenging the discriminator’s ability to distinguish between real and fake images.
### 4. Evaluation:
- Visualize and assess the quality of the generated images, monitor generator and discriminator losses, and analyze training progression over multiple epochs.

## Project Results
### 1. Dataset Preparation:
- The anime dataset was successfully preprocessed. Images were resized to 64x64 pixels and normalized to fall within the range [0, 1].
- Data augmentation techniques, such as random flipping and rotation, were applied to increase dataset diversity.

### 2. Model Architecture:
- The Generator progressively transformed random noise into detailed, 64x64 anime face images using transposed convolutional layers.
- The Discriminat+or effectively classified real and fake images through a series of convolutional and pooling layers with LeakyReLU activations.

### 3. Training:
- The DCGAN was trained over 30 epochs with a batch size of 32.
- Both generator and discriminator loss trends were monitored to ensure adversarial balance and stable convergence.

### 4. Image Generation:
- By the end of training, the generator produced visually appealing anime faces with realistic features such as well-structured eyes, hair, and facial contours.
- A grid of 36 synthetic images was visualized, showcasing the generator's ability to create diverse anime faces from random noise.

### 5. Performance Metrics:
- Loss curves indicated effective learning, with generator loss decreasing as the discriminator’s ability to distinguish real from fake improved.
- The model captured intricate features of anime faces while maintaining diversity across generated images.
