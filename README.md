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

## How to cite the usage of *STITA* dataset in pubblications?

Please, to cite this package, cite the paper:
```
del Gobbo, E., Guarino, A., Cafarelli, B. et al. GradeAid: a framework for automatic short answers grading in educational contexts—design, implementation and evaluation. _Knowl Inf Syst_ 65, 4295–4334 (2023). https://doi.org/10.1007/s10115-023-01892-9
```

Here you can find the citation in BibTeX format:
```
﻿@Article{delGobbo2023,
  author={del Gobbo, Emiliano
  and Guarino, Alfonso
  and Cafarelli, Barbara
  and Grilli, Luca},
  title={GradeAid: a framework for automatic short answers grading in educational contexts---design, implementation and evaluation},
  journal={Knowledge and Information Systems},
  year={2023},
  month={Oct},
  day={01},
  volume={65},
  number={10},
  pages={4295-4334},
  issn={0219-3116},
  doi={10.1007/s10115-023-01892-9},
  url={https://doi.org/10.1007/s10115-023-01892-9}
}
```

Here the citation in RIS format:
```
TY  - JOUR
AU  - del Gobbo, Emiliano
AU  - Guarino, Alfonso
AU  - Cafarelli, Barbara
AU  - Grilli, Luca
PY  - 2023
DA  - 2023/10/01
TI  - GradeAid: a framework for automatic short answers grading in educational contexts—design, implementation and evaluation
JO  - Knowledge and Information Systems
SP  - 4295
EP  - 4334
VL  - 65
IS  - 10
AB  - Automatic short answer grading (ASAG), a hot field of natural language understanding, is a research area within learning analytics. ASAG solutions are conceived to offload teachers and instructors, especially those in higher education, where classes with hundreds of students are the norm and the task of grading (short)answers to open-ended questionnaires becomes tougher. Their outcomes are precious both for the very grading and for providing students with “ad hoc” feedback. ASAG proposals have also enabled different intelligent tutoring systems. Over the years, a variety of ASAG solutions have been proposed, still there are a series of gaps in the literature that we fill in this paper. The present work proposes GradeAid, a framework for ASAG. It is based on the joint analysis of lexical and semantic features of the students’ answers through state-of-the-art regressors; differently from any other previous work, (i) it copes with non-English datasets, (ii) it has undergone a robust validation and benchmarking phase, and (iii) it has been tested on every dataset publicly available and on a new dataset (now available for researchers). GradeAid obtains performance comparable to the systems presented in the literature (root-mean-squared errors down to 0.25 based on the specific tuple $$\langle $$dataset-question$$\rangle $$). We argue it represents a strong baseline for further developments in the field.
SN  - 0219-3116
UR  - https://doi.org/10.1007/s10115-023-01892-9
DO  - 10.1007/s10115-023-01892-9
ID  - delGobbo2023
ER  - 
```
