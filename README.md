# Square-Cube-of-a-number-using-8051
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
```asm
ORG 00H
MOV R0,#50H
MOV A,@R0
MOV B,A
MUL AB
INC R0
MOV @R0,A
END
```

### CALCULATION 
<img width="184" height="191" alt="image" src="https://github.com/user-attachments/assets/2bedc449-9b09-483c-85c9-26eab115017a" />

## OUTPUT

<img width="959" height="503" alt="Screenshot 2026-09-19 082734" src="https://github.com/user-attachments/assets/435e1b26-aa2c-4c70-b3db-1eeb745abc2b" />

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
```asm
ORG 0000H
MOV R0,#40H
MOV A,@R0
MOV B,A
MUL AB
MOV B,@R0
MUL AB
INC R0
MOV @R0,A
END
```

### CALCULATION 
<img width="159" height="214" alt="image" src="https://github.com/user-attachments/assets/30e994a2-dc6f-4207-9b36-989f983fefa2" />

## OUTPUT

<img width="959" height="503" alt="Screenshot 2026-09-19 085720" src="https://github.com/user-attachments/assets/4bca786b-408e-4d46-b28e-0d3f5da304e2" />

## RESULT
Thus, the cube of the given data is calculated using 8051 Keil.


