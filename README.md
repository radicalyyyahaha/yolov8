### These files only contains our works, the full code please go to https://github.com/ultralytics/ultralytics
---
#### How to use?
1. First of all , you should `pip install ultralytics`, then choose a directory, git clone the project mentioned above.
2. replace code in ultralytics/ultraltics/nn/modules with nn.modeuls
3. replace tasks.py in ultralytics/ultraltics/nn
4. pay attention to ultralytics/ultraltics/cfg, it's a config directory, add train.yaml, yolov8_a.yaml, this two files define the model structure and training parameters.
5. the most important thing is to download coco2017 dataset, it's about 24G, and use 2.py to change it as yolo style.
6. Finally, you can begin with `python train.py`
