# Write an API test that uses one data from one request in another

In this challenge, you need to create a test that can only be done by making multiple API calls.

## Quality Engineer

Working with APIs and data is extremely important for Quality Engineers for many reasons, including Test Data Management. This requires some automation engineering skills, usually programming, in order to chain flows together to automate a process.

## Specs

* System Under Test (SUT): [Deck of Cards API](https://deckofcardsapi.com)
* Use the existing `cards.spec.ts` file in this folder to complete this challenge

## Goals

* Create an automated API test that asserts the user can create a new, shuffled deck and draw two cards from it
* The deck should be shuffled and start with 52 cards
* Once two cards are drawn, the deck should have 50 cards remaining

> Feel free to use an API client like Postman or Insomnia to try this out if you're not comfortable with code
