Portable Environments
=========================


### Conda

Problem exporting yaml file in linux to use in macos: ResolvePackageNotFound problem

Faster solution: recreate env with seme packages:

```bash
conda config --add channels conda-forge
conda create -n env_ga_mac
conda activate env_ga_mac
conda install numpy matplotlib pandas scikit-learn
conda install jupyter
conda install scipy
conda install pygmo
```
