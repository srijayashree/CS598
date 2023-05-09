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


## Results

| Model name         				| Heart failure   		| Diabetes		 	     |
| ----------------------------------|----------------------	| -----------------------|
|									|	Recall 	|	 ACN	|	Recall		|   ACN	 |
| Original paper				    |     .85   | 	 0.69	|  .74          |   .74  |
| Project						    |     .55   |    0.85	|  .0           |   .53  |

