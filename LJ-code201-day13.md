## Learning Journal Day 13

Today we learned about how to save data into localStorage. This will enable to make the data persistent even if browser is refreshed or even closed.
localStorage.setItem() will save the key-value pair data. However, JSON.stringify() method needs to be used to save the data into string and when you retrieve the data, you have to use localStorage.getItem() and then subsequently parse the data using JSON.parse().