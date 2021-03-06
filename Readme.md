# RoboND Robotic Inference Project

This project is split into two sections. The first one is an inference project for supplied data from  udacity. The second one is for the data collected by students. Each result is documented in the [Writeup.pdf](https://github.com/shotaro12oyama/RoboND-Inference/blob/master/Writeup.md).

## Environment
Used the [Nvidia Digits](https://developer.nvidia.com/digits) Workflow which is provided by NVIDIA.


## Trainning & Evaluation on Supplied Data
In terms of the model, Alexnet is selected with Adam Optimizer.
(The trained model is [here](https://github.com/shotaro12oyama/RoboND-Inference/tree/master/20180605-195054-04e7_epoch_5.0))

![Training Graph](https://github.com/shotaro12oyama/RoboND-Inference/blob/master/IMG/supplied_data_training.png)

The result of evaluation command, which is provided the course, is as follows.  It could pass the criteria provided by the course. (The required inference time of 10 ms on the supplied workspace, and accuracy of 75%.)
![Evaluation Result](https://github.com/shotaro12oyama/RoboND-Inference/blob/master/IMG/evaluation_result.png)
