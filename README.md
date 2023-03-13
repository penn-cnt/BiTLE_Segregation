# Repository for analyses related to the manuscript: "Resting State Functional Connectivity Demonstrates Increased Segregation in Bilateral Temporal Lobe Epilepsy"

For the full manuscript see: https://doi.org/10.1111/epi.17565

## Accessing the fully processed connectivity matrices

Links to the fully processed functional connectivity matrices are available here: https://osf.io/xs2q6/

## Running the analyses

We provide a stand-alone Jupyter notebook as a companion to the manuscript. The notebook runs all the analyses required to generate the figures and findings in the manuscript.

### Installing the Conda virtual environment

Please make sure you have [Anaconda](https://www.anaconda.com/) installed. After cloning, open the repository folder in a terminal window and type: 
```
conda env create -f bitle_segregation.yml
```
this will create a new Python virtual environment with all the required libraries

Activate the environment with: 
```
conda activate bitle_segregation
```

### Running the Jupyter notebook

In order to run the analysis, clone this repository, install the conda virtual environment and download the processed functional connectivity matrices from the OSF link above. After download, place the downloaded binary file in the `/data` folder and open the the `code/processing_analysis_final.ipynb` notebook. If the conda environment was setup appropriately and the connectivity matrices were placed in the correct folder, everything should run correctly.
