## install miniconda
https://docs.conda.io/en/latest/miniconda.html

## setup environment
```
conda create --name sysgen python=3.7
conda activate sysgen
conda install -y numpy scipy matplotlib pandas ipython scikit-learn statsmodels jupyterlab
pip install pandas-plink
pip install limix-lmm
```

## download data
* download https://www.dropbox.com/s/86fdj3i7ir3vap7/ALL.chr22_GRCh38.genotypes.20170504.zip?dl=0
* unzip files

## download notebooks and start tutorial part1
```
git clone git@github.com:fpcasale/IN2344-finemap.git
cd IN2344-finemap
cd notebooks
jupyter lab
```
