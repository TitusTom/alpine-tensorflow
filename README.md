Alpine Tensorflow Python 2.7 Version
-------------------------------------

Modified version of https://github.com/better/alpine-tensorflow to produce a python 2.7 verion of tensorflow 1.7.0.


Tensorflow 1.7.0  - Python 2.7 Wheel file
------------------------------------------
```
pip install
```

Compile from source
-------------------
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
