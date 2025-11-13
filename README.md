# IR-Temperature-Sensor
**The GY-906 MLX90614ESF (BAA/BCC)** is a non-contact infrared temperature sensor that measures the surface temperature of objects or the human body without physical contact. It uses the MLX90614ESF chip from Melexis and communicates via I²C or PWM, making it compatible with Arduino and various microcontrollers. Its small size, low power consumption, and high accuracy make it suitable for both educational and industrial applications.

## This sensor is suitable for:
- Non-contact body and skin temperature measurement
- Smart home systems and automatic climate control
- Industrial and agricultural monitoring
- Measuring the temperature of electronics, radiators, or appliances
- Health devices such as fever detectors
- Motion detection based on temperature changes
- Picker systems in warehouses, logistics, or robotic arms

## Specifications
|Parameter|Value|
|-|-|
|**Model**|MLX90614ESF-BAA / MLX90614ESF-BCC|
|**Object Temperature Range**|–70 °C to +380 °C|
|**Ambient Temperature Range**|–40 °C to +125 °C|
|**Accuracy**|±0.5 °C (0 °C to 50 °C)|
|**Interface**|I²C (SMBus compatible), PWM|
|**Operating Current**|2 mA|
|**Supply Voltage**|3 V – 5 V|
|**Module Size**|~16.8 × 11.5 × 6.2 mm|

![Description](https://github.com/bigbangcmu/bigbang/blob/bigbangcmu/Ultrasonic%20Sensor/Example%20code.png?raw=true){{{width="250" height="auto"}}} 
[**Download the working code here**](https://code.gogoboard.org/#/program/2f3b8945-7ff7-4fce-8d05-b11faf89312e)


## Block Code Reference
|![](https://github.com/bigbangcmu/bigbang/blob/bigbangcmu/IR%20Thermal%20Temperature/IR%20Temp%204.png?raw=true){{{width="150" height="auto"}}}| Use this block to read the object temperature (°C) detected by the sensor.|
|-|-|
|![](https://github.com/bigbangcmu/bigbang/blob/bigbangcmu/IR%20Thermal%20Temperature/IR%20Temp%205.png?raw=true){{{width="150" height="auto"}}}|**Use this block to read the ambient (surrounding) temperature (°C) from the sensor.**|

## **Required Equipment**
|Infrared Temperature Sensor with built-in Grove connector|![Description](https://github.com/bigbangcmu/bigbang/blob/bigbangcmu/IR%20Thermal%20Temperature/ir%20temp.png?raw=true){{{width="200" height="auto"}}}|
|-|-|
|**Grove cable**|![Description](https://github.com/bigbangcmu/bigbang/blob/bigbangcmu/Ultrasonic%20Sensor/only%20grove%20(test).png?raw=true){{{width="200" height="auto"}}}|
|**Computer or Tablet**|![Description](https://github.com/bigbangcmu/bigbang/blob/bigbangcmu/Ultrasonic%20Sensor/computer%20or%20tablet.png?raw=true){{{width="200" height="auto"}}}|
|**GoGo Board and USB-C cable**|![Description](https://github.com/bigbangcmu/bigbang/blob/bigbangcmu/Ultrasonic%20Sensor/gogoboard%20and%20usb.png?raw=true){{{width="200" height="auto"}}}|

## **How to use**
**1. Connect the GoGo Board**
- Connect the GoGo Board to your computer or tablet via USB-C cable or Wi-Fi
![](https://github.com/thegogoboard/gogodoc/blob/main/Automation/Image%20(91).jpg?raw=true){{{width="500" height="auto"}}}

**2. Connect the  Sensor**
There are two ways to connect the IR Temperature sensor:
**Option 1:** Using a Grove Connector
- Connect the IR Temperature Sensor to a Grove cable, then plug the cable into the purple Multi Port on the GoGo Board.
![](https://github.com/bigbangcmu/bigbang/blob/bigbangcmu/IR%20Thermal%20Temperature/IR%20Temp.gif?raw=true){{{width="500" height="auto"}}}

**Option 2:** Using Jumper Wires (Dupont Wires)
- If you don’t have a Grove connector, you can use jumper wires to connect the sensor directly to the pins on the GoGo Board.
![Description](https://github.com/bigbangcmu/bigbang/blob/bigbangcmu/IR%20Thermal%20Temperature/ir%20temp%20with%20adapter.png?raw=true){{{width="500" height="auto"}}} ![Description](https://github.com/bigbangcmu/bigbang/blob/bigbangcmu/IR%20Thermal%20Temperature/ir%20temp%20with%20board.png?raw=true){{{width="500" height="auto"}}} 

## Getting Started with the IR Temperature Sensor on GoGo Code 

**1. Visit the GoGo Code website:**
- Go to [GoGo Code](https://code.gogoboard.org/#/program) to start programming and controlling your device.

**2. Add the IR Temperature Sensor extension:**
- Click on the **Add Extension** category
![](https://github.com/bigbangcmu/bigbang/blob/bigbangcmu/IR%20Thermal%20Temperature/IR%20Temp%201.gif?raw=true){{{width="1000" height="auto"}}}

- Select **Official**, then click the **[ Multi ] - IR Temperature Sensor** card. The system will automatically return to the main page.
![](https://github.com/bigbangcmu/bigbang/blob/bigbangcmu/IR%20Thermal%20Temperature/IR%20Temp%202.gif?raw=true){{{width="1000" height="auto"}}}

**3. Add sensor command blocks:**
- Click on the **[ Multi ] - IR Temperature Sensor** category. You will see two available blocks:
![](https://github.com/bigbangcmu/bigbang/blob/bigbangcmu/IR%20Thermal%20Temperature/IR%20Temp%203.gif?raw=true){{{width="1000" height="auto"}}}

**4. Write a simple program to display sensor data:**
- Use the **“show number”** block from the **Built-in Display** category to display the value on the GoGo Board screen.
- Insert the **"Object Temperature (°C)"** block into the show number block
- To display the value continuously, place everything inside the **“forever do each time wait…”** block from the **Loops** category. You can also set how often the value should be updated (e.g., every 1 second).
![](https://github.com/bigbangcmu/bigbang/blob/bigbangcmu/IR%20Thermal%20Temperature/IR%20Temp%206.png?raw=true){{{width="500" height="auto"}}}

**5. Download and test your code:**
- Click **Download**, then click **Run Code** to start running your program
![](https://github.com/bigbangcmu/bigbang/blob/bigbangcmu/IR%20Thermal%20Temperature/IR%20Temp%207.gif?raw=true){{{width="1000" height="auto"}}}

::: details Additional information
  **Buy online:** [IR Temperature Sensor](https://th.shp.ee/rVTCu3K)
  
  **Cautions**
- Avoid modifying wires or connecting them incorrectly, as this may damage the device.
- Do not touch the sensor head while it is operating, as it may affect detection accuracy.
- If the sensor does not work, check the voltage and wiring connections.
:::
