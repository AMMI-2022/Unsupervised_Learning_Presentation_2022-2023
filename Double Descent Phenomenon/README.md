# Double_Descent_Phenomenon
The double descent phenomenon refers to a peculiar behavior observed in certain models where the
test error initially decreases as the model complexity increases, then reaches a minimum, and finally
increases again as the model becomes more complex. This phenomenon challenges the traditional
bias-variance tradeoff and suggests that adding more complexity to a model may not always lead to
overfitting.
Currently, the double descent phenomenon has been observed in models such as:

- Linear regression
- Linear Discriminant Analysis
- Logistic regression

On the other hand, there are still ongoing research and investigation to determine
whether or not the following models exhibit the double descent phenomenon:

- Quadratic Discriminant Analysis (work on Linear Discriminant Analysis may be extended)
- Random forests
- Support Vector Machines
- Neural networks with nonlinear activation

The double descent phenomenon has sparked significant interest in the machine learning com-
munity as it challenges our traditional understanding of model complexity and generalization error.
Further research is being conducted to better understand the underlying causes and implications of
this phenomenon in different models.

 Python Code
The code aims to investigate whether the double descent phenomenon occurs for a synthetic dataset
and how the regularization parameter affects the shape of the test error curve. Linear regression is
used as a simple model to test for double descent, and a function for the L2 regularizer is defined to
further analyze the phenomenon.
