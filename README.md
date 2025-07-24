# BreastSegNet

This repository hosts the pretrained weights used in the paper  
**[BreastSegNet: Multi-label Segmentation of Breast MRI](https://www.arxiv.org/abs/2507.13604)**.  
The training and testing datasets used in this work will be released upon approval.  
Please stay tuned for future updates.
We welcome feedback and contributions from the community.

## Pretrained Weights

The pretrained `nnUNet` weights for BreastSegNet are available on [Google Drive](https://drive.google.com/file/d/1o9lcFrPDA2UGNolvsyvzOE4YvNFojz1q/view?usp=drive_link).

## Dependencies

Please follow the official [`nnUNet` installation instructions](https://github.com/MIC-DKFZ/nnUNet/blob/master/documentation/installation_instructions.md) to set up all required dependencies. Ensure that `nnUNet` is correctly installed and the environment variables are properly configured.

## Inference

To run inference with BreastSegNet, follow the [nnUNet inference tutorial](https://github.com/MIC-DKFZ/nnUNet/blob/master/documentation/how_to_use_nnunet.md), specifically the **Run Inference** section.

## Citation

If you find this work helpful, please cite our paper:

```bibtex
@misc{li2025breastsegnet,
      title={BreastSegNet: Multi-label Segmentation of Breast MRI}, 
      author={Qihang Li and Jichen Yang and Yaqian Chen and Yuwen Chen and Hanxue Gu and Lars J. Grimm and Maciej A. Mazurowski},
      year={2025},
      eprint={2507.13604},
      archivePrefix={arXiv},
      primaryClass={eess.IV},
      url={https://arxiv.org/abs/2507.13604}, 
}
