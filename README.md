# CropSensAI 🌾

This repo contains my hackathon solution for crop identification.

## Contents
- `notebook.ipynb` → full Kaggle notebook with preprocessing, training, evaluation, and predictions.
- (Optional) `checkpoints/` → model weights if needed.
- (Optional) `test_predictions/` → saved predictions.

## How to run
1. Open `notebook.ipynb` in Kaggle.
2. Run all cells.
3. Outputs (predictions + checkpoints) will be saved automatically.

## Features implemented
✔️ 12-band multispectral data  
✔️ Dice loss with class weighting  
✔️ Prithvi backbone + UperNet decoder  
✔️ Baseline UNet (ResNet18) comparison  
✔️ Augmentations (D4 rotations)  
✔️ Evaluation: Accuracy, IoU, F1  

## Notes
- Ignore index handled properly (`255`).  
- Final submission prepared as `final_submission.zip`.  

---
