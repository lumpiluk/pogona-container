# pogona-container
Singularity container definition for the upcoming Pogona simulator

[![https://www.singularity-hub.org/static/img/hosted-singularity--hub-%23e32929.svg](https://www.singularity-hub.org/static/img/hosted-singularity--hub-%23e32929.svg)](https://singularity-hub.org/collections/4128)

## Usage

To build the container image, install Singularity – now called [Apptainer](https://apptainer.org/)? – and run the following command:

```bash
./singularity_build.sh
```

**WARNING**: Singularity-hub has been discontinued and only an archived version of the singularity container is still available with the command below. Unfortunately, newer versions of OpenFoam appear to be incompatible with our OpenFoam simulation cases for the Pogona simulator for unknown reasons. Please follow the instructions above to build a compatible version 1912 container.

To use a pre-built image, first pull it from Singularity Hub:

```bash
singularity pull shub://lumpiluk/pogona-container
```

Afterwards, you can open a subshell using the image by running

```bash
./singularity_shell.sh
```

From there, all prerequisites for running OpenFOAM simulations should be available.
