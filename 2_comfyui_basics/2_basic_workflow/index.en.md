---
title: "Basic Workflow"
weight: 43
---

Let's start by accessing your ComfyUI instance and running the default workflow to understand how everything works together.

## Accessing ComfyUI

1. Access your AWS console
2. In the search bar, type "CloudFront"
3. Click on "Distributions"
4. Find and copy the Distribution domain name
5. Open the domain in a new browser tab

![AWS CloudFront Console](/static/comfyui/intro/cloudfront.png)

## Running the Default Workflow

When you first open ComfyUI, you'll see a pre-loaded default workflow. This workflow demonstrates basic image generation using Stable Diffusion.

![Default Workflow Example](/static/comfyui/intro/comfyui_gui.png)

### Components of the Default Workflow:
1. **Load Checkpoint**: Loads the generative AI model
2. **CLIP Text Encode**: Converts your text prompts into model-readable format
3. **KSampler**: Controls the image generation process
4. **VAE Decode**: Converts the KSampler output into a viewable image
5. **Save Image**: Saves your generated image

### Try It Yourself:
1. Click "Queue Prompt" in the top-right corner
2. Watch the progress in the queue information panel
3. See your generated image appear in the right panel
4. Change prompt and Queue prompt again


> **💡 Tip:** The default workflow is a great template to start understanding how nodes connect and work together.

## Understanding the Flow

The workflow follows this basic pattern: **Load Model → Process Text → Generate Image → Save Result**  
Each node in the workflow has a specific purpose, and the connections between them show how data flows from one step to the next.

---

## Next Steps

Now that you've run your first workflow, we'll explore:
- Choose different models
- Working with different types of Workflows
- Adjust and change workflows

> **💡 Note:** Keep the browser tab with ComfyUI open as we'll use it throughout the workshop.

