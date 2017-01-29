from tensorflow/tensorflow:latest
MAINTAINER Aaron Zhao (yaz21@cam.ac.uk)
# Get pip to download
RUN pip install matplotlib

WORKDIR /root

COPY pretrain.py /root/pretrain.py
COPY MNIST.data /root/MNIST.data
CMD ["python", "/root/pretrain.py"]
