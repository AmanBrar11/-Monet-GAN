# Monet Painting Generative Adversarial Network (GAN)

## Project Overview
This project explores building a Generative Adversarial Network (GAN) to transform real-life photos into artworks resembling Monet's paintings. With a dataset of 300 Monet paintings and 7038 real-world photos, the aim was to delve into the rapidly evolving field of GANs and understand their capability in art generation.

## Data
The data comprises 256x256 pixel images, split into two main categories: Monet paintings and real-world photos. The Monet dataset serves as the style target for the GAN, while the photos are used as the input to be transformed.

## Process
The project involved the construction of a GAN with a modified U-Net architecture for the generator and a separate discriminator model. The training process used adversarial loss functions and the Adam optimizer to iteratively enhance the generator's output. This process was conducted over multiple epochs, refining the model to better mimic Monet's style.

## Results and Conclusion
The final model achieved notable results, with the transformed images showcasing characteristics reminiscent of Monet's work, especially in their color palettes. Achieving a rank of 77 on the Kaggle leaderboard, this project provided valuable insights into GANs and their application in art generation, indicating potential areas for further improvement and exploration.

## Usage
To replicate the results, ensure to install the required packages, load the datasets, and follow the steps outlined in the training section. The `generate_images` function can be used to visualize the transformation of input photos into Monet-like paintings.
