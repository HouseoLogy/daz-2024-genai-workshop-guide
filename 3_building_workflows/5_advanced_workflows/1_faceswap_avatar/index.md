---
title: "Face swapping Avatars"
weight: 72
---

# Image-to-Image Workflow

Let's explore how to transform existing images using AI by combining them with text prompts to create new artistic variations.

## Workflow Components
![Image-to-Image Workflow](/static/comfyui/workflows/2_image_to_image.png)

The workflow adds image input capability to our base workflow:
1. **Load Image**: Loads your reference image
2. **VAE Encode**: Converts the image to latent space
3. **CLIP Text Encode**: Adds style and modification prompts
4. **KSampler**: Controls the transformation process
5. **VAE Decode**: Converts back to visible image
6. **Preview Image**: Shows the result

## Example Used
**Input Image**  
:image[Toucan Photoraph]{src='/static/comfyui/workflows/assets/toucan-unsplash.jpg' width=196}

**Style Prompt**
:::code{showCopyAction=true}
cybernetik bird, vaporwave aesthetics, sci-fi
:::
**Negative prompt**
:::code{showCopyAction=true}
text, watermark, bad quality, blurry, pixelated
:::

### Key Parameters Explained
- **Model**: dreamshaper-XL.safetensors
- **Size**: 1024 x 1024
- **Steps**: 6 (Fewer steps needed for img2img)
- **CFG**: 3.0 (Higher for stronger style transfer)
- **Sampler**: dpmpp_2m
- **Scheduler**: karras
- **Denoise**: 0.70 (Controls how much of original image to keep)

## Practical Use Cases

::::tabs{variant="container"}
:::tab{id="style" label="Style Transfer"}
- Photo to digital art
- Reality to fantasy
- Period style transformations
:::
:::tab{id="creative" label="Creative Editing"}
- Character modifications
- Scene alterations
- Artistic interpretations
:::
:::tab{id="brand" label="Brand Asset Creation"}
- Logo variations
- Product visualizations
- Marketing material alternatives
:::
::::
  

## Hands-on: Loading the Workflow

1. Right-click on the workflow image above
2. Select "Save Image As..."
3. Drag and drop the saved image into your ComfyUI workspace
4. Load your own image through the "Load Image" node

---

> **💡 Pro Tips:**
> - Denoise strength controls the balance between original and new elements
> - Start with lower denoise values (0.5-0.7) to maintain more original image
> - Use descriptive style prompts that match your vision
> - Keep original image aspects you want to maintain in your prompt
> - Experiment with different CFG values for style intensity

---

Next, we'll learn about **inpainting** - selective image editing for precise control.