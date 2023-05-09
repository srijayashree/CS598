>📋  A template README.md for code accompanying a Machine Learning paper

# Reproducing sEHR-CE: Language modelling of structured EHR data for efficient and generalizable patient cohort expansion


>📋  Optional: include a graphic explaining your approach/main result, bibtex entry, link to demos, blog posts and tutorials

## Requirements

To install requirements:

```setup
pip install transformers 
 
```

>📋  Describe how to set up the environment, e.g. pip/conda/docker commands, download datasets, etc...

## Training

To train the model(s) in the paper, run this command:

```train
Model_finetuning_2tests.ipynb 
```

>📋  Describe how to train the models, with example commands on how to train the models in your paper, including the full training procedure and appropriate hyperparameters.

## Pre-trained Models

You can download pretrained models here:

- [My awesome model](https://colab.research.google.com/drive/1xlLYSoa_5tWJ2ekAAZZV_P0nOWN1HFf8#scrollTo=lD9afARpmTWh) trained on MIMC-iii datasets. 

>📋  Give a link to where/how the pretrained models can be downloaded and how they were trained (if applicable).  Alternatively you can have an additional column in your results table with a link to the models.

## Results

Our model achieves the following performance on :

### [Image Classification on ImageNet](https://paperswithcode.com/sota/image-classification-on-imagenet)

| Model name         				| Heart failure   		| Diabetes		 	     |
| ----------------------------------|----------------------	| -----------------------|
|									|	Recall 	|	 ACN	|	Recall		|   ACN	 |
| Original paper				    |     .85   | 	 0.69	|  .74          |   .74  |
| Project						    |     .55   |    0.85	|  .0           |   .53  |


>📋  Include a table of results from your paper, and link back to the leaderboard for clarity and context. If your main result is a figure, include that figure and link to the command or notebook to reproduce it. 


