Note this implementation works with pytorch=0.4.0 and cuda8.0.
## Create a conda environment

```
conda env create -f csm.yml
source activate csm
```

## Download and install dependecies
```
mkdir sources
pip install -U pip
pip download cupy==2.3.0
tar -xf cupy-2.3.0.tar.gz
cd cupy-2.3.0
python setup.py install
```

## Download & clone the repo
```
git clone https://github.com/nileshkulkarni/csm
"csm"-Hauptverzeichnis umbenennen in csm_root
```


## Download external dependcies
```
cd csm_root/csm/external/
sh install.sh
```

## Install remaining dependencies
```
cd csm_root
pip install -r requirements.txt
```




