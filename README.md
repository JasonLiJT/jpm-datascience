# Machine Learning in Python Setup Instructions

## Setup for the impatients

If you are on a unix machine and are a unix wizz (if you are not, please jump to the next section) here are the condensed set of actions you need to do:

Start by installing Anaconda:  [https://www.continuum.io/downloads](https://www.continuum.io/downloads). Then:

```bash
sudo pip install seaborn plotly
```

And _on the day_,

```bash
git clone http://gitlab.cambridgespark.com/pub/jpm-datascience/
```

You're now ready to go.

## Install Python and Anaconda

Start by checking the version of Python that you are running by typing

```bash
python -V
```

in your terminal (_Terminal_ in Mac and Linux, _Command prompt_ or `cmd.exe` for Windows). If this fails, download and install Python [https://www.python.org/downloads/](https://www.python.org/downloads/).
Then, install the corresponding version of Anaconda from:  [https://www.continuum.io/downloads](https://www.continuum.io/downloads).
This includes many necessary libraries we will be using such as `numpy`, `pandas`, `scipy` and `scikit-learn`.

## Install Packages with pip

Open your terminal/command prompt and check whether you have the `pip` command correctly installed by typing

```bash
pip -V
```

Note that `pip` comes with Anaconda so if an error is returned, it may mean that you haven't installed Anaconda properly or that your computer does not know where Anaconda is. Check the installation steps of Anaconda to verify you have not missed one.

Assuming you have `pip`, you can now install additional useful libraries, in particular `seaborn` and `plotly` (for data visualisation). For this type:

```bash
pip install seaborn plotly
```

if it fails mentioning access rights, you need to run the command with administrator rights:

* with Windows this means running the command prompt as administrator,
* with unix machine, add `sudo` in front of the line i.e.:

```bash
sudo pip install seaborn plotly
```

which will prompt you for your system password.

## Using Git

Git is a very powerful versioning tool. Check if you have it by typing `git --version` in your terminal/command-prompt. If it returns an error (along the lines of `command not found`), you can install it from  [http://git-scm.com/](http://git-scm.com/).

### (On the day) clone the code from the repository

On the day, notebooks and datasets will be made available in the remote folder (_repository_) in which this `README` file is located.

In order to make a local copy of this repository, pick an appropriate location on your computer (say your desktop), open a terminal/command-prompt within that directory and execute the cloning command:

```bash
git clone http://gitlab.cambridgespark.com/pub/jpm-datascience
```

### In case of troubles

Alternatively you can also download the repository by clicking on the "Download ZIP" button.

If you encounter other issues, please contact <mailto:thibaut@cambridgespark.com>.
