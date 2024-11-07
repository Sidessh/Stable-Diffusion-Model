# Custom Stable Diffusion Generator

This project implements a custom Stable Diffusion model using key components like **UNet**, **CLIP**, and **VAE** for text-to-image synthesis. The model leverages a deep learning pipeline to generate high-quality, detailed images from textual prompts, allowing for a variety of creative image generation tasks.

## Key Features

- **Text-to-Image Synthesis:** Generate images from text prompts by embedding text with CLIP, generating latents with UNet, and decoding them into high-quality images using VAE.
- **Customizable Generation Parameters:** Control image resolution, inference steps, and guidance scale for personalized image generation.
- **Efficient Latent Diffusion:** Utilize a customized scheduler and noise reduction techniques to ensure high-quality output with reduced artifacts.
  
## Components

- **UNet**: Used for generating image latents and applying denoising to ensure clean, detailed images.
- **CLIP**: Converts text prompts into embeddings, which guide the image generation process.
- **VAE (Variational Autoencoder)**: Decodes image latents into pixel-space to produce the final output images.
- **Scheduler**: Manages the inference steps to fine-tune the image generation process.
  
