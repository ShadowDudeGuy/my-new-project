# My School Homework Helper
Final project for the Building AI course

## Summary
My project is an AI tool that helps middle schoolers with their homework. You just copy and paste long science or history chapters into it, or upload a photo of a textbook page. The AI then shrinks it down into simple bullet points and automatically makes a quick 5-question practice quiz so you can study fast.

## Background
Middle school is way harder than elementary school because we get way more homework and have to read massive textbook chapters every night. 
* It takes forever to read 10 pages of history, and it's hard to know what will actually be on the test.
* If you get stuck on a hard word at home, you can't ask your teacher for help until the next day.
* Just rereading notes over and over is super boring and doesn't work.

I wanted to make this because my friends and I always get stressed out studying for big quizzes, and I think an AI could make studying feel more like a quick game.

## How is it used?
You use this right after school when you are sitting at your desk doing homework. 
1. You take a picture of your textbook page with your phone or copy the text from your online school assignment.
2. The AI reads it and picks out the most important definitions and facts.
3. It gives you 3 easy bullet points to read and a few flashcards to test yourself.

<img src="https://wikimedia.org" width="300" alt="Me after reading science for an hour">

```python
# A simple python function to check if a student got a quiz question right
def check_my_answer(your_answer, correct_answer):
    if your_answer.lower() == correct_answer.lower():
        return "Good job! You got it right!"
    else:
        return "Not quite. The right answer was: "+your_answer+"."

# Let's test it out:
print(check_my_answer("Cells", "cells"))
```

## Data sources and AI methods
This project needs to read school texts so it understands how middle school classes work.
* **Data Sources:** I will use free open-source textbooks online and my own school study sheets.
* **AI Methods:** It uses Natural Language Processing (NLP) so the AI can read human languages, and text summarization to make long paragraphs much shorter.


| What the AI does | What it's called |
| ----------- | ----------- |
| Reads text from a photo | OCR (Optical Character Recognition) |
| Cuts a long page down to 3 lines | Text Summarization |
| Makes up the quiz questions | Language Generation |

## Challenges
The AI won't be perfect, so there are a few limitations:
* Sometimes the AI might make a mistake, so you still need to check your real notes.
* If you take a blurry photo of messy handwriting, the AI won't be able to read it.

## What next?
Next, I want to add a feature where you can actually talk to the AI. You could speak into your microphone and tell it something, and it would talk back to you.

## Acknowledgments
* The template is from the University of Helsinki's Building AI course.
* Image from: [Sleeping Cat on Her Back by Umberto Salvagnin](https://wikimedia.org) / [CC BY 2.0](https://creativecommons.org)
