# Image-Quality-Enhancement

# ESRGAN

Enhanced Super-Resolution Generative Adversarial Networks (ESRGAN) implementation.

## Table of Contents

- [Quick Test](#quick-test)
- [Dependencies](#dependencies)
- [Test Models](#test-models)

## Quick Test

### Step 1: Install Dependencies

Ensure you have the following dependencies installed:

- Python 3
- PyTorch >= 1.0 (CUDA version >= 7.5 if installing with CUDA. More details [here](https://pytorch.org/get-started/previous-versions/))
- Python packages: `numpy` and `opencv-python`

You can install the required Python packages using pip:

```bash
pip install numpy opencv-python

### **Step 2: Clone the repository**

```bash
git clone https://github.com/xinntao/ESRGAN
cd ESRGAN

### Step 3: Prepare Input Images

Place your own low-resolution images in the ./LR folder. There are four sample images (baboon, comic, hqdefault and images) provided.

### Step 4: Download Pretrained Models

Download pretrained models from Google Drive. Place the models in the ./models folder. We provide two models with high perceptual quality and high PSNR performance (see model list).

### Step 5: Run the Test

```bash
python test.py

