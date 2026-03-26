# Rocket Club Airbrakes Controller — 2‑Layer PCB

This board was designed for a student rocketry group that needed an airbrakes control module sized to fit inside their rocket’s body tube (≈80 mm inner diameter). It used an Arduino Nano as the main controller, included a barometer for altitude sensing, and provided servo connections for actuating the airbrake fins.

This was my **first real dip into a more complex 2‑layer board**. Before this, I stuck to simple 2‑layer designs mainly for space and simplicity. This project pushed me to think about routing density, sensor placement, and mechanical constraints in a much more serious way.

---

## Overview

The board was built around four core requirements:

### **1. Match the rocket’s internal diameter**
The PCB had to fit perfectly inside the airframe tube, which required:
- Curved board edges  
- Precise diameter matching  
- Careful component height budgeting  
- Mounting hole alignment with the rocket structure  

### **2. Integrate an Arduino Nano**
The Nano served as the flight computer responsible for:
- Reading barometric altitude  
- Running the airbrake control algorithm  
- Driving the servos  

### **3. Provide servo outputs for airbrake actuation**
The board included:
- Servo headers  
- Power routing for servo loads  
- Clean signal paths from the Nano  

### **4. Include a barometer**
Used for:
- Detecting ascent/descent  
- Triggering airbrake deployment  
- Providing altitude feedback to the control loop  

---

## Screenshots

*(Embed your images here)*

![Board Screenshot 1](./images/board1.png)
![Board Screenshot 2](./images/board2.png)

---

## What I Learned

This project taught me several foundational lessons in real PCB design:

### **Designing to mechanical constraints**
Matching the tube diameter forced me to think about:
- Geometry  
- Clearances  
- Component height  
- Mounting alignment  

### **Working with microcontroller modules**
Integrating the Arduino Nano taught me about:
- Pin mapping  
- Power distribution  
- Signal routing  
- Noise considerations  

### **Sensor + actuator integration**
Combining a barometer with servo outputs introduced me to:
- Mixed‑signal layout  
- Power isolation  
- Clean routing strategies  

### **Designing for someone else’s requirements**
This was my first time building hardware for another team, which meant:
- Communicating constraints  
- Iterating based on feedback  
- Designing for real use, not just experimentation  

### **First step into more complex 2‑layer design**
This board pushed me past “beginner PCB” territory and into:
- Tighter routing  
- More thoughtful placement  
- Real‑world constraints  
- More advanced design decisions  

---

## Status

**Completed.**  
Delivered to the rocketry group for integration into their airbrakes system.


