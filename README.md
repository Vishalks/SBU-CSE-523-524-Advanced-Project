# SBU-CSE-523-524-Advanced-Project
This repository contains code related to my Masters' advanced project on Missing Data Imputation using GANs.

# Installation
This project is implemented in python 3.7 and tensorflow 1.x. Follow these steps to setup your environment:
1. [Download and install Conda](http://https://conda.io/projects/conda/en/latest/user-guide/install/index.html "Download and install Conda")

2. After Anaconda has been installed, open up the terminal (Unix) or Anaconda prompt (Windows).
Create a new environment where Tensorflow and related dependencies are installed.
	```bash
	conda create --name tf-env
  	```

3. Activate the new *tf-env* environment.

	```bash
	conda activate tf-env
	```
  
4. Run your Python IDE from this environment, for example:

	```bash
	jupyter notebook
	```
	or

	```bash
	spyder
	```
  5. Open main.ipynb and mention the dataset among the 3 datasets - college, spam, letter for which you want to run the GAIN algorithm. A csv will be generated for the imputed data which we can use for analysis.
  
  6. For visualizing the imputation accuracy thrugh various plots, run visualisation.ipynb.
