# Clover-boot-GPD-WIN-2
### macOS Mojave build for GPD WIN 2 handheld x86 PC


## Getting Started
  #### 1. BIOS Setup
  Power on devic, then press and hold `Esc` or `Delete` until the setup screen is loaded.
  #### 2. Enable Thunderbolt
  Find the Thunderbolt configuration menu and make sure thunderbolt is not its default value `fully disabled`.
  Also, enable booting from thunderbolt storage. You can play around with all the settings in thunderbolt, not sure 
  yet what effect the other thunderbolt options have.
  #### 3. Use an adapter to connect install USB boot image into the USB-C port. 
  **(official Apple USB thunderbolt adapter is recommended for battery charging during the installation.)**

![alt text](https://raw.githubusercontent.com/MattAndrzejczuk/Clover-boot-GPD-WIN-2-/master/GPDinstalldemo.jpg)

This is a work in progress for supporting all macOS Mojave drivers on GDP WIN 2 hardware.

## Drivers Successfully Installed
**- Bluetooth**

**- Internal Audio**

**- Intel Graphics**

**- Internal Fan Speed & Thermal Sensors**

## Unresolved Issues 
**- No WIFI yet, (intel AC 7265)**

**- Thunderbolt Alpine Ridge controller**


**- No battery status**


**- Internal MicroSD card reader not working**


![alt text](https://raw.githubusercontent.com/MattAndrzejczuk/Clover-boot-GPD-WIN-2-/master/DEMO.jpeg)

___

## GPD WIN 2 Hardware 

### Intel® Core™ m3-7Y30 Processor
Codename **Kaby Lake**

Lithography **14 nm**

Cores **2**

Threads **4** 

Processor Base Frequency **1.00 GHz**

Max Turbo Frequency **2.60 GHz**

Cache **4 MB SmartCache**

Bus Speed **4 GT/s OPI**

TDP **4.5 W**

Configurable TDP-up Frequency **1.60 GHz**

Configurable TDP-up **7 W**

Configurable TDP-down Frequency **600 MHz**

Configurable TDP-down **3.75 W**

___

### Intel HD Graphics 615
Codename	**Kaby-Lake GT2**

Architecture	**Intel Gen. 9 (Kaby Lake)**

Pipelines	**24 - unified**

Core Speed	**300 - 1050 (Boost) MHz**

Memory Bus Width	**64/128 Bit**

Memory Type	**DDR3L/LPDDR3**

Shared Memory	**yes**

___

### INTEL® DUAL BAND WIRELESS-AC 7265

Bands **2.4 GHz, 5 GHz**

Wi-Fi **802.11ac**

Bluetooth **Version 4.2**

System Interface Type **Wi-Fi**(``PCIe``), **BT**(``USB``)





