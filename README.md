# C-vs-TensorFlow
This repository is linked to this video : https://www.youtube.com/watch?v=i2LZBnPCxsU

The video shows both the programs running simuntaneously as shows the result.

C++: minGW
Python: Python 3.5
Tensorflow: Tensorflow GPU

The task is to evaluate the function (root(x) + 523)/5.3 for 10000 inputs, 1000000 times. Total iterations = 10^10

CPU: Intel I7 4th gen
GPU: Nvidia GTX 960m 4GB

Observation: c++ gets effected by gpu! This means mingw uses gpu when available?

Clearly C++ out performs tensorflow.
