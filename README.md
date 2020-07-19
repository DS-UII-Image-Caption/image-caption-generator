# image-caption-generator

Image Caption Generator Bahasa Indonesia with CNN &amp; LSTM

![image](https://drive.google.com/uc?export=view&id=1kWQGTA6Rd44TeKMHWUmUCCxxMB5gbVpm)


## Table of Contents

1. [Contributors](#1-contributors)
2. [Requirements](#2-requirements)
3. [Project Files Structure](#3-project-files-structure)
4. [How To Run](#4-how-to-run)
5. [Result Testing](#5-result-testing)

<br>


## 1. Contributors

<table>
 	<tr>
		<td align="center"><a href="https://github.com/DedeBrahma"><img src="https://avatars2.githubusercontent.com/u/7386006?s=460&u=6093910d6194fc6df127f0b52d8d5be5f0fbc41e&v=4" width="100px;" alt=""/><br /><sub><b>Dede Brahma</b></sub></a></td>
		<td align="center"><a href="https://github.com/fahminurrahim"><img src="https://avatars3.githubusercontent.com/u/55684889?s=460&u=d2e28a8186229c3b87b463e13396a4d666a16d63&v=4" width="100px;" alt=""/><br /><sub><b>Fahmi Nurrahim</b></sub></a></td>
		<td align="center"><a href="https://github.com/yopiazani02"><img src="https://avatars2.githubusercontent.com/u/55723941?s=460&u=961af8317996e4cd0fc59b8fc2151fea8d53d93c&v=4" width="100px;" alt=""/><br /><sub><b>Yopi Azzani</b></sub></a></td>
	</tr>
</table>


## 2. Requirements

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



## 3. Project Files Structure

The below files will be created by us while making the project.

- **Models** : It will contain our trained models.
- **Descriptions.txt** : This text file contains all image names and their captions after preprocessing.
- **Features.p** : Pickle object that contains an image and their feature vector extracted from the Xception pre-trained CNN model.
- **Tokenizer.p** : Contains tokens mapped with an index value.
- **Model.png** : Visual representation of dimensions of our project.
- **Training_caption_generator.ipynb** : Jupyter notebook in which we train and build our image caption generator.
- **Testing_caption_generator.py** : Python file for generating a caption of any image.



## 4. How To Run

1. Download Dataset, then put the required dataset files in `Dataset` folder.
2. Download utils file, then put root folder
3. Run `training_caption_generator` via Jupyter Notebook
4. You can download pre-trained model without run `training_caption_generator`
5. Run `testing_caption_generator` with terminal <br>
```python testing_caption_generator.py -i "Dataset\test_img\IC3.jpg"```


## 5. Result Testing

1. Report project (PDF).
2. Slide presentation project
3. Video testing project
4. Images of result testing

Result Testing Link: [Download](https://drive.google.com/drive/folders/1cfqdFWQ0azcrIShGUFaqzwB9oOW112SF?usp=sharing)
