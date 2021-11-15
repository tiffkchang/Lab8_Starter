# Lab 8 - Starter

Name: Tiffany Chang

1) In your own words: Where would you fit your automated tests in your Recipe project development pipeline?

Within a Github action that runs whenever code is pushed

This is because we want to protect the main branch from having any broken code pushed to it. Automated tests that run whenever code is pushed to a pull request will help accomplish this because if they fail, it won't allow you to merge your branch until you fix the issues and all of the tests pass. 

2) Would you use an end to end test to check if a function is returning the correct output? (yes/no)

No. End to end testing is used for testing UI and emulating user actions, not for checking individual functions.

3) Would you use a unit test to test the “message” feature of a messaging application? Why or why not? For this question, assume the “message” feature allows a user to write and send a message to another user.

No, since unit testing is for testing specific parts of your code. An end to end test would be more useful in this situation since it's more UI related.

4) Would you use a unit test to test the “max message length” feature of a messaging application? Why or why not? For this question, assume the “max message length” feature prevents the user from typing more than 80 characters.

Yes, you would use a unit test to test max message length since it's a specific function being tested.