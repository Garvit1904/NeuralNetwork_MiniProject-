# Road Surface Classification using Mobile Sensors

## Project Overview
This project involves developing an Android application that captures motion sensor data (accelerometer and gyroscope) from a smartphone. The application records the motion characteristics of an average person driving a two-wheeler to build a dataset. This dataset is then used to train an LSTM (Long Short-Term Memory) classifier that classifies 3-second motion samples into different road surface types:

- **Kankar Road** (Gravel/Rough Surface)
- **Bitumen Road** (Asphalt/Paved Surface)
- **Concrete Road**
- **Single Speed Breaker**
- **Multiple Speed Breakers**

## Features
- **Real-time Sensor Data Collection:** The app captures accelerometer and gyroscope readings.
- **Dataset Generation:** Sensor readings are stored for further processing and model training.
- **LSTM-based Classification:** A deep learning model (LSTM) is trained to classify the road conditions based on 3-second motion data.
- **User-friendly Interface:** Simple UI for users to start and stop data collection.
- **Data Storage:** Collected data is saved for training and testing the LSTM classifier.


---
Developed by **Garvit Solanki**

