README-python.md

https://glyph.twistedmatrix.com/2016/08/attrs.html

Poetry
https://dev.to/bowmanjd/python-tools-for-managing-virtual-environments-3bko#poetry

https://github.com/pathbird/poetry-kernel


# python powered shell & CLI
https://github.com/google/python-fire
https://github.com/microsoft/knack
https://github.com/Andarius/piou
https://xon.sh/


# packaging
* virtualenv
* pipx
* poetry
  - https://dev.to/bowmanjd/python-tools-for-managing-virtual-environments-3bko
  - curl -sSL https://raw.githubusercontent.com/python-poetry/poetry/master/get-poetry.py | python -
  - https://dev.to/bowmanjd/getting-started-with-python-poetry-3ica
 
 
  - poetry self update
  - poetry completions bash > /etc/bash_completion.d/poetry.bash-completion
  - poetry new --name disc0rd --src candib0t
  - poetry new --name hackern3ws --src .
  - poetry add 



# documentation
https://pdoc.dev/

# openai/pytorch
https://openai.com/blog/openai-pytorch/
https://github.com/jina-ai
  * NLU
    https://arxiv.org/abs/2003.07082
  * eye tracking
    https://www.pygaze.org/

# RUST, wasm, javascript
https://pyodide.org/en/stable/
http://saidvandeklundert.net/learn/2021-11-18-calling-rust-from-python-using-pyo3/

# date & time & data classes:
https://pypi.org/project/koda/
https://github.com/mvrozanti/dte
https://github.com/dabeaz/dataklasses

# dataflow
https://www.trymito.io/
https://streamz.readthedocs.io/en/latest/index.html
https://fastapi.tiangolo.com/
https://github.com/stitchfix/hamilton (DAGS)

# bioinformatics
https://seq-lang.org/

# whatsapp
https://www.trymito.io/

# gui
https://docs.beeware.org/en/latest/

-----

# mostly just articles I need to review/incorporate
* operators & lambda
  = https://martinheinz.dev/blog/54
  Typing, debugging.
  https://martinheinz.dev/blog/67

https://blog.guilatrova.dev/handling-exceptions-in-python-like-a-pro/

https://github.com/chriskiehl/Gooey


Filesystem Spec (FSSPEC) is a project to unify various projects and classes to work with remote filesystems and file-system-like abstractions using a standard pythonic interface.

https://filesystem-spec.readthedocs.io/en/latest/index.html#


...

# https://docs.anaconda.com/anaconda/user-guide/tasks/docker/
docker pull continuumio/miniconda3

docker run -t -i continuumio/miniconda3 /bin/bash

docker run -d -it --name gptx -p 8888:8888/tcp --mount type=bind,source="/home/brianh/gpt-neox",target="/gptx" continuumio/miniconda3

/opt/conda/bin/conda install jupyter -y --quiet && 
mkdir /opt/notebooks
/opt/conda/bin/jupyter notebook \
--notebook-dir=/opt/notebooks --ip='*' --port=8888 \
--no-browser --allow-root

## this is in /gptx
git clone https://github.com/EleutherAI/gpt-neox.git


docker run -i -t -p 8888:8888 continuumio/miniconda3 /bin/bash \
-c "/opt/conda/bin/conda install jupyter -y --quiet && mkdir \
/opt/notebooks && /opt/conda/bin/jupyter notebook \
--notebook-dir=/opt/notebooks --ip='*' --port=8888 \
--no-browser --allow-root"

pip install torch

####
# https://docs.nvidia.com/datacenter/cloud-native/container-toolkit/install-guide.html
curl https://get.docker.com | sh \
  && sudo systemctl --now enable docker

docker build -t gpt-neox -f Dockerfile .
nvidia-docker run --rm -it -e NVIDIA_VISIBLE_DEVICES=0,1,2,3 --shm-size=1g --ulimit memlock=-1 --mount type=bind,src=$PWD,dst=/gpt-neox gpt-neox



# rust
matruin build and publish cretes with pyo3 rust-cpython and cffi bindings as well as rust binaries as python packages
zero config. replacement for setuptools-rust and milksnake
https://github.com/PyO3/maturin

writing and publishing a python module in rust
https://blog.yossarian.net/2020/08/02/Writing-and-publishing-a-python-module-in-rust
