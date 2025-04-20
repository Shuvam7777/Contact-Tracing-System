# Contact-Tracing-System

# Introduction
Contact tracing plays a critical role in managing infectious disease outbreaks by identifying individuals who may have come into contact with an infected person. This project focuses on building a contact tracing system using machine learning techniques to analyze user interaction data, assess transmission risks, and help contain the spread of contagious diseases like COVID-19. By automating the tracing process, this system supports public health efforts with real-time alerts and risk prediction.

# Objectives
To develop a system that tracks user interactions and identifies potential transmission chains.

To use machine learning algorithms for assessing exposure risk based on proximity data.

To analyze contact patterns and predict infection likelihood.

To ensure privacy and data security while handling sensitive health-related information.

# Dataset Description
The system utilizes simulated or real-world data that may include:

User ID / Device ID

Timestamped Location Data (GPS/Bluetooth)

Duration of Contact

Distance Between Individuals

Infection Status (Binary Target Variable)

Contact Frequency

This is framed as a classification problem, where the goal is to predict whether a person is at risk (high/low) based on their contact history.
