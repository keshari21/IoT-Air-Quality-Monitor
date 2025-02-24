# IoT-Air-Quality-Monitor

**COMPANY**: CODTECH IT SOLUTIONS

**NAME**: SUKANYA

**INTERN ID**: CT12GFT

**DOMAIN**: INTERNET OF THINGS(IoT)

**BATCH DURATION**: DECEMBER 25TH, 2024 TO FEBRUARY 25TH, 2025

**MENTOR NAME**: NEELA SANTOSH KUMAR

# DESCRIPTION                      
The IoT Air Quality Monitor is a smart environmental monitoring system designed to measure air quality parameters such as temperature, humidity, and harmful gas concentrations. This project is built using an ESP8266 module, along with various sensors, to collect real-time data and transmit it to a cloud platform or display it on a web dashboard. The goal is to provide an affordable, efficient, and scalable solution for monitoring air pollution, making it useful for smart homes, offices, and industrial applications.              

**Key Features**                   
•	Real-time monitoring of air quality parameters                                   
•	Wi-Fi connectivity using the ESP8266 module for data transmission                               
•	Cloud integration for remote access to data                             
•	User-friendly dashboard for displaying sensor readings                           
•	Alerts and notifications when pollution levels exceed safe limits                                

**Components Used**                           
1.	ESP8266 (NodeMCU) – Acts as the main microcontroller, enabling Wi-Fi connectivity for data transmission.                                  
2.	MQ135 Gas Sensor – Detects hazardous gases such as CO₂, NH₃, alcohol, benzene, and smoke.                                    
3.	DHT11/DHT22 Sensor – Measures temperature and humidity.                                      
4.	OLED Display (Optional) – Displays real-time sensor readings locally.                                                   
5.	Buzzer (Optional) – Provides an alert when air quality deteriorates beyond a set threshold.                                      
6.	Resistors & Jumper Wires – For necessary electrical connections.                                                    
7.	Power Supply (5V) – To power the ESP8266 and sensors.                                               

**Working Principle **                                         
The IoT Air Quality Monitor operates by collecting environmental data through various sensors and transmitting it over Wi-Fi for remote monitoring. The MQ135 gas sensor detects the presence of harmful gases and sends analog signals to the ESP8266, which converts them into digital values. Similarly, the DHT11/DHT22 sensor measures temperature and humidity and transmits the data to the microcontroller.                                           
The ESP8266 processes all collected data and:                                 
1.	Displays real-time sensor values on an OLED screen (if included).                                     
2.	Sends data to a cloud platform such as ThingSpeak, Firebase, or MQTT broker.                                          
3.	Triggers an alert (buzzer notification or LED indicator) if air quality crosses unsafe levels.                                          
The user can monitor live air quality data through a web dashboard or mobile application, making this system ideal for both personal and professional use.                             

**Implementation Steps **                                         
1. Circuit Design and Assembly                             
•	Connect the MQ135 gas sensor to the ESP8266’s analog input (A0).                             
•	Interface the DHT11/DHT22 sensor with a digital pin of the ESP8266.                                 
•	(Optional) Connect an OLED display to display readings locally.                          
•	Ensure a stable 5V power supply is provided to all components.                                                                 

2. Programming the ESP8266                                
•	Write code in Arduino IDE or MicroPython, including necessary libraries (DHT.h, Adafruit_SSD1306.h, etc.).                          
•	Configure Wi-Fi connectivity to enable real-time data transmission.                                    
•	Implement data processing algorithms for accurate sensor reading analysis.                                       
•	Define threshold values to trigger alerts when pollution levels are high.                                

3. Data Transmission and Visualization                              
•	Upload sensor data to a cloud platform (ThingSpeak, Firebase, or MQTT).                                     
•	Create a web-based dashboard using HTML, JavaScript, or third-party IoT platforms.                                     
•	Implement mobile notifications or email alerts for critical pollution levels.                                   

**Applications**                                            
•	Smart Cities: Helps monitor pollution levels in urban areas.                                  
•	Industrial Safety: Detects toxic gases in factories and manufacturing units.                                     
•	Indoor Air Quality: Suitable for homes, offices, and hospitals.                                     
•	Weather Monitoring Stations: Provides real-time environmental data.                                   

**Future Enhancements**                                              
•	Integration with AI/ML models to predict pollution trends.                                         
•	Battery-powered operation for greater mobility.                                         
•	GPS module support for location-based air quality monitoring.                                      
•	Integration with IoT platforms like AWS IoT Core for advanced analytics.                                   

**Output**                           

