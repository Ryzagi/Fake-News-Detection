# Test_task_kontur
Test task for the detection of fake news in the Contour company, 12th place out of 170
# Test task

To complete the test task, it is required to develop a model that will be able to distinguish between the headlines of real and fictional news.
To train the model, use the data from the `train.tsv` file. The file contains a table consisting of two columns.
The title column contains the headline of the news. The is_fake column contains labels: 0 – real news; 1 – fictional news.
To demonstrate the operation of the model, use the data of the test set from the `test.tsv` file. It also has a title column, the data of which is input for your model.
You need to copy the file `test.tsv`, rename it to `predictions.tsv` and fill the is_fake column with the values of your model's predictions, similar to `train.tsv'.
Initially, the column is filled with the value 0.

# Evaluation criteria
1. The F1 score metric will be used to evaluate the final decision.
2. The purity of the code, design and clarity of the study.

# Solution Requirements
As a solution, we expect a zip archive with all *.py and *.ipynb files in the solution folder and the `predictions.tsv` file in the root. Format of the zip archive name: LastName_FirstName.zip (example Ivanov_Ivan.zip ).
The `predictions.tsv` file must include a title column containing the same data as the original `test.tsv` file, as well as an is_fake column containing the values 0 or 1.
Marking up a test dataset and including it in training/validation is prohibited.

The solution folder should contain the study and all the code needed to reproduce the study.

