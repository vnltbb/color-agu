# color-agumentation
## dataset structure
- original
    - class 1: Pepper Mild Mottle Virus(PMMoV)
    - class 2: Powdery Mildew
    - class 3: Healthy
- Only augmentation 1
    - class 1
    - class 2
    - class 3
- Only augmentation 2
    - class 1
    - class 2
    - class 3
- Only augmentation 3
    - class 1
    - class 2
    - class 3

## experiment
### experiment 1: CNN backbone with original-1000
- backbone: EfficientNet, MobilNet, DenseNet, ResNet
- regulation: preprocess_map
- image size: 224, 224

### experiment 2: Color Agumentation
- color agumentation: color jittering, color mapping 
- HSV image use: RGB -> HSV, brightness/chroma

### experiment 3: ratio original:agumentation
- 9/1, 8/2, 7/3, 6/4, 5/5, 4/6, 3/7, 2/8, 1/9