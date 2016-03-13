# nn-experiments

If you want to learn about deep learning I highly recommend the excellent [WildML](http://www.wildml.com/) series written by Danny Britz.

The notebooks in this project are variations on his '[Implementing a Neural Network from Scratch in Python](http://www.wildml.com/2015/09/implementing-a-neural-network-from-scratch/) exploring expressing the same using *Tensorflow*, *Keras*, and *skflow*.

**Note:** Im new to these frameworks, so there maybe better ways to express this then I came up with.

## setup

**Note:** You will have to update *requirements.txt* and change the tensorflow dependency if you install on something else the Mac OS X, [see here](https://www.tensorflow.org/versions/r0.7/get_started/os_setup.html#pip-installation). 

```bash
# Create a new virtual environment
virtualenv venv
source venv/bin/activate
# Install requirements
pip install -r requirements.txt
# Start the notebook server
KERAS_BACKEND=tensorflow jupyter notebook
```
