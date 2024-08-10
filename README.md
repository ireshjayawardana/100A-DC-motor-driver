## Introduction

This project involves the design and implementation of a **80A/30V Half-Bridge PCB** using **Altium Designer**. The PCB is equipped with high-speed gate drivers capable of driving MOSFETs at speeds up to **1MHz**. The design focuses on achieving high efficiency and reliability, making it suitable for applications requiring rapid switching and high current handling.

Key features of the design include:
- **High-Speed Gate Drivers**: (Tested 20A) Ensuring precise control and fast switching of MOSFETs - LM5109BMA.
- **80A Current Handling**: Capable of managing high current loads with minimal losses-Rohm RD3G07BBG N ch power mosfets.
- **Optimized Layout**: Designed to minimize parasitic inductance and resistance, enhancing overall performance, Shorter and wider tracks to drive gates avoid short throughs.
- **Thermal Management**: Incorporating effective heat dissipation techniques to maintain operational stability, Solder mask removeed over the Hi current paths, ehanced with solder after manufacturing.
- **Shunt Current sensor**: Based on Current sense amplifier INA180 and a 0.5mOhm resistor, Ideal for low side current measuring for protection and FOC control in BLDC motors.


This PCB design is ideal for power electronics applications such as motor drives, power inverters, and other high-power switching systems.

![image](https://github.com/user-attachments/assets/f7f297ad-952c-44a9-99bd-866235dc6eb3)
3D modal of the layout - top

Terminal wire connectors are used for power in and out, but are not rated above 20A, Direct soldering to the PCB is recommended. Bootstrap capacitors and diodes were chosed according to the LM5109BMA application notes.

![image](https://github.com/user-attachments/assets/81717fb8-493c-4f36-b39a-f346f080962d)
3D modal of the layout - bottom

Use case - International future energy challenge 2020 - best participant award
video demonstration - https://drive.google.com/file/d/1KCNZwbfYyB2SS2QFnANqthyECo4qD7X-/view
![image](https://github.com/user-attachments/assets/1c03d337-5f0f-4506-a1dc-b85fe6a594a2)
