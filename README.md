# JPG-Title-Snapper
JPGTitleSnapper is a script for Adobe InDesign that automates JPEG export by naming files based on a specific text box's content on each page. This ensures logical organization of files, reflecting the document's content, and reduces manual errors.


System Requirements
Adobe InDesign: Ensure you have Adobe InDesign installed on your computer. The script is compatible with versions CS6 and later.
Operating System: Compatible with both Windows and macOS.
Installation
Download the Script:

Save the JPGTitleSnapper.jsx file to your local machine.
Install the Script:

Navigate to your InDesign scripts folder:
Windows: C:\Users\[Your Username]\AppData\Roaming\Adobe\InDesign\[Version]\en_US\Scripts\Scripts Panel
macOS: ~/Library/Preferences/Adobe InDesign/[Version]/en_US/Scripts/Scripts Panel
Copy the JPGTitleSnapper.jsx file into the Scripts Panel folder.
Launch the Script:

Open Adobe InDesign.
Open your document.
Go to Window > Utilities > Scripts to open the Scripts panel.
Double-click JPGTitleSnapper.jsx to launch the script.
Using the Script
Running the Script:

Once launched, a dialog box will appear.
Input Required:

ScriptLabel: Enter the label (name) of the text box containing the title you want to use for naming your JPEG files.
Export Path: Specify the directory where you want to save the exported JPEG files.
Page Range: Enter the range of pages you wish to export (e.g., 1-3 or 5).
Export Options:

After the initial dialog, a second dialog will ask for export settings:
DPI: Choose the resolution (72, 150, 300 DPI).
JPEG Quality: Select the quality of the JPEG (LOW, MEDIUM, HIGH, MAXIMUM).
Exporting:

Click OK to start the export process. The script will automatically name and save the files based on the content of the specified text box on each page.
Troubleshooting
No Text Found: If a page doesn’t have the specified text box or the text box is empty, the script will skip the page and notify you of the error.
File Naming Issues: The script automatically cleans file names of any invalid characters to ensure compatibility with your operating system.

Changelog
Version 1.0: Initial release with basic page export and naming functionalities.
This manual provides all necessary steps to install, configure, and use the JPGTitleSnapper script effectively. Enjoy an automated and organized export process for your InDesign projects!
