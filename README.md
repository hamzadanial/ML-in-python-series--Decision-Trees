
### Highlights inside the notebook

| Section | What you’ll find |
|---------|------------------|
| **1. Training & Visualising** | Build a `DecisionTreeClassifier`, plot decision regions on the Iris dataset, export to Graphviz. |
| **2. Class Probability & Gini/Entropy** | How trees compute class probability; comparing Gini impurity vs entropy. |
| **3. Regularisation (max_depth, min_samples_leaf, …)** | Demonstrates under-/over-fitting control with detailed plots. |
| **4. Regression Trees** | Fits a `DecisionTreeRegressor`, compares piece-wise constant predictions to true function. |
| **5. Pruning with Cost-Complexity** | Uses `ccp_alpha` path to prune and evaluate tree sizes. |
| **6. Exercise Solutions** | Complete answers to the end-of-chapter exercises, with explanations. |

---

## Running the notebook

### 1 · Colab (recommended)

Click the **“Open in Colab”** badge at the top of this page.  
Colab spins up a ready-to-use environment; no local installs needed.


# 2. Create & activate a Python ≥3.9 virtual environment (optional but advised)
python -m venv .venv
source .venv/bin/activate   # Windows: .venv\Scripts\activate

# 3. Install minimal requirements
pip install -r requirements.txt

# 4. Launch Jupyter
jupyter notebook decision_trees.ipynb
