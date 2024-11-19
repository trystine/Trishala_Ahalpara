---
layout: default
title: "Projects"
---

# Projects

---
## ***1. Process Mining- Longest State Prediction (Fujitsu Research of America)***

- Process mining is a technique that analyzes event logs from information systems to discover, monitor, and improve real business processes by providing insights into their actual execution.
- The aim of this project is to process the raw data of incident tickets provided by Data Warehouse and create a machine learning model that can predict the longest state in which a particular incident ticket will be stuck based on the partial history. Project involves end to end development of data pipelines with various components. My contribution towards the project was to create the Feature Generation pipeline which focuses on feature engineering strategies of creating time-based features, statistical based features and graph-based features using networkx library.
- Collaborated in developement of the Automated Pipeline and submitted a patent for the same.

---

## ***2. Process Mining- Burst Detection on Insights (Fujitsu Research of America)***

- This project is focused on building an Analysis and Predictive Tool powered by Artificial Intelligence and Machine Learning research for the Business Processes.
- There are some key challenges faced by the team regarding Incident ticket analysis and Conformance Checking. The need to have a tool which can help Troubleshoot what went wrong in a process cycle and identify the pain areas is one of the avenues where the project is focused on.
- My contribution towards this project was to research and implement how we can utilize the Fujitsu’s in-house proprietary technology on the Process Mining data. To generate insights such as what kind of feature combinations and values contributes towards a non-conforming or conforming Incidents. Identifying these pain areas can help Operation Managers to focus on only those features that are causing the issue.
- Further Application of Burst Detection Algorithm to find important trends and patterns is one of the research areas I am currently focusing on and writing a patent for.

---

## ***[3. User Segmentation- Data Science for All Fellowship-](projects/User_segmentation.md)*** 

- This project aimed to perform user segmentation on Stack Overflow data to identify distinct user groups and analyze their behavior patterns. Using data from 2017-2021 from the Stack Overflow BigQuery table, we employed clustering techniques, including the Elbow and Silhouette methods, to segment users into four main groups: reputable contributors, inactive users, curious learners, and community builders. We applied Principal Component Analysis (PCA) to reduce dimensionality and retain 41% of the data variance across two principal components, which were then used to build clusters. The clustering model identified unique user behavior traits based on their contributions, participation frequency, and question/answer activity, offering insights into how these users engage with the platform.

---

## ***[4. Sequential Coverage Analysis of Flash Memory Subsystem](projects/sequential_coverage.md)*** 

- The project aimed to perform a comprehensive coverage analysis and generate a detailed report for the XD7 FSS system, while also validating the functionality of the VC_2.6 Request Packets. This involved assessing the extent to which verification objectives were met by tracking and analyzing the percentage of covered verification points.

- Using a sequence of Request Packets (RPs), we mapped the number of legal sequences hit and successfully covered. To achieve this, logical coverage points were embedded into the C++ firmware code. The experiment was conducted with the Perspec tool, a sophisticated software-driven SoC (System-on-Chip) verification solution. Additionally, regression testing was integrated into the process using Jenkins, where I developed a custom Python script to automate the coverage analysis and streamline the connection of all essential components. This automation ensured an efficient and scalable process for verifying system coverage.

---

## ***[5. Biases in Deep Fake Videos Using Deep Learning Technology](projects/biases_in_deepfakes.md)*** 

- This project investigates gender and fat anti-fat biases present in DeepFake-generated videos using the FaceForensics++ dataset, which contains 500 videos manipulated through the FaceSwap DeepFake generator. The dataset primarily consists of Caucasian subjects, with a significant gender imbalance favoring females. By applying multiple deep learning techniques—GRU, RNN, and CNN—the study found that CNNs performed best in doing visual based classification. Misclassifications that were identified were further studied and it was noted that traditional physical traits, like women with short hair or wearing formal clothes, were wrongly classified as male. The study also included an extended societal bias survey where participants were shown images of obese individuals and were requested to provide their views. The study revealed that females tend to be more critical of physical traits in obese individuals in the survey

---

## ***[6. MindCare-Self-Harm Prediction Model](projects/self_harm_prediction.md)***  

- This research project addresses the prevalence of psychological disorders, specifically self-harm and depression, among institute-going students aged 15-30. Conducted with the validation and recommendation of a professional psychiatrist, the study develops a predictive model to identify self-harm tendencies. Utilizing a dataset of 353 students, seven machine learning algorithms were applied, with the Random Forest algorithm demonstrating the highest accuracy and a low false-positive rate. Feature selection reduced the initial 25 attributes to 13 using the Random Forest classifier's feature importance method. The model was trained through Stratified K-Fold sampling and hyperparameter optimization via Grid Search CV, culminating in a user-interactive web application for real-time prediction.

---

## ***[7. Event Recommendation System using NLP and Machine Learning Technology](projects/event_recommendation_system.md)***  
- The Event Recommendation System is an innovative solution leveraging Natural Language Processing (NLP) and Machine Learning to streamline event suggestions for employees. The system processes event details from a CSV file, using the TFIDF algorithm for feature extraction and a Random Forest Classifier to predict the domain and type of each event. Based on these predictions, it matches the events to employees whose preferences align with the predicted domains. Trained on a diverse dataset sourced from platforms like Coursera and event websites, this model efficiently automates event classification and personalizes recommendations for 185 employees, ensuring only relevant events are suggested to everyone.

---
