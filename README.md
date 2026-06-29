# File Renaming Script
**Standardize filename in a directory with optional arguments for personalized formatting**

## Instalation:
Download the [source code](https://github.com/gindvd/Filename_Reformatter/archive/refs/heads/main.zip), and move to preferred directory

## How to use:
After downloading the source code, open a terminal, and navigate inside the source code folder.

Use pip to install PILLOW dependency
```batch
python -m pip install pillow
```

To run, call the file file_renamer.py file with python, and add the path to the directory with all the files to be renamed.
See example for command

### Base Functionality:
With no extra aguments, the script will parse through all files and replace any spaces or dashes with underscores.
All alpha characters will be lowercased

## Example:
** Without arguments: **
```batch
python file_renamer.py C:\Path\to\Folder
```

** With arguments: **
```batch
python file_renamer.py C:\Path\to\Folder -rp -c -r
```

## CLI Arguments:
** Add arguments after specified directory for personalized naming preferences **
| Args | Details |
|--------|----------|
| -rp --remove-punctuation | Removes all non-alphanumeric characters from a file name |
| -c --captitalize | Capitalizes the first character if every word in the files name |
| -r --resolution | Add resolution of image to end of files name |
