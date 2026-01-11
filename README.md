# Deep Learning-based Image Segmentation in Complex Two-Phase Flows



---

## Overview

This work proposes a deep learning-based approach for accurate segmentation of gas-liquid interfaces (bubbles) in two-phase flow images. The model utilizes a modified U-Net architecture trained on experimental data acquired from high-speed imaging of complex flow conditions.

---

## Project Structure

- `src/` – Training and inference scripts  
- `models/` – Pretrained model weights  
- `data/` – Sample frames and masks  

---


## Run inference
python src/inference.py --input data/sample_input/frame_001.png --output results/
