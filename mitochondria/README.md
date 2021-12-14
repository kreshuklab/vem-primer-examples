# Data Analysis: Mitochondria

Analysis workflow for mitochondria. This example is focused on more advanced analysis using python, in particular making use of
a pretrained network for mitochondria segmentation from [the bioimageio modelzoo](https://bioimage.io).
This analysis approach is suitable for most structures that have clearly identifiable boundaries.
To apply it to a different EM modality or organelle, you will need to train your own network, see below.

- 1_data_preparation.ipynb: Download the example data, convert to suitable file format, downsample data. [Open in colab](TODO)
- 2_semantic_segmentation.ipynb: Segment mitochondria into foreground and boundaries. [Open in colab](TODO)
- 3_instance_segmentation.ipynb: Segment individual mitochondria based on the semantic segmentation. [Open in colab](TODO)
- 4_visualization_and_analysis.ipynb: Visualize the segmentation and analyse the size distribution of mitochondria. [Open in colab](TODO)
- 5_advanced_visualization.ipynb: Prepare a MoBIE project for advanced visualization and data exploration. [Open in colab](TODO)

## Training the segmentation network (Advanced)

## Alternative approaches

### Data preparation using the BigDataProcessor Fiji Plugin

### Semi-automatic segmentation wth the ilastik carving workflow
