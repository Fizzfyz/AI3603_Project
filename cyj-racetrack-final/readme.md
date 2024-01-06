# SAC and WC-SAC for racetrack

usage: 

environment: 

```shell
    conda create -n racetrack python=3.8
    conda activate racetrack
    pip install -r requirements.txt

```

train: 

SAC

```shell

    cd ./racetrack_SAC
    python train trainRacetrack.py

```
SC-SAC:

```shell

    cd ./racetrack_WCSAC
    python train trainRacetrack_wcsac.py

```

The hyper-parameters of the corresponding model is saved in `hyperparameters.txt`