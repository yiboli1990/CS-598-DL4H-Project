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
   
2. **Install Python**: Ensure that Python 3.8 or above is installed on your machine.

3. **Install Dependencies**:
   ```bash
   pip install -r requirements.txt









   
