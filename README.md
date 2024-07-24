# GridSense-ADS

## Project Overview
GridSense-ADS is an Industrial IoT approach designed for real-time anomaly detection in power grid systems. This project leverages machine learning models to monitor and analyze data collected from sensors in power grid environments, aiming to detect anomalies that could lead to significant negative consequences such as electrocution or electric fires.

## Table of Contents
- [Introduction](#introduction)
- [Features](#features)
- [Installation](#installation)

## Introduction
The GridSense-ADS project integrates advanced IoT technologies and machine learning algorithms to proactively detect anomalies in power grid systems. It uses a DHT11 sensor connected to an ESP8266 microcontroller to monitor humidity levels, with data relayed through MQTT protocol to an AWS EC2 instance for real-time analysis.

## Features
- **Real-time Data Collection and Analysis**: Utilizes DHT11 sensors and ESP8266 microcontrollers for monitoring humidity in power grid environments.
- **Machine Learning Models**: Implements Isolation Forest, Local Outlier Factor (LOF), and One-Class Support Vector Machine (OCSVM) for anomaly detection.
- **Cloud Integration**: Uses AWS EC2 for scalable and resilient data processing.
- **High Accuracy**: Achieves high precision and recall in detecting anomalies with Isolation Forest being the most effective model.

## Installation
To set up the project locally, follow these steps:

1. Clone the repository:
    ```sh
    git clone https://github.com/your-username/GridSense-ADS.git
    cd GridSense-ADS
    ```

2. Install the necessary dependencies:
    ```sh
    pip install -r requirements.txt
    ```

3. Configure the AWS EC2 instance and MQTT broker settings in the provided configuration files.

