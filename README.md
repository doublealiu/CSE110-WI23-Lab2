# CSE110-WI23-Lab2
Starter code for CSE 110 Winter 2023's Lab 2.

## Part 2
### Question 1.
I think one of the big benefits of continuous integration to a software team is that it provides a single source of truth for whether or not tests pass. Whether or not a test passes on GitHub actions can help resolve disputes where tests will run on one member’s environment while failing on another’s environment.

### Question 2.
Unit tests try to test single pieces of functionality. The distinction of what constitutes a single “piece” is relatively arbitrary, but unit tests are supposed to be the most fine grained type of test. Integration tests test bigger chunks of functionality than unit tests. I think the best way to put it is that rather than testing just pieces of code, integration tests will test “features,” or functionality that runs in a production environment.

## Part 3
### Question 3
Espresso tests are in the android test directory. This is because Espresso tests don’t mock anything, they just run off a real android environment. In our gradle build script the android test directory is the only place we give access to the android environment specific dependencies for testing.

### Question 4
Integration and unit tests may test a large portion of our app’s functionality, but UI tests will test the app as it is for a user, which means that their test coverage is wider than the previous two combined. They test the “whole” system, so to speak.
