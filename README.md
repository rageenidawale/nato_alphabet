# NATO Phonetic Alphabet Converter

## Overview
This Python script converts a user-inputted word into its NATO phonetic alphabet equivalent. It reads data from a CSV file and maps each letter to its corresponding phonetic code.

## Features
- ✅ Converts words into NATO phonetic alphabet
- ✅ Handles invalid inputs gracefully
- ✅ Uses recursion for reattempts if input is incorrect

## Requirements
- Python 3.x
- pandas library

You can install the required library using:
```bash
pip install pandas
```

## Installation & Usage
1. Clone or download the repository.
2. Ensure the `nato_phonetic_alphabet.csv` file is present in the same directory as the script.
3. Run the script:
   ```bash
   python nato_converter.py
   ```
4. Enter a word when prompted. The script will output the NATO phonetic spelling.
5. If an invalid character is entered, the script will ask for input again.

## File Structure
```
|-- nato_converter.py  # Main script
|-- nato_phonetic_alphabet.csv  # CSV file with phonetic alphabet data
```

## Example Usage
```
Enter a word: hello
['Hotel', 'Echo', 'Lima', 'Lima', 'Oscar']
```

If a non-alphabetic character is entered:
```
Enter a word: h3llo
Sorry! Only letters in the alphabet please.
Enter a word: hello
['Hotel', 'Echo', 'Lima', 'Lima', 'Oscar']
```

## Future Enhancements
- Add a graphical interface
- Support full sentences
- Integrate text-to-speech for pronunciation

Enjoy learning the NATO phonetic alphabet! 🎙️📖
