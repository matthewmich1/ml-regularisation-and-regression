## **Project: Bias-Variance Tradeoff and Regularisation in Machine Learning**

### Overview
Investigated the impact of model complexity and regularisation on predictive performance using polynomial, 
Ridge, Lasso, and logistic regression models.
Evaluated bias–variance trade-offs, generalisation error, and model selection using cross-validation and Scikit-learn pipelines.

### Key Concepts & Skills Demonstrated
- Supervised Machine Learning
- Polynomial Feature Engineering
- Bias–Variance Trade-off Analysis
- Ridge Regression 
- Lasso Regression
- Logistic Regression
- Model Selection and Hyperparameter Tuning
- Cross-Validation
- Training vs Test Error Analysis
- Generalisation Performance
- Feature Selection
- Machine Learning Pipelines
- Classification and Regression Modelling
- Data Visualisation

### Technologies Used
- Python
- NumPy
- Pandas
- Scikit-learn
- Matplotlib
- Jupyter Notebook

### Results
<img width="556" height="301" alt="bias-variance-tradeoff" src="https://github.com/user-attachments/assets/50b92fe3-b7ee-410b-9234-a1f3bfcb5084" />

Training and testing mean squared error (MSE) as a function of model complexity. From the plot we see that the polynomial regression model with k = 8 has the best bias-variance 
tradeoff.


<img width="395" height="276" alt="l2-regularisation" src="https://github.com/user-attachments/assets/f975b555-97d1-4808-b999-cd94fdf29178" />

Applied Ridge regularisation to a polynomial regression model and selected the optimal penalty parameter ($λ≈0.234$) by minimising the test MSE over candidate values. 
The resulting model achieved a smooth fit that captured the underlying trend while reducing overfitting.










