# compile-n-run (cnr)

`compile-n-run` is a command-line tool for Unix-like operating systems to automatically compile C/C++, Rust files and run them.

(This is a small project to get used to Bash programming, don't take it too seriously)

### Prerequisites

Before installing `compile-n-run`, ensure you have the following:
- A Linux or Unix-like operating system.
- The `gcc` and `g++` compiler installed for compiling C and C++ programs, respectively.
- The `rustc` compiler if you want to compile Rust

### Installation

Follow these steps to install `compile-n-run` on your system:

1. **Clone the Repository**

   Begin by cloning the `compile-n-run` repository to your local machine:

   ```bash
   git clone https://github.com/pythonHater170/compile-n-run.git
2. **Make the script executable**
   
   You need to make the file executable.
   In Linux you would do :
      ```bash
       chmod +x cnr
3. **Move the script to a PATH directory**
    ```bash
    sudo mv cnr /usr/local/bin
    
### Usage 
You are now ready to use `compile-n-run`!

To compile a C program :
    
    
    cnr your_program.c
Or a C++ program :
    
    
    cnr your_program.cpp
And you shall see your code appear in your terminal.
