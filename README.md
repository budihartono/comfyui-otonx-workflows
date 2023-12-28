# Otonx's ComfyUI Workflows

This repository holds workflows crafted for generating AI images through Stable Diffusion using ComfyUI. The workflows are arranged for clarity and ease of use.

## Latest Update: 

`otonx_sdxl_base+lora+controlnet+refiner+upscale+facedetail_workflow`

This workflow incorporates SDXL models with a refiner. Users have the option to add LoRAs, ControlNet models or T21 Adapters, and an Upscaler. The ControlNet / T21 section is implemented as a Switch logic, allowing users to select between ControlNet models or T21 adapters. After the refiner KSampler, the users have the options to do face fix/detailing.

`otonx_sdxl_base+refiner+lcmlora+facedetailer_workflow`

My attempt to use LCM Lora with SDXL models.

### Key Components:

- **ComfyUI**: An intuitive interface for crafting AI art pipelines.
- **Stable Diffusion**: A technique for AI art generation, enhanced by SDXL models.
- **SDXL Models**: A two-step process with a base model and a refiner model.
- **ControlNet Models**: Extend diffusion models to allow conditional inputs.
- **T21 Adapters**: Enable text-to-image conversion efficiently.
- **LoRAs and Upscalers**: Additional modules for refining and upscaling images.

### Workflow Details:

- **Aspect Ratio**: The aspect ratio recommended for the Stable Diffusion XL model can be set.
- **LoRA Stack**: Multiple LoRAs can be used through the LoRA Stack.
- **Custom Nodes**: A set of custom nodes have been created and are utilized in this project. They can be found at [comfyui_otonx_nodes](https://github.com/budihartono/comfyui_otonx_nodes).

### Getting Started

1. Clone the repository.
2. Navigate to the `workflows` directory to access workflow files.
3. Load the desired workflow file in ComfyUI.
4. Modify the workflow nodes and groups as needed.
5. Start generating AI art.