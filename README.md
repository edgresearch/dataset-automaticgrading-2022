# Annotated Datasets for Automatic Grading of open ended questionnaries responses
The repository contains a set of 5 Dataset to be used for benchmarking Automatic Grading of open ended questionnaries algorithms.

In particular the repository contains 4 datasets elaborated from existing datasets for this task, and a new dataset:

- _asap.xlsx_ - *ASAP* -> Based on the original from  https://www.kaggle.com/competitions/asap-aes/data
- _cunlp.xlsx_ - CU-NLP -> Based on the original from  https://bmb.cu.edu.tr/uorhan/CuNLP.htm
- _sag.xlsx_ - SAG -> Based on the original from  https://github.com/dbbrandt/short_answer_granding_capstone_project
- _scientsbank.xlsx_ - SciEntsBank -> Based on the original from https://github.com/dbbrandt/short_answer_granding_capstone_project
- _stita.xlsx_ - *STITA* -> New dataset containing a set of question-answers about statistics in higher education. The original dataset was in italian, it is released translated in english with EasyMNT (open state-of-art translator). The dataset is licensed under Creative Commons Attribution-ShareAlike 4.0 International License.


The datasets files are in XLSX format (Excel 2007).

The datasets are made of eight columns:

1. *id* contain the id of the answer.
2. *dataset* indicates the name of the dataset (helpful if concatenating all datasets).
3. *question_id* indicates the question id. Usefull when the question is void to group answers to the same question.
4. *question* indicates the text of the question.
5. *real_answer* indicates the correct answer to the question.
6. *answer* indicates the answer provided from the student .
7. *score* indicates the score received from the question (scaled between 0 = worst to 5 = Excellent).
8. *correct* indicates is the answer is correct = 1, of wrong = 0.

--------