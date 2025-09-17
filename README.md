# EXPERIMENT--01-ALP-FOR-8086
# Name : DHINESH M
# Roll no :212223040040
# Date of experiment : 01/09/2025





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
org 100h

mov al,88h
mov bl,65h
add al,bl

ret
```


## Output  

 <img width="1908" height="1190" alt="Screenshot 2025-08-31 183306" src="https://github.com/user-attachments/assets/271bc294-9c5f-45c5-88da-0c6276e72364" />

## Subtraction   of 8 bit numbers  ALP 
```
org 100h

mov al,84h
mov bl,63h
sub al,bl

ret
```
 
## Output
<img width="1920" height="1200" alt="Screenshot 2025-08-31 183428" src="https://github.com/user-attachments/assets/d364ebbe-189e-4946-9537-e0a7f227b2b9" />

## Multiplication alp 
```
org 100h

mov al,75h
mov bl,32h
mul bl

ret
```
 ## Output  
<img width="1920" height="1200" alt="Screenshot 2025-08-31 183644" src="https://github.com/user-attachments/assets/f020309c-fb01-4f89-82ea-40b25204e37f" />


## Division alp 
```
org 100h  

mov al,68h
mov bl,18h
div bl

ret
```

## Output  
<img width="1920" height="1200" alt="Screenshot 2025-08-31 183815" src="https://github.com/user-attachments/assets/ac0fab71-4200-4642-867b-53c0d9b1fb49" />

## AND alp
```
org 100h

mov al,44h
mov bl,98h
and al,bl

ret
```
## Output 
<img width="1920" height="1200" alt="Screenshot 2025-08-31 184742" src="https://github.com/user-attachments/assets/2fdcc8e5-3acf-4ac8-b840-cef89b28bf18" />

## OR alp
```
org 100h

mov al,45h
mov bl,66h
or al,bl

ret
```
## Output
<img width="1920" height="1200" alt="Screenshot 2025-08-31 184337" src="https://github.com/user-attachments/assets/a404e88e-e58a-4b6d-b71f-812ef740f668" />

## NOT alp
```
org 100h

mov al,60h
not al

ret

```
## Output
<img width="1919" height="1137" alt="Screenshot 2025-09-01 094812" src="https://github.com/user-attachments/assets/31dd005d-36ae-4b2c-9041-41cd6428bccf" />


## XOR alp
```
org 100h

mov al,99h
mov bl,60h
xor al,bl

ret
```
## Output
<img width="1920" height="1200" alt="Screenshot 2025-08-31 185015" src="https://github.com/user-attachments/assets/7397e51c-2f23-4d4a-bdc6-e7ea33b550bc" />

## NAND alp
```
org 100h

MOV al,0BH
MOV bl,05H
AND al,bl
NOT bl

ret
```
## Output
<img width="1908" height="1190" alt="Screenshot 2025-09-01 193626" src="https://github.com/user-attachments/assets/77e58786-dfd6-406a-a0ab-40ec9b0c24ac" />



## Result :

The execution of ALP on fundamental arithmetic and logical operations is successfully completed
