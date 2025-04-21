# Waste Classification (12 Classes)

A complete pipeline for classifying household waste into 12 categories using MobileNetV2.

## Dataset
- [Garbage Classification (Kaggle)](https://www.kaggle.com/datasets/mostafaabla/garbage-classification)

## Steps
1. Clone the repo  
2. Place the dataset in `./garbage_classification/`  
3. Run `Project.ipynb` step by step  
4. Final model saved as `final_mobilenet_model.h5`

## Requirements
pip install -r requirements.txt

## Output
- Accuracy: **95%**
- Model: **MobileNetV2**
- Files:
  - `deduplicated_dataset/`
  - `final_filtered_dataset/`
  - `split_dataset/`
  - `final_unseen_dataset/`
  - `final_mobilenet_model.h5`
