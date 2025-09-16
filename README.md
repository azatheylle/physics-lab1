# Physics Lab 1 - T4 Temperature Calculator

This repository contains a web-based calculator for solving the thermal equilibrium physics problem using the formula:

**T4 = ((m1 × c1 × (T2 - T1) + m3 × c3 × (T6 - T5)) / (m2 × c2)) + T3**

## Features

- **Interactive Calculator**: Easy-to-use web interface similar to a Google Sheet
- **Real-time Calculation**: Enter values and get instant results
- **Detailed Breakdown**: Shows step-by-step calculation process
- **Input Validation**: Prevents errors and guides users
- **Clear Function**: Reset all fields with one click

## How to Use

1. Open `physics-calculator.html` in your web browser
2. Enter the required values:
   - **Mass values**: m1, m2, m3 (in kg)
   - **Specific heat values**: c1, c2, c3 (in J/kg·K)
   - **Temperature values**: T1, T2, T3, T5, T6 (in °C or K)
3. Click "Calculate T4" to get the result
4. Use "Clear All Fields" to reset and start over

## Formula Explanation

The formula calculates the final temperature T4 in a thermal equilibrium problem where:
- m1, m2, m3 are masses of different materials
- c1, c2, c3 are specific heat capacities
- T1-T6 are temperatures at different states

## File Structure

- `physics-calculator.html` - The main calculator interface
- `README.md` - This documentation file

## Running the Calculator

### Option 1: Direct File Opening
Simply double-click on `physics-calculator.html` and it will open in your default browser.

### Option 2: Local Web Server
For better compatibility, you can run a local web server:

```bash
# Using Python 3
python3 -m http.server 8000

# Using Python 2
python -m SimpleHTTPServer 8000

# Using Node.js (if you have http-server installed)
http-server

# Using PHP
php -S localhost:8000
```

Then navigate to `http://localhost:8000/physics-calculator.html` in your browser.

## Screenshot

![Physics Calculator Demo](https://github.com/user-attachments/assets/9c17bd75-f3ac-402b-9d95-f9f6f6f9748c)

## Example Calculation

Using the sample values shown in the screenshot:
- m1=2, c1=4186, T1=20, T2=80
- m2=1.5, c2=387, T3=25
- m3=1, c3=900, T5=15, T6=50

Result: **T4 = 944.586563**