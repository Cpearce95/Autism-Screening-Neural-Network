# Autism-Screening-Neural-Network
Sequential Neural Network Model for the Detection of Autism amongst individuals.
As part of the nine-week project, a sequence neural network model was planned, designed, and implemented to perform an Autism screening task and make predictions for the diagnosis of Autism within children. The initial intentions were to utiliise the model and incorporate the technologies into a ChatBot application which encompassed the neural network model. However, due to the actual events of the project and a change request occuring in week 6, the decision was made to finalise and test the developed sequential ensuring the quality of work produced remained high and in line with the overall integrity of the project. The following section details the Autism screening solution completed for the project sponsor as part of the project. The solution was developed using Anaconda Python using Theano backend, Jupyter Lab used for running the ipython scripts with Keras, whilst Pandas was use for the dataframe holding the data from the imported UCI machine learning dataset.

The following software packages and libraries are required to successfully compile and run the project neural network solution. 
Anaconda
Python == 2.7.6 
Jupyterlab 
Theano == 1.0.4
Keras == 2.1.4
Sklearn == 0.20.3
Pandas == 0.24.2

Solution Technical Instructions
1. Install Python version 2.7

2. Install the Anaconda Data Science platorm

	https://www.anaconda.com/

3. Open an Anaconda command prompt.

4. Install pip Python package manager.

To install pip, download get-pip.py.

	curl https://bootstrap.pypa.io/get-pip.py -o get-pip.py

Then run the following:

	python get-pip.py



5. Install the following dependencies with pip.

	pandas 0.24.2

		pip install pandas==0.24.2

	sklearn 0.20.3

		pip install numpy scipy scikit-learn==0.20.3

	keras 2.1.4

		pip install keras==2.1.4

	theano 1.0.4

		pip install theano==1.0.4

	jupyterlab

		pip install jupyterlab


6. Set the backend configuration of keras to use theano instead of default tensorflow.

	Navigate to your home directory.
	Navigate to the .keras directory.

	Edit keras.json so that the value for "backend" is set to "theano"

	E.G.

	{
    	"epsilon": 1e-07, 
    	"floatx": "float32", 
    	"image_data_format": "channels_last", 
    	"backend": "theano"
	}

7. Clone the repository
8. Navigate to the directory

9. Run:

	jupyter lab

10. A browser will open up with the directory contents in the jupyter lab environment.

	Open autism_screening.ipynb from the left handside file directory system.

	This file contains the python machine learning scripts.

	Under the upper left "Run" menu.
