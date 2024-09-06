# countries_by_area.py

## How Many Countries Fit into Another?

This project provides a Python tool to calculate how many times one country fits into another based on their total land area. Using a Wikipedia dataset, the user can select two countries and receive a result displaying how many times the first country can fit inside the second.

# Features

Select Two Countries: Use dropdowns to select two countries for comparison.
Accurate Calculations: Get results to four decimal places.
Sorting by Name: The countries are sorted alphabetically to make selection easier.
Real-World Data: The data is pulled from Wikipedia’s "List of countries and dependencies by area." from the following link:

https://en.wikipedia.org/wiki/List_of_countries_and_dependencies_by_area

The dataset is sourced from Wikipedia's list of countries by area, ensuring accurate, real-world calculations. It includes each country's total area (in square kilometers). You can also access the dataset from the GitHub repository:

(https://github.com/Barryal82/countries_by_area.py/blob/main/countries_by_area.csv)

# Setup Instructions

*Prerequisites*
Python 3.x installed on your machine.
Libraries: Install required libraries with pip install pandas.

### Installation
1. Clone the repository from GitHub:
   ```bash
   git clone https://github.com/barryal82/countries-by-area.git
   cd countries-by-area
   ```

2. Install the necessary dependencies:
   ```bash
   pip install pandas
   ```

### Usage

1. Run the script:
   ```bash
   python countries_by_area.py
   ```

2. Select two countries from the dropdowns.

3. The program will display how many times one country can fit into another.

### Example Calculation
If you select **Qatar** and **Spain**, the program will tell you how often Qatar fits into Spain based on its total land area.

## Contributions
Feel free to fork out this project and submit pull requests. Contributions to improving the functionality or accuracy of this tool are welcome.

## License
This project is licensed under the MIT License - see the https://github.com/Barryal82/countries_by_area.py/blob/main/LICENSE file for details.

## Author
- **Barry** - Initial work
