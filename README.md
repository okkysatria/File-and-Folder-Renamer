# File and Folder Renamer

## Overview

The **File and Folder Renamer** is a Python GUI application designed to simplify the process of batch renaming files and folders. With features like undo and redo, sorting, and filtering, this tool provides a user-friendly interface for managing and organizing items in a directory.

## Features

- **Batch Rename**: Easily rename multiple files or folders at once.
- **Undo and Redo**: Revert or repeat recent renaming actions with ease.
- **Filter and Sort**: Filter items based on text and sort them by name or date modified.
- **Copy to Clipboard**: Copy the list of items to the clipboard for easy sharing.
- **Save to Note**: Save the list of items to a text file for record-keeping.

## How to Use

1. **Select Directory**: Click the "Select Directory" button to choose the directory containing the files or folders you want to rename.
2. **Choose Scan Mode**: Use the radio buttons to select whether to scan for files or folders.
3. **Sort Items**: Use the "Sort By" dropdown menu to sort items by Name or Date Modified.
4. **Filter Items**: Enter a filter text in the "Filter" entry box and click "Apply Filter" to filter items.
5. **Copy or Save Item List**: Use the "Copy to Clipboard" button to copy the list of items or "Save to Note" to save it to a text file.
6. **Batch Rename**: Enter new names in the "New Names" text area and click "Batch Rename" to rename all selected items.
7. **Undo and Redo**: Click "Undo" to revert the last change or "Redo" to reapply a change that was undone.

## Installation

Ensure you have Python 3.x installed. To install the required dependencies, use the provided `requirements.txt`:

```bash
pip install -r requirements.txt
```

## Running the Application

Run the Python script to launch the GUI application:

```bash
python file_and_folder_renamer.py
```

or just run EXE file
