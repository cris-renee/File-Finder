# File-Finder
# File Finder Utility

A user-friendly graphical application for searching files on your computer.

## Features

- Search by file name patterns (e.g., *.txt, *.pdf)
- Browse folders easily with a directory picker
- Sort results by name, date, or size
- Clear and intuitive interface
- Shows file sizes in human-readable format
- Real-time search progress updates

## Installation

### Option 1: Run from Source

1. Make sure you have Python 3.8 or later installed
2. Install required packages:
```bash
pip install rich pyinstaller
```
3. Run the application:
```bash
python file_finder_gui.py
```

### Option 2: Create Standalone Executable

1. Install Python 3.8 or later
2. Install required packages:
```bash
pip install rich pyinstaller
```
3. Build the executable:
```bash
python build.py
```
4. Find the executable in the `dist` folder:
   - Windows: `FileFinder.exe`
   - Mac/Linux: `FileFinder`

## Usage

1. Launch the application by double-clicking the executable
2. Enter a search pattern (e.g., *.txt for text files)
3. Choose a folder to search in using the "Browse" button
4. Select how to sort the results (by name, date, or size)
5. Click "Search" to start searching
6. Results will appear in the table below
7. Click column headers to sort results

## Tips

- Use wildcards in search patterns:
  - `*` matches any characters
  - `?` matches any single character
  - Examples:
    - `*.txt` finds all text files
    - `doc*.pdf` finds PDF files starting with "doc"
    - `report???.xlsx` finds Excel files starting with "report" followed by any 3 characters

## Troubleshooting

If you encounter any issues:
1. Make sure you have the latest version of Python installed
2. Try reinstalling the required packages
3. Check if you have proper permissions for the folders you're searching in

## License

This project is open source and free to use.
