# rtt_carrier

Altium Project for RTT UP Core <---> GPS/Magnetometer Carrier

# GPS and Magnetometer (6 Pin Board {5V, RX, TX, SDA, SCL, GND})

PCB Design has 12 pins

## 3.3V GPS I2C -

Pin 1 - Connect to GPS/Magnetometer (Driven by 5V coming from upcore)

Pin 2 - Common GND

Pin 3 - SDA/SCL 3.3V translate to 1.8V (GPS Side)

Pin 4 - SDA/SCL 3.3V translate to 1.8V (GPS Side)

## 3.3V GPS UART -

Pin 1 - RX/TX 3.3V Logic Level (GPS Side)

Pin 2 - RX/TX 3.3V Logic Level (GPS Side)

## 1.8V - 5V Upcore I2C -

Pin 1 - SDA/SCL 1.8V Logic Level to be translated (Upcore Side)

Pin 2 - SDA/SCL 1.8V Logic Level to be translated (Upcore Side)

Pin 3 - Common GND

Pin 4 - Connect to Upcore 5V

## 1.8V - 5V Upcore UART -

Pin 1 - RX/TX 3.3V Logic Level (Upcore Side)

Pin 2 - RX/TX 3.3V Logic Level (Upcore Side)
