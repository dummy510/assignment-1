# Text Analysis Tool

A modular Python program that analyzes text input from users, calculating statistics and creating visualizations of the results.

## 📋 Overview

This text analysis tool takes user input text and provides detailed statistics and visualizations, including:
- Character count
- Word count
- Sentence count
- Average word length
- Word frequency analysis
- Letter frequency analysis
- Text composition (letters, spaces, punctuation)

The program features a clean, modular design with robust error handling and can create various visualizations of the analysis results.

## ✨ Features

- **Modular Design**: Clean separation of concerns with specific functions for different aspects of text analysis
- **Robust Error Handling**: Gracefully handles empty input, input with only punctuation, and other edge cases
- **Intuitive Interface**: Console-based menu system using pyinputplus for input validation
- **Comprehensive Analysis**: Multiple metrics and statistics for text analysis
- **Data Visualization**: Uses matplotlib to create visual representations of the results
- **Input Validation**: Provides helpful warnings and recommendations for improving input

## 🔧 Requirements

- Python 3.6+
- Required libraries:
  - matplotlib
  - pyinputplus
  - collections (standard library)
  - re (standard library)

## 📦 Installation

1. Clone the repository:
```bash
git clone https://github.com/dummy510/assignment-1
cd text-analysis-tool
```

2. Install the required dependencies:
```bash
pip install matplotlib pyinputplus
```

## 🚀 Usage

Run the main program:
```bash
python text_analysis_tool.py
```

The program will present a menu with the following options:
1. Enter text for analysis
2. Visualize results
3. Exit

After analyzing text, you can choose from various visualization options:
1. Word frequency bar chart
2. Letter frequency bar chart
3. Text composition pie chart

## 📊 Example

```
Welcome to the Text Analysis Tool!

=== Main Menu ===
1. Enter text for analysis
2. Visualize results
3. Exit
Enter your choice (1-3): 1

=== Text Input ===
Enter your text for analysis: The quick brown fox jumps over the lazy dog.

=== Text Analysis Results ===
Character count: 44
Word count: 9
Sentence count: 1
Average word length: 3.89 characters

Top 5 most frequent words:
  the: 2
  quick: 1
  brown: 1
  fox: 1
  jumps: 1

Top 5 most frequent letters:
  o: 4
  e: 3
  h: 2
  t: 2
  r: 2
```

## 🧪 Testing

The repository includes several test modules:
- `text_analysis_test_cases.py`: Unit tests for individual functions
- `manual_tests.py`: Manual test cases covering various input scenarios
- `integration_test.py`: End-to-end testing of the complete program flow
- `test_specific_cases.py`: Tests for specific edge cases

Run the unit tests with:
```bash
python text_analysis_test_cases.py
```

## 📐 Project Structure

```
text-analysis-tool/
├── text_analysis_tool.py      # Main program
├── test_specific_cases.py     # Edge case testing
├── input_validator.py         # Input validation module
├── text_analysis_test_cases.py # Unit tests
├── manual_tests.py            # Manual test cases
├── integration_test.py        # Integration tests
└── README.md                  # This file
```

## 📝 Code Structure

The code follows a modular design with the following key functions:

- `main()`: Main program flow and menu handling
- `get_user_text()`: Gets text input from the user
- `analyze_text()`: Orchestrates the text analysis process
- `get_statistics()`: Calculates basic text statistics
- `get_word_frequencies()`: Analyzes word frequency distribution
- `get_letter_frequencies()`: Analyzes letter frequency distribution
- `get_text_composition()`: Calculates text composition statistics
- `display_results()`: Shows analysis results to the user
- `create_visualizations()`: Creates and displays visualizations
- `visualize_frequencies()`: Generic function for frequency visualizations
- `visualize_pie_chart()`: Generic function for pie chart creation
- `validate_text_input()`: Comprehensive input validation

## 🎓 Assignment Requirements Satisfied

- **Modular Design**: Program is broken into logical functions and modules
- **Python Fundamentals**: Demonstrates understanding of sequences, selection, repetition, and basic data types
- **Library Integration**: Effectively uses collections, matplotlib, and pyinputplus
- **User Interface**: Creates an intuitive console-based menu system
- **Documentation**: Includes appropriate code comments and documentation

