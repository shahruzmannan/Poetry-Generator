# Poetry Generator
Implemented a Poetry Generator using Long short-term memory networks (LSTM) with word2vec embeddings as a term project.

1. Install all necessary packages (can be done straight in Jupyter Notebook)
	* !pip install pandas
	* !pip install numpy
	* !pip install matplotlib
	* !pip install tensorflow
	* !pip install sklearn

2. The dataset used for this project is [Complete poetryfoundation.org dataset](https://www.kaggle.com/johnhallman/complete-poetryfoundationorg-dataset)
2. To open tensorboard, run either one of the commands below:
	* run `tensorboard --logdir logs/fit` in anaconda prompt in the folder
	* run `%tensorboard --logdir logs/fit` in jupyter notebook after the training cell
4. If old logs want to be removed, just delete the logs folder
5. If checkpoint want to be removed, delete weights.best.hdf5 file
6. More information about this project can be read from **Poetry Generator.pdf**
