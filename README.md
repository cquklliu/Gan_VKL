# Gan_VKL
Varying k-Lipschitz Constraint for Generative Adversarial Networks
implementation of paper"Varying k-Lipschitz Constraint for Generative Adversarial Networks"

Prerequisites
Python 2.7 or Python 3.3+
Tensorflow 0.12.1
SciPy
pillow


download celebA to ./data

To train on toy distribution:
$ python gan_toy.py

To train a model with downloaded dataset:
$ python main.py --input_height=158 --train --crop
