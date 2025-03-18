# Temperature Converter in C

## Overview
This C program converts temperatures between **Celsius** and **Fahrenheit**.

## How It Works
1. The user selects an option:
   - Convert Celsius to Fahrenheit
   - Convert Fahrenheit to Celsius
2. The user enters a temperature value.
3. The program calculates and displays the converted temperature.

## Compilation & Usage

### Requirements
- A C compiler (e.g., GCC, Clang, MSVC)

### Compiling the Program
```sh
gcc temperature_converter.c -o temperature_converter
```

### Running the Program
```sh
./temperature_converter
```

### Expected Output
```
Temperature Converter
1. Celsius to Fahrenheit
2. Fahrenheit to Celsius
Choose an option: 1
Enter temperature in Celsius: 25
25.00 Celsius = 77.00 Fahrenheit
```

## Future Enhancements
- Support **Kelvin** conversions.
- Implement a **GUI** for better user interaction.
- Allow **continuous conversions** without restarting the program.