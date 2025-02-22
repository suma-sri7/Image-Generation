# Image-Generation
# Description
Image Generation using Stable Diffusion & ComfyUI with v1-5-pruned.safetensors
This project utilizes Stable Diffusion and ComfyUI to generate high-quality AI-generated images. ComfyUI provides a node-based interface, allowing users to create custom workflows for image generation.
The v1-5-pruned.safetensors model is a Stable Diffusion v1.5 checkpoint that has been optimized for better performance and reduced size. It enables faster image generation.
# Download
1.download ComfyUI(Main Framework)

2.download v1-5-pruned.safetensors(Stable Diffusion Model Checkpoint)
# Usage
1️⃣ Open ComfyUI Folder
    Navigate to the ComfyUI directory where it is installed.
    
2️⃣ Run ComfyUI on CPU

    Double-click on run_cpu
    A Command Prompt window will open and start processing.
    Once started, your browser will automatically open http://127.0.0.1:8188
   
3️⃣Generate Images Using ComfyUI

    Load your Stable Diffusion model (v1-5-pruned.safetensors) in the "Load Checkpoint" node.
    Adjust parameters like prompt, resolution, sampler, etc.
    Click "Queue Prompt" to generate an image.
