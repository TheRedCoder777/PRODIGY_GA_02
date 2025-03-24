Stable Diffusion Image Generation Web App:
This is a Flask-based web application that generates AI-generated images using Stable Diffusion (v1.4). Users can input a text prompt, and the model will generate a corresponding image, which can be downloaded.

Features:
1. Generates images from text using Stable Diffusion v1.4
2. Supports CUDA for GPU acceleration (if available)
3. Displays the generated image on the webpage
4. Allows users to download the generated image

Tech Stack:
1. Python
2. Flask
3. Torch (PyTorch)
4. Diffusers Library (Stable Diffusion)

How It Works:
1. User enters a text prompt in the web interface.
2. The Stable Diffusion model processes the input and generates an image.
3. The generated image is saved in the static/ directory.
4. The image is displayed on the webpage and can be downloaded.
