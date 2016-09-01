# python34-examples
## A repository of Python example code.
This repository contains a series of examples of commonly-required tasks using Python 3.4. The examples are stored as Jupyter notebooks. They can can be opened directly from the repository and, providing the commands in the notebook had been run before saving, then the results can be viewed. However, if it is required to run the commands in the notebook locally, then it is necessary to install a virtual Python environment in the folder containing the notebook files. The virtual environment can be installed in a directory called env/ or env3/ – both these directory names are included in .gitignore and, therefore, will not be pushed to Github.
In order to install a virtual environment use:
```
$ cd path_to_required_directory
$ git clone url_of_repository
$ cd python34-examples   # i.e. cd to cloned directory
$ virtualenv -p /Library/Frameworks/Python.framework/Versions/3.4/bin/python3.4 env3
```
The virtual environment will also need to have several required libraries installed, such as:
```
$ env3/bin/pip install numpy
$ env3/bin/pip install pandas
$ env3/bin/pip install matplotlib
$ env3/bin/pip install jupyter
```
Other libraries may also need to installed.

```
$ env3/bin/pip install pymssql
$ evn3/bin/pip install pymysql
```

To open the jupypter notebook, use:
```
$ env3/bin/jupyter-notebook
```
