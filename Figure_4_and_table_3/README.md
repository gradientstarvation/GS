# CelebA with gender bias experiment
The provided code is a modified version of the code in https://github.com/kohpangwei/group_DRO

Run `table_2.sh` to reproduce the results of the paper.

Expected results:
```
# ERM:     
Average test accuracy over 10 runs: 94.61 % (pm 0.67)
Worst Case test accuracy over 10 runs: 40.35 % (pm 1.68)

# SD:
Average test accuracy over 10 runs: 91.64 % (pm 0.61)
Worst Case test accuracy over 10 runs: 83.24 % (pm 2.01)

# Group DRO:
Average test accuracy over 10 runs: 91.76 % (pm 0.28)
Worst Case test accuracy over 10 runs: 87.78 % (pm 0.96)
```