# yelp_reviews

This is in response to the question posed about how I would determine the popularity of mexican vs. italian restaurants.

I used the yelp API to pull data and transformed the response into a pandas dataframe.

I do want to say that this isn't perfect for a few different reasons. One is yelp has a limit on API calls which I would have exceeded in a single request so in the interest of time I only selected the top five restaurants in a few select states. This project could also use a little more finesse because it seems to only have pulled Italian restaurants. My best guess is that's due to the top five in each state are Italian, as my code requested (which could be an answer to the question in itself). Ideally I would test that by making a second request for only Mexican restaurants and merging those two dataframes together to run my analysis. But again, in the interest of time I wanted to pass this along as soon as possible and I think it still shows how I would approach the problem, and in its current state I think it still displays some of my skill level with Python. 
