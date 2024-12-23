# SeedGerm-VIG
Jie Dai, Zhenjie Wen, Ji Zhou

## The main files are as follows:

### Dataset <br>
(1) The 'SeedVig-phase' dataset for object detection, predicting seed-level germination phases (such as imbibition, protrusion, radicle emergence, and seedling establishment); <br>

(2) The 'SeedVig-traits' dataset for semantic segmentation, predicting masks of seeds without roots and seedling, seeds with roots and seedling, and seedling only.

### Jupyter notebook <br> 
Python-based source code that contains the image pre-processing, the model integration and execution.

### Outputs of the AI model <br> 
(1) The YOLOv8s-germ model and output results for germination phase detection; <br>

(2) The U-net models and output results for masks of seeds without roots and seedling, seeds with roots and seedling, and seedling only.

We also uploaded two example image series.

## To install Python, Anaconda and Libraries If you wish to run from the source code provided in this project, you will need to set up Python on your system.

• Read the beginner’s guide to Python if you are new to the language: https://wiki.python.org/moin/BeginnersGuide

• For Windows users, Python 3 release can be downloaded via: https://www.python.org/downloads/windows/

• To install Anaconda Python distribution:

Read the install instruction using the URL: https://docs.continuum.io/anaconda/install <br>
For Windows users, a detailed step-by-step installation guide can be found via: https://docs.continuum.io/anaconda/install/windows <br>
An Anaconda Graphical installer can be found via: https://www.continuum.io/downloads <br>

We recommend users install the latest Anaconda Python distribution

## Some dependencies of the Jupyter notebooks: <br>
TensorFlow = 2.2; <br>
Scikit-image = 0.19; <br>
Matplotlib = 3.5.1; <br>
Pandas = 1.4.2; <br>
Numpy = 1.22.4; <br>
Scipy = 1.7.3; <br>
ultralytics = 8.1.9; <br>
PyTorch = 1.9.0;
