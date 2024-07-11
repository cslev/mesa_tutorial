# mesa_tutorial
This repo contains source files for the Mesa agent-based modeling framework's tutorial.
Mostly for one or two of them, and in jupyter notebook format (developed in VS code though).

## What is Mesa? 
*"Mesa allows users to quickly create agent-based models using built-in core components (such as spatial grids and agent schedulers) or customized implementations; visualize them using a browser-based interface; and analyze their results using Python's data analysis tools. Its goal is to be the Python-based alternative to NetLogo, Repast, or MASON."* --> more info click [here](https://github.com/projectmesa/mesa).

## What this repo is all about
Basically, it is the reproduction of the official Mesa tutorial found [here](https://mesa.readthedocs.io/en/stable/tutorials/intro_tutorial.html)....and maybe more examples from the wild.

## Requirements
If you use this in VS Code as I do, first add/open the directory in your VS code, open the `money_model.ipynb` (or any other `ipynb` file) and create a Python virtual environment via clicking on the top right corner's button stating "Select kernel". 

Then choose your Python environment (e.g., Python3.9, Python3.10) and let VS code do its job. The benefit of letting VS code doing the virtual environment is that it will install the `jupyter-notebook `related packages. If you create your virtual enviroment on your own via `python3 -m venv .venv`, you should install jupyter-notebook related packages on your own.

After having the virtual environment created (`.venv` directory) and as you can observe the `.vscode` directory also has a `settings.json` file pointing to here. Therefore, your VS code environment will know the interpreter and won't complain about missing imports later.

### Install Mesa libs into your venv
Open a terminal, or use the terminal in VS code and activate the virtual environment.
```
$ source .venv/bin/activate
```
#### Install libs
```
$ pip install --upgrade mesa
$ pip install seaborn
```

Now, you are done and ready to use this repo.




