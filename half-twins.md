# m3hd1's half-twins

## Decompiler: Ghidra

Upon decompilation we find only the main function to be of any use. The main function takes two string argumants and runs a lot of checks on them. So let's proceed check by check through to the solution.

### Check-1

It checks whether we are providing the required two arguments or not.

### Check-2 and 3

These check whether the length of our strings are greater than 7 or not. Applies for both the strings.

### Check-4

This checks whether the length of the strings are same or not.

### Check-5

This checks whether the strings are of even length or not.

### Check-6

This checks whether the first half of both the strings is same or not.

## Solution

Based upon all these checks, the solution which matches the answer comprises of 2 strings in the format:

1. Greater than 7 characters long.
2. Has even number of characters.
3. The first half of both the strings should be identical.
