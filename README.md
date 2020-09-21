### Object-Detection (MobileNet and MobileNet SSD)

In this [notebook](https://github.com/A2Amir/Object-Detection--MobileNet-and-MobileNetSSD-/blob/master/Object%20Detection%20(MobileNet%20and%20MobileNet%20SSD).ipynb):

* Learn about *MobileNets* and separable depthwise convolutions.
* The SSD (Single Shot Detection) architecture used for object detection
* Use pretrained TensorFlow object detection inference models to detect objects
* Use different architectures and weigh the tradeoffs.
* Apply an object detection pipeline to a video.


### Applied object detection pipeline to a video

<img src="./assets/1.gif" />

### Requirements

Install environment with [Anaconda](https://www.continuum.io/downloads):

```sh
conda env create -f environment.yml
```

Change TensorFlow pip installation from `tensorflow-gpu` to `tensorflow` if you don't have a GPU available.

The environment should be listed via `conda info --envs`:

```sh
# conda environments:
#
carnd-advdl-odlab        /usr/local/anaconda3/envs/carnd-advdl-odlab
root                  *  /usr/local/anaconda3
```

Further documentation on [working with Anaconda environments](https://conda.io/docs/using/envs.html#managing-environments). 

Particularly useful sections:

* https://conda.io/docs/using/envs.html#change-environments-activate-deactivate
* https://conda.io/docs/using/envs.html#remove-an-environment



### Resources


* TensorFlow object detection [model zoo](https://github.com/tensorflow/models/blob/master/research/object_detection/g3doc/detection_model_zoo.md)
* [Udacity](https://www.googleadservices.com/pagead/aclk?sa=L&ai=DChcSEwiakvGY7oLoAhVE-VEKHRTwDvgYABAAGgJ3cw&ohost=www.google.com&cid=CAASEuRoxDWu_76j2oNRAn6sQGxq2w&sig=AOD64_0PJ1T_DEbslELxkiZZ8vnegkKO5Q&q=&ved=2ahUKEwia8-qY7oLoAhWJzaQKHZXODF4Q0Qx6BAgbEAE&adurl=)

