# piecewise_jerk_path_optimizer
Pure C piecewise jerk path optimizer of Apollo for S-L Planning

*Note* This project heavily depends on the following open-source repos:

[qpSwift](https://github.com/qpSWIFT/qpSWIFT) Light-weight sparse Quadratic Programming Solver

[sparse_matrix_conversion](https://github.com/kmpape/sparse_matrix_conversion) Utilities to convert dense matrix formats to sparse matrix formats and the reverse.

## Results

+ Matlab quadprog path problem

![](./Matlab/matlab.png)

+ Matlab quadprog speed problem

  ![](./Matlab/QP_speed.png)

## Dev Tasks

- [x] Construct a typical QP demo using the sparse_matrix_conversion Tool for creating sparse matrix.
- [x] Construct a typical Piecewise_Jerk_Path QP problem using Matlab quadprog function.
- [x] Construct a typical Piecewise_Jerk_Speed QP problem using Matlab quadprog function.
- [ ] Perform  piecewise_jerk_path_optimizer task in pure c code.
