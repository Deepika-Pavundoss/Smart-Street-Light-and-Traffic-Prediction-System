# Smart-Street-Light-and-Traffic-Prediction-System

## Abstract:

The project involves a smart street light system which switches ON the street lights at night on detecting the presence of any human or vehicle otherwise, the street lights are turned OFF. Also to visualize the traffic pattern.

## Hardware Used:

1. **Node MCU**:
It is based on the ESP8266 Wi-Fi module. It allows developers to easily create Wi-Fi enabled IoT (Internet of Things) projects. Sensors and actuators have been integrated with NodeMCU. The NodeMCU takes in sensor values, processes them and the actions to be performed (by actuators-LED) based on the sensor data have been coded on Arduino IDE and then loaded into NodeMCU. The NodeMCU being WiFi enabled, enables us to easily connect with cloud platforms. Here, ThingSpeak has been used. 

2. **IR Sensor**:
An IR (infrared) sensor is a device that detects and responds to the infrared radiation emitted or reflected by objects. It is used to detect the presence of any person or vehicle in the area to switch on or off the lights accordingly and followed by calculating the traffic pattern using the same sensor.

3. **LDR (Light Dependent Resistor)**:
It is a sensor that detects changes in light levels. It is also known as a photoresistor or photocell. It is used to detect the presence or absence of light to smartly switch on or off the street lights.

4. **LED (Light Emitting Diode)**: 
It is a semiconductor device that emits light when an electric current is passed through it. Here LED is used to represent the street lights in this project.

## Flowchart:

![image](https://user-images.githubusercontent.com/83827603/237008497-58a5344d-998d-4ba5-b660-1dceabc3fb2d.png)

1. Design: Design the prototype and the requirements of the system

2. Sensors Required: Light Dependent Resistor (LDR) to detect the presence of light in streets and Infrared (IR) sensor to detect presence of people and vehicles in street.

3. Microcontroller: ESP8266 has been used to facilitate integration with all sensors, obtaining the sensor data and processing them, send them to the Cloud platform. The Actuator – LED is made to perform action (glow or not glow) according to the code and requirement.

4. IoT Cloud: ThingSpeak has been used to Visualize the each of the processed data from the microcontroller.

5. LED (Light Emitting Diode): It represents the street lights which work as:

    - Glow when people are present and its dark outside
  
    - Off when street is empty
  
    - Off during day time

## Hardware Connections:

![image](https://user-images.githubusercontent.com/83827603/237011348-504a091c-193c-4a59-8081-ea4872147562.png)

![image](https://user-images.githubusercontent.com/83827603/237011619-2b328e57-c209-4b1e-ac99-97cac9f3385a.png)

## Demonstration:

1. **During the day, when light is detected so street lights are kept OFF**

    ![image](https://user-images.githubusercontent.com/83827603/237011824-2c9d5d21-95fd-4716-8a6a-bed2314e9f43.png)

2. **During the night, when light is not detected and vehicles are detected so street lights are kept ON**
    
    ![image](https://user-images.githubusercontent.com/83827603/237012011-a21764f9-3c7f-4c0d-97a6-e42eb62e84bf.png)

3. **During the night, but vehicles are absent so street lights are kept OFF**

    ![image](https://user-images.githubusercontent.com/83827603/237012128-30505385-d375-4f13-93f2-bc0f7c9ac965.png)

4. **During day, irrespective of vehicles are present or absent, street lights are kept OFF**

    ![image](https://user-images.githubusercontent.com/83827603/237012383-a27a133a-f819-46d3-9ca4-6b4981dad554.png)

## Matlab Code for Visualization:

![image](https://user-images.githubusercontent.com/83827603/237018815-5a994a98-b235-4ddd-b8f8-5b5e15e9558f.png)

## Output at ThingSpeak:

![image](https://user-images.githubusercontent.com/83827603/237014614-de25b695-10ab-4118-a850-77166ecd4f02.png)

![image](https://user-images.githubusercontent.com/83827603/237014736-0090832d-1e5f-4e5e-bef1-eccfcee863a1.png)

![image](https://user-images.githubusercontent.com/83827603/237018523-c6d12ddd-7640-41e8-8317-951016550d74.png)


