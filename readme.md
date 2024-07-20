# ComfyUI-Mixed-Utils: Basic Utilities

This repository, **ComfyUI-Mixed-Utils**, contains basic utilities and styles for ComfyUI, created to share with others.

# ComfyUI-Easy-Use Additional Styles

## Installation

1. Install [ComfyUI-Easy-Use](https://github.com/yolain/ComfyUI-Easy-Use) using the [ComfyUI Manager](https://github.com/ltdrdata/ComfyUI-Manager).

2. Copy `ComfyUI-Mixed-Utils/styles/mixed_styles.json`and kolors_styles.json to your local ComfyUI directory:

    ```
    \custom_nodes\ComfyUI-Easy-Use\styles\
    ```

3. Copy all images from `ComfyUI-Mixed-Utils/google_styles/samples/` (excluding the folder itself) to:
    
    ```
    \custom_nodes\ComfyUI-Easy-Use\styles\samples\
    ```

## Usage

![mixed_styles](assets/images/styles.png)

To increase/decrease the style's weight

![mixed_concat_styles](assets/images/styles_concat.png)

## Notes

1. mixed_styles: The sample images were generated using the [Pixart-Sigma Checkpoint](https://huggingface.co/PixArt-alpha/PixArt-Sigma-XL-2-1024-MS). Please be aware that results may vary when using these styles with different models or configurations. The styles follow this naming convention: Category__Style_Name. However, some exceptions apply to styles I've incorporated from SAI and other external sources.

2. kolors_styles are from [modelscope/Kolors_awesome_prompts](https://modelscope.cn/datasets/modelscope/Kolors_awesome_prompts/dataPeview) for use with the [Kolors model](https://huggingface.co/Kwai-Kolors/Kolors) model.