# MAKERMANIA 2026

## Innovation Project Workbook

> Program Duration: 1 June 2026 – 4 July 2026
>
> Location: MBF Tinkerers' Lab 007
>
> Team Size: 3–5 Students
>
> Goal: Identify a real-world problem and develop an innovative, patentable, and implementable solution.

---

# 1. Team Identity 

## 1.1 Team Name and Photo
<img width="1600" height="900" alt="Group photo" src="https://github.com/user-attachments/assets/1b1dbdaa-fc0c-4990-8285-51c80e2aa52b" />

---

## 1.2 Team Members

| Name | Role | Year | Skills |
|------|------|------|--------|
| Faizan&nbsp;Rabbani | | 2nd | Embedded Systems (ESP32, ESP32-S3, RPi Pico, Arduino) · FreeRTOS · ESP-NOW · Bluetooth Classic & LE · Wi-Fi · Sensor Interfacing · PCB Design (KiCad) · 3D Design & Printing (Fusion 360) · Laser Cutting · Hardware Debugging & Testing |
| Shalaka&nbsp;Sonje | | 2nd | |
| Pavitra&nbsp;Patil | | 1st | ESP32 / Arduino Fundamentals · Sensor Interfacing · LaserCAD & Laser Cutting · 3D Modelling & Printing |

---
## Useless Product
https://www.youtube.com/watch?v=37OpgQ1Qc6c

## 1.3  SCAMPER PPT
[PPT link](https://github.com/bitFaizan/MakerMania-2026-MindMesh/blob/e62c00793618741bcbeed3320611c6efa03701b6/docs/SCAMPER_MindMesh.pptx)


# 2. Problem Discovery

## 2.1 Observation Area

Where did you conduct your observations?

* Hostel
* Canteen
* Workshop
* Hospital
* Public Transport
* Home
* Other

---

## 2.2 AEIOU Observation Sheet

### Activities

What are users doing?
Completing sensor-based missions and challenges.
Exploring the house to find dark, warm, or magnetic locations.
Solving puzzles, collecting rewards, and leveling up.
Performing movement-based tasks like shaking, balancing, and staying still.

### Environment

What conditions affect them?

Indoor home environments (bedroom, living room, kitchen, etc.).
Different lighting, temperature, and magnetic conditions.
Safe spaces for movement and exploration.

### Interactions

Who or what are they interacting with?

The handheld game device (screen, buttons, LEDs, speaker).
Built-in sensors (light, motion, temperature, magnetometer).
Household objects and family members during multiplayer activities.

### Objects

What tools or products are used?

ESP32, TFT display, APDS9960, MPU6050, magnetometer, temperature sensor.
Speaker, WS2812B LEDs, buttons, battery.
Household items such as blankets, magnets, and warm objects.

### Users

Who are the primary users?

Children aged 6–11 years.
Secondary users: parents and teachers who supervise or assist gameplay.

---

## 2.3 Observation Log

| Observation                                 | Evidence                                              | Pain Point                                 |
| ------------------------------------------- | ----------------------------------------------------- | ------------------------------------------ |
| Kids enjoyed treasure hunt missions.        | High engagement during exploration tasks.             | Lost interest in repetitive missions.      |
| Children preferred story-based challenges.  | More excitement during "Alien" and "Dragon" missions. | Simple sensor tasks felt boring.           |
| Kids liked rewards and level progression.   | Frequently asked about unlocking new levels.          | Lack of rewards reduced motivation.        |
| Some tasks were difficult to understand.    | Needed help reading instructions.                     | Instructions should be simpler.            |
| Sound and LED effects increased excitement. | Strong reactions to alerts and animations.            | Too few visual effects reduced engagement. |


# 3. User Research

## 3.1 Interview Summary

Number of users interviewed: _5

## 3.2 Key Quotes
1.children enjoy adventure and story-based missions more than educational tasks.


2.Rewards, points, and level progression increase motivation.


3.Random missions keep the game interesting.


4.Visual and sound feedback make gameplay more engaging.


5.Difficulty should increase gradually as players level up.


---

## 3.3 User Persona

### Name

### Age

### Occupation

### Goals

### Frustrations

### Needs

---

# 4. Problem Framing

## Problem Statement

Children needs a way to stay physically active and engaged through interactive indoor activities because traditional games and educational activities can become repetitive and less motivating over time.__.

---

## How Might We Questions

1.

2.

3.

---

## Opportunity Ranking

| Criteria         | Score |
| ---------------- | ----- |
| Severity         |       |
| Frequency        |       |
| Feasibility      |       |
| Novelty          |       |
| Market Potential |       |
| Total            |       |

---

# 5. Solution Ideation

## Brainstormed Ideas

| Idea | Advantages | Challenges |
| ---- | ---------- | ---------- |
|      |            |            |
|      |            |            |

---

## Selected Concept

Why was this concept chosen?

This concept was chosen because it combines STEM learning, physical activity, and interactive gameplay into a single experience. Many children spend significant time on passive screen-based entertainment, which can reduce physical activity and engagement with their surroundings.

The proposed device encourages children to:


1. Explore their home environment.

2. Learn scientific concepts such as light, temperature, motion, and magnetism through play.

3. Stay physically active while completing missions.

4. Remain engaged through rewards, levels, challenges, and storytelling.

Additionally, the concept is technically feasible using affordable sensors and has the potential to provide a fun, educational, and reusable learning experience for children aged 6–14 years.

---

# 6. System Design

## High-Level Description

Explain your solution.

---
## System Architecture
https://github.com/bitFaizan/MakerMania-2026-MindMesh/blob/7f59693fe44dfb7642426f4cc8876c6e7a04f7f5/images/pathfinder_system_architecture.svg

## Block Diagram

https://github.com/bitFaizan/MakerMania-2026-MindMesh/blob/d8038770b9b0a6f1e90658749bfeef002117fcc3/images/pathfinder_block_diagram_clean.png

---

## Inputs

List sensors, user inputs, data sources.

---

## Outputs

List displays, actuators, software outputs.

---

# 7. Technical Planning

## Bill of Materials

| Category | Component | Specification | Qty | Approx. ₹ | Link |
|----------|-----------|---------------|----:|----------:|------|
| **MCU** | ESP32-S3 Super Mini | N4R2 (4MB Flash + 2MB PSRAM) | 1 | 469 | https://hubtronics.in/esp32-s3-supermini-board |
| **External Storage** | W25Q128 SPI Flash Module | 128 Mbit (16MB) | 1 | 120 | https://www.flyrobo.in/w25q128-128m-bit-flash-storage-module |
| **Display** | ILI9341 SPI TFT Display | 1.8" 128x160 Color TFT | 1 | 294 | https://robocraze.com/products/1-8-inch-tft-lcd-module?variant=40194139095193&country=IN&currency=INR&utm_medium=product_sync&utm_source=google&utm_content=sag_organic&utm_campaign=sag_organic&campaignid=22116884086&adgroupid=&keyword=&device=m&gad_source=1&gad_campaignid=22113249746&gbraid=0AAAAADgHQvbua7aG_WkYCTwxgxn5ZovKb&gclid=CjwKCAjw9NjRBhATEiwA_p2J8WH4ppD888B0LVwjfNiMKOFQ-X85lYHgbT1Ty4mDLfVd4O5kB8B9dhoCN80QAvD_BwE |
| **Audio** | MAX98357A | I²S Digital Audio Amplifier | 1 | 134| https://hubtronics.in/max98357a-stereo-amplifier-module |
| | Speaker | 8Ω 1W 28mm | 1 | 60 | https://probots.co.in/8-ohm-1w-2415-mm-oval-mini-audio-speaker.html |
| **Sensors** | APDS9960 | Gesture + RGB + Ambient Light + Proximity | 1 | 247| https://robu.in/product/apds9960-rgb-gesture-sensor-detection-i2c-breakout-module/ |
| | MPU6500 | 3-Axis Accelerometer + Gyroscope | 1 | 170 | https://robu.in/product/mpu6500-gyroscope-accelerometer-digital-motion-processor-dmp-6-axis-motion-sensor-with-i2c-spi-interface/  |
| | MAX30102 |Heart rate & Sp02 | 1 |120|https://www.flyrobo.in/gy-max30100-pulse-oximeter-heart-rate-sensor-development-board?tracking=ads&tracking=4a9a9a&gad_source=1&gad_campaignid=17426303996&gbraid=0AAAAAC6AkE_weY_bxNC5nEjj0xWWSxzWx&gclid=CjwKCAjw0dPRBhAPEiwAE5vTTtHxikMV1QpJ_Qa2RiY5fvUDgVDxP-I4UzZZ2vwzktsXwlzXjRVQ1hoC-ToQAvD_BwE  |
| | QMC5883L | 3-Axis Magnetometer | 1 | 164 | https://www.flyrobo.in/gy-271-qmc5883l-3-axis-electronic-compass-module-magnetic-field-sensor |
| | MLX90614 | Non-contact IR Temperature Sensor | 1 | 674 | https://robu.in/product/mlx90614-esf-non-contact-human-body-infrared-temperature-measurement-module/ |
| **Lighting** | WS2812B LEDs | 20 × Individually Addressable RGB LEDs | 20 | 95 | https://hubtronics.in/ws2812b-5050-led |
| **Haptics** | Coin Vibration Motor | 1034 ERM (10×3.4mm, 3V) | 1 | 30 | https://www.flyrobo.in/1034-3v-flat-motor?tracking=ads&tracking=4a9a9a&gad_source=1&gad_campaignid=17426303996&gbraid=0AAAAAC6AkE_weY_bxNC5nEjj0xWWSxzWx&gclid=CjwKCAjw0dPRBhAPEiwAE5vTTusDCopbeCECv82Od6AZetLfyB4-6Lixyd2sunzWefowDhXiV-SItxoC7TUQAvD_BwE |
| **Power** | LiPo Battery /18650 Li-ion | 3.7V 1000mAh | 1 | 380 | https://robu.in/product/wly102050-1000mah-3-7v-single-cell-rechargeable-lipo-battery/?gad_source=1&gad_campaignid=17427802559&gbraid=0AAAAADvLFWcH1QsNu4yu5-7gAhiQl8WD_&gclid=CjwKCAjw9NjRBhATEiwA_p2J8aa8utVyPJU_Z3qiq0VIpvFHz8700kfJqL5RVB0Uj4qS8GCwLUXb4xoCAcwQAvD_BwE |
| | TP4056 | LiPo Charging Module with Protection | 1 | 45 | https://www.amazon.in/Charging-Lithium-Battery-Overcharge-Protection/dp/B0H2FGVLT7 |
| | LDO | Low Dropout regulator 5v to 3.3v | 1 | 70 | https://evelta.com/7semi-5v-to-3-3v-1a-ldo-low-dropout-regulator-breakout-with-enable/ |
| **User Input** | Large Push Button | 12×12mm Tactile | 1 | 30 | |
| | Small Push Button | 6×6mm Tactile | 1 | 15 | |
| **Power Control** | Slide Switch | Mini SPDT | 1 | 5 | https://rajivelectronics.com/product/ss12f44g5-on-off-spdt-1p2t-2-position-3-pin-pcb-panel-mini-vertical-slide-switch |
| **Miscellaneous** | MOSFET | A03400 | 3 | 24 | https://robu.in/product/ao3400-xblw-30v-5-8a-34m%CF%894-5v5a-1-4w-700mv250ua-1-n-channel-sot-23-3l-mosfets-rohs/ |
| | JST PH Connector | 2.0 2 pin | 2 | 10 | |


## Electronics

| Component | Purpose |
| --------- | ------- |
|           |         |
|           |         |

---

## Software

| Tool | Purpose |
| ---- | ------- |
|      |         |
|      |         |

---

## Mechanical / CAD

Describe fabricated components.

---

# 8. Prototype Development

## Version 1

Description:Developed the first functional prototype of a handheld educational adventure device using an ESP32-S3. The prototype integrates motion sensing (MPU6500), compass navigation (QMC5883L), environmental sensing (DHT), vibration feedback, and a TFT display. A basic mission system was implemented where users complete interactive challenges such as shaking, orientation detection, temperature-based tasks, and direction-finding activities. The prototype focuses on validating core gameplay mechanics and sensor functionality before hardware miniaturization and PCB development.

Lessons Learned:

I²C sensor integration requires careful address management and bus testing.

Early breadboard prototyping significantly reduces debugging time before PCB design.

Motion-based activities using the MPU6500 provide engaging gameplay opportunities.

Compass calibration is essential for accurate direction-based tasks.

Using modular sensor breakout boards speeds up development and testing.

TFT display readability and UI design greatly affect user experience.

Power management must be considered early when using battery-powered devices.

Iterative testing helped identify practical and fun mission ideas for children.

Simple game mechanics are often more engaging than overly complex challenges.

Designing around available components allows rapid prototype development and validation.


## Version 2

Description:

Lessons Learned:

---

## Final Prototype

Description:

---

# 9. Testing & Validation

## Testing Plan

| Test | Success Criteria |
| ---- | ---------------- |
|      |                  |
|      |                  |

---

## User Feedback

| User | Feedback | Action Taken |
| ---- | -------- | ------------ |
|      |          |              |

---

# 10. Innovation Assessment

## Existing Solutions

List competing products.

---

## What Makes This Different?

---

## Innovation Score

| Parameter       | Score |
| --------------- | ----- |
| Novelty         |       |
| Technical Depth |       |
| Feasibility     |       |
| Impact          |       |
| Scalability     |       |

---

# 11. Intellectual Property

## Prior Art Search

Patents / Products Found:

---

## Novel Features

1.

2.

3.

---

## Provisional Patent Draft

### Title

### Abstract

### Problem

### Solution

### Claims

---

# 12. Business & Deployment

## Target Users

---

## Estimated Cost

---

## Market Opportunity

---

## Sustainability Considerations

---

# 13. Final Demonstration

## Prototype Images

Insert photos.

---

## Demonstration Video Link

---

## GitHub Repository

---

## Presentation Link

---

# 14. Reflection

## What Worked Well?

---

## What Failed?

---

## Key Learnings

---

## Next Steps

* Patent Filing
* Startup Exploration
* Product Development
* Research Publication
* Competition Submission

---

# 15. Final Deliverables Checklist

* Problem Discovery Complete
* User Interviews Complete
* Persona Created
* Problem Statement Finalized
* System Design Complete
* Prototype Demonstrated
* Testing Completed
* Patent Draft Prepared
* Presentation Submitted
* GitHub Repository Updated

---

# MAKERMANIA FINAL PITCH

Each team will present:

1. Problem
2. User Research
3. Insights
4. Solution
5. Prototype Demo
6. Innovation & Patentability
7. Future Roadmap

Presentation Time: 5 Minutes

Q&A: 3 Minutes
