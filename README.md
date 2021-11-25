# TwitterAPI-Integrations
Integrations that I have developed using the Twitter API via SnapLogic (Integration Platform):

Scenario 1 – posts a tweet to twitter which includes place, latitude and longitude. If successfully, tweet will be posted and will return a 200 with sender id and message id

Scenario 2 – Query the tweets based on any subject and retrieve the a specified number of tweets from that subject. Filter and sort based on retweets.

Scenario 3 – Get the tweets from a particular user/handle. Manipulate and sort the data and write to a file in JSON format.

Scenario 4 – Retrieves data from a given user via screenname. Generates a summary in the following format:  $name + " has " + $friendsCount + " friends and " + $followersCount + " followers". Prints to XML or JSON depending on the responseFormat given.
