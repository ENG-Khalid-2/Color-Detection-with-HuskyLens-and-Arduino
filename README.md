
# 🎨 Color Detection with HuskyLens and Arduino

## 💡 Project Idea
This project uses the **HuskyLens AI Camera** and an **Arduino Uno** to recognize colors in real-time and print their names to the Serial Monitor.  
The goal is to explore color recognition using AI without complex training or coding — just plug and play with HuskyLens!

---

## 🧰 Components Used

| Component             | job |
|-----------------------|------------------------------------------------|
| Arduino Uno           | to disply the color on the serial monitor      |
| HuskyLens AI Camera   | using ai to recognise the envarioment          |
| Jumper Wires          | to send the deta between Arduino and HuskyLens |
| Breadboard (optional) | to program the Arduino                         |


---

## 📷 Camera Used
- **Model:** HuskyLens AI Camera  
- **Mode:** Color Recognition Mode

---

## ⚙️ Steps and Configuration

1. **Connected HuskyLens to Arduino Uno** using SoftwareSerial (Pins 10 & 11).
2. **Installed the HuskyLens Arduino Library** from the official GitHub repo:
   > https://github.com/HuskyLens/HUSKYLENSArduino
3. Switched HuskyLens to **"Color Recognition"** mode using the onboard button.
4. Taught the camera different colors (Red, Green, Blue, etc.) by showing them and pressing the learning button.
5. Wrote Arduino code to read the detected color ID and print the corresponding **color name** to the Serial Monitor.

---

## 🖥️ Output Example (Serial Monitor)

