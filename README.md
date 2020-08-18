# PF-Net_PaddlePaddle
Author: CAO RUI

PaddlePaddle Implementation for [PF-Net: Point Fractal Network for 3D Point Cloud Completion](https://arxiv.org/abs/2003.00410)

# Prerequisites

Python: Python 3.6+

[PaddlePaddle](https://github.com/PaddlePaddle/Paddle) : Deep learning framework

[open3d](http://www.open3d.org/docs/release/): 3D vision visualization toolbox

Then, run script```download_shapenet_part16_catagories.sh``` in folder ```dataset``` for preparing shapenet part dataset.

# Install
Clone the repo

```git clone https://github.com/63445538/PF-Net_PaddlePaddle.git```

# Train

```python Train_FPNet.py```

# Test

```python Test_FPNet.py```

# Result

Here show the completion results:
![image](https://github.com/63445538/PF-Net_PaddlePaddle/blob/master/img/1.png)
![image](https://github.com/63445538/PF-Net_PaddlePaddle/blob/master/img/2.png)
![image](https://github.com/63445538/PF-Net_PaddlePaddle/blob/master/img/3.png)

