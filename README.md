# Pytorch GANs for ultrasound images
PyTorch로 구현한 GAN(Generative Adversarial Networks)
초음파 영상 버전으로 확장하기 위한 前 단계(for study)

_Datasets 폴더에 학습 이미지를 저장하면 됩니다._
_결과 영상은 model 폴더 내 image폴더에 저장됩니다.

* To do list
  - 학습 결과 이미지 첨부하기
  - 논문 내용 요약하기


## Development Environment
* NVIDIA GeFore 940MX
* cuda 8.0
* python 3.6.5
* pytorch 0.4.0
* torchvision 0.2.1



### Vanilla GAN
_Generative Adversarial Network_

[[Paper]](https://arxiv.org/abs/1406.2661) [[Code]](models/GAN/network.py)


### CGAN
_Conditional Generative Adversarial Network_

[[Paper]](https://arxiv.org/abs/1411.1784) [[Code]](models/CGAN/network.py)


### DCGAN
_Deep Convolutional Generative Adversarial Network_

[[Paper]](https://arxiv.org/abs/1511.06434) [[Code]](models/DCGAN/network.py)


### ACGAN
_Auxiliary Classifier Generative Adversarial Network_

[[Paper]](https://arxiv.org/abs/1610.09585) [[Code]](models/ACGAN/network.py)


### InfoGAN
_Information Maximizing Generative Adversarial Nets_

[[Paper]](https://arxiv.org/abs/1606.03657) [[Code]](models/InfoGAN/network.py)


## Acknowledgements
This implementation has been based on [this repository](https://github.com/eriklindernoren/PyTorch-GAN) and tested with Pytorch over ver 0.4.0 on Windows 10 and Ubuntu 14.04.
