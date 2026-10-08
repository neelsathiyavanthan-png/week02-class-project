# Ohm's Law Calculator

## Purpose
Reads a voltage and a resistance and prints the current, using I = V / R.

## Input format
Two numbers separated by a space: voltage in volts, then resistance in ohms.
Example: 12 4

## Build and run
    mkdir -p build
    g++ -std=c++17 -Wall -Wextra -pedantic src/main.cpp -o build/app
    ./build/app

## Test
    bash test.sh

## Example output
Input: 12 4   Output: Current: 3 A
Input: 12 0   Output: Invalid input

## Limitations
- Handles one calculation per run.
- Rejects zero or negative resistance and non-numeric input.
- Only works in volts and ohms.

## Debugging reflection
[2 to 3 sentences on what went wrong and how you fixed it, e.g. running
commands in PowerShell instead of Ubuntu, git not knowing your name, the
token login, or the missing main branch.]

## AI-use disclosure
[One sentence on how you used AI, e.g. "I used Claude to walk me through
the steps and explain errors; I typed the commands myself."]

