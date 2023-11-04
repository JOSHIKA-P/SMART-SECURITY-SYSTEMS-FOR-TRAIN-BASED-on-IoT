# Smart Security Systems for Trains based on IoT

## Problem Statement

The unavailability of precise methods for accident occurrence detection alongside a reliable locating tool with a quick reporting feature is the major problem under research. Due to the delay in the arrival of the ambulance to the accident spot, it causes the loss of human life. So, it is necessary to take the accident victim to the hospital as early as possible. The proposal combines independent and complementary solutions in a global accident detection system to provide stable and accurate positioning of a train accident even in severe urban environments. The proposed solutions consist of augmenting the navigation solution exploiting the inertial sensor to estimate the dynamics of the train to extract the accident.

Develop a system that offers security to the train using the Internet of Things (IoT). The system must be able to perform user authentication for access control and monitor the train for suspicious activity. It must keep the train secured by notifying the user via SMS.

The problem statement of fair accidents in trains can be described as the occurrence of accidents in trains that affect passengers or railway workers, which are caused by factors such as inadequate safety measures, poor maintenance of railway infrastructure, human error, or other external factors.

The issue of fair accidents in trains can be particularly concerning as it can result in the loss of life, injuries, and significant damage to property. It is important to identify the root causes of such accidents and implement measures to prevent them from happening in the future. Additionally, it is critical to ensure that appropriate compensation is provided to those affected by such accidents, and that safety standards are upheld to prevent future incidents.

## Abstract

Train accidents are one of the major issues in recent times. The objective of this project is to create a Security System for trains. We made continuous observations on trains with Gas sensors which measure the leakage of any harmful gases. In this system, we implement a smart fire detection system that would not only detect the fire using integrated sensors but also alert proper owners, emergency services, and nearby stations. The proposed model in this system employs different integrated detectors. The signals from those detectors go through the system algorithm to check the fire’s potentiality and then broadcast the predicted result to various parties using the Wi-Fi module. To get real-life data without putting human lives in danger, an IoT technology has been implemented to provide the fire department with the necessary data. Using IoT devices like the Wi-Fi module, we continuously monitor the train to save human lives by providing the data collected from the gas sensor and temperature sensor. As soon as the fire is detected, the sprinkler we implemented will automatically be turned on, which reduces the effect caused by fire.

## Introduction

Travel is captivating, especially train travel, which is more exciting compared to other modes. With increased comfort levels, low tariffs in train transport, and traffic in trains, there is a pressing need to improve safety concerns and advantages in train travel. This paper explores the possible approach to improving train track safety using an on-board monitoring system, inspection system, and dynamic track monitoring system.

The Internet of Things (IoT) is the physical network of things or objects – devices, buildings, trains, and other items embedded with electronics, software, sensors, and network connectivity that enables these things or objects to collect and exchange data. The IoT is expected to produce a high degree of human-to-machine communication along with machine-to-machine communication. The primary objective of this project is to reduce human work. Automation has always been a prime factor for security systems. Our aim in the project is to design and implement a security system that offers controllability through a hand-held mobile phone by means of IoT.

In today’s world where science has made amazing advances, so have recent trains. These trains are more advanced than ever, with more speed, state-of-the-art engines, and increased complexity. Due to these reasons, there is a need to adapt a device that can continuously monitor all the various parameters of a train. We have designed such a system which, in case of an accident, will record all the parameters and help us prevent accidents to happen to a certain extent. The project is developed to record informational data, such as the temperature of the train, gas leakage level, etc.

## Literature Review

The system is highly reliable, tamper-proof, and secure. In the long run, the maintenance cost is efficient. It is highly accurate. Travel is captivating, especially, train travel is more exciting one in travelling when comparing to others. With the increased comfort levels, low tariff in train transport and traffic in trains, we are in a high important situation to improve the safety concerns and advantages in train travel. In this paper, it explores the possible approach of improving train track safety using an on-board monitoring system, inspection system, and dynamic track monitoring system. This project will enable the trains to work and implement without accident and safely. The Existing system had only tracked monitoring and no transportation of data, but this paper proves its worth by giving solutions. These systems are less cost and highly efficient worth systems and on implementation can yield excellent and amazing results. With the use of high-end Internet of Things (IoT) system the consistency of the system is minor concern. Implementation is based on which the sensor is included.

A system that provides information when there is a gas leakage. In those cases, this system alerts the people around them and the nearby station. In the proposed system, we have designed “Gas Leakage and temperature monitoring system”. This report focuses on the detection of harmful combustible gases.

## Project Methodology

This monitoring system consists of ESP8266 module, MQ-135 gas sensor, LM35 temperature sensor, LED, and buzzer. The cloud service used is Thingspeak.com. This system will be placed at such a location that there will be no disturbance in monitoring. The sensors used for monitoring will be placed in the compartments of the train. If the MQ-135 sensor finds that there is any concentration of harmful combustible gas in the surrounding environment, then it will sense it and will send a signal to ESP8266 module via Arduino UNO. The Arduino UNO will process the signal and will activate the LED or buzzer depending on the strength of the signal received. The maximum voltage to the sensor is 5V. When it detects the gas in the surrounding, the resistance of the sensor changes (increases or decreases) the voltage of the sensor.

The signal generated by the sensor will depend on the voltage output of the sensor. Lower the voltage, stronger the signal generated. This system consists of LM35 temperature sensor, an Arduino module, ESP8266 Wi-Fi module, MQ-135 gas sensor, Buzzer, and LED. This system will be placed in every compartment of the train. The LM35 temperature sensor is used to measure the temperature of the compartment. This temperature sensor will indicate if there is any fire produced in the compartment. If the fire is detected, it will alarm the driver with the help of the buzzer and the nearby station using the Wi-Fi module. Using this Wi-Fi module, we can know the position and distance of the train from the nearby station. It gives the output in analog form.

If the temperature of the compartment is more than 200 deg Celsius, the Wi-Fi module will notify the driver and nearby station. This system also measures if any harmful combustible gases are present in the compartment which may also lead to a fire accident.

### Components

#### Microcontroller Module

The microcontroller is a compact microcomputer, designed to control the operation of embedded electronic systems in various applications. Here, it is used to read the environmental temperature from the sensor module, display the characters on the display module, and switch on or off the necessary pins as per the program uploaded on the microcontroller.

![Arduino UNO](link-to-image-arduino-uno)

#### MQ135 Gas Sensor

The MQ 135 sensor can be implemented to detect smoke, benzene, vapors, and other hazardous gases. It can detect various harmful gases. It can be used for air quality monitoring, noxious gas detection, home air pollution detection, industrial pollution detection, portable air pollution detection, etc.

**Specifications of MQ-135 Gas Sensor:**
- Power requirements: 5 VDC @ ~165 mA (heater on) / ~60 mA (heater off)
- Current Consumption: 150mA
- DO output: TTL digital 0 and 1 (0.1 and 5V)
- AO output: 0.1- 0.3 V (relative to pollution), the maximum concentration of a voltage of about 4.2V
- Detecting Concentration: 0.05-10mg/L Alcohol
- Interface: 1 TTL compatible input (HSW), 1 TTL compatible output (ALR)
- Heater consumption: less than 750mW
- Operating temperature: 14 to 122 °F (-10 to 50°C)
- Load resistance: 200kΩ
- Sensitivity S: Rs (in air)/Rs (0.4mg/L Alcohol) ≥5
- Sensing Resistance Rs: 2KΩ-20KΩ (in 0.4mg/l alcohol)
- Dimensions: 35 x 22 x 23 mm

![MQ135 Gas Sensor](link-to-image-mq135-gas-sensor)

#### LM35 Temperature Sensor

![LM35 Temperature Sensor](link-to-image-lm35-temperature-sensor)

#### Buzzer

The buzzer in this circuit is used when the microcontroller provides a high signal, i.e., when a temperature is greater than or equal to 35 degrees Celsius, the circuit will be completed, and the buzzer will start alarming.

![Buzzer](link-to-image-buzzer)

#### LED Bulb

A light-emitting diode (LED) is a semiconductor device that emits light when current flows through it. Electrons in the semiconductor recombine with electron holes, releasing energy in the form of photons.

![LED Bulb](link-to-image-led-bulb)

#### Wi-Fi Module (ESP8266)

Wi-Fi modules or Wi-Fi microcontrollers are used to send and receive data over Wi-Fi. They can also accept commands over Wi-Fi. Wi-Fi modules are used for communications between devices. They are most used in the field of the Internet of Things.

![Wi-Fi Module ESP8266](link-to-image-wifi-module)

#### Power Supply - 12 Volt Battery

12V power supplies (or 12VDC power supplies) are one of the most common power supplies in use today. In general, a 12VDC output is obtained from a 120VAC or 240VAC input using a combination of transformers, diodes, and transistors. Switching regulated 12VDC power supplies, sometimes referred to as SMPS power supplies, switchers, or switched mode power supplies, regulate the 12VDC output voltage using a complex high frequency switching technique that employs pulse width modulation and feedback. Acopian switching regulated power supplies also employ extensive EMI filtering and shielding to attenuate both common and differential mode noise conducted to the line and load. Galvanic isolation is standard in our 12VDC switchers, affording our users input to output and output to ground isolation for maximum versatility. Acopian switching regulated power supplies are highly efficient, small, and lightweight, and are available in both AC-DC single and wide-adjust output and DC-DC configurations. Our Low Profile wide adjust output switchers can be voltage or current regulated and are externally programmable.

Linear regulated 12VDC power supplies regulate the output using a dissipative regulating circuit. They are extremely stable, have very low ripple, and have no switching frequencies to produce EMI. Galvanic isolation is standard in our 12VDC linear, affording our users input to output and output to ground isolation for maximum versatility. Acopian linear regulated power supplies are available AC to DC single and wide adjust outputs.

Unregulated 12VDC power supplies are basic power supplies with an AC input and an unregulated 12VDC output. The output voltage changes with the input voltage and load. These power supplies are inexpensive and extremely reliable.

![Circuit Diagram for 12-Volt Battery](link-to-image-circuit-diagram-12-volt-battery)

### Testing and Charging

The checking of 12-Volt battery is done by a voltmeter, which can be purchased cheaply from most major automotive parts stores. Check the voltage of your battery using the voltmeter to help determine your next course of action. 12.6V volts or above - Your battery is healthy and fully charged. A 12V flooded lead acid battery will have an open circuit voltage of around 12.6 volts when fully charged.
### Writing Sketches

Programs created using the Arduino Software (IDE) are known as sketches. These sketches are authored in the text editor and saved with the file extension `.ino`. The IDE's editor facilitates actions such as cutting, pasting, searching, and replacing text. The message area offers real-time feedback, indicating errors during processes like saving and exporting.

### Arduino IDE Interface (Fig.3.10)

The console within the Arduino IDE displays textual output, providing complete error messages and relevant information. The lower-right corner of the window showcases the configured board and serial port. The toolbar includes buttons for critical functions, enabling users to verify and upload programs, create, open, and save sketches, and open the serial monitor.
## Working Method

The safety of the consumer is mandatory. An efficient and fast-working controller is needed to continuously sense the MQ-135 gas sensor and LM35 temperature sensor. Also, a fast reply is desired when harmful gas and fire are detected. Along with this, a system must possess the capacity to store some information which can be used for further processing.

### Sensor Operation

1. **Gas Sensor (MQ-135):** Detects the presence of harmful combustible gas.
2. **Temperature Sensor (LM35):** Measures the heat level in the compartment.

### Microcontroller (Arduino UNO)

The microcontroller continuously monitors the data from the gas and temperature sensors. It takes corrective or necessary actions based on the sensor readings.

### Actions Taken

- The status of all sensor readings is conveyed to the driver and nearby station.
- In the presence of injurious gas detected by the MQ135 sensor or a high temperature measured by the temperature sensor, corrective actions are initiated.

### Data Flow

1. **Data Collection:** Gas sensor and temperature sensor collect data from the environment.
2. **Arduino UNO:** Processes the collected data.
3. **ESP8266 Wi-Fi Module:** Transmits the processed data to the cloud.
4. **Indicators (Buzzer and LED):** Provide real-time indications based on sensor readings.

### Indicators Operation

- **Buzzer:** Alarms if the temperature exceeds a certain limit.
- **LED:** Indicates the presence of harmful gas when detected.

### Cloud Integration

The collected data, including gas and temperature readings, can be viewed in the cloud using the Wi-Fi module (ESP8266). This allows for remote monitoring and further analysis.

This system ensures a proactive approach to safety, providing real-time alerts and data storage capabilities for future reference.
## Working Operation

The Gas sensor in the system is utilized to detect the presence of any harmful combustible gas, while the temperature sensor identifies the temperature of the compartment. It promptly alerts the driver and nearby station in the event of a fire in the compartment. These sensors produce analog signals transmitted to the controller. The controller processes the high signals from the input devices and takes necessary actions.

If the predefined limit is exceeded, the controller issues orders to the indicators. The system's output measurements can be viewed on THINGSPEAK.COM through the Wi-Fi module. Additionally, the output measurements can be displayed on a dedicated display module.

## Results and Discussion

The system aims to provide a safe, reliable, simple, and cost-effective monitoring and security system for trains. It seeks to offer a straightforward, secure, decisive, and affordable security system for train passengers. This system has the advantage of being cost-effective, utilizing readily available components. Its major superiority over conventional human-based systems lies in providing quick response, precise detection, and control, contributing to the appropriate handling of critical situations.

[Insert Output Chart Here - Fig.5.1]

## Conclusion

The primary objective of this project was to enhance the safety of people during train travel. Train accidents have led to numerous injuries and fatalities, and this system addresses this issue by employing two analog sensors operating within closed environments. These sensors measure appropriate values and trigger safety measures. The integrated indication system notifies the driver and nearby stations via a buzzer and LED through the Wi-Fi module. With the Wi-Fi module, information can be accessed from anywhere using THINGSPEAK.COM.

