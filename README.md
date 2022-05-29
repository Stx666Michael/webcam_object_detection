# Webcam Object Detection

## Description
This is an implementation of a webcam object detector using [TensorFlow Object Detection API](https://github.com/tensorflow/models/tree/master/research/object_detection), which is able to detect objects **in realtime**.

## Model
`ssd_mobilenet_v1_coco_11_06_2017`

There are other options which can be downloaded [here](https://github.com/tensorflow/models/blob/master/research/object_detection/g3doc/tf2_detection_zoo.md), and store `frozen_inference_graph.pb` in `model/`.

## Instrutions
- Run `python3 main.py`
- Press `Q` to exit

## Screenshots
![screenshots](data/screenshot.png)

## Performance
10-15 FPS using _NVIDIA GeForce GTX 1650_