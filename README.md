# PCB Defects Detection Using YOLO11n

I used YOLO11n for this project, the dataset used is [this](https://www.kaggle.com/datasets/akhatova/pcb-defects).


Dataset consists of 6 labels:

- Missing Hole
- Mouse Bite
- Open Circuit
- Short
- Spur
- Spurious Copper

# Installation

- `pip install -r ultralytics/examples YOLOv8-Action-Recognition/requirements.txt`

# To Run the project
### For Apple Silicons
- `python main_apple_silicon.py`

### For PCs/Google Collab
- `python main_pc.py`

# Results from Google Collab

### Confusion Matrix Normalized
![Confusion Matrix Normalized](results_google_collab/confusion_matrix_normalized.png)

### F1 Curve
![F1 Curve](results_google_collab/F1_curve.png)

### PR Curve
![PR Curve](results_google_collab/PR_curve.png)

### Results
![Results](results_google_collab/results.png)

# Testing

### Actual
![Labeled](results_google_collab/val_batch1_labels.jpg)

### Predicted
![Predicted](results_google_collab/val_batch1_pred.jpg)