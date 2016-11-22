# Machine Learning in Python Setup Instructions

## Install Python and Anaconda

http://gitlab.cambridgespark.com/pub/jpm-datascience

Start by checking the version of Python that you are running by typing

```bash
python -V
```

in your terminal (_Terminal_ in Mac and Linux, _Command prompt_ or `cmd.exe` for Windows). If this fails, download and install Python [https://www.python.org/downloads/](https://www.python.org/downloads/).
Then, install the corresponding version of Anaconda from:  [https://www.continuum.io/downloads](https://www.continuum.io/downloads).
This includes many necessary libraries we will be using such as `numpy`, `scipy` and `scikit-learn`.

## Install Packages with pip

Open your terminal/command prompt and check whether you have the `pip` command correctly installed by typing `pip -V` and enter. It should return something like

```bash
pip 9.0.1 from <PATH> (python 3.5)
```

where `<PATH>` is a directory on your computer. Note that `pip` comes with Anaconda so if an error is returned, it may mean that you haven't installed Anaconda properly or that your computer does not know where Anaconda is. Check the installation steps of Anaconda to verify you have not missed a step.

Assuming you have `pip`, you may need to use `sudo` (for OSX, *nix, etc) or run your command shell as Administrator (for Windows) to be able to perform the installation of the following individual packages. Try without sudo first and if an error mentioning access rights is returned, add it. The packages to install are `seaborn` and `plotly` (useful to visualise data):

```bash
(sudo) pip install seaborn
(sudo) pip install plotly
```

## Using git

Check if you have git by typing `git --version` in your terminal/command-propmpt. If it returns an error (along the lines of `command not found`), you can install it from  [http://git-scm.com/](http://git-scm.com/).

### (On the day) clone the code from the repository

On the day, notebooks and datasets will be made available in a remote folder (_repository_) which you will have to make a local copy of.

For this, pick an appropriate location on your computer (say your desktop) navigate to it using your terminal (using the command `cd <DIR>`) and finally execute the cloning command:

```bash
git clone http://gitlab.cambridgespark.com/pub/jpm-datascience
```

### In case of troubles

Alternatively you can also download the repository by clicking on the "Download ZIP" button.

If you encounter other issues, please contact <mailto:thibaut@cambridgespark.com>.
