# AIQuizz

## Summary

AIQuizz is a serious game, in the format of a quizz, that introduces you to AI. In the first part, the user is taught some theory about AI split into 4 categories: 
  1. What's AI?
  2. In which context do we talk about AI?
  3. What are the applications of AI?
  4. What are the dangers of AI?

In a second part, the user is asked to do the quizz. There are a series of 15 questions to answer.

## Access the quizz

To run the project:
1. Follow the instructions given [here](https://github.com/Simadiver/serious-lab)
2. When on the platform, go to **"Games"** section
3. As a theme, select **"AI"**
4. Choose to play **"Level 1"**

## Gamification

The game has a gamification system based two main parameters: **a score** and **a timer**. 

The **timer** starts at the beginning of the quizz and ends as soon as the user reaches the end of it.

The **score** increases as soon as a good answer is made. Chaining the right answers sets up a *score multiplicator* that make the user earn more points as he advances in the quizz.

### Trophies

The game also includes a **rewarding system** which consists in **unlocking trophies** for performing specific actions or series of actions (i.e. *Make a series of 5 right answers*)
As soon as a trophy is unlocked, the user can witness a wizard showing the unlocked trophy's title. To know about how to unlock a trophy, the user can find a information list from **Serious-Lab website** (link forthcoming).

#### Communication with the backend

To make the game's rewarding system work, you need to ensure to properly set up the **server**, the **database** AND **being logged-in to the platform**. If you're not logged-in, the game won't deal with any rewards. A whole project is in charge of providing backend features for the game, that you can find [here](https://github.com/Simadiver/serious-lab).
