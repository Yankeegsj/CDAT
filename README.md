# CDAT

## 1. Install anaconda

## 2. Install packages

```
conda create --name CDAT
source activate CDAT
conda install pip
conda install python==3.6.6
pip install torch==1.10.0
pip install numpy==1.19.2 six==1.15.0 pillow==8.0.1
pip install torchvision==0.11.0
pip install pandas==1.1.3 python-dateutil==2.8.1 pytz==2020.1
pip install scipy==1.5.3 opencv-python==4.4.0.44
pip install opencv-python==4.4.0.44 cycler==0.10.0 kiwisolver==1.2.0 matplotlib==3.3.2 pyparsing==2.4.7
pip install bbox==0.9.2 pyquaternion==0.9.9
pip install PyWavelets==1.1.1 decorator==4.4.2 imageio==2.9.0 networkx==2.5 scikit-image==0.17.2 tifffile==2020.9.3
pip install boxx==0.9.2.28 fn==0.4.3 pprofile==2.0.5 py-heat==0.0.6 pyopengl==3.1.5 seaborn==0.11.0 snakeviz==2.1.0 tornado==6.1
pip install cached-property==1.5.2 h5py==3.1.0
```

## 3. Model download

download MAE_92.3_SHA model from [link](https://1drv.ms/u/s!AuOdja6S-tY7g5xowvDG5TFJRO2kyg?e=x2kDWO) 

## 3. File system
```
- CDAT
  - code
    -pre_models
      -SHA_92.3.pth
    - test.py
    - ...
  - data
    - SHA
``` 

## 4. run the code
bash run.sh
