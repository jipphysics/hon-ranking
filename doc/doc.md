# Documentation

The code is composed of a single [Jupyter notebook](https://github.com/jipphysics/hon-ranking/blob/main/code/hon-ranking.ipynb).

You will see in the notebook, that there is some code common to all experiments and there is some code specific to the experiments of each network model. With this code, you can generate the raw data, which is basically composed of samples of the inference of ratings and rankings of network samples. The data is stored as dictionaries saved in JLD2 format (see the [data](https://github.com/jipphysics/hon-ranking/tree/main/data) folder).
The code to run the simulations to generate the data is commented, to avoid the accidental overwritting of the data provided in the data folder.
To reproduce the results, you can uncomment such code, but be aware the it may take several days to run.
Then, at the end of the notebook, you can find extra code to agregate the generated data to perform the analysis and plots of the manuscript.
