# Texas COVID Modeling
Some scripts (Jupyter notebooks) that model the spread of COVID-19 in the state of Texas.

---

## Dependencies

To view these notebooks, you will need to install the jupyter notebook system in your Python3 environment, which can be done with:

```
pip3 install notebook
```

The remaining Python3 dependencies are below. These can also be installed with ``pip3 install <dependency>``:

```
# dependencies

numpy
scipy
pandas
matplotlib
tensorflow
tqdm
```

Additional dependencies may need to be installed to read the Excel spreadsheet datasets. Check the error log in the notebooks for additional dependencies.

---

## Jupyter Notebooks

An index of the Jupyter notebooks in this repository is given below:

* **SIR Model Examples** - A notebook with some examples of the SIR model in action. This is a recommended starting point for those unfamiliar with the SIR model.

* **TX COVID Analysis** - A notebook that performs forecasting and visualizes Texas COVID data on a per-county basis. For more information on the datasets and their sources, see the notebook header.

* **TX COVID RNN** - A Recurrent Neural Network (RNN) approach to model the righthand side (i.e. derivative) of the growth of the COVID 19 pandemic on a per-county basis. This righthand side is integrated (at least for now) using just the forward Euler method. The RNN is trained via Tensorflow2, however you should not need any more computing power than a standard CPU to train and run it.
