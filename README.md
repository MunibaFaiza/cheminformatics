# cheminformatics
## Perform operations on chemical structures using Python.

### Introduction
**_pdb_ligand_id-to-smi.ipynb_** notebook demonstrates how to obtain SMILES of ligands using ligand ID from PDB.

**_sdftosmi.py_** script will convert molecules in sdf format into their corresponding SMILES. All molecules are provided in a single SDF file as input.

**_smitostr.py_** will convert smiles to structure.

### Requirements
It requires Python3. This script uses RDKit and some additional packages. Install them using the following commands.

`conda create -c conda-forge -n my-rdkit-env rdkit`

`conda install pandas`

### Usage
To get SMILES from ligand IDs, save all ligand IDs in a CSV file (lig-ids.csv) and run the notebook.
The other two scripts are simple Python scripts that you can easily run in a terminal.

For more information, read this article:
https://bioinformaticsreview.com/20221120/how-to-obtain-smiles-of-ligands-using-pdb-ligand-ids/
