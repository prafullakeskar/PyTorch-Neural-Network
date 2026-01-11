# PyTorch Neural Network Classification

A clean, well-structured PyTorch project for neural network classification on the Iris dataset.

## Project Structure

```
PyTorch/
├── src/
│   ├── data/
│   │   └── dataset.py      # Data loading and preprocessing
│   ├── models/
│   │   └── mlp.py          # Neural network model definition
│   └── training/
│       └── train.py        # Training script
├── data/                   # Data directories
├── experiments/            # Training outputs and results
├── notebooks/              # Jupyter notebooks
├── requirements.txt        # Python dependencies
└── README.md              # This file
```

## Features

- **Modular Architecture**: Clean separation of data, models, and training logic
- **Iris Dataset**: Classification on the classic Iris dataset (4 features, 3 classes)
- **Neural Network**: Multi-layer perceptron (MLP) with configurable architecture
- **Training Pipeline**: Complete training loop with loss tracking and visualization

## Installation

1. Clone the repository:
```bash
git clone <your-repo-url>
cd PyTorch
```

2. Create a virtual environment (recommended):
```bash
python -m venv venv
source venv/bin/activate  # On Windows: venv\Scripts\activate
```

3. Install dependencies:
```bash
pip install -r requirements.txt
```

## Usage

Run the training script:
```bash
python src/training/train.py
```

This will:
- Load and preprocess the Iris dataset
- Initialize the neural network model
- Train for 10 epochs
- Display training and test loss curves

## Model Architecture

- **Input Layer**: 4 features (Iris dataset)
- **Hidden Layer**: 64 units with ReLU activation
- **Output Layer**: 3 classes (softmax via CrossEntropyLoss)

## Requirements

- Python 3.7+
- PyTorch
- scikit-learn
- matplotlib
- numpy

See `requirements.txt` for the complete list.

## License

[Add your license here]

