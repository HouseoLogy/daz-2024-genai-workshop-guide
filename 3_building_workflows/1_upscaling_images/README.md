# Upscaling Images Workflow

Let's enhance our text-to-image workflow by adding upscaling capabilities to achieve higher resolution and sharper details.

## Workflow Components
![Upscaling Workflow](/static/comfyui/workflows/1_upscale_workflow.png)

The workflow builds on the basic text-to-image workflow and adds:
1. **Load Upscale Model**: Loads RealESRGAN_x2.pth for high-quality upscaling
2. **Upscale Image**: Processes the generated image to increase resolution
3. **Preview Image**: Shows both original and upscaled results

## New Components Explained
### Upscaling Process
- **RealESRGAN Model**: ML model upscaling that maintains image quality
- **2x Upscaling**: Doubles the resolution (1024x1024 → 2048x2048)
- **Quality Preservation**: Maintains details while increasing size

### Key Parameters
All previous parameters remain the same, plus:
- **Upscale Model**: RealESRGAN_x2.pth
- **Original Size**: 1024 x 1024
- **Upscaled Size**: 2048 x 2048

## Practical Use Cases
### High-Resolution Requirements
- Print-ready artwork
- Large format displays
- Detailed presentations

### Detail Enhancement
- Portrait enhancement
- Product photography
- Architectural renderings

## Hands-on: Loading the Upscaling Enhanced Workflow

1. Right-click on the workflow image above
2. Select "Save Image As..."
3. Drag and drop the saved image into your ComfyUI workspace

---

> **💡 Pro Tips:**
> - Original image quality matters - garbage in, garbage out
> - Not all images need upscaling - consider your use case
> - Check the final file size - upscaled images are larger

---

Next, we'll explore **image-to-image** techniques for transforming existing images.