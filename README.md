# Beyond Goldfish Memory: What is Relevant in Long-Term Dialogue?

This repository is the code which was developed as part of the thesis done in the CLTL Master's Linguistics - Language and AI program at VU Amsterdam. 

# Overview

The thesis notebook `src/Thesis.ipynb` is with all of the code and research. The notebook should be run with Python 3.9 kernel and `requirements.txt` will install the necessary packages.

There is also an exploratory notebook `src/ParlAI.ipynb` to test out the ParlAI framework and package.

- The original pre-processed JSON datasets can be downloaded from http://parl.ai/downloads/msc/msc_v0.1.tar.gz. 
- The processed CSV datasets are saved under `src/data/` and the trained models are saved under `src/model/`.
- The resulting predictions from the evaluation are saved under `src/results/` for validation dataset and `src/results_test/` for the test dataset.
- `src/llm_judge/` has the prompts and resulting predictions for LLM as a Judge evaluation with session summary, and
- `src/llm_eval` has the prompts and predictions for LLM as a Judge evaluation with utterances.

# Project structure

```
thesis-project
└───src
│   └───Thesis.ipynb
    └───data
        └───train
        └───valid
        └───test
    └───results
    └───results_test
    └───model
    └───llm_eval
    └───llm_judge
│   .gitignore
│   LICENSE
│   README.md
│   requirements.tx
```

## Thesis report
Thesis is available on request.
