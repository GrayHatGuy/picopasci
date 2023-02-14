## picoponic 

Sensor monitor and control firmware for an economical and scalable hydroponic system using an RP2040 pico and standard off the shelf sensors and components.
 *  air temp
 *  water temp
 *  humidity
 *  VOC
 *  CO2
 *  Soil H2O
 *  TDS
 *  EC
 ![image](https://github.com/GrayHatGuy/picoponic/blob/0f7c91f61f793c428a4101a5d96488dfcb26ee3a/repo_full%20picoponicwire.png?raw=true)
## Features
- ### Nutrient mixing 
The system accomodates four liquid reservoirs with triggered solenoid valves for mixing water and up to three nutrients.  After inputing the nutrient tank capacity target EC/TDS and mix ratios the system will automatically mix and fill the tank.  
- ### Water quality
The TDS/EC sensor can be used as a continuous monitor to ensure the water quality is within the target range and compensate for drift by adding water or nutrients.  
- ### Irrigation
A moisture sensor is included to monitor the moisture content of the grow media and trigger a watering. The nutrient mix can then be used to irrigate multiple grow media hydroponic, aquaponic, or terrestial grow sytems.  Additional valves can be added to the nutrient resovoir for automatic watering.
- ### Air Quality
Includes temperature, humidity, C02, and volatile organic chemical (VOC) sensors. These sensors can be used to automate HVAC triggers.
## libs:
 *  [SGP30 Gas Sensor](https://github.com/Seeed-Studio/SGP30_Gas_Sensor)
 *  [SHT4x TempRH](https://www.arduinolibraries.info/libraries/sensirion-i2-c-sht4x)
 *  _TBD_ 
## parts: 
 *  [Grove SHT4x Temp/RH](https://www.seeedstudio.com/Grove-Temp-Humi-Sensor-SHT40-p-5384.html?queryID=79f54ab791e4345a5bd143b2f1674b74&objectID=5384&indexName=bazaar_retailer_products)
 *  [Grove SGP30 VOC/CO2](https://www.seeedstudio.com/Grove-VOC-and-eCO2-Gas-Sensor-for-Arduino-SGP30.html?queryID=f5af88e62b89603f700a72fc7083e746&objectID=127&indexName=bazaar_retailer_products)
 *  [Grove Soil Moisture](https://www.seeedstudio.com/Grove-Moisture-Sensor.html?queryID=8f8a40002a96e9bcb9aad1275f9a6cad&objectID=1678&indexName=bazaar_retailer_products)
 *  [Water quality TDS/EC](https://www.amazon.com/dp/B08DGLY3J2)
 *  [Relays 5V SPST - 4X bank](https://www.amazon.com/dp/B098DWS168)
 *  [5V Solenoid Valves](https://www.amazon.com/dp/B07WR9CSNQ)
 *  [RP2040 grove breakout](https://www.digikey.com/en/products/detail/seeed-technology-co.,-ltd/103100142/13688265)
 *  [RP2040 pico](https://www.raspberrypi.com/products/raspberry-pi-pico/)
## next...
 *  Use sensor metrics as a feed forward mechanism for closed loop control of lighting, water, and air quality.  
### _If you are interested in contributing or participating in this project contact_ GrayHatGuy@GrayHatGuy.com
