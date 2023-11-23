# GoIT Python Course Homework Projects
This repository contains a series of projects developed as part of the Python course homework assignments

## File organiser

The repository contains a Python script designed for organisation and renaming of files within a designated directory. Its key functionality lies in its ability to systematically sort files based on their type, with support for a wide range of file formats. The script is particularly efficient in handling:

-   **Image Files:** JPEG, PNG, JPG, SVG
-   **Video Files:** AVI, MP4, MOV, MKV
-   **Documents:** DOC, DOCX, TXT, PDF, XLSX, PPTX
-   **Audio Files:** MP3, OGG, WAV, AMR
-   **Archives:** ZIP, GZ, TAR
-   **Unknown Extensions:** files with unrecognisable extensions

A key feature of this script is its file renaming capability. The 'normalize' function is designed to transliterate Cyrillic characters to their Latin equivalents and to sanitise file names by replacing non-standard characters with underscores ('_'). This ensures compatibility across different operating systems and environments.

### Installation and Usage:
    # Clone the repository
    git clone https://github.com/alex-nuclearboy/goit-python-homeworks.git
    # Navigate to the script directory
    cd goit-python-homeworks/goit-python-hw-01/file-sorting
    # Run the script on your desired directory
    python3 sorter.py <path_to_target_directory>
