# SQUARE AND CUBE OF A NUMBER
# 8051 Square  Program

## AIM
To write and execute an Assembly language program for finding the square of a given data using 8051 microcontroller in Keil software.

## APPARATUS REQUIRED
- Personal computer
- Keil μVision IDE

## ALGORITHM
1. Enter the Assembly language program.
2. Provide the input value to Port 0 (P0).
3. Execute the program.
4. The output square value is stored in Port 2 (P2).

## PROGRAM
```
ORG 0000H
MOV R0,#50#
MOV A,@R0
MOV B,@R0
MUL AB
INC R0
MOV @R0,A
END









```

## OUTPUT
<img width="1692" height="782" alt="image" src="https://github.com/user-attachments/assets/691de811-a3b4-4443-a291-93fc05b4124a" />



## RESULT
Thus, the square of the given data is calculated using 8051 Keil.

# 8051 Cube  Program

## AIM
To write and execute an Assembly language program for finding the cube of a given data using 8051 microcontroller in Keil software.

## APPARATUS REQUIRED
- Personal computer
- Keil μVision IDE

## ALGORITHM
1. Enter the Assembly language program.
2. Provide the input value.
3. Execute the program.
4. The output cube value is stored in a memory location.

## PROGRAM
```
ORG 00H
MOV R0,#50H
MOV A,@R0
MOV B,A
MUL AB
MOV B,@R0
MUL AB
INC R0
MOV @R0,A
INC R0
MOOV @R0,B
END








```


## OUTPUT
![WhatsApp Image 2026-02-14 at 09 21 51](https://github.com/user-attachments/assets/ba275f00-7ee4-438e-b8ab-4ff69e523c11)


## RESULT
Thus, the cube of the given data is calculated using 8051 Keil.
