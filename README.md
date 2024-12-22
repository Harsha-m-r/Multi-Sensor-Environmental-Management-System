# Multi-Sensor Environmental Management System

## Course Name and Code

**Linear Integrated Circuits 23EVTC206**

## Faculty In Charge

**Pallavi H**

## Team Members

- Amogh P
- Sahil P
- Harsha M R
- Amoghraj N

## Abstract

In this project, we aimed to address and mitigate the challenges faced by workers in a nut and bolt manufacturing factory through the implementation of sustainable energy solutions and advanced sensor technologies. Our primary focus was on enhancing workplace safety, comfort, and energy efficiency. We installed solar panels to harness renewable energy, significantly reducing the factory's dependency on non-renewable power sources and lowering overall energy costs.

To further optimize energy usage and improve working conditions, we integrated several smart sensors into the factory's infrastructure. Light Dependent Resistors (LDRs) were used to automate the lighting system, ensuring lights are only on when necessary and conserving energy. Thermostats are used to monitor ambient temperature and control exhaust fans, maintaining an optimal working environment by regulating temperature and ventilation. Additionally, MQ2 gas sensors are used to detect smoke, automatically activating a buzzer/siren. This proactive approach safeguards workers from potential health risks.

Through these innovations, our project demonstrates a comprehensive approach to improving industrial working conditions by leveraging sustainable energy and intelligent sensor technology. The implementation of these solutions showcases a practical and scalable model for other manufacturing units aiming to enhance worker well-being and operational efficiency while promoting environmental sustainability.

## Introduction

### 1.1 Background

This project enhances sustainability and worker safety in manufacturing by integrating solar energy and sensor technologies. Solar panels reduce the carbon footprint, while LDRs, thermostats, and MQ2 sensors improve energy efficiency, safety, and comfort. This approach promotes environmental responsibility and operational improvements.

### 1.2 Objectives

- **Implement Sustainable Energy**: Install solar panels to reduce dependency on non-renewable energy sources and promote environmental sustainability within the factory.
- **Enhance Worker Safety**: Utilize sensors like the MQ2 gas sensor to detect smoke, ensuring early warning systems for fire hazards and triggering immediate alerts to prevent accidents.
- **Improve Working Conditions**: Use thermostats to regulate temperature and activate exhaust fans as needed, providing a comfortable and safe working environment for the workers.
- **Optimize Energy Usage**: Utilize light-dependent resistors (LDR) to automate lighting based on ambient light levels, reducing energy consumption while ensuring adequate illumination.
- **Demonstrate Cost-Efficiency**: Showcase how integrating sustainable energy and smart sensor technologies can lead to long-term cost savings for the factory while improving worker productivity.
- **Promote Environmental Responsibility**: Raise awareness about the benefits of renewable energy and efficient resource utilization, encouraging other industrial setups to adopt similar practices.

### 1.3 Relevance to SDGs

- **Goal 7: Affordable and Clean Energy**: The use of solar panels provides clean and renewable energy to the factory, reducing reliance on non-renewable energy sources and promoting affordable and clean energy access.
- **Goal 9: Industry Innovation and Infrastructure**: Integrating solar panels and sensors represents innovation in industrial infrastructure, improving efficiency and reducing environmental impact.
- **Goal 11: Sustainable Cities and Communities**: By using sustainable energy and sensors for safety, the project improves working conditions, contributing to safer and more sustainable communities around the factory.
- **Goal 13: Climate Action**: Solar energy reduces the factory's carbon footprint by decreasing reliance on fossil fuels, supporting efforts towards mitigating climate change and promoting sustainable practices.

## Methodology

### Project Design

- **BLOCK DIAGRAM**

### Explanation of Block Diagram

- A 12V solar panel is used for sustainable energy. If the solar energy is insufficient due to clouds or other factors, a 220V AC source is used.
- LDR (Light Dependent Resistor) senses light and controls the relay of tube lights via an OpAmp.
- Thermistor (Temperature Dependent Resistor) senses temperature and controls intake and exhaust fans via an OpAmp.
- MQ-2 (Smoke Sensor) detects smoke and controls buzzers via an OpAmp.

### Components Used

|        Component        | Specification | Quantity |
| :---------------------: | :-----------: | :------: |
|       Solar Panel       |      12V      |    1     |
| Transformer (step down) | 12-0-12V, 5A  |    1     |
|        Rectifier        | Diode Bridge  |    1     |
|        Batteries        |     3.3V      |    3     |
|           LDR           |   3V-5V DC    |    2     |
|       Thermistor        |   103 (10K)   |    1     |
|      Smoke Sensor       |     MQ-2      |    1     |
|         OpAmps          |      741      |    3     |
|         Relays          |      5V       |    2     |
|          LEDs           |   Any color   |    3     |
|         DC Fan          |      12V      |    1     |
|         Buzzer          |      3V       |    1     |

### Sensor Data

- **LDR (Light Dependent Resistor)**:
  - Distance vs. Voltage and Resistance
    - 10 cm: 4.5V, 1000 Ω
    - 20 cm: 3.6V, 500 Ω
    - 40 cm: 2.8V, 250 Ω
    - 80 cm: 1.9V, 125 Ω
    - 160 cm: 1.1V, 62.5 Ω
- **MQ-2 Gas Sensor**:
  - Gas Concentration (ppm) vs Voltage (V):
    - 100 ppm: 1.2V
    - 200 ppm: 1.5V
    - 400 ppm: 1.9V
    - 800 ppm: 2.3V
    - 1600 ppm: 2.7V
- **Thermistor**:
  - Temperature (°C) vs Resistance (Ω):
    - 0°C: 5000 Ω
    - 10°C: 4000 Ω
    - 20°C: 3000 Ω
    - 30°C: 2000 Ω
    - 40°C: 1500 Ω
    - 50°C: 1000 Ω

### Circuit Design and Simulation
  - **Liight sensor** 

    ![Light sensor](<images/circuit_diagram/Light sensor.png>)
 - **Temperature controlled fan** 
  
   ![Temp fan](<images/circuit_diagram/TEmo control fan.png>)
- **Smoke sensor**
  
   ![smoke sensor](<images/circuit_diagram/smoke sensor.png>)
  



### Implementation

- **Snapshots**: 


## Results and Discussions

- Data and observations from practical implementation.
- Comparison with simulation results.

## Contribution to Sustainable Development Goals (SDGs)

- **Goal 7: Affordable and Clean Energy**: Utilization of solar panels for clean, renewable energy.
- **Goal 9: Industry Innovation and Infrastructure**: Innovation through advanced sensor technologies.
- **Goal 11: Sustainable Cities and Communities**: Improved working conditions and community safety.
- **Goal 13: Climate Action**: Reduced carbon footprint through solar energy.

## Conclusions

The project successfully enhanced the working environment in a nut and bolt manufacturing factory by integrating sustainable energy solutions and advanced sensor technologies. The implementation of solar panels, LDRs, thermostats, and MQ2 gas sensors improved worker safety, comfort, and energy efficiency. This project demonstrates a practical, scalable model for other industrial setups, contributing to several key SDGs and promoting a sustainable and safe working environment.

## Acknowledgments

B. V. B. College of Engineering & Technology  
B. V. Bhoomaraddi College Campus, Vidyanagar, Hubballi 580031, Karnataka, India  
Tel: +91 - 836 - 2378250  
Fax: +91 - 836 - 2374985  
[www.kletech.ac.in](http://www.kletech.ac.in)
