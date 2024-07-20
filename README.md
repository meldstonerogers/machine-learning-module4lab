# machine-learning-module4lab
AML Module 4 Lab
Melissa Stone Rogers, July 20, 2024

## Introduction
Professional project to use Jupyter Lab, python, and needed frameworks to build a regression model that will predict weigh based on heigh in the Howell dataset.
Commands were used on a Mac machine running zsh.  

## How to Install and Run the Project
Create project repository in Github and clone to your machine.

```
git clone project.url
```
Verify Python version of Python 3
```
python3 --version

```
```
python3 -m venv venv
source venv/bin/activate
```

Install required packages 
```
pip install jupyterlab pandas matplotlib scikit-learn
python3 -m pip install -U scikit-learn
```

Create requirements.txt in the root project folder. 
```
touch requirements.txt
```
Add the following requirements into requirements.txt:
- jupyterlab 
- pandas
- matplotlib
- sklearn

## Freeze Requirements

```
python3 -m pip freeze > requirements.txt
```

## Add .gitignore File
Add .gitignore file to the root project folder. 
```
touch .gitignore
```
Add the following to your .gitignore file: 
- .venv/
- .vscode/
- .ipynb_checkpoints/

## Initial Project Save
```
git add .
git commit -m "initial"                         
git push origin main
```
### Start and Complete Project 
Copy lab1_starter.ipynb into workspace. Rename it to personalize to your work. Open and begin your project. 

Follow project steps as found in [this PDF](https://github.com/meldstonerogers/machine-learning-module2lab-/blob/main/Lab%20W2%20scikit.pdf).

## Complete Your Project
Save your project and push back to your repository. 
```
git add .
git commit -m "final"                         
git push origin main
```