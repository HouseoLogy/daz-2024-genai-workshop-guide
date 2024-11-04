---
title : "Stable Diffusion XL 1.0"
weight : 32
---

When using Stable Diffusion XL 1.0 you have several configuration options and actions to control your image generation:

### Available Actions for SDXL
- **Generate Image**: Create a new image from your prompt
- **Generate Variations**: Create variations of an existing image
- **Edit**: Edit selected objects from the image


### Basic Configuration

#### Negative Prompt
Enter terms describing what you want to avoid in your image.  
Example: ’bad quality, blurry, distorted, pixelated’

#### Response Image Settings
- **Orientation**
  - Landscape
  - Portrait
- **Size**: 1024 x 1024 pixels (standard size, several options available)

### Advanced Configurations

#### Prompt Strength
- Scale: 1-30 (default: 10)
- Higher values: Stronger adherence to prompt
- Lower values: More creative freedom by the model

#### Generation step
- Scale: 1-150 (default: 50)
- Higher values: Potential more accurate results but longer execution time
- Lower values: Potential less accurate results but faster execution time

#### Seed
- Numerical value (e.g., 0)
- Use specific seeds to recreate exact results
- Same seed + same prompt = same image

> **💡 Tip:** Keep a fixed seed value if you want to recreate or iterate on a specific generation

---

# Image Generation


For generating an image you just have to type in a prompt, optionally change the configurations based on your preferences, and press the Run button to execute the image generation.

> **💡 Tip:** You can search online for Stable Diffusion prompt guidelines to ramp-up and master your prompt engineering skills.

![SDXL 1.0 - Generate Image](/static/bedrock/stability/sdxl/sdxl_generate_image.png)

#### Used Prompt for source Image
**Positive prompt**
:::code{showCopyAction=true}
fragmented geometric face, overlapping planes, analytical cubism, muted earth tones, newspaper texture, gallery presentation, clean composition
:::
**Negative prompt**
:::code{showCopyAction=true}
realistic, smooth, natural colors, organic shapes
:::

---

# Generate Variations

![SDXL 1.0 - Generate Variations](/static/bedrock/stability/sdxl/sdxl_generate_variations.png)

---

# Edit Image

Similar to Titan Image Generator you have the capability of editing an existing image. Here you have to mask an area with the selector tool and describe in the prompt what you want to generate in that area.

#### Edit : remove object
![SDXL 1.0 - Edit remove object](/static/bedrock/stability/sdxl/sdxl_edit_remove_object.png)

#### Edit : remove object result
![SDXL 1.0 - Edit remove result](/static/bedrock/stability/sdxl/sdxl_edit_remove_result.png)

#### Edit: replace object result
![SDXL 1.0 - Edit replace result](/static/bedrock/stability/sdxl/sdxl_edit_replace_result.png)

---

### Diverse Prompt Insipirations for SDXL  

![SDXL 1.0 - Sci-Fi Metropolis](/static/bedrock/stability/gallery/sdxl_scifi-metropolis.png) ![SDXL 1.0 - Digital Abstract](/static/bedrock/stability/gallery/sdxl_digital_abstract.png) ![SDXL 1.0 - Fantasy Realm](/static/bedrock/stability/gallery/sdxl_fantasy_realm.png) ![SDXL 1.0 - Retro Futuristic](/static/bedrock/stability/gallery/sdxl_retro_futuristic.png)

:::::tabs{variant="container"}

::::tab{id="scifi" label="Sci-Fi Metropolis"}
:::code{showCopyAction=true}
futuristic sci-fi cityscape, towering holographic skyscrapers, flying vehicles, vibrant neon lights, diverse alien cultures walking the streets, soft ambient glow, advanced technology integration, stunning sunset sky, deep shadows, cinematic angle, ultra high resolution, dynamic composition
:::
::::

::::tab{id="abstract" label="Digital Abstract"}
:::code{showCopyAction=true}
abstract digital artwork, flowing geometric shapes, vibrant color gradients, swirling patterns, light effects interacting with shapes, dynamic movement, ethereal atmosphere, high-definition details, immersive visual experience, unique artistic interpretation
:::
::::

::::tab{id="jungle" label="Neon Jungle"}
:::code{showCopyAction=true}
bioluminescent rainforest at night, glowing flora and fauna, neon pink and blue organic lighting, mystical fog effects, floating spores, ethereal atmosphere, exotic plant structures, dynamic lighting, deep shadows, ultra detailed environment, perfect composition, photorealistic quality
:::
::::

::::tab{id="retro" label="Retro Future"}
:::code{showCopyAction=true}
retro-futuristic scene, 1980s inspired architecture with vibrant neon colors, flying cars resembling vintage designs, palm trees lining the streets, sci-fi elements blended with nostalgia, cosmic backgrounds, playful and imaginative atmosphere, dreamlike quality
:::
::::

::::tab{id="fantasy" label="Fantasy Realm"}
:::code{showCopyAction=true}
enchanting fantasy forest realm, mystical creatures roaming among vibrant flora, ethereal light breaking through the canopy, ancient ruins covered in moss, whimsical architecture, magical atmosphere, sense of adventure and exploration, picturesque and serene
:::
::::

:::::

---

Let's explore the capabilities of the next Stability AI model **SD3 Large 1.0**



