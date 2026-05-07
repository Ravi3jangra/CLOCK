# ⏰ TTL Digital Clock using 7490, 7447 & Seven Segment Display

A fully functional digital clock designed in Proteus using TTL logic ICs without any microcontroller.

The project displays time in HH:MM:SS format using 7-segment displays and counter logic circuits.

---

## 🚀 Features

- Displays time from `00:00:00` to `23:59:59`
- Built completely using TTL ICs
- Uses 555 Timer for clock pulse generation
- BCD counting using 7490 decade counters
- 7447 BCD to Seven Segment Decoder
- Common Anode 7-Segment Displays
- Designed and simulated in Proteus

---

## 🛠️ Components Used

| Component | Purpose |
|---|---|
| IC 7490 | Decade Counter |
| IC 7447 | BCD to 7-Segment Decoder |
| IC 555 | Clock Pulse Generator |
| IC 7805 | 5V Voltage Regulator |
| Seven Segment Display (CA) | Time Display |
| Resistors & Capacitors | Circuit Support |

---

## ⚙️ Working Principle

The 555 timer generates 1 Hz clock pulses.

These pulses are fed into cascaded 7490 decade counters which count seconds, minutes, and hours.

The BCD outputs from the counters are decoded by 7447 ICs to drive the Common Anode 7-segment displays.

The circuit resets appropriately after reaching 23:59:59.

---

## 🖥️ Software Used

- Proteus Design Suite

---

## 📷 Project Preview

Add screenshots here from Proteus simulation.

Example:

![Clock Simulation](images/clock.png)

---

## 📂 Files Included

- Proteus simulation files
- Circuit schematic
- Project images

---

## 🔮 Future Improvements

- Add AM/PM mode
- Add alarm functionality
- Add RTC module
- PCB design implementation

---

## 👨‍💻 Author

Ravi Jangra

Open file in Proteus 8 
In case of project not working thats mean seven segment not getting power so try to connect #00061 wire with seven segment display if still not work then try with #00101 
 
