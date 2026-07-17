# Microbit_V2 Thermometer

A simple digital thermometer built for the **BBC micro:bit V2** using the **Microsoft MakeCode Editor**.
The project uses the micro:bit's built-in temperature sensor, LED matrix, buttons, and speaker to provide a visual and audible temperature monitoring system.

Developed with the **Microsoft MakeCode Editor**: https://makecode.microbit.org/#editor

## Features

### 1. LED Temperature Bar Graph

The 5×5 LED matrix displays the current temperature as a vertical bar graph.  
<img width="224" height="180" alt="Temperature Graph" src="https://github.com/user-attachments/assets/d315d7e0-82f6-4b53-886e-a488383e171d" />

---

### 2. Numeric Temperature Display

Press **Button A** to display the current temperature as scrolling text on the LED matrix instead of the bar graph.

<img width="234" height="185" alt="Numeric Temperature Display" src="https://github.com/user-attachments/assets/7fce51a6-64f4-4a42-9aac-edf1530a5917" />

---

### 3. Audible Temperature Warnings

The thermometer provides progressively stronger audible alerts as the temperature increases.

* **30°C – 39°C:** A short warning melody is played at regular intervals.
* **40°C – 49°C:** A louder alarm consisting of three repeating beeps is played.
* **50°C and above:** A rapid continuous alarm is activated, and a **skull icon** is displayed on the LED matrix to indicate a critical temperature.

<img width="228" height="183" alt="Critical Temperature Warning" src="https://github.com/user-attachments/assets/ecf86e2d-df76-4100-b8e5-8fbd513f7c9c" />  

The audible alerts continue until the temperature falls below the corresponding threshold.  

#### Sound Controls

* **Button B:** Mute all audible warnings.
* **Buttons A + B (simultaneously)** or **AB** on the back of the Microbit: Re-enable audible warnings.



