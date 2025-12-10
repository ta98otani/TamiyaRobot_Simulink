# TamiyaRobot_Simulink
マイコンロボット工作セット (クローラータイプ)をSimulinkでプログラミングするブロックです
This Simulink model is created using "older" model with BBC micro:bit version 1.5
(micro:bit V2.1 version of robot is currently sold from Tamiya)

# Required Software
Created and Tested with R2024b version of MATLAB and Simulink
You need: MATLAB, Simulink, MATLAB Coder, Simulink Coder 
and Install following hardware support package
[https://jp.mathworks.com/academia/courseware/microbit.html](https://jp.mathworks.com/matlabcentral/fileexchange/60273-simulink-coder-support-package-for-bbc-micro-bit-board)

# Block Example includes access to distance sensor and motors
The block example here is quite simple.  
I used Simulink functions and MATLAB Function block for measureDistance function to access necessary I2C hardware components. 

<img width="1060" height="735" alt="image" src="https://github.com/user-attachments/assets/996ab24a-b832-401e-92b0-6b208be09661" />

