# SeedGerm-VIG
Jie Dai, Zhenjie Wen, Ji Zhou

## A brief introduction:
Early developmental phases such as seed germination and seedling establishment are key to cereal plants' growth and development as they impact directly on crop performance and yield potential. Hence, it is critical to develop varieties with favourable early growth characteristics under various growing conditions to sustain early crop performance. In this repository, we present SeedGerm-VIG, an automated and comprehensive pipeline developed for assessing seed vigour in wheat and other cereal crops. Building on the SeedGerm system (https://nph.onlinelibrary.wiley.com/doi/full/10.1111/nph.16736), we integrated multiple deep learning models (i.e. YOLOv8x-Germ and optimised U-Net) and computer vision algorithms into the automated seed-level analysis pipeline to identify key germination phases and measure seed-, root-, and seedling-level phenotypic traits. <br>

In the repository, we provide algorithms (in Jupyter notebooks) using time series directed graph to track root tips to measure root emergence during the germination procedure, as well as a new approach to examine speed and uniformity of germination (i.e. seed vigour assessment). The datasets also include 21 commercial wheat genotypes, and 6 rice and 12 barley genotypes.

## The main files are as follows:

### Dataset <br>
(1) The 'SeedVig-phase' dataset for object detection, predicting seed-level germination phases (such as imbibition, protrusion, radicle emergence, and seedling establishment); <br>

(2) The 'SeedVig-traits' dataset for semantic segmentation, predicting masks of seeds without roots and seedling, seeds with roots and seedling, and seedling only.

### Jupyter notebook <br> 
Python-based source code that contains the image pre-processing, the model integration and execution.

### Outputs of the AI model <br> 
(1) The YOLOv8x-Germ model and output results for germination phase detection; <br>

(2) The U-net models and output results for masks of seeds without roots and seedling, seeds with roots and seedling, and seedling only.

### Image series
We also uploaded all the image series used including wheat, rice, and barley, with two example image series (i.e. black_G7, and blue_G2) packaged separately.

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
