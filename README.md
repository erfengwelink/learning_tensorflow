# learning_tensorflow
========================

using platform: MACOS

**#1 install anconda2 from https://www.anaconda.com/download/#macos**

**#2 Installing tensorflow with Anaconda**

(terminal cmd input:)
$ conda create -n tensorflow pip python=2.7

**#3 activate tensorflow:**

(terminal cmd input:)
$ source activate tensorflow

**#4 Issue a command of the following format to install TensorFlow inside your conda environment:**

(terminal cmd input:)
$ pip install --ignore-installed --upgrade \
 https://storage.googleapis.com/tensorflow/mac/cpu/tensorflow-1.7.0-py2-none-any.whl
 
if installed ok you will see:

Successfully built gast absl-py termcolor html5lib
Installing collected packages: astor, gast, setuptools, six, protobuf, absl-py, backports.weakref, markdown, futures, werkzeug, html5lib, wheel, numpy, bleach, tensorboard, termcolor, funcsigs, pbr, mock, enum34, grpcio, tensorflow
Successfully installed absl-py-0.2.0 astor-0.6.2 backports.weakref-1.0.post1 bleach-1.5.0 enum34-1.1.6 funcsigs-1.0.2 futures-3.2.0 gast-0.2.0 grpcio-1.11.0 html5lib-0.9999999 markdown-2.6.11 mock-2.0.0 numpy-1.14.2 pbr-4.0.2 protobuf-3.5.2.post1 setuptools-39.0.1 six-1.11.0 tensorboard-1.7.0 tensorflow-1.7.0 termcolor-1.1.0 werkzeug-0.14.1 wheel-0.31.0

**#5 simply programming:**

(terminal cmd input:)
$ python

U will see:
Python 2.7.14 |Anaconda, Inc.| (default, Mar 27 2018, 12:28:59)
[GCC 4.2.1 Compatible Clang 4.0.1 (tags/RELEASE_401/final)] on darwin
Type "help", "copyright", "credits" or "license" for more information.
>>> import tensorflow as tf
>>> tf.__version__
'1.7.0'
>>> exit()


**#6 deactivate tensorflow**

(terminal cmd input:)

(tensorflow) ➜  ~ source deactivate

➜  ~


**next U'd follow my folder "tutorial_codes"'s codes to test/exercise**


![image](https://github.com/erfengwelink/learning_tensorflow/tree/master/img_floder/1.png)

Illustration:
![Image text](https://github.com/erfengwelink/learning_tensorflow/tree/master/img_floder/2.png)