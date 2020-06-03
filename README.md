# Profanity-Checker
A code snippet written in python to get tweets from a csv file and get the % of profanity and store them in a formatted output file

## Files

There are three files included in this repo:

* `profanity.py` -> main script used to check profanity
* `tweets.csv` -> formatted input file
* `profanity_degree.txt` -> formatted output file

## Usage
- Copy/Create the `tweets.csv` file in the same directory as the `profanity.py` script
- Run `profanity.py` the results should be stored in `profanity_degree.txt`

## Assumptions
- I have assumed that the input file is formated as a csv file in the format `<index>, <tweetID>, <tweet>`
- I have assumed that the profanity ratio uses the formula `(number of slurs)/(total number of words in tweet) * 100`
- I have assumed that the output is in the format `<index> - <tweetID> - <profanity%> - <found slur words>`

## Screenshots

<img src="https://i.imgur.com/UG7CrUa.png" height="218">  <img src="https://i.imgur.com/l9xeGtM.png" height="267">
