[![Review Assignment Due Date](https://classroom.github.com/assets/deadline-readme-button-24ddc0f5d75046c5622901739e7c5dd533143b0c8e959d652212380cedb1ea36.svg)](https://classroom.github.com/a/kzkUPShx)
# a14g-final-submission

    * Team Number: T08
    * Team Name: Magic Curtain Opener
    * Team Members: Weiheng Zhuang & Yining Xia
    * Github Repository URL: https://github.com/ese5160/a14g-final-submission-t08-magic-curtain
    * Description of test hardware: Win11 Desktop, SAMW25 Custom board

## 1. Video Presentation

Click on photo below to view the vedio

[![Final Project Demo Video](image/device.jpg)](https://www.youtube.com/watch?v=DNdOzl5xq_A "Final Project Demo Video")

## 2. Project Summary



## 3. Hardware & Software Requirements

### 3.1 Software Requirements:

**HRS 01 (System Composition)**: The system shall be based on a customized PCB board with SAM W25 microcontroller, photoresistor, tempertature and humidity, servo motor, LCD screen, air quality IC, IR receiver, ensuring component compatibility.

- Check, We used our custome PCB for Demo and video

**HRS 02 (Sensor and Motor Functionality)**: All sensors and motors shall perform efficiently and reliably under defined conditions.

- Check, we used a 160x128 LCD screen to present sensors data and also add a CLI command to show data and drive motor

**HRS 03 (Curtain Opener Housing)**: The housing shall robustly enclose all electronics, protecting them from environmental factors.

- Check, we used a 3D printing case to achieve it

**HRS 04 (Mounting and Positioning)**: The curtain opener should mount securely on a curtain rod, with the servo motor's wheel in contact with the rod for precise movement control.

- Check, we have it in the demo as well as video

### 3.2 Software Requirements:

**SRS 01 (Curtain and Environment Data Retrieval)**: The system shall enable users to access real-time curtain status and environmental data (temperature, humidity, air quality) via a smartphone app.

**SRS 02 (Curtain Time Adjustment)**: The system shall allow users to modify curtain operating times through the app.

**SRS 03 (Manual Curtain Opening)**: The app shall provide a feature to open curtains using an “Open Curtain” button.

**SRS 04 (Automated Curtain Opening by Time)**: Users shall be able to set specific times for automatic curtain opening in the app.

**SRS 05 (Automated Curtain Opening by Sunlight)**: With “Smart Decision” mode, the system shall open curtains automatically in intense sunlight.

**SRS 06 (Manual Curtain Closing)**: The app shall include a “Close Curtain” button for manual curtain closure.

**SRS 07 (Automated Curtain Closing by Time)**: Users shall be able to program specific times for automatic curtain closure.

**SRS 08 (Automated Curtain Closing by Low Sunlight)**: In “Smart Decision” mode, the system shall close curtains in low sunlight conditions.

**SRS 09 (Remote Control)**: Users shall operate the openess of curtain via remote control.

**SRS 10 (Curtain Opening Constraint)**: The system shall prevent curtain opening if already open.

**SRS 11 (Curtain Closing Constraint)**: The system shall prevent curtain closing if already closed.

## 4. Project Photos & Screenshots
