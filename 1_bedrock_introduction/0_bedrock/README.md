# What is Amazon Bedrock?


![Amazon Bedrock](/static/bedrock/bedrock_banner.png)  
Amazon Bedrock is a fully managed service that provides access to high-performing foundation models (FMs) through a unified API. It offers a broad set of capabilities to build generative AI applications with security, privacy, and responsible AI practices.

## Key Features

![Amazon Bedrock Features](/static/bedrock/bedrock_features.png)  

- Model choice: Access to FMs from AI21 Labs, Anthropic, Cohere, Meta, Mistral AI, Stability AI, and Amazon for text generation, summarization, question answering, image generation, and more.
- Customization: Privately fine-tune FMs with your own labeled datasets or continue pretraining with unlabeled data to adapt models to your specific domain or industry.
- Security, privacy, and safety: Amazon Bedrock provides features for data security, privacy, and responsible AI practices, such as guardrails for safe model outputs.
- Data usage: AWS and the third-party model providers will not use any inputs to or outputs from Amazon Bedrock to train Amazon Titan or any third-party models.
- Playgrounds: Use FMs directly over the AWS Console with Playgrounds to test out and use leading FMs directly.

### Image Generation Capabilities
- **Titan Image Generator**: Amazon's proprietary model for diverse image creation
- **Stable Diffusion**: Stability AI's state-of-the-art image generation models (including Stable Diffusion 3 and Stable Image Core / Ultra)

## How Bedrock Works

1. **Model Selection**
  - Choose from available foundation models
  - Each model has specific strengths and use cases

2. **Use over AWS Console or API Integration**
  - Use models directly in the AWS Console over Image playground in Amazon Bedrock
  - Simple REST API calls
  - SDK support for multiple programming languages
  - Consistent interface across different models

3. **Security & Governance**
  - Built-in AWS security features
  - Private endpoint support
  - Model access management

## Workshop Focus

In this workshop, we will specifically use:
- Titan Image Generator for actiosn like removing or replacing objects, backgrounds 
- Stable Diffusion for generating images and variations

> **💡 Tip:** While Bedrock offers many models, we'll focus on those suited for image generation tasks.

## Next Steps

In the following sections, we'll:
1. Enable model access in your account
2. Create your first generated image
3. Explore Titan Image Genrator and Stable Diffusion features

Ready to start generating images? Let's proceed to setting up [Amazon Bedrock Model Access](../1_model_access/README.md)!

---

### Additional resources and references

[Amazon Bedrock](https://aws.amazon.com/bedrock/)  
[Titan Image Generator v2 Blog](https://aws.amazon.com/blogs/aws/amazon-titan-image-generator-v2-is-now-available-in-amazon-bedrock/)  
[Stability AI new models Blog](https://aws.amazon.com/blogs/aws/stability-ais-best-image-generating-models-now-in-amazon-bedrock/)

