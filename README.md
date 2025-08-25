# EXPERIMENT--01-ALP-FOR-8086
## Name : Ram Prasath S
## Roll no : 212224040266 
## Date of experiment : 19.08.2025


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
mov ax,5aa3h
mov bx,2cfch
add ax,bx

ret
```

## Output  

<img width="1782" height="1124" alt="Screenshot 2025-08-21 134203" src="https://github.com/user-attachments/assets/c2a2b89c-128b-410b-bb1f-6f7e0f012f0c" />

 
## Subtraction   of 8 bit numbers  ALP 
```
org 100h

mov ax, 1468h
mov bx, 0057h
mov ax,[bx]
sub ax,bx

ret
```

 
## Output  

<img width="1775" height="1074" alt="Screenshot 2025-08-21 144003" src="https://github.com/user-attachments/assets/4959e828-1f45-479b-a079-d3871f74af28" />


## Multiplication alp 

```
org 100h

mov ax, 77h
mov bx, 34h
mul ax

ret
```

 ## Output  

<img width="1853" height="1094" alt="Screenshot 2025-08-21 144105" src="https://github.com/user-attachments/assets/2156d77d-831b-4dd7-963e-450d2dd2817f" />


## Division alp 

```
org 100h
mov ax, 290h
mov bx, 458h
div bx

ret
```


## Output  

<img width="1744" height="1064" alt="Screenshot 2025-08-21 144244" src="https://github.com/user-attachments/assets/adcc6a6d-01e9-42d3-b6f0-87502539855c" />

## AND Opreration:

```
org 100h

mov ax, 44h
mov bx, 98h
and ax,bx

ret
```
## Output

<img width="1652" height="1075" alt="Screenshot 2025-08-21 144508" src="https://github.com/user-attachments/assets/b2cafcd8-08a1-4875-9e65-5bd061e137dc" />


## OR Operation:

```
org 100h

mov ax, 4599h
mov bx, 5070h
or ax,bx

ret
```

## Output

<img width="1727" height="1073" alt="Screenshot 2025-08-21 144559" src="https://github.com/user-attachments/assets/faa156cb-46fc-4e96-bec5-4f9f5639e3d3" />


## X-0R Operation

```
org 100h
mov ax, 99h
mov bx, 60h
xor ax,bx

ret
```

## Output

<img width="1659" height="1074" alt="Screenshot 2025-08-21 144711" src="https://github.com/user-attachments/assets/c93cdfa4-13bd-4c29-989e-3bf54dacca0b" />


## NOT Operation:   

```
org 100h

mov ax, 60h
not ax

ret
```


## Output

<img width="1687" height="1069" alt="Screenshot 2025-08-21 144928" src="https://github.com/user-attachments/assets/d0b1fadf-a0aa-4632-935d-5c4578b926c5" />


## Result :
 
Thus the execution for ALP on fundamental arithmetic and logical operations in done
on 8086 microprocessor.







