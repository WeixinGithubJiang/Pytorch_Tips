# Pytorch Tips

## 1. how to run codes from Github?
> build a new virtual environment

> Most time, the structure of the code is: Dataloader --> Network --> Train/Test. The best option is always not to try to write code from scratch, instead, only change the module that has to be replaced. The is very true, especially for bad coders, like me.


## 2. how to run YOLO3?
> install cython
```bash
conda install -c anaconda cython
```

> install pycocotools
```bash
git clone https://github.com/philferriere/cocoapi.git
pip install git+https://github.com/philferriere/cocoapi.git#subdirectory=PythonAPI
```

> install yaml
```bash
python -m pip install PyYAML
```
