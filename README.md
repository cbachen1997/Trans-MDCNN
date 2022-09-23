# Trans-MDCNN

Original Tensorflow implentation of Trans-MDNN: ["Multi-modal fusion of satellite and street-view images for urban village classification based on a dual-branch deep neural network"](https://www.sciencedirect.com/science/article/pii/S0303243422001209)

## Get Started
Install packages with:
```Python
$pip install requirements.txt
```

:warning::warning::warning:
The code was implented 2 years ago when I was not very good at coding. The the *vit_b16option* used in **main.py** is not a official implentation. I modified it from the source code of the **vit_keras** dependency package on [PyPI:vit-keras](https://pypi.org/project/vit-keras/), so installing the dependency package directly from *requirments.txt* will results in an undefined function error. I have provided the modified version of the source code, please overwrite it in conda/envs/**your_environment**/lib
