# Data Analysis: Neurons

Analysis workflow for neurons:

This example uses the ilastik neural network workflow to predict neuron boundaries with a pretrained network (semantic segmentation)
and then uses the multicut workflow to segment the individual neurons (instance segmentation). 
We use data from the [CREMI Neuron Segmentation Challenge](https://cremi.org/), which contains a ssTEM stack of neural tissue of the fruit-fly.

**Obtain the data:**

Download [Sample A+](https://cremi.org/static/data/sample_A%2B_20160601.hdf) from the CREMI website.

**Predict boundaries with ilastik:**

TODO short explanation + link to tutorial for neural network workflow and give DOI for the pretrained model we use
Upload example ilastik project here

**Segment neurons with ilastik:**

TODO short explanation + link to tutorial for multicut workflow
Upload eample ilastik project here

## Alternative approaches

### Instance segmentation with the Mutex Watershed (Advanced)

TODO add notebook
(before working on this recommend to go through the notebooks for MitoEM, which are similar but easier)

### Training affinity/boundary network (Advanced)

TODO add notebook
