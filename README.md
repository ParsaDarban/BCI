# BCI
Electroencephalogram (EEG) signals play a significant role in understanding brain activity and cognitive processes. Nowadays, processing and classifying these signals using machine learning methods has broad applications in brain-computer interfaces, clinical diagnostics, and neuroscience in general.

In this project, we first familiarize ourselves with EEG signal data, then explore various preprocessing methods, including data cleaning and noise removal, which are typically associated with real-world signals. Afterward, we focus on feature extraction from the signals and proceed to classify and cluster them.

Motor imagery is a process in which an individual is asked to imagine performing an action, such as moving their fingers or feet, without physically performing the movement. During this activity, EEG signals are recorded. These EEG signals capture the brain's electrical activity by placing electrodes on various regions of the scalp. 

These signals represent electrical potentials as a function of time. It is expected that while the individual imagines the movement, patterns associated with the activity of relevant brain regions can be identified using EEG signals. The aim of this project is to process EEG signals to detect patterns related to this task.

In this project, we use a dataset specifically designed to challenge and advance the development of Brain-Computer Interface (BCI) technologies. This dataset serves as a tool for testing algorithms that classify EEG experiments, where each experiment represents a fixed-length windowed signal associated with a specific mental state.

Unlike conventional datasets, where changes in mental states are explicitly marked, this dataset focuses on asynchronous BCI input. Here, classifiers must continuously process EEG data without explicit cues indicating that the user has changed their intention.

Data set:

https://www.bbci.de/competition/download/competition_iv/BCICIV_1_mat.zip

Filter we use in this project:
Laplacian filter & CAR filter

Feature extraction used in this project:
CSP & Wavelet Transform

Classification algorithms:
KNN & MLP & Logistic Regression

![image](https://github.com/user-attachments/assets/6576e413-7244-41a7-bbb7-cf325497e205)

Clustering is an unsupervised learning technique that involves grouping data points into clusters such that points within the same cluster are more similar to each other than to points in other clusters.
GMM might be better suited for complex datasets with varying cluster shapes and densities due to probabilistic nature and ability to model covariance. K-Means is efficient and effective for well-separated spherical clusters.

**Note:**  
The first phase involves research on EEG signals, focusing on the challenges associated with pattern recognition in motor imagery signals and exploring methods to address these issues.  

The second phase involves implementing the methods discussed in the articles from the first phase.
