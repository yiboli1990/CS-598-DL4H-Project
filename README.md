# CS-598 Deep Learning for Healthcare Project

This repository contains all the necessary code and documentation for the CS-598 Deep Learning for Healthcare project focused on predicting intraoperative hypotension using physiological waveforms. The project utilizes machine learning techniques to analyze arterial blood pressure (ABP), electroencephalogram (EEG), and electrocardiogram (ECG) data.

## Project Overview

### Background
Intraoperative hypotension (IOH) is a significant perioperative issue associated with increased risks of acute kidney injury, myocardial injury, and other complications. This project aims to develop a predictive model that can forecast IOH events effectively, thereby enhancing patient outcomes through timely interventions.

### Objectives
- To predict the occurrence of intraoperative hypotension using machine learning models.
- To evaluate the effectiveness of different physiological waveforms in predicting IOH.

## Repository Structure

- `README.md`: Provides an overview of the project along with setup and execution instructions.
- `DL4H_Team_172.ipynb`: The primary Jupyter notebook containing all data analyses, model training, and evaluation code.
- `requirements.txt`: Specifies the Python packages required to replicate the analysis environment and run the notebook.
- `model_checkpoint.h5`: Pretrained model checkpoint for the comprehensive model utilizing ABP, EEG, and ECG waveforms.
- `abp_eeg_model_checkpoint.h5`: Pretrained model checkpoint for the simplified model using only ABP and EEG data.

## Environment Setup

1. **Clone the Repository**:
   ```bash
   git clone https://github.com/yiboli1990/CS-598-DL4H-Project.git
   cd CS-598-DL4H-Project

2. **Download Test Data**: The test datasets are too large to host directly on GitHub and are instead available on Google Drive. You must download these files before running the notebook to ensure it functions correctly. Use the following commands to download the x_test and y_test datasets:
   ```bash
   wget --no-check-certificate 'https://drive.google.com/uc?export=download&id=11ECqyTTMq8aGqw0g9RQFH6Fm-Mrn7TYm' -O x_test.csv
   wget --no-check-certificate 'https://drive.google.com/uc?export=download&id=18gxmUysPZK3sp6CbRR5HIZjmYUuQYe8b' -O y_test.csv

2. **Install Python**: Ensure that Python 3.8 or above is installed on your machine.

3. **Install Dependencies**:
   ```bash
   pip install -r requirements.txt









   
