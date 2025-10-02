# Plant_Watering_Machine
Automated plant watering system with cloud-based monitoring and manual pump control.

## Purpose

This project aims to realize a **multi-plant watering machine**.  
Soil moisture levels are measured by individual sensors and transmitted by an **Arduino UNO R4 WiFi** to the **Arduino Cloud**, where the data is visualized.  

From the cloud dashboard, a user can press a button to activate the corresponding pump, delivering water to a specific plant.

---

## Current Progress

- ✅ Circuit plan designed  
- ✅ Initial breadboard tests with moisture sensors and pumps  
- 📸 Photos of Simulation included 
- ⏳ Firmware and full PCB design in progress  

---

## Files

- **Circuit Plan**
  - `circuit_plan/Schaltplan_V1.0.pdf` — full circuit schematic  

- **Photos**
  - `images/LTSpice_Simulation` — Simulation setup in LTSpice
  - `images/LTSpice_MaxCurrent.jpg` — Voltage and current flowing through Arduino pin during MOSFET activation

---

## Hardware Overview

- **Microcontroller**: Arduino UNO R4 WiFi  
- **Sensors**: Soil moisture sensors (one per plant)  
- **Actuators**: Mini water pumps (controlled individually)  
- **Cloud Platform**: Arduino Cloud for visualization and control  

---

## Next Steps

- Implement firmware to send sensor data to Arduino Cloud  
- Integrate cloud dashboard with on/off pump buttons and soil sensor data display
- Design and manufacture PCB for a multi-plant version  
- Test long-term reliability of sensors and pumps  

---

## License

[MIT](LICENSE) — free to use for personal, educational, or academic purposes.  

---

## Contact

- Name: Annalena Schmid
- Email: annalena.schmid.2003@gmail.com
- GitHub: [github.com/AnnSchmid](https://github.com/AnnSchmid)
