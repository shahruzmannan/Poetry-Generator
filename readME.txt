1 . Install all necessary packages (can be done straight in jupyter notebook)
	-!pip install pandas
	-!pip install numpy
	-!pip intall matplotlib
	-!pip install tensorflow
	-!pip install sklearn

2. To open tensorboard
	a) run tensorboard --logdir logs/fit in anaconda prompt in the folder

or 	b) run %tensorboard --logdir logs/fit in jupyter notebook after the training cell

3. If old logs want to be removed, just delete the logs folder from the project folder

4. If checkpoint want to be removed, delete weights.best.hdf5 file