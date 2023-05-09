>📋  A template README.md for code accompanying a Machine Learning paper

# Reproducing sEHR-CE: Language modelling of structured EHR data for efficient and generalizable patient cohort expansion


## Requirements

To install requirements:

```setup
pip install transformers 
 
```
## Training

To train the model(s) in the paper, run this command:

```train
Model_finetuning_2tests.ipynb 
```

>📋  Describe how to train the models, with example commands on how to train the models in your paper, including the full training procedure and appropriate hyperparameters.

## Pre-trained Models

You can download pretrained models here:

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


