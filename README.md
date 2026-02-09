# Quiz Feature Test

This file demonstrates the new quiz syntax for markdown-ultra.

## Science Quiz

Here's a sample quiz about basic science:

~QUIZ
Q: What is the chemical symbol for Gold?
A) Go
B) Gd
C) Au
D) Ag
ANSWER: C
~

## Math Quiz

Try this mathematics question:

~QUIZ
Q: What is the square root of 144?
A) 10
B) 11
C) 12
D) 13
ANSWER: C
~

## History Quiz

Test your history knowledge:

~QUIZ
Q: In which year did World War II end?
A) 1943
B) 1944
C) 1945
D) 1946
ANSWER: C
~

## Multiple Quizzes

You can add as many quizzes as you need!

~QUIZ
Q: Which planet is known as the Red Planet?
A) Venus
B) Mars
C) Jupiter
D) Saturn
ANSWER: B
~

## Quiz Syntax Guide

To add a quiz to your markdown, use the following syntax:

```
~QUIZ
Q: Your question here?
A) Option A
B) Option B
C) Option C
D) Option D
ANSWER: C
~
```

**Rules:**
- Start with `~QUIZ` on its own line
- Begin your question with `Q:`
- List options with `A)`, `B)`, `C)`, `D)`, etc.
- Specify the correct answer with `ANSWER:` (use the letter)
- End with `~` on its own line
