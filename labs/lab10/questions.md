# Worksheet for Lab 10\!

### Question 1: What happens when you swap the delimiter from commas to tabs? How does the preview change?

	It changes from everything being in tables sepearted by the commas to a table with 2 columns.
(Make sure "disable live preview is not checked if you don't see a change)

### Question 2: Try sorting the scientificName facet by name and by count. What problems are there with the data?

	There are hidden spaces, spelling errors, and broken characters.

### Question 3: Use faceting to figure out the following:

#### How many different years are represented in this file?

	16

#### What year occurs the most times?

	1978

#### What year occurs the least number of times?
	
	1993

# Questions for Post-Lab Assignment 10\!

### Question 4: What happens when you make a numerical facet of column note1, then convert the column to numbers? Is something different about the facet compared to yr?

	You get nothing at first then the convert to number makes a bar graph. The yr column has a numeric year for every single row in the dataset.
	 The note1 column has a mix of numbers and a large number of empty/blank cells. 

### Question 5: Click and drag on the scatterplot facet you made to highlight a rectangle. What happens to the data points being displayed?

	It adds a lighter bar to the other bar graphs to show the data from the scatterplot.	

### Question 6: After the last step, some columns are empty. (You can check by text faceting a column) Why? What do you think we can do to fix it?

	
	Some columns are empty because of the leading spaces in the  data which caused the program to create extra, misplaced columns during the split.	
	 To fix this, undo the split, apply Trim leading and trailing whitespace to clean the text, and then re-split the column.
