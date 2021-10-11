# Bit-wise Training of Neural Network Weights
Repository for ICLR2022 submission 2798: https://openreview.net/forum?id=gxk4-rVATDA

First working version. Updates will follow.

Trainer.py runs the main code. It trains LeNet on MNIST (also ResNet20 and Conv6) with bit-depth 6. Trainable bits are the first 3 most significant one. The following are untrainable.
