# Docx to Txt Converter

This Python script converts a `.docx` file to `.txt`, considering the presence of the Russian alphabet and discarding any images in the document. It uses the `python-docx` library to handle `.docx` files.

## Prerequisites

- Python 3.6 or later
- `python-docx` library

## Installation

1. Clone this repository or download the script file (`docx_to_txt.py`) to your local machine.

2. Install the required `python-docx` library by running the following command:

   ```bash
   pip install python-docx
   ```

## Usage

1. Place the `.docx` file you want to convert in the same directory as the `docx_to_txt.py` script.

2. Open the terminal (or command prompt) and navigate to the directory containing the script.

3. Run the following command to execute the script:

   ```bash
   python docx_to_txt.py
   ```

4. The script will prompt you to enter the name of the input `.docx` file.

5. After you provide the input file name, the script will convert it to `.txt` format, considering the Russian alphabet and discarding any images.

6. The resulting `.txt` file will be saved in the same directory as the input file.

7. Check the terminal output for the name of the output file.

## Example

Let's assume you have a file named `example.docx` that you want to convert to `.txt`. Follow these steps:

1. Place `example.docx` in the same directory as `docx_to_txt.py`.

2. Open the terminal and navigate to the directory containing the script.

3. Run the following command:

   ```bash
   python docx_to_txt.py
   ```

4. When prompted, enter `example.docx` as the input file name.

5. The script will convert `example.docx` to `example.txt`.

6. The resulting `.txt` file will be saved in the same directory.

7. The terminal output will indicate the completion of the conversion and display the name of the output file.

## Notes

- Make sure the input `.docx` file contains text in the utf-8 for accurate conversion.

- Any images present in the `.docx` file will be discarded in the resulting `.txt` file.

- The output `.txt` file will be encoded using UTF-8.

## License

This project is licensed under the [MIT License](LICENSE).
