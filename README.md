# ASR with NeMo

[Neural Modules (NeMo)](https://developer.nvidia.com/nvidia-nemo) is a toolkit developed by NVIDIA for creating Conversational AI applications, with prebuilt modules for automatic speech recognition among many others. In this repository, you can find 2 main notebooks.

## 1. NeMo ASR Simple Training

This is a simple notebook that follows [part 1 of NeMo's tutorial](https://github.com/NVIDIA/NeMo/blob/master/examples/asr/notebooks/1_ASR_tutorial_using_NeMo.ipynb), where we train on a small sample of the AN4 dataset. The purpose is to get used and practice in training an end-to-end ASR model with the NeMo toolkit.

## 2. NeMo ASR Pretrained Model

The next notebook utilises the Jasper model that NVIDIA pretrained over several datasets, including [Singapore's National Speech Corpus](https://www.imda.gov.sg/programme-listing/digital-services-lab/national-speech-corpus). In this notebook, we attempt to load in the pretrained model and run inference on a set of local sample clips. We will also look into using a language model to improve our final results. 

## Citations

```
@misc{nemo2019,
    title={NeMo: a toolkit for building AI applications using Neural Modules},
    author={Oleksii Kuchaiev and Jason Li and Huyen Nguyen and Oleksii Hrinchuk and Ryan Leary and Boris Ginsburg and Samuel Kriman and Stanislav Beliaev and Vitaly Lavrukhin and Jack Cook and Patrice Castonguay and Mariya Popova and Jocelyn Huang and Jonathan M. Cohen},
    year={2019},
    eprint={1909.09577},
    archivePrefix={arXiv},
    primaryClass={cs.LG}
}
```
