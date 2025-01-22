# Boston House Pricing Prediction

# 1. Software And Tools Requirements

a. Github Account
b. HerokuAccount
c. VSCodeIDE
d. GitCLI

# 2. Create new env 

conda create -p venv python==3.7 -y 

if the above command did not work then use below commands and check the compatibility accordingly

conda update -n base -c defaults conda
conda search python --channel conda-forge
CONDA_SUBDIR=osx-64 conda create -p venv python=3.7 -y -c conda-forge

# 3. Activate the env

conda activate venv/

# 4. Create requirements.txt file and run it

pip install -r requirements.txt
