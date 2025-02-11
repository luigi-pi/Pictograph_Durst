# **Pictograph PCB Replacement with Arduino**  

This project replaces some missing or malfunctioning **DURST Pictograph PCBs** with an **Arduino Mega 2560**-based solution, ensuring continued operation with enhanced control and modern components. The system integrates **motor drivers, stepper controllers**, and an **User Interface** with **LCD, and rotary encoders** for intuitive control.  

---

## 🚀 **Features & Hardware Modifications**  

### 🔹 **Main Controller**  
- **Arduino Mega 2560**  

### 🔹 **Motor & Filter Controls**  
- **Head motor driver** → **Replaced with DRV8871** (see head motor program)  
- **Color filters** → **Controlled by StepperOnline DM320T stepper drivers**  
- **Shutter & density filters** → **Controlled by DRV8871**  

### 🔹 **User Interface Enhancements**  
- **2004 Red LCD (I2C-controlled)** for real-time display  
- **3x KY-040 rotary encoders** for control of:  
  - Color filters  
  - Shutter  
  - Density filters  

### 🔹 **Additional Upgrades**  
- **Lamp ON/OFF control** using a relay  

---

## 🎯 **Why Use This Replacement?**  
✅ **Restores most of the functionality** of broken Pictograph systems  
✅ **Cost-effective** alternative to original PCBs, no more available since the product is discontinued 
✅ **Customizable & open-source** for additional modifications  
✅ **Enhanced usability** with a modernized interface  

---

## 🤝 **Contributions & Feedback**  
This project is open-source! Contributions, improvements, and feedback are welcome.  
- **Submit pull requests** for improvements  
- **Open issues** for troubleshooting or feature requests  
