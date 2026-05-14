# IJC – Project 1

First assignment for the IJC course focused on bit arrays, prime number generation, and comment removal in C source files.

## Features

- Bitset implementation using macros and inline functions
- Sieve of Eratosthenes for prime number generation
- Comment remover using a finite-state machine
- Dynamic and static memory handling
- Error handling module

## Build

```bash
make
````

## Run

```bash
make run
```

## Programs

* `primes` – computes prime numbers using the Sieve of Eratosthenes
* `primes-i` – inline-function variant
* `no-comment` – removes comments from C source files

## Compilation

Tested with:

```bash
gcc -std=c11 -Wall -Wextra -pedantic
```
