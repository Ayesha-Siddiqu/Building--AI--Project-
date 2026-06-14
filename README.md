# AI Threat Detection

## Summary
An AI system using machine learning to detect network anomalies and security threats in real-time.

## Background
Automated network scans and cyber threats are constant global challenges. Manual log monitoring is impossible due to sheer data volume.

## How it Works
The system monitors network logs, normalizes data, and triggers automated alerts if anomaly scores spike.

## Data Sources & AI Methods
Using public cybersecurity datasets like NSL-KDD, the project applies Random Forest classifiers for traffic anomaly detection.

## Challenges
Minimizing false positives from legitimate but rare operations while handling sensitive internal log data securely.

## What's Next
Integrating unsupervised learning models like Autoencoders to detect completely unknown zero-day attacks.
