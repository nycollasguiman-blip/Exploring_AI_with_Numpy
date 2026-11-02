# Exploring AI with NumPy

Machine learning algorithms implemented **from scratch using only NumPy**, to understand the math that libraries like scikit-learn, TensorFlow and PyTorch abstract away.

![Python](https://img.shields.io/badge/python-3.10%2B-blue)
![NumPy](https://img.shields.io/badge/numpy-only-informational)
![Status](https://img.shields.io/badge/status-in%20progress-yellow)

---

## Why this repository exists

Calling `model.fit()` is easy. Knowing what happens inside it is what lets you debug a model that does not converge, pick the right algorithm, and explain a result to someone else.

The goal here is **not** production-ready code. It is understanding: every algorithm is derived, implemented step by step in NumPy, and then checked against a reference implementation to confirm it behaves as expected.

## Notebooks

| # | Notebook | What it covers | Status |
|---|----------|----------------|--------|
| 01 | [Linear Regression](01_linear_regression.ipynb) | Least squares, cost function, gradient descent | ✅ Done |
| 02 | [LMS Algorithm](02_lms_algorithm.ipynb) | Online learning, Widrow-Hoff update rule, learning rate | ✅ Done |

## How each notebook is organized

1. **The math**: short derivation of the algorithm, with equations.
2. **Implementation**: written in plain NumPy, in small functions with clear names.
3. **Sanity check**: results compared against scikit-learn (coefficients, error or accuracy).
4. **What I learned**: takeaways, including what went wrong along the way.

## Results

<!-- Add 1 or 2 images from your notebooks here. Save them in an `images/` folder.
Examples:
![Cost curve](images/linear_regression_cost.png)
![Fitted line vs. scikit-learn](images/linear_regression_fit.png)
-->

| Notebook | My implementation | scikit-learn | Difference |
|----------|-------------------|--------------|------------|
| 01 Linear Regression | _fill in (e.g. MSE)_ | _fill in_ | _fill in_ |
| 02 LMS Algorithm | _fill in_ | _fill in_ | _fill in_ |

## Getting started

```bash
# 1. Clone the repository
git clone https://github.com/nycollasguiman-blip/exploring-ai-with-numpy.git
cd exploring-ai-with-numpy

# 2. (Optional) create a virtual environment
python -m venv .venv
source .venv/bin/activate        # Windows: .venv\Scripts\activate

# 3. Install dependencies
pip install -r requirements.txt

# 4. Open the notebooks
jupyter notebook
```

## Repository structure

```
exploring-ai-with-numpy/
├── 01_linear_regression.ipynb
├── 02_lms_algorithm.ipynb
├── requirements.txt
└── README.md
```

## Roadmap

- [x] Linear regression with gradient descent
- [x] LMS algorithm
- [ ] ???
- [ ] ???
- [ ] ???
- [ ] ???

## References

<!-- List the books, papers and courses you actually used. Examples of the format:
- Author, *Title*, edition, publisher.
-->

## About me

I am a Mechatronics Engineering student at Poli-USP (São Paulo, Brazil), focused on data science and machine learning. This repository is where I build the foundations; my applied projects live in other repositories.

- LinkedIn: [nycollas-guimaraes](https://www.linkedin.com/in/nycollas-guimaraes)
- GitHub: [@nycollasguiman-blip](https://github.com/nycollasguiman-blip)

## License

Distributed under the MIT License. See `LICENSE` for details.
