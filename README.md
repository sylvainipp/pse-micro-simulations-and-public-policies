# PPD/APE Micro-Simulations and Public Policies

My mail adress : sylvain.duchesne@ipp.eu

Actions students have to take

* [Before first session (2024/02/01)](#before-first-session)
* [Before second session (2024/02/15)](#before-second-session)

## Before first session

### Install the software

You have to bring your own laptop computer and install the python software.

For the tutorial, you will need to install the Python language together with some specific packages. You need to have a functional internet connection.

#### Python

You can install a minimal Python or use Anaconda

##### Minimal install

Start by downloading Python 3.11 from [this page](https://www.python.org/downloads/).

*Be careful to download the right version, i.e at least a Python 3 version !*

Install the software.

##### Anaconda

Download Anaconda for Python 3.11 from [this page](https://www.anaconda.com/products/individual) and install the software.

Create an environment for this class

```shell
conda create --name pse python=3.11
```

#### Install additional packages.

Open a console/terminal/command tool on your computer and type:

```shell
pip install matplotlib jupyter
```

or if you use Anaconda

```shell
activate pse
conda install matplotlib jupyter
```

- Install the survey capabilities of openfisca-senegal:
  
```
pip install openfisca-senegal[survey]
```

You should be able to use Jupyter Notebook wich is now installed on your computer.

```
jupyter notebook
```

<!-- #### Troubleshouting on Microsoft Windows systems:

If the command

```
pip install jupyter matplolib
```

does not install the packages, you should try the following steps:
  - Add the Python `Scripts` directory (it looks like `C:\Python39\Scripts`) to your `PATH`
  - Type the command
```
python -m pip install jupyter matplotlib
```
  - If  you get an SSL certificate error
```
python -m pip install --index-url=http://pypi.python.org/simple/ --trusted-host pypi.python.org jupyter matplotlib
``` -->

#### Worst case scenario

Nothing works, try the launch binder badges whenever it appears below.


### Take the Python crash course (*required*)

#### Get familiar with the notebook

It is required to read [this excellent introduction to the notebook](http://nbviewer.jupyter.org/github/ipython-books/minibook-2nd-code/blob/master/chapter1/13-nbui.ipynb).

#### Learn some Python

It is required to read and try to execute [this introductory notebook to the Python langage](http://nbviewer.jupyter.org/github/ipython-books/minibook-2nd-code/blob/master/chapter1/14-python.ipynb). [![Binder](https://mybinder.org/badge_logo.svg)](https://mybinder.org/v2/gh/sylvainipp/pse-micro-simulations-and-public-policies.git/master?labpath=notebooks%2F14-python.ipynb)


You can also have a look at one of these Python tutorials:

- [The official learn Python tutorial]( https://www.learnpython.org/)

- [Learn Python in 10 minutes](https://www.stavros.io/tutorials/python/)

- [Learn Python in Y minutes](https://learnxinyminutes.com/docs/python/)

### Load the following notebooks for the first session

- [Python crash course with exercises](./notebooks/python_crash_course_student.ipynb). [![Binder](https://mybinder.org/badge_logo.svg)](https://mybinder.org/v2/gh/sylvainipp/pse-micro-simulations-and-public-policies.git/master?labpath=notebooks%2Fpython_crash_course_student.ipynb)

- [Numpy and pandas](./notebooks/numpy-and-pandas.ipynb). [![Binder](https://mybinder.org/badge_logo.svg)](https://mybinder.org/v2/gh/sylvainipp/pse-micro-simulations-and-public-policies/HEAD?labpath=notebooks%2Fnumpy-and-pandas.ipynb)


- [Explore the Senegalese tax and benefits system](./notebooks/Senegal-student.ipynb). [![Binder](https://mybinder.org/badge_logo.svg)](https://mybinder.org/v2/gh/sylvainipp/pse-micro-simulations-and-public-policies.git/master?labpath=notebooks%2FSenegal-student.ipynb)


## Before second session

<!--- [Complete the exploration of the Senegalese tax and benefits system by coding a loop for the gain of having one more child depending on the income for different number of children](./notebooks/Senegal-student.ipynb). [![Binder](https://mybinder.org/badge_logo.svg)](https://mybinder.org/v2/gh/sylvainipp/pse-micro-simulations-and-public-policies.git/master?labpath=notebooks%2FSenegal-student.ipynb)

- [You can look at the correction of the first part of the notebook (Warning, I included the last loop, try not to use it while searching !)](./notebooks/Senegal-exercices-solutions1.ipynb).
-->


- We will manipulate [dataframes](http://pandas.pydata.org/): learn how to use them by having a look at this [introduction](http://pandas.pydata.org/pandas-docs/stable/10min.html)

- Download the [the second session notebook](./notebooks/Fake-data-Senegal.ipynb). [![Binder](https://mybinder.org/badge_logo.svg)](https://mybinder.org/v2/gh/sylvainipp/pse-micro-simulations-and-public-policies.git/master?labpath=notebooks%2FFake-data-Senegal.ipynb)


<!--
## After the second session:

You now have access to the complete notebooks with exercise solutions
 - Download the [the first session notebook with exercises solutions](./notebooks/Senegal-exercices-solutions.ipynb). [![Binder](https://mybinder.org/badge_logo.svg)](https://mybinder.org/v2/gh/sylvainipp/pse-micro-simulations-and-public-policies.git/master?labpath=notebooks%2FSenegal-exercices-solutions.ipynb)


 - Download the [the second session notebook with exercises solutions](./notebooks/Fake-data-Senegal-Correction.ipynb). [![Binder](https://mybinder.org/badge_logo.svg)](https://mybinder.org/v2/gh/sylvainipp/pse-micro-simulations-and-public-policies/HEAD?labpath=notebooks%2FFake-data-Senegal-Correction.ipynb)
-->
