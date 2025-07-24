#  3D Reconstruction of Fibula and Tibia 
Using Mimics This project shows how I created 3D models of the fibula and tibia bones using medical CT scan images in Materialise Mimics software.
 --- 
# Project Folders -
 dicom_files/ – Due to size limitations, the original DICOM files are not included here.

You can download the full dataset from this link:  
[Download DICOM files](https://drive.google.com/drive/folders/18yY5gkLlyTd0PESGFxgUD1B6sDEVFVzT?usp=drive_link)  
 screenshots/ – Images showing each step of the process   
 stl/ – Final 3D bone models saved as .stl files   
--
# Steps I Followed
 1. Imported DICOM files into Mimics  
 2. Used thresholding to separate the bones  
 3. Cropped the area I wanted to work on   
 4. Used region growing to select bone parts better  
 5. Cleaned the mask and removed extra parts   
 6. Used polylines to improve the shape of the mask   
 7. Made the 3D models of fibula and tibia  
 ---
 # Screenshots 
 Step 1 – Import DICOM| Step1_import_dicom.png 

  Step 2 – Thresholding  Step2_thresholding.png 

  Step 3 – Crop Masking  Step3_crop_masking.png 

  Step 4 – Region Growing  Step4_Region_growing.png 

 Step 5 – Edit Mask  Step5_edit_masking.png 

 Step 6 – Polylines  Step6_using_polylines.png 

 Step 7 – 3D Calculation |Step7_calculating_3D_from.png  

All files are saved in the screenshots/ folder. 
---
 # Final 3D Models 
 fibula_model.stl   
 3D model of the fibula   
 tibia_model.stl  
 3D model of the tibia   
---
 # Extra Info
  This is a project for bone segmentation and 3D modeling   
 Software used:  
  Materialise Mimics v10.01
