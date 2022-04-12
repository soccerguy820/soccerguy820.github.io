[Back to Portfolio](./)

Assembly Code and Verilog
===============

-   **Class:** CSCI 330 - Computer Architecture
-   **Grade:** A
-   **Language(s):** Assembly Code (.asm) and Verilog (.v)
-   **Source Code Repository:** [soccerguy820/csci-330](https://github.com/soccerguy820/csci-330)  
    (Please [email me](mailto:pesnow@csustudent.net?subject=GitHub%20Access) to request access.)

## Project description

This repository will consist of a couple assignments that utilized the languages known as Assembly machine code and Verilog. Each lab utilizes different languages to execute certain commands ranging from sorting out an assembly code executing certain commands to making gates with Verilog.

## How to compile and run the program

How to compile and run the project.

For Assembly:
```bash
cd ./[file name here]
nasm -felf64 [assembly code here] && gcc -no-pie -fPIC [name here].o && ./a.out
```

For Verilog:
```bash
cd ./[file name here]
iverilog *.v && ./a.out
```


## UI Design

Lab01.asm writes "Hello from C library" and then prints an the integer 2022 to the console using a C library.
Lab02.asm takes the sum of all the elements of array1 and array2 and prints the total sum.
Lab03.asm finds the sum of all the elements of the array using a loop and prints the sum.
Lab04.asm is assembly for the following:
 int multadd(int y) {
   int a;
   a = 23;
   return y * y + a;
 }
 int main() {
     printf("%ld\n", example(33);
 }
 
 Verilog lab01.v is writing the NAND gate and the verilog inputs.
 Verilog lab02.v is writing with multiple gates to form one model.
 Verilog lab03.v is similar to lab02.v but trying to form a bigger model.
 Verilog lab04 is writing NAND gates to form an SR Latch.
 Verilog lab05 is writing more NAND gates in combination with a SR Latch to form a Gated SR Latch.

![screenshot](images/lab01shot.JPG)  
Fig 1. The output(s) of lab01 assembly code.

![screenshot](images/lab02shot.JPG)  
Fig 2. The output(s) of lab02 assembly code.

![screenshot](images/lab03shot.JPG)  
Fig 3. The output(s) of lab03 assembly code.

![screenshot](images/lab04shot.JPG)  
Fig 4. The output(s) of lab04 assembly code.

![screenshot](images/vlab01shot.JPG)  
Fig 5. The output(s) of lab01 verilog inputs.

![screenshot](images/vlab02shot.JPG)  
Fig 6. The output(s) of lab02 verilog inputs.

![screenshot](images/vlab03shot.JPG)  
Fig 7. The output(s) of lab03 verilog inputs.

![screenshot](images/vlab04shot.JPG)  
Fig 8. The output(s) of lab04 verilog inputs.

![screenshot](images/vlab05shot.JPG)  
Fig 9. The output(s) of lab05 verilog inputs.


For more details see [GitHub Flavored Markdown](https://guides.github.com/features/mastering-markdown/).

[Back to Portfolio](./)
