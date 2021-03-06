# COVID-19 Detection from Lung CT-Scan Images using Transfer Learning Approach
<a href="https://doi.org/10.1088/2632-2153/abf22c"><img src="https://img.shields.io/badge/IOP%20Science-Publisher-blue"/></a>
<a href="https://iopscience.iop.org/article/10.1088/2632-2153/abf22c"/><img src="https://img.shields.io/badge/DOI-10.1088%2F2632--2153%2Fabf22c-blue"/></a>
<a href="https://creativecommons.org/licenses/by/3.0/"/><img src="https://img.shields.io/badge/License-CC%20BY%203.0-lightgrey"/></a>
<br>
<img alt="Python" src="https://img.shields.io/badge/python-%2314354C.svg?style=for-the-badge&logo=python&logoColor=white"/> <img alt="NumPy" src="https://img.shields.io/badge/numpy-%23013243.svg?style=for-the-badge&logo=numpy&logoColor=white" /> <img alt="Pandas" src="https://img.shields.io/badge/pandas-%23150458.svg?style=for-the-badge&logo=pandas&logoColor=white" /> <img alt="Jupyter" src="https://img.shields.io/badge/Jupyter-%23F37626.svg?style=for-the-badge&logo=Jupyter&logoColor=white" />
<img alt="TensorFlow" src="https://img.shields.io/badge/TensorFlow-%23FF6F00.svg?style=for-the-badge&logo=TensorFlow&logoColor=white" />
<img alt="OpenCV" src="https://img.shields.io/badge/opencv-%23white.svg?style=for-the-badge&logo=opencv&logoColor=white"/>
<img alt="Keras" src="https://img.shields.io/badge/Keras-%23D00000.svg?style=for-the-badge&logo=Keras&logoColor=white"/>

### Abstract
From the onset of 2020, Coronavirus disease (COVID-19) has rapidly accelerated worldwide into a stage of a severe pandemic. COVID-19 has infected more than 29 million people and caused more than 900 thousand deaths. Being highly contagious, it causes community transmission explosively. Thus, health care delivery has been disrupted and compromised by lack of testing kits. The COVID-19 infected patient shows severe acute respiratory syndrome. Meanwhile, the scientific community has been on a roll implementing Deep Learning techniques to diagnose COVID- 19 based on lung CT-scans, as computed tomography (CT) is a pertinent screening tool due to its higher sensitivity for recognizing early pneumonic changes. However, large dataset of CT-scan images are not publicly available due to privacy concerns and obtaining very accurate model becomes difficult. Thus to overcome this drawback, transfer learning pre-trained models are used to classify COVID-19 (+ve) and COVID-19 (-ve) patient in the proposed methodology. Including pre-trained models (DenseNet201, VGG16, ResNet50V2, MobileNet) as backbone, a deep learning framework is developed and named as KarNet. For extensive testing analysis of the framework, each model is trained on original (i.e., non-augmented) and manipulated (i.e., augmented) dataset. Among the four pre-trained models of KarNet, the one with DenseNet201 illustrated excellent diagnostic ability with an AUC score of 1.00 and 0.99 for models trained on non-augmented and augmented data set respectively. Even after considerable distortion of images (i.e., augmented dataset) DenseNet201 gained an accuracy of 97% on the testing set, followed by ResNet50V2, MobileNet, VGG16 (96%, 95% and 94% respectively).

### Dataset
 <img src="Figures/FIGURE 1 (a).jpg" hspace="10"/><img src="Figures/FIGURE 1 (b).jpg"/>

### Architecture
<img src="Figures/FIGURE 2.jpg" height="500" width="550" align="center" />

## Citation

Please cite my research paper as:
```
ARPITA HALDER et al 2021 Mach. Learn.: Sci. Technol. https://doi.org/10.1088/2632-2153/abf22c
```
*** Code will be uploaded soon ***
