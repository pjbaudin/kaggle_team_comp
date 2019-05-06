# kaggle_team_comp
ML for Kaggle competition

# Conda commands

Open an Anaconda Prompt

Create environment with python verion 3.6
`conda create --name <name of env> python=3.6`

List current environment
`conda info --envs`

Activate environment
`conda activate <name of env>`

List packages
`conda list`

Export environment
`conda env export | grep -v "^prefix: " > environment.yml`

Create an environment from requirement.txt
`conda env create -f environment.yml`