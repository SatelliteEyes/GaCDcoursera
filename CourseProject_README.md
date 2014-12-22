1. Reads in features and assigns the second column to a character vector names colNames
2. Reads in and merges, using rbind, the X_train and X_test files into a single X data.frame
3. Assigns the colNames vector as column names of X
4. Assigns to a variable Xkeep the subset of X corresponding to columns containing "mean"or "std" in the column name

5. Reads in and merges, using rbind, the y_train and y_test files into a single y data.frame
6. assigns the name "activity" to y

7. Reads in and merges, using rbind, the subject_train and y_test files into a single subject data.frame
8. assigns the name "subject" to subject

9. reads in the activity_labels text file
10. loops over the numerical activiy codes in the y data.fame and replaces them with the corresponding descriptive names in activity_lables

11. binds, subject, y and Xkeep into a single dataset, Total
12. writes Total to a txt file
