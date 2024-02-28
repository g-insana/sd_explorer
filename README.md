# sd_explorer
Exploration of stable diffusion spaces (prompt embedding and diffusion noise spaces) via torch in python
by [Giuseppe Insana](https://insana.net), December 2022

## Requirements
torch, transfomers, diffusers, safetensors, PIL, matplotlib

## Usage
Clone the repository and run the provided jupyter notebook.

## Tutorial
Code and usage examples are all in the provided [jupyter notebook](sd_explorer.ipynb).
All the main functions have documentation on their usage and arguments.

Note: if the version on github is not rendering properly, try [this one, via nbviewer.jupyter.org](https://nbviewer.jupyter.org/github/g-insana/sd_explorer/blob/main/sd_explorer.ipynb#Examples) to preview the notebook before you run it on your environment. Tip: jump to usage examples

## Examples and main functionalities
* Simple text2img and repeated sampling
* Interpolation between text prompts:
![From boy to car](boy_to_car.jpg)
* Walking in embedding space beyond the correct point produced by a prompt:
![green hair girl eating noodles](green_haired_girl.jpg)
* Circular or spiral spherical walks through the diffusion noise space with 2 or 3 seeds:
![horses_circular_walk](horses_r48.jpg)
* Multiple variations over a prompt
* Gradual interpolation between variations

## Inspiration
[A walk through latent space with Stable Diffusion](https://keras.io/examples/generative/random_walks_with_stable_diffusion/)


