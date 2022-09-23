# Trans-MDCNN

Original Tensorflow implentation of [Trans-MDNN](https://www.sciencedirect.com/science/article/pii/S0303243422001209)

## Get Started
Install packages with:
```Python
$pip install requirements.txt
```

:warning::warning::warning:  

The code was implented 2 years ago when I was not very good at coding. The the *vit_b16option* used in **main.py** is not a official implentation. I modified it from the source code of the **vit_keras** dependency package on [PyPI:vit-keras](https://pypi.org/project/vit-keras/), so installing the dependency package directly from *requirments.txt* will results in an undefined function error.   

I have provided the modified version of the source code, please overwrite it in conda/envs/**your_environment**/lib

## Note
>1. The final results in the paper are average of the results of 5 training from scratch and random initialization was used each time, so there is no specific number of random seed. In order to ensure that the reimplementation gets similar results as much as possible, we suggest to take the same training strategy.
>2. Due to limited knowledge, the environment where the code was run has not been made into a docker image, so if you have any problems while trying to compile it, please feel free to contact with me.
>3. This is my early work during my master's degree and done in jupyter, so the code is not elegant and seems very long, it may take some time to read and understand the code.
