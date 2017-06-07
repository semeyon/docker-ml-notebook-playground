FROM rlxs/tensorflow:0.12.1-gpu-py3
RUN apt-get update && apt-get install htop net-tools curl
RUN pip3 install --upgrade pip && pip3 install jupyter
ADD code ../code
WORKDIR ../code
CMD ["/bin/bash"]
