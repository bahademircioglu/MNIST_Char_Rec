# MNIST_Char_Rec

MNIST Character Recognition with 4-Fold Cross Validation

## Overview

A deep learning project that uses a Convolutional Neural Network (CNN) to recognize handwritten digits from the MNIST dataset. Implements 4‑fold cross‑validation and visualizes accuracy and loss.

## Features

- Selects 500 samples (50 per digit) for quick experiments  
- Three-layer CNN with max-pooling  
- 4‑fold cross‑validation  
- Plots for training/validation accuracy and loss  

## Prerequisites

- Python 3.7+  
- TensorFlow 2.x or Keras  
- NumPy, Matplotlib, scikit-learn

## Installation

```bash
git clone https://github.com/bahademircioglu/MNIST_Char_Rec.git
cd MNIST_Char_Rec
pip install -r requirements.txt
```

*(create `requirements.txt` with: `tensorflow numpy matplotlib scikit-learn`)*

## Usage

Launch the Jupyter notebook:

```bash
jupyter notebook MNIST.ipynb
```

Inspect the plots and model results directly in the notebook.

## Project Structure

```
MNIST_Char_Rec/
├── MNIST.ipynb
├── data/                
├── requirements.txt
├── LICENSE (GPL-3.0)
└── README.md
```

## Contributing

Contributions are welcome! Please open an issue or submit a PR.

## License

GPL‑3.0 License.
