# Data Analysis: Neurons

Analysis workflow for neurons:

This example uses the ilastik neural network workflow to predict neuron boundaries with a pretrained network (semantic segmentation)
and then uses the multicut workflow to segment the individual neurons (instance segmentation). 
We use data from the [CREMI Neuron Segmentation Challenge](https://cremi.org/), which contains a ssTEM stack of neural tissue of the fruit-fly.

**Obtain the data:**

Download [Sample A+](https://cremi.org/static/data/sample_A%2B_20160601.hdf) from the CREMI website.

**Predict boundaries with the ilastik neural network classification workflow:**

- Start ilastik
- Create a new `Neural Network Classification (Local)` project
- Add the CREMI data in the `Input Data` menu
- Select the pretrained CREMI model in the `NN Prediction` menu via TODO (FIXME latest ilastik version does not support 0.4+ yet)
- 

You can find an example project TODO
For more information check out the [neural network classification workflow documentation](https://www.ilastik.org/documentation/nn/nn)


TODO short explanation + link to tutorial for neural network workflow and give DOI for the pretrained model we use
Upload example ilastik project here

**Segment neurons with ilastik:**

TODO short explanation + link to tutorial for multicut workflow
Upload eample ilastik project here
https://www.ilastik.org/documentation/multicut/multicut

## Alternative approaches

### Instance segmentation with the Mutex Watershed (Advanced)

TODO add notebook
(before working on this recommend to go through the notebooks for MitoEM, which are similar but easier)

### Training affinity/boundary network (Advanced)

TODO add notebook
