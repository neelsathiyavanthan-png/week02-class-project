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
My first commands failed because I was in PowerShell instead of the Ubuntu
terminal, so g++ and nano were not found. My first commit was refused until
I set my name and email with git config, and my first push failed until I
used a personal access token instead of my password. The repo also had no
main branch because it started empty, so I pushed my feature branch to
GitHub as main before opening the pull request.
## AI-use disclosure
I used Claude to walk me through the steps, explain errors, and I typed the commands myself
