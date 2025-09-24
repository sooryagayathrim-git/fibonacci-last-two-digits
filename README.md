# fibonacci-last-two-digits
A simple Python program to compute the last two digits of the Nth Fibonacci number.  Uses modulo arithmetic to efficiently calculate results for very large values of N.
This project computes the Nth Fibonacci number using a recursive approach and then finds its last two digits.

The Fibonacci sequence is defined as:
F(0) = 0
F(1) = 1
F(n) = F(n-1) + F(n-2), for n ≥ 2

Program workflow:
1. Reads an integer N as input.
2. Recursively computes the Nth Fibonacci number.
3. Prints the full Fibonacci number.
4. Extracts and prints the last two digits using modulo 100.

Note:
- This implementation is simple and easy to understand, but recursion is not efficient for very large N.
- For larger inputs, optimized methods (like dynamic programming or matrix exponentiation) are recommended.
