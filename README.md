
# DoctorFiles

![DoctorFiles Logo](https://img.shields.io/badge/DoctorFiles-Automated%20File%20Sorter-blueviolet)

## Overview
DoctorFiles is an **automated file sorter** inspired by the iconic "Doctor Who" series. Designed to bring order to chaos, this Python-based tool automatically organizes files in a directory into folders based on their extensions, making file management easier and more efficient. It also cleans up empty folders after sorting, ensuring a tidy workspace.

---

## Features

- Automatically sorts files by extension into respective folders (e.g., pdf, jpg, mp4)
- Creates new folders on-the-fly if they don’t exist
- Handles files without extensions gracefully by placing them in a separate folder
- Deletes empty folders after sorting for a clean directory
- Simple setup and usage, ideal for Windows File Explorer environments

---

## Installation

1. Clone or download the repository:
   ```
   git clone https://github.com/nipungoel24/DoctorFiles.git
   ```
2. Navigate to the project folder:
   ```
   cd DoctorFiles
   ```
3. Ensure you have Python 3.x installed.
4. (Optional) Create and activate a virtual environment:
   ```
   python -m venv env
   source env/bin/activate         # On macOS/Linux
   .\env\Scripts\activate          # On Windows
   ```
5. No additional dependencies required beyond standard Python libraries.

---

## Usage

1. Specify the directory path containing files to be sorted by editing the `path` variable in the script (`Automatic_File_Sorter_in_File_Explorer.ipynb` or `.py`):

   ```
   path = r"your-directory-path"
   ```

2. Run the script:
   ```
   python automatic_file_sorter.py
   ```

3. The script will organize files into folders by their file extensions and remove any empty folders.

---

## Example

Directory before sorting:
```
Files/
├── report.pdf
├── photo.jpg
├── video.mp4
├── notes.docx
└── ...
```

Directory after running DoctorFiles:
```
Files/
├── pdf/
│   └── report.pdf
├── jpg/
│   └── photo.jpg
├── mp4/
│   └── video.mp4
├── docx/
│   └── notes.docx
```

---

## Why DoctorFiles?

Inspired by **Doctor Who**, this tool symbolizes mastery over file management across "space and time" within your computer. It’s designed to save time, reduce clutter, and bring organization to your digital workspace effortlessly.

---

## Contribution

Contributions, issues, and feature requests are welcome! Feel free to fork the project and submit pull requests.

---

## License

This project is licensed under the MIT License - see the [LICENSE](LICENSE) file for details.

---

## Contact

For any questions or suggestions, reach out via GitHub Issues or contact the maintainer at nipun24.goel@gmail.com.

---

*Organize your digital universe with DoctorFiles!* 🚀📁
