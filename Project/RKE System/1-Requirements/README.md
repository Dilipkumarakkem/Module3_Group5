# TITLE: RKE (Remote Keyless Entry)
## INTRODUCTION
RKE (Remote Keyless Entry):
Remote keyless entry (RKE) is an electronic access system that can be controlled from a distance. 
RKEs, which are typically used to remotely lock or unlock doors, require the end user to initiate an action that
 will cause a physical or software key fob to transmit a radio signal to a receiver that controls an electronic lock. 
 Typically, the action is to press a button on a physical fob or mobile app.
Remote keyless entry, which is commonly used to protect vehicles from theft,
 can be contrasted with passive keyless entry (PKE), which does not require any 
 action on the part of the end user. Most RKEs operate at a frequency of 315 MHz for North America-made 
 cars and at 433.32 MHZ for European, Japanese and Asian cars. Modern systems since the mid-1990s implement 
 encryption as well as rotating entry codes to prevent car thieves from intercepting and spoofing the signal.
  A controller chip in the receiver changes the exact frequency required for RKE each time the lock is accessed, 
  a security feature known as rolling code or hopping code.

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
  
 ###  Low Level Requirements:
 |  ID         |	     DESCRIPTION |STATUS|
 |-------------|------------------|------|
  |  LLR01	 |   Print "Lock" when the door is unlock |Implemented |
  |   LLR02	  | Print "UnLock" when the door lock |Implemented |
   |  LLR03	  | Print "Alarm Activation/Deactivation" when the alarm is activated/deactivated|Implemented |
   |  LLR04	  | Print "Approach Light" when Blue switch is pressed four times |Implemented |
   
## 5W's and 1H
### WHAT
The term remote keyless system (RKS), also called keyless entry or remote control locking, refers to a lock that uses an electronic remote control as a key which is activated by a handheld device.
### WHY
When within a few yards of the car pressing a button on the remote can lock or unlock the doors, and may perform other functions.
### WHERE
It is used in automobiles like cars etc.
### When
In automobiles when to lock or unlock the doors and others functions.
### WHO
It will be used by the owner of the automobiles.
### HOW
  1. When we press the blue button once all four leds should ON that indicate car door is locked.
  2. When we press the blue button twice all four leds should OF that indicate cae door is unlocked.
  3. When we press the blue button thrice all four leds should ON in clockwise manner which indicate alarm activate/deactivate.
  4. When we press the blue button four times all four leds should ON in anticlockwise manner which indicate approach light.
## SWOT
![SWOT](https://user-images.githubusercontent.com/98832647/157811229-94b1beb3-bd24-4608-b92a-4606e70aa0d8.png)
