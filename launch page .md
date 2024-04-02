**Vaaman** is a high-performance edge computing board, featuring a six-core ARM CPU and an FPGA with 112,128 logic cells. Its unique design makes it ideal for addressing many challenges unmet by current products. With a 300-Mbps link between FPGA and CPU, Vaaman is optimized for hardware acceleration and excels at parallel computing. Vaaman's versatility extends to its comprehensive range of interfaces, including PCI, HDMI, USB, MIPI, audio, Ethernet, Wi-Fi, Bluetooth, BLE, LVDS, and GPIOs. 

Vaaman accelerates your most demanding edge-computing scenarios.

{vaaman-angle-03 | link}

## Overcome Challenges With Parallel Processing

Vaaman stands at the forefront of Edge AI and ML acceleration, providing a dynamic platform for groundbreaking applications. We are currently developing a custom platform called "Gati," which will enable custom end-to-end solutions, and enable convolutional neural networks (CNN) exclusively on Vaaman. By mapping these advanced algorithms to the FPGA, the CPU is left free to handle other critical tasks, which improves overall performance.
  
- **Object Classification and Detection:** Vaaman excels at object classification tasks, leveraging FPGA parallel processing to swiftly categorize and identify objects in real time.
- **Human Presence and Gesture Detection:** Vaaman is capable of detecting human presence in real time and accurately counting people to facilitate applications in retail analytics, building management, and more. Gesture detection can open the door to intuitive human-machine interaction.
- **Edge Machine Vision:** Vaaman transforms machine vision at the edge, accelerating the processing of visual data for applications like quality control, defect detection, and industrial automation. 
- **Cryptographic Algorithms:**  Vaaman processes advanced cryptographic algorithms efficiently thanks to the parallel nature of Vaaman. FPGAs frequently outperform GPUs when it comes to cryptographic acceleration.
- **Video and Image Decoders:** Real-time video and image processing benefit from Vaaman's parallel task handling and high-speed performance with consistent latency. Vaaman's reconfigurability allows us to deploy more efficient encoders and decoders.

{vaaman-block-diagram | link}
   
## Use Vaaman's Onboard FPGA as Part of Your Toolchain

- **Create Custom Hardware Platforms:** You have the freedom to configure Vaaman's FPGA to create custom hardware platforms, tailoring the system to specific needs or applications.
- **Quick Testing and Prototyping:** Vaaman accelerates the development process by allowing rapid testing and prototyping of peripheral systems using the FPGA. Engineers can experiment with different configurations to optimize functionality.
- **Simulate Specialized Interfaces:** Vaaman can serve as an educational platform by simulating various interfaces, providing a hands-on learning experience for students and enthusiasts interested in hardware and communication protocols.
- **Real-Time Testing of New or Niche Protocols:** Researchers and developers can use Vaaman to test a variety of communication protocols in real time while exploring and validating innovative interface designs.

## Supported Platforms

Pre-built images for Android 12.1, Debian (Bullseye 11), and Ubuntu (Focal 20.04).

{vaaman-angle-05 | link}

## Specifications

**SOC:** Rockchip RK3399 (Dual Cortex-A72 + Quad Cortex-A53)
- Mali-T864 GPU, OpenGL ES1.1/2.0/3.0/3.1, OpenCL, DX11
- 2 GB or 4 GB of LPDDR4 RAM

**Ports:**
- 2x USB 2.0 Type-A
- 1x USB 3.0 Type-A
- 1x HDMI 2.0 (Micro), Supports maximum 4K @ 60 Hz display
- 1x MIPI-DSI, Supports 2560x1600 @ 60 fps output with dual channel
- 1x USB Type-C with DP, Supports maximum 4K @ 60 Hz display
- 1x MIPI-CSI, 2 lanes via FPC connector, support up to 800 MB/s bandwidth
- 3.5 mm jack with mic
- Gigabit ethernet (Realtek RTL8211E)
- MicroSD

**Wireless:** Integrated RTL8822CS Wi-Fi and Bluetooth Combo Module (6222B-SRC)
- Wi-Fi 2.4G+5G Wi-Fi 2T2R
- Bluetooth 5.0

**Storage:** 16/32/64/128-GB eMMC built-in

**PCIe:** PCIe 2.1 (4 full-duplex lanes at 20 Gbps)

**Real-Time Clock:** RTC support via built-in battery interface

**Power:** 18-W USB Type-C PD

**I/O:**
- 40-pin GPIO header: supports one 12-pin PMOD and two LVDS lanes or 25 GPIOs
- 1x UART
- 2x SPI bus
- 2x I²C bus
- 1x PCM/I²S
- 1x SPDIF
- 1x PWM
- 1x ADC
- 6x GPIO
- 2x 5-V DC
- 2x 3.3-V power pin

**FPGA:** Efinix Trion T120
- Logic Elements: 112,128
- Embedded Memory: 5,407 Kb
- Embedded Memory Blocks (5 Kb each): 1,056
- Embedded Multipliers: 320 (18x18 bit)
- 4GBit or 8GBit of DDR3L dedicated RAM, x16 PHY with memory controller hard IP, 25.6 Gbps aggregate bandwidth
- Supports 1.8, 2.5, and 3.3-V single-ended I/O standards and interfaces
- Up to 16 PLL-generated global clock signals 

**FPGA Interface Blocks:**
- GPIO
- PLL
- LVDS 800 Mbps per lane with up to 20 TX pairs and 20 RX pairs
- MIPI DPHY with CSI-2 controller hard IP, 1.5 Gbps per lane
- Direct CSI-2 connectors

**Dimensions & Weight:**
- Length 85 mm x Width 85 mm
- Final weight 62 grams and height 20.5 mm



{vaaman-cnn | link}
## Acessories 
**INSIDE THE BOX**

**Power Delivery cable:-** The length of cable is **1.5 meters**. It's a Type-C to Type-C PD cable.

**OPTIONAL ACESSORIES**

**Power Delivery (PD) Adapter:-** Vicharak Vaaman will need a 12V-5A power adapter. This adapter is a Power Delivery (PD) adapter and can be used to power the board.

**Wi-Fi and Bluetooth Antenna:-** The antenna is connected to the board via a U.FL connector. The antenna is a 2.4 GHz antenna and is compatible with 802.11 b/g/n Wi-Fi and Bluetooth 4

**Heat Sink Accessory:-**  The heat sink is attached to the board using 4 M3 screws. The heat sink is designed to dissipate heat from the board when the board is used in high power applications.

**USB to TTL Serial Converter:-** The USB to TTL Serial Converter is a module for converting USB interface to serial interface. It is useful for debugging your Vaaman board.

**M.2 Expansion Board:-** The M.2 Expansion Board is a board that plugs into the M.2 connector on the Vaaman SBC. The board provides a 4-lane PCIe slot that can be used to connect an NVMe SSD.

**UART Expansion Board Module:-** The UART Expansion Board is a serial port expansion board that uses FPGA and LVDS technology to provide 8 additional UART ports. It can provide 20 additional UART ports when connected to LVDS TX and RX on the Vaaman board.

**Raspberry Pi Camera Module:-** You can use the Raspberry Pi Camera Module v1 and v2 with the Vicharak Vaaman. The raspi camera module is a small circuit board that connects to the CSI connector on the Vaaman and allows you to take photos and videos.

We do not build or design the camera module, but we do test it for compatibility with our Vaaman. We recommend buying the original camera module from the Raspberry Pi Foundation, or from one of our authorized resellers or Crowd Supply.

**USB-C to USB-A Cable:-** A USB-C to USB-A cable is required to connect the Vicharak's Vaaman SBC to the host computer. The cable is not included in the Vicharak Vaaman board kit. You can purchase any USB-C-to-USB-A cable from anywhere. We recommend the Basics USB-C to USB-A Male cable.

## Legend
Insert the legend image 

## Safty
To affirm our commitment to consumer safety, we will highlight our product’s robust protective casing, comprehensive ESD, and under- and over-voltage protection. We will also showcase our compliance with global standards through **FCC** and **CE** certifications. These safety assurances will position our product as a customer-centric solution that prioritizes not just functionality but also the well-being of our users.

## Comparison Table 

| SBC Name                                        | VAAMAN                                                                                                                                                     | RASPBERRY PI 4                                                  | JETSON NANO                                 | ALINX AXU2CGB                                                                                       | ULX3S                                          | PolarFire SoC Icicle Kit                                                  | snickerdoodle                                                                      | Kria KV260                                      |
| ----------------------------------------------- | ---------------------------------------------------------------------------------------------------------------------------------------------------------- | --------------------------------------------------------------- | ------------------------------------------- | --------------------------------------------------------------------------------------------------- | ---------------------------------------------- | ------------------------------------------------------------------------- | ---------------------------------------------------------------------------------- | ----------------------------------------------- |
| **SOC**                                            | • RockChip RK3399                                                                                                                                          | • Broadcom BCM2711                                              | • NVIDIA® Tegra® X1 series SoC              | • Xilinx Zynq UltraScale+ MPSOC XCZU2CG                                                             | NA                                             | NA                                                                        | NA                                                                                 | Zynq™ UltraScale+™ MPSoC                                              |
| **CPU**                                             | • 6 Core ARM CPU @ 1.8 Ghz ( 4 Core--2 Core ) | • Quad core Cortex-A72 (ARM v8) 64-bit SoC @ 1.5GHz             | • Quad-core ARM A57 @ 1.43 GHz              | • Dual-core Arm® Cortex®-A53 MPCore™ up to 1.3GHz<br>• Dual-core Arm Cortex-R5F MPCore up to 533MHz | NA                                             | 600 MHz clock<br>1 x RV64IMAC core by SiFive<br>4 x RV64GC core by SiFive | 32-bit dual-core ARM Cortex-A9 w/640kB cache and 2x 128-bit NEON coprocessors      | Quad-core Arm® Cortex®-A53 MPCore™ up to 1.5GHz |
| **GPU**                                             | • ARM Mali-T860MP4 GPU, support OpenGL ES1.1/2.0/3.0, OpenCL1.2, DirectX11.1                                                                               | • Broadcom VideoCore VI                                         | • 128-core Maxwell                          | • Mali™-400 MP2 up to 667MHz                                                                        | NA                                             | NA                                                                        | NA                                                                                 | Mali™-400 MP2 up to 667 MHz                     |
| **MEMORY**                                          | • 2GB LPDDR4-3200 SDRAM                                                                                                                                    | • 1GB, 2GB, 4GB or 8GB LPDDR4-3200 SDRAM                        | • 4 GB 64-bit LPDDR4 25.6 GB/s              | • 2GByte DDR4, 32bit, Data Speed 2400Mbps                                                           | NA                                             | NA                                                                        | NA                                                                                 |                                                 |
| **STORAGE**                                         | • High-Speed eMMC 16GB/32GB/64GB/128GB<br>• MicroSD (TF) Card Slot<br>• PCIE for extended SSD                                                                   | • microSD                                                       | • microSD<br>• 16GB eMMC 5.1                | • 1GB eMMC, 256Mb QSPI FLASH<br>• SD Card Slot<br>• PCIe\*1 Interface Slot                          | •Micro-SD                                      | 1 Gb SPI flash<br>8 GB eMMC flash or SD card slot (multiplexed)           | NA                                                                                 | 4 GB 64-bit DDR4 (non-ECC) and 16 GB eMMC       |
|                                                 |  **Hardware Features**                                                                                                                                          |                                                                 |                                             |                                                                                                     |
| **DISPLAY**                                         | • 1 x HDMI 2.0 (Micro)，Support maximum 4K@60Hz display<br>• 1 x MIPI, Support 2560x1600@60fps output with dual channel<br>• DisplayPort over Type-C        | • 2 × micro-HDMI ports<br>• 2-lane MIPI DSI display port        | • HDMI<br>• Display port                    | • Mini DP interface, Supports 4K x 2K@30Fps Output                                                  | • Placeholder for 0.96" SPI color OLED SSD1331 | NA                                                                        | NA                                                                                 | DisplayPort 1.2a                                |
| **AUDIO**                                           | • 3.5mm jack with mic                                                                                                                                      | • 3.5mm jack                                                    |                                             |                                                                                                     | • 3.5mm jack                                   | • 3.5mm jack                                                              | NA                                                                                 | NA                                              |
| **ETHERNET**                                        | • 10/100/1000Mbps Ethernet (Realtek RTL8211E)                                                                                                              | • Gigabit Ethernet                                              | • Gigabit Ethernet                          | • Gigabit Ethernet                                                                                  | • Via ESP32, USB                               | 2 x Gigabit Ethernet                                                      | 2x gigabit ethernet                                                                | 1Gb Ethernet                                    |
| **CAMERA**                                          | • MIPI CSI 2 lanes via FPC connector, support up to 800MP camera                                                                                           | • MIPI CSI 2 lanes                                              | • 2x MIPI CSI-2 DPHY lanes                  | • MIPI Camera Interface                                                                             | NA                                             | NA                                                                        |                                                                                    | 3 MIPI sensor interfaces, USB cameras           |
| **WIRELESS**                                        | • Integrated WiFi Combo Module (6222B-SRC)<br>• WiFi 2.4G+5G WiFi 2T2R<br>• BT5.0                                                                          | • 2.4 GHz and 5.0 GHz IEEE 802.11ac wireless<br>• Bluetooth 5.0 | • M.2 Key E                                 |                                                                                                     | • ESP32-WROOM-32                               | NA                                                                        | 150Mbps 2x2 MIMO 2.4GHz/5GHz 802.11n 3Mbps dual-mode Bluetooth 4.0 Classic+EDR/BLE | NA                                              |
| **PCIe**                                            | • x4 PCIe Gen 2 Interface via FPC connector                                                                                                                | NA                                                              | NA                                          | • PCIe\*1 Interface Slot                                                                            | NA                                             | x4 PCIe® Connector                                                        | • PCIe\*1 Interface Slot                                                           | NA                                              |
| **USB**                                             | • 2 x USB2.0 HOST，<br>• 1 x USB3.0，<br>• 1 x USB3.0 Type-C                                                                                                 | • 2 x USB 3.0 ports<br>• 2 x USB 2.0 ports.                     | • 4 x USB 3.0<br>• 1 x USB 2.0 Micro-B      | • 4 x USB 3.0 Host, Speed up to 5.0 Gb/s                                                            | • 1 x USB 2.0 Micro-B                          | • 1 x USB 2.0 Micro-B                                                     | NA                                                                                 | 4 x USB 3.0 Host, Speed up to 5.0 Gb/s          |
| **RTC**                                             | • Support RTC, on-board backup battery interface                                                                                                           | NA                                                              |                                             |                                                                                                     | • MCP7940N, Low Power Sleep, Wakeup            | NA                                                                        |                                                                                    |                                                 |
| **IOs**                                             | • 1 x UART<br>• 2 x SPI bus<br>• 2 x I2C bus<br>• 1 x PCM/I2S<br>• 1 x SPDIF<br>• 1 x PWM<br>• 1 x ADC<br>• 6 x GPIO                                       | • GPIO<br>• I2C<br>• I2S<br>• SPI<br>• UART                     | • GPIO<br>• I2C<br>• I2S<br>• SPI<br>• UART | • 2\*40-pin Expansion Connectors for Modules                                                        | • 56-pin Expansion Connectors for Modules      | 40-pin Raspberry Pi® Expansion Connector                                  | • 179-pin Expansion Connectors for Modules                                         | Pmod 12-pin interface                           |
|                                                 |**FPGA on Board**                                                                                                                                              |                                                                 |                                             |                                                                                                     |
| **FPGA CHIP**                                       | • Efinix® T120F324                                                                                                                              | NA                                                              | NA                                          | NA                                                                                                  | • Lattice ECP5 LFE5U-85F-6BG381C               | Microchip’s PolarFire SoC (MPFS250T-FCVG484EES)                           | • Xilinx Zynq-7020                                                                 | Kria KV260                                      |
| **MEMORY**                                          | • DRAM Chip DDR3 SDRAM 4GBit or 8GBit 256Mx16 1.35V/1.5V.<br>• 128 Mbit SPI NOR flash memory                                                                        | NA                                                              | NA                                          | NA                                                                                                  | • 32 MB SDRAM 166 MHz                          | • 2 GB LPDDR4 x 32                                                        | • 16MB XIP NOR + up to 200GB SDIO NAND via captive microSD card cage               | 4GB (4 x 512Mb x 16 bit) [non-ECC]              |
| **SYSTEM LOGIC CELLS (K)**                          | • 112K+                                                                                                                                                    | NA                                                              | NA                                          | • 103K                                                                                              | • 12K – 84K                                    | • 254K                                                                    | • 17.6K                                                                            | 256K                                            |
| IOs                    | • 40-pin GPIO header: supports one 12-pin PMOD and two LVDS lanes or 25 GPIOs | NA | NA | NA     | NA          | NA     | NA      | NA   |
| **TOTAL BLOCK RAM (Mb)**                            | • 5.3                                                                                                                                                      | NA                                                              | NA                                          | • 5.3                                                                                               | • 3.7                                          | NA                                                                        | • 36 KB                                                                            | 144                                             |
| **DSP BLOCKS**                                      | • 320                                                                                                                                                      | NA                                                              | NA                                          | • 240                                                                                               | NA                                             | NA                                                                        | • 220                                                                              | 1.2K                                            |
| **MIPI 4-LANE DPHY WITH BUILT-IN CSI-2 CONTROLLER** | • 1 TX<br>• 1 RX                                                                                                                                           | NA                                                              | NA                                          | NA                                                                                                  | NA                                             | NA                                                                        | NA                                                                                 | Multi-camera Support: Up to 8 interfaces        |
| **LVDS (TX, RX)**                                   | • 20 TX<br>• 20 RX                                                                                                                                         | NA                                                              | NA                                          | NA                                                                                                  | 28                                             | NA                                                                        | NA                                                                                 | NA                                              |
| **PLLs**                                            | • 7                                                                                                                                                        | NA                                                              | NA                                          |                                                                                                     | NA                                             | NA                                                                        | • 4                                                                                | NA                                              |
| **PRICE***                                         | $180.00                                                                                                                                                    | $75                                                             | $300                                        | $251                                                                                                | $252                                           | $599                                                                      | $245                                                                               | $300                                            |
## Manufacturing Plan
We have spent the last SIX months leading up to the campaign finalizing part selections, nailing down the supply chain, negotiating with vendors and distributors, evaluating contract manufacturers, and setting up for high-volume production and fulfillment. The minute we hit our goal, we will be placing orders for long-lead-time parts and wrapping up the final hardware details.

Pre-order Vaaman volumes will dictate where assembly ultimately takes place. We are planning (and hoping) to have board assembled by one of our partners in China, but only if volume warrants. Fabrication will take place either in/near Shenzhen. Cable assemblies are scheduled to be assembled and packaged in China.

Crowd Supply has also offered to assist us with packaging requirements/sourcing as well as domestic and international logistics to ensure you receive the best and most reliable customer service and ordering experience possible.
## Risk and Challenges
The journey of manufacturing hardware at scale is filled with challenges. From potential disruptions in supply chains to quality assurance, from component shortages to unforeseen natural disasters, there are numerous hurdles that could impact the successful delivery of a hardware product.

Similarly, software development is not without its risks and demands a meticulously designed and executable strategy. Our foremost commitment is to ensure the utmost quality of Vaaman’s fundamental software components: wireless connectivity, board support packages, mobile applications, backend device management and data security, and baseboard functionality.

We’ve made every effort to account for possible delays in delivery, quality issues, and other unexpected obstacles, ensuring they can be resolved without causing fulfillment delays. However, we pledge to maintain transparency, responsiveness, and promptness in providing updates throughout this journey. Our backers will always be kept informed about our progress, our direction, the challenges we may encounter, and the steps we are taking to overcome them. We deeply value your trust and support in us.
## Open Source

This is an open hardware project, and we will release schematics of the board after completing fulfillment to backers. Learn more about Vaaman by [reading our documentation](https://docs.vicharak.in/).

## Support & Documentation
You will find setup and configuration guides, tutorials, and sample code in our Repository on GitHub. Additional resources are available in our Community Projects repository, or you can also reach out to other Vaaman developers through our Gitter community and Discord Community.

## Interested in This Project?

You can sign up at the top of this page to be notified when the campaign launches and to receive other updates. We only send out relevant information, and you can unsubscribe at any time.
