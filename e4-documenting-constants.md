|Name|Description|Type|Value|
|:---|:----------|:---:|:--:|
|`commMoveBackward`|Command code to instruct the robot to move backward.|Number|0x02|
|`commMoveForward`|Command code to instruct the robot to move forward.|Number|0x01|
|`commStop`|Command code to instruct the robot to stop.|Number|0x00|
|`commTurnLeft`|Command code to instruct the robot to turn left.|Number|0x03|
|`commTurnRight`|Command code to instruct the robot to turn right.|Number|0x04|
|`errBadCommand`|Error code the robot sends when it does not recognize a command.|Number|0xFF02|
|`errBadSignal`|Error code the robot sends when the signal from the device is not good.|Number|0xFF01|
|`errBatteryLow`|Error code the robot sends when its batteries are low.|Number|0xFF03|
|`productName`|Marketing name for the robotic ball product.|String|RoboBall|
|`versionNumber`|Software development kit version number.|Number|1.6|
<br>

`commMoveBackward = 0x02`;\
Command code to instruct the robot to move backward.

`commMoveForward = 0x01`;\
Command code to instruct the robot to move forward.

`commStop = 0x00`;\
Command code to instruct the robot to stop.

`commTurnLeft = 0x03`;\
Command code to instruct the robot to turn left.

`commTurnRight = 0x04`;\
Command code to instruct the robot to turn right.

`errBadCommand = 0xFF02`;\
Error code that the robot sends when it does not recognize a command.

`errBadSignal = 0xFF01`;\
Error code that the robot sends when the signal from the device is not good.

`errBatteryLow = 0xFF03`;\
Error code that the robot sends when its batteries are low.

`productName = RoboBall`;\
 Marketing name for the robotic ball product.

`versionNumber = 1.6`;\
Software development kit (SDK) version number.
<br><br><br>

What the fictional engineering team provided:
* Constants that start with “comm” are codes that you send to the robot to tell it what to do.
* Constants that start with “err” are error codes that the robot sends back if there is a problem.
* errBadSignal means that the robot is not getting a good signal from the device.
* errBadCommand means that you sent a command that the robot doesn’t recognize.
* errBatteryLow means that the robot’s batteries are low.
* productName is a string with the name of the physical product. 
* versionNumber is the SDK version number.
<br>

*Exercise 4 – Documenting Constants*, from this [course].  

[course]: https://www.udemy.com/course/coding-for-writers-1-basic-programming/