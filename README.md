# TOSAH
The Open Source Aquarium Hood

About: 
TOSAH is a hardware platform for the management and automation of an aquarium. Measurement of parameters such as temperature, motor output, etc are fed through an internal web server to the aquarist. 


Prospective Features:
Traditional Aquarium Maintenance & Monitoring functions - Lighting, Filtration, Feeding, Water Changes, Dosing (Fluval, API, Etc), CO2 Control/Monitoring, pH, gH, kH, Ammonia, Nitrite, Nitrate, temperatures

Killer features: Web monitoring, SMS alerts, "cloud services", webcams and automation, fish breeding “programs” to increase breeding frequency

Hardware
Platform Candidates: ATMEL, RPi or a combination of both OR a similar architecture with similar footprint but more computing power.

Design considerations
Material design
Support chassis holding electronics such as power supplies and computing devices
Modular approach for added lighting, computing, filtration, dosing, feeding, etc
Wall wart for AC/DC conversion or internal power supply
Internal hood heat control, UL STANDARDS
Independent motor board
Scaling pricing enabled by a modular approach
NEMA rated enclosure or equivalent
Retractable UI and displays for wireless settings
backup battery
Hardware design
Wifi
Core board
Daughter boards
Motor control
LED power and control
Sensors
Temperature
photons (light)
Software design
Web front end, SNMP backend, tunnel software
flat files, off-site storage, DB?
management logic
Example - if temperature is less than 70 turn heater on
every X hours do Y
every 24 hrs dose with Flourish excel