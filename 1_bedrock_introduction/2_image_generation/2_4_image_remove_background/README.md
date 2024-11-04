---
title : "Remove Background"
weight : 27
---

Background removal in Titan Image Generator v2 uses advanced segmentation capabilities to automatically identify and isolate foreground objects from their background. The model can intelligently detect multiple objects in the foreground and cleanly separate them, even when they overlap with other elements. The output is provided with a transparent background, making it ideal for creating product images or preparing assets for various marketing materials. This feature is exclusive to the v2 model and requires no manual masking input from the user.

#### Replace Background with Selector
![Titan Image Generator - Replace Background with Selector](/static/bedrock/titan/titan_background_object.png)


#### Replace Background with Prompt
![Titan Image Generator - Replace Background with Prompt](/static/bedrock/titan/titan_background_prompt.png)


#### Replace Background Result
![Titan Image Generator - Replace Background Results](/static/bedrock/titan/titan_background_result.png)


#### Used Prompt for source Image
We will use the previous prompt to illustrate the different actions.
:::code{showCopyAction=true}
A white art gallery wall with a large framed canvas in the center, professional gallery lighting from above, polished concrete floor, 
minimalist gallery setting, showing an abstract painting with flowing shapes in blue and gold tones, 4k quality, professional interior photography
:::

---

Let's explore the capabilities of the next Image Generation model: Stable Diffusion.





