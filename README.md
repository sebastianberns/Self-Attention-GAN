# Self-Attention GAN

Fork of [heykeetae/Self-Attention-GAN](https://github.com/heykeetae/Self-Attention-GAN) adapted for MNIST at 32x32 px size.

## Usage

Tested with:

- Python 3.6.3
- CUDNN 7.6 and CUDA 10.1
- PyTorch 1.6.0
- Torchvision 0.7.0

### Train

```bash
$ python main.py --dataset mnist --imsize 32 --imchan 1 --adv_loss hinge --batch_size 64 --version sagan_mnist
```
