# vem-primer-examples

Data analysis examples for the vEM primer (under developments).

## Examples

Here, we show two example data analysis workflows for volume electron microscopy.
- In the `neurons` example we segment neural processes in a small TEM volume of fruit-fly brain tissue, which is provided by [the CREMI segmentation challenge](https://cremi.org/). Here, we use the ilastik neural network and multicut workflow for segmentation.
- In the `mitochondria` example we segment and analyse mitochondria in a SBEM volume of human cortex, which is provided by [the MitoEM segmentation challenge](https://mitoem.grand-challenge.org/). Here, we segment and analyse the data using python notebooks. 

For both examples we also present some alternative segmentation approaches. In order to run these examples you will need to install a recent version (1.4 or newer) of [ilastik](https://www.ilastik.org/) for the `neurons` example.
The python notebooks can either be run on google colab (links are available in the example folders) or on your own system using conda (see below).


## Setting up conda environments (advanced)

You can install either `environment_cpu.yaml` (if your machine does not have a GPU) or `environment_gpu.yaml` (if your machine has a GPU) via:
```
conda env create -f environment_cpu.yaml
```
or
```
conda env create -f environment_gpu.yaml
```
Then activate it via
```
conda activate vem-primer-cpu
```
or
```
conda activate vem-primer-gpu
```
You can then start a notebook server via `jupyter notebook`.

Note that you will need to update the CUDA version in [environment_gpu.yaml](TODO) according to your system specifications.
