
[![forthebadge made-with-python](http://ForTheBadge.com/images/badges/made-with-python.svg)](https://www.python.org/)

# cnn-pruning-status_200

# Authors
- [Alok Kumar]
- [Ritvika Pillai]
- [Siddharth Raman]

## Steps to run the Project

1. Clone the project using ````https://github.com/cs532-2021-fall/cnn-pruning-status_200.git```` or download the zip file to your local machine.
2. Downloads all the pre-trained models from the drive link    [pretrained models](https://drive.google.com/drive/u/1/folders/1shjh5fCQ_UZZuVOVNWs9xv8i1w5PWMaZ).
3. Unzip the downloaded file which will give you a folder named **state_dicts**. This folder contains all the pre-trained models including original unpruned models and pruned models with different sparsity ratios. If downloading went right then you should be able to 7 pre-trained models in this folder, 6 pruned models for various sparsity ratio,s and one unpruned original model.
4. Place this folder inside **cifar10_models** directory which is present at the project root level.
5. Upload the whole project to your google drive so that it can be accessed from colab
6. To Evaluate the pruned models and generate all the results shown in the result section you just need to run the following two notebooks **Validate_iterative_pruning.ipynb** and **validate_one_shot_pruning.ipynb**

## Architecture of the System.

Please follow the [documentation](https://github.com/cs532-2021-fall/cnn-pruning-status_200/blob/main/Project2_documentation.pdf) provided to understand the architecture of the system.

