# Algorithm Sentence Analizer

## Description
This project provides an algorithm that reads a sentence character by character until it reaches a period (`.`), and calculates:
- The total number of characters in the sentence
- The number of words (words are separated by a single space)
- The number of vowels (a, e, i, o, u in both cases)

## How it Works
The algorithm uses three counter variables:
- `length` to track total characters
- `words` to track the number of words
- `vowels` to count all vowels
The loop continues reading each character until it reaches a period.

## Counters Used
- **length**: Integer, counts characters including spaces and period
- **words**: Integer, increments when a space is found
- **vowels**: Integer, increments for each vowel found

This README explains the logic and steps clearly.