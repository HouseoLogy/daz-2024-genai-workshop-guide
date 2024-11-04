---
title : "Generate Variations"
weight : 24
---

The Titan Image Generator can create multiple variations of an existing image while maintaining its core elements and style. This feature allows you to explore different interpretations of the same concept by using the ImageVariationTask. When generating variations, you can specify the number of variations to create (between 1-5) and use a seed value to control reproducibility.

#### Generate Variations
![Titan Image Generator - Generate variations](/static/bedrock/titan/titan_variations.png)


#### Variations Result - Similarity strength 0.2
![Titan Image Generator - Variation low similarity](/static/bedrock/titan/titan_variations_low_similarity.png)


#### Variations Result - Similarity strength 0.9
![Titan Image Generator - Variation high similarity](/static/bedrock/titan/titan_variations_high_similarity.png)


#### Used Prompt for source Image
We will use the previous prompt to illustrate the different actions.
:::code{showCopyAction=true}
A white art gallery wall with a large framed canvas in the center, professional gallery lighting from above, polished concrete floor, 
minimalist gallery setting, showing an abstract painting with flowing shapes in blue and gold tones, 4k quality, professional interior photography
:::

---

Let's try out the next action ’Remove Object’



