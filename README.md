# Week 02 Class Project — Ohm's Law Calculator

## Purpose
This program calculates current using Ohm's Law. The user enters a voltage and resistance, and the program calculates the current.

## Input Format
Enter two numbers separated by a space:
- Voltage in volts
- Resistance in ohms

The resistance must be greater than zero.

## Example
Input: 12 4

Output: Current: 3 A

Invalid input: 12 0

Output: Invalid input

## Build
mkdir -p build
g++ -std=c++17 -Wall -Wextra -pedantic src/main.cpp -o build/app

## Run
./build/app

## Test
bash test.sh

## Limitations
The program only calculates current. It does not calculate voltage or resistance. It also rejects invalid numeric input and resistance values that are zero or negative.

## Debugging Reflection
I used the test files to check whether the program calculated current correctly and rejected invalid resistance values. Both tests passed when I ran test.sh in Ubuntu.

## AI Use
I used ChatGPT to help understand the assignment, set up the project files, and follow the Git and Ubuntu commands. I tested the program in Ubuntu to verify that it worked.
