# Mind-Reader
Create a program that predicts one of two choices that the user will enter. Prompt the
user to enter one of two possible inputs: X and O, or a sentinel (ex. ‘Q’), to allow the
player to quit.
The program makes predictions based on the history of user’s previous inputs by storing
the last four inputs into a pattern string, and then using a HashMap to store the different
patterns that have come up (the keys), with a count of how many times that pattern has
appeared before (the value).
