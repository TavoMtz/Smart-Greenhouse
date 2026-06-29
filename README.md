# Predictive Smart Greenhouse - IoT & ML System

An automated, smart agricultural solution engineered to process real-time environmental data and optimize cultivation parameters through predictive computing.

## Complete Tech Stack

### Hardware Components
* Microcontroller: Arduino Uno
* Sensors: DHT11 Temperature & Humidity Sensor, Analog Soil Moisture Sensor
* Actuators & Control: L298N H-Bridge Module, Submersible Water Pump, DC Fan

### Software & Architecture
* Backend: Python 3, Flask
* Machine Learning: Scikit-Learn, Pandas, Joblib
* Networking & APIs: PySerial (Serial Communication), Telegram Bot API
* Frontend: HTML5, CSS3, JavaScript (Fetch API)

---

## Core Architecture & Features

### Predictive Automation (Machine Learning)
* Trained and deployed a Random Forest model with 99.8% accuracy utilizing Scikit-Learn and Pandas to predict precise water requirements based on real-time soil and ambient variables.
* Models are serialized and loaded dynamically via Joblib for fast inference loops.

### IoT Data Pipeline & Networking
* Developed a Flask API that parses continuous incoming streams from the Arduino Uno via PySerial.
* Implemented real-time evaluation loops to balance greenhouse variables dynamically.

### Automated Notification Gateway
* Integrated the Telegram API to deploy an instant alerting system, broadcasting critical thresholds or autonomous irrigation system updates directly to stakeholders.

---
