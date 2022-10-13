# pogona-container
Apptainer container definition for the upcoming Pogona simulator

## Usage

To build the container image, install [Apptainer](https://apptainer.org/) and run the following command:

```bash
./apptainer_build.sh
```

Afterwards, you can open a subshell using the image by running

```bash
./apptainer_shell.sh
```

From there, all prerequisites for running OpenFOAM simulations should be available.
