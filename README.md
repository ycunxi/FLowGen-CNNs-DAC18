# FLowGen-CNNs-DAC18: 
Demo datasets generated with open source Logic Synthesis framework ABC from UC Berkeley [see https://github.com/berkeley-abc/abc]
Technology: 14nm <br/>
Link to paper: https://ycunxi.github.io/cunxiyu/papers/dac18.pdf

[![license](https://img.shields.io/packagist/l/doctrine/orm.svg)](https://github.com/ycunxi/FLowGen-CNNs-DAC18/blob/master/LICENSE.md)
[![dep1](https://img.shields.io/badge/implementation-tensorflow-orange.svg)](https://www.tensorflow.org/)
[![dep2](https://img.shields.io/badge/python-3.4-red.svg)](https://www.python.org/download/releases/3.4/)

## Requirements

- Python 2.7/3.x
- [Tensorflow] backend
- [Keras] high-level neural networks API
- [pandas, numpy, sklearn, h5py] 
- [matplotlib] plot



# FLowGen-CNNs-DAC18
## Contents
### ABC Random flows
/datasets/abc_100k_random_flows.rc
### Datasets
64-bit Montegomery Multiplier datasets (csv format): datasets/64bitGF/delay/ <br/>
For example: rw; rw; rf; rfz; b; rf; b; rw; rfz; rs -K 6; b; rf; b; rs -K 6; rwz; rfz; rs -K 6; rw; rwz; rwz; rf; rwz; rfz; rs -K 6<br/>
Note: please always start with "strash" ("st") before applying the random flows.<br/>
### Demo Code
./dac18_keras_implementation.ipynb (keras implementation)
## Reference
*Developing Synthesis Flows without Human Knowledge.* Cunxi Yu, Houping Xiao and Giovanni De Micheli<br/>
ACM/IEEE Design Automation Conference (DAC'18)<br/>

## Contact
Cunxi Yu.<br/>
Email: cunxi.yu@epfl.ch<br/>
