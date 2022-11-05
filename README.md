# COMP8240project. 

## Original Paper
* HateXplain: A Benchmark Dataset for Explainable Hate Speech Detection (2020). Binny Mathew1, Punyajoy Saha1, Seid Muhie Yimam, Chris Biemann, Pawan
Goyal, Animesh Mukherjee. https://arxiv.org/pdf/2012.10289v2.pdf

## Original HateXPlain Github Repository
* https://github.com/hate-alert/HateXplain

## Objective of the Project
- Replicate and reproduce results as the published paper on the BiRNN-HateXplain [Attn] model designed for Hate Speech Detection.
- Construct 2 new datasets and test them against the model.
    
## Contribution on New Dataset Construction 
- Dataset 1 Existing Hatespeech Research Dataset : Lei Yang
- Dataset 2 Twitter Dataset: Wei En Tiong
- The new datasets were constructed, preprocessed and evaluated by the creators seperately. 

## Result
- The original work was successfully replicated and similar results have been reproduced.
- Both the new datasets have very similar results in terms of bias and explainability with the original published results.


## Folder Description 📂

* ./Annotation                    --> Contains the annotation files.
* ./Evaluation - New Dataset      --> Contains the evaluation results performed on new datasets.
* ./Measure of Agreement  	      --> Contains the codes used to measure Interannotators Agreeement.
* ./New Dataset                   --> Contains the raw and final transformed on the mew constructed datasets.
* ./Preprocessing                 --> Contains the codes used to preprocess the new datasets.
* ./Replication                   --> Contains the codes used to replicate on the original paper result.
