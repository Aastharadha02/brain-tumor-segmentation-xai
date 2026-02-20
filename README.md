i have these# brain-tumor-segmentation-xai
U-Net based brain tumor segmentation on MRI slices with explainable AI using Grad-CAM. Includes qualitative analysis, Dice/IoU evaluation, and visual overlays.
# Brain Tumor Segmentation with U-Net and Grad-CAM (XAI)

This repository contains an implementation of a U-Net based deep learning model for brain tumor segmentation on MRI slices. The project also integrates Grad-CAM to provide explainable AI (XAI), highlighting regions that influenced the model’s predictions.

##  Features
- U-Net architecture for 2D MRI tumor segmentation  
- Handles class imbalance using sampling and loss design  
- Qualitative visualization of predictions (overlays on MRI)  
- Explainability using Grad-CAM heatmaps  
- Evaluation using Dice and IoU metrics  

##  Dataset
- BraTS (Brain Tumor Segmentation) dataset (processed H5 slices)
- Due to dataset size constraints, a subset of samples is used for demonstration.
- The dataset is **not included** in this repository.

##  Results
- The model localizes tumor regions on MRI slices.
- Grad-CAM highlights salient regions influencing segmentation decisions.
- Performance is limited by dataset size and severe class imbalance.
- Qualitative results include successful cases and failure cases for honest evaluation.

##  How to Run
1. Open the notebook in Google Colab  
2. Upload the dataset to Google Drive  
3. Run all cells in order  

##  Limitations
- Limited training data  
- 2D slice-based segmentation  
- Single MRI modality  
- Not intended for clinical use  

##  Future Work
- 3D U-Net  
- Multi-modal MRI inputs (T1, T1c, T2, FLAIR)  
- Larger training dataset  
- Improved post-processing  

##  License
This project is licensed under the MIT License.
