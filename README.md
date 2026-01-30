
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

Images V1.1
![image](https://github.com/user-attachments/assets/ed229efe-5f5f-486f-a3b6-d562591d951b)
![image](https://github.com/user-attachments/assets/e4e4cad4-ea1c-4c35-ac2c-3bbabf4c07f0)
![image](https://github.com/user-attachments/assets/da8698ef-64d5-4a60-9b35-fa594ddab3bc)

## Circuit diagram 

<img width="3507" height="2480" alt="grafik" src="https://github.com/user-attachments/assets/b85fb5a2-f350-4f89-8eca-df37260d3872" />

PCB by Aisler: [link](https://aisler.net/p/XZHLUZKY)

## Partlist

- C3,CP_EIA-7343-31_Kemet-D,1,10µ,
- C4,CP_EIA-7343-31_Kemet-D,1,22µ,
- D1,D_SMA,1,B230A,
- D2,D_SMA_TVS,1,SMAJ5.0CA,
- D3,D_SMA_TVS,1,P4SMAJ26CA,
- D4,SOT-143,1,PRTR5V0U2X,
- D5,SOT-23,1,PESD1CAN,
- FL1,B82789C0113N002,1,EPCO B82789C0513,
- J11,PinHeader_1x04_P2.54mm_Horizontal,1,I2C,
- J12,JST_PH_S4B-PH-K_1x04_P2.00mm_Horizontal,1,I2C,
- J13, J16,PinSocket_1x04_P2.54mm_Horizontal,2,I2C,
- J15,JST_SH_SM04B-SRSS-TB_1x04-1MP_P1.00mm_Horizontal,1,I2C,
- J3,PinHeader_2x10_P2.54mm_Vertical,1,Conn_01x20_Pin,
- J4,Molex_KK-254_AE-6410-02A_1x02_P2.54mm_Vertical,1,Conn_01x02_Pin,
- J6,PinHeader_1x02_P2.54mm_Vertical,1,~,
- J7,PinHeader_1x04_P2.54mm_Vertical,1,Conn_01x04_Pin,
- J8,PinSocket_1x04_P2.54mm_Vertical,1,I2C,
- R1, R2,1206,2,10k,
- RV1,1210,1,EPC B72530T0300,
- U2,Converter_DCDC_TRACO_TSR-1_THT,1,TSR1-2450,
- U3,SOIC-8_3.9x4.9mm_P1.27mm,1,TCAN332,


## Boarddesign

<img width="1415" height="934" alt="grafik" src="https://github.com/user-attachments/assets/7bc54435-a38f-4503-994c-1f9ccb59d401" />
<img width="1415" height="934" alt="grafik" src="https://github.com/user-attachments/assets/8d943c69-64fc-4eee-9989-5e186b83a693" />

## Versions

1.3 Change Connector J4 to Molex KK
1.2 Change all SMD Parts to Side2 for automatic assembly
1.1 Change lettering PCB for NMEA2000 Connector
1.0 Initial

