
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
MOV A,P0
MOV R0,A
MOV B,R0
MUL AB
MOV P2,A
END
```

## OUTPUT
<img width="1480" height="739" alt="image" src="https://github.com/user-attachments/assets/e4af1ecf-1585-4042-a8a1-a54246e6c52a" />


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
MOV A, P0     
MOV R0, A     
MOV B, A      
MUL AB        
MOV R1, A    
MOV A, R1     
MOV B, R0     
MUL AB        
MOV P2, A   
END
```


## OUTPUT
<img width="1387" height="674" alt="image" src="https://github.com/user-attachments/assets/d8e2c51f-9a0e-4c92-ae05-5fa33310743b" />

## RESULT
Thus, the cube of the given data is calculated using 8051 Keil.
