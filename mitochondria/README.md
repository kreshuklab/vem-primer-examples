# Data Analysis: Mitochondria

Analysis workflow for mitochondria: data preparation, semantic + instance segmentation and (simple) downstream analysis to determine the mitochondria size distribution. 

![mito-em-analysis](https://user-images.githubusercontent.com/4263537/146000127-84b4b6e0-2b52-402c-b6b6-e8969f272025.png)

This example is focused on more advanced analysis using python, in particular making use of
a pretrained network for mitochondria segmentation from [the bioimageio modelzoo](https://bioimage.io).
This analysis approach is suitable for most structures that have clearly identifiable boundaries.
To apply it to a different EM modality or organelle, you will need to train your own network, see below.

- 1_data_preparation.ipynb: Download the example data, convert to suitable file format, downsample data. [Open in colab](https://colab.research.google.com/github/kreshuklab/vem-primer-examples/blob/main/mitochondria/1_data_preparation.ipynb)
- 2_semantic_segmentation.ipynb: Segment mitochondria into foreground and boundaries. [Open in colab](https://colab.research.google.com/github/kreshuklab/vem-primer-examples/blob/main/mitochondria/2_semantic_segmentation.ipynb)
- 3_instance_segmentation.ipynb: Segment individual mitochondria based on the semantic segmentation. [Open in colab](https://colab.research.google.com/github/kreshuklab/vem-primer-examples/blob/main/mitochondria/3_instance_segmentation.ipynb)
- 4_visualization_and_analysis.ipynb: Visualize the segmentation and analyse the size distribution of mitochondria. [Open in colab](https://colab.research.google.com/github/kreshuklab/vem-primer-examples/blob/main/mitochondria/4_visualization_and_analysis.ipynb)
- 5_advanced_visualization.ipynb: Prepare a MoBIE project for advanced visualization and data exploration. [Open in colab](https://colab.research.google.com/github/kreshuklab/vem-primer-examples/blob/main/mitochondria/5_advanced_visualization.ipynb)

## Training the segmentation network (Advanced)

[Open in colab](https://colab.research.google.com/github/kreshuklab/vem-primer-examples/blob/main/mitochondria/advanced_network_training.ipynb)

## Alternative approaches

### Data preparation using the BigDataProcessor Fiji Plugin

### Semi-automatic segmentation wth the ilastik carving workflow
