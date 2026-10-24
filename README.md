# AQUASPLASHBOT — Smart Water Quality Monitoring and Surface Waste Collection Robot

An innovative, modular solution designed to monitor water quality and collect floating waste from water bodies, helping protect aquatic ecosystems and promote cleaner, healthier environments.

## Revolutionizing Water Body Management: The AQUASPLASHBOT Project

Water pollution is a growing environmental challenge that threatens aquatic ecosystems, public health, and the sustainability of freshwater resources. Floating plastic, discarded packaging, and other surface debris accumulate in lakes, ponds, and reservoirs, while changes in water quality may go unnoticed without regular monitoring.

AQUASPLASHBOT addresses these challenges through an integrated system combining water quality monitoring with robotic surface waste collection. Its two-module architecture aims to improve pollution awareness and reduce dependence on labour-intensive manual cleaning.

## The Water Pollution Challenge

Water bodies face multiple threats, including floating litter, suspended particles, and changing chemical conditions. Conventional cleaning methods often require manual intervention, while periodic water testing provides only limited snapshots of water quality.

In Tamil Nadu, maintaining lakes, ponds, reservoirs, and other freshwater resources is important for communities, biodiversity, and sustainable water management. Affordable technologies that support both pollution monitoring and waste collection can help communities identify problems and manage water bodies more effectively.

AQUASPLASHBOT focuses on addressing these challenges through accessible electronics, modular hardware, and automation.

## A Sustainable Mission

AQUASPLASHBOT's mission is to contribute to cleaner water bodies through technology-assisted monitoring and surface waste collection.

The project aims to combine two complementary capabilities: monitoring selected water quality parameters and collecting floating debris. By integrating these functions into a modular platform, AQUASPLASHBOT seeks to support more informed environmental management while encouraging responsible water resource conservation.

Its long-term vision is to develop an affordable, scalable system that can be adapted to different water bodies and expanded as additional technologies become available.

## Introducing the AQUASPLASHBOT Solution

AQUASPLASHBOT consists of two interconnected project modules:

### 1. AQUASPLASH NODE — Water Quality Monitoring Unit

AQUASPLASH NODE is designed to monitor selected water quality parameters using sensors connected to an ESP32 microcontroller.

Its proposed capabilities include:

* **Turbidity monitoring:** Estimates water cloudiness caused by suspended particles.
* **pH monitoring:** Measures the acidity or alkalinity of water.
* **Temperature monitoring:** Tracks water temperature variations.
* **Pollution indication:** Uses LED indicators to communicate predefined water quality categories.
* **Alert mechanism:** Can use a buzzer to indicate readings that cross configured thresholds.
* **Data connectivity:** Can be extended to transmit readings wirelessly for remote monitoring.

The collected measurements can help identify changes that warrant further investigation. These parameters do not independently establish whether water is safe for drinking or determine the presence of every pollutant.

### 2. AQUASPLASHBOT — Robotic Surface Waste Collection Unit

AQUASPLASHBOT is a catamaran-style floating robot designed to collect floating waste from the water surface.

Its proposed design incorporates:

* **Catamaran hull:** Two floating hulls provide a platform for the collection mechanism.
* **Conveyor-based collection:** An inclined conveyor moves floating debris into a collection bin.
* **ESP32-based control:** Manages motor operation and coordinates the robot's functions.
* **Differential-thrust propulsion:** Uses two independently controlled motors to support forward movement and turning.
* **Waste collection bin:** Stores collected debris for removal and disposal.
* **GPS waypoint navigation:** Can be incorporated to support predefined route navigation.
* **Smart return logic:** Future upgrades can detect a full collection bin and initiate a return-to-station sequence.

Together, these modules aim to combine environmental monitoring with practical waste collection in a single project ecosystem.

## A Smart and Scalable Technology Platform

AQUASPLASHBOT is designed around accessible, modular technologies that can support future improvements.

The proposed technology stack includes:

* **Microcontroller:** ESP32 development board.
* **Sensors:** Turbidity, pH, and water temperature sensors.
* **Actuation:** DC motors, motor drivers, and conveyor mechanism.
* **Navigation:** GPS module for future waypoint-based navigation.
* **Power system:** Rechargeable battery with suitable voltage regulation and protection.
* **Communication:** Potential wireless data transmission for remote monitoring.
* **Software:** Embedded firmware for sensor acquisition, classification, and motor control.

The modular architecture allows the monitoring unit and robotic collection unit to be developed, tested, and improved independently before further integration.

## A Glimpse into the Future

AQUASPLASHBOT envisions evolving from a prototype into a more capable water body management platform.

Potential future developments include:

* **Autonomous waypoint navigation:** Planning and following predefined routes across selected water areas.
* **Automated docking and recharging:** Returning to a designated station when battery levels are low.
* **Intelligent waste management:** Detecting collection-bin capacity and optimizing collection routes.
* **IoT dashboard:** Displaying sensor readings, operating status, and historical measurements.
* **Pollution mapping:** Combining location-tagged readings to visualize variations across monitored areas.
* **Solar-assisted charging:** Exploring solar energy to extend operating time.
* **Advanced pollution detection:** Evaluating additional sensors for specific contaminants.
* **Modular collection attachments:** Investigating suitable methods for collecting different categories of floating debris.

These developments would be subject to engineering validation, field testing, safety assessment, and cost evaluation.

## Overcoming Challenges and Ensuring Reliability

Developing a practical water-cleaning robot requires careful attention to mechanical, electrical, and environmental constraints.

AQUASPLASHBOT must address challenges such as:

* **Waterproofing:** Protecting electronics and electrical connections against water ingress.
* **Stability:** Maintaining buoyancy and balance under varying collection loads.
* **Power management:** Coordinating propulsion, sensing, and conveyor operation within battery limits.
* **Collection efficiency:** Designing the conveyor and intake mechanism to handle floating debris effectively.
* **Sensor reliability:** Calibrating sensors and accounting for measurement uncertainty.
* **Navigation reliability:** Managing GPS limitations, obstacles, currents, and communication interruptions.
* **Environmental safety:** Avoiding harm to aquatic organisms and preventing collected waste from re-entering the water.
* **Maintenance:** Ensuring that the collection mechanism, sensors, and propulsion system can be inspected and serviced easily.

These considerations are essential for progressing from a controlled prototype to reliable operation in real water bodies.

## A Commitment to Sustainable Development

AQUASPLASHBOT primarily aligns with **United Nations Sustainable Development Goal 6 (Clean Water and Sanitation)**, particularly Target 6.3, which addresses improving water quality and reducing pollution.

The project also supports the broader objectives of:

* **SDG 14 — Life Below Water:** Contributing to efforts to reduce marine pollution, subject to appropriate deployment and environmental safeguards.
* **SDG 12 — Responsible Consumption and Production:** Encouraging responsible waste collection and disposal.
* **SDG 11 — Sustainable Cities and Communities:** Supporting cleaner urban lakes, ponds, and other local water bodies.

By focusing on pollution monitoring, floating waste collection, and modular engineering, AQUASPLASHBOT aims to contribute to more sustainable water resource management.

## Conclusion

AQUASPLASHBOT presents an integrated approach to water body management by combining sensor-based water quality monitoring with a catamaran-style robotic waste collection system.

Through AQUASPLASH NODE and AQUASPLASHBOT, the project aims to improve awareness of water quality changes, collect floating debris, and reduce dependence on manual cleaning alone.

With further prototype development, systematic testing, and collaboration with environmental organizations and local authorities, AQUASPLASHBOT could evolve into a practical tool for supporting cleaner and healthier water bodies.

**AQUASPLASHBOT — Monitor Water. Collect Waste. Protect Our Future.**
