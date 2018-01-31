# Sieve-of-Eranthoses-C
The Sieve of Eranthoses algorithm is a method to find prime numers by "knocking off" multiplicities 
of numbers up until a user specified N, where "N" is some positive integer between 1 and 32,000,000.
This particular instance is written in the C programming language, and utilizes an array of unsigned
integers to be considered as an array of booleans, where the index of each bit translates to an
integer. Any multiplication of numbers from 1 to the square root of N is set to be false, since it 
cannot be considered a prime.

To compile:

  gcc -g -o main.c
  gcc -g -o primes.c
  gcc -g -o main main.o primes.o
  
To run:
  
  ./main N
  
