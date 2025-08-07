# Step-by-Step-Power-Generation-System
Arduino-based footstep power generation system using piezo sensors and LCD display.
# ⚡ Footstep Power Generation System using Piezo Sensors and LCD

This project demonstrates a smart and sustainable method of energy harvesting by converting mechanical pressure from footsteps into electrical energy using piezoelectric sensors. The voltage generated is displayed on an LCD screen in real-time.

---

## ✅ Project Overview

- **Project Name**: Footstep Power Generation System
- **Domain**: Embedded Systems / IoT / Renewable Energy
- **Objective**: To generate power through footsteps and display the voltage output using an LCD.
- **Status**: Completed ✅

---

## 🔧 Components Used

| Component               | Description                                |
|------------------------|---------------------------------------------|
| Piezoelectric Sensors  | To convert foot pressure into voltage       |
| Arduino Uno            | Main microcontroller for control            |
| LCD Display (16x2)     | To display generated voltage and name       |
| Resistor               | Used in place of voltage regulator          |
| LED                    | Lights up when pressure is applied          |
| Jumper Wires, Breadboard | For circuit connections and prototyping   |

---

## 🧠 Working Principle

1. When a person steps on the piezo sensor, it produces a voltage due to mechanical pressure.
2. This voltage is directly connected to the analog input of the Arduino.
3. The Arduino reads the voltage value from the sensor.
4. Initially, the LCD displays your name (e.g., "Welcome Kaviya").
5. After a delay, the LCD displays the actual voltage sensed from the footstep.
6. An LED glows to indicate pressure has been applied on the sensor.

---

## 🖼️ Output & Circuit Images

### ✅ Working Output

![working_output jpg](https://github.com/user-attachments/assets/88c4d9c0-12de-4af3-930d-8e8920039049)

### 🧪 Circuit Diagram

<img width="811" height="572" alt="circuit_diagram jpg" src="https://github.com/user-attachments/assets/c07b7fc0-4b7a-4ae4-b709-20768a14ba24" />

---

## 💻 Arduino Code

The Arduino sketch is available in [`main_code.ino`](main_code.ino).

### Key Features:
- LCD initialization and setup
- Analog voltage reading from piezo sensor
- Display of name followed by voltage on LCD
- LED control based on pressure detection

---

## 🔍 Sample LCD Output

Welcome Haritha
Voltage: 2.45V

---

## 📈 Future Enhancements

- Store generated voltage into a rechargeable battery
- Add multiple piezo sensors in series/parallel for better voltage gain
- Send voltage readings to cloud via IoT modules (ESP8266, etc.)
- Display step count and energy estimate on LCD or web app

---

## 📚 Learning Outcomes

- How piezoelectric sensors work for energy generation
- Analog to digital conversion using Arduino
- LCD interfacing with Arduino (16x2 display)
- Real-time monitoring of sensor data
- Basic embedded hardware prototyping

---

## 🧑‍💻 Author

**HARITHA P**  
Final Year CSE Student  
[GitHub Profile](https://github.com/P-HARITHA)

---

## 🌐 Tags

`arduino` `iot` `piezoelectric` `lcd` `embedded-systems` `voltage-display`  
`student-project` `power-generation` `energy-harvesting`
