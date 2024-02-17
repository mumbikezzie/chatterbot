# chatterbot

attempting to install chatterbot

## To run the Project

**Setup A virtual Environment**
Virtual environments will allow you to install whichever versions of whichever packages you need for a given project, without messing with my base installation

1. Create a new virtual Environment
   `conda create -n medicbotenv python=3.6`
2. Activate the virtual environment
   `conda activate medicbotenv`
3. For you to run this project in Jupyter Notebook, you need a way to reference this new virtual environment instead if the base environment.

- In your virtual environment, install jupyter
  `conda install jupyter`

4. In your base environment install **nb_conda_kernels**(Just one time) - automatically creates a new kernel for each virtual environment you create - Note for this step you must be in your base env.
   Run `conda activate`

In the above, I choose to use Python 3.6
