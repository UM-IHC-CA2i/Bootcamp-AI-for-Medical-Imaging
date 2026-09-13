# MedSAM2 Integration and Slice Propagation for Brain MRI Segmentation in 3D Slicer

## 1. 3D Slicer Setup
- Install the latest version of [https://www.slicer.org/](3D Slicer).
- Load2-5 brain MRIs (BraTS is a good choice).

## 2. MedSAM2 Integration
- Python Interactor in Slicer to call the MedSAM2 model.
- Or write a simple scripted module wrapping MedSAM2 inference.

## 3. Slice Propagation Practice
- Pick a few slices and run MedSAM2 (e.g., bounding box or point prompt). Adjust the settings to achieve the best performance possible.
- Then, manually or semi-automatically propagate the segmentation to neighboring slices using:
  - 3D Slicer’s built-in “fill between slices” tool in Segment Editor
  - Or simulate your own logic using simple interpolation

## 4. Evaluation
- Compare your mask against the ground truth mask using Dice Similarity Coefficient (DSC)
- Document any challenges or observations (e.g., drift, oversegmentation).

## 5. Deliverables
- Screenshots or screen recordings showing segmentation + propagation
- Code or scripts used
- Short report explaining:
  - Workflow
  - How propagation was tested
  - Quantitative results + interpretation
  - Any limitations or ideas for improvement




