# RP2040 HAT Expansion
<img src = "https://github.com/sbcshop/RP2040-HAT-Expansion/blob/main/images/img.JPG"/>

### RP2040-HAT-Expansion is an RP2040 based board that allows to use Raspberry pi PICO and Raspberry pi HAT'S. 

## Raspberry Pi Configuration
<img src = "https://github.com/sbcshop/RP2040-HAT-Expansion/blob/main/images/img1.JPG"/>

## Run both Raspberry Pi and Raspberry pi PICO HAT'S
<img src = "https://github.com/sbcshop/RP2040-HAT-Expansion/blob/main/images/img3.jpg"/>

## Schematic diagram
<img src = "https://github.com/sbcshop/RP2040-HAT-Expansion/blob/main/images/img4.JPG"/>

## About RP2040 HAT Expansion
  * RP2040 microcontroller with 2MB Flash
  * USB Type C port for power and data (and for reprogramming the Flash)
  * Exposes 26 multi-function 3.3V General Purpose I/O (GPIO)
  * 23 GPIO are digital-only and 3 are ADC capable

## Operating Condition 
 * Operating Temp Max 85°C (including self-heating)
 * Operating Temp Min -20°C
 * VBUS 5V ± 10%.
 * VSYS Min 1.8V
 * VSYS Max 5.5V
 
## Parts specification   
1. **RP2040 Microcontroller IC**
   * Dual ARM Cortex-M0+ @ 133MHz
   * Support for up to 16MB of off-chip Flash memory via dedicated QSPI bus (External flash W25Q16JVSNIQ)
   * 264kB on-chip SRAM in six independent banks
   * On-chip programmable LDO to generate the core voltage
   * 2 on-chip PLLs to generate USB and core clocks
  
2. **Status Led**
   * Status led is connected to **GP24** Pin of PiSquare
  
3. **Three push buttons**
   * Reset button     (Reset pisquare)
   * Boot button      (Boot button of RP2040)

## Setup RP2040 HAT Expansion 
### It Support C/C++, MicroPython and circuitpython
1. Download Thonny IDE 

   https://thonny.org/
   
   <img src= "https://github.com/sbcshop/RoundyPi/blob/main/images/img.JPG" />
   
2. In RP2040 HAT Expansion we can use both MicroPython and CircuitPython, but we use micropython ( **use micropython** * )
   * Install **Micropython** in PiSquare
     first you need to press the boot button of RP2040 HAT Expansion, then connect the USB, don,t release the button until you connect the USB to the laptop. then you see a new        device named "RPI-RP2". 
        <img src= "https://github.com/sbcshop/RoundyPi/blob/main/images/img13.png" />
        
     After this go to run->select interpreter,choose device,port and install micropython (install firmware)
        <img src= "https://github.com/sbcshop/RoundyPi/blob/main/images/img2.png" />
        <img src= "https://github.com/sbcshop/RoundyPi/blob/main/images/img3.png" />
        <img src= "https://github.com/sbcshop/RoundyPi/blob/main/images/img4.png" />
   ### Or drag and drop the firmware "rp2-pico-20220618-v1.19.1.uf2" to RP2040 directory     
   * Install **CircuitPython** in RP2040 HAT Expansion
     Insert the circuit python to the PiSquare(it is circuit python firmware "adafruit-circuitpython-raspberry_pi_pico-en_US-7.1.1.uf2"). for this first you need to        press the boot button then connect the USB, don,t release the button until you connect the USB to the laptop. then you see a new device named "RPI-RP2" drag this      file "adafruit-circuitpython- raspberry_pi_pico-en_US-7.1.1.uf2" to this device as shown in figure:
     this is the official website, or you can download from here https://circuitpython.org/board/raspberry_pi_pico/
     
     <img src= "https://github.com/sbcshop/RoundyPi/blob/main/images/img13.png" />  
     When you properly insert the circuitpython then you see a new device that looks like the below image:-
     <img src= "https://github.com/sbcshop/RoundyPi/blob/main/images/img11.png" />
     
      After this go to run->select interpreter,choose device and port
         <img src= "https://github.com/sbcshop/RoundyPi/blob/main/images/img18.png" />
         <img src= "https://github.com/sbcshop/RoundyPi/blob/main/images/img19.png" />
         <img src= "https://github.com/sbcshop/RoundyPi/blob/main/images/img20.png" />
    
