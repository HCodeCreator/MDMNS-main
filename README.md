# MDMNS: Modal-aware Diffusion-enhanced with Multi-level Negative Sampling for Multimodal-based Recommendation

## 📝 Environment

We develop our codes in the following environment:

- python==3.9.13
- numpy==1.23.1
- torch==1.11.0
- scipy==1.9.1

## 👉 Code Structure

```
.
├── README.md
├── Main.py
├── Model.py
├── Params.py
├── DataHandler.py
├── Utils
│   ├── TimeLogger.py
│   └── Utils.py
├── figures
│   ├── model.png
│   ├── dataset.png
│   └── performance.png
└── Datasets
    ├── tiktok
    │   ├── trnMat.pkl
    │   ├── tstMat.pkl
    │   ├── valMat.pkl
    │   ├── audio_feat.npy
    │   ├── image_feat.npy
    │   └── text_feat.npy
    ├── baby.zip
    └── README.md
```

## 📚 Datasets

<img src="./figures/dataset.png" style="zoom:100%;" />

## Acknowledgements
We are particularly grateful to the authors of DiffMM, as parts of our code implementation were derived from their work. We have cited the relevant references in our paper.

Click to browse DiffMM: https://dl.acm.org/doi/abs/10.1145/3664647.3681498
