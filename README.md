# DOCX Formatter

This Python script reformats a `.docx` document by applying specific styles to text that matches certain patterns.

## Features
- **Bold Text**: Any text enclosed within double asterisks (`**`) will be converted to bold.
- **Headings**: Lines starting with `###` will be converted to headings with specific font sizes and bold styling.

## Dependencies

- `python-docx`: This Python library allows manipulation of `.docx` files.
- `re`: This is a built-in Python module for regular expressions.

To install `python-docx`, you can use pip:
```bash
pip install python-docx
```

## Usage

- Update the `input_filename` variable with the path of your `.docx` file to be processed.
- Update the `output_filename` variable with the desired name of the output file.
- Run the script.
