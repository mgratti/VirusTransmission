# VirusTransmission

Simplified simulation of an epidemic in a jupyter notebook.

Developed for the Physics Praktikum, Spring Semester 2021.

The repository contains:

- the up-to-date [experiment manual](./73_Manual_Statistical_Physics__Virus_Transmission.pdf)
- the jupyter notebook [SimpleVirusTransmissionV1.ipynb](./notebooks/SimpleVirusTransmissionV1.ipynb) containing the classes and the detailed tasks
- an environment file for anaconda [mg_environment.yml](mg_environment.yml)

Please, read carefully the manual and the indications therein, including getting acquainted with the notebook.

To run the notebook, you need recent python and numpy versions and, of course, jupyter.

If you use anaconda, do:
```
conda env create -n virus --file mg_environment.yml
conda activate virus
```

## Solutions

Solutions to the tasks can be found in the notebook [SimpleVirusTransmissionV1Solution.ipynb](./notebooks/SimpleVirusTransmissionV1Solution.ipynb)

Explicit solution of the differential equation can be found (hand-written) in [diff_eq_solution.pdf](./images/diff_eq_solution.pdf)

Error treatment for exercise 1 can be found in a separate notebook [AppendixErrorTreatment.ipynb](./notebooks/AppendixErrorTreatment.ipynb)
