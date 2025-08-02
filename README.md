# Quick Metadata Music Editor
A lightweight Jupyter notebook that extracts artist and title information from MP3 filenames, writes ID3 tags automatically, and optionally renames the files.

## Usage

1. Open `music_metadata_editor.ipynb` in Jupyter Notebook.
2. In **Cell 1**, change the value of the folder_path to the path containing your own MP3 files.
3.  Run each cell in order:
- extract metadata from filenames  
- preview results  
- write tags  
- (optionally) rename the files

## Filename Requirements

This notebook assumes your MP3 filenames follow a format like: Artist Name - Track Title (other info).mp3. Adjust the parsing logic in **Cell 2** if your naming convention differs.
