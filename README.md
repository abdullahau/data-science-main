# Titanic Notebook

This notebook uses machine learning algorithms to get the best accuracy of predictions for who survived the sinking of the Titanic given the attributes in the dataset.

## Setup

- Install Python 3.12.2
  - Run `python --version` to ensure you have the correct version
- and/or create a Python virtual environment with Python 3.12.2 
  - If you have the right python version, simply create a new python virtual environment using the following CLI `python -m venv /path/to/new/virtual/environment` (I prefer placing the virtual environment inside the project folder so that VS code can automatically detect the right kernel)
- [Activate](https://docs.python.org/3/tutorial/venv.html) your virtual environment
- Once your environment is activated, navigate to the folder containing the project/repo files and run the following command the terminal to install all required packages:
  - `pip install -r requirements.txt`
- In VS Code, open the [Titanic.ipynb](Titanic.ipynb) file and ensure the right kernel is connected
- To be able to view the decision tree in the output, you will need to install the [graphviz](https://graphviz.org/download/) library.
  - I used graphviz version 10.0.1 (post installation you can check the version and correct installation by running `dot -V` in the terminal)
  - I simply used scoop on windows to install graphviz. You can use brew on Mac/Linux to install graphviz.