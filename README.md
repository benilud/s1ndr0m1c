# AI-Generated Medical Images for Genetic Syndromes Research

## Overview

This repository contains the computational resources and workflows used in our research publication on AI-generated medical imagery for various genetic syndromes, published in the American Journal of Medical Genetics.

## Repository Contents

- `workflow_s1dr0m1c.json` - ComfyUI workflow configuration for generating medical imagery
- `models/` - Directory containing trained model weights for different genetic syndromes:
  - `apert.safetensors` - Apert syndrome (AS, OMIM #101200)
  - `charge.safetensors` - CHARGE syndrome (OMIM #214800)
  - `crouzon.safetensors` - Crouzon-Pfeiffer syndrome (CPS, OMIM #123500 and #101600)
  - `guion_almeida.safetensors` - Mandibulofacial Dysostosis with Microcephaly (MFDM, OMIM #610536)
  - `kabuki.safetensors` - Kabuki syndrome (KS, OMIM #147920 and #300867)
  - `muenke.safetensors` - Muenke syndrome (MS, OMIM #602849)
  - `nager.safetensors` - Nager Acrofacial Dysostosis (NAFD, OMIM #154400)
  - `Saerthre_chotzen.safetensors` - Saethre-Chotzen syndrome (SCS, OMIM #101400)
  - `silver_russel.safetensors` - Silver-Russell syndrome (SRS, OMIM #180860)
  - `treacher_collins.safetensors` - Treacher Collins syndrome (TCS, OMIM #154500)
- `pose.png` - Reference pose image for image generation
- `ComfyUI_00042_.png` - Example output from the AI generation pipeline

## Requirements

- [ComfyUI](https://github.com/comfyanonymous/ComfyUI) - AI image generation interface
- Compatible GPU with sufficient VRAM for model inference
- Python environment with required dependencies

## Usage

1. Install ComfyUI following the official installation instructions
2. Load the provided workflow file (`workflow_s1dr0m1c.json`) into ComfyUI
3. Place the desired syndrome model file from the `models/` directory into ComfyUI's models directory
4. Use the reference pose image (`pose.png`) as input for consistent generation parameters
5. Select the appropriate model based on the genetic syndrome you wish to study

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
