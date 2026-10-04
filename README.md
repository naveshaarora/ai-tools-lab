# AI Tools Lab

A Python project containing core sorting algorithms and helpful utility functions, built utilizing version control workflows.

## Features
* **Bubble sort implementation with an early-exit optimisation** (`sorting.py`)
* **Utility functions with full docstrings** (`utils.py`):
    * `is_palindrome(s)`: checks if a string is a palindrome, ignoring case, spaces and punctuation
    * `count_words(text)`: counts the words in a text
    * `celsius_to_fahrenheit(c)`: converts Celsius to Fahrenheit

## Installation
1. Make sure Python 3.8 or higher is installed:
```bash
python --version
```

2. Clone the repository:
```bash
git clone https://github.com
```

3. Move into the project folder:
```bash
cd ai-tools-lab
```
No extra libraries are required.

## Usage

### Sorting
```python
from sorting import bubble_sort

numbers = [64, 34, 25, 12, 22, 11, 90]
print(bubble_sort(numbers))
# Output: [11, 12, 22, 25, 34, 64, 90]
```

### Utility functions
```python
from utils import is_palindrome, count_words, celsius_to_fahrenheit

print(is_palindrome("A man, a plan, a canal: Panama")) # Output: True
print(count_words("Hello AI Tools Lab"))               # Output: 4
print(celsius_to_fahrenheit(100))                     # Output: 212.0
```

You can also run each file directly:
```bash
python sorting.py
python utils.py
```

## Project Structure
```text
ai-tools-lab/
├── README.md
├── hello.py
├── sorting.py
└── utils.py
```

## Contributors
* naveshaarora

## License
This project is licensed under the MIT License - see the LICENSE file for details.
