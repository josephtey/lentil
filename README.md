Lentil - Latent Skill Embedding
===============================

A package for training, evaluation, and visualization of the Latent Skill Embedding model. Read
more about the model at http://siddharth.io/lentil.

Usage
-----

You can install the package's dependencies with

```
pip install -r requirements.txt
```

You can install the package in your environment with

```
python setup.py install
```

If you wish to run the tests, make sure you have
[tox](https://tox.readthedocs.org/en/latest/) installed and then run

```
tox
```

Once installed in your environment, command-line interfaces for training and
evaluation are available through `lse_train` and `lse_eval`. The appropriate format for input
interaction log data is given in the documentation for `lentil.datatools.InteractionHistory`.
IPython notebooks used to conduct experiments are available in the `nb` directory, and provide
example invocations of most functions and classes. It is recommended that you read the notebooks
in the following order: `toy_examples`, `synthetic_experiments`, `data_explorations`,
`model_explorations`, `evaluations`, `sensitivity_analyses`, and `bubble_experiments`.

To create the transition graph visualizations in `nb/data_explorations.ipynb`, you will need to install [pygraphviz](http://pygraphviz.github.io/).

Documentation
-------------

Build the documentation with

```
tox -e docs
```

Once run, open doc/_build/html/index.html for Sphinx documentation on modules in the package.

Questions and comments
----------------------

Please contact the author at `sgr45 [at] cornell [dot] edu` if you have questions or find bugs.

Citation
--------
If you find this software useful in your work, we kindly request that you cite the following [paper](http://arxiv.org/abs/1602.07029):

```
@InProceedings{Reddy/etal/16c,
  title={Latent Skill Embedding for Personalized Lesson Sequence Recommendation},
  author={Reddy, Siddharth and Labutov, Igor and Joachims, Thorsten},
  booktitle={Arxiv 1602.07029},
  year={2016},
  url={http://arxiv.org/abs/1602.07029}
}
```
