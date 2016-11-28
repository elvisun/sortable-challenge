# How I approached this problem

##Here are some observations I made at the beginning
1. I formatted the json file so I can read them without hurting my eyes. Saved into `products for human.json`, `listings.txt` was too big for me to prettify it
2. I realized there are some "-" or "_" in the product, we may need to convert them into seperate words
3. Announced date is a datetime object, we probably only need the date

I also think using a database could be an easy approach, but let's not assume you guys the database installed, so that leaves me with connecting to a database on the cloud. I'll leave this option to the last as I want to implement the search functionality with more flexibility.


