# CS6220-HW-5
# Installation
- Download and follow instruction for Deepwalk: https://github.com/phanein/deepwalk <br>
- Install conda from: https://www.anaconda.com/ <br>
- Extract all files into a folder <br>
- In the root of the folder run the following line using conda command line<br>
```
conda env create -f environment.yml
```
```
conda activate HW5
```
- Run the deep_walk.ipynb <br>
- Run all cells and the models should results as .csv files and embeddings will be in the /output folder<br>
- The graphs and stats will also be pasted in the cells on the notebook file
# Files
- congress.csv: The final printout for the congress dataset which contains top K recommendations
- facebook.csv: The final printout for the facebook dataset which contains top K recommendations
- congress.txt: uncleaned edge list (gets cleaned in notebook file, but is the raw edge list from the downloaded dataset)
- congress_edgelist.txt: cleaned edge list
- facebook_combined.txt: edge list from the dataset downloaded
- README.md: readme file containing information about the repo
- deep_walk.ipynb: Model file that runs everything
- environment.yml : env file that has all the used packages/versions
- outputs: contains the outputs of deepwalk which are the embeddings for both of the datasets

