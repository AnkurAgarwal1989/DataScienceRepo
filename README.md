1. The 'run_analysis.R' script is meant to run when kept in the same directory as the 'getdata_projectfiles_UCI HAR Dataset' folder.
2. The script clears out the workspace on starting.
3. The data from 'subject*.txt', 'X*.txt' and 'y*.txt' is read individually and then row bound.
4. No external processing is required.

Tidy Data:
The dataset attached is tidy because:
1. Each variable is in one column:
	The means of each type of measurements are in their respective columns. Since these are different types of measurements of different types of physical entities.
2. Each different observation of that variable should be in a different row:
	Each row in the tidy data corresponds to the mean of a different activity when performed by a particular subject.