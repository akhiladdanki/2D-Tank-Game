# Thread-Racer Description

Create a group of threads and then try to coax them into producing as many race conditions as possible. First, your program should declare a single shared global integer with initial value 0. Then the program will spawn off 10 threads each of which increments the shared variable by 10, waits for all threads to complete and then prints out the final value of the global counter. When all threads execute sequentially, then the final value of the counter will be 100. 


# Compile Instructions

Navigate to file location using command line. Open folder that contains test and main.c. Type in ./test in order to run the program.


