# pogona-container
Singularity container definition for the upcoming Pogona simulator

[![https://www.singularity-hub.org/static/img/hosted-singularity--hub-%23e32929.svg](https://www.singularity-hub.org/static/img/hosted-singularity--hub-%23e32929.svg)](https://singularity-hub.org/collections/4128)

## Usage

To use a pre-built image, first pull it from Singularity Hub:

```bash
singularity pull shub://lumpiluk/pogona-container
```

Afterwards, you can open a subshell using the image by running

```bash
./singularity_shell.sh
```

From there, all prerequisites for running OpenFOAM simulations or setting up a Python Pipenv/Virtualenv for the Pogona simulator should be available.
