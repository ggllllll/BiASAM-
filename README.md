# :page_facing_up: BiASAM: Bidirectional-attention guided Segment Anything Model for Very Few-shot Medical Image Segmentation

<p align="center"><img src="figures/1.png" width="90%"></p>

### Dependency Preparation

```shell
cd BiASAM
# Python Preparation
conda create -n BiASAM python=3.10
activate BiASAM
# It is recommended to use the conda installation on the Pytorch website https://pytorch.org/
pip install -r requirements.txt
```

### Model Training

```shell
# Model Train
# Please set the path of training image, training label in Train.py file.
python Train.py
```

### Citation ✏️ 📄

If you find this repo useful for your research, please consider citing the paper as follows:

```
@article{zhou2024biasam,
  title={Biasam: Bidirectional-attention guided segment anything model for very few-shot medical image segmentation},
  author={Zhou, Wei and Guan, Guilin and Cui, Wei and Yi, Yugen},
  journal={IEEE Signal Processing Letters},
  year={2024},
  publisher={IEEE}
}
```
