# Fundamentals of Data Analysis 2019 Project
## G00190832 
## Peter McGowan

## Introduction

This analysis of the Tips Dataset has been carried out as an assignment of the Fundamentals of Data Analysis module of the Higher Diploma In Data Analytics at GMIT. The project description can be found [here](https://github.com/ianmcloughlin/project-2019-fundda/blob/master/project.pdf).

The repository contains a Jupyter Notebook that explores aspects of the Tips Dataset with the aid of Seaborn. The tasks assigned are as follows:
1. <b>Description:</b> >Create a git repository and make it available online for the lecturer to clone. The repository should contain all your work for this assessment. Within the repository, create a jupyter notebook that uses descriptive statistics and plots to describe the tips dataset. This part is worth 30% of your overall mark.
2. <b>Regression:</b> >To the above jupyter notebook add a section that discusses and analyses whether there is a relationship between the total bill and tip amount, and this part is also worth 30%.
3. <b>Analyse:</b> >Again using the same notebook, analyse the relationship between the variables within the dataset. You are free to interpret this as you wish --- for example, you may analyse all pairs of variables, or select a subset and analyse those. This part is worth 40%.


The repository also includes:
* Readme file
* License file
* Gitignore folder
* Several images

## License

This project is licensed under the GNU General Public License v3.0 - see [LICENSE.md](LICENSE) for details.

## Jupyter Notebook

### Downloading the Repository

The repository is stored at [https://github.com/Pmcg1/FoDA_Project_2019](https://github.com/Pmcg1/FoDA_Project_2019).

To download it, do the following:

1. Click on the "Clone or Download" button
2. Select "Download ZIP". This will open a prompt allowing you to save the file to your computer.
3. Navigate to the download location and extract the compressed (.zip) folder to a suitable location.

### Software Required

The notebook has been written using Jupyter Lab v1.0.2. and Python v3.7.3 and should be run on a computer with these versinos or higher if possible. I recommend that you download the current Python 3.x Anaconda Distribution (which contains both Python and Jupyter Lab) from the [downloads section](https://www.anaconda.com/distribution/#download-section) of the Anaconda Website.

When it has downloaded, follow the installation steps with the default options to install Anaconda on your computer.

You can check which (if any) versions of these that you have installed by typing the following at the command prompt:
* python --version
* jupyter --version

This project also requires a number of external Python libraries ([listed below](#Libraries-Used)). These come with the Anaconda Distribution and should not need to be installed separately, however links to the website for each are included.

### Libraries Used

* [Pandas](https://pandas.pydata.org/) - Used for managing and manipulating the data;
* [Matplotlib.pyplot](https://matplotlib.org/tutorials/introductory/pyplot.html) - Used for manipulation of elements of certain plots in the notebook;
* [Seaborn](https://seaborn.pydata.org/) - Used for creation and manipulation of all plots in the notebook;
* [Numpy](https://www.numpy.org/) - Numpy is used for some mathematical and statistical functions;
* [scipy](https://www.scipy.org/) - The [scipy.stats](https://docs.scipy.org/doc/scipy/reference/stats.html) library is used for its skewness function.

Please note that the programmes will not run successfuly if their required libraries are not installed.

### How to Run

Once the correct software has been installed, running either of the included programmes can be carried out as follows:

1. Open a command prompt (cmd) or equivalent on your PC. The alternative "cmder" programme ([available here](https://cmder.net/)) is recommended.
2. Navigate to the drive that the folder is on.
3. Navigate to the correct folder.
4. Run jupyter lab by typing the following at the command prompt (do not close the command prompt window throughout):
> jupyter lab

5. A window or tab should open in your default web browser (Mozilla Firefox and Google Chrome are recommended). If this does not happen, read the command prompt output. It should provide a URL which you can copy and paste into your web browser to access Jupyter Lab.
6. Using the menu on the left side of the page, double click the jupyter notebook file:
> ProgDA_Assessment_1_2019.ipynb

7. The notebook should open in a new tab. You can run each cell with the keyboard shortcut SHIFT+ENTER, alternatively use the "play" button on the menu bar. Please note that certain cells must be run before others e.g. the cells importing the various Python libraries. You may find it convenient to use the "Run all Cells" option in the "Run" dropdown menu.
