## Demonstration

<!DOCTYPE html><html><body>
<iframe src="https://drive.google.com/file/d/1x_zV01n-ljWfHhH3gGzmYHVVbGZhNbh6/preview" width="640" height="480"></iframe>
</body></html>

## Tech used
- [OpenCV](https://opencv.org/)
- [Caffe-based face detector](https://caffe.berkeleyvision.org/)
- [Keras](https://keras.io/)
- [TensorFlow](https://www.tensorflow.org/)
- [MobileNetV2](https://arxiv.org/abs/1801.04381)

## Dataset
This dataset consists of __4095 images__ belonging to two classes:
*	__with_mask: 2165 images__
*	__without_mask: 1930 images__

The images used were real images of faces wearing masks. The images were collected from the following sources:

* __Bing Search API__
* __Kaggle datasets__
* __RMFD dataset__

## Prerequisites

All the dependencies and required libraries are included in the file <code>requirements.txt</code>



## Installation and running

1. Clone the repo
```
$ git clone git@gl.mazars.ru:knowledge-base/mask_det.git
```

2. Change your directory to the cloned repo
```
$ cd mask_det
```

3. Create a Python virtual environment named 'test' and activate it
```
$ virtualenv test
```
```
$ source test/bin/activate
```

4. Run the following command in your Terminal/Command Prompt to install the libraries required
```
$ pip3 install -r requirements.txt
```

5. To detect face masks in real-time video streams type the following command:

```
$ python3 mask_det_video.py
```
