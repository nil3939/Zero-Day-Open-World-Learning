# Zero-Day Attack Detection with Open-World Learning

A machine learning framework for detecting previously unseen cyberattacks using **Open-Set Recognition, Weighted Ensemble Learning, and Continual Learning**.

## Overview

Traditional intrusion detection systems assume that all attack classes are known during training. This project explores an **Open-World Learning** approach where the model can identify attacks that were not seen during training as **unknown attacks**.

### Key Features

* Open-World Attack Detection
* Unknown / Zero-Day-like Attack Detection
* Open-Set Recognition
* Weighted Ensemble Learning
* Novel Attack Identification
* Continual Learning
* Known vs Unknown Attack Classification
* CIC-IDS2017-based evaluation

## Workflow

```text
Network Traffic
      ↓
Data Preprocessing
      ↓
Known-Class Training
      ↓
Multiple ML Models
      ↓
Weighted Ensemble
      ↓
Open-Set Rejection
      ↓
 ┌───────────┬────────────┐
 ↓           ↓
Known      Unknown
 ↓           ↓
Class      Novel Attack
Detection    Detection
              ↓
       Continual Learning
```

## Dataset

The primary dataset used is **CIC-IDS2017**, containing benign traffic and multiple network attack categories.

The experiments create an open-world scenario by training on selected attack classes and testing with previously unseen attack classes.

## Technologies

* Python
* Jupyter Notebook
* NumPy
* Pandas
* Scikit-learn
* Matplotlib
* Machine Learning
* Cybersecurity

## Evaluation Metrics

The project evaluates:

* Accuracy
* Precision
* Recall
* F1-Score
* Unknown Attack Detection Rate
* AUROC
* Open-Set Recognition Performance

## Research Direction

The project focuses on combining:

**Open-Set Recognition + Ensemble Learning + Unknown Attack Detection + Continual Learning**

to develop adaptive intrusion detection systems capable of handling evolving and previously unseen cyber threats.

## Author

**Rudra Arindom Niloy**

Computer Science & Engineering
AI, Cybersecurity & Machine Learning Research

GitHub: [nil3939](https://github.com/nil3939)
