## install miniconda
https://docs.conda.io/en/latest/miniconda.html

## setup environment for linear regression
```
conda create --name sysgen_1 python=3.12
conda activate sysgen_1
conda install -y numpy scipy matplotlib pandas ipython scikit-learn statsmodels jupyterlab
pip install pandas-plink
pip install limix-lmm
```

## setup environment for gwas
```

conda create --name sysgen_2 python=3.9
conda activate sysgen_2
conda install -c conda-forge numpy=1.24 scipy=1.9 pandas matplotlib scikit-learn -y
pip install pandas-plink
pip install limix-lmm

```

## download data
* download https://www.dropbox.com/s/86fdj3i7ir3vap7/ALL.chr22_GRCh38.genotypes.20170504.zip?dl=0
* unzip files

## download notebooks and start tutorial part1
```
git clone https://github.com/fpcasale/IN2344-finemap.git
cd IN2344-finemap
cd notebooks
jupyter lab
```
