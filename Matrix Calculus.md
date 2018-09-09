# Matrix Calculus

## 基本法则

情形：$\frac{\part Y}{\part X}$ 

* 当 $X$ 或 $Y$ 其中之一是标量时，结果的维数与另一个变量完全相同。

* 当 $X$ 和 $Y$ 都是向量时，结果为 Jacobian 矩阵。

  $$
  \frac{\partial \mathbf{y}}{\partial \mathbf{x}} =
  \begin{bmatrix}
  \frac{\partial y_1}{\partial x_1} & \frac{\partial y_1}{\partial x_2} & \cdots & \frac{\partial y_1}{\partial x_n}\\
  \frac{\partial y_2}{\partial x_1} & \frac{\partial y_2}{\partial x_2} & \cdots & \frac{\partial y_2}{\partial x_n}\\
  \vdots & \vdots & \ddots & \vdots\\
  \frac{\partial y_m}{\partial x_1} & \frac{\partial y_m}{\partial x_2} & \cdots & \frac{\partial y_m}{\partial x_n}\\
  \end{bmatrix}
  $$

* 当 $X$ 和 $Y$ 都是矩阵时，结果为二阶张量。



