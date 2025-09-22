# Task-1: Medical Image Segmentation

## 📌 Project Overview
This project focuses on *medical image segmentation* of three organs:  
- *Eye*  
- *Kidney*  
- *Pancreas*  

For each organ, three anatomical parts will be segmented using *three AI models from different families*.  
The project also implements evaluation metrics to assess segmentation quality.

---

## 🧩 Organs & Parts
- *Eye*: [Part 1], [Part 2], [Part 3]  
- *Kidney*: [Part 1], [Part 2], [Part 3]  
- *Pancreas*: [Part 1], [Part 2], [Part 3]  

---

## 🤖 Models
We are applying three models from different AI families:  
1. *Model 1* → (e.g., U-Net, CNN family)  
2. *Model 2* → (e.g., Vision Transformer, Transformer family)  
3. *Model 3* → (e.g., Random Forest, ML family)  

---

## 📊 Evaluation Metrics
We will evaluate segmentation performance using:  
- *Dice Coefficient*  
- *Intersection over Union (IoU)*  
- *Pixel-wise Accuracy*

---

## ⚙ Environment Setup
We use *Conda* to manage the environment.  

### Create Environment
```bash
conda env create -f environment.yml
conda activate medseg

## Setting up the Environment

1. Create the conda environment:
   ```bash
   conda env create -f environment.yml
