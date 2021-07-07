# Quantum Machine Learning for jet tagging at LHCb - PyHEP 2021

[![Binder](https://mybinder.org/badge_logo.svg)](https://mybinder.org/v2/gh/dnicotra/pyhep2021-qml4jet/HEAD)


This repository contains an example code for PyHEP 2021.

At LHCb, b-jets are tagged using several methods, some of them with high efficiency  but low purity or high purity and low efficiency. Particularly our aim is to  identify  jets produced by <img src="https://render.githubusercontent.com/render/math?math=b"> and <img src="https://render.githubusercontent.com/render/math?math=\bar{b}"> quarks, which is fundamental to perform important physics searches, *e.g.* the measurement of the <img src="https://render.githubusercontent.com/render/math?math=b-\bar{b}"> charge asymmetry, which could be sensitive to New Physics processes.

Since this is a classification task, Machine Learning (ML) algorithms can be used to achieve a good separation between <img src="https://render.githubusercontent.com/render/math?math=b">- and <img src="https://render.githubusercontent.com/render/math?math=\bar{b}">-jets: classical ML algorithms such as Deep Neural Networks have been proved to be far more efficient than standard methods since they rely on the whole jet substructure. In this work, we present a new approach to <img src="https://render.githubusercontent.com/render/math?math=b">-tagging based on Quantum Machine Learning (QML) which makes use of the QML Python library Pennylane integrated with the classical ML frameworks PyTorch and Tensorflow. Official LHCb simulated events of <img src="https://render.githubusercontent.com/render/math?math=b \bar{b}"> di-jets are studied and different quantum circuit geometries are considered. Performances of QML algorithms are compared with standard tagging methods and classical ML algorithms, preliminarily showing that QML algorithms perform almost as good as classical ML algorithms, despite using fewer events due to time and computational constraints.
