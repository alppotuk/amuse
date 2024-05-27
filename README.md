# AMUSE - A Variational Autoencoder Conditioned Music Generating Diffusion Model

This repository contains the code and notebooks for training and testing a Variational Autoencoder (VAE) and a conditioned diffusion model. This project aims to generate music tracks based on input playlists by extracting the "taste" from the playlists. Please keep in mind that this is my graduation project and it is **still under construction**. I will be updating the dataset, model structures and also some output samples.

## Notebooks

1. **VAE Training and Tests**

   - This notebook contains the code for training the Variational Autoencoder (VAE) model and some tests to evaluate its performance.

2. **VAE Conditioned Diffusion Model Training**

   - This notebook includes the training process for the diffusion model conditioned on the VAE's latent space representation.

3. **Final Model Parameter Testing**
   - This notebook focuses on testing the final model parameters to ensure the quality and performance of the generated music tracks.

## Model Repository

The trained models can be found on Hugging Face:
[Variational Autoencoder Conditioned Diffusion Model v2](https://huggingface.co/alppo/vae-conditioned-diffusion-model_v2)

## Project Overview

The main goal of this project is to use deep learning techniques to produce new music tracks that align with the preferences of given input playlists. The project involves:

- **Variational Autoencoder (VAE)**: A neural network that learns a compressed latent space representation of the input data, in this case, mel spectrogram images of audio samples.
- **Diffusion Model**: A model that generates new data points by progressively refining random noise into meaningful data, conditioned on the VAE's latent space.

## Influences and Data

This project is highly influenced by the work of [Teticio](https://huggingface.co/teticio), and for simplicity, their dataset was used during the development phase. Future work will involve using my personal dataset to ensure authenticity and further refine the model.

## Dependencies

- Python 3.x
- Colab Notebook (Jupyter fine also)
- PyTorch
- Huggingface Diffusers

## Acknowledgements

This project was developed as part of my graduation project at Istanbul Technical University (ITU). Special thanks to my advisors and colleagues for their support and guidance. Special recognition to Teticio for their influential work and dataset.
