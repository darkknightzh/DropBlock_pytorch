# DropBlock_pytorch


This is my second time to upload code to github, if there is something wrong wi the README and LICENSE, 
please let me know. I will modify or delete the code or project if necessary.

other implementations of DropBlock:

[Randl:DropBlock-pytorch](https://github.com/Randl/DropBlock-pytorch)

[DHZS:tf-dropblock](https://github.com/DHZS/tf-dropblock)


An implementation of `DropBlock` in PyTorch. `DropBlock` is a replacement for dropout which zero-es 
entire spatial blocks instead of single pixels. For more information, check the paper:
[DropBlock: A regularization method for convolutional networks](https://arxiv.org/abs/1810.12890) 

Inspired by [DHZS:tf-dropblock](https://github.com/DHZS/tf-dropblock), I modified the code from 
[Randl:DropBlock-pytorch](https://github.com/Randl/DropBlock-pytorch), and use max pooling instead 
of conv to get the mask of DropBlock(named DropBlock2DV2 in the code). All the code except DropBlock2DV2 
comes from [Randl:DropBlock-pytorch](https://github.com/Randl/DropBlock-pytorch), you can go to 
[Randl:DropBlock-pytorch](https://github.com/Randl/DropBlock-pytorch) for more information.