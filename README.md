# InstanceSegmentation
Instance Segmentation using Mask R-CNN. Currently code only detects instances of class 'Person'.
## Requirements
```
wget --quiet http://sceneparsing.csail.mit.edu/data/ChallengeData2017/images.tar
wget --quiet http://sceneparsing.csail.mit.edu/data/ChallengeData2017/annotations_instance.tar
tar -xf images.tar
tar -xf annotations_instance.tar
rm images.tar annotations_instance.tar
pip install -qU torch_snippets
wget --quiet https://raw.githubusercontent.com/pytorch/vision/release/0.12/references/detection/engine.py
wget --quiet https://raw.githubusercontent.com/pytorch/vision/release/0.12/references/detection/utils.py
wget --quiet https://raw.githubusercontent.com/pytorch/vision/release/0.12/references/detection/transforms.py
wget --quiet https://raw.githubusercontent.com/pytorch/vision/release/0.12/references/detection/coco_eval.py
wget --quiet https://raw.githubusercontent.com/pytorch/vision/release/0.12/references/detection/coco_utils.py
pip install -q -U 'git+https://github.com/cocodataset/cocoapi.git#subdirectory=PythonAPI'```
