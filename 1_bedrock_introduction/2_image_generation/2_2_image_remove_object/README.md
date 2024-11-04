# Remove Object

Object removal in Titan Image Generator uses semantic masks to isolate and remove specific elements from an image. The process employs content-aware inpainting to seamlessly fill the space where the object was removed. You can specify the object to remove either through a text prompt (maskPrompt) or by providing a binary mask image (maskImage) where a rectangle shape indicate the area to be removed. The model will automatically fill the removed area to match the surrounding context.

#### Remove Object with Selector
![Titan Image Generator - Remove Object with Selector](/static/bedrock/titan/titan_remove_object.png)


#### Remove Object with Prompt
![Titan Image Generator - Remove Object with Prompt](/static/bedrock/titan/titan_remove_prompt.png)


#### Remove Object Result
![Titan Image Generator - Remove Object Results](/static/bedrock/titan/titan_remove_result.png)


#### Used Prompt for source Image
We will use the previous prompt to illustrate the different actions.
```
A white art gallery wall with a large framed canvas in the center, professional gallery lighting from above, polished concrete floor, minimalist gallery setting, showing an abstract painting with flowing shapes in blue and gold tones, 4k quality, professional interior photography
```

---

Let's try out the next action ’Replace Object’


