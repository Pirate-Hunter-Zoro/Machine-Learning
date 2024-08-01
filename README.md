# About
This is a repository containing notebooks and machine learning models using the PyTorch Python library.

## Instructions
To run these notebooks, perform the following tasks, which will include cloning this repository and creating a Python virtual environment containing the libraries necessary for running the notebooks:
1. Navigate to a folder on your command line and run the following command:
   ```git clone https://github.com/Pirate-Hunter-Zoro/Machine-Learning.git```
2. Create a python virtual environment named "machine_learning_new" (or whatever you want to call it) via the following command:
   ```python -m venv machine_learning_new```
3. Activate the virtual environment:
   ```source machine_learning_new\Scripts\activate```
4. Install the necessary Python libraries:
   ```pip install -r requirements.txt```

### Useful Notes
Note that the ".gitignore" file contains instructions for Git to ignore all directories called "machine_learning_venv", because that is the folder I created my Python virtual environment in, which I do not want stored on the local repository.
To write all of the requirements in the Python virtual library into "requirements.txt", run the following command:
```pip freeze > requirements.txt```

## Source
For those curious, I am following an online course:
https://zerotomastery.io/courses/learn-pytorch/