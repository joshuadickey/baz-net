# baz-net
A Deep Neural Network for Confident Three-component Backazimuth Prediction

# Setup the Environment:

### _Creating the Python Environment:_

_Ensure that Anaconda is installed on your system, then create a new conda virtual environment named __SeisTF2__, and activate it:_

    conda create -n SeisTF2

    conda activate SeisTF2
    
    

_Next, install the basic anaconda packages, geoscience packages, xgboost and gpu acceleration packages:_

    conda install -c anaconda anaconda
    
    conda install -c conda-forge obspy cartopy geographiclib
    
    conda install -c conda-forge xgboost eli5
    
    conda install cudnn cupti cudatoolkit=10.0
    
    

_Finally, use pip to install tensorflow 2.0 with gpu support:_

    pip install tensorflow-gpu
    
    
### _Running the Notebook:_

_Save the contents of this git repository to your local computer, open a terminal in the folder where it resides, then type the following:_

    conda activate SeisTF2
    
    jupyter notebook
    
_Your web browser should now open to show the contents of the folder from which you activated the notebook. Simply click on the __BazNet.ipynb__ file and the notebook should open._
