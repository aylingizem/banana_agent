# Banana  Agent

## Project's goal

The goal is for this project train an agent to navigate a virtual world and collect yellow bananas while avoiding blue bananas

Example of the virtual world

![navigation banana](img/navigation_banana.gif)

## Project Details
* The goal is to collect the yellow ones while avoiding the blue ones. 
* This environment provides states to the agent in the form of a 37-dimensional continuous space. 
* It contains the agent's velocity, along with a ray-based perception of objects around the agent's forward direction.
* In response to this state, the agent can take one of these four actions: move forward, move backward, turn left or turn right.
* A reward of +1 is obtained for each yellow bananas encountered and -1 for the blue ones. 
* The environment is considered solved when the average score over 100 episodes overreaches 13.



## Instructions 

1. To install the requirements
```
pip install -r requirements.txt
```

2. run the navigation.py as
```
python navigation.py
```

## Conclusion

In this scenario,

* Environment solved in 1109 episodes	and average score is 13.01.
* Total Training time = 57.5 min

