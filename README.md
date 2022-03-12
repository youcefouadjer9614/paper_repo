## Towards Self-Supervised Learning of Human Identity from Gesture Patterns

This repository contains the implementation of "Towards Towards Self-Supervised Learning of Human Identity from Gesture Patterns" by Youcef Ouadjer, Adnane Mourad, Sid-Ahmed Berrani and Nesrine Bouadjenek.
- Self-supervised Contrastive Learning framework:

![image](https://github.com/youcefvision/paper_reop/blob/main/media/contrastive_learning.PNG)

- Encoder architecture uses depth-wise separable convolutions:

![image](https://github.com/youcefvision/paper_reop/blob/main/media/architecture.PNG)

### Requirements
You need to install the following packages
- Python 3.6 +
- torch 1.1 +
- cuda 10.1 +
- ptflops 0.6.8 + https://pypi.org/project/ptflops/ (Flops counter for convolutional neural networks on pytorch)
### Self-supervised pre-training
To train the models run the following command:

```
git status
git add
git commit
```

### Evaluation 

### Inference time and complexity

### Results
- User identification on HMOG Dataset

Models | GestureNet | MobileNetV1 | MobileNetV2 | EfficientNetB0 | 
--- | --- | --- | --- |--- |
Accuracy | 79.84 % | 61.4 % | 74.75 % | 89.11 % |

- User identification on Touchalytics

Models | GestureNet | MobileNetV1 | MobileNetV2 | EfficientNetB0 | 
--- | --- | --- | --- |--- |
Accuracy | 85 % | 83 % | 88 % | 98 % |

- User verification 
![image](https://github.com/youcefvision/paper_repo/blob/main/media/verification_accuray.PNG)

### Citation
Please consider citing our work if you find this repository helpful for your research
