Alpine Tensorflow for Python 2 (2.7)
-------------------------------------

Modified version of https://github.com/better/alpine-tensorflow to produce tensorflow 1.7.0 library for python 2 (2.7).  


Tensorflow 1.7.0  - Python 2 (2.7) Wheel file
------------------------------------------
```
pip install https://github.com/TitusTom/alpine-tensorflow/releases/download/1.0/tensorflow-1.7.0-cp27-cp27mu-linux_x86_64.whl
```

Compile from source
-------------------
This is time intensive.
```
git clone https://github.com/TitusTom/alpine-tensorflow/
cd alpine-tensorflow
sudo docker build .
```

if you need to start the docker service
```
$ sudo systemctl start docker
```
or 

```
sudo service docker start
```
