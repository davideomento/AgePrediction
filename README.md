# Age Estimation
Project for the exam Data Science Lab: processes and methods in collaboration with Geard Koci
# 🧠 Speaker Age Estimation from Audio

This project addresses the problem of estimating the **age of a speaker** based on the information extracted from an audio recording in which the speaker utters a sentence. The system's goal is to predict a **single numerical value** corresponding to the speaker's estimated age.

## 📊 Dataset Overview

The dataset consists of **3624 samples**, divided into:

- **Development Set**: 2933 samples, each with the corresponding target age (used for training and analysis).
- **Evaluation Set**: 691 samples, without target labels (used for final evaluation).

The development set contains **20 columns**: 19 features and 1 target column (age). The evaluation set includes only the 19 input features.

## 🔍 Project Objective

The aim of this project is to develop a **regression model** that can accurately estimate the speaker's age using a mix of **audio**, **linguistic**, and **demographic** features extracted from the recordings.
