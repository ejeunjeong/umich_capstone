## The objective of our project
- Investigate the effectiveness of using a pre-trained model in a different language to perform a task in English: Especially, we will examine whether a Korean Language pre-trained model can be fine-tuned to summarize English reviews effectively.
- Investigate the use of generative models that do noe require fine-tuning: We will explore the use of generative models that do not require fine-tuning to summarize reviews. We will compare the performance of these models with the fine-tuned Korean Language model and assess their effectiveness.

## Data Description
- Amazon review data separated into train and test
- fewshot_examples.csv is a set of examples created specifically for few-shot learning.

Below is the origin source of the dataset. 
https://snap.stanford.edu/data/web-Amazon.html

## Code Description 
Most of our code is written in Jupyter Notebook, and you can run the code by executing each cell.
- modeling: Using KoBART and ChatGPT for review summarizaiton 
- evaluation: Evaluation results using BELU and ROUGE 

We did not utilize any code from an open source project, therefore we are not required to include licenses for in-line code attributions.
