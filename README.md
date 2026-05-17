# Comfy-UI-Workflow-for-upscaling
Realistic Upscaling a blurry photo of a person with identity preservation, and depth mapping.

It takes an blurry-low quality image of a person and upscales the picture, tries best to not re-imagine the features of the person, but there can be some imagination if the features themselves are blurry.
(Basically, if you can identify the person accurately just by seeing the pic, it means features are present clearly)

It uses SuPIR to upscale, and creates a new image using Nunchaku's FLux+PuLID nodes. (Hence PuLID is also used for indentity preservation)
It uses depth-anything to create the conditioning (depth map) of the final image. You need a realsitic pic of the way you want final image to be like.
