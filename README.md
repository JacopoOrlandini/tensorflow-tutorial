# TensorFlow Tutorial

## Install Requirements

The easiest way to install TenorFlow is to create a virtual environment 
using [Anaconda](https://conda.io/miniconda.html).

```bash
conda create -n tf-tutorial python=3.6 jupyter pandas matplotlib pip
source activate tf-tutorial  # remove the initial 'source' if you are using Windows
pip install tensorflow tensorflow-tensorboard keras
```

This will install the correct TensorFlow version and other libraries within your
virtual environment. Now, start a Jupyter Notebook server by running:

```bash
jupyter notebook
```


## References

The tutorial is based on

 * https://github.com/random-forests/tensorflow-workshop
 * https://www.tensorflow.org/get_started/mnist/pros

