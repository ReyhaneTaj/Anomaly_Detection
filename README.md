# Anomaly_Detection
Project Title: Anomaly Detection and Data Resampling for Solar Power Systems

# Overview
This project implements an anomaly detection method to enhance the Xalt maintenance application at HEXAGON Solar Park, improving operational efficiency and system reliability. The project focuses on resampling and analyzing time-series data from solar power generation devices to detect abnormal behavior across various devices.
Introduction
The project addresses the need for efficient anomaly detection in solar power systems by resampling time-series data and identifying abnormal devices based on their performance compared to the average behavior(the solar park age was less than two years so they hadnt considered this type of evaluation befor but it ias obvious that it would be a real need in near futur). The methods implemented here can be used to process and analyze data from different devices within the solar park, helping to maintain high system reliability and operational efficiency.

# Features
Resampling of Time-Series Data: The data from different devices is resampled at user-defined intervals, allowing for more manageable and comparable datasets.
Anomaly Detection: Devices are analyzed to detect abnormal behavior, which can indicate potential issues that need maintenance.
Data Merging: The project also includes functionality to merge data from different sources, such as trackers and inverters, providing a comprehensive view of system performance.
The method focuses on improving operational efficiency and system reliability by resampling time-series data from various solar power generation devices. It identifies devices with abnormal performance by comparing their output to the average across the system. Additionally, the project includes functionality to merge and analyze data from different sources, such as trackers and inverters, providing a comprehensive view of the solar park's performance.
