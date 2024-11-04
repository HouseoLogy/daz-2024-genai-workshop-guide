# Image generation with Titan Image Generator


## Titan Image Generator G1 v2

![Titan Image Generator G1 v2](/static/bedrock/titan/generate_art_gallery.png)

#### Example Prompt for Titan Image Generator
:::code{showCopyAction=true}
A white art gallery wall with a large framed canvas in the center, professional gallery lighting from above, polished concrete floor, 
minimalist gallery setting, showing an abstract painting with flowing shapes in blue and gold tones, 4k quality, professional interior photography
:::
  

**Open Image Playground in Bedrock**
1. Search for Amazon Bedrock in the Search Bar (star it for bookmarking)
2. Select Playgrounds / Image
3. Select model
4. Model provider Amazon
5. Titan Image Generator G1 v2
6. Apply

---

## Configuration Guide

When using Titan Image Generator, you have several configuration options and actions to control your image generation:

### Available Actions
- **Generate Image**: Create a new image from your prompt
- **Generate Variations**: Create variations of an existing image
- **Remove Object**: Remove selected objects from the image
- **Replace Object**: Replace selected objects with new ones
- **Remove Background**: Remove the background, keeping only the main subject

### Basic Configuration

#### Negative Prompt
Enter terms describing what you want to avoid in your image.  
Example: ’bad quality, blurry, distorted, pixelated’

#### Response Image Settings
- **Orientation**
  - Landscape
  - Portrait
- **Size**: 1024 x 1024 pixels (standard size, several options available)
- **Number of Images**: Generate 1-5 images per run (slider control)

### Advanced Configurations

#### Prompt Strength
- Scale: 1-10 (default: 8)
- Higher values: Stronger adherence to prompt
- Lower values: More creative freedom by the model

#### Seed
- Numerical value (e.g., 0)
- Use specific seeds to recreate exact results
- Same seed + same prompt = same image

> **💡 Tip:** Keep a fixed seed value if you want to recreate or iterate on a specific generation

---

These settings allow you to configure your image generation process and maintain consistency across multiple generations when needed.

--
### Diverse Prompt Insipirations for Titan Image Generator  

![Titan - Paint Data Flow](/static/bedrock/stability/gallery/titan_paint.png) ![Titan - Mechanical Bloom](/static/bedrock/stability/gallery/titan_bloom.png) ![Titan - Cyber Shrine](/static/bedrock/stability/gallery/titan_temple.png) ![Titan - Time Gallery](/static/bedrock/stability/gallery/titan_museum.png) 

## Paint Data Flow
```
flowing paint streams in digital space, abstract data visualization through liquid colors, geometric patterns emerging from paint splashes, holographic color theory, dynamic brush strokes, clean composition, perfect color harmony, ultra sharp details, artistic algorithms
```

## Cyber Shrine
```
ancient temple with cybernetic upgrades, holographic prayer wheels, neon-lit ancient symbols, incense smoke with data particles, clean architectural lines, perfect mood lighting, dynamic composition, ultra detailed ornaments, ethereal atmosphere
```

## Liquid Architecture
```
flowing metallic structures defying gravity, liquid mercury buildings catching light, chrome waterfalls between geometric forms, clean minimal design, perfect reflections, dynamic fluid motion, ultra sharp details, professional lighting, ethereal atmosphere
```

## Mechanical Bloom
```
clockwork flowers opening at dawn, brass and copper petals with steam effects, geometric garden design, clean industrial aesthetic, perfect morning light, dynamic mechanisms, ultra detailed machinery, professional composition, ethereal mist
```

## Time Gallery
```
museum space warping through different eras, classical sculptures morphing into futuristic forms, clean white gallery space, perfect temporal transitions, dynamic chronological flow, ultra detailed art pieces, professional lighting, ethereal atmosphere
```

---

Let's jump to the next chapter, where we cover the Titan Image Varations Actions.

