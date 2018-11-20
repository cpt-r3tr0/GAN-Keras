## Keras-GAN
Collection of Keras implementations of Generative Adversarial Networks (GANs) suggested in research papers. These models are in some cases simplified versions of the ones ultimately described in the papers, but I have chosen to focus on getting the core ideas covered instead of getting every layer configuration right.

## Table of Contents
  * [Installation](#installation)
  * [Implementations](#implementations)
    + [Auxiliary Classifier GAN](#ac-gan)
    + [Adversarial Autoencoder](#adversarial-autoencoder)
    + [Bidirectional GAN](#bigan)
    + [Boundary-Seeking GAN](#bgan)

## Installation
    $ git clone https://github.com/cpt-r3tr0/GAN-Keras.git
    $ cd GAN-Keras/
    $ sudo pip3 install -r requirements.txt

## Implementations 
  
### AC-GAN
Implementation of _Auxiliary Classifier Generative Adversarial Network_.

[Code](implementations/acgan/acgan.py)

Paper: https://arxiv.org/abs/1610.09585

#### Example
```
$ cd implementations/acgan/
$ python3 acgan.py
```

<p align="center">
    <img src="assets/acgan.gif" width="640"\>
</p>

### Adversarial Autoencoder
Implementation of _Adversarial Autoencoder_.

[Code](implementations/aae/aae.py)

Paper: https://arxiv.org/abs/1511.05644

#### Example
```
$ cd implementations/aae/
$ python3 aae.py
```

<p align="center">
    <img src="assets/aae.png" width="640"\>
</p>

### BiGAN
Implementation of _Bidirectional Generative Adversarial Network_.

[Code](implementations/bigan/bigan.py)

Paper: https://arxiv.org/abs/1605.09782

#### Example
```
$ cd implementations/bigan/
$ python3 bigan.py
```

### BGAN
Implementation of _Boundary-Seeking Generative Adversarial Networks_.

[Code](implementations/bgan/bgan.py)

Paper: https://arxiv.org/abs/1702.08431

#### Example
```
$ cd implementations/bgan/
$ python3 bgan.py
```
