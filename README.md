# Marine-Robot

# Thrusters Controller Description :

This intelligent Actuator is designed to controll the two thrusters of the robot.
the board will communicate with the on board computer of the robot via the CAN bus.

**the features of the board are :** 

- STM32F103C8T6 ARM 32-bit Cortex™-M3 is the CPU of the board. Higher frequency, higher speed and cost-effictive.

- 2 channels high power H-bridge .

- SN65HVD230 CAN bus controller Operating with a single 3.3 V Supply and Compatible With ISO 11898-2 Standard.

- Serial wire debuger as a programming interface and uart as serial communication interface.

- Operating Voltage up to 24V.

- Maximum Motor Current: 10A continuous, 30 A peak.

- Buck regulator to produce 3.3V/1A output with reverse voltage protection.

- LEDs for motor output state.

- PWM frequency up to 20 kHz.

**The schematic of the board :**




![alt text](https://github.com/ALICHOUCHENE/Marine-Robot/blob/main/Thrusters%20Controller/schematic/schematics.PNG?raw=true)




**The PCB layout of the board :**




![alt text](https://github.com/ALICHOUCHENE/Marine-Robot/blob/main/Thrusters%20Controller/PCB/PCB.PNG?raw=true)





# Manufactoring : 
After finishing the Routing and verifying the pcb. We will make the board at JLC PCB and we chose also the PCB Assembly service.
Here is the BOM and posistion file needed to order from JLC PCB :


**BOM : **

| Designator  | Value         | Footprint                                                | LCSC Part |
|-------------|---------------|----------------------------------------------------------|-----------|
|         C1  | 100nF         | C_0805_2012Metric                                        | C49678    |
|         C3  | 100nF         | C_0805_2012Metric                                        | C49678    |
|         C4  | 100nF         | C_0805_2012Metric                                        | C49678    |
|         C5  | 100nF         | C_0805_2012Metric                                        | C49678    |
|         C6  | 100nF         | C_0805_2012Metric                                        | C49678    |
|         C7  | 100nF         | C_0805_2012Metric                                        | C49678    |
|         C8  | 100nF         | C_0805_2012Metric                                        | C49678    |
|         C16 | 100nF         | C_0805_2012Metric                                        | C49678    |
|         C9  | 4.7uF         | C_0805_2012Metric                                        | C1779     |
|         C10 | 4.7uF         | C_0805_2012Metric                                        | C1779     |
|         C11 | 4.7uF         | C_0805_2012Metric                                        | C1779     |
|         C2  | 47uF          | Capacitor_SMD:CP_Elec_5x5.3                              | C134798   |
|         C12 | 47uF          | Capacitor_SMD:CP_Elec_5x5.3                              | C134798   |
|         C17 | 10UF          | Capacitor_Tantalum_SMD:CP_EIA-3216-18_Kemet-A            | C7171     |
|         C18 | 22pF          | C_0402_0603Metric                                        | C70464    |
|         C19 | 22pF          | C_0402_0603Metric                                        | C70464    |
|         D1  | LED           | LED_0603_1608Metric                                      | C916074   |
|         D2  | LED           | LED_0603_1608Metric                                      | C916074   |
|         J1  | MOTOR1        | TerminalBlock_Altech:Altech_AK300_1x02_P5.00mm_45-Degree | C430582   |
|         J4  | MOTOR2        | TerminalBlock_Altech:Altech_AK300_1x02_P5.00mm_45-Degree | C430582   |
|         J5  | POWER         | TerminalBlock_Altech:Altech_AK300_1x02_P5.00mm_45-Degree | C430582   |
|         Q1  | AO3401A       | Package_TO_SOT_SMD:SOT-23                                | C15127    |
|         Q2  | TP0610L       | Package_TO_SOT_SMD:TO-263-2                              | C468007   |
|         Q4  | TP0610L       | Package_TO_SOT_SMD:TO-263-2                              | C468007   |
|         Q6  | TP0610L       | Package_TO_SOT_SMD:TO-263-2                              | C468007   |
|         Q8  | TP0610L       | Package_TO_SOT_SMD:TO-263-2                              | C468007   |
|         Q3  | IRF740        | Package_TO_SOT_SMD:TO-263-2                              | C483709   |
|         Q5  | IRF740        | Package_TO_SOT_SMD:TO-263-2                              | C483709   |
|         Q7  | IRF740        | Package_TO_SOT_SMD:TO-263-2                              | C483709   |
|         Q9  | IRF740        | Package_TO_SOT_SMD:TO-263-2                              | C483709   |
|         R1  | 330           | R_0805_2012Metric                                        | C17630    |
|         R9  | 330           | R_0805_2012Metric                                        | C17630    |
|         R10 | 330           | R_0805_2012Metric                                        | C17630    |
|         R13 | 330           | R_0805_2012Metric                                        | C17630    |
|         R3  | 100K          | R_0805_2012Metric                                        | C17407    |
|         R4  | 1K            | R_0805_2012Metric                                        | C17513    |
|         R5  | 1K            | R_0805_2012Metric                                        | C17513    |
|         R6  | 10k           | R_0805_2012Metric                                        | C17733    |
|         R7  | 1M            | R_0402_2012Metric                                        | C26083    |
|         R2  | 10K           | R_0805_2012Metric                                        | C17733    |
|         R8  | 10K           | R_0805_2012Metric                                        | C17733    |
|         R11 | R_US          | R_0805_2012Metric                                        | C17733    |
|         R12 | R_US          | R_0805_2012Metric                                        | C17733    |
|         U1  | AMS1117-3.3   | Package_TO_SOT_SMD:SOT-223-3_TabPin2                     | C6186     |
|         U2  | STM32F103C8Tx | Package_QFP:LQFP-48_7x7mm_P0.5mm                         | C8734     |
|         U3  | EL817         | Package_DIP:SMDIP-4_W7.62mm                              | C106900   |
|         U5  | EL817         | Package_DIP:SMDIP-4_W7.62mm                              | C106900   |
|         U6  | EL817         | Package_DIP:SMDIP-4_W7.62mm                              | C106900   |
|         U7  | EL817         | Package_DIP:SMDIP-4_W7.62mm                              | C106900   |
|         U4  | SN65HVD230    | Package_SO:SOIC-8_3.9x4.9mm_P1.27mm                      | C12084    |
|         Y1  | 8MHz          | Crystal:Crystal_SMD_0603-2Pin_6.0x3.5mm                  | C128364   |




