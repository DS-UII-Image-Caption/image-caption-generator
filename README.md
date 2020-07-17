# image-caption-generator

Image Caption Generator Bahasa Indonesia with CNN &amp; LSTM

![image](https://drive.google.com/uc?export=view&id=1kWQGTA6Rd44TeKMHWUmUCCxxMB5gbVpm)


## Table of Contents

1. [Requirements](#1-requirements)
2. [Project Files Structure](#2-project-files-structure)
3. [How To Run](#3-how-to-run)
4. [Result Testing](#4-result-testing)


## 1. Requirements

Recommended System Requirements to train model.

<ul type="square">
	<li>A good CPU and a GPU with atleast 8GB memory</li>
	<li>Atleast 8GB of RAM</li>
</ul>

Required libraries for Python along with their version numbers used while making & testing of this project

<ul type="square">
	<li>Python</li>
	<li>Numpy</li>
	<li>Tensorflow-GPU</li>
	<li>Keras</li>
	<li>Nltk</li>
	<li>PIL</li>
	<li>Matplotlib</li>
	<li>Tqdm</li>
</ul>

<strong>Dataset:</strong> Download dataset Flickr_8k:

<ul type="square">
	<li>Flickr8k_Dataset</li>
	<li>Flickr8k_text</li>
	Download Link:<a href="https://drive.google.com/drive/folders/1fiP5oFZsoa2iHYG0pTpOUzCzpBTzdPzC?usp=sharing"> Download</a>
</ul>



## 2. Project Files Structure

The below files will be created by us while making the project.

- **Models** : It will contain our trained models.
- **Descriptions.txt** : This text file contains all image names and their captions after preprocessing.
- **Features.p** : Pickle object that contains an image and their feature vector extracted from the Xception pre-trained CNN model.
- **Tokenizer.p** : Contains tokens mapped with an index value.
- **Model.png** : Visual representation of dimensions of our project.
- **Training_caption_generator.ipynb** : Jupyter notebook in which we train and build our image caption generator.
- **Testing_caption_generator.py** : Python file for generating a caption of any image.



## 3. How To Run

1. Download Dataset, then put the required dataset files in `Dataset` folder.
2. Download utils file, then put root folder
3. Run `training_caption_generator` via Jupyter Notebook
4. You can download pre-trained model without run `training_caption_generator`
5. Run `testing_caption_generator` with terminal <br>
```python testing_caption_generator.py -i "Dataset\test_img\IC3.jpg"```


## 4. Result Testing

1. Report project (PDF).
2. Slide presentation project
3. Video testing project
4. Images of result testing

The result testing: [LINK](https://drive.google.com/drive/folders/1cfqdFWQ0azcrIShGUFaqzwB9oOW112SF?usp=sharing)
