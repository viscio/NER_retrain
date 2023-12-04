# Retraining a simple DistilBERT on the MultiNERD dataset for NER applications
The two notebooks show the process to fine tune a DistilBERT model on the MultiNERD datasset. The first notebook generates and evaluates Model A, which is a simple fine tune based on the whole English part of the MultiNERD dataset, with all the classes included. 
The second notebook generates and evaluates Model B, which is a fine tune on the English part of the MultiNERD dataset, but with a smaller number of classes. 

These are simple notebooks, and the required libraries are indicated in the first cell of each book. These notebooks have been run on Google Colab using V100 as GPU accelerator. 

To run the code, simply install the libraries mentioned in the first cell in the notebook, download the notebook and run it, or even better, run it in Google Colab. 
