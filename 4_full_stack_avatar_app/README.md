# 4 - Full Stack Avatar App

## Personalized generative AI Avatars
The application is based on this repo:

> - **[aws-samples/comfyui-personalized-generative-ai-avatars-app](https://github.com/aws-samples/comfyui-personalized-generative-ai-avatars-app)**




### Avatar App Workflow running on ComfyUI
!["ComfyUI Avatar User Experience"](/static/avatar_app/comfyui_avatar_workflow.png)*workflow included in png.  

### Avatar App look and feel (it's a video)
[![Avatar App UX](/static/avatar_app/avatar-app-ux.jpg)](/static/avatar_app/avatar-app-ux.mp4)


### Avatar Gallery look and feel
!["ComfyUI Avatar UI"](/static/avatar_app/avatar-gallery-ui.jpg)


### Application Features
- File Upload component
    - on mobile: photos can be choosen from gallery or depending on OS / Manufacturer also directly taken from the camera
    - on desktop: the user is able to upload files from their file system. Webcam feature is coded, but commented out per default.
- Amazon Rekognition integrated for face detection. If user doesn't upload an image with a face, then the options of generating an avatar are not available.
- Describe Image: Invokes Amazon Bedrock with Anthropic Haiku LLM to describe the uploaded image
- Customization options:
    - Presets provided for Sci-fi heros, EURO 2024 soccer players and other Sports characters
    - Customization options for influencing Avatar outputs (gender, hair length an color, skine tone, face expression)
- Image Share button for sharing avatars to Avatar Gallery (see below)
- Amazon Rekognition integrated for moderating output images, i.e. no Image is shown to the user if containing nudity, drugs, violence.
- Avg. Avatar generation takes 4-7 seconds.
