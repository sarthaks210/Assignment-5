 <h1 align="center">INTRODUCTION</h1>
The top 1000 records were extracted from the 4000 records in the youtube_dataset, and the distribution of these channels were extracted and placed in a table.<br><br>
1.	Firstly, the two libraries which work with numerical data NumPy and Pandas were imported into the Jupyter Notebook as np and pd. After that, the packages for visualization such as matplotlib and seaborn were imported.<br>
2.	Secondly, pd.read_csv code was used to read the data in the form of a data frame. An encoding “cp1252” was used to allow characters such as “€” which are part of our dataset.<br>
3.	Then, the distribution of top 1000 channel types was plotted. Under this function, “dataframe.iloc” was used to slice the top 1000 rows and seaborn distribution plot (sns.displot) was used to plot the values.<br>
4.	“.to_csv” was used to export the data frame to a csv file named “Top_1000.csv” with the encoding “cp1252” to allow for special characters (€).<br>
5.	The seaborn plot style was set as ‘white grid’ along with aspect ratio for the plot which was chosen to be 3.<br>
6.	The function was called by inputting the first row and last row values by using “plot_channel_dist” which returned the figure for distribution of top 1000 channel types.<br>
7.	After extraction from python, the “Top_1000.csv” file was imported as a table into a mysql schema named ‘data 1202’. 6. The table was retrieved using the SELECT statement. <br>


<h1 align="center">CONCLUSION</h1>
The distribution of the top 1000 channel types were found using a variety of functions in Python. It was then exported to a csv file which was then imported as a database file in SQL.<br>

