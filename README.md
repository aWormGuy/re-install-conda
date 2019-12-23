# re-install-conda
Re-install conda
Back to the quarterly cycle of deleting and re-instaling conda to get things to work :(

# Step 1
1. Move the existing conda folder to a different one : Effectively deleting the current conda installation.
`cd; cd work;`
`mv my_miniconda3 my_miniconda3_deleted20191222`

2. Install a fresh version of Miniconda; Install basic packages from my basic list : See `set-up-cluster-conda.20191222.sh` , which takes as input the file `conda-basic-packages-20191009.txt`
3. Create all the differet environments by running `conda-new-environments.20191222.sh`

# Step 2: 
1. Configure Perl

