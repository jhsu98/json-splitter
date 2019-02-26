# json-splitter
A simple command line tool for splitting large JSON files into smaller files. Python 3+ is required for this script to work.

## Table of Contents

- [json-splitter](#json-splitter)
  - [Table of Contents](#table-of-contents)
  - [Installation](#installation)
  - [Usage](#usage)
  - [Support](#support)

## Installation
This script requires Python to be installed on the local machine. Please visit [Python.org](https://www.python.org/) to install or type `python3 --version` to verify it is already installed.

Once Python is installed, clone the project or download the [ZIP file](https://github.com/jhsu98/json-splitter/archive/master.zip) and extract manually.

## Usage
Place a JSON file within the same directory as the script. The JSON file must be an Array of Objects or Multidimensional Array.

Navigate to the directory where the script exists and begin by typing `python3 json-splitter.py`

Enter the name of the JSON file (include the extension) when prompted, then enter the maximum number of MB for each file.

The script will complete and equally split the JSON file into the appropriate number of files to stay under the maximum size.

## Support
Please [open an issue](https://github.com/jhsu98/json-splitter/issues/new) for support.