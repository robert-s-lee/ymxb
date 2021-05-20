These are steps for setting up Grid.AI CLI using `conda`.  
In the machine learning world, the standard is `conda`.
Virtu 

# (Setup Virtual Environments)[https://docs.grid.ai/products/global-cli-configs/virtual-environments]

## install (miniconda)[https://docs.conda.io/en/latest/miniconda.html]

Used (Python 3.9 Pkg)[https://repo.anaconda.com/miniconda/Miniconda3-py39_4.9.2-MacOSX-x86_64.pkg]

start a new iterm2


https://platform.grid.ai/#/settings?tabId=apikey


```
conda create --name gridai python=3.7

conda activate gridai

pip install lightning-grid --upgrade
```


The following environemnts are available for testing.
```
export GRID_URL=https://platform.grid.ai 	# production
export GRID_URL=https://staging.grid.ai		# staging
export GRID_URL=https://qa.grid.ai		# qa

```

For experiments, (NYC Taxi and Limousine Commission TLC public datasets)[https://www1.nyc.gov/site/tlc/about/tlc-trip-record-data.page] will be used

https://www1.nyc.gov/site/tlc/about/tlc-trip-record-data.page

