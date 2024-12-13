# ML-SVM-Tutorial
# Mastering SVMs: Understanding Kernels and Visualizing Decision Boundaries

Welcome to the repository for the tutorial on Support Vector Machines (SVMs), focusing on understanding kernels and visualizing decision boundaries! This project provides a comprehensive introduction to SVMs, demonstrates their use with various kernel functions, and includes visual insights into how SVMs classify data.

## Features
- Explanation of SVM theory and kernel functions.
- Step-by-step guide to generating and splitting datasets.
- Implementation of SVM models with linear, polynomial, and RBF kernels.
- Visualization of decision boundaries for each kernel and dataset.
- Accuracy comparison for different datasets and kernels.

---

## Repository Structure

```plaintext
├── tutorial.pdf            # The complete tutorial in PDF format.
├── svm_tutorial.ipynb      # Jupyter Notebook containing all the code.
├── results/                # Folder containing decision boundary plots.
├── README.md               # This file.
├── LICENSE                 # Open-source license (MIT).
```

---

## Getting Started

To run this project on Google Colab:

### Prerequisites

Ensure you have access to Google Colab and an internet connection. The required libraries will be installed in the notebook.

### Steps

1. Open the notebook in Google Colab:
   - Download the `svm_tutorial.ipynb` file from this repository.
   - Upload it to your Google Drive.
   - Open it with Google Colab.

2. Install dependencies by running the following command in the first cell:
   ```python
   !pip install numpy pandas scikit-learn matplotlib seaborn
   ```

3. Follow the notebook cells step-by-step to:
   - Generate synthetic datasets (`make_moons` and `make_blobs`).
   - Train SVM models with different kernel functions.
   - Visualize decision boundaries.
   - Evaluate and compare model accuracy.

---

## Usage

1. Run the notebook to:
   - Generate synthetic datasets (`make_moons` and `make_blobs`).
   - Train SVM models with different kernel functions.
   - Visualize decision boundaries.
   - Evaluate and compare model accuracy.

2. Use the tutorial (PDF) to learn the concepts and follow along.

---

## Results

| Dataset         | Kernel   | Accuracy |
|-----------------|----------|----------|
| Moons Dataset   | Linear   | 90.0%    |
| Blobs Dataset   | Linear   | 100.0%   |
| Moons Dataset   | Poly     | 91.1%    |
| Blobs Dataset   | Poly     | 100.0%   |
| Moons Dataset   | RBF      | 96.7%    |
| Blobs Dataset   | RBF      | 100.0%   |

Visualizations of decision boundaries are generated dynamically in the notebook.

---

## License

This project is licensed under the MIT License - see the [LICENSE](LICENSE) file for details.

---

## References

1. Cortes, C., & Vapnik, V. (1995). *Support-vector networks*. Machine Learning, 20(3), 273–297.
2. Schölkopf, B., & Smola, A. J. (2002). *Learning with Kernels: Support Vector Machines, Regularization, Optimization, and Beyond*. MIT Press.
3. [Scikit-learn Documentation](https://scikit-learn.org/stable/)
4. [Towards Data Science: Understanding Kernel Functions](https://towardsdatascience.com/kernel-functions)

---

## Acknowledgments

Special thanks to the creators of Scikit-learn for providing accessible tools for implementing SVMs, and to the authors of the referenced papers and tutorials for their insights.
