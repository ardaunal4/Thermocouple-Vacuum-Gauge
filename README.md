# Thermocouple-Vacuum-Gauge
The project is briefly signal conditioning electronic circuit design of GTC-036 type Vacuum Gauge(More information: https://www.fabsurplus.com/sdi_catalog/salesItemDetails.do?id=83892). The sensor provides input between 0 V (1 atm) to 11 mV(1.3E-6 atm). I designed a circuit that provides output between 1.5V to 10V for PLC analog input. I used LTspice to simulate an amplifier circuit for the validation of the technique. I used KiCad for test PCB. I designed professional PCBs using Altium Designer. There are 3 different boards in this design: 1. Stage designed for sensor signal acquisition and sensor feeding. The second stage consists of signal processing circuits and sensor feed voltage production circuits. The third stage includes a regulator and a connector for PLC. Here I would like to share some of the 3D models of my work:
1. Sensor connector PCB: 
![alt text](https://github.com/ardaunal4/Thermocouple-Vacuum-Gauge/blob/main/3DBoardModels/Stage1.jpg)
2.Sensor signal conditioning circuit:
![alt text](https://github.com/ardaunal4/Thermocouple-Vacuum-Gauge/blob/main/3DBoardModels/Stage2_bottom.jpg)
