# What Dose Questions Ask Exactly?  MFAE: Duplicate Question Identificationwith Multi-Fusion Asking Emphasis

Our code can run on four Datasets: 

Duplicate Question Identification DatasetsQuora Ques-tion Pairs, CQADupStack;

Natural language inference Datasets: SNLI and MultiNLI.

After download the dataset, you can run process_quora_bert.py, process_quora.py(elmo), 
process_mnli_bert.py et. in scripts/preprocessing to preprocess the data. 

For convenience, you can simply run run.sh to train the model based on BERT service (https://github.com/hanxiao/bert-as-service) on every dataset one by one.
You can also select the specific file(bert_quora.py, bert_cqadup.py,
bert_mnli.py, bert_snli.py) to train AMAE on BERT or (elmo_quora.py, elmo_mnli.py, elmo_snli.py) on Elmo.

