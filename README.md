# EEG Alpha ERD Analysis (Quantifying Motor Imagery Dynamics)
### EEG 알파 ERD 분석: 운동 상상에 따른 뇌파 다이내믹스의 정량화

---

### 🇬🇧 English
This repository documents my learning process of analyzing Alpha **Event-Related Desynchronization (ERD)** from EEG signals using MNE-Python. I have built a data science pipeline to quantitatively analyze the ERD (Event-Related Desynchronization) phenomenon of alpha/mu rhythms (8-12 Hz) during motor imagery.

### 🇰🇷 한국어
본 레포지토리는 MNE-Python을 사용하여 EEG 신호에서 알파 **사건 관련 비동기화(ERD)**를 분석하는 학습 과정에 대한 기록입니다. 운동 상상 중 발생하는 알파/뮤 리듬(8-12 Hz)의 ERD 현상을 정량적으로 분석하는 데이터 과학 파이프라인을 구축했습니다.

---

## Motivation
* **EN:** I wanted to better understand how EEG rhythms change during motor imagery. Instead of starting with machine learning models, I decided to first learn the basic signal processing steps used in computational neuroscience.
* **KR:** 상상 운동 중에 뇌파(EEG) 리듬이 어떻게 변화하는지 이해하려는 동기가 있었습니다. 머신러닝 모델부터 시작하는 대신, 계산신경과학에서 사용되는 기본적 신호 처리 단계부터 학습했습니다.

---

## Background
* **Alpha/Mu Rhythm (8–12 Hz):** A brain rhythm commonly observed over the motor cortex during rest.
* **Event-Related Desynchronization (ERD):** A decrease in Alpha power that occurs when a person performs or imagines a movement.

---

## Objectives
* Load EEG data
* Apply basic preprocessing
* Extract the Alpha band
* Observe Alpha power changes during motor imagery

---

## Dataset
* **Source:** PhysioNet EEG Motor Movement/Imagery Dataset (Subject 1, Motor Imagery Runs)
* **Configuration:** 64-channel EEG sampled at 160 Hz based on the international 10-10 system.

---

## Repository Structure
```
eeg-alpha-erd-analysis/
│
├── README.md
├── requirements.txt
├── .gitignore
│
├── data/
├── figures/
└── notebooks/
    ├── 01_eeg_loading_visualization.ipynb
    ├── 02_alpha_band_filtering.ipynb
    ├── 03_epoch_extraction.ipynb
    ├── 04_alpha_erd_quantification.ipynb
    └── 05_visualization_statistics.ipynb
```

---

## Pipeline (Analytical Framework)
01. EEG data loading

02. Alpha-band filtering

03. Epoch extraction

04. ERD calculation

05. Result visualization

---

## Results
*This section will be updated as each notebook is completed.*

---

## Key Findings
*This section will be updated as each notebook is completed.*

---

## Future Work
* Support multiple subjects
* Compare left and right hand imagery
* Visualize ERD over motor cortex
* Explore simple statistical comparisons

---

## References
* Pfurtscheller, G., & Da Silva, F. L. (1999). Event-related EEG/MEG synchronization and desynchronization: basic principles. *Clinical Neurophysiology*.
* MNE-Python Documentation: Time-frequency and ERD analysis guidelines.
* PhysioNet EEG Motor Movement/Imagery Dataset

---

## Acknowledgement
This project was developed independently for learning and portfolio purposes. Publicly available datasets from PhysioNet and the MNE-Python ecosystem were used throughout this project.