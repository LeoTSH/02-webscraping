# Instructions

This directory contains HTML source file ```Free Programming Ebooks - O'Reilly Media.html``` and assets from O'Reilly's Free Programming Ebooks page at http://www.oreilly.com/programming/free/ as at 10 Jan 2018 08:54pm.

Your task is as follows:

1. Write a Jupyter Notebook or a R Markdown/Notebook document to scrape the HTML source file and useful data of all the free books that O'Reilly has made available. For Python, you can use the BeautifulSoup library. For R, you can use a combination of RCurl and XML or something like rvest. You are also free to use whatever libraries you are comfortable with. Save the data as a single CSV file named ```oreilly-free-books.csv```.
2. Add a narrative or story to your document and describe the data in the CSV file. This can include things like a count of all Python books or a list of books about containers or microservices.
3. Bonus: Add some visuals to make your document engaging and informative.

# Submission

To submit your assignment, commit your script(s), Jupyter Notebook or R Markdown document and the CSV file back into the repository.

# Logic Flow
1. Determine the HTML elements containing information about the books
2. Use BeautifulSoup to scrap and extract the elements
3. Iterate through the elements using the HTML tags and extract relevant information
4. Convert and save information to a csv file

# Notes
* As the website did not contain HTML tags which can be used to determine the category of the books, I had a difficulty classifying them and decided to hardcode the titles to act as filters
* Overall, there were 4 Java, 4 Open Source, 7 Python, 8 Software Architecture and 13 Other category books