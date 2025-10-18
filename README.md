\# 🧠 Intrusion Detector ML  

\*A Deep-Learning–Based Intrusion Detection Framework using TabNet and TabTransformer\*



---



\## 🔍 Overview

This project implements an interpretable \*\*Deep Learning Intrusion Detection System (IDS)\*\* built on \*\*TabNet\*\* and \*\*TabTransformer\*\* architectures.  

The goal is to improve the \*\*accuracy and interpretability\*\* of intrusion detection by combining \*\*statistical feature analysis\*\* with \*\*attention-based learning\*\*.



The work explores how deep models such as \*\*TabNet\*\*, \*\*CNN-1D\*\*, and \*\*Transformers\*\* can detect malicious network activity across multiple benchmark datasets.



---



\## 🎯 Research Motivation

Traditional ML-based IDS (SVM, Random Forest, Gradient Boost) struggle with:

\- High false-positive rates  

\- Extensive feature engineering  

\- Limited adaptability to new attack patterns  



This project addresses these issues by:

1\. Employing \*\*sequential attention (TabNet)\*\* to dynamically select relevant features  

2\. Integrating \*\*feature property analysis\*\* (Sequential Feature Selector)  

3\. Using \*\*weighted cross-entropy\*\* to handle \*\*class imbalance\*\*  

4\. Extending experiments to \*\*TabTransformer\*\* for reasoning-based classification decisions  



---



\## 🧩 Proposed Framework

The system workflow includes:

1\. \*\*Data Acquisition:\*\* Network traffic from NSL-KDD, CIDDS-002, and CIC-IDS-2018 datasets.  

2\. \*\*Feature Selection:\*\* Sequential Feature Selector (SFS) determines dominant features for classification.  

3\. \*\*Deep Learning:\*\* TabNet performs sequential attention-based training on selected features.  

4\. \*\*Loss Balancing:\*\* Weighted Cross-Entropy compensates for skewed class distributions.  

5\. \*\*Interpretability:\*\* Visualizations (t-SNE, feature importance) explain model decisions.  





