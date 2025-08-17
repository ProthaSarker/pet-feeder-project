# pet-feeder-project
##  Overview
This is an inexpensive programmable pet feeder that can be used in shelters for animals. It automates frequent feeding, tracks consumed food, and provides notification to workers in instances where feeding is a challenge. It uses the application of sensors, motors, and common sense logic in feeding pets regularly at an inexpensive rate.

## Features
- Eating at regular time intervals (08:00 AM and 06:00 PM)
- Store hopper at food level
Pre- and post-feeding bowl weight monitoring
-Absence of food non-presence or non-ingestion notifications
- Tracking success/failure Feeding records
- Economically engineered with cheap material

## Requirements
-
- **Hardware Components:**
- Servo motor (food dispenser) 
- Real-time clock module
- Hopper food level sensor
- Bowl weight sensor (±5g tolerance)
- Microcontroller (e.g., Arduino, Raspberry Pi)
- Alert system (through buzzer or SMS module)
- Power supply with optional battery backup

- **Software Requirements:**
- Logic-based control algorithm
- Logging system (CSV or local database)
- Optional: Integration via alert application or SMS

## Installation
1. Assemble hardware components based on the system diagram
2. Microcontroller motor and sensor.
3. Program the control algorithm in its microcontroller.
4. Set the feeding time and quantity of food.
5. Check motor rotation and sensor.
6. Alert and logging system.


## Usage
- Runs the system and verifies the current time.
- It searches for feeding schedule, then it searches for food availability.
- Problems ~100g of rations if there are rations available.
- It checks every 10 minutes whether the pet has eaten.
- Alarms sound if the food was not released or eaten.
-The feeding history is updated after every attempt at feeding.


## Restrictions 
- Not ideal for dispensing moist food
- Fixed schedule of feeding, no adaptive adjustment
- Separate bowls for each system
- ±5g limited sensor accuracy
- Manual intervention needed upon triggering of alerts
-No multi-pet distinction in current version

##  Future Enhancements
- Variable portion sizes
- App-based notifications and remote control
-Motion- or camera-based detection of pets
- Machine learning to change feeding behavior
- Multi-pet mode w/ ID
- Improvements in error handling and diagnostics
- Business continuity battery backup

## Integrating the AI Agent

Microsoft Copilot was utilized for:

- Updation and optimization of algorithm logic
- Suggest variable renaming and fault detection improvements
 - Give this professional README.md template
 - Explain ethical issues relating to automated pet care 

## Ethical Issues 
-Avoiding dependency in the use
 - Providing human control in the event of system failure Pet privacy in the context of camera use
 -Developing AI systems for constructive, people-centric applications ---

