# llm-hallucination-fyp

This repository stores the appendix content for the paper "Reducing LLM Hallucinations: Exploring the Efficacy of Temperature Adjustment through Empirical Examination and Analysis" by Max Tan Zheyuan

### Experiment Results

The experiment results can be found in the excel file, “Wikibot Temperature Response.xlsx” 
There are 4 sections as denoted by the worksheets:
1.	Knowledge Recall: Prompts that query the model for information on real life characters (Main experiment).
2.	Made up Characters: Prompts that query the model for information about fabricated characters that do not exist. These characters do not even exist in fictional stories.
3.	Similar Question from Context: Prompts very similar to the information provided in the context of the model.
4.	Loaded Question: Prompts to test if the model is able to pick up the false assumption behind a loaded question.

### Data Analytics
The Python notebook used to analyse the experiment results can be found in the file “analysis.ipynb”. The input expected is in the same format as the Experiment Results above. 

### Prompts
Go to the `prompts` directory to find the prompt(s) used for the experiment. You may drag and drop the prompt into a cloned `llama.cpp/prompts` directory to use it to reproduce the results. 
