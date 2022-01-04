# Two Stage Aspect-Based Sentiment Analysis: Multi-Target extraction and Polarity Classification

A two stage ABSA span based extraction and classification model, developed in PyTorch, based on the [work](https://github.com/huminghao16/SpanABSA) by Hu et Al., and tested on SemEval2014 (laptop14).  

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
0) Download the following pre-trained models and put them in the related folders in order to evaluate the results without training:
    -  [te_net](https://drive.google.com/file/d/1X08p9KKnlaXLXhR-CN7XR-iRQXa5nYm_/view?usp=sharing) in the folder Data/Previous_training/best_te and also in the folder Data/Jointed;
    -  [pc_net](https://drive.google.com/file/d/1Nlq2sQl0CKOM6NerrTqbIVYC0h-4qPHR/view?usp=sharing) in the folder Data/Previous_training/best_pc and also in the folder Data/Jointed;
    -  [bert-base-uncased](https://drive.google.com/file/d/12Te1-ABCwW65D7RxJYzhtIZ-T3CuM4uL/view?usp=sharing) in the folder Data/bert-base-uncased;
2) Run the block with all the imports
3) Be sure to have selected the colab flag to false if you are not using it, and the basepath to your own (path/to/NLU_Project)
4) All the modalities can be customized from their workspace functions
5) When you run the evaulation (target extraction or polarity classification) be sure to have added the basepath of the model in the variables of the main function
6) For a detailed description of all the parameters download the report above
