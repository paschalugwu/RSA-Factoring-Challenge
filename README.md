# RSA Factoring Challenge

**AlgorithmScripting by Julien Barbier**

This project aims to tackle the RSA Factoring Challenge, a fascinating endeavor in algorithmic problem-solving. The challenge involves factorizing numbers into products of two smaller numbers, with a twist in the advanced version where the factors must be prime.

## Project Details

* **Weight:** 1
* **Project Start:** Nov 13, 2023, 6:00 AM
* **Project End:** Nov 27, 2023, 6:00 AM
* **Checker Release:** Nov 16, 2023, 6:00 PM
* **Auto Review:** Will be launched at the deadline

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

Example:
```bash
$ cat tests/test00
4
12
34
...
$ time ./factors tests/test00
4=2*2
12=6*2
34=17*2
...
real    0m0.009s
user    0m0.008s
sys     0m0.001s
```

### Task 1: RSA Factoring Challenge #advanced

RSA Laboratories states that for each RSA number n, there exist prime numbers p and q such that n = p × q. The task is to find these two primes, given only n.

This task is an extension of Task 0 with the following differences:

    p and q are always prime numbers.
    There is only one number in the files.

How far can you go in less than 5 seconds?

Example:
```bash
$ cat tests/rsa-1
6
$ ./rsa tests/rsa-1
6=3*2
...
$ cat tests/rsa-16
2497885147362973
$ ./rsa tests/rsa-16
2497885147362973=49979141*49978553
```

## GitHub Repository

* Repository Name: RSA-Factoring-Challenge
* Files: factors, rsa
