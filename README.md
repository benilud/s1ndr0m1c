# AI-Generated Medical Images for Crouzon Syndrome Research

## Overview

This repository contains the computational resources and workflows used in our research publication on AI-generated medical imagery for Crouzon syndrome studies, published in the American Journal of Medical Genetics.

## Repository Contents

- `workflow_s1dr0m1c.json` - ComfyUI workflow configuration for generating medical imagery
- `crouzon.safetensors` - Trained model weights specific to Crouzon syndrome characteristics
- `pose.png` - Reference pose image for image generation
- `ComfyUI_00042_.png` - Example output from the AI generation pipeline

## Requirements

- [ComfyUI](https://github.com/comfyanonymous/ComfyUI) - AI image generation interface
- Compatible GPU with sufficient VRAM for model inference
- Python environment with required dependencies

## Usage

1. Install ComfyUI following the official installation instructions
2. Load the provided workflow file (`workflow_s1dr0m1c.json`) into ComfyUI
3. Ensure the model file (`crouzon.safetensors`) is placed in the appropriate models directory
4. Use the reference pose image (`pose.png`) as input for consistent generation parameters

## Citation

If you use this work in your research, please cite our publication:

```bibtex
[Article currently under review at American Journal of Medical Genetics - Citation details will be updated upon publication]
```

## Ethical Considerations

This research tool is intended for medical research and educational purposes only. Generated images should not be used for clinical diagnosis or patient care without appropriate validation and ethical oversight.

## License

This project is released under the MIT License - see the LICENSE file for details.

**Note**: For academic research purposes. Commercial use may require additional permissions.

## Contact

For questions regarding this research or the computational methods, please contact:

[Author contact information]

## Acknowledgments

We acknowledge the support of [Institution/Funding sources] in conducting this research.

---

**Note**: This repository contains research materials supporting our publication on AI-generated medical imagery. All generated content is for research purposes and should be used responsibly within appropriate ethical frameworks.
