# TITLE: RKE (Remote Keyless Entry)
## INTRODUCTION:
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
### WHEN
In automobiles when to lock or unlock the doors and others functions.
### WHO
It will be used by the owner of the automobiles.
### HOW
  1. When we press the blue button once all four leds should ON that indicate car door is locked.
  2. When we press the blue button twice all four leds should OF that indicate cae door is unlocked.
  3. When we press the blue button thrice all four leds should ON in clockwise manner which indicate alarm activate/deactivate.
  4. When we press the blue button four times all four leds should ON in anticlockwise manner which indicates approval of light.
## SWOT
![SWOT](https://user-images.githubusercontent.com/98832647/157811229-94b1beb3-bd24-4608-b92a-4606e70aa0d8.png)
## Structural diagram
![Structural Diagram](https://user-images.githubusercontent.com/98832647/157826237-fa995719-e925-4004-824c-c127b1e5deaa.png)
## Behavioural diagram
![BD](https://user-images.githubusercontent.com/98832647/157826412-bd191fbb-2dea-493c-9617-eab2ec038471.jpeg)
# Test Plan and output

|Test ID   |Test Case objective  |Input data   |Expected output   |Actual Output| Status|
|----------|---------------------|-------------|------------------|-------------|-------|
|TC-01     |lock the system    |press the blue switch once |Car door locked(All leds are ON) | Car door locked(All leds are ON)| Pass|
|TC_02     |unlock the system  | press the blue switch is pressed twice | Car door unlocked(All leds are OFF) | Car door unlocked(All leds are OFF)|Pass|
|TC_03     | alarm activation/deactivation  | press the blue switch three times |Car alarm activate/deactivate(All led are ON in clockwise manner) | Car alarm activate/deactivate(All led are ON in clockwise manner)|Pass|
|TC_04| approach light |press the blue switch four  |Car alarm approach light(All led are ON in anti-clockwise manner)| Car alarm approach light(All led are ON in anti-clockwise manner)|Pass|
## main
![Main](https://user-images.githubusercontent.com/98832647/158003671-bf8aadc9-1596-4f07-8823-9f38537d4875.png)
## Lockdoor
![Lockdoor](https://user-images.githubusercontent.com/98832647/158003682-36e1de95-0ce2-4646-be86-db67fbcd158f.png)
## Closedoor
![unlock door](https://user-images.githubusercontent.com/98832647/158003707-4bd6f392-e515-4725-924a-5a65a8db396c.png)
## Alarm activate/deactivate
![Acti](https://user-images.githubusercontent.com/98832647/158003739-6c96d89a-dbc6-426b-b829-f90ef8580adc.png)
## approach light
![light approach ](https://user-images.githubusercontent.com/98832647/158003748-e903331a-118f-4731-8802-4cfde8bbf1c7.png)

