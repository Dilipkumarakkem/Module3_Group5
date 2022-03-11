# Test Plan and output

|Test ID   |Test Case objective  |Input data   |Expected output   |Actual Output| Status|
|----------|---------------------|-------------|------------------|-------------|-------|
|TC-01|chcek encryption|3+4|7|7|Pass|
|TC-01     |lock the system    |7 & press the blue switch once |Car door locked(All leds are ON) | Car door locked(All leds are ON)| Pass|
|TC_02     |unlock the system  | press the blue switch is pressed twice | Car door unlocked(All leds are OFF) | Car door unlocked(All leds are OFF)|Pass|
|TC_03     | alarm activation/deactivation  | press the blue switch three times |Car alarm activate/deactivate(All led are ON in clockwise manner) | Car alarm activate/deactivate(All led are ON in clockwise manner)|Pass|
|TC_04| approach light |press the blue switch four  |Car alarm approach light(All led are ON in anti-clockwise manner)| Car alarm approach light(All led are ON in anti-clockwise manner)|Pass|
