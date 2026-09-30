# CodeAlpha_TaskAutomation

## Project Description

This project is a simple task automation script developed using Python.

The script automatically identifies JPG and JPEG image files from a source folder and moves them into a separate destination folder.

## Features

* Automatically detects JPG and JPEG files
* Creates the destination folder automatically
* Moves image files using Python
* Ignores other file types
* Displays the number of files moved
* Simple and easy to use

## Technologies Used

* Python
* OS module
* Shutil module

## Project Structure

```text
CodeAlpha_TaskAutomation/
│
├── automation.py
└── README.md
```

For local testing:

```text
CodeAlpha_TaskAutomation/
│
├── automation.py
├── MyFiles/
└── JPG_Files/
```

## How to Run

1. Install Python.
2. Open the project folder in VS Code.
3. Create a folder named `MyFiles`.
4. Add JPG/JPEG files to the `MyFiles` folder.
5. Open the VS Code terminal.
6. Run:

```bash
python automation.py
```

The script will automatically move JPG/JPEG files from `MyFiles` to `JPG_Files`.

## Example

Before running:

```text
MyFiles/
├── photo1.jpg
├── photo2.jpg
├── document.pdf
└── notes.txt
```

After running:

```text
JPG_Files/
├── photo1.jpg
└── photo2.jpg
```

The PDF and TXT files remain in the original folder.

## Author

Anil Kushwaha

## Internship

CodeAlpha Python Programming Internship
