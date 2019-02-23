Convolutional Recurrent Neural Network
======================================

This software implements the Convolutional Recurrent Neural Network (CRNN) in pytorch.

- Resize the image height to 32, and the width should be multiple of 8.

Run demo
----------
Launch the demo by:

    python train.py --test-only --resume densenet_best.pth.tar

Train a new model
----------
    python train.py --not-pretrained --arch densenet

Reference
----------
- [crnn.pytorch](https://github.com/meijieru/crnn.pytorch)
- [efficient_densenet_pytorch](https://github.com/gpleiss/efficient_densenet_pytorch)
- [DenseNet on CIFAR10]()