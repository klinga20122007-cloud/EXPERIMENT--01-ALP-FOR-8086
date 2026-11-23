# EXPERIMENT--01-ALP-FOR-8086
 
## Name :LINGESHWARI K
## Roll no :212225220057
## Date of experiment :23-11-2026






## Aim: To Write and execute ALP on fundamental arithmetic and logical operations
## Components required: 8086  emulator 
## Theory 
Running The Emulator (emu8086) Intro 8086 Microprocessor Emulator, also known as EMU8086, is an emulator of the program 8086 microprocessor. It is developed with a built-in 8086 assembler. This application is able to run programs on both PC desktops and laptops. This tool is primarily designed to copy or emulate hardware. These include the memory of a program, CPU, RAM, input and output devices, and even the display screen. There are instructions to follow when using this emulator. It can be executed into one of the two ways: backward or forward. There are also examples of assembly source code included. With this, it allows the programming of assembly language, reverse engineering, hardware architecture, and creating miniature operating system (OS). The user interface of 8086 Microprocessor Emulator is simple and easy to manage. There are five major buttons with icons and titles included. These are “Load”, “Reload”, “Step Back”, “Single Step”, and “Run”. Above those buttons is the menu that includes “File”, “View”, “Virtual Devices”, “Virtual Drive”, and “Help”. Below the buttons is a series of choices that are usually in numbers and codes. At the leftmost part is an area called “Registers” with an indication of either “H” or “L”. The other side is divided into two, which enables users to manually reset, debug, flag, etc. What is 8086 emulator emu8086 is an emulator of Intel 8086 (AMD compatible) microprocessor with integrated 8086 assembler and tutorials for beginners. Emulator runs programs like the real microprocessor in step-by-step mode. it shows registers, memory, stack, variables and flags.


 ## Running the Emulator :
1.	Download and install emu8086 (www.emu8086.com) It is usually installed in C:\EMU8086 subfolder in the “Windows” directory
2.	  Run  emu8086 icon (on the desktop or in the c:\EMU8086 folder of window) It has green color 
 
 
3.		write the code for the appropriate program for ADDITION,SUBTRACTION, MULTIPLICATION,  DIVISION operations 

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







## Programs for arithmetic  operations

## Addition  of 8 bit ALP 
```
MOV AL,74H
MOV BL,69H
SUB AL,BL
HLT

```


## Output  
<img width="1093" height="557" alt="image" src="https://github.com/user-attachments/assets/3a2acb9b-9fef-4373-b800-c0b153756fa9" />



## Subtraction   of 8 bit numbers  ALP 
 ```
MOV AL,74H
MOV BL,69H
SUB AL,BL
HLT
```
## Output
<img width="1093" height="557" alt="image" src="https://github.com/user-attachments/assets/eb926dc5-68fc-4906-ba80-af41e08ae661" />

## Multiplication alp 
```
org 100h
MOV AL,75H
MOV BL,32H
MUL BL
HLT
ret
```
 ## Output  
<img width="1081" height="547" alt="image" src="https://github.com/user-attachments/assets/48035a40-5685-45f8-a6eb-7cdeca40a265" />



## Division alp 
```
org 100h
MOV AL,70H
MOV BL,10H
DIV BL
HLT
ret
```
## Output  
<img width="1102" height="557" alt="image" src="https://github.com/user-attachments/assets/a08596ee-3e5d-4da1-80cf-5c8dfbf5c53a" />


## AND GATE OF 8 BIT ALP:

```
org 100h
MOV AL,33H
MOV BL,44H
AND AL,BL
HLT
ret
```
## OUTPUT
<img width="1110" height="554" alt="image" src="https://github.com/user-attachments/assets/4f96d779-57d8-46e3-97e7-2a1e6523a146" />

## OR GATE OF 8 BIT ALP:
```
org 100h
MOV AL,33H
MOV BL,44H
OR AL,BL
HLT
ret
```
## OUTPUT
<img width="1092" height="573" alt="image" src="https://github.com/user-attachments/assets/d2a4178a-645c-45d7-9cc4-994cd3298e94" />

## NOT GATE OF 8 BIT ALP:
```
org 100h
MOV AL,65H
NOT AL
HLT
ret
```
## OUTPUT
<img width="1093" height="548" alt="image" src="https://github.com/user-attachments/assets/24045501-2c20-4b0c-ba94-e5f835de7b6c" />

## XOR GATE OF 8 BIT ALP:
```
org 100h
MOV AL,66H
MOV BL,77H
XOR AL,BL
HLT
ret
```
## OUTPUT
<img width="1101" height="563" alt="image" src="https://github.com/user-attachments/assets/bc1a27f0-808e-4463-82b1-b71a72c6f1b1" />


## Result :
 
Thus the program has been executed successfully.







