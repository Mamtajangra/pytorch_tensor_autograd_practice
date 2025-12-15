# PyTorch Practice Repository

This repository contains a collection of Jupyter notebooks designed to help you learn and practice PyTorch. The focus is on tensors, autograd, datasets, and building training pipelines.

## Project Overview
The repository is structured to provide step-by-step learning through practical examples and experiments. Each notebook focuses on a specific concept or workflow in PyTorch, making it easier to build a strong foundation.

## Contents

### Notebooks

1. **[pytorch_tensors.ipynb](pytorch_tensors.ipynb)**
   - Introduction to PyTorch tensors.
   - Topics covered:
     - Creating tensors using `torch.tensor()`, `torch.zeros()`, `torch.ones()`, `torch.rand()`, etc.
     - Tensor attributes like `.shape`, `.dtype`, `.device`.
     - Basic tensor operations (addition, multiplication, etc.).
     - Reshaping tensors with `view()` and `reshape()`.

2. **[pytorch_autograd.ipynb](pytorch_autograd.ipynb)**
   - Understanding PyTorch's autograd module for automatic differentiation.
   - Topics covered:
     - Computing gradients with `torch.autograd`.
     - Using `requires_grad` to track operations.
     - Gradient computation for scalar and non-scalar outputs.

3. **[pytorch_dataset_dataloader.ipynb](pytorch_dataset_dataloader.ipynb)**
   - Working with PyTorch's `Dataset` and `DataLoader` classes.
   - Topics covered:
     - Creating custom datasets.
     - Using `DataLoader` for batching and shuffling.
     - Iterating through datasets efficiently.

4. **[pytorch_improve_pipeline_use_nn_module1.ipynb](pytorch_improve_pipeline_use_nn_module1.ipynb)**
   - Improving training pipelines using `torch.nn.Module`.
   - Topics covered:
     - Defining models with `nn.Module`.
     - Using activation functions and layers.
     - Forward and backward passes.

5. **[pytorch_nn_module_on_diabetes2.ipynb](pytorch_nn_module_on_diabetes2.ipynb)**
   - Applying `nn.Module` to a real-world dataset (diabetes dataset).
   - Topics covered:
     - Data preprocessing.
     - Building and training a regression model.
     - Evaluating model performance.

6. **[pytorch_training_pipeline.ipynb](pytorch_training_pipeline.ipynb)**
   - End-to-end training pipeline example.
   - Topics covered:
     - Model definition.
     - Loss computation and optimization.
     - Training loops and evaluation.

7. **[dataset_dataloader_diabetes.ipynb](dataset_dataloader_diabetes.ipynb)**
   - Using `Dataset` and `DataLoader` with the diabetes dataset.
   - Topics covered:
     - Loading and batching data.
     - Preparing data for training.

## Quick Start

1. Clone the repository:
   ```bash
   git clone https://github.com/your-username/pytorch_practice.git
   cd pytorch_practice
   ```

2. Install dependencies:
   ```bash
   pip install torch jupyter
   ```

3. Open the notebooks in Jupyter:
   ```bash
   jupyter notebook
   ```

## Notes
- Python 3.8+ is recommended.
- All notebooks are self-contained; execute cells sequentially.
- GPU support is optional but recommended for faster computation.

## License
This repository is for personal practice and educational purposes. Feel free to use and modify the notebooks for your learning.

## Contact
For questions or suggestions, feel free to open an issue or contact the author.



