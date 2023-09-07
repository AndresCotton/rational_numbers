# rational_numbers_datasets
Datasets used for the paper "**Mental representations of rational numbers: a Massive Online Experiment**".

To ease the use of the provided datasets, we clarify some useful details:
Both datasets contain 22221 rows, each corresponding to a different participant. 

## answers.csv
This is a 22221x23 binary matrix containing the answers given by each user to each of the 23 questions; “1” indicates a correct answer and “0” indicates an incorrect answer. The questions are stated in the article.

## demographic.csv
This file is a 22221x10 matrix. It has 7 columns containing the following information: (A) id of the participant, (B) age, (C) gender, (D) educational attainment, (E) number of mathematical problems completed, (F) number of correct answers (G) total time. In every case, **the value “-999” indicates that the information of that cell is missing**.

- (A) Each participant is identified with a unique id number.
- (B) Age is indicated in years.
- (C) The gender field has 3 possible values: “1” indicates “female”, “2” indicates “male”, “3” indicates “other”.
- (D) The educational attainment field has 5 possible values: “1” indicates "none", “2” indicates “completed primary school”, “3”  indicates “completed secondary school”, “4” indicates “completed university degree”, “5” indicates “completed postgraduate degree”.
- (E) The number of mathematical problems completed can go from 1 to 23.
- (F) The number of correct answers can go from 1 to 23.
- (G) Total time is reported in miliseconds.

This datasets were obtained by Andrés Rieznik, Verónica C. Ramenzoni, Florencia Rocca, Carolina Londoño & Valeria Edelsztein by a Massive Online Experiment with previous informed consent.
