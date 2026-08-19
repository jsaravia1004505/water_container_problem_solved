# Trapped Rainwater Calculator

An algorithm implementation that calculates the total units of rainwater trapped between stacked blocks represented by an array of positive integers.

## 🌧️ Problem Description

Given an array of positive integers where each integer represents the height of stacked block columns, the program determines how much water remains trapped between them after raining. It assumes an impermeable ground at the bottom that retains all trapped water.

### Example

Given the array `[4, 0, 3, 6, 1, 3]`:

        ⏹
        ⏹
  ⏹💧💧⏹
  ⏹💧⏹⏹💧⏹
  ⏹💧⏹⏹💧⏹
  ⏹💧⏹⏹⏹⏹

* ⏹ represents a block unit
* 💧 represents a trapped water unit

Total trapped water: 7 units

## 🚀 Getting Started

### Prerequisites

* Any standard C compiler (GCC, Clang, or MSVC)

### Compilation and Execution

1. Clone the repository:
   git clone https://github.com/your-username/trapped-rainwater.git
   cd trapped-rainwater

2. Compile the program:
   gcc main.c -o rainwater

3. Run the executable:
   ./rainwater

## 🛠️ Algorithm Approach

* Calculates trapped water per column using boundary checks.
* Time Complexity: O(n)
* Space Complexity: O(1)

## 📄 License

This project is licensed under the MIT License - see the LICENSE file for details.
