---
title : "Replace Object"
weight : 26
---

Object replacement combines inpainting capabilities with prompt-guided generation. You can select an area to modify using either a maskPrompt or maskImage, then provide a text description of the new content to replace it. The model supports a maximum resolution of 1408×1408 and ensures the new element blends naturally with the existing image. For example, you can replace one subject with another (like replacing an existing artwork with a new one) while maintaining the overall composition and lighting of the scene.

#### Replace Object with Selector
![Titan Image Generator - Replace Object with Selector](/static/bedrock/titan/titan_replace_object.png)


#### Replace Object with Prompt
![Titan Image Generator - Replace Object with Prompt](/static/bedrock/titan/titan_replace_prompt.png)


#### Replace Object Result
![Titan Image Generator - Replace Object Results](/static/bedrock/titan/titan_replace_result.png)


#### Used Prompt for source Image
We will use the previous prompt to illustrate the different actions.
:::code{showCopyAction=true}
A white art gallery wall with a large framed canvas in the center, professional gallery lighting from above, polished concrete floor, 
minimalist gallery setting, showing an abstract painting with flowing shapes in blue and gold tones, 4k quality, professional interior photography
:::

---

Let's try out the last action ’Remove Background’
