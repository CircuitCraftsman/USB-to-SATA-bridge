# USB-to-SATA-bridge
Open-Source SATA to USB 3.0 bridge 🔧

 The main chip is TUSB9261 from Texas Instruments. It is compatible with SATA 1.5-Gbps or SATA 3.0-Gbps devices. The TUSB9261 comes with loaded firmware. Therefore you don't need to write firmware.
 
📍 The PCB was designed in 4 layers: Signal-Gnd-Pwr-Signal.

📍 SATA signals are routed as differential pair 100Ω (single-ended 50Ω) and length matched within 2.5 mil tolerance.

📍 USB 3.0 super speed signals are also differential pair 90Ω (single-ended 50Ω) and length matched.

 📍 JLC04161H-3313 controlled impedance PCB stackup.

📍The small fan was used to cool down the main chip. It is optional.

                                          System Block Diagram

![Alt text](https://github.com/CircuitCraftsman/USB-to-SATA-bridge/blob/main/USB%20to%20SATA%20bridge/Project%20Outputs/Images/Block%20diagram.png?raw=true)

                                                   MCU

![Alt text](https://github.com/CircuitCraftsman/USB-to-SATA-bridge/blob/main/USB%20to%20SATA%20bridge/Schematic/MCU.png)

                                                  Power
![Alt text](https://github.com/CircuitCraftsman/USB-to-SATA-bridge/blob/main/USB%20to%20SATA%20bridge/Schematic/Power.png)
