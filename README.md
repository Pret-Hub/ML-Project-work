# ML-Project-work

Quantum Neural Network for MNIST Binary Classification

Project Overview:-

This project implements a Quantum Neural Network (QNN) for binary classification of MNIST digits using TensorFlow Quantum. The unique aspect of this implementation is the use of extreme data compression, reducing 28x28 pixel images to just 2x2 pixels, which are then encoded into a 4-qubit quantum circuit.
Key Features

Quantum-Classical Hybrid Model: Utilizes a 4-qubit quantum circuit integrated with classical neural network components.
Extreme Data Compression: Downscales MNIST images to 2x2 pixels, demonstrating quantum classification with minimal input data.
Custom Quantum Circuit: Implements a parameterized quantum circuit (PQC) with XX and ZZ gates for data processing.
TensorFlow Quantum Integration: Leverages TFQ for seamless integration of quantum circuits with classical machine learning workflows.

Technical Details

Quantum Circuit: 4 data qubits with XX and ZZ gates, and a readout qubit with Hadamard gates.
Data Preprocessing: Resizes 28x28 MNIST images to 2x2 pixels using TensorFlow.
Model Architecture: Sequential model with a PQC layer from TFQ.
Training: Utilizes hinge loss and a custom hinge accuracy metric.

Results

-> Achieved 82% accuracy in binary classification.

-> Demonstrates the potential of quantum computing in pattern recognition tasks with severely limited data input.

Technologies Used

- TensorFlow and TensorFlow Quantum
- Cirq
- Python
- NumPy
- Matplotlib (for visualization)

Future Work

-> Explore scaling to multi-class classification.

-> Investigate performance on other datasets.

-> Optimize quantum circuit design for improved accuracy.

This project showcases the application of quantum machine learning techniques to a classical problem, highlighting the potential of quantum computing in handling tasks with minimal data input.
