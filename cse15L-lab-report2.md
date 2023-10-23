Part1
I invoked the method named "handleRequest" where I've encapsulated all the functionalities for querying URLs. This method requires the website's URL as a parameter, with pertinent details including the path of the website, the key for querying, and the messages to be queried. 

To display new messages on the site, I need to modify the URL data, appending "/add-message?s=" to its tail. Within the code, I have already established an ArrayList designed to accumulate all the messages. Consequently, each time a message is appended through the query request "/add-message?s=", it gets preserved in the ArrayList.

First I use /add-message?s=Hello,Hello become first message in Webpage.

Second I use /add-message?s=How are you,How are you become second message in Webpage.

I also try add my name in webpage,it's become third message


Part2
