# Task

Collect the code from https://github.com/gabrielgarza/Mask_RCNN, deploy it in production and add tests to it.

# Important files
* [Task.ipynb](Task/Task.ipynb) contains the deployment of the model (using the "coco" weights), along with the tests.

* [results_log.npy](Task/results_log.npy) a log of all of the model's results.

* ([model.py](mrcnn/model.py), [utils.py](mrcnn/utils.py), [config.py](mrcnn/config.py)): These files contain the main Mask RCNN implementation. 

* [Dockerfile](Dockerfile) Contains the commands to build the image necessary to run the code.
