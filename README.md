# deceptive-attention-master_fact_ai

Github for FACT_AI course 2020.

## To Reproduce Report

Install environment as specified https://github.com/danishpruthi/deceptive-attention
Logging module can be found here https://github.com/danishpruthi/log
Common errors:
When running bash files , unbuffer may not be found, you can run bash files without this
Similarly the command python3.6 may need to be replaced with just python.

## Classification Tasks

## Sequence to Sequence Tasks
To produce the tables of the sequence to sequence tasks from the log files open deceptive-attention-master_fact_ai/deceptive-attention-master/src/seq2seq_tasks/Check_Logs.ipynb . Here test runs of the code can also be performed.

## Extension Tasks
In deceptive-attention-master_fact_ai/deceptive-attention-master/src/classification_tasks/ run cells in YELP notebook.ipynb, and make sure locations of files in cell 1 are correct. The YELP results notebook.ipynb helps parse the output to give the results/plots as seen in the report.
Important params are passed to main function via a dictionary. 
The output dir will store all files and produce an error if the folder already exists.
