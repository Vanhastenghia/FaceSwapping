## Environment setup
```
!git clone https://github.com/Vanhastenghia/FaceSwapping.git
!pip install -r requirements.txt
```
## Directories structure
```
DiffFace
├── checkpoints
    ├── Arcface.tar
    ├── FaceParser.pth
    ├── GazeEstimator.pt
    └── Model.pt
├── data
    └── src
        ├── 001.png
        └── ...
    └── targ
        ├── 001.png
        └── ...
├── models
├── optimization
├── utils
└── main.py
```
## Quick Inference Using Pretrained Model 
Place source and target images in data/src, and data/targ. Then run the following. 
```
python main.py --output_path output/example
```



