Interactive Personal Data Collector
A Python script that collects basic personal information from the user via terminal input, then displays it back along with each variable's data type and memory address.
What it does

It then prints out each value along with its Python type() and memory location using id(), and estimates the user's approximate birth year based on the current year and their age.
# Code Overview

The script performs the following core actions:

1. User Input Collection:
   * `Name`: Read as a string (`str`)
   * `Age`: Converted to an integer (`int`)
   * `Height`: Converted to a floating-point number (`float`)
   * `Favourite Number`: Converted to an integer (`int`)

2. Data & Memory Analysis:
   * Displays variable values alongside their data types and unique memory IDs.

3. Dynamic Computation:
   * Calculates estimated birth year using the current year standard: `2026 - Age`.

