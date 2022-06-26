# MSc.-Thesis---Danish-Text-Summarisation-Model

M.Sc. Thesis - Codebook README File (Tom Yagel)

The main (parent) folder contains the following files:
articles_summaries.csv - The raw data used in the codebook.
language.py - A language model required to run the PageRank baseline (import commands are included in the notebook).


The main parent folder contains the following folders:
The data folder - Contains all saved and preprocessed training and test data subsets, including the corresponding .json files.
The models folder - Contains all saved and preprocessed model .pth files.
The results folder - Contains screenshots of codebook-produced results, taken after every experiment has finished its course.
***Note that the results folder is only attached for reference and it is not required to run any of the code pieces. Most of its content is already shown in the written thesis file.
The utils folder - Contains the data_loader and SBERT (Sentence-BERT) python files required to run the codebbok (import commands are included in the notebook).

The results folder contains sub-folders in the format XXYY:
XX represents the experimented values for the minimum sentence length hyperparameter (14, 18 or 22).
YY represents the experimented values for the ROUGE threshold score hyperparameter (0.50, 0.55 or 0.60).
Each of the above folders contains screenshots of boxplots and a ROUGE score table generated at the end of the experiment corresponding with the folder name.
All F1 boxplots are already included in the Thesis Appendices section, while the R1, R2 AND R-L recall and precision scores are not.
A TTS (Training-test-sizes) image is also included in each folder, as sizes differ for each experiment.

To run the codebook in accordance with the written thesis report, kindly run the following Jupyter notebook files in the following order:
Part 1 - Data Preprocessing and Analysis.ipynb
Part 2 - Model Core Design and Training.ipynb
Part 3 - Extractive Summary Generation and Evaluation.ipynb
Two Baselines - Definition and Evaluation.ipynb

Further details and comments are included in the Jupyter notebook files.
