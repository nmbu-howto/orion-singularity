Bootstrap: docker
From: tensorflow/tensorflow:latest-gpu-py3
Stage: build

%post
    apt update -y
    apt upgrade -y
    pip install ipython
    pip install scikit-image
    pip install scikit-learn
    pip install mypy
    pip install nptyping

%environment
    export KERAS_MODE=TENSORFLOW
