# Word Scrambler

## Description

Aanlrtppey eevn wehn wodrs are all smraelcbd , as lnog as the frsit and lsat ltteer saty the smae , yuor biarn can slitl raed it! At least, that's what some clickbait article said.

## Prerequisites

You should be comfortable with the following topics:

- Loops
- String manipulation
- Functions
- Lists / Arrays

## Prompt

"Apparently, even when words are all scrambled , as long as the first and last letter stay the same , your brain can still read it !"

Regardless of whether you believe it, this kind of exercise is perfect for lists. We’re going to be creating a program that takes in a phrase or sentence and scrambles every word, keeping only the first letter and the last letter the same. Since it’s random, the same phrase should come out different every time you run it. Here’s the phrase "I love learning computer science" scrambled five different times by the same program:

```
I lvoe lrnanieg cpueomtr sncceie
I lvoe liarnneg cpeoutmr scniece
I lvoe lnanrieg coptmuer sneicce
I lvoe lnanireg ceptmour senicce
I lvoe lannreig ctomeupr seincce
```

As you can see, each one is slightly different from the last.

This is an exercise in algorithmic thinking - coming up with a strategy to a single problem - how do you scramble a word keeping the first and last letters the same? Note that only words with length 4 or greater should be scrambled, as anything with 3 or less letters cannot be scrambled as long as the first and last letter stay the same.

## Testing

Simply look at the output and make sure that the letters are indeed scrambled, except for the first and last letter. If any words have a different first or last letter, or are missing letters, then you know that something is wrong.

## Extensions

### Implementing Shuffling

If you're using a language like Python or JavaScript that has nifty methods for shuffling/randomizing a list, that's neat! As a challenge, see if you can implement the shuffling/randoming on your own.

### Handle Punctuation

Punctuation should not be shuffled since it's not technically part of the word. But if your program is simply splitting up your string by spaces, then some punctuation may get caught in the shuffle! Modify your program so that punctuation is not shuffled with a word.
