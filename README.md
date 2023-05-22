# baz-net
A Deep Neural Network for Confident Three-component Backazimuth Prediction

# Setup the Environment:

_Save the contents of this git repository to your local computer, open a terminal in the folder where it resides, then follow the instructions below:_

### _Use CONDA to create the Python Environment:_

_Ensure that Anaconda is installed on your system, then create a new conda virtual environment named __BazEnv__, and activate it:_

    conda env create -f environment.yml

    conda activate BazEnv
    
    
### _Use VENV to create the Python Environment:_

_Ensure that venv is installed on your system, then create a new virtual environment:_

    python3 -m venv env

    python3 -m pip install -r requirements.txt
    
    
# Running the Notebook:

_Open a terminal in the folder where you saved this repository, activate your env created above, then type the following:_
    
    jupyter notebook
    
_Your web browser should now open to show the contents of the folder from which you activated the notebook. Simply click on the __BazNet.ipynb__ file and the notebook should open._
