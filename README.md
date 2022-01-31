# Jabama web scrapping 
Fateme Shariat September 2021

In this project I am web scrapping the Jabama website, using Selenium package in Python. For viewing codes, open "Jabama" file.

Description:
After running the webdriver, we choose our city and filters we want to add in the website, then we give the address to selenium and make a datframe of all the rooms. 
For doing so we have two ways, first way is to write a loop which worked perfectly at first but after some changes in the website itself, had some problems, you can find the loop at the end of the codes.
The second way is to run the 9th line, 5 times, after that you'll get an eror, but it has already added the information to the list of rooms, so we're good.
Next up we see a table containing these information about rooms: Room Name,	Price, Link,	Star,	Reviews,	Rule 1,	Rule 2,	Rule 3,	Rule 4 and	Rule 5. We can save this table as CSV file for easier access.
About the columns, Link is the web adress you can view all the info about rooms, Star is stars assigned to the room by reviewers, Reviews is the number of reviews it got, Rules are the rules assigned to the room by the owner.
Now if we want to save each room's pictures we take the next step, we write a loop that takes each room's link, and then we save pictures.
We can also take a screenshot of the calendar that shows when the room is empty and you can reserve it! 
