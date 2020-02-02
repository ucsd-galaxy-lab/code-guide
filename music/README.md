# MUSIC

## Compiling

### Dependencies

- FFTW (both 2 and 3 are okay)
- GSL
- HDF5

### General Procedure

- Edit the Makefile according to the specific HPC
    - Make sure the MPI compiler is set correctly
    - Make sure the OpenMP option is set correctly
    - Make sure dependency paths are included
- `make`

## Run

```console
MUSIC music.conf
```

Details of configuration file parameters could be found in the User's Manual.

## Links

- [Code repo](https://bitbucket.org/ohahn/music/)
- [User's Manual](https://bitbucket.org/ohahn/music/downloads/MUSIC_Users_Guide.pdf)
