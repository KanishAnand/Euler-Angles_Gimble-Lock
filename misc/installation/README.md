 We highly recommend using anaconda distribution or at the minimum, virtual environments for this assignment. Goes without saying: please use Python3 for the entirety of this course.

# Setting up Anaconda environment (Recommended)
1. Install Anaconda or Miniconda from [here](https://docs.conda.io/projects/conda/en/latest/user-guide/install/linux.html) depending on your requirements.
2. Now simply run `conda env create -f environment.yml` in the current folder to create an environment `mr_assignment1`.
3. Activate it using `conda activate mr_assignment1`.

# Setting up Virtual environment using venv
Please prefer using the above method over this:
1. Run `sudo apt-get install python3-venv` from command line.
2. `python3 -m venv ~/virtual_env/mr_assignment1`.
3. `source ~/virtual_env/mr_assignment1/bin/activate`
4. `pip3 install -r requirements.txt` from the current folder.
