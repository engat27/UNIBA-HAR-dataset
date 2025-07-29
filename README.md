# UNIBA HAR Dataset

This repository contains the **UNIBA Dataset**, introduced in the following publication:

> **Vincenzo Gattulli, Donato Impedovo, Antonio Piccinno, Giuseppe Pirlo **, *Human Activity Recognition Using Smartphone Sensors: Focusing on Fall Detection with the UNIBA Dataset*.  
> Published in **Springer SN Computer Science** (2025).  
> DOI: [10.1007/s42979-025-04187-8](https://doi.org/10.1007/s42979-025-04187-8)

---

## 📄 Description

The **UNIBA Dataset** was collected through a recruitment protocol aimed at ensuring data quality and representativeness.  
A total of 19 participants (13 males, 6 females) aged between 18 and 59 years, with heights ranging from 160 to 190 cm, voluntarily participated in the study. The data collection occurred in a controlled laboratory environment using a smartphone-based application that recorded accelerometer data at **200 Hz**.

Each participant was instructed to place the smartphone in their pants pocket (screen facing the body) and perform **eight specific actions**:

- Walking  
- Running  
- Jumping  
- Sitting  
- Falling forward  
- Falling backward  
- Falling to the right  
- Falling to the left

Each action was repeated **2–3 times**, with each trial lasting **15 seconds**. For fall activities, a safety mat was used to allow for natural and secure movement.

### 📊 Data Format

- **File format**: `.csv`  
- **Sampling rate**: 200 Hz  
- **Columns**:
  1. `user_id`: identifier of the participant  
  2. `activity`: label of the performed activity  
  3. `timestamp`: milliseconds from the start of the action  
  4. `x`, `y`, `z`: triaxial accelerometer values

---

## 🚀 Key Features

- Fine-grained classification of **fall types** (forward, backward, lateral)
- Recorded **entirely using smartphones**, making it highly applicable to real-world scenarios
- High **temporal resolution** (200Hz)
- Designed for **balanced class distribution** to support robust ML and cross-dataset experiments

Unlike many HAR datasets that rely on IMUs placed on various body parts, UNIBA focuses on **smartphone-based sensing** from the pocket position.

---

## 📁 Files

- `uniba_dataset.csv` – main dataset .zip 
---

## 📚 Citation

If you use this dataset, please cite the following work:

Gattulli, V., Impedovo, D., Piccinno, A. et al. Human Activity Recognition Using Smartphone Sensors: Focusing on Fall Detection with the UNIBA Dataset. SN COMPUT. SCI. 6, 640 (2025). https://doi.org/10.1007/s42979-025-04187-8


