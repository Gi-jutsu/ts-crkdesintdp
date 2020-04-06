<p align="center">
  <img alt="" src="./crkdesintdp.logo.png"">
</p>

## <a name='TOC'>🐼 Summary</a>

* [Rules](#rules)
* [Overview](#overview)
* [Story](#story)
* [Postlude](#postlude)
* [Bonus](#bonus)
* [Credits](#credits)

## <a name='overview'>🦊 Rules</a>

Hi, here are some rules to carry out this story oav;

* You **MUST** create a git repository named `ts-crkdesintdp`
* You **MUST** create a file called `.author.json` with your fullname

```sh
~/ts-baratie ❯❯❯ cat -e .author.json
{
  "fullname" : "Donald Knuth"
}$
```

> Of course, you can talk about the subject with other developers, peer-learning is
> the key to be a better developer. Don't hesitate to ask questions or help people on slack.

> Don't forget, there is no useless question :-)

* You **MUST** return the project on Tuesday March, 31 at 23:42 pm by sending an MP on slack with the link of your github repo.

Your repository **MUST** contain the totality of your source files, but no useless files (node_modules, temp files, log files,...).

## <a name='overview'>🐱 Overview</a>

The purpose of this project is to make you realize a simulation of a restaurant, which is composed of the reception that accepts new commands, of several kitchens, themselves with several cooks, themselves cooking several dishes.

You will learn to deal with various problems, including load balancing, process and thread synchronization and communication.

Before you get started, should take some time to read up on the following tools you’ll need to use :
- [Processes](https://nodejs.org/api/child_process.html)
- [IPC aka Inter-processcommunication](https://en.wikipedia.org/wiki/Inter-process_communication)

## <a name='exercises'>🐨 Exercises</a>

### = Ex.01 - Deck of Cards

Design the data structures for a generic deck of cards.<br />
Explain how you would subclass the data structures to implement blackjack. 

### = Ex.02 - Call Center

Imagine you have a call center with three levels of employees: `respondent`, `manager`,
and `director`.<br />
An incoming telephone call must be first allocated to a respondent who is free.

If the respondent can't handle the call, he or she must escalate the call to a manager.<br />
If the manager is not free or not able to handle it, then the call should be escalated to a director.

Design the classes and data structures for this problem.<br />
Implement a method dispatchCall() which assigns a call to the first available employee. 

### = Ex.03 - Jukebox

Design a musical jukebox using object oriented principles. 

### = Ex.04 - Parking Lot

Design a parking lot using object-oriented principles. 

### = Ex.05 - Online Book Reader

Design the data structures for an online book reader system. 

### = Ex.06 - Jigsaw

Implement an NxN jigsaw puzzle.<br />
Design the data structures and explain an algorithm to solve the puzzle.

You can assume that you have a fitsWith method which, when passed two puzzle edges, returns true if the two edges belong together.

### = Ex.07 - Chat Server

Explain how you would design a chat server.<br />
In particular, provide details about the various backend components, classes, and methods.

What would be the hardest problems to solve? 

### = Ex.08 - Othello

Othello is played as follows: Each Othello piece is white on one side and black on the other.<br />
When a piece is surrounded by its opponents on both the left and right sides, or both the top and
bottom, it is said to be captured and its color is flipped.

On your turn, you must capture at least one of your opponent's pieces. <br />

The game ends when either user has no more valid moves. The win is assigned to the person with the most pieces.

Implement the object-oriented design for Othello

### = Ex.09 - Circular Array

Implement a CircularArray class that supports an array-like data structure which
can be efficiently rotated.<br />

If possible, the class should use a generic type (also called a template), and should support iteration via the standard f or (Obj o : circularArray) notation.

## <a name='bonus'>🦄 Bonus</a>

I know you love that, well you can in bulk:

* Add graphical version of the reception
* Being able to add new dish very simply (abstraction?)

## <a name='credits'>🐵 Credits</a>

Craft with :heart: in **Paris**.
