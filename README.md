# DL-1
Hands-on DL

Python 3.10

https://github.com/bourneli/deep-learning-notes/tree/master

#### Install conda windows cli:
curl https://repo.anaconda.com/miniconda/Miniconda3-latest-Windows-x86_64.exe -o miniconda.exe
start /wait "" miniconda.exe /S
del miniconda.exe

conda create -n py310 -y python=3.10
conda activate py310
conda install -y pandas numpy matplotlib ipykernel nltk tensorflow scikit-learn