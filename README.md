# Context-Aware-Sarcasm
> Project of Essentials in Text and Speech Processing

## Start

To install environment, run 
`conda env create -f environment.yml`

To activate the environment, run 
`conda activate sarcasm_nlp`

## Dataset
iSarcasm()[linktobeadded] (866 pairs)
GPT4o-mini-data (2314 pairs)

## Case analysis

### Model fine-tuned on FLAN-t5, 10 epochs with iSarcasm 

One inference in test set of iSarcasm is:

> src: @MarkHendyHR Only joking... keep it real. HR professionals have a life too... 🤔 
> translation: I don't think HR professionals have a life. 
> ground_truth: Only joking. Keep it real. HR professionals don't have a life. 

One inference in GPT4o-mini-data is:

> src: Look at you, finishing all your snacks before dinner. What a healthy choice! 
> translation: I would say that eating snacks before dinner is not healthy. 
> ground_truth: Eating snacks before dinner is not a good decision for your health.
