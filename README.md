# Visualizing Attention Matrices

<img src="./attention_matrix.png" width="400" height="300">
<img src="./modularity_scores.png" width="400" height="300">


This repository contains a Jupyter Notebook for visualizing attention matrices, which are often used in transformer-based neural network models. The visualization helps in understanding how different parts of the input sequence contribute to the attention mechanism, providing insights into model interpretability and behavior.

## Contents

- `Visualizing Attention Matrices.ipynb`: The main Jupyter Notebook that demonstrates how to visualize attention matrices.

## Requirements

To run the notebook, you need to have the following libraries installed:

- `numpy`
- `matplotlib`
- `seaborn`
- `pandas`
- `torch` (for PyTorch-based models)
- `transformers` (for Hugging Face models)

You can install these libraries using pip:

```bash
pip install numpy matplotlib seaborn pandas torch transformers
```

## Usage

1. **Clone the repository**:
   ```bash
   git clone https://github.com/galenwilkerson/Visualizing-Attention-Matrices.git
   cd Visualizing-Attention-Matrices
   ```

2. **Open the Jupyter Notebook**:
   ```bash
   jupyter notebook Visualizing Attention Matrices.ipynb
   ```

3. **Run the cells in the notebook** to visualize the attention matrices. The notebook provides step-by-step instructions and explanations for each part of the visualization process.

## Visualizations

The notebook includes the following visualizations:

- Heatmaps of attention matrices
- Layer-wise and head-wise attention patterns
- Analysis of attention scores and their distribution

These visualizations help in understanding the inner workings of attention mechanisms in transformer models.



## Contributing

If you would like to contribute to this project, please fork the repository and submit a pull request. We welcome all contributions, including bug fixes, feature enhancements, and documentation improvements.

## License

This project is licensed under the MIT License. See the [LICENSE](LICENSE) file for details.

## Acknowledgments

- The Hugging Face team for their `transformers` library
- The PyTorch community for their contributions to the `torch` library
