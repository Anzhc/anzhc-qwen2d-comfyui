A node to support inference using this vae - https://huggingface.co/Anzhc/Qwen2D-VAE

Allows to use much cheaper and faster approach for models that use Qwen VAE, but do not utilize temporality, like:

- Anima
- Krea 2
- Qwen Image
- Any other model that gens images and uses WAN/Qwen vae.
