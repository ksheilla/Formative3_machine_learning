## Probability Distributions & Gradient Descent Analysis ##
## Group Members:
Celine LAURA ISHMWE, Loic HIGIRO, Ulrich RUKAZAMBUGA, Sheilla KEZA RUVUGABIGWI
## PDF for manual calculations and contributions: 
<link>
## Overview ##

This project explores the intersection of statistical theory and machine learning optimization. It covers the implementation of probability distributions from scratch, the application of Bayesian probability to NLP (Sentiment Analysis), and the manual and programmatic execution of Gradient Descent for linear regression.

 ## Project Structure ##
The repository is organized into four main components:
## Part 1: Bivariate Normal Distribution
Dataset: [BMI Dataset]
Implementation: Developed the Bivariate Normal PDF from scratch using Python (no statistical libraries).
Visualization: Included 3D Surface plots and 2D Contour plots to analyze the joint probability density of Height and Weight.

## Part 2: Bayesian Sentiment Analysis
Dataset: IMDb Movie Reviews .
Methodology: Applied Bayes' Theorem to calculate the posterior probability of a review being Positive given specific keywords.
Logic: Implemented modular Python functions to calculate Prior, Likelihood, and Marginal probabilities.

## Part 3 & 4: Gradient Descent Optimization
Objective: Optimize m (slope) and b (intercept) for the points (1,3) and (3,6).
Manual Calculation: Four iterative updates performed by each group member, documented in the attached PDF.
Programmatic Implementation: SciPy-based gradient descent with a visible update loop to visualize convergence.
Analytics: Plots tracking the reduction of Mean Squared Error (MSE) and parameter convergence.

## How to Run ##
git clone https://github.com/ksheilla/Formative3_machine_learning.git
cd project-folder
pip install -r requirements.txt
jupyter notebook

## Requirements ##

Python 3.10+

numpy

pandas

matplotlib

scipy

jupyter
