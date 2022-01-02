***
## GMIT: Fundamentals-of-Data-Analysis
***
### Overview
This repository contains all the files relevant to my 2021 Fundamentals of Data Analysis project.<br>
Read on to explore the project motivations, repository contents, technologies used and project<br>outcomes.
<br />
<br />


### Motivations
1. The first aim of this project was to explore the Python pyplot module from the Matplotlib<br>
plotting library, how it works and what it has to offer in terms of code and plotting capabilities.
2. The second aim was to explore the level 8 CAO points data from 2018 to 2021 while applying skills<br>
of scraping websites, manipulating data using pandas and numpy and analysing the data through<br>
visualisations.

<br />


### Contents of repository:<br />
1. **pyplot.ipynb**: <br />  
    - This Jupyter notebook contains an overview of the matplotlib.pyplot Python package with <br>
    in-depth explanation of three plots from the package. <br />
    - Quicklinks below: *nbviewer* for static, *binder* for dymanic:<br />
        
        <br />
        
   &nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;
[![nbviewer](https://raw.githubusercontent.com/jupyter/design/master/logos/Badges/nbviewer_badge.svg)](https://nbviewer.jupyter.org/github/CiaranMoran27/Fundamentals-of-Data-Analysis/blob/main/pyplot.ipynb) 
[![Binder](https://mybinder.org/badge_logo.svg)](https://mybinder.org/v2/gh/CiaranMoran27/Fundamentals-of-Data-Analysis/HEAD?filepath=pyplot.ipynb) <br />
     
   <br />
      
2. **cao.ipynb**: <br />  
    - This Jupyter notebook details how to scrape CAO points data from the CAO website into a <br />
    pandas data frame, along with a detailed comparison of CAO points in 2019, 2020, and 2021.
    - Quicklinks below: *nbviewer* for static, *binder* for dymanic:<br />
        
       <br />
                    
   &nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;
[![nbviewer](https://raw.githubusercontent.com/jupyter/design/master/logos/Badges/nbviewer_badge.svg)](https://nbviewer.jupyter.org/github/CiaranMoran27/Fundamentals-of-Data-Analysis/blob/main/cao.ipynb) 
[![Binder](https://mybinder.org/badge_logo.svg)](https://mybinder.org/v2/gh/CiaranMoran27/Fundamentals-of-Data-Analysis/HEAD?labpath=cao.ipynb)
<br />
<br />

3. **requirements.txt file**:   
This file contains the packages necessary to run the two notebooks. The binder quicklink calls<br>
    this file and installs the packages listed within allowing the user to easily interact with the<br>
    notebooks.   
<br /> 
4. **data Folder**:  
Contains files of data scraped from CAO website and data files post cleansing.<br /> 

<br>

<br>

### Running notebooks locally

1. Download [Anaconda](https://docs.anaconda.com/anaconda/install/index.html), this contains the python 
interpreter and libraries needed to run this notebook.
2. Download [cmder](https://cmder.net/) if working on a Windows Operating System, alternatively use the basic *command <br>line interface*
if working on a Linux or Mac operating system.
3. Clone [repository](https://github.com/CiaranMoran27/Fundamentals-of-Data-Analysis) as laid out [here](https://docs.github.com/en/github/creating-cloning-and-archiving-repositories/cloning-a-repository).
4. Run '*jupyter lab*' command on:
    - *Cmder* if working on a Windows operation system.
    - *Command line interface* if working on a Linux or Mac operating system.
    
Although Anacondas contains the required packages to run the listed notebooks, one can download <br />
package requirements via running the following command (adjust path accordingly): <br />

``` Python
pip install -r /path/requirements.txt
```

<br>


### Project Outcomes:
#### Matplotlib:
This project showed how useful the pyplot module is at plotting, and how its stateful approach can be<br>
overcome when adopting the object orientated approach. It also shows how one can effectively plot and<br>
utilise the histogram, violin plot and scatter plot on real world data.

#### CAO Points:
Exploring the web scraping capability of python showed how dynamic it is at scraping html, excel files<br>
and pdf files when leveraging regular expressions. This project successfully joined and cleansed the CAO<br>
data from 2019 to 2021 and compared counts via using barcharts, spread via boxplots and distributions<br>
via histograms / KDE's. The overall findings showed an increase in the points of courses offered in 2021.

