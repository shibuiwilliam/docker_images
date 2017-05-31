Docker image for Jupyter Notebook with deep learning libraries on CentOS7, with Python2.7 and Python3.5 available.
Libraries include TensorFlow, Keras and Chainer

In order to start this docker container, run these commands on your docker host.

```
 docker pull shibui/jupyter_deep_learning
 docker run -it -d -p 18888:8888 --name jpdl shibui/jupyter_deep_learning
```

The container will start Jupyter Notebook on http://your ip address:18888 .
There is no authentication to it, so you can start using the Notebook.


Please refer to this github for the dockerfile.

https://github.com/shibuiwilliam/docker_images/upload

Refer to the following for Jupyter Notebook.

http://jupyter.org/

http://jupyter.org/documentation.html


Thanks.
