
# FIS Data Rearranger

## Description
`fis_data` is a Python script designed to manage and reformat data derived from FIS analysis. Specifically, it targets data stored in an Excel sheet named "Normalised." This script enables users to efficiently extract and rearrange this data, facilitating its export into a new Excel file tailored for subsequent analyses. This tool is especially beneficial for conducting FIS Analysis within our research group, streamlining the workflow and improving data handling efficiency.

## Installation
To install `fis_data`, you can use pip:
```bash
pip install fis_data
```
Ensure that you have `Python 3.6` or later installed.

## Usage
Once installed, you can use the `rearrange_fis_data` command-line tool as follows:
```bash
rearrange_fis_data <input_filepath> <output_filepath> [--sheet_name SHEET_NAME]
```
- `input_filepath`: Path to the input Excel file.
- `output_filepath`: Path to save the rearranged Excel file.
- `--sheet_name`: (Optional) Name of the sheet to be processed. Defaults to "Normalised".

### Example
```bash
rearrange_fis_data input_data.xlsx rearranged_data.xlsx
```

## Development
To contribute to `fis_data`, clone the repository:
```bash
git clone https://github.com/NEbrahimi/fis_data.git
```
Install the development dependencies:
```bash
pip install -r requirements.txt
```
Make your improvements and submit a pull request.

## License
This project is licensed under the MIT License. See the `LICENSE` file for more details.

