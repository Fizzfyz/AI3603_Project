## Environment

We use [conda](https://anaconda.org/anaconda/conda) to make and manage python environments.

1. `conda create -n highway python=3.8`
2. `conda activate highway`
3. `pip install -r requirements.txt`

## Running Guide

### Train

```shell
bash runIntersection.sh
bash runHighway.sh
bash runParking.sh
bash runRaceTrach.sh
```

More detailed hyperparameters are located in(highway for example):

``` shell_tree
.
├── eval_files/
│   ├── models 
|       ├── highway
|           ├── hyperparameters.txt


```
### Eval

```shell
cd eval_files
python eval_highway.py
python eval_intersection.py
python eval_parking.py
python eval_racetrack.py
```

### Results

![img](https://github.com/Fizzfyz/AI3603_Project/blob/final/firgure/highway.gif)
![img](https://github.com/Fizzfyz/AI3603_Project/blob/final/firgure/intersection.gif)
![img](https://github.com/Fizzfyz/AI3603_Project/blob/final/firgure/racetrack.gif)
![img](https://github.com/Fizzfyz/AI3603_Project/blob/final/firgure/parking.gif)


