---
layout: home
permalink: index.html

repository-name: e20-4yp-Adversarial-and-Noise-Robust-Training-for-Lightweight-Audio-Event-Detection
title: Adversarial and Noise Robust Training for Lightweight Audio Event Detection
---

# Adversarial and Noise Robust Training for Lightweight Audio Event Detection

#### Team

- E/20/371, Rishopika S, [e20371@eng.pdn.ac.lk](mailto:e20371@eng.pdn.ac.lk)
- E/20/338, Rishanthan S,[e20338@eng.pdn.ac.lk](mailto:e20338@eng.pdn.ac.lk)
- E/20/376, R.M.M. Shyamantha,[e20376@eng.pdn.ac.lk](mailto:e20376@eng.pdn.ac.lk)

#### Supervisors

- Prof. Roshan G. Ragel, [roshanr@eng.pdn.ac.lk](mailto:roshanr@eng.pdn.ac.lk)
- Puvanendran Rukshani, [rukupuvan@gmail.com](mailto:rukupuvan@gmail.com)

---

#### Table of Content

1. [Abstract](#abstract)
2. [Related Works](#related-works)
3. [Methodology](#methodology)
4. [Experiment Setup and Implementation](#experiment-setup-and-implementation)
5. [Results and Analysis](#results-and-analysis)
6. [Conclusion](#conclusion)
7. [Publications](#publications)
8. [Links](#links)

---

## Abstract

Respiratory diseases can be identified through analysis of acoustic signals such as coughs, wheezes, and breathing sounds. This project focuses on developing a lightweight Audio Event Detection (AED) system capable of identifying respiratory-related sound events in noisy real-world environments. The system incorporates adversarial training and noise-robust learning techniques to improve model generalization across different datasets and recording conditions. By utilizing efficient neural network architectures, the proposed approach ensures accurate detection while maintaining low computational complexity, making it suitable for deployment in resource-constrained devices such as mobile and embedded systems.

---

## Related Works

Previous studies in respiratory sound classification have used deep learning models such as CNNs and RNNs to detect abnormalities in breathing and cough signals. However, many of these models struggle when exposed to real-world noise and cross-dataset variations. Researchers have explored data augmentation, transfer learning, and adversarial training techniques to improve robustness. Lightweight neural networks have also been proposed to enable deployment on edge devices. This project builds upon these approaches by integrating adversarial and noise-robust training strategies into a lightweight audio event detection framework.

---

## Methodology

The proposed system processes respiratory audio signals using a structured pipeline that includes data preprocessing, feature extraction, model training, and evaluation. Audio signals are first cleaned and converted into time-frequency representations such as spectrograms. These features are then used to train a lightweight neural network model designed for efficient audio event detection. Adversarial training techniques are applied during model learning to increase robustness against noisy inputs. The model is evaluated using cross-dataset validation to measure its ability to generalize across different respiratory sound datasets.

---

## Experiment Setup and Implementation

The system is implemented using Python and deep learning frameworks such as TensorFlow or PyTorch. Publicly available respiratory sound datasets are used for training and testing the model. Preprocessing includes noise filtering, segmentation, and feature extraction using Mel-spectrograms. The model is trained using adversarial noise augmentation to simulate real-world conditions. Experiments are conducted to compare the performance of the proposed approach against baseline models under different noise levels and dataset variations.

---

## Results and Analysis

The experimental results demonstrate that the proposed adversarial and noise-robust training strategy significantly improves detection accuracy in noisy environments. The lightweight architecture maintains efficient computational performance while achieving competitive classification results. Cross-dataset evaluations indicate that the model generalizes well across different recording conditions. The results highlight the potential of the proposed method for real-world respiratory monitoring applications.

---

## Conclusion

This project presents a lightweight and noise-robust audio event detection system for identifying respiratory sound events. By incorporating adversarial training techniques, the model achieves improved generalization and robustness to environmental noise. The system demonstrates strong performance while maintaining low computational requirements, making it suitable for deployment in mobile and embedded healthcare applications.

---

## Publications

<!-- Add once available -->

---

## Links

- [Project Repository](https://github.com/cepdnaclk/e20-4yp-Adversarial-and-Noise-Robust-Training-for-Lightweight-Audio-Event-Detection)
- [Project Page](https://cepdnaclk.github.io/e20-4yp-Adversarial-and-Noise-Robust-Training-for-Lightweight-Audio-Event-Detection)
- [Department of Computer Engineering](http://www.ce.pdn.ac.lk/)
- [University of Peradeniya](https://eng.pdn.ac.lk/)
