# 🔑 Arduino Password Entry System  
## 📌 Project Overview  
This is an **Arduino-based password system** using a **keypad, LCD, and LEDs**. It checks for a correct password and provides visual feedback.  

## 🛠️ Components Used  
- Arduino Mega 2560  
- LCD 1602A Module  
- 10k Potentiometer  
- 4x4 Membrane Keypad  
- **Two LEDs (Green & Red) for feedback**  
- Breadboard & Jumper Wires  

## ⚙️ How It Works  
1️⃣ Enter a **4-digit password** using the keypad.  
2️⃣ If correct (**2004**):  
   - ✅ **Green LED blinks 5 times** (Welcome).  
3️⃣ If incorrect:  
   - ❌ **Red LED blinks 5 times** (Access Denied).  

## 🔌 Wiring & Setup  
1. **Connect LCD, Keypad, and LEDs** as per the wiring diagram.  
2. **Upload** the `.ino` file to your **Arduino Mega 2560**.  
3. **Power on & test the system.**  

## 🚀 Future Improvements  
- 🔊 **Add a buzzer** for sound feedback.  
- 🔐 **Integrate with a servo motor** for door unlocking.  
- 📲 **WiFi or Bluetooth support** for remote access.  
