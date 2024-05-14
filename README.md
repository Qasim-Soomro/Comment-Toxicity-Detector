# Comment Toxicity Detector

We train single CNN architecture for 2 epochs and comapre the classification scores. The data used is taken from [a dataset of comments](https://drive.google.com/file/d/1Sh5rQFwbP31oUpjj4ligVjdWb1OzWLBY/view?usp=sharing). The network achieves 98%+ peak accuracy in classification.

## STEP 1: Getting the train.cvs file
You can [download  train.cvs  here](https://drive.google.com/file/d/1Sh5rQFwbP31oUpjj4ligVjdWb1OzWLBY/view?usp=sharing)

## STEP 2: Installing Requirements
	
	python3 -m pip install -r requirements.txt

## STEP 3: Running
Executing the code for training and testing

	python3 code.ipynb
	upload the train.cvs in colab if using google colab(recommended)
	continue exceuting training

## STEP 4: Run the last cell of gradio to get interface
In the interface there is a comment box and output for toxicity values as true/false