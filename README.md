# NU-LiteNet: Mobile Landmark Recognition using Convolutional Neural Networks
By [Chakkrit Termritthikun](https://github.com/chakkritte) and Paisarn Muneesawang.

This repository is the implementation of "NU-LiteNet: Mobile Landmark Recognition using Convolutional Neural Networks" [[paper]](https://www.tci-thaijo.org/index.php/ecticit/article/view/165074/152412)  on Singapore and Paris landmark datasets.


## Result NU-LiteNet with Singapore landmark dataset

#### Single-crop (224x224) average of 10-fold-cross-validation

| Network       | Parameters (x10^6) | Top-1 Accuracy | Top-5 Accuracy |
| --------      | --------       | --------       | --------   |
| AlexNet       | 62.37          | 64.82          | 84.94       |
| GoogLeNet     | 6.02           | 70.69           | 88.75      |
| SqueezeNet    | 0.75          | 	60.08          | 83.24       |
| **NU-LiteNet-A**  | 0.28           | 78.09           | 92.75       |
| **NU-LiteNet-B**  | 0.94          | 81.15	         | 	93.96      |

		
## Result NU-LiteNet with Paris dataset

#### Single-crop (224x224) average of 10-fold-cross-validation

| Network       | Parameters (x10^6) | Top-1 Accuracy | Top-5 Accuracy |
| --------      | --------       | --------       | --------   |
| AlexNet       | 62.36          | 58.62	         | 	90.00       |
| GoogLeNet     | 6.01           | 59.97          | 91.10     |
| SqueezeNet    | 0.74          | 	53.34         | 87.97      |
| **NU-LiteNet-A**  | 0.27           | 66.67          | 94.07       |
| **NU-LiteNet-B**  | 0.93          | 69.58	         | 	94.65     |
	

## License and Citation

NU-LiteNet for **non-commercial research/educational** use.

( Thai ) NU-LiteNet อนุญาตให้ใช้เฉพาะเพื่อการ**ศึกษาและวิจัยเท่านั้น ห้ามนำไปใช้เชิงการค้าทุกรูปแบบ**
