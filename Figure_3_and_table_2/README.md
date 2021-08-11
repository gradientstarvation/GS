# Colored MNIST with color bias
The provided code is a modified version of the code in https://github.com/facebookresearch/InvariantRiskMinimization
Please read the LICENSE file obtained from https://github.com/facebookresearch/InvariantRiskMinimization

Run `table_1.sh` and `fig_4.py` to reproduce the results of the paper.
Expected results:
```
# ERM:     
Average train accuracy over 10 runs: 91.08 % (pm 0.43)
Average test accuracy over 10 runs: 23.70 % (pm 0.76)

# SD:
Average train accuracy over 10 runs: 70.04 % (pm 0.91)
Average test accuracy over 10 runs: 68.40 % (pm 1.24)

# IRM:
Average train accuracy over 10 runs: 70.54 % (pm 0.67)
Average test accuracy over 10 runs: 67.08 % (pm 1.47)
```