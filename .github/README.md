# ComfyUI Subgraphs

Reusable ComfyUI nodes for image editing, prompt writing, upscaling, and video tools. Each JSON contains a single reusable subgraph with a Quick Start note inside.

## How to use

1. Download the JSON you want and open it in ComfyUI.
2. Copy the subgraph node into your workflow. To keep it in your node library, select it and choose **Add Subgraph to Library**.
3. Open the subgraph and read its **Quick Start** note. Connect the required inputs and send its output to a preview, save node, or the next step in your workflow.
4. If a node or model is missing, check the loaders inside the subgraph and install the required files. The Ideogram prompt tools and Z-Image pass also need the Ollama service and model configured in their nodes.

See the [ComfyUI subgraph guide](https://docs.comfy.org/interface/features/subgraph) for details on editing subgraphs and saving them to the library.

## Included subgraphs

| Subgraph | What it does |
| --- | --- |
| [Frame Interpolation](../Frame%20Interpolation.json) | Adds frames between existing video frames. |
| [Image to Ideogram Prompt](../Image%20to%20Ideogram%20Prompt.json) | Expands a text idea into a structured Ideogram prompt. |
| [Image to Ideogram Realistic Prompt](../Image%20to%20Ideogram%20Realistic%20Prompt.json) | Writes a structured Ideogram prompt for realistic images. |
| [Klein Inpaint](../Klein%20Inpaint.json) | Edits a masked area with FLUX.2 Klein. |
| [Klein Outpaint](../Klein%20Outpaint.json) | Extends an image beyond its original borders with FLUX.2 Klein. |
| [Realistic Post](../Realistic%20Post.json) | Upscales and finishes an image with sharpening, noise, brightness, and contrast controls. |
| [SeedVR2 Image Upscale](../Seed2VR%20Image%20Upscale.json) | Enlarges images with SeedVR2. |
| [Video Metadata](../Video%20Metadata.json) | Returns a text summary of a video's dimensions, frame rate, duration, and other properties. |
| [Z-Image Pass with LoRA](../Z-Image%20Pass%20with%20LoRa.json) | Refines an input image with Z-Image and a selected LoRA. |
