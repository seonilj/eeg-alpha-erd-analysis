# EEG Alpha ERD Analysis (Quantifying Motor Imagery Dynamics)
### EEG 알파 ERD 분석: 운동 상상에 따른 뇌파 다이내믹스의 정량화

---

### 🇬🇧 English
This repository establishes a specialized neuro-data science pipeline to quantify **Event-Related Desynchronization (ERD)** within the Alpha/Mu rhythm (8–12 Hz) during motor imagery tasks. Shifting the focus from black-box machine learning algorithms, this project benchmarks spatial and statistical cortical gating mechanisms over the human motor cortex using the PhysioNet EEGBCI dataset.

### 🇰🇷 한국어
본 레포지토리는 운동 상상 중 발생하는 알파/뮤 리듬(8-12 Hz)의 **사건관련 동기비동기화(ERD)** 현상을 정량적으로 분석하는 데이터 과학 파이프라인을 구축합니다. 블랙박스 형태의 머신러닝 알고리즘을 넘어, PhysioNet EEGBCI 데이터를 기반으로 인간 운동 피질 영역의 공간적·통계적 피질 게이팅 메커니즘을 검증하는 데 집중합니다.

---

## 1. Motivation
* **EN:** I wanted to deep-dive into how neural oscillations shift dynamically during cognitive states and understand the quantitative mechanics behind neurophysiological suppression (ERD) rather than simply running end-to-end black-box classifiers.
* **KR:** 단순한 분류기 실행을 넘어, 인지적 상태에 따라 신경 진동(Neural Oscillations)이 어떻게 동적으로 변화하는지 깊이 이해하고, 신경생리학적 억제 현상(ERD)을 정량화하는 분석적 배경을 학습하고자 시작했습니다.

---

## 2. Background
* **Alpha/Mu Rhythm (8–12 Hz):** Synchronized neural oscillations recorded over the sensorimotor cortex that reflect a state of sensory-motor rest.
* **Event-Related Desynchronization (ERD):** The localized decrease or suppression of these rhythmic amplitudes during active cortical processing or motor imagery, serving as a vital neuro-biomarker for translational BCI profiling.

---

## 3. Objectives
* **Standardize & Map:** Load the PhysioNet EEGBCI dataset using MNE-Python and assign international electrode coordinates.
* **Isolate Oscillation:** Extract clean Alpha/Mu bands (8-12 Hz) via localized sensory-motor channel selection (C3, Cz, C4).
* **Quantify ERD:** Measure and visualize time-resolved power suppression during active imagery versus baseline periods.

---

## 4. Dataset
* **Source:** PhysioNet EEG Motor Movement/Imagery Dataset (Subject 1, Motor Imagery Runs)
* **Configuration:** 64-channel EEG sampled at 160 Hz based on the international 10-10 system.

---

## 5. Pipeline (Analytical Framework)
*(Note: Active development in progress. Individual notebooks are being sequentially constructed.)*

*(참고: 현재 활발히 개발 중입니다. 각 노트북이 순차적으로 구축되고 있습니다.)*

---

## 6. Results
*(Note: Visual outputs will be automatically generated and populated into the `/figures` directory upon notebook execution.)*

*(참고: 노트북 실행 후 생성되는 시각화 결과물이 `/figures` 디렉토리에 순차적으로 채워질 예정입니다.)*

---

## 7. Key Findings
*(Note: Analytical observations and statistical validations will be documented as development progresses.)*

*(참고: 분석 결과에 따른 통계적 검증 및 관찰 사실이 개발 진행에 맞춰 이곳에 기록될 예정입니다.)*

---

## 8. Future Work
*(Note: Future research extensions and multi-subject scaling plans will be continuously updated as the core framework stabilizes.)*
*(참고: 핵심 프레임워크가 안정화됨에 따라 향후 연구 확장 및 다중 피험자 확장 계획이 지속적으로 업데이트될 예정입니다.)*

---

## 9. References
* Pfurtscheller, G., & Da Silva, F. L. (1999). Event-related EEG/MEG synchronization and desynchronization: basic principles. *Clinical Neurophysiology*.
* MNE-Python Documentation: Time-frequency and ERD analysis guidelines.