**IPEC ESP32 ATM90E32 IoT Power Energy Controller and Monitor SDK**

**IPEC** is an **IoT Power Energy Monitor and Controller.** 3 Phase, or 3 x Single Phase with DAC/PWM/MPPT/I2C Expansion Port Outputs

New Product - Further details to follow

**IPEC Production - 3D Prototype Beta Board**

![IPEC](https://github.com/DitroniX/IPEC-IoT-Power-Energy-Controller/blob/main/Datasheets%20and%20Information/IPEC%20ESP32E%20ATM90E32%20SDK%201.2306.101%20-%203D.jpg)

 The **IPEC IoT Power Energy Controller** board main features:
 - **Compact** and **Flexible Design** SDK Board
	 - All connections are **low voltage**, for **safe operation**
	 - **Easy to interface**
 - *Optional* **Espressif** **ESP32** **WROOM**
	 - **ESP32-WROOM-32E-N4** 
		 - Integral Antenna Wireless and Bluetooth  
	 - **ESP32-WROOM-32UE-N4** 
		 - Ext Antenna - U.FL Socket 
		 - Wireless and Bluetooth
 - **ATM90E32** Energy Monitor 
	 - 3 x Phases Line CT Clamp Input  
		 -  Example YHDC SCT013000
	 - 3 x Voltage Sensing Inputs (AC RMS)
		 - Can be used with Single Phase, or Multi AC Inputs (For Split or 3Phase)
		 - Normally Taken from AC Power Input (by Default)
	 - Power Modes Settings
 - **MCP4728** DAC
	 - 12bit I2C DAC
	 - Four Independent Buffered Output Channels
	 - Configured for Default DAC Out, or Modulated (Example MPPT)
		 - Configurable Solder Pads
	 - On-Board DAC EEPROM (For DAC Codes and Addressing)
	 - Can be configured to drive DAC based on CT Clamp Current / Power
 - **24C64** EEPROM I2C
	 - Parameter Settings
	 - Logging
 - **OLED I2C**
	 - I2C Interface
	 - OLED I2C Connector
		 - Configurable Power Pins
 - **AC Low Voltage** Input (for Safety)
	 - Standard 2.1mm Jack Socket
	 - Power safely derived from a SELV / Wall AC/AC Power Supply 
		 - 8 to 12V AC RMS (Nominal 12V)
		 - Examples GreenBrook DAT01A or TLC TC TR7
 - Onboard **3V3 DC SMPS** Power Supply
	 - Power taken from AC Input, or USB 5V
 - Arduino **Wemos D1 Compatible** USB Interface
	 - On-board Micro USB Socket
	 - Flashing and Programming
	 - Example wemos_d1_mini32
	 - Can also used to power the board
	 - Debugging
 - **Expansion Port**
	 - Configurable and Flexible Port
	 - DAC Outputs
	 - I2C Interface
	 - 3v3 Power
	 - Standard JST SH 6 Way Header
 - **USER GPIO/UART**
	 - 2 GPIO for User (GP16 and GP17)
	 - UART Interfacing (UART 2)
 - **Reset Button** 
 - User **Programmable Button** 
 - **RGB Status LED**
	 - User Configurable
 - **Power LED**
	 - On 3V3 
 - **ATM CT LEDs**
	 - CF1 - Active 
	 - CF2 - ReActive
	 - CF3 - Fundamental
	 - CF4 - Harmonic
 - **Configuration**
	 - Solder Pads on Rear of PCB.
 - PCB designed to fit neatly into an BMC enclosure 
	 - Also allows for the display to be included, or not. 
 - **Firmware - Code**
	 - Full Example Code in GitHub
	 - Source Code Based on IPEM
	 - Publish to MQTT
	 - Publish to Domoticz
	 - Publish to ThingSpeak
	 - Drive DAC for PWM / Voltage or MPPT Based on CT Readings
 - **Size** 70 mm x 53 mm