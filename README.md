# Face_Generation_pytorch_udacity

This project is a part of deep learning nano degree at udacity.

## Project Overview:

This project, uses generative adversarial networks to generate new images of faces.In this project, you'll define and train a DCGAN on a dataset of faces. Your goal is to get a generator network to generate new images of faces that look as realistic as possible!

The project will be broken down into a series of tasks from loading in data to defining and training adversarial networks. At the end of the notebook, you'll be able to visualize the results of your trained Generator to see how it performs; your generated samples should look like fairly realistic faces with small amounts of noise.

<img src="assets/processed_face_data.png">

## Project Overview:

1. Clone the repository and navigate to the downloaded folder.

    `git clone https://github.com/DhruvMakwana/Face_Generation_pytorch_udacity.git`
    
2. Install PyTorch and torchvision; this should install the latest version of PyTorch.
	* Linux or Mac:
	
		`conda install pytorch torchvision -c pytorch`
	
	* Windows:
			
			`conda install pytorch -c pytorch`
			`pip install torchvision`
3. Make sure you have already installed the necessary Python packages according to the requirements.txt file.
		
	`pip install -r requirements.txt`
	
or

	`conda install --yes --file requirements.txt`

4. Open a terminal window and navigate to the project folder. Open the notebook and follow the steps.

    `jupyter dlnd_face_generation.ipynb`
