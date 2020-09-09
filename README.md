# Benzinga-Ratings-Scrape
Takes the html code from a popular ratings site for stocks, then outputs a text file that lists you the best stock buys for that day, based on your own weighting or using a base weighting already in place.


How to:

Go to https://www.benzinga.com/calendar/ratings, and with inspect element on chrome, right click where it says <html xmlns>, then copy->copy element. Create a new 
file in any text editor and call it "BenzingaData.html", paste the copied html code into "BenzingaData.html". Save "BenzingaData.html" in the same folder as the 
python file you download, "BenzingaScrape.py". Now just run "BeningaScrape.py", the resulting txt file will be in the same folder as mentioned before. 
 
 
 If you want to manipulate the different weightings of the ratings then go into the python file and change the "weighter" function, you can change each weight by 
 going to the rating you want to change, then changing that line of code to say : weights['<whatever rating>'] = <integer weight of your choice>.
  
  
