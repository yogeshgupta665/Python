# Python

Demonstrating NumPy, Pandas, Matplotlib, and Scipy libraries in a single code

1. We import the required libraries: NumPy, Pandas, Matplotlib, and Scipy.
2. We generate a sample dataset of exam scores using NumPy's randint function.
3. We create a Pandas DataFrame from the NumPy array, assigning column names as 'Exam 1', 'Exam 2', and 'Exam 3'.
4. We calculate summary statistics (mean, median, and standard deviation) for each exam using NumPy's mean, median, and std functions.
5. We create another DataFrame (df_summary) to store the summary statistics.
6. We visualize the data using Matplotlib's boxplot function. This creates a box plot showing the distribution of scores for each exam.
7. We perform a statistical test using Scipy's ttest_ind function to compare scores between Exam 1 and Exam 2.
8. Finally, we print the summary statistics, display the box plot, and print the results of the t-test.
