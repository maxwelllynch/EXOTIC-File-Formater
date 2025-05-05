Introduction:
This code is meant to be a resource for citizen scientists to prepare personal observations for use with NASA's EXOTIC tools.

How to set up:
1. Create a directory on your desktop named "EXOTIC".

2. Move the directory of files you want to format into the "EXOTIC" directory

3. Copy all appropriate dark FITS files into a directory (e.g. darks/)

4. Copy all appropriate science FITS files into another directory (e.g. science/)

5. Make a copy of this text file, "README.txt", and move it into the folder from step 2. You will need to make sure the copied file has the same name (i.e. "README.txt" not "README_copy.txt"). The file path of the duplicated README file should be "~/Desktop/Exotic/Ex_Folder/README.txt".

6. Create another directory in "EXOTIC" called "Tools"

7. Download 'evformat.py' from this github and copy it into "Tools"

8. Download zip file from Mike Primm's "evtools" github and unzip in "Tools". It may be helpful to read through 'README.md' at this link: https://github.com/mikeprimm/evtools/tree/main

9. Move 'evformat.py' into evtools directory

10. Replace variable descriptors with variable values below

11. Run 'python evformat.py' to begin formatting files



Please update the following parameters that are specific to your observations:

Object = Target object name (e.g., HAT-P-22)
Right Ascension = Right Ascension of telescope pointing (hh:mm:ss or degrees)
Declination = Declination of telescope pointing (dd:mm:ss or degrees)
Filter = Photometric filter used (e.g., V, R, I, Clear)