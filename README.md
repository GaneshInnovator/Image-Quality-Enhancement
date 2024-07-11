# Image-Quality-Enhancement


Enhanced Super-Resolution Generative Adversarial Networks (ESRGAN) implementation.


## Quick Test

### Step 1: Install Dependencies

Ensure you have the following dependencies installed:

- Python 3
- PyTorch >= 1.0 (CUDA version >= 7.5 if installing with CUDA. More details [here](https://pytorch.org/get-started/previous-versions/))
- Python packages: `numpy` and `opencv-python`

You can install the required Python packages using pip:
```
pip install numpy opencv-python
```
### Step 2: Clone the Repository
```
git clone https://github.com/GaneshInnovator/Image-Quality-Enhancement.git
cd Image-Quality-Enhancement
```
### Step 3: Prepare Input Images

Place your own low-resolution images in the ./LR folder. There are four sample images (baboon, comic, hqdefault and images) provided.

### Step 4: Download Pretrained Models

Download pretrained models from Google [Drive](https://drive.google.com/drive/folders/1Lwd_RRcn5NGEARxKSi54LlWAkIvvDiTx?usp=sharing). Place the models in the ./models folder. We provide two models with high perceptual quality and high PSNR performance.

### Step 5: Run the Test
```
python test.py
```

## Results

![baboon](https://github.com/GaneshInnovator/Image-Quality-Enhancement/assets/128501278/90a1cc91-fba3-49aa-941e-effb7e7499e1)
