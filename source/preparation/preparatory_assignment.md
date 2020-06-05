Advanced Geoscripting  - SS 2020  -  Instructor: Christina Ludwig 

# Preparatory Assignment

Within this assignment you will ...

*  install and configure all required software for the course,
*  read about reproducibility and replicability in science and 
*  learn the basics of version control with git. 

**Attention: Completing this preparatory assignmet is a prerequisite for attending the course!**

## 1. Install and configure required software

Follow the instructions given in the section [Software Setup](./software_setup) to install all required software for the course. Make sure that everything works as described (e.g. importing python packages). If you encounter any problems, create a new topic in the [GitHub forum](https://github.com/orgs/geoscripting/teams/advanced-geoscripting-2020/discussions) and describe your problem. 


## 2. Performing Scientific Analyses

<img src="../_static/images/phdcomic_final.png" alt="final" width="300px" align="right" />
  
Read the paper by [Wilson et al (2014)](https://www.ncbi.nlm.nih.gov/pmc/articles/PMC3886731/) on Best Practices for Scientific Computing and answer the following questions: 

1. The paper describes several problems scientist face when conducting data analyses. From your experience in performing (GIS) analyses, which of these problems seem familiar to you? Did you face other problems not mentioned in the paper? (~100 words)
2. Which methods described in the paper could help you avoid these problems in the future? (~100 words)
3. One of the recommendations by [Wilson et al (2014)](https://www.ncbi.nlm.nih.gov/pmc/articles/PMC3886731/) for scientists is to use a Version Control System (VCS). Briefly explain your own words, what the benefits of VCS are in the context of scientific analyses. (~100 words)

<sup>Image source: “Piled Higher and Deeper” by Jorge Cham, http://www.phdcomics.com</sup> -> 


## 3. Using Version Control with git

In this last section of the assignment, you will learn how to 

* create a new git repository,
* create a new jupyter notebook,
* track your file changes using git and 
* synchronize your changes with GitHub. 

Before you work on the following exercise, work through the [introduction to git](git/index.rst).

### 1. Create a new git repository

1. Create a new directory which will contain your project. 
2. Move inside this directory and create a git repository. 

### 2. Create a new Jupyter notebook

1. Activate the "geoscripting2" environment and start jupyter notebook. 
2. Create a new jupyter notebook using the Python 3 kernel. 
3. Import gdal, do something meaningful and save your notebook

### 3. Track the notebook with git 

1. Create a commit which includes the notebook. 
2. Within the notebook, write a function which adds two numbers together.  
3. Create a new commit containing the changes of the notebook. 
4. Execute ``git log`` to answer the question: How many commits are there? 

### 4. Synchronise your repository with GitHub

1. Create a new repository on GitHub and provide the link in your documentation. __Note:__ Do not initialise the repository with  a README, license or .gitignore file. 
2. Copy the URL of this repository and link it to your local git repository. 
3. Push all your commits to GitHub. 


### Well done, your ready for the course! :) 







