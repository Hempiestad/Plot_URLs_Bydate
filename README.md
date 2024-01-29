# Plot_URLs_Bydate
a script that will take an excel sheet with a URL column and a Date Column and create a graph.
The script achives this bydoing the following:
1.Read the Excel sheet into a pandas DataFrame.
2.Convert the "Last Visited-Time" column to datetime format.
3.Extract the date part from the datetime column.
4.Group the data by date and count the number of URLs visited per day.
5.Plot the data using matplotlib.

make sure you have pandas and matplotlib installed, I had to also install openpyxl.
pip install pandas
pip install matplotlib
pip install openpyxl

Due to syntax errors I was getting the excel file and save locations are useing raw strings inidcted by the "r" prior to the file path.

the comments in the script should answer any additional questions.
