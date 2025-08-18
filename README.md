# Welcome to the wonderful world of Python and Jupyter Notebooks!
This repo contains a Jupyter Notebook (`hull_jupyter_demo_clean.ipynb`) that takes a modified version of a supplementary table from [Ortiz et al., 2021](https://journals.asm.org/doi/10.1128/mbio.01672-21) and produces plots (`ortiz_boxplot.png`, `ortiz_boxplot_dots.png`, and `ortiz_dotplot.png`) from it. The overarching goal of the notebook and the other files in this repo is to introduce the user to [Jupyter Notebooks](https://jupyter.org/), Python, and the command line in general.

This documentation assumes the user is running macOS on their local computer.

## Dependencies: Programs and Python Packages that the notebook assumes you already have installed
[JupyterLab or Notebook](https://jupyter.org/), [pandas](https://pandas.pydata.org/), and [matplotlib](https://matplotlib.org/)

### Determining if you have the dependencies
1. Open a terminal
    1. Click the magnifying glass - `Spotlight Search` - in the upper right of your screen
    2. Type `Terminal` and hit `return` on your keyboard
1. Check if you have `Jupyter` installed
    1. Type the following in the terminal:
        ```
        which jupyter
        ```
        1. If the command returned a directory path (ex. `/usr/bin/jupyter`), the program is installed.
        2. If the command returned nothing or a message like `jupyter not found`, you need to install the program using the instructions in the next section.

3. Check if you have the Python packages
    1. Type the following in the terminal:
        ```
        pip show <package_name>
        ```
        Replace `<package_name>` with the name of the package you want to check.
       1. If the command returned a ton of text about the package, the package is installed.
       2. If the command returned a message like `WARNING: Package(s) not found: pandas`, you need to install the package using the instructions in the next section.
### Installing Dependencies if you don't have them
```
pip install jupyterlab pandas matplotlib
```
- Only include the software or packages you are missing
  
## Cloning (downloading) this repo
1. Navigate to the directory (folder) you want to clone the repo into
    ```
    cd ~/Documents
    ```
2. Clone repo
    ```
    git clone https://github.com/meadm/hull_jupyter_demo.git
    ```

### Or download the repo as a zipped folder
1. On the repo's main page, click `<> Code`
    - A red arrow is pointing to it in the picture below
      <img width="1439" height="689" alt="Image" src="https://github.com/user-attachments/assets/30073f78-009f-4586-a6cd-bf5e8e9273d2" />
2. Click `Download ZIP` in the menu that pops up
    - A red arrow is pointing to it in the picture below
      <img width="1439" height="689" alt="Image" src="https://github.com/user-attachments/assets/6ad5f891-1acf-43c0-bf41-26946031633c" />
3. Place the `.zip` file in your desired directory/folder and unzip it

## Opening and running the Jupyter Notebook
1. Navigate into the repo
   ```
   cd hull_jupyter_demo
   ```
2. Open the notebook
   ```
   jupyter lab hull_jupyter_demo_clean.ipynb
   ```
   - Note that `hull_jupyter_demo_draft.ipynb` is a draft notebook that contains errors and extraneous code.
   - A window or tab containing the Jupyter notebook will open in your default internet browser.
3. Running a code cell
   1. Click in the cell (gray box - a red arrow is pointning to one in the image below) that you want to run

      <img width="700" height="300" alt="Image" src="https://github.com/user-attachments/assets/8488af5e-3a86-4651-b718-4789b5030cdc" />   
   2. Press `shift` + `enter` on your keyboard at the same time to execute the code in the cell

## Outputs
After running all cells (and assuming you didn't change any of the cells) you should have versions of `ortiz_boxplot.png`, `ortiz_boxplot_dots.png`, and `ortiz_dotplot.png` in the repo directory. Examples of each plot are below.

<img width="400" height="400" alt="Image" src="https://github.com/user-attachments/assets/16f2069a-1bd2-4ae1-9f1f-9bb63d4cd387" />

<img width="500" height="500" alt="Image" src="https://github.com/user-attachments/assets/1146efe5-2ed1-4975-8d6c-1bdc18e46082" />

<img width="400" height="400" alt="Image" src="https://github.com/user-attachments/assets/16831bf5-b2d7-4cec-bf60-13383b69d4e4" />

*(This repo was originally designed as part of a demonstration given to the [Hull Lab](https://hulllab.bmolchem.wisc.edu/dr-christina-hull-2/)'s journal club on 2025-08-14)*
