# 🌡️ IoT Real-Time Dashboard with DHT11, Arduino, and Streamlit

This project shows how to read temperature and humidity data from a DHT11 sensor using Arduino, and display it in real-time using Python and Streamlit.

## 📦 Features
- Real-time data acquisition
- Dynamic dashboard with charts
- Linear regression prediction
- Live table display

## 🛠️ Hardware
- Arduino UNO or Nano
- DHT11 sensor
- 10kΩ resistor
- Jumper wires

## 🧰 Setup Instructions

1. Upload `arduino_dht11.ino` to your Arduino board.
2. Connect Arduino to your PC via USB.
3. Make sure the serial port (e.g., `COM3`) is correct in `iot_dashboard.py`.
4. Install dependencies:
   ```bash
   pip install -r requirements.txt

