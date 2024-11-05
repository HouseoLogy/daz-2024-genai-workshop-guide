# QR Code Art Blending Workflow

Learn how to transform QR codes into artistic designs while maintaining their scannable functionality using ControlNet and advanced blending techniques.

## Workflow Components
![QR Code Art Workflow](/static/comfyui/workflows/5_qr_code_workflow.png)
## Workflow Components
![Style Transfer Workflow](/static/comfyui/workflows/4_style_transfer_workflow.png)

The QR code art workflow uses ControlNet for structure preservation:
1. **Load Checkpoint**: dreamshaper-8-sd15 model
2. **Load ControlNet Model**: control_v1p_sd15 for structure guidance
3. **Empty Latent Image**: Sets generation canvas
4. **Load Image**: Your QR code input
5. **Apply ControlNet**: Maintains QR code structure
6. **CLIP Text Encode**: Style and negative prompts
7. **KSampler Advanced**: Precise generation control
8. **VAE Decode**: Final image rendering

## Example Used
**Input Image**  
:image[QR Code]{src='/static/comfyui/workflows/assets/qr-code-input.jpg' width=196}

## Style Prompt
```
sci-fi landscape, dystopian, dune style
```

## Negative prompt
```
bad quality, blurry, pixelated
```

### Key Parameters Explained
- **Size**: 512 x 512 (balanced for QR readability)
- **ControlNet Settings**:
  - Strength: 1.25 (strong structure preservation)
  - Start Percent: 0.077 (early guidance)
  - End Percent: 0.921 (extended control)
- **Sampling Parameters**:
  - Steps: 8 (balanced detail)
  - CFG: 2.0 (style flexibility)
  - Sampler: dpmpp_2m
  - Scheduler: karras

## Practical Use Cases

### Branding
- Custom business QR codes
- Event ticket QR designs
- Brand identity integration

### Marketing
- Interactive advertisements
- Product packaging
- Social media campaigns

### Artistic
- Gallery installations
- Digital art pieces
- Mixed media projects

## Hands-on: Creating Scannable Art

1. Start with a high-contrast QR code
2. Set appropriate ControlNet strength (1.2-1.4)
3. Use descriptive style prompts
4. Test scan after each generation
5. Adjust parameters if needed

---

> **💡 Pro Tips:**
> - Keep high contrast in prompt design for better scanning
> - Test QR code functionality frequently during generation
> - Use ControlNet strength above 1.0 to preserve structure
> - Start_percent near 0.07 helps establish basic structure
> - End_percent around 0.92 maintains readability
> - Lower CFG (1.8-2.2) allows for more artistic freedom while maintaining structure
> - Consider the final use case when selecting resolution

---

## Optimization Guidelines

### For Better Scannability:
```markdown
- Increase ControlNet strength (1.2-1.4)
- Maintain high contrast in style prompts
- Use larger resolution for complex QR codes
- Keep CFG below 2.5
```

### For More Artistic Freedom:
```markdown
- Reduce ControlNet strength slightly (1.0-1.2)
- Experiment with style prompts
- Use start_percent/end_percent for controlled variation
- Consider multiple generation attempts
```

---

Next, we'll explore **advanced** workflows in ComfyUI.
