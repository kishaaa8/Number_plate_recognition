# Number_plate_recognition

## Project structure
```
project-root/
├─ data/
│  ├─ images/train/        # will hold images
│  ├─ images/val/
│  ├─ labels/train/        # YOLO .txt labels
│  └─ labels/val/
├─ notebooks/
│  ├─ eda.ipynb
│  └─ train_yolo.ipynb
├─ src/
│  ├─ detector.py
│  ├─ recognizer.py
│  ├─ utils.py
│  └─ preprocess_labels.py  
├─ models/                   # trained weights
├─ requirements.txt
├─ README.md
└─ main.py
