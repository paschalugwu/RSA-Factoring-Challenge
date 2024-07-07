# RSA Factoring Challenge

**AlgorithmScripting by Julien Barbier**

This project aims to tackle the RSA Factoring Challenge, a fascinating endeavor in algorithmic problem-solving. The challenge involves factorizing numbers into products of two smaller numbers, with a twist in the advanced version where the factors must be prime.

## Tasks

### Task 0: Factorize all the things! #advanced

- Factorize as many numbers as possible into a product of two smaller numbers: the task requires you to write a python script called `factors` that reads numbers from a file and factors them into a product of two smaller numbers. The script should follow certain requirements, such as reading numbers from a file, outputting the factorization in the format `n=p*q`, handling numbers greater than 1, running without any dependencies, and completing within a time limit of 5 seconds.

**Usage:**
bash
factors <file>
    <file> is a file containing natural numbers to factor.
    One number per line.
    All lines will be valid natural numbers greater than 1.
    No empty lines or spaces before/after the valid number.
    The file will always end with a new line.

Output format: n=p*q
    One factorization per line.
    p and q don’t have to be prime numbers.

Additional Guidelines:

    Work on the numbers in the file in the order of your choice.
    Your program should run without any dependency.
    Time limit: 5 seconds.

### Task 1: RSA Factoring Challenge #advanced

RSA Laboratories states that for each RSA number n, there exist prime numbers p and q such that n = p × q. The task is to find these two primes, given only n.

This task is an extension of Task 0 with the following differences:

    p and q are always prime numbers.
    There is only one number in the files.

How far can you go in less than 5 seconds?

## GitHub Repository

* Repository Name: RSA-Factoring-Challenge
* Files: factors, rsa
