# ASIC DESIGN CLASS

## LAB 1 - Create a C program which will caluculate sum from 1 to n, And compile it using GCC compilier

1)- Write a C program in text editor as sum 1 to n  

Following image will show about the image of the C program 

![image1lab1](https://github.com/user-attachments/assets/bdd30330-f82b-488c-ba6f-2216d53d4d38)

2- Compile the code using GCC compiler and run the code to see the output

Image will show about the commands used and output of sum1ton

![image2lab1](https://github.com/user-attachments/assets/c247d982-e748-4ed9-9ed5-bcae0e249202)

## LAB 2 - Compiling Lab1(sum 1 to n) C program with RISCV Compiler

1) We will run lab 1 program using RISCV Gcc compiler


![image1lab2](https://github.com/user-attachments/assets/44bf2daf-6c83-4f52-86ad-afb83a292f7c)

2)In a new tab we will check the assembly code for C program we Run

Here we went to the "main"  when I calculted using calculator got (35)dec and (23)hex 

![img3lab2](https://github.com/user-attachments/assets/d5ab9bb2-d94f-4b70-8e69-0277e7e2aabd)

4) Hence now we will use Ofast on the RISCV compiler and we will use the same C code 
image which describes about the commands


![img5lab2](https://github.com/user-attachments/assets/816cc5e4-374e-4de9-95da-b0ec6eb3158c)

5) We got 12 instructions(byte adressing) in the main section (adress 100bo)

![img6lab2](https://github.com/user-attachments/assets/3a3c8018-28fa-4629-b4c8-d561402dbbbb)

6) RISCV compilation output
 Code Compilation using RISC-V GCC compiler with a different optimization flag (Ofast)
we will compile the code with compiler flag set as -Ofast and then we will check the assembly code again
![lab 2 8](https://github.com/user-attachments/assets/9d590d74-02ef-4005-887b-16107e7326a1)
![lab 2 9](https://github.com/user-attachments/assets/f882ce66-3843-4c09-81e2-ae3fef84b769)



