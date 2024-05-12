### EXPERIMENT--01-ALP-FOR-8086
# Name : Dhanusya.K
# Roll no : 212223230043
# Date of experiment : 11-03-24





### Aim: To Write and execute ALP on fundamental arithmetic and logical operations
## Components required: 8086  emulator 
## Theory 
Running The Emulator (emu8086) Intro 8086 Microprocessor Emulator, also known as EMU8086, is an emulator of the program 8086 microprocessor. It is developed with a built-in 8086 assembler. This application is able to run programs on both PC desktops and laptops. This tool is primarily designed to copy or emulate hardware. These include the memory of a program, CPU, RAM, input and output devices, and even the display screen. There are instructions to follow when using this emulator. It can be executed into one of the two ways: backward or forward. There are also examples of assembly source code included. With this, it allows the programming of assembly language, reverse engineering, hardware architecture, and creating miniature operating system (OS). The user interface of 8086 Microprocessor Emulator is simple and easy to manage. There are five major buttons with icons and titles included. These are “Load”, “Reload”, “Step Back”, “Single Step”, and “Run”. Above those buttons is the menu that includes “File”, “View”, “Virtual Devices”, “Virtual Drive”, and “Help”. Below the buttons is a series of choices that are usually in numbers and codes. At the leftmost part is an area called “Registers” with an indication of either “H” or “L”. The other side is divided into two, which enables users to manually reset, debug, flag, etc. What is 8086 emulator emu8086 is an emulator of Intel 8086 (AMD compatible) microprocessor with integrated 8086 assembler and tutorials for beginners. Emulator runs programs like the real microprocessor in step-by-step mode. it shows registers, memory, stack, variables and flags.


 ## Running the Emulator :
1.	Download and install emu8086 (www.emu8086.com) It is usually installed in C:\EMU8086 subfolder in the “Windows” directory
2.	  Run  emu8086 icon (on the desktop or in the c:\EMU8086 folder of window) It has green color 
3.		Write the code for the appropriate program for ADDITION,SUBTRACTION, MULTIPLICATION,  DIVISION operations 
4.	 Compile the program and check for the errors 
5.	Run (once there is no syntax error) 
6.	Click OK to see/view the output of your program on the Emulator screen. 
7.	After running the program, another menu screen will be displayed, where you have the option to “View” symbol table,
8.	 


![image](https://user-images.githubusercontent.com/36288975/189273263-d65baae9-4b8f-4723-afb3-c0ffa4052b04.png)











9.	Click on emulate to start emulation 








![image](https://user-images.githubusercontent.com/36288975/189273273-9bb36ec1-e2e8-4892-8d35-37707332bfdc.png)








10.	If no errors are found click on run the program and check the status of various flags in the flags tab as shown below 






![image](https://user-images.githubusercontent.com/36288975/189273277-113a2a33-4a40-4ff8-95a5-ecd3a1f504fe.png)







## Programs for arithmetic  operations:

# Addition  of 8 bit ALP 
## mov AL,48h
## mov BL,60h
## ADD AL,BL
## HLT


# Output:
![Screenshot 2024-03-11 112519](https://github.com/Dhanu654/EXPERIMENT--01-ALP-FOR-8086/assets/148514965/f1250846-dc44-4ceb-8e7c-a56f04b2c193)


 
# Subtraction   of 8 bit numbers  ALP
## mov AL,20h
## mov BL,25h
## sub AL,BL
## HLT
 
# Output:
![Screenshot 2024-03-11 112156](https://github.com/Dhanu654/EXPERIMENT--01-ALP-FOR-8086/assets/148514965/451f689f-3cf7-43ab-8c46-efab3fe4b49a)


# Multiplication alp 
## mov AL,27h
## mov BL,30h
## mul AL
## HLT
# Output:
 ![Screenshot 2024-03-11 112322](https://github.com/Dhanu654/EXPERIMENT--01-ALP-FOR-8086/assets/148514965/071db632-2a5d-4244-b33c-33126cef3bb3)

 


# Division alp 
## mov AL,40h
## mov BL,28h
## DIV AL
## HLT

# Output:
![Screenshot 2024-03-11 112430](https://github.com/Dhanu654/EXPERIMENT--01-ALP-FOR-8086/assets/148514965/2d9f8b7e-f5f7-45aa-8a16-7e0cd8688c75)




## Result :
Thus the execution of  ALP on fundamental arithmetic and logical operations is successfully verified.
 








