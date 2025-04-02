# EulerCharacteristicTransform_Tutorial
This repository contains tutorial of how to compute and use the euler characteristic (EC), the euler characteristic curve (ECC), and the euler characteristic transform (ECT) in python.


## Usage

1) Clone this repository:

```bash
git clone https://github.com/victosdur77/EulerCharacteristicTransform_Tutorial.git
```

2) Create a virtual environment (it has been developed specifically using Python3.10.11):

```bash
virtualenv -p python env
```

3) Activate the virtual environment:

```bash
env\Scripts\activate
```

4) Install the neccesary dependencies for compute the euler characteristic (EC), the euler characteristic curve (ECC), and the euler characteristic transform (ECT). There are different librarys for it:

- "ect". You can find the documentation [here](https://munchlab.github.io/ect). To install it:

```bash
pip install ect
```

- "dect". You can find the documentation [here](https://aidos.group/dect/dect.html). This is a differentiable version of ECT, and is connected with Pytorch framework To install it: 

```bash
pip install git+https://github.com/aidos-lab/dect.git #  require an up-to-date installation of PyTorch, either with (pip install torch torchvision torchaudio --index-url https://download.pytorch.org/whl/cu126) or without (pip install torch) CUDA support: 
```

- "demeter". You can find the documentation [here](https://github.com/amezqui3/demeter). This is a python package to quickly compute the ECC of any given grayscale image in linear time with respect to its number of pixels. To install it:

```bash
git clone https://github.com/amezqui3/demeter/
cd demeter
pip install -e . # it requires the following dependencies to work then in experiments: matplotlib numpy scipy tifffile 
```


Remember to install ipykernel to use the kernel of the created virtual environment:
```bash
pip install ipykernel
```

## Repository structure

- ect: Tutorial about the use of "ect" library.

- dect: Tutorial about the use of "dect" library.

- demeter: Tutorial about the use of "demeter" library.