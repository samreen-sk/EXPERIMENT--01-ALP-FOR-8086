# EXPERIMENT--01-ALP-FOR-8086
## Name : SHAIK SAMREEN
## Roll no : 212223110047





## Aim: To Write and execute ALP on fundamental arithmetic and logical operations
## Components required: 8086  emulator 
## Theory 
Running The Emulator (emu8086) Intro 8086 Microprocessor Emulator, also known as EMU8086, is an emulator of the program 8086 microprocessor. It is developed with a built-in 8086 assembler. This application is able to run programs on both PC desktops and laptops. This tool is primarily designed to copy or emulate hardware. These include the memory of a program, CPU, RAM, input and output devices, and even the display screen. There are instructions to follow when using this emulator. It can be executed into one of the two ways: backward or forward. There are also examples of assembly source code included. With this, it allows the programming of assembly language, reverse engineering, hardware architecture, and creating miniature operating system (OS). The user interface of 8086 Microprocessor Emulator is simple and easy to manage. There are five major buttons with icons and titles included. These are “Load”, “Reload”, “Step Back”, “Single Step”, and “Run”. Above those buttons is the menu that includes “File”, “View”, “Virtual Devices”, “Virtual Drive”, and “Help”. Below the buttons is a series of choices that are usually in numbers and codes. At the leftmost part is an area called “Registers” with an indication of either “H” or “L”. The other side is divided into two, which enables users to manually reset, debug, flag, etc. What is 8086 emulator emu8086 is an emulator of Intel 8086 (AMD compatible) microprocessor with integrated 8086 assembler and tutorials for beginners. Emulator runs programs like the real microprocessor in step-by-step mode. it shows registers, memory, stack, variables and flags.


 ## Running the Emulator :
1.	Download and install emu8086 (www.emu8086.com) It is usually installed in C:\EMU8086 subfolder in the “Windows” directory
2.	  Run  emu8086 icon (on the desktop or in the c:\EMU8086 folder of window) It has green color
3. write the code for the appropriate program for ADDITION,SUBTRACTION, MULTIPLICATION,  DIVISION operations 
4. Compile the program and check for the errors
5.  Run (once there is no syntax error)

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
MOV AL,11h;
MOV BL,20h;
ADD AL,BL;
MOV [6379h],AL;
ret

```
## Output  
 ![Screenshot 2024-08-23 135805](https://github.com/user-attachments/assets/18367edb-b5c5-42f2-8db5-5f6718a667b6)

## Subtraction   of 8 bit numbers  ALP 
```

org 100h
MOV AL,05h;
MOV BL,02h;
SUB AL,BL;
ret

```
## Output  
![Screenshot 2024-08-23 140547](https://github.com/user-attachments/assets/d322ac06-39ee-450c-89ec-bc90ebff90a2)

## Multiplication alp 
```

org 100h
MOV AL,03h;
MOV BL,02h;
MUL BL;
ret

```
 ## Output  
![Screenshot 2024-08-23 141109](https://github.com/user-attachments/assets/fdb25476-2708-4a61-abfe-21a8c3c55ba8)


## Division alp 
```

org 100h
MOV AL,10h;
MOV BL,02h;
DIV BL;
ret

```
## Output  
![Screenshot 2024-08-23 142040](https://github.com/user-attachments/assets/3b983224-6d20-44c4-aa6c-48e7923a8a6a)

## Programs for logical  operations

## OR Operation
```

org 100h
MOV SI,0532H;
MOV AX,0A35H; 
MOV BX,0B13H;
OR AX,BX;
ret

```
## output
![Screenshot 2024-08-23 142707](https://github.com/user-attachments/assets/f184479a-6df9-4808-bce0-cacf849bb290)

## AND Operation
```

org 100h
MOV SI,0532H;
MOV AX,0A35H; 
MOV BX,0B13H;
AND AX,BX;
ret

```
## output
![Screenshot 2024-08-23 143111](https://github.com/user-attachments/assets/b50a0210-f2e8-44aa-aad8-a54d478a2061)

## XOR Operation
```

org 100h
MOV SI,0532H;
MOV AX,0A35H; 
MOV BX,0B13H;
XOR AX,BX;
ret

```
## output
![Screenshot 2024-08-23 143321](https://github.com/user-attachments/assets/f078c199-5ff7-427c-a1ee-c34758d43f29)

## NOT Operation
```

org 100h
MOV SI,0532H;
MOV AX,0A23H; 
NOT AX;
ret

```
## output
![Screenshot 2024-08-23 143606](https://github.com/user-attachments/assets/01c2b8b6-beef-4f4a-b5ad-ac3b5e664d0a)


## Result :
 Thus the code executed successfully.








