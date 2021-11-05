# Deep Learning and Computer Vision Project

## Team

* Hiesl, Oliver
* Kniplitsch, Thomas
* Niedermayr, Lisa

## How to run

* open PowerShell
* navigate to ./jupyter/
* execute command
  ```
  docker run --rm -it --name tensorflow -p 8888:8888 -p 6006:6006 -v ${PWD}:/tf/notebooks tensorflow/tensorflow:2.6.0-jupyter
  ```
* open the printed URL with a browser
  * URL should look something like this:
    http://127.0.0.1:8888/?token=d81337b6fc0b04ecd4f26052b2252850051ddf00d18a8fb7
