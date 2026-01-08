# Histopathologic Cancer Detection

## Project Overview
This project uses a Convolutional Neural Network (CNN) to detect metastatic cancer in histopathologic scans of lymph node sections.

## Dataset
- **Competition**: [Histopathologic Cancer Detection](https://www.kaggle.com/c/histopathologic-cancer-detection)
- **Images**: 96x96 pixel pathology images
- **Task**: Binary classification (Cancer vs No Cancer)

## Model Architecture
- Custom CNN with 4 convolutional blocks (32→64→128→256 filters)
- Batch Normalization and Dropout for regularization
- Binary Cross-Entropy loss with Adam optimizer

## Results
| Metric | Score |
|--------|-------|
| Public AUC | 0.9607 |
| Private AUC | 0.9498 |

## Leaderboard
![Leaderboard Screenshot](images/leaderboard.png)

## Files
- `cancer_detection.ipynb` - Main notebook with all code
- `submission.csv` - Kaggle submission file

## Requirements
- Python 3.8+
- TensorFlow 2.x
- OpenCV
- NumPy, Pandas, Matplotlib, Seaborn

## Author
JinchenYu61
```


