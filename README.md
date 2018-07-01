# Feed Reader Testing
## Overview:
This project has been prepared as an assignment of Udacity Front-End Web Developer Nanodegree Program. 
It includes application that retrieves RSS feeds, but the task has been performed on feedreader.js file to manipulate testing of the application. 
The testing has been carried out on jasmine testing framework (jasmine-2.1.2).

## How to run application
By double clicking index.html files it renders in the browser. 

## Testing and feedreader.js 
Four test suites have been created:

1. RSS Feeds:

* Write a test that loops through each feed in the allFeeds object and ensures it has a URL defined and that the URL is not empty.
* Write a test that loops through each feed in the allFeeds object and ensures it has a name defined and that the name is not empty.

2. The menu:

* Write a test that ensures the menu element is hidden by default. You'll have to analyze the HTML and the CSS to determine how we're performing the hiding/showing of the menu element.
* Write a test that ensures the menu changes visibility when the menu icon is clicked. This test should have two expectations: does the menu display when clicked and does it hide when clicked again.

3. Initial Entries:

* Write a test that ensures when the loadFeed function is called and completes its work, there is at least a single .entry element within the .feed container. Remember, loadFeed() is asynchronous so this test will require the use of Jasmine's beforeEach and asynchronous done() function.

4. New Feed Selection 

* Write a test that ensures when a new feed is loaded by the loadFeed function that the content actually changes. Remember, loadFeed() is asynchronous.

