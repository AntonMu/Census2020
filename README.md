# Census2020
In this tutorial we walk through an example of using jupyter notebooks and pandas to create a bar chart race for the US census data from the past 230 years. 

If you already know how to run jupyter notebooks and how to install python packages, you can go straight to the notebook with:

```
jupyter notebook
```
and then opening [`USCensus2020.ipynb`](USCensus2020.ipynb) from within the jupyter notebook interface. The entire tutorial and all of its steps are described in the notebook.  

If you need help setting up jupyter notebooks on your machine, follow the instructions below:

## Getting Started with Jupyter Notebooks

### Requisites
The only hard requirement is a running version of python 3.3 or newer. To install the latest python 3.x version go to [python.org/downloads](https://www.python.org/downloads/) and follow the installation instructions. 

### Installation

#### 1a Setting up Virtual Environment [Linux or Mac]

Clone this repo with:
```
git clone https://github.com/AntonMu/Census2020
cd Census2020
```
Create Virtual **(Linux/Mac)** Environment (requires [venv](https://packaging.python.org/guides/installing-using-pip-and-virtual-environments/) which is included in the standard library of Python 3.3 or newer):
```
python3 -m venv env
source env/bin/activate
```
Make sure that, from now on, you **run all commands from within your virtual environment**.

#### 1b Setting up Virtual Environment [Windows]
Use the [Github Desktop GUI](https://desktop.github.com/) to clone this repo to your local machine. Navigate to the `Census2020` project folder and open a power shell window by pressing **Shift + Right Click** and selecting `Open PowerShell window here` in the drop-down menu.

Create Virtual **(Windows)** Environment (requires [venv](https://packaging.python.org/guides/installing-using-pip-and-virtual-environments/) which is included in the standard library of Python 3.3 or newer):

```
py -m venv env
.\env\Scripts\activate
```
![PowerShell](/Screenshots/PowerShell.png)
Make sure that, from now on, you **run all commands from within your virtual environment**.

#### 2 Install Required Packages [Windows, Mac or Linux]
To install required packages run:

```
pip3 install -r requirements.txt
```

### Run Jupyter Notebook
Once the requirements installed, you are able to start the jupyter notebook service via:

```
jupyter notebooks
```

This should automaticaly open a web browser with the notebook server. If it doesn't work you can go to a web browser and manually go to [localhost:8888](http://localhost:8888/]). 

Finally, open [`USCensus2020.ipynb`](USCensus2020.ipynb) from within the jupyter notebook interface.

<!-- https://janakiev.com/blog/jupyter-virtual-envs/ -->

## Licensing 
This work is licensed under a [Creative Commons Attribution 4.0 International
License][cc-by]. This means that you are free to:

 * **Share** — copy and redistribute the material in any medium or format
 * **Adapt** — remix, transform, and build upon the material for any purpose, even commercially.

Under the following terms:

 * **Attribution** — a link to this [github repo](https://github.com/AntonMu/Census2020)!
 
[![CC BY 4.0][cc-by-image]][cc-by]

[cc-by]: http://creativecommons.org/licenses/by/4.0/
[cc-by-image]: https://i.creativecommons.org/l/by/4.0/88x31.png
[cc-by-shield]: https://img.shields.io/badge/License-CC%20BY%204.0-lightgrey.svg