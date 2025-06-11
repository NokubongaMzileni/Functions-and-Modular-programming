# Age-Based Scholarship Eligibility Checker

This Python script calculates the average age from a list of inputs, determines scholarship eligibility based on age (18+), and visualizes the results with a bar chart.

## Features

- Calculates average age from user input.
- Determines eligibility (18 years and older).
- Filters and displays eligible ages.
- Visualizes age eligibility using a bar graph (green = eligible, red = not eligible).

## Installation

### Prerequisites

- [Python 3.x](https://www.python.org/downloads/)
- [Visual Studio Code](https://code.visualstudio.com/)

### Steps

1. **Install VS Code**  
   Download and install from: [https://code.visualstudio.com/](https://code.visualstudio.com/)

2. **Install Python Extension in VS Code**  
   Open VS Code → Extensions (`Ctrl+Shift+X`) → Search `Python` → Click Install.

3. **Run the Script**  
   - Open VS Code.
   - Create a new `.py` file and paste the script.
   - Open terminal (`Ctrl+``).
   - Install required package:
     ```bash
     pip install matplotlib
     ```
   - Run the script:
     ```bash
     python filename.py
     ```

## Usage

When prompted, enter ages separated by commas (e.g., `17, 18, 21, 15`).  
The script will output:

- Average age
- Eligibility status for each age
- List of eligible ages
- A bar chart visualizing the data

## License

This project is open-source and free to use.
