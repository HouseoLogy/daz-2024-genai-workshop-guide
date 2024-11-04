# Inpainting Workflow

Learn how to selectively edit specific parts of images using AI, allowing for precise modifications while maintaining the original image's integrity.

## Workflow Components
![Inpainting Workflow](/static/comfyui/workflows/3_inpainting_workflow.png)

The inpainting workflow builds upon our previous knowledge with specialized components:
1. **Load Image & Mask**: Loads your base image and masking area
2. **Load Checkpoint**: Loads the AI model (dreamshaper-XL_lightning_painting)
3. **CLIP Text Encode**: Handles positive (green) and negative prompts (red)
4. **InpaintModelConditioning**: Processes the masked area
5. **KSampler**: Controls the generation process
6. **VAE Decode**: Converts latents to visible image
7. **Inpaint CropAndStitch**: Handles seamless integration

## Example Used
**Input Image**  
:image[Toucan with masked head]{src='/static/comfyui/workflows/assets/toucan-mask.jpg' width=196}

## Style Prompt
```
sci-fi horse head, purple and colorful
```

## Negative prompt
```
text, watermark, bad quality, blurry, pixelated
```

### Key Parameters Explained
- **Model**: dreamshaper-XL_lightning
- **Size**: 1024 x 1024
- **Steps**: 18 (More steps for detailed inpainting)
- **CFG**: 2.8 (Balance between creativity and coherence)
- **Sampler**: dpmpp_2m
- **Scheduler**: karras
- **Denoise**: 0.90 (Higher for masked area regeneration)

### Inpainting-Specific Settings
- **context_expand_pixels**: 10 (Blending border size)
- **blend_pixels**: 16.0 (Smoothing between original and new)
- **fill_mask_holes**: true (Clean mask processing)
- **blur_mask_pixels**: 8.0 (Edge softening)

## Practical Use Cases

### Image Repair
- Remove unwanted objects
- Fix damaged areas
- Clean up backgrounds

### Creative Editing
- Change specific features
- Add new elements
- Style specific areas

### Photo Composition
- Blend multiple images
- Adjust lighting/shadows
- Create seamless composites

## Hands-on: Creating an Inpainting Mask

1. Right-click on the workflow image above
2. Select "Save Image As..."
3. Drag and drop the saved image into your ComfyUI workspace
4. Load your own image through the "Load Image" node or choose an existing one
5. Right click on the image and press "Open in MaskEditor"
6. Select area which you want to mask with brush
7. Save mask to node
8. Change prompt and queue it

---

> **💡 Pro Tips:**
> - Create soft mask edges for better blending
> - Use higher denoise values (0.7-1.0) for complete replacements
> - Adjust blend_pixels based on the complexity of surrounding area
> - Use detailed prompts that match surrounding style and lighting

---

Next, we'll explore **Advanced Workflows** including batch processing and animations.