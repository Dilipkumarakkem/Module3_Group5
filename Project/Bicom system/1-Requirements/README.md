# TITLE: BICOM SYSTEM
## Introduction
This project is an BiCom System. This system Displays  Alarm Status, Door Status . There are leds signaling which helps us to identify the features. For example if we press a button 1 time all the LED will be ON which means the car door is locked, similarly for 2 times all leds will be OFF which means door unlocked, for 3 times the all leds will be ON in clockwise which means the alarm is activated/deactivated, for 4 times the all leds will ON in anti-clockwise direction which means approach light. There are several features like communication between car to key and key to car.
## Requirements:

 ###  High Level Requirements:
 |  ID         |	     DESCRIPTION | STATUS|
 |-------------|------------------|-------|
 |HLR01|STM32 CubeIDE|Implemented |
 |HLR02|CYGWIN |Implemented |
 |HLR03|qemu-system-gnuarmeclipse|Implemented |
 |HLR04|STM32F407VG|Implemented |
 |  HLR05	 |  It shall check window status the |Implemented |
 |   HLR06  | It shall check alarm status |Implemented |
 |  HLR07	  | It shall get the battery information |Implemented |
 |  HLR08	  | It shall check the door status |Implemented |
  
 ###  LOW Level Requirements:
 |  ID         |	     DESCRIPTION |STATUS|
 |-------------|------------------|------|
  |  LLR01	 |   Print "Lock" when the door is unlock |Implemented |
  |   LLR02	  | Print "UnLock" when the door lock |Implemented |
   |  LLR03	  | Print "Alarm Activation/Deactivation" when the alarm is activated/deactivated|Implemented |
   |  LLR04	  | Print "Approach Light" when Blue switch is pressed four times |Implemented |
   
## 5W's and 1H
### WHAT
The term remote keyless system (RKS), also called keyless entry or remote control locking, refers to a lock that uses an electronic remote control as a key which is activated by a handshield device.
### WHY
When within a few yards of the car pressing a button on the remote can lock or unlock the doors, and may perform other functions.
### WHERE
It is used in automobiles like cars etc.,
### WHEN
In automobiles when to lock or unlock the doors and other functions.
### WHO
It will be used by the owner of the automobiles.
### HOW
  1. When we press the blue button once all four leds should ON that inndicate car door is unlocked.
  2. When we press the blue button twice all four leds should OF that indicate cae door is unlocked.
  3. When we press the blue button thrice all four leds should ON in clockwise manner which indicate alarm activate/deactivate.
  4. When we press the blue button four times all four leds should ON in anticlockwise direction which indicate approach light.
## SWOT
![SWOT](https://user-images.githubusercontent.com/98832647/157811229-94b1beb3-bd24-4608-b92a-4606e70aa0d8.png)
