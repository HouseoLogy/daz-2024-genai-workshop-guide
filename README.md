# daz-2024-genai-workshop-guide
```bash
temporary workshop guide to deep-dive into some neat generative AI topics.
```
![Stable Image Ultra - Hyperrealistic Portrait](/static/bedrock/stability/gallery/ultra_hyper.jpeg) ![Stable Image Ultra - Desert Punk](/static/bedrock/stability/gallery/ultra_desert.jpeg) ![Stable Image Ultra - Sleeping Exposure](/static/bedrock/stability/gallery/ultra_exposure.jpeg)

## Table of Contents
- [Getting Started](0_getting_started/README.md)
- [1 - Amazon Bedrock Introduction](1_bedrock_introduction/README.md)
    - [What is Amazon Bedrock](1_bedrock_introduction/0_bedrock/README.md)
    - [Enable Amazon Bedrock Model Access](1_bedrock_introduction/1_model_access/README.md)
    - [Titan Image Generation](1_bedrock_introduction/2_image_generation/README.md)
        - [Image Variation](1_bedrock_introduction/2_image_generation/2_1_image_variation/README.md)
        - [Image Remove Object](1_bedrock_introduction/2_image_generation/2_2_image_remove_object/README.md)
        - [Image Replace Object](1_bedrock_introduction/2_image_generation/2_3_image_replace_object/README.md)
        - [Image Remove Background](1_bedrock_introduction/2_image_generation/2_4_image_remove_background/README.md)
    - [Stable Diffusion Models](1_bedrock_introduction/3_image_generation_sd/README.md)
        - [SDXL](1_bedrock_introduction/3_image_generation_sd/3_1_SDXL/README.md)
        - [SD3Large](1_bedrock_introduction/3_image_generation_sd/3_2_SD3Large/README.md)
        - [StableImageCore](1_bedrock_introduction/3_image_generation_sd/3_3_StableImageCore/README.md)
        - [StableImageUltra](1_bedrock_introduction/3_image_generation_sd/3_4_StableImageUltra/README.md)
- [2 - ComfyUI Basics](2_comfyui_basics/README.md)
    - [What is ComfyUI](2_comfyui_basics/0_comfyui/README.md)
    - [ComfyUI Interface](2_comfyui_basics/1_ui/README.md)
    - [Basic Workflow](2_comfyui_basics/2_basic_workflow/README.md)
- [3 - Building Workflows](3_building_workflows/README.md)
    - [Text to Image](3_building_workflows/0_text_to_image/README.md)
    - [Upscaling Images](3_building_workflows/1_upscaling_images/README.md)
    - [Image to Image](3_building_workflows/2_image_to_image/README.md)
    - [Inpainting](3_building_workflows/3_inpainting/README.md)
    - [Style Transfer](3_building_workflows/4_style_transfer/README.md)
    - [Advanced Workflows](3_building_workflows/5_advanced_workflows/README.md)
        - [IP-Adapter](3_building_workflows/5_advanced_workflows/0_ipadapter/README.md)
        - [Face Swap Avatar](3_building_workflows/5_advanced_workflows/1_faceswap_avatar/README.md)
        - [Batch Text to Video](3_building_workflows/5_advanced_workflows/2_batch_text_to_video/README.md)
        - [Image to Video Morph](3_building_workflows/5_advanced_workflows/3_image_to_video_morph/README.md)
    - [QR Code Art Blending](3_building_workflows/5_qrcode_art_blending/README.md)
    - [Temporary Workflows](3_building_workflows/5_tmp_workflows/README.md)
- [4 - Full Stack Avatar App](4_full_stack_avatar_app/README.md)
- [5 - Advanced Features](5_advanced_features/README.md)
- [6 - Wrap Up](6_wrap_up/README.md)
  

---

# Creative generative AI Workshop

Welcome to this hands-on workshop where you'll explore the exciting world of generative AI using Amazon Bedrock and ComfyUI. In this workshop, you'll learn how to create, manipulate, and automate image generation using state-of-the-art AI models.

## What you will learn

Throughout this workshop, you'll gain hands-on experience with:
- Creating custom images using Amazon Bedrock's AI models (Titan Image Generator and Stable Diffusion)
- Building and automating image generation workflows with ComfyUI
- Developing a full-stack AI Avatar generation application
- Working with advanced models like Flux and Stable Diffusion 3

## Who is this workshop for?

This workshop is ideal for:
- Software developers with interest in image / video generation
- Game designer / developer
- Digital artists and designers
- Tech and generative AI enthusiasts

No prior experience with AI or AWS is required.

## Technical requirements

- A laptop with internet access
- Web browser (Chrome/Firefox recommended)
- AWS Account (instructions provided in setup)

Note: This workshop involves some hands-on activities and cloud resource usage. Tablets and mobile devices are not suitable for completing the exercises.

## Time to complete

Estimated time: 2-3 hours

Let's start exploring the creative possibilities of generative AI! Let's :link[Get Started]{href="/0-getting-started"}!


## What content you can expect

![SDXL 1.0 - Sci-Fi Metropolis](/static/bedrock/stability/gallery/sdxl_scifi-metropolis.png) ![SDXL 1.0 - Digital Abstract](/static/bedrock/stability/gallery/sdxl_digital_abstract.png) ![SDXL 1.0 - Fantasy Realm](/static/bedrock/stability/gallery/sdxl_fantasy_realm.png) ![SDXL 1.0 - Retro Futuristic](/static/bedrock/stability/gallery/sdxl_retro_futuristic.png) ![SD3 Large - Epic Gaming Discovery](/static/bedrock/stability/gallery/sd3_epic_fantasy.jpeg) ![SD3 Large - Atomic Age Cityscape](/static/bedrock/stability/gallery/sd3_atomic_age.jpeg) ![SD3 Large - Wisdom Portrait](/static/bedrock/stability/gallery/sd3_wisdom_portrait.jpeg) ![SD3 Large - Modern Art](/static/bedrock/stability/gallery/sd3_modern_art.jpeg) ![Stable Image Core - Steampunk Observatory](/static/bedrock/stability/gallery/core_steampunk.jpeg) ![Stable Image Core - Miniature World](/static/bedrock/stability/gallery/core_mini.jpeg) ![Stable Image Core - Paper Univers](/static/bedrock/stability/gallery/core_paper.jpeg) ![Stable Image Core - Neon Noir](/static/bedrock/stability/gallery/core_neon.jpeg)  
