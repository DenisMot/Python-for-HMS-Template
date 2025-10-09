# A minimal template for data analysis with python 

This is a minimal template for data analysis with python, intended to researchers in human movement sciences that are new to python.   
Cloning this template for each new data analysis problem should facilitate data analyses with python and minimize potential errors.   

## Usage
1. Download as a zip file (green button `< > Code` on the top right of the page)
1. Expand the archive on your computer (e.g., in your `Download` folder). 
1. Rename the extracted folder with the name of your new project (e.g., `ECG_analysis`)
1. Move the new `ECG_analysis` folder where it should be located (e.g., in your `Documents/CodeProjects/` directory)
1. In VSCode :
    1. open the new project in a new window. 
    1. open `main.ipynb` and click `Run all`

## Notebook template
The `template.ipynb` notebook contains a minimal template for data analysis with python. It includes the following sections:
- **Header:**
  - The first cell will add a header to the notebook with the project title, author, date. 
  - You should edit this cell to add your information.
- **Data Analysis Cells:**
  - The cells you will use for data analysis (e.g., loading data, preprocessing, modeling, etc.) go here.
- **Export Cell:**
  - The last cell will save the notebook as a HTML file next to the notebook file and open it in your web browser. 
  - The HTML will include all the graphics, and will not show the cell numbers. 
  - Cells tagged with `hide` will not be shown in the HTML file. 
    - You can add the `hide` tag to any cell you do not want to appear in the HTML file (e.g., in VSCode, click on  `...` in the icon box in the top left of the cell)

## Requirements
- [A minimal Python environment for reproducible research in human movement sciences](https://github.com/DenisMot/Python-minimal-install) is my preferred solution.
- Any IDE supporting python and jupyter notebooks is an alternative solution. 