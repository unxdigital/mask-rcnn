# Mask-RCNN and Tensorflow

[![N|Solid](https://res.cloudinary.com/dlvaangxn/image/upload/c_scale,w_150/v1563630297/unx-logo.png)](https://www.unxdigital.com/)

![CircleCI](https://circleci.com/gh/google/wikiloop-battlefield/tree/master.svg?style=svg)

Implement Real-Time Semantic Segmentation with [Mask_RCNN](https://github.com/matterport/Mask_RCNN).

![multi-face-result](https://raw.githubusercontent.com/unx-digital/Age-Gender-CNN-TensorFlow/master/images/multiple-faces-result.png)

## DEPENDENCIES
This project has following dependencies and tested under OSX with Python 3.5. We use [virtualenv](https://virtualenv.pypa.io/en/latest/) to play safely with multiple Python versions.

- Python 3.5
- Tensorflow 1.8
- Keras 2.1.6
- OpenCV 3.4

```bash
$ pip install -r requirements.txt
$ pip install git+https://github.com/philferriere/cocoapi.git#subdirectory=PythonAPI
$ wget https://github.com/matterport/Mask_RCNN/releases/download/v2.1/mask_rcnn_balloon.h5
```


## HOW TO USE?

```bash
$ python detector_demo.py {YOUR_TEST_VIDEO}
```


```
MIT License

Copyright (c) [2019] [UNX Digital]
```
×
Drag and Drop
The image will be downloaded by Fatkun