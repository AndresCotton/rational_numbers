# rational_numbers_datasets
Datasets used for the paper "**Mental representations of rational numbers: a Massive Online Experiment**".

To ease the use of the provided datasets, we clarify some useful details:
Both datasets contain 22221 rows, each corresponding to a different participant.

The demographics dataset has 6 columns that contain the following information: (A) id of the participant, (B) age, (C) gender, (D) educational attainment, (E) number of correct answers (F) total time. In every case, cells with the value “-999” indicate that the participant didn’t answer the question.

  - (B) Age is indicated in years.
  - (C) The gender field has 3 possible values: “1” indicates “female”, “2” indicates “male”, “3” indicates “other”.
  - (D) The educational attainment field has 5 possible values: “1” indicates "none", “2” indicates “completed primary school”, “3”  indicates “completed secondary school”, “4” indicates “completed university degree”, “5” indicates “completed postgraduate degree”.
  - (E) The number of correct answers can go from 1 to 23.
  - (F) Total time is reported in miliseconds.

The answers dataset has 23 columns, each corresponding to one item of the questionnaire. “1” indicates a correct answer, “0” indicates an incorrect answer.
