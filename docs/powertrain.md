# **Veydra – Powertrain & Energy System**

Veydra’s powertrain is designed around efficiency, modularity, and responsiveness.  
Instead of chasing extreme horsepower numbers, the focus is on **useful performance**, **high recuperation efficiency**, and **smooth energy flow** through a mixed-chemistry battery system.

This document outlines the propulsion architecture, battery design, regenerative braking approach, and supporting control systems.

---

# ⚡ **1. Propulsion Architecture Overview**

Veydra uses compact, modular **e-axle units** that combine:
- Motor  
- Single-speed gearbox  
- Differential (if needed)  
- Inverter  
- Cooling hardware  

These e-axles bolt directly to reinforced points on the perimeter frame.

## **1.1 Configurations**
- **RWD (standard)**  
  - One rear e-axle  
  - Balanced handling  
  - Efficient packaging  

- **AWD (optional)**  
  - Adds a front e-axle  
  - Independent torque control  
  - Enhanced traction and acceleration  

---

# 🌀 **2. Motor Technology**

### **2.1 Axial-Flux Motors**
Veydra uses **axial-flux permanent magnet motors** due to their:
- High power density  
- High torque from a compact form factor  
- Short axial length  
- Low mass  
- High efficiency at partial loads  

This enables:
- Lower unsprung mass (motors are inboard, not in-wheel)  
- Better weight distribution  
- More cabin/passenger space  

### **2.2 Drive Characteristics**
Target characteristics:
- Smooth torque delivery  
- High efficiency in everyday driving  
- Strong low-end torque for responsiveness  
- Predictable regen control  

---

# 🔋 **3. Battery System**

Veydra employs a **mixed-chemistry battery** composed of two functional layers:

## **3.1 Main Energy Pack**
- High-energy-density chemistry  
- 75–85 kWh usable capacity  
- Optimized for long cycle life  
- Provides the bulk of driving range  

### Purpose:
- Long-distance travel  
- High highway efficiency  
- Consistent thermal performance  

---

## **3.2 Power Buffer Layer**
A smaller, high-power battery layer:
- Designed for rapid charge/discharge  
- Handles peak power events (acceleration, regen)  
- Reduces stress on the main pack  

### Benefits:
- Improved long-term battery health  
- Higher regen efficiency  
- Faster response during dynamic driving  
- Reduced thermal load on the main pack  

### Connection:
- Communicates via a **bidirectional DC/DC converter**  
- Acts as a capacitor-like buffer during transients  

---

# 🥶 **4. Thermal Management System**

Veydra integrates propulsion and battery cooling into a **shared thermal spine** running along the center of the structural floor.

### Components:
- Liquid cooling loops  
- Thermal fuses  
- Cold plates  
- Heat pump interface  
- Electric valves  

### Goals:
- Maintain stable battery temperature  
- Reduce inverter/motor heat stress  
- Improve cabin heating efficiency  
- Enable rapid DC fast charging  

---

# 🔄 **5. Regenerative Braking System**

Veydra’s regen strategy is designed for **maximum energy recovery** without compromising safety or driver confidence.

### **5.1 Enhanced Regen Layout**
Thanks to the power buffer layer, regen can:
- Capture more energy from deceleration  
- Apply stronger regen without battery stress  
- Operate efficiently across a wider temperature range  

Target regen efficiency improvement:  
**5–15% more recovered energy** vs. typical EVs.

---

### **5.2 Regen-Friction Integration**
Regen is blended with friction braking via:
- Brake-by-wire  
- Predictive algorithms  
- Adaptive AeroBrake activation in emergencies  

### Results:
- Consistent pedal feel  
- Shorter stopping distances under load  
- Higher energy recovery during daily driving  

---

## 🧠 **6. Torque Vectoring & Traction Control**

Both e-axles can modulate torque independently.

### Functions:
- Stability enhancement  
- Cornering assistance  
- Slip mitigation  
- Predictive distribution based on sensor data  

### AWD variant:
- Virtual “center differential” controlled in software  
- Real-time torque split optimization  

---

# 🛠️ **7. Charging System**

### **7.1 DC Fast Charging**
- Up to 250–300 kW (target)  
- Enabled by power buffer layer handling high C-rates  

### **7.2 AC Charging**
- 11–19 kW depending on market  

### **7.3 Smart Charging Features**
- Preconditioning before fast charge  
- Intelligent off-peak charging  
- Solar roof trickle charge (if equipped)  

---

# 🧭 **8. Summary**

Veydra’s powertrain is built on four pillars:

- **Efficient motors** that deliver smooth, usable performance  
- A **mixed-chemistry battery** that balances range, life, and power  
- A **thermal spine** that simplifies cooling and increases reliability  
- **High-efficiency regenerative braking** enabled by a power buffer layer  

The result is a drivetrain that’s responsive, efficient, and modern — engineered for real-world driving rather than spec-sheet extremes.
