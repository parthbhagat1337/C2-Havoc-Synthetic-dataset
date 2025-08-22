📊 Synthetic C2 Traffic Dataset

This repository contains a synthetic network traffic dataset generated for research on Command-and-Control (C2) detection using Machine Learning.

🔹 Dataset Overview
Total samples: 90,263
  Benign traffic: 77,742
  Malicious (C2) traffic: 12,521
Traffic source: Generated in a controlled virtual lab environment.
C2 Framework: Havoc C2
Capture method: Traffic collected from attacker–victim communication and converted to CSV using CICFlowMeter.
Format: CSV files with extracted flow-based features.

🔹 Features

Each row represents a network flow with features such as:
Flow duration
Packet length statistics
Inter-arrival times
TCP flag counts
Bytes sent/received
Label (Benign or Malicious)

🔹 Purpose
This dataset was created to support research in:
Detecting C2 traffic in encrypted environments.
Evaluating ML algorithms for intrusion detection.
Studying generalization of detection models across different C2 frameworks.

🔹 Limitations
The dataset is synthetic and collected in a controlled lab, so it may not fully reflect real-world network traffic diversity.
Currently includes traffic from only one C2 framework (Havoc).

🔹 License & Usage

This dataset is released for academic and research purposes only.
If you use it in your work, please cite this repository.
