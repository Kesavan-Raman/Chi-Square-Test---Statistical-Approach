# Chi-Square Test - Statistical Approach

This is a simple Python script that demonstrates how to perform a chi-square test using a statistical approach. The script takes two input CSV files: one containing the observed frequencies and one containing the expected frequencies. It then calculates the chi-square statistic and the corresponding p-value, and outputs the results to the console.

## Requirements

- Python 3.x
- NumPy
- Pandas

## Usage

1. Clone this repository or download the `chisquare.py` file.
2. Install the required packages using pip: `pip install numpy pandas`
3. Prepare two CSV files with the observed and expected frequencies. The CSV files should have a single column each, and the same number of rows.
4. Run the script with the following command: `python chisquare.py path/to/observed.csv path/to/expected.csv`

Example:
python chisquare.py data/observed.csv data/expected.csv


## License

This code is released under the MIT License. See the `LICENSE` file for more information.

## Acknowledgments

This script was inspired by the following resources:

- [Chi-squared Test for Independence in Python](https://towardsdatascience.com/chi-squared-test-for-independence-in-python-with-example-from-the-fbi-crime-data-616cb4a7a890) by Will Koehrsen
- [Using Chi-Square Statistic in Research](https://www.scribbr.com/statistics/chi-square-test/) by Scribbr
