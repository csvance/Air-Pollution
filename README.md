# Air-Pollution 

Update 1/4/2019: 
To-Do:
1. Calculate min and max values for all columns ahead of time to assist with min max scaling
2. add K-means
3. refactor code for better indexing

PLAN:
"so conceptually heres the idea i have in my head for our pipeline
mpi_transform will transform the data to the format we need
then we have a windower/sequencer
which scales to the min/max
and records them
and then we create a feature enrichment script to add additional features?
so 3 seperate stages
"

Update 12/28/18:

Both Carroll and Nicholas have achieved great results in mean absolute error and mean squared error metrics using random forest and a LSTM. FFT was tried with little advantage in using it. The next step will be wavelet-transform. 

Work at scale on the cluster.
