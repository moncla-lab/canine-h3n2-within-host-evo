# canine-h3n2-within-host-evo
Repo for within-host evolution analyses on canine H3N2 sequences collected from PennVet in 2023

## Running the code:

### NumPy has compatibility issues with newer versions of SciPy so before running any of the analysis notebooks you need to create a conda environment with the compatible versions.

First, git clone this repo:

		gh repo clone moncla-lab/canine-h3n2-within-host-evo

Navigate your way into the repo:

		cd canine-h3n2-within-host-evo
		
Create a conda environment with the provided configuration file:

		conda env create -f env.yml
		
Activate the conda environment:

		conda activate within-host-prelim-analysis
