# Humidity Measurement System

The Humidity Measurement System provides a convenient and reliable solution for measuring and monitoring humidity levels in various indoor or outdoor settings. By utilizing the ESP8266 NodeMCU board, this project enables wireless communication, allowing users to access and view humidity data remotely.

## Table of Contents

- [Installation](#installation)
- [Usage](#usage)
- [Features](#features)
- [Configuration](#configuration)
- [Acknowledgments](#acknowledgments)
- [Contributing](#contributing)
- [License](#license)
- [Contact](#contact)

## Installation

1. Clone or Download the repository to your local machine using the following command:
```
git clone https://github.com/kershrita/Humidity-System.git
```

2. Hardware setup:

- Connect the DHT11 or DHT22 humidity sensor to the digital pin 4 of the ESP8266 NodeMCU board.
![Circuit Diagram](Circuit.jpg)
- Make sure the necessary libraries (DHT.h, ESP8266WiFi.h, BlynkSimpleEsp8266.h, SPI.h) are installed in your Arduino IDE.
-Components:
	- 1 * ESP8266 NodeMCU
	- 1 * DHT11 Humidity Sensor
	- 2 * Switch
	- 1 * Power Jack
3. Blynk setup:

- Install the Blynk mobile app on your smartphone or tablet.
- Create a new Blynk account and project.
- Obtain the authentication token for your project by going to Project Settings in the Blynk app.

4. Software setup:

- Open the provided code in the Arduino IDE.
- Modify the following variables in the code:

	- **auth**: Replace with your Blynk authentication token.
	- **ssid**: Enter your Wi-Fi network name (SSID).
	- **pass**: Enter your Wi-Fi network password.

- Upload the code to the ESP8266 NodeMCU board.

## Usage

- Power on the ESP8266 NodeMCU board.
- Launch the Blynk mobile app and open your project.
- The system will start measuring humidity and sending the data to the Blynk cloud platform.
- Use the Blynk app to monitor the real-time humidity readings and access historical data.

## Features

- **Real-time humidity measurement**: The system continuously monitors and updates humidity levels, providing accurate and up-to-date information.
- **Wireless connectivity**: The ESP8266 NodeMCU board connects to a Wi-Fi network, enabling remote access to the humidity data through the Blynk cloud platform.
- **Blynk integration**: The project uses the Blynk IoT platform to visualize the humidity data and provide a user-friendly interface for monitoring.
- **Data logging**: The Blynk platform allows users to log and store historical humidity data, enabling trend analysis and data-driven decision-making.

## Configuration

The Humidity Measurement System with ESP8266 NodeMCU offers several practical uses and applications:

- **Indoor Climate Monitoring**: The system allows you to monitor and track humidity levels in indoor spaces such as homes, offices, warehouses, and server rooms. By keeping an eye on the humidity, you can ensure a comfortable and healthy environment for occupants or maintain optimal conditions for equipment and sensitive electronics.
- **Greenhouse Management**: If you're involved in greenhouse or indoor gardening, this system can be used to monitor the humidity levels critical for plant growth. It enables you to assess and adjust humidity conditions to create an optimal microclimate for plants, improving their health and productivity.
- **Home Automation**: By integrating the humidity measurement system into a broader home automation setup, you can create smart home applications. For example, you can automatically trigger actions like turning on dehumidifiers, activating ventilation systems, or sending notifications when humidity levels exceed predefined thresholds.

## Acknowledgments

We would like to acknowledge the following resources and libraries that have been instrumental in developing Kids Learning Program:

- **[Arduino IDE](https://www.arduino.cc/en/software)**:  An open-source integrated development environment (IDE) used for programming Arduino boards.
- **ESP8266 NodeMCU**: An open-source development board that combines the ESP8266 Wi-Fi module with a microcontroller unit (MCU). It provides an easy and cost-effective way to add Wi-Fi connectivity to your projects and is widely used in IoT (Internet of Things) applications.
- **DHT**:  An arduino library software library that enables the easy integration and use of DHT (Digital Humidity and Temperature) sensors with Arduino microcontrollers. The library provides functions to read and retrieve humidity and temperature data from DHT sensors accurately.

## Contributing

Contributions to this project are welcome. If you find any issues or have suggestions for improvement, please open an issue or submit a pull request on the project's GitHub repository.

## License

Humidity Measurement System is released under the [MIT License](LICENSE).

## Contact

- Mail: ashrafabdulkhaliq80@gmail.com
- LinkedIn: https://www.linkedin.com/in/ashraf-abdulkhaliq
- GitHub: https://github.com/kershrita