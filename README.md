# Segmentation of Cornea Cells using U-Net Architecture
Segmentation of microscopic images of corneal endothelium cells as cell interior, cell border, or background.
- Segmented the microscopic images of corneal endothelium cells and labeled each pixel as cell interior, cell border, or background.
- Developed and trained a 32x32 image patch-segmenting 24-layer U-Net model to an accuracy of 80% in training and 72% in validation.
- Reconstructed test segments by applying a sliding window operation on 500x500 test images while employing a 32x32 U-Net model.
- Plotted the ROC Curves and got an area under the curve (AUC) of 0.869 with the training set patches and 0.839 with the testing set patches.

**NOTE: Open "Final_Project.ipynb" to see the full training, testing & evaluation processes.**

## The Network Architecture:
![U-Net_Network](/screenshots/network.jpg?raw=true "U-Net Network")

## Segmentation & Reconstruction Quality:
![Segmentation_Quality](/screenshots/segmentation_quality.png?raw=true "Segmentation Quality")

## Segmented 32x32 Patches output from the network:
![Segmented_Patches](/screenshots/segmented_patches.png?raw=true "Segmented Patches")

## ROC Curves:
### Training:
![ROC_Training](/screenshots/ROC_Curve_training.png?raw=true "ROC Training")
### Testing:
![ROC_Testing](/screenshots/ROC_Curve_testing.png?raw=true "ROC Testing")
