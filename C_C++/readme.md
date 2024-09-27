# C Compiler on ubuntu using terminals

    1. open Terminal : Crtl +Alt + T
    2. Update package list always
    
    ```bash
        sudo apt update
    ```

    3.install GCC (GNU Compiler Collection) : 

    ```bash
        sudo apt isntall build-essential
    ```
    
    this command install necessary software devolopment tools ,such as make.

    4.check the installation : after install with command
    ```bash
        gcc --version
    ```

    1. create example C file with command 
   ```bash
        nano hello.c
   ```

   and then input code:

   ```c
    #include <stdio.h>

    int main() {
        printf("Hello World\n");
        return 0 ;

    }
   ```

   enter Crtl + X ,  Y and Enter for Save File

   6.Compiler C program :Using this command
   ```bash
        gcc hello.c -o hello
   ```

    7.run Program :With command
    ```bash
        ./hello
    ```