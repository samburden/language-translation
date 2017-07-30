# Deep Learning - Language Translation project

This is a recurrent neural network (RNN) that trains a sequence to sequence model used for translating an English sentence to a French sentence. For training, a very small vocabulary of
English and French sentences are used. This vocabulary can be found in the [data](data) folder. The full corpus for the subset of data is the [WMT10 French-English corpus](http://www.statmt.org/wmt10/training-giga-fren.tar)

This project is using Python 3 and needs the following libraries:

* numpy
* tensorflow
* matplotlib
* jupyter notebook

These can be installed using pip or conda if using [Anaconda](https://www.continuum.io/downloads).

The project is implemented in a Jupyter notebook and can be run using the following from a terminal:

```jupyter notebook dlnd_language_translation.ipynb```

<br/>
If interested in training your model on a GPU for better performance, checkout <a href="http://www.floydhub.com">FloydHub</a>.
