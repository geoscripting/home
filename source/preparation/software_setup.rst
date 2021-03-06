Software Setup
###############

This page contains all software that we are going to need for the course. Please make sure that all software is installed and working on your computer.

Python
*******

Download and install `Anaconda <https://www.anaconda.com/products/individual>`_. You may also use virtualenv or the like if you prefer, but I recommend Anaconda.

Python Environment
===================

If you are using Anaconda, open the Anaconda prompt and execute the commands below to set up a new environment called *advgeo*

**1. Create a new virtual Python environment.**

::

  $ conda create -n advgeo python=3

**2. Install all required Python packages** listed in :download:`requirements.txt <../_static/requirements.txt>`. Remember to activate your environment before installing the packages.

::

  $ conda activate advgeo
  $ conda install --file requirements.txt


Python IDEs
===================

An IDE (Integrated Development Environments) is basically a text editor with a lot of additional functionalities (e.g. syntax highlighting, automated code completion) which make writing code easier and faster. During this course we will use PyCharm and Jupyter Notebooks.

PyCharm
----------

I recommend applying for a `free student license <https://www.jetbrains.com/community/education/#students>`_, which let's you use the PyCharm Professional Edition for free. Compared to the PyCharm Community Edition (which is free for everyone), the Professional Edition provides a few more useful tools for scientific programming. (e.g. viewing plots)

.. image:: ../_static/images/pycharm.png
  :width: 750
  :align: center
  :alt: pycharm home screen

**Configure Python Environment in PyCharm**

1. Open PyCharm and create a new, empty project or open an existing one.
2. Open the project preferences.
3. Choose the *advgeo* environment as the Project Interpreter.

.. image:: ../_static/images/project_interpreter.png
  :width: 700
  :align: center
  :alt: pycharm project_interpreter

The new environment is probably not shown in the list of available environments within Pycharm. In this case, click on the button marked in the image above and choose "Add". The following window should appear. Select the new anaconda environment and click "OK".

.. image:: ../_static/images/add_conda_env.png
  :width: 600
  :align: center
  :alt: add conda environment to PyCharm

Make sure that you set the new environment also for the Python console within PyCharm.

.. image:: ../_static/images/python_interpreter_console.png
  :width: 700
  :align: center
  :alt: pycharm python interpreter for console


Jupyter Notebook
------------------

During the course we will be working with Jupyter Notebooks. In a nutshell, a Jupyter notebook is basically a combination of an HTML page and a python script. In this way, it can display Python code alongside formatted text, figures and charts. Notebooks are used frequently within scientific computing, because it is great way of explaining what the script is doing.

**Verify installation**

1. We've already installed jupyter notebook using conda above. To check wether it works, start a new jupyter notebook server by executing the following command within the Anaconda prompt.

::

  $ jupyter notebook


A new browser window will open. If you started the jupyter server from within the folder of the preparatory assignment, then it will look like this.

.. image:: ../_static/images/jupyter_start.png
  :width: 750
  :align: center
  :alt: Jupyter notebook home screen

If you get a ``command not found`` message, make sure that the correct Python environment is activated.
To create a new jupyter notebook, click on the drop down menu *New* (top right) and create a new Jupyter Notebook by clicking on *Python 3*.


.. _installgit:

git
*****

git is a version control system which lets you track the changes you or others have made to the files of your project. If you are on Mac OS or Linux, git should already be preinstalled.

git for Windows
================

If you are on Windows, install `git for Windows  <https://git-scm.com/download/win>`_. Please follow this `video tutorial <https://www.youtube.com/watch?v=339AEqk9c-8>`_ in order to choose the right settings during installation.
