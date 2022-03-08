# Task 2 Encoding and Classifier

## Description

- Encode the following files in a quantum circuit [mock_train_set.csv](https://drive.google.com/file/d/1PIcC1mJ_xi4u1-2gxyoStg2Rg_joSBIB/view?usp=sharing) and [mock_test_set.csv](https://drive.google.com/file/d/1aapYE69pTeNHZ6u-qKAoLfd1HWZVWPlB/view?usp=sharing) in at least two different ways (these could be basis, angle, amplitude, kernel or random encoding).
- Design a variational quantum circuit for each of the encodings, using the `column4` as the target, this is a binary class 0 and 1.
- You must use the data from `column0` to `column3` for your proposed classifier.
- Consider the ansatz you are going to design as a layer and find out how many layers are necessary to reach the best performance.

Analyze and discuss the results.

Feel free to use existing frameworks (e.g. PennyLane, Qiskit) for creating and training the circuits.  
This PennyLane demo can be useful: [Training a quantum circuit with Pytorch](https://pennylane.ai/qml/demos/tutorial_state_preparation.html).  
This Quantum Tensorflow tutorial can be useful: [Training a quantum circuit with Tensorflow](https://www.tensorflow.org/quantum/tutorials/mnist).

For the variational circuit, you can try any circuit you want. You can start from one with a layer of RX, RZ and CNOTs.
