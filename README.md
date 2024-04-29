## Installation

### Build environment

We recommend a python version >=3.10 and cuda version =11.7. Then build environment as follows:

```shell
py -3.10 -m venv venv
venv\Scripts\activate.bat
set PYTHONUTF8=1

python -m pip install --upgrade pip setuptools
pip install torch torchvision torchaudio --extra-index-url https://download.pytorch.org/whl/cu118
pip install numpy
pip install scikit-image
pip install pillow
pip install opencv-python
pip install paddlepaddle
pip install paddlehub
pip install gradio
pip install gdown
```

### Download weights

All the weights should be placed under the `./models` direcotry. You can download weights manually as
follows:

1. Download the trained [weights](https://drive.google.com/uc?id=1ao1ovG1Qtx4b7EoskHXmi2E9rp5CHLcZ), which include : `u2net.pth`.

2. Download the trained [weights](https://drive.google.com/uc?id=1IG3HdpcRiDoWNookbncQjeaPN28t90yW), which include : `u2net_portrait.pth`.

