- JUST RUN THE CODE BLOCK-BY-BLOCK - IN CASE SOME BLOCK CANNOT RUN, JUST TRY TO RUN THE PREVIOUS BLOCKS

- IN Q1, For running code with different basis function (x^2 and x^3), please de-comment / comment the code block ##BASIS FUNCTION (which has 6 line of code) as below:

If use X (simple model): use line 1 and 4, comment on line 2 3 5 6
If use X^2: use line 2 and 5, comment on line 1 3 4 6
If use X^3: use line 3 and 6, comment on line 1 2 4 5

	##BASIS FUNCTION (line 1 to 6)
1	X = X[['x']]
2	# X = X[['x', 'x^2']]
3	# X = X[['x', 'x^2', 'x^3']]
4	X_test = X_test[['x']]
5	# X_test = X_test[['x', 'x^2']]
6	# X_test = X_test[['x', 'x^2', 'x^3']]