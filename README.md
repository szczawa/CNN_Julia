# CNN_Julia
A convolution neural network that does not use libraries with ready-made solutions. Polish comments on code.

## Features

- **Customizable CNN Architecture**: Modify layers and parameters as needed.
- **Training and Evaluation**: End-to-end training and evaluation workflow in Julia.
- **Data Preprocessing**: Image transformations and data augmentation options.
- **Metrics Tracking**: Monitor training loss and accuracy metrics for insights into model performance.

## Basic Theory

### Convolutional Neural Networks (CNNs)

CNNs are specialized neural networks particularly effective for image-related tasks. They use convolutional layers to automatically learn spatial hierarchies of features from input images. Key concepts in CNNs include:

- **Convolution Layers**: Apply filters (kernels) across the image to detect various features such as edges, textures, and shapes.
- **Pooling Layers**: Downsample feature maps to reduce spatial dimensions, which helps in lowering computational complexity and capturing important patterns.
- **Fully Connected Layers**: Often used towards the end of the network to combine all learned features for final classification.

### Training Process

Training a CNN involves several steps:

1. **Forward Pass**: Input images pass through the network, layer by layer, to produce predictions.
2. **Loss Calculation**: The difference between predictions and actual labels is calculated, typically using a loss function like cross-entropy.
3. **Backpropagation**: The loss is propagated backward through the network, adjusting weights to minimize errors.
4. **Optimization**: Techniques like gradient descent are used to update weights iteratively, improving the model’s accuracy.

CNNs learn through numerous training epochs, where they iteratively adjust weights to minimize errors. This training process enables CNNs to generalize and classify unseen data accurately.

