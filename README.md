
![KiCad](https://img.shields.io/badge/KiCad-darkblue?logo=KiCad)
![Relaise](https://img.shields.io/github/release-date/gerryvel/OPB40-Connect-Board-?)
![lastcommit](https://img.shields.io/github/last-commit/gerryvel/OPB40-Connect-Board-)
[![OBP](https://img.shields.io/badge/Sailing_with-OpenBoatsProjects-blue)](https://open-boat-projects.org/de/)
[![PCB](https://img.shields.io/badge/PCB-byAisler-red)](https://aisler.net/p/XZHLUZKY)

## Description

This board it's an addon to: https://github.com/norbert-walter/esp32-nmea2000-obp60.
It's for connect to the 20pin-socket on the OBP40 (elecrow Display) and the case from [@norbert-walter].

Function: 
- N2k interface (with ESD-cicuit)
- 12/5V Stepdown converter
- I2C connector (with ESD-cicuit)
- NMEA0183 connector
- voltage divider for measuring battery voltage

12V supply use N2K, I2C power supply is 3,3V from elecrow Display. I2C board is eqipped with varios connectors for sensors etc.
If you use only I2C funtion, this connect only to board and you don't need the 12V/5V Converter.

## Foto

![image](https://github.com/user-attachments/assets/ed229efe-5f5f-486f-a3b6-d562591d951b)
![image](https://github.com/user-attachments/assets/e4e4cad4-ea1c-4c35-ac2c-3bbabf4c07f0)
![image](https://github.com/user-attachments/assets/da8698ef-64d5-4a60-9b35-fa594ddab3bc)

## Circuit diagram 

<img width="3507" height="2480" alt="grafik" src="https://github.com/user-attachments/assets/262a00c8-9f63-401c-81e4-83c8ee02143e" />

## Partlist

- BT1, LIPO 3,7V 1200mAh
- C3, 10µ,Capacitor_Tantalum_SMD
- C4, 22,Capacitor_Tantalum_SMD
- D1, B230A
- D2, SMAJ5.0CA
- D3, P4SMAJ26CA
- D4, PRTR5V0U2X
- D5, PESD1CAN
- FL1, EPCO B82789C0513
- J1, J2, J4, J5, J6, J10, Connector_PinHeader_2.54mm
- J3, Conn_01x20_Pin,C onnector_PinHeader_2.54mm
- J7, Conn_01x04_Pin, Connector_PinHeader_2.54mm
- J8,J11,J12,J13,J14,J15,J16,Connector_JST:JST_PH_S4B-PH-K
- R1,R2, 10k
- RV1, EPC B72530T0300
- U2, TSR1-2450
- U3, TCAN332

## Boarddesign

<img width="1415" height="934" alt="grafik" src="https://github.com/user-attachments/assets/bfcee918-8740-4566-9dc4-eff2f4e6e65d" />


