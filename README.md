# Image-Generation
# Description
Image Generation using Stable Diffusion & ComfyUI with v1-5-pruned.safetensors
This project utilizes Stable Diffusion and ComfyUI to generate high-quality AI-generated images. ComfyUI provides a node-based interface, allowing users to create custom workflows for image generation.
The v1-5-pruned.safetensors model is a Stable Diffusion v1.5 checkpoint that has been optimized for better performance and reduced size. It enables faster image generation.
# Download
1.download ComfyUI(Main Framework)

2.download v1-5-pruned.safetensors(Stable Diffusion Model Checkpoint)
# process
Run ComfyUI with GPU Acceleration
1️⃣ Double-click run_gpu
    A Command Prompt window will open and start processing.
2️⃣ Open ComfyUI in a Web Browser
    Once started, your browser will automatically open http://127.0.0.1:8188
    If it doesn't open automatically, manually open the URL in your browser.
3️⃣Generate Images Using ComfyUI
    Load your Stable Diffusion model (v1-5-pruned.safetensors) in the "Load Checkpoint" node.
    Adjust parameters like prompt, resolution, sampler, etc.
    Click "Queue Prompt" to generate an image.
