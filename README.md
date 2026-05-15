# DRLZDNIDS
A deep reinforcement based echo state network for network intrusion classification

Authors: Khorshed Alam, Mahbubul Haq Bhuiyan, Dewan Md Farid

Publication date: 2026/4/16

Journal: PloS one

Volume: 21

Issue: 4

Publisher: Public Library of Science

URL: https://journals.plos.org/plosone/article?id=10.1371/journal.pone.0333038 

Abstract: 
Network intrusion classification referred to the process of monitoring and analyzing network traffic to identify suspicious activities or attacks. In this work, author proposed a novel approach to classify network intrusion by utilizing deep reinforcement learning (DRL), integrating a reservoir computing approach Echo State Network (ESN). A DRL-based approach improved upon traditional deep learning by adapting dynamically to novel/unknown and evolving attack patterns. Unlike static models, DRL continuously learned optimal strategies through interaction with the environment, allowing for better detection of previously unseen threats in real-time. To address the class imbalance often encountered in network intrusion datasets, we evaluated the performance of several advanced data balancing techniques, including Borderline-SMOTE, SMOTE-ENN, ADYSN, and K-means SMOTE. The findings demonstrated that the K-means-based data balancing method outperformed other techniques, resulting in the most robust performance across various metrics. Author conducted multi-dataset validation on benchmark datasets like NF-BoT-IoT, NF-UNSW-NB15, NF-ToN-IoT, NF-ToN-IoT-v2, NF-CSE-CIC-IDS2018 and NF-UNSW-NB15-v3 to ensure robustness across different network flow data. For adaptive modeling testing, author excluded some attack types from training data and included them in testing data (e.g., DoS, Backdoor attacks were excluded from the training data but included in the testing data (see Table 3)). The proposed approach enhanced the accuracy and reliability of intrusion detection, making it a viable solution for securing modern network infrastructures. The source code of this work is available in this Github repository (https://github.com/codewithkhurshed/DRLZDNIDS).
