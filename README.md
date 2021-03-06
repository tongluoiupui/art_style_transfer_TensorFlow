# Art Style Transfer

[![Build Status](https://travis-ci.org/conan7882/art_style_transfer_TensorFlow.svg?branch=master)](https://travis-ci.org/conan7882/art_style_transfer_TensorFlow)
[![Coverage Status](https://coveralls.io/repos/github/conan7882/art_style_transfer_TensorFlow/badge.svg?branch=master)](https://coveralls.io/github/conan7882/art_style_transfer_TensorFlow?branch=master)

- This repository contains implementations of art style transfer algorithms in recent papers.
- The source code in the repository can be used to demostrate the algorithms as well as test on your own data.

## Requirements
- Python 3.3+
- [Tensorflow 1.3](https://www.tensorflow.org/)
- [TensorCV](https://github.com/conan7882/DeepVision-tensorflow) 


## Algorithms 

- [Neural Style](https://github.com/conan7882/art_style_transfer_TensorFlow/tree/master/nerual_style#neural-style) (2015)


## Neural Style

- This algorithm combines two images (content and style image) by using content and style features extracted from a pre-trained CNN (ex. VGG).
- The stylized image is generated by minimizing the difference of content and style features between a random noise image and input images. 
- Details of the implementation and more results can be find [here](https://github.com/conan7882/art_style_transfer_TensorFlow/tree/master/nerual_style). Some results:

<p align = 'center'>
<img src ="nerual_style/fig/cat.png" height="300px" />
<a href = 'nerual_style/fig/chong.jpg'><img src ="nerual_style/fig/chong_s.png" height="300px" /></a>
<img src ="nerual_style/fig/cat_chong.png" height="300px" />
</p>

