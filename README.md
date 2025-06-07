# DILPPG-Dataset

The **Deep Intelligence Lab Photoplethysmography (DILPPG)** dataset is an in-house curated resource designed to facilitate research in cuffless blood pressure estimation using photoplethysmography (PPG) signals. It includes synchronized measurements of systolic and diastolic blood pressure (SBP/DBP) along with corresponding PPG recordings.

---

## 📋 Dataset Overview

   | Statistics | Min (mmHg) | Max (mmHg) | Mean (mmHg) | STD (mmHg) |
   |------------|------------|------------|--------------|------------|
   | SBP        | 84         | 164        | 113.73       | 13.24      |
   | DBP        | 55         | 111        | 72.48        | 8.79       |

---

## 🧪 Data Collection Protocol

![Data Collection Setup](images/BP-collection(PPG-BP).png)

1. **Consent Taking**  
   Participants were first briefed on the study procedure, and informed consent was obtained from those who agreed to participate.

2. **BP Measurement**  
   Blood pressure readings were acquired using the **OMRON HEM-8712** digital BP monitor, with a measurement range of 20–280 mmHg and an accuracy of ±3 mmHg.

3. **PPG Recording**  
   PPG signals were recorded using a **Beurer PO80** pulse oximeter attached to the index finger of the right hand. The device supports a heart rate range of 30–250 BPM with an accuracy of ±2 BPM. Each session lasted for 180 seconds.

---

## 👥 Participant Demographics

- **Total Participants:** 194  
- **Gender Distribution:** 41 females and 153 males

---

## Dataset Access

Please note that this dataset could be used for research purposes only, and any commercial use of the data is prohibited. To access this dataset, send a request to the following email addresses:
* phd2201101014@iiti.ac.in
* deeplearning@iiti.ac.in 


##  Citation
```bash
@misc{DILPPG2025,
  title={VOLEMIA: Non-Invasive Blood Pressure Estimation Using Temporal-Spectral Convolutional Network},
  author={Trishna Saikia and Satwik Vankayalapati and Puneet Gupta and Pasi Liljeberg},
  journal={Digital Signal Processing},
  year={2025},
  publisher={Elsevier}
}

