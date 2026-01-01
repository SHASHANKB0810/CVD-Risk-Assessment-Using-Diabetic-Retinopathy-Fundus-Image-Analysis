# CVD-Risk-Assessment-Using-Diabetic-Retinopathy-Fundus-Image-Analysis
Project ID: PW25_MHR_05
Team Details
Project Guide: Dr. Mamatha H R
1) Hrithika Arun Divate PES1UG22AM070 CSE(AI ML)
2) J Vignesh PES1UG22AM074 CSE(AI ML)
3) K A Amrutha Aithal PES1UG22AM077 CSE(AI ML)
4) Shashank R Bellad PES1UG22AM150 CSE(AI ML) 

#Contents of the ZIP File and File Description
#1. Vessel segmentation code
This notebook contains the complete implementation for retinal blood vessel segmentation 
from fundus images.
Includes:
1.1 Image preprocessing steps (resizing, normalization, contrast enhancement).
1.2 Deep learning model architecture used for vessel segmentation (VGG16 based Unet 
model).
1.3 Training and validation pipeline.
1.4 Prediction/inference code for segmenting vessels from unseen fundus images.
1.5 The trained vessel segmentation model is saved as:
vgg16_unet400_DREnhanced_model.keras

#2. Optic segmentation code
This notebook contains code for optic disc segmentation, which is required to exclude the 
optic disc region during vessel analysis.
Includes:
2.1 Preprocessing of fundus images.
2.2 Model architecture and training code for optic disc segmentation.
2.3 Inference code to generate optic disc masks.
2.4 The trained optic disc segmentation model is saved as: efficientnetb3_unet_idrid.h5.

#3. Optic segmentation code
This notebook contains code for optic disc segmentation, which is required to exclude the 
optic disc region during vessel analysis.
Includes:
2.1 Preprocessing of fundus images.
2.2 Model architecture and training code for optic disc segmentation.
2.3 Inference code to generate optic disc masks.
2.4 The trained optic disc segmentation model is saved as: efficientnetb3_unet_idrid.h5.

#4. Complete code (Including AVR calculation)
This file integrates all individual modules into a single end-to-end pipeline.
Includes:
3.1 Loading of trained vessel and optic disc segmentation models.
3.2 Vessel segmentation and optic disc removal.
3.3 Extraction of arterioles and venules.
3.4 Calculation of: AVR (Arteriolar-to-Venular Ratio)
3.5 Batch processing of the entire dataset.
5. ReadME file
