#### smatthews39
#### Sean Matthews

# Unsupervised Learning and Dimensionality Reduction

## Requirements
You will need to use python 3.x with this code, and to pip install the packages in `requirements.txt`.

## How to run
1. Run All experiments first by `python run_experiment.py --all`
2. Plot the results `python run_experiment.py --plot` to see some graphs
3. Run `run_clustering.sh`
4. One final run to plot the rest `python run_experiment.py --plot` which will add plots for parts 4 and 5

## Graphing

The run_experiment script can be use to generate plots via:

```
python run_experiment.py --plot
```

Since the files output from the experiments follow a common naming scheme this will determine the problem, algorithm,
and parameters as needed and write the output to sub-folders in `./output/images`.

