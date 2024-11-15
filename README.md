# Context-Aware-Sarcasm
> Project of Essentials in Text and Speech Processing

This is the code repository for our project. This project focuses on developing a system to address sarcasm by detecting and interpreting sarcastic comments in a clear and straightforward manner. Sarcasm detection identifies comments containing sarcasm, while sarcasm interpretation rewrites them to preserve the intended meaning in an unambiguous way.

## Start

To install environment, run 
`conda env create -f environment.yml`

To activate the environment, run 
`conda activate sarcasm_nlp`

## Dataset
[iSarcasm](https://www.kaggle.com/datasets/tegzes/isarcasm?select=isarcasm2022.csv):
A collection of tweets, labelled as either sarcastic or non\_sarcastic. There are 866 sarcastic pairs with notations.  
GPT-4o-data (augmented dataset using GPT-4o, 2314 pairs):
An augmented dataset generated using APIs from famous language model GPT-4o, with size mini. All generated pairs are sarcastic. 

## Case analysis
Interpretation for sarcastic statement: 

**Source**: love when the train stops in philly and everybody boards and of a sudden it smells like a ham sandwich.

**Model Output**: I hate when the train stops in Philadelphia and everybody boards and of a sudden it smells.

**Ground Truth**: i'm disappointed but not surprised that my train stopped in philly and everybody got on and suddenly it smelled like ham sandwich. 

Results for Non-sarcastic statement would be Non-Sarcastic. 

