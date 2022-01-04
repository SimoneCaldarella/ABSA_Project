# Two Stage Aspect-Based Sentiment Analysis: Multi-Target extraction and Polarity Classification

A two stage ABSA span based extraction and classification model, developed in PyTorch, based on the [paper](https://github.com/huminghao16/SpanABSA) by Hu et Al., and tested on SemEval2014 (laptop14).  

The report of the project can be downloaded [here](./NLU_Report.pdf).

---

### Author info: 
- Student name: Simone Caldarella
- Student Number: 224434
- Email: simone.caldarella@studenti.unitn.it

### Other info:
- Dataset: https://github.com/lixin4ever/E2E-TBSA
- Paper: https://aclanthology.org/P19-1051.pdf
    
### To install the required libraries run the following command:
`pip install -r requirements.txt`
    
### Usage:

1) Run the block with all the imports
2) Be sure to have selected the colab flag to false if you are not using on it, and the basepath to your own (path/to/NLU_Project)
3) All the modalities can be customized from their workspace functions
4) When you run the evaulation (target extraction or polarity classification) be sure to have added the basepath of the model in the variables of the main function
5) For a detailed description of all the parameters download the report above
