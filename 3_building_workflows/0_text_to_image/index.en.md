---
title: "Text-to-Image"
weight: 61
---

# Text-to-Image Generation

Let's explore the fundamental workflow for generating images from text descriptions using ComfyUI.

## Workflow Components
![Text to Image Workflow](/static/comfyui/workflows/0_text_to_image.png)

The basic workflow consists of:
1. **Load Checkpoint**: Loads the generative AI model (in our case dreamshaper-XL)
2. **Empty Latent Image**: Defines the canvas size (1024x1024)
3. **CLIP Text Encode**: Processes positive and negative prompts
4. **KSampler**: Controls generation parameters
5. **VAE Decode**: Converts latent image to visible image
6. **Preview Image**: Displays the result

## Example Prompts used
**Positive prompt**
:::code{showCopyAction=true}
interstellar transit hub, massive glass domes showing nebulas, floating anti-gravity platforms, holographic arrival boards, stellar transit vehicles, atmospheric space effects, clean futuristic design, dynamic lighting, perfect composition
:::
**Negative prompt**
:::code{showCopyAction=true}
text, watermark, bad quality, blurry, pixelated
:::

### Key Parameters Explained
- **Model**: dreamshaper-XL.safetensors (Excellent for detailed scenes)
- **Size**: 1024 x 1024 (Standard high-resolution output)
- **Steps**: 8 (Balance between quality and speed)
- **CFG**: 2.0 (Controls prompt influence strength)
- **Sampler**: dpmpp_2m (Good quality/speed balance)
- **Scheduler**: karras (Improved detail distribution)
- **Denoise**: 1.0 (Full image generation)

## Practical Use Cases
::::tabs{variant="container"}
:::tab{id="concept" label="Concept Art Creation"}
   - Scene visualization
   - Character design
   - Environment design
:::
:::tab{id="marketing" label="Marketing Materials"}
   - Product visualization
   - Advertisement backgrounds
   - Social media content
:::
:::tab{id="arch" label="Architectural Visualization"}
   - Interior concepts
   - Exterior renderings
   - Space planning
:::
::::

---

## Hands-on: Loading the Workflow

1. Right-click on the workflow image above
2. Select "Save Image As..."
3. Drag and drop the saved image into your ComfyUI workspace

---

> **💡 Pro Tips:**
> - Start with simple prompts and gradually add detail
> - Use negative prompts to avoid common issues
> - Experiment with different samplers for varying results
> - Save successful prompts for future reference
> - Use Amazon Bedrock Chat to create more comprehensive prompts
> - Try changing one parameter at a time to understand its impact

---

Next, we'll enhance this workflow with **upscaling & sharpening** techniques to achieve even higher quality results.