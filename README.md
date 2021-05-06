# Automatic-License-Plate-Recognition-System-for-Distorted-Images
### Conjunction of ALPR with SRGAN

The ALPR system for distorted images augments the efficiency and accuracy of the Traditional ALPR system by refining 
the quality and resolution of the localized images, unlike the traditional system where the localized plate was directly fed to OCR.


#### Model Architecture:
<p align="center">
<img align="center" src="images/system_model.jpg" alt="Architecture of ALPR system for distorted images">
</p>

### Methodology:
1. License Plate Detection and Localization- Using WPOD-NET
2. Super Resolution - Using SRGAN
3. Character Segmentation - Using contour-based approach
4. Character Recognition - Using SVM

