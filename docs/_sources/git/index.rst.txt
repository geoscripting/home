Introduction to git
=========================

git is a version control system, which makes it easy to track the changes of your project. The Software Carpentry provides a good introduction to git. So please work through sections 1 to 7 of `the Software Carpentry git tutorial <http://swcarpentry.github.io/git-novice/>`_ to learn the basics of git.

In addition, I have prepared some videos showing you how to access the material of the preparatory assignment through GitHub Classroom and how to submit your solutions using git.

In order to use git you need to have a **GitHub Account** and **git must be installed** on your computer (see :ref:`Software Setup <installgit>`).


1. Accessing the preparatory assignment material through GitHub Classroom
########################

To access the material for the preparatory assignment and to submit your solutions GitHub Classroom will create a GitHub repository for you. This repository is only accessible and visible to you and the teacher.

.. raw:: html

   <p align="center"><iframe width="800" height="450" src="https://www.youtube.com/embed/st7j4x-UxEw" frameborder="0" allow="accelerometer; encrypted-media; gyroscope; picture-in-picture" allowfullscreen></iframe></p>


2. Cloning the repository to your computer
########################

In order to work on the files in the repository and to add new ones, you need to clone the repository to your computer using the following command.

::

  $ git clone https://github.com/geoscripting/preparatory-assignment-hettner.git


.. raw:: html

   <p align="center"><iframe width="800" height="450" src="https://www.youtube.com/embed/yfFbOUnbE1Y" frameborder="0" allow="accelerometer; encrypted-media; gyroscope; picture-in-picture" allowfullscreen></iframe></p>



3. Synchronizing your changes with GitHub
#########################################

When you create or edit files, you can track these changes and synchronise them with the remote repository on GitHub using the following git commands.

::

  $ git add scientific_programming.txt
  $ git commit -m "added scientific_programming.txt"
  $ git push origin master

.. raw:: html

   <p align="center"><iframe width="800" height="450" src="https://www.youtube.com/embed/kVCLIPHfPDo" frameborder="0" allow="accelerometer; encrypted-media; gyroscope; picture-in-picture" allowfullscreen></iframe></p>

4. Submission through GitHub Classroom
#######################################

When we are using GitHub Classroom, creating commits and pushing them to GitHub does not just mean that you are tracking your work progress, it also means that you are automatically submitting your answers to the exercises of the assignment. However, these "submissions" are never final. You can always change your answers and solutions by creating another commit and pushing it to GitHub.

Please remember that GitHub Classroom is not part of git. It is just an application built on top of git to help instructors teach programming to students.


If you have questions please, post it in the `GitHub geoscripting forum <https://github.com/orgs/geoscripting/teams/advanced-geoscripting-2020/discussions>`_ or write an email to `christina.ludwig@uni-heidelberg.de <mailto:christina.ludwig@uni-heidelberg.de>`_.




.. toctree::
   :maxdepth: 1
