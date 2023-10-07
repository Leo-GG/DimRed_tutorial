# Instructions for teachers

## Installation
In order to use interactive python notebooks (ipynb) in classes you need to choose the platform that best suits your students and classroom resources. There is no optimal solution for every case as every platform has advantages and disadvantages. Installing Anaconda (https://www.anaconda.com/download) and running Jupyter Notebook is often a great choice. Other options include installing Visual Studio Code or running the notebooks on Google Colab. 
Here are some advantages and disadvantages of each: 
- Jupyter Notebook:
  - Advantages: It’s an open-source web application that allows you to create and share documents that contain live code, equations, visualizations, and narrative text. It’s great for data cleaning and transformation, numerical simulation, statistical modeling, data visualization, machine learning, and much more.
  - Disadvantages: It can be a bit complex to set up for beginners. It requires local installation and setup of Python and necessary libraries.

- Visual Studio Code (VSCode):
  - Advantages: VSCode is a free source-code editor made by Microsoft for Windows, Linux, and macOS. It includes support for debugging, embedded Git control, syntax highlighting, intelligent code completion (IntelliSense), snippets, and code refactoring. It also supports Jupyter notebooks natively.
  - Disadvantages: Similar to Jupyter Notebook, it requires local installation and setup. While it’s a powerful tool for coding, it might be overwhelming for beginners due to its wide range of features.

- Google Colab:
  - Advantages: Google Colab is a free cloud service based on Jupyter Notebooks for machine learning education and research. It provides free GPU and is easy to use. It’s an excellent tool for collaborative projects as notebooks can be easily shared with others.
  - Disadvantages: The session times out after a period of inactivity; also, there’s less control over the environment compared to local setup.
 
## Running the notebooks on Google Colab
- If you have a (free) google account, you can run Jupyter notebooks on [colab](https://colab.research.google.com/) directly on your browser without having to download or install anything on your computer. To do so, simply click the links bellow:
  -[Notebook with PCA using COVID-19 data](https://githubtocolab.com/Leo-GG/DimRed_tutorial/blob/main/demographicsMaterials/covid_PCA.ipynb)
  -[Notebook with non-linear methods using COVID-19 data](https://githubtocolab.com/Leo-GG/DimRed_tutorial/blob/main/demographicsMaterials/covid_NonLinear.ipynb)
  -[Notebook with PCA using single-cell RNAseq data](https://githubtocolab.com/Leo-GG/DimRed_tutorial/blob/main/scMaterials/sc_PCA.ipynb)
  -[Notebook with non-linear methods using single-cell RNAseq data](https://githubtocolab.com/Leo-GG/DimRed_tutorial/blob/main/scMaterials/sc_NonLinear.ipynb)
  
-  Feel free to make alterations in the Jupyter notebooks you can allways go back to the original files or save your own versions.
-  You can use Google Colab to open Jupyter notebooks on your local computer by going to https://colab.research.google.com/ and pressing "File/Upload notebook" on the top menu. The colab interface is slightly different from the Jupyter one, but both will run the same Python code.


## Interacting with the notebooks

- Notebook Structure: Guide your students to understand the Notebook Structure. The notebook is divided into cells which can contain either code or markdown text for explanations. Cells are executed in order, from top to bottom. To execute a code cell, click on it and press `Shift + Enter`. This will run the cell. The output of the code in that cell (if any) is displayed below it.

- Importing Libraries: The first cells contain import statements for libraries that are used in the notebook. Remind your students to make sure to run these cells to import the necessary libraries before running the cells that use the modules.
When the students encounter a “ModuleNotFoundError: No module named ..” error, it means that the Python interpreter couldn’t find that specific module in that environment. ‘Pandas’ for instance is a very popular data manipulation library in Python, but it’s not included in the standard library. Therefore, it needs to be installed separately. It can be done directly from the notebook by running a code cell with !pip install pandas.

- Data Loading and Preprocessing: There will be cells dedicated to loading the required data (usually in CSV or similar format) and preprocessing it (cleaning, normalization, etc.). Instruct the students to download the files, place the files in the same folder as the notebook, and carefully read the comments and markdown text to understand what each step does.

- Data Analysis and Visualization: Several cells contain code for analyzing the data and visualizing the results using plots and charts. Again, make sure the students read any accompanying text or comments and that they are confident to run, re-run and even alter parameters. Remind the students that the best way to learn is by doing. They should not hesitate to modify the code, try new things, and see what happens! 

- Customizing  the Notebook: If you want to try different preprocessing steps or analysis methods, you can edit the code in a cell and re-run it. You can also add new cells by clicking on `Insert > Insert Cell Below`. If you want to share your new notebook, you can export it in various formats (`File > Download as`). Happy teaching! 🚀
