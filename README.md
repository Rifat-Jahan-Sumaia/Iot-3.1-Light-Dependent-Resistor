# Iot-3.1-Light-Dependent-Resistor
This project demonstrates how to use an LDR (Light Dependent Resistor) to detect darkness and control an LED automatically.  

## Features  
- Detects ambient light levels using an LDR.  
- Turns on an LED when the surrounding area is dark.  
- Simple and effective logic for light detection and LED control.
- Also implements the reverse logic.  

## Components Used  
- **LDR (Light Dependent Resistor):** Senses light intensity.  
- **LED:** Lights up in darkness.  
- **Resistors:** Ensures proper circuit operation.  
- **Microcontroller (if applicable):** Processes LDR readings (e.g., Arduino).  

## How It Works  
1. The LDR's resistance varies with light intensity:  
   - **Darkness:** High resistance.  
   - **Light:** Low resistance.  
2. The circuit or microcontroller logic compares the LDR's output to a threshold value:  
   - When the light level falls below the threshold, the LED turns on.  
   - When the light level is above the threshold, the LED remains off.  

---

