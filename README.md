# Text File Data Filtering

A Python project exploring text-file data processing, numerical analysis, and data visualization using NumPy and Matplotlib.

## Overview

This project organizes data-processing functions and explores relationships within datasets through numerical analysis and graphical representations.

## Technologies

- Python
- NumPy
- Matplotlib

## Features

- **Data Processing:** Processes data obtained from text files.
- **Numerical Analysis:** Explores best-fit calculations using NumPy.
- **Data Visualization:** Uses Matplotlib to generate graphs for examining data trends.

## Project Structure

The repository includes code related to best-fit analysis, reusable functions, and graph plotting.

## Getting Started

1. Clone or download this repository.
2. Install Python and the required dependencies.
3. Review the source files to identify the program entry point and required input format.
4. Run the appropriate Python script using your local Python environment.

Install the main dependencies with:

```bash
pip install numpy matplotlib
```
## Methods and Analysis

**Data Processing**
- Loaded student records from CSV files and converted values to appropriate numeric types where possible.
- Filtered records by selected student attributes and calculated average grades using FallGrade and WinterGrade.

**Visualization**
- Used Matplotlib to generate histograms for numerical attributes and bar charts for categorical attributes.

**Relationship Analysis**
- Grouped students by selected attributes and calculated average grades for each group.
- Applied NumPy polynomial fitting to model relationships between student attributes and average grades.

**Dataset**
- Number of records analyzed: 500+
- Tools: Python, NumPy, Matplotlib

## Future Improvements

- Add sample input files and example outputs.
- Document the expected input format and filtering criteria.
- Handle missing files and malformed input data.
- Include example graphs with descriptive titles and labelled axes.
- Add tests for data-processing functions.

## Notes

Refer to the source files for the current implementation and supported inputs.
