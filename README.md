# SpatioTemporalNormalisation

This repository consists of 3 jupyter notebooks that come together in order to display the optimal normalisation strategy for SpatioTemporal Graphs.

The conclusion from running our experiments were that the [UnitedNorm](https://arxiv.org/pdf/2009.11746.pdf) technique that utilises a coalescence of LayerNorm, InstanceNorm, BatchNorm, GraphNorm and TemporalNorm is most effective when dealing with SpatioTemporal Graphs when normalizing the inputs to smoothen out training and speed up convergence.

## Run Instructions:
The experiments can be run by opening the jupyter notebooks in Google Colab and following these steps:
1. Save the **SpatioTemporalNorm.ipynb** and the **SpatioTemporalNorm.ipynb** files in Google Drive within the same directory.
2. Change the following line of code in 5th cell of **SpatioTemporalNorm_Experiments.ipynb** to point to the Google Drive directory that you chose in Step 1 : `%cd "mnt/My Drive/Colab Notebooks/GDL/"`
3. Run the **SpatioTemporalNorm_Experiments.ipynb** file. 