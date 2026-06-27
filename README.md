"# -Person-Re-Identification-using-Deep-Learning" 
# Person Re-Identification using Deep Learning

## Overview

This project implements a **Person Re-Identification (Person Re-ID)** system using deep learning techniques. Person Re-ID aims to identify the same individual across images captured by different surveillance cameras despite changes in viewpoint, illumination, pose, and background.

The model is trained on the **Market-1501** dataset and learns discriminative feature embeddings to match people across multiple camera views.

---

## Features

- Deep learning-based Person Re-Identification
- Trained on the Market-1501 dataset
- Feature embedding extraction
- Query-Gallery matching
- Rank-based retrieval
- Evaluation using Rank-k Accuracy and mAP

---

## Dataset

**Market-1501**

- 1,501 identities
- 12,936 training images
- 3,368 query images
- 19,732 gallery images
- Images captured from 6 different cameras

Dataset Link:
https://www.kaggle.com/datasets/pengcw1/market-1501

---


## Installation

Clone the repository

```bash
git clone https://github.com/yourusername/Person-ReID.git
```

Move into the project directory

```bash
cd Person-ReID
```

Install the required packages

```bash
pip install -r requirements.txt
```

---

## Training

Run

```bash
python train.py
```

---

## Testing

Run

```bash
python test.py
```

---

## Evaluation Metrics

The model is evaluated using:

- Mean Average Precision (mAP)
- Rank-1 Accuracy
- Rank-5 Accuracy
- Rank-10 Accuracy

---

## Technologies Used

- Python
- PyTorch
- NumPy
- OpenCV
- Torchvision
- Matplotlib
- Scikit-learn

---

## Applications

- Smart Surveillance
- Security Systems
- Missing Person Search
- Multi-Camera Tracking
- Forensic Investigation

---

## Future Improvements

- Improve model accuracy using attention mechanisms
- Support real-time inference
- Deploy as a web application
- Train on larger Person Re-ID datasets
- Optimize for edge devices


