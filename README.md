# Deep Learning-based Image Segmentation in Complex Two-Phase Flows



---

## Overview

This work proposes a deep learning-based approach for accurate segmentation of gas-liquid interfaces (bubbles) in two-phase flow images. The model utilizes a modified U-Net architecture trained on experimental data acquired from high-speed imaging of complex flow conditions.

---

## Project Structure

- `src/` – Training and inference scripts  
- `model/` – Pretrained model weights  
- `data/` – Sample frames and masks  


## Project Structure
The dataset used in this work is gathered from different works developed in the Fluid Engineering Laboratory at PUC-Rio

If you use this data in your work, please cite the following articles:

@article{FARIAS2023104381,
	title = {Characterization of interfacial waves in stratified turbulent gas-liquid pipe flow using Particle Image Velocimetry and controlled disturbances},
	journal = {International Journal of Multiphase Flow},
	volume = {161},
	pages = {104381},
	year = {2023},
	issn = {0301-9322},
	doi = {https://doi.org/10.1016/j.ijmultiphaseflow.2023.104381},
	url = {https://www.sciencedirect.com/science/article/pii/S0301932223000046},
	author = {P.S.C. Farias, L.F.A. Azevedo, I.B. {de Paula}}
}

@article{Fernandes2018,
title = {A technique for measuring ensemble-averaged, three-component liquid velocity fields in two-phase, gas–liquid, intermittent pipe flows},
journal = {Experiments in Fluids},
volume = {59},
pages = {147},
year = {2018},
issn = {1432-1114},
doi = {10.1007/s00348-018-2601-5},
url = {https://doi.org/10.1007/s00348-018-2601-5},
author = {Leonardo S. {Fernandes}, Fabio J. W. A. Martins, Luis F. A. Azevedo }
}


W.R. de Oliveira, I.B. de Paula, F.J.W.A. Martins, P.S.C. Farias, L.F.A. Azevedo,
Bubble characterization in horizontal air–water intermittent flow,
International Journal of Multiphase Flow,
Volume 69,
2015,
Pages 18-30,
ISSN 0301-9322,
https://doi.org/10.1016/j.ijmultiphaseflow.2014.10.014.
