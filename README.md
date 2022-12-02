# Machine-Learning-Group-project(HKU 2022)
NeurGMC:Unsupervised Semantic Segmentation in Neural Radiation Fields </br>
(Junming Wang and Yangqin Jiang)


## Getting Started

For flawless reproduction of our results, the Ubuntu OS 20.04 is recommended. The models have been tested using Python 3.7, Pytorch 1.6.0, CUDA10.1. Higher versions should also perform similarly.
![image](https://user-images.githubusercontent.com/51500826/204769202-183db1f4-906c-4869-807e-e6c2055d7d03.png)
### Dependencies
Main python dependencies are listed below:
- Python >=3.7
- torch>=1.6.0 (integrate *searchsorted* API, otherwise need to use the third party implementation [SearchSorted](https://github.com/aliutkus/torchsearchsorted) )
- cudatoolkit>=10.1

Following packages are used for 3D mesh reconstruction:
- trimesh==3.9.9
- open3d==0.12.0

With Anaconda, you can simply create a virtual environment and install dependencies with CONDA by:
- `conda create -n NeurGMC python=3.7`
- `conda activate NeurGMC`
- `pip3 install -r requirements.txt`

## Datasets
We mainly use [Replica](https://github.com/facebookresearch/Replica-Dataset) datasets for experiments.
