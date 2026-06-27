# Dataset Info
The Bangalore EEG Epilepsy Dataset (BEED) is a comprehensive EEG collection for epileptic seizure detection and classification. Recorded at a neurological research centre in Bangalore, India, it features high-fidelity EEG signals captured using the standard 10-20 electrode system at a 256 Hz sampling rate. BEED contains 16,000 segments of 20-second EEG recordings evenly distributed across four categories: Healthy Subjects (0), Generalized Seizures (1), Focal Seizures (2), and Seizure Events (3), where seizure activity occurs with events like eye blinking, nail biting, or staring. Each category includes data from 20 adult subjects (ages 21-55) with equal gender representation. The dataset comprises 16 EEG channels (X1-X16) corresponding to different brain regions, with a binary label (y) indicating seizure presence (1) or absence (0). BEED supports machine learning in seizure detection, epilepsy analysis, and EEG research with its balanced, high-resolution data.]

# Additional Info
Dataset Details
Dataset Characteristics: Multivariate
Feature Type: Integer
Subject Area: Health and Medicine
Instances: 8,000 (2,000 per category)
Classes: 4
Format: CSV
Features: 16 (EEG channels)
Associated Tasks: Classification
No missing Values

Data Structure
•	Subjects: 80 individuals (20 per file across four folders)
•	Time Points: 200 per subject
•	Explanatory Variables (X1–X16): 16 features representing EEG signal characteristics
•	Response Variable (y) (Column 17): Categorizes the EEG recordings into four distinct classes:
o	3 – Recording of seizure events (including activities such as eye blinking or constant staring)
o	2 – Recording of focal seizures
o	1 – Recording of generalized seizures
o	0 – Recording of healthy subjects (control group without epileptic seizures)

#Link
https://archive.ics.uci.edu/dataset/1134/beed:+bangalore+eeg+epilepsy+dataset
