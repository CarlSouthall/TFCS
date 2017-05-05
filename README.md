# Tensorflow CS

High level classes for RNN and CNN implementation built on top of Tensorflow.

## License

This library is published under the BSD license which allows redistribution and modification as long as the copyright and disclaimers are contained. The full license information can be found on the [license](https://github.com/CarlSouthall/TFCS/blob/master/LICENSE) page. 

## Installation

#### Required Packages

• [numpy](https://www.numpy.org)   
• [tensorflow](https://www.tensorflow.org/)

The easiest and suggested method to install the library is to use pip.

     pip install TFCS

To update the library use

     pip install --upgrade TFCS
     
For further install information see the [install](https://github.com/CarlSouthall/TFCS/blob/master/install.md) page.


## Algorithms

-- CNN -- Convolutional neural networks :

- 2d and 3d convolutional usage.

-- RNN -- Recurrent neural networks :

 -  tanh, LSTM, LSTMP and GRU cells.
 - single directional and bi-directional configurations.
 -  soft attention mechanisms.

## Usage


```Python
import TFCS as tfcs

CNN1=tfcs.CNN(train_data, train_targ, val_data, val_targ, mini_batch_numbers, filename)
CNN1.train()
out=CNN1.implement(test_data)

RNN1=tfcs.RNN(train_data, train_targ, val_data, val_targ, filename)
RNN1.train()
out=RNN1.implement(test_data)

```
For further usage details see the [usage](https://github.com/CarlSouthall/TFCS/blob/master/usage.md) page.

##Help

Any questions please feel free to contact me on carl.southall@bcu.ac.uk





