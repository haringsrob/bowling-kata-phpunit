# Bowling kata phpunit

This project is a starterkit to quickly start your practise.

## What is a kata?

As explained by uncle bob:

> A kata is meant to be memorized.
> Students of a kata study it as a form, not as a conclusion. 
> It is not the conclusion of the kata that matters, it's the 
> steps that lead to the conclusion. If you want to lean to 
> think the way I think, to design the way I design, then you 
> must learn to react to minutia the way I react. Following 
> this form will help you to do that. As you learn the form, 
> and repeat it, and repeat it, you will condition your mind 
> and body to respond the way I respond to the minute factors 
> that lead to design decisions.

Let me refer you to the page by [Robert C. Martin](http://butunclebob.com/ArticleS.UncleBob.TheBowlingGameKata).

## Why?

It can be used to train muscle memory, get fit for the new day,
or practice test driven development in a new language.

Because the task is not complex it should not take to long to
complete and can be done multiple times a week.

It is a developers way to stay in shape.


## The bowling kata, basic information to get started

If you are doing this for the first time, or maybe the 100th time.

Below is a short explanation of the bowling game (you might already)
know it, but I'll just highlight the required items.

1. A game exists out of 10 frames
2. In each frame the user can throw maximum of 2 times, up to 10 points
3. The score is the total number of points, added with bonus points
from spares and strikes.

*A spare:* is when a user throws all 10 points within 2 tries.

**Bonus:** The number of points in the next throw.

*A strike:* is when a user throws all 10 points in 1 try.

**Bonus:** The number of points in the next 2 throws.

In the last (10th) frame, if a spare or strike is thrown, the user
is allowed to roll an extra ball, with a maximum of 3.

## What do you have to do:

The goal is to:

Create a test: BowlingGameTest

Create a class: BowlingGame

Write the test until it fails >> Write the game until it passes >> Write test >> Write game ...

Never write more code than required to make the test fail or the game
to pass the test.

However, refactor the code when you feel it is needed to maintain
the quality and simplicity.

**It is up to you to:**

- Create the further file structure.
- Execute the test runner
- Format the code

This is part of the practice.

## Additional reading material

[PHPSpec version](https://github.com/laracasts/Code-Katas-in-PHP/tree/master/bowling-game)

[Javascript version](https://github.com/hontas/bowling-game-kata)

[Clean code guidelines in PHP](https://github.com/jupeter/clean-code-php)

