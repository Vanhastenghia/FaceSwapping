## Environment setup
```
!git clone https://github.com/Vanhastenghia/FaceSwapping.git
%cd FaceSwapping
!pip install -r requirements.txt
!pip install torch==1.12.0+cu113 torchvision==0.13.0+cu113 torchaudio==0.12.0 -f https://download.pytorch.org/whl/torch_stable.html
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
## Using  Model 

```
!python main.py --output_path output/example
```



