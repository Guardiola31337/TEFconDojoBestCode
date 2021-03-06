# Kata - Coding Dojo

## Objectives
> The focus is to practice writing the best code we can possibly write and challenge ourselves. It is important to mention that the goal is not to finish the exercise as soon as posible, but to learn during the process via the discussion with our partner.

## Requirements
> Each developer must come with their favourite IDE ready to start practicing TDD, ideally with an empty class or function and its associated test prepared to be launched.

## Rules
* Developers should work in pairs.
* As a rule, Test-Driven Development is mandatory. If you are unaware of this procedure, please try to pair with someone who does.
* We will run a small retrospective at the end of the session where we will discuss what difficulties we found, what we have done and what we have learnt.
* Developers would thank their pairs when the session is over.

## What you should NOT expect from this dojo session
* It's neither a master class nor a workshop, but you will learn new approaches to face problems from different perspectives.  
* It's not a place to learn new languages. At least, one of the pair should be comfortable with the chosen programming language.
* It's not a place to learn how to set up an environment.

## How to start
1. **Find a pair**.
2. **Decide** which **programming language** you are going to use and in which laptop you will code.
3. **Read carefully the problem** described below and if you have any doubt, please refer to the facilitator.


***

## The Problem: Bowling Game

## Before you start:
* Do one task at a time. The trick is to learn to work incrementally.

### Bowling Game

*Thanks to Robert C. Martin, who designed this Kata.*

Create a program, which, given a valid sequence of rolls for one line of American Ten-Pin Bowling, produces the total score for the game. This is a summary of the rules of the game:

* Each game, or “line” of bowling, includes **ten turns**, or “frames” for the bowler.
* In **each frame**, the bowler gets up to **two tries** to knock down all the pins.
* If in two tries, he fails to knock them all down, **the score for that frame is the total number of pins knocked down** in his two tries.
* If in two tries he knocks them all down, this is called a **“spare”** and his score for the frame **is ten plus the number of pins knocked down on his next throw** (in his next turn).
* If on his first try in the frame he knocks down all the pins, this is called a **“strike”**. His turn is over, and his score for the frame **is ten plus the simple total of the pins knocked down in his next two rolls**.
* **If he gets a spare or strike in the last (tenth) frame, the bowler gets to throw one or two more bonus balls, respectively**. - These bonus throws are taken as part of the same turn. If the bonus throws knock down all the pins, the process does not repeat: the bonus throws are only used to calculate the score of the final frame.
* The game score is the total of all frame scores.

Here are some things that the **program will not do**:

* We will not check for valid rolls.
* We will not check for correct number of rolls and frames.
* We will not provide scores for intermediate frames.

The input is a scorecard from a finished bowling game, where “X” stands for a strike, “-” for no pins bowled, and “/” means a spare. Otherwise figures 1-9 indicate how many pins were knocked down in that throw.

#### Sample games:

```
12345123451234512345
```

always hitting pins without getting spares or strikes, a total score of 60

```
XXXXXXXXXXXX
```
a perfect game, 12 strikes, giving a score of 300

```
9-9-9-9-9-9-9-9-9-9-
```
heartbreak - 9 pins down each round, giving a score of 90

```
5/5/5/5/5/5/5/5/5/5/5
```
a spare every round, giving a score of 150

**Keep calm and refactor on green!**

Have fun!
