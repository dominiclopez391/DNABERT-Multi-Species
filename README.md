This version of DNABERT uses a modified package with a custom 26-species classification task. 
If you wish to use this version, please install this package to your environment, following the 
same steps to install DNABERT. 

 https://github.com/jerryji1993/DNABERT

Execute the pretrain.sh and finetune.sh scripts (optionally with Sbatch) to train a 26 species
DNABERT model, based on the MBARC-26 dataset. Due to its size, the multispecies_data folder was
moved to a separate Google drive download.

See Generate-Results-And-Visualize/ for files on how to generate predictions and the final hidden
layers for the test dataset, as well as visualizing the outputs in graphs and figures.
