# GoIT Python Course Homework Projects
This repository contains a series of projects developed as part of the Python course homework assignments

## File Organiser

The `goit-python-core-hw-06` contains a Python script (`file-sorting/sorter.py`) designed for organisation and renaming of files within a designated directory. Its key functionality lies in its ability to systematically sort files based on their type, with support for a wide range of file formats. The script is particularly efficient in handling:

-   **Image Files:** JPEG, PNG, JPG, SVG
-   **Video Files:** AVI, MP4, MOV, MKV
-   **Documents:** DOC, DOCX, TXT, PDF, XLSX, PPTX
-   **Audio Files:** MP3, OGG, WAV, AMR
-   **Archives:** ZIP, GZ, TAR
-   **Unknown Extensions:** files with unrecognisable extensions

A key feature of this script is its file renaming capability. The `normalize` function is designed to transliterate Cyrillic characters to their Latin equivalents and to sanitise file names by replacing non-standard characters with underscores ('_'). This ensures compatibility across different operating systems and environments.

### Installation and Usage:
    # Clone the repository
    git clone https://github.com/alex-nuclearboy/goit-python-homeworks.git
    # Navigate to the script directory
    cd goit-python-homeworks/goit-python-hw-06/file-sorting
    # Run the script on your desired directory
    python3 sorter.py <path_to_target_directory>

## Python Package and Console Script for File Organiser

The `goit-python-core-hw-07` section of the repository contains a command-line utility designed to organise and clean up specified directories by sorting files into categorised folders. 

### Installation and Usage:
    # Clone the repository
    git clone https://github.com/alex-nuclearboy/goit-python-homeworks.git
    # Navigate to the directory containing setup.py
    cd goit-python-homeworks/goit-python-core-hw-07/clean_folder
    # Install the package using pip:
    pip install .
    # Run the script
    clean_folder <path_to_target_directory>
    
