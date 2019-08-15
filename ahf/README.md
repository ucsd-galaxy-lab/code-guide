# AHF Example

This example shows how to compile and run AHF on TSCC.

First, reset the modules:
```console
module purge
module load intel openmpi_ib hdf5
module list
```

Then, compile:
```console
make compile
```

Finally, run:
```console
make run
```

The results could be checked in the `run` directory.

To submit a job script to run AHF for multiple snapshots use:
'''console
make submit
'''
