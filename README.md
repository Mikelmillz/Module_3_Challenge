# pandas-challenge
Due Monday 10/30  by 11:59pm
https://www.statology.org/pandas-count-unique-values/ for counting unique values. Not much to say about the beginning. This time the code is kinda spoon-fed to us.
https://pandas.pydata.org/docs/reference/api/pandas.DataFrame.set_index.html for set_index and lesson 4.1, 04-Stu_DataFrameShop_Pandas. The counting is done in this exercise 06-Stu_TrainingGrounds_DataFunctions in 4.1 as well.
4.2 lesson 07-Par_Census_GroupBy and https://stackoverflow.com/questions/39922986/how-do-i-pandas-group-by-to-get-sum helped me get the correct grouping and sum and means. At first I wanted to do a loc function on just the old school data to find the budget but I realized when going on to the next problem that they needed to be similar because we were going to make a table of these variables that we are creating. After thinking about it for a while I realized that I could just add up the whole budget and then divide by the number of students to get back to that oringial budget like how the ttotal students count looks. (I also had to change the school types since it was not aphabetical which I found help doing so here: https://stackoverflow.com/questions/66271694/sort-pandas-dataframe-by-index-then-by-alphabetical-order)
I found lesson 4.3 03-Ins_Binning helpful for the cut funtion and bins.

Trying to add the bins I ran into a number of errors. After troubleshooting to get different errors I realized that we formated that column with the $ which was making that a string and I needed to make it read as an interger/float again to make the bins work. Once I finally realized that I found https://stackoverflow.com/questions/38516481/trying-to-remove-commas-and-dollars-signs-with-pandas-in-python to be helpful.
I did change the second labels to labels2 so that I can have them be distinct (for my mind.)



