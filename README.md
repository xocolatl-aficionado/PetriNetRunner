# PetriNetRunner
Runs PN analyses on PN nets using LoLA

## A trivial deadlocking example

## The 5 dining philosophers cant eat

If each philosopher picks up their left fork, does some thinking, and then tries to pick up the other fork when done, they'd realize no one can eat. After all, the one to the right needs to put down the fork they picked up in order to allow the other to eat. But how can they put down the fork they picked up if they havent eaten themselves? 

## 4 out of 5 philosophers can eat

One way to solve the dining philosopher problem is to ensure that each philosopher picks up both forks on either side simultaneously when they are done thinking and ready to eat instead of locking up resources when they arent quite ready to use them. 
