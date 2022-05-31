README-python.md

mostly just articles I need to review/incorporate

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


