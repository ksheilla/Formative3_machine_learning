**PDF for Manual Calculations and Group Contributions:**
https://drive.google.com/drive/folders/161SKoA1FH3522who6h5BXrYomwDLL0b2?usp=sharing

# Statistical Learning & Optimization: Probability, Bayes, and Gradient Descent


## 👥 Group Members
* **Celine LAURA ISHMWE**
* **Loic HIGIRO**
* **Ulrich RUKAZAMBUGA**
* **Sheilla KEZA RUVUGABIGWI**

---

##  Project Overview
This project explores the intersection of statistical theory and machine learning optimization. It covers the implementation of probability distributions from scratch, the application of Bayesian probability to Natural Language Processing (Sentiment Analysis), and the manual and programmatic execution of Gradient Descent for linear regression.

##  Project Structure

### Part 1: Bivariate Normal Distribution
* **Dataset:** BMI Dataset (Analysis of Height vs. Weight).
* **Implementation:** Developed the Bivariate Normal PDF from scratch using Python, avoiding external statistical libraries to demonstrate a deep understanding of the mathematical formula.
* **Visualization:** 3D Surface plots and 2D Contour plots created with Matplotlib to analyze joint probability density.



### Part 2: Bayesian Sentiment Analysis
* **Dataset:** IMDb Movie Reviews.
* **Methodology:** Applied **Bayes' Theorem** to calculate the posterior probability $P(Positive | Keyword)$ of a review being positive based on specific evidence (keywords).
* **Logic:** Implemented modular, DRY-compliant Python functions to calculate:
    * **Prior:** $P(Positive)$
    * **Likelihood:** $P(Keyword | Positive)$
    * **Marginal:** $P(Keyword)$

### Part 3 & 4: Gradient Descent Optimization
* **Objective:** Optimize parameters $m$ (slope) and $b$ (intercept) for the data points $(1,3)$ and $(3,6)$.
* **Manual Calculation:** Four iterative updates (one per group member) documented in the manual submission.
* **Programmatic Implementation:** Used **SciPy** to implement gradient descent with a visible update loop to ensure the process is transparent and verifiable.
* **Analytics:** Visual tracking of the **Mean Squared Error (MSE)** reduction and parameter convergence.


##  How to run

### Prerequisites
* Python 3.10+
* Required Libraries: `numpy`, `pandas`, `matplotlib`, `scipy`, `jupyter`

### Installation & Execution
```bash
# Clone the repository
git clone [https://github.com/ksheilla/Formative3_machine_learning.git](https://github.com/ksheilla/Formative3_machine_learning.git)

# Navigate to the project folder
cd Formative3_machine_learning

# Install dependencies
pip install numpy pandas matplotlib scipy jupyter

# Launch the notebook
jupyter notebook
