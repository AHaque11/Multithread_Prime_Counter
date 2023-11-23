# Multithread_Prime_Counter

This C program uses multiple threads to count the prime numbers within a given range. The program takes user input of the number range (low, high) and the number of threads. 

The given number range is evenly divided among the number of threads. Each thread counts and prints the prime numbers within its assigned section, and the total count is added and displayed at the end. An example of the program execution is included in the repository.

The program usage is: 

                      gcc -o primeCounter primeCounter.c  
                      ./primeCounter [low] [high] [number of threads]
