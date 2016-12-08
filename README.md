# worksheets-5-8
Worksheet 5 - Do chapter 3 of online R tutorial http://tryr.codeschool.com/

1.	How could you make a matrix that is 5 columns wide and 2 rows deep and that has the value 1 in each cell? 

> matrix(1,2,5)


2.	How could you make a matrix that is 2 wide and 2 deep and that has the values 10, 14, 20 and 30 in it? 
matrix((10,14,20,30),2,2)

3. What does the dim assignment function do to a vector? 
Sets the dimensions in a matrix 


4. This chapter is about matrices. Can you think of data that would come in the form of a matrix? Remember that in a matrix, all cells have the same datatype. 

Theres some biological data that can be set in matrices, or business data with numbers and money values 

5. You learned three commands to plot a matrix. Which are they? Which one do you think would be most useful? 

Contour, image, and perspective

I think perspective and contour would be of more use 











Finished! 
Name: Janette Zaragoza


Date:  
10/27/2016 
Worksheet 6: Do chapter 4 of Try R codeschool 

You can do all the exercises in the online tutorial first, then come back to this worksheet to answer a few questions. 

1. You used about 5 functions in this tutorial.  Write down the functions and how they work. 

Mean gives average , abline is a line on the plot representing the mean, median is using the middle or middle two umbers if there is an even set , meanValue, deviation gives the range of typical values 


2. Several objects were used in this tutorial. Two of them are vectors - which ones? 
Which ones were simple "numeric"s? 

Pounds and limbs 




3.	How would you use the function abline to create a horizontal line that crosses the y-axis at 10? And a vertical line that crosses the x-axis at 10?

Abline(h = 10 , v = 10)

If you want to try this out (which would be great! use Rstudio), you need to first create a plot with some data, for example: 
x<-1:12
y<-1:12
plot(x,y)

Now you can play with the abline() function to add horizontal and vertical lines. 









Awesome! Another tutorial done! 
Name: 
Janette Zaragoza	

Date:  10/26/2016 
**Install R and RStudio prior to working on this worksheet**
Worksheet 7 Getting to know Rstudio through videos from Udacity. 

If you are doing this at home, you should first install R studio (worksheet 11). If you are in the computer room, you can start with this worksheet. 
Rstudio is installed on the computers, find it in the "dock" and start the program. 

Task 1. Watch video on Rstudio basics:

https://www.youtube.com/watch?&v=FDSmlIBy7ko

Task 2. Watch video on changing the settings of Rstudio (up to 45 seconds). 

https://www.youtube.com/watch?&v=vLlj5nNj8x4

Task 3. Change the settings for "appearance" and enjoy the new colors. 

Task 4. Watch video on getting help for R

https://www.youtube.com/watch?v=ABVX527RODE

Task 5. Go to the quick R website (google quick R or go to http://www.statmethods.net/). Search for information on bar plots. You'll need it for the next task. 

Task 6. Create a new R script in Rstudio

Write code to make two numeric vectors of equal length, and plot them in a scatter plot.
Then plot one of them in a barplot. Make the barplot horizontal. 
Create a matrix that combines both vectors using rbind(vector1,vector2) and create a barplot of that matrix. 

x<-c(1:10) 
y<-c(1:10) 
plot(x,y) 
barplot(x) 
matrix<-rbind(x,y) 
barplot(matrix)



Save your code in a place on your computer where you can find it back. Submit your .R code file along with your worksheets through iLearn.
How to save your code in an R script : https://vimeo.com/142568715
Doing great! 
Name: 
Janette Zaragoza	
Date:  
10/26/2016

 
Worksheet 8: Chapter 5 of Try R codeschool 

Chapter 5 is about factors. Nominal data should be stored as factors. 
The following are examples of data that should be stored as factors: 

1. Gender (male / female / unspecified)
2. Nationality (e.g., US, Canada, Mexico)
3. Type of animal (e.g., dog, fish, cat, horse)
4. Age if range is used (below 40, 40 or older)

The following are examples of data that should not be stored as factors: 
1. Age if years or months are used (numeric)
2. Height (numeric)
3. Price (numeric)

Task 1. Come up with at least 4 examples of data that should be stored as factors. 

1-	Type of cereal 
2-	States
3-	Capitols
4-	Type of plants 




Task 2. Explain all parts of the command 
plot(weights, prices, pch=as.integer(types))


•	weights represents the values to be plotted in the x-axis. It is a numeric vector, where each number is representative of each factor in the vector types.
•	Prices represents the values to be plotted in the y-axis. It is a numeric vector, where each number is representative of each factor in the vector types.
•	pch converts factors to integers so that they can be passed as additional arguments to set parameters for the plot. once the factors have been passed as integers, the pch argument can be used to assign an integer value to each factor level and that integer value can be assigned to a specific symbol.






On your way to becoming an R ninja!
Name:
 Janette zaragoza

Date:  12/7/2016
