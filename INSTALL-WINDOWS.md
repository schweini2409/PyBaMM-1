## Prerequisites

To use and/or contribute to PyBaMM, you must have Python 3.6 or 3.7 installed (note that 3.8 is not yet supported).

To install Python 3 download the installation files from [Python's website](https://www.python.org/downloads/windows/). Make sure
to tick the box on `Add Python 3.X to PATH`. For more detailed instructions please see the 
[official Python on Windows guide](https://docs.python.org/3.7/using/windows.html).

## Install PyBaMM

### User install
Launch the Command Prompt and go to the directory where you want to install PyBaMM. You can find a reminder of how to
navigate the terminal [here](http://www.cs.columbia.edu/~sedwards/classes/2015/1102-fall/Command%20Prompt%20Cheatsheet.pdf).

We recommend to install PyBaMM within a virtual environment, in order not
to alter any distribution python files.

To create a virtual environment `env` within your current directory type:

```bash
python -m venv env
```
You can then "activate" the environment using:

```bash
env\Scripts\activate.bat
```
Now all the calls to pip described below will install PyBaMM and its dependencies into
the environment `env`. When you are ready to exit the environment and go back to your
original system, just type:

```bash
deactivate
```

PyBaMM can be installed via pip:
```bash
pip install pybamm
```

PyBaMM's dependencies (such as `numpy`, `scipy`, etc) will be installed automatically when you install PyBaMM using `pip`.

For an introduction to virtual environments, see (https://realpython.com/python-virtual-environments-a-primer/).

## Uninstall PyBaMM
PyBaMM can be uninstalled by running
```bash
pip uninstall pybamm
```
in your virtual environment.

## Installation using WSL
If you want to install the optional PyBaMM solvers, you have to use the Windows Subsystem for Linux (WSL). You can find
the installation instructions [here](INSTALL-WINDOWS-WSL.md).
