# CS492_Project_Team26


### Team 26: Nikolai Kurlovich


## Installation

1. Clone this repository

    ```bash
    git clone https://github.com/ashnvael/FProject_Team26.git
    ```

2. ALso in addition to the standard packages please install those 

    ```bash
    pip install tensorflow
    pip install keras-tcn
    pip install ray['rllib']
    pip install nengolib
    pip install keras-tcn
    ```

3. ***IMPORTANT: In the source files of ```ray['rllib']``` just installed, please replace ```ray/rllib/models/modelv2.py``` by the ```modelv2.py``` file contained in this project. This file fixes (supposedly) a bug in one of the RLLIB functions.***

## File Descriptions:

Jupyter Notebooks are named after the section of the paper their results appear in. 

1. Part 1 - In this part we build a DRL agent and provide it with 2 NN models.

2. Part 2 - In this part we label the data and build several models aimed to generate features. 

3. Part 3 - In this part we were supposed to extract the features and feed them into the model. The first part shows how to load weights and extract the features. However, due to ineer intricacies of RLLIB I failed to make RLLIB accept the extracted features, and so this section is left without significant results. 

To run evaluations, use the Jupyter notebooks containing ```eval``` in their names.
