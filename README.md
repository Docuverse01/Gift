# Instructions

## 1. Download the Repository:

   - Click on the green "Code" button on the GitHub repository page.
   - Select "Download ZIP" from the dropdown menu.
   - Save the ZIP file to your preferred location.

   ![Download ZIP](https://images-ext-1.discordapp.net/external/mwBzZKN2f0PvtA--zrq7Fbus5vRZ7f5sZoRw3OHMmk8/https/i.ibb.co/rdDHzdv/image1.png?format=webp&quality=lossless)

## 2. Extract the ZIP file:

   - Locate the downloaded ZIP file (check your donwloads) then move it to your desktop.
   - Right-click on the file and select "Extract Here...".
   - a folder with the name `BAC` will be created


## 3. Download the HTML File:

   - Open a browser and visit the website containing the desired HTML file (example: [http://www.bacweb.tn/tma.htm](http://www.bacweb.tn/tma.htm)).
   - Type `Ctrl + S` to save the HTML file.
   - Save the downloaded HTML file in the 'BAC' directory (and don't change its name; it should be `Les épreuves corrigées du Baccalauréat.html`).
   - Ensure the HTML file is placed in the same directory as the provided Python script (`Docuverse-BAC-System.py`).



## 4. Install Required Libraries:

   - Open the command prompt (CMD) by pressing `Win + R` and typing `cmd`.
   - Type the following command to install the required libraries:

     ```bash
     pip install Pillow img2pdf beautifulsoup4 openpyxl PyMuPDF pandas
     ```

## 5. Run the Code:

   - Replace 'Les épreuves corrigées du Baccalauréat.html' with the actual name of the downloaded HTML file in the code.
   - Run the provided Python script (`Docuverse-BAC-System.py`).
   - Wait the result and don't close the black window (the cmd/ terminal)
   - once the code have finished you can see the result (they may be some lagging right after the result reveal)
     NB: you can always reuse the code, just replace the HTML file with the old one, and don't forget to change the folder name of the result

## 6. Understand the Results:

   - Two folders will be created: 'Correction' and 'Devoirs', containing downloaded PDFs.
   - Two PDF files will be generated: 'Section-Matiere-Livre-Correction.pdf' and 'Section-Matiere-Livre-Devoirs.pdf' - combining all PDFs in their respective folders.
   - Two Excel files will be created: 'Sommaire_Correction.xlsx' and 'Sommaire_Devoirs.xlsx', providing a summary of PDF information.

Ensure you have Python and pip installed on your system before executing these commands.
