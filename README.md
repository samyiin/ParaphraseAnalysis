# Paraphrase Detection 
In this project we will fine-tune pretrained language models to perform paraphrase detection on
the MRPC dataset from the GLUE benchmark (https://huggingface.co/datasets/nyu-mll/glue).

## Dataset
We will use the MRPC dataset. This dataset consist of a set of two sentences and labels that indicates if this two sentences are paraphrase.  
An example for paraphrase is:
Original: Any trip to Italy should include a visit to Tuscany to sample the region's exquisite wines.  
Paraphrase: Be sure to make time for a Tuscan wine-tasting experience when visiting Italy.    
This two sentences have the same meaning but phrased differently. Our goal is to train the model to identify paraphrases.  

## Models and Tasks
In this project, we did four things under four notebooks: 
1. Full fine-tuned microsoft/deberta-v3-base to train the model to identify paraphrases.
2. Low Rank Adaptation on microsoft/deberta-v3-base to train the model to identify paraphrases.
3. Low Rank Adaptation on microsoft/deberta-v3-large to train the model to identify paraphrases.
4. Low Rank Adaptation on google/gemma-2b to train the model to identify paraphrases   
*google/gemma-2b is a relatively new model by the time this project is done.

## Results
We reached around 90% accuracy with each single model, to view the exact accuracy, please refer to our notebooks.  
In additon, I also record the results in the file Results.pdf
