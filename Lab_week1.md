# Lab 1
## Setting up environment

### Anaconda

To begin, you need to set up the environment with python. We will use Anaconda, an environment manager for it.

* [MAC]: (https://www.datacamp.com/community/tutorials/installing-anaconda-mac-os-x )

* [WINDOWS]: (https://medium.com/@GalarnykMichael/install-python-on-windows-anaconda-c63c7c3d1444 )


### Unix

We will use Unix commands for Navigating directories, installing packages and libraries, copying and checking files, etc. 

* [MAC]: MAC comes with a Unix shell, so no need to install anything. (A tutorial for basic commands: https://faculty1.coloradocollege.edu/~sburns/UnixTutorial/unix1.html)

* [WINDOWS]: To use unix commands on Windows, follow this (https://www.howtogeek.com/249966/how-to-install-and-use-the-linux-bash-shell-on-windows-10/)


### Git

Git is a version control system that is often used to record changes to a file or set of files over time so that you can recall specific versions later. 

* To set up Git on you computer: (https://git-scm.com/downloads)
* To learn Github usage: (https://docs.github.com/en/github/getting-started-with-github/set-up-git)


### Jupyter notebook

We will use Jupyter notebooks for our exercises in this course. Jupyter offers both text and coding elements for machine learning and data analysis puposes.

* To know how to use Jupyter: (https://www.datacamp.com/community/tutorials/tutorial-jupyter-notebook)


** Note 1: We recommend using Python3 for all your installation of packages. Ensure you are using Python3, as Python2 is no longer supported.

** Note 2: 
We recommend using a virtual conda anvironment for this class using : 
`conda create -n <your_environment_name> python=3.7'`

to activate the environment: `conda activate <your_environment_name>`

* Follow this for more details on virtual environment: (https://docs.conda.io/projects/conda/en/latest/user-guide/tasks/manage-environments.html)



## Exercises

### Instructions: 

- Lab 1 consists of 10 questions. 

- In session 1, you will work on the first 5 problems, and in session 2, you will work on the last 5 problems. 

- Once completed, you will submit your exercises as jupyter notebooks (as a .ipynb file) through e-mail at 'tahiya.chowdhury@rutgers.edu' for grading.

- In the e-mail, use subject line: `CPSML: Week X`, where X represents the week.

- Both the jupyter notebook and e-mail should contain your name in English.



### 1. Print 'Hello World'

- Run `print("Machine Learning")` in a jupyter cell. 
- Replace 'Machine Learning' with 'Hello World'.
- Now declare a variable `my_text` with some text in the value. Print the variable.


### 2. Declare 2 variables `x` and `y` with values `20` and `4`.

- Add them (`x+y`). Print the result.
- Subtract them (`x-y`). Print the result.
- Multiply them (`x*y`). Print the result.
- Exponentiate x with power of 2 and and y with power of 3. Print the result.


### 3. Declare a list of 5 animals: `['cat', 'dog', 'monkey', 'bird', 'turtle']`

- Print the elements in the list using a for loop.


### 4. Create a python list with list elements from 1 to 15

- Print all list elements.
- Print elements from 5th to last position.
- Print the last element.
- Print the squared value of every 3rd of the elements.


### 5. Consider the string: `www.google.com`. 

- Calculate the length of the string and print it.


### 6. Consider the string: `www.google.com`. 
  
  - Count the number of times each character appear (character frequency) in the string. Print in this format `{ 'o': 3, .......}`.


### 7. Consider two strings `Bill` and `Fox`. 

- Create a single string from the two given strings, separated by a space and swap the first two characters of each string. Print the result.


### 8. Consider the string `Caterpiller`.

- remove all occurence of `er` from the string. Print the result.
- remove the n-th index character from the original string, where n = 3, 6, 9. print the result in all 3 cases.


### 9. Consider this comma seperated sequence of words: `['breakfast', 'towel', 'noon', 'magical', 'profession']`

 - take this sequence of words as input and print the length of the longest word.


### 10. Consider the sentence `the quick brown fox jumps over the lazy dog`

- Count the occurrences of each word in the sentence. Print the result.




