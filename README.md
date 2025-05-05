# ML Apprentice Take Home Assessment

## Overview
This project demonstrates a multi-task learning model based on a pre-trained DistilBERT encoder.  
The model handles two tasks simultaneously:
- Task A: Topic classification (Finance/Tech, Health/Lifestyle, Entertainment/Sports)
- Task B: Sentiment classification (Positive/Negative)

## Structure
- Built a basic sentence transformer with mean pooling.
- Extended it to multi-task learning with two separate classifier heads.
- Simulated training with a small custom dataset.
- Computed loss and training accuracy for both tasks.
- Designed a simple, reproducible pipeline with Docker support (optional).

---

## Instructions to Run

### Without Docker
Simply open `ML_Assessment.ipynb` in any Jupyter Notebook environment (Colab, Jupyter Lab, etc.) and run the cells sequentially.

### With Docker (Optional Bonus)

To run inside Docker:

1. Build the Docker image:
   ```bash
   docker build -t ml-apprentice .
