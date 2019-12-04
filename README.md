## Accessing LENS Data on `/glade` with `intake-esm`

This repo gives a brief example of how to use `intake-esm` to read a catalog pointing to LENS data.
The catalog was created based on the `yaml` file in `collection_gen/`.
That directory also contains an older version of the `yaml` file and instructions on generating the intake `netCDF` file / converting it to `json` and `csv`.

### Using this repository

To help create a conda environment, `environment.yaml` from the [cesm2-marbl](https://github.com/marbl-ecosys/cesm2-marbl) repository is provided.
This will create an environment named `cesm2-marbl`.
To install (only needs to be done once):

```
$ conda env create -f environment.yaml
```

To use:
```
$ conda activate cesm2-marbl
```