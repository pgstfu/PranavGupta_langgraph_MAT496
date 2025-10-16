# PranavGupta_langgraph_MAT496

## Setup
- Setting up vs code for the langgraph project.
- Pasting commands from the given readme file in the github to download the neccesary libraries.

# Module 0
- It explains the basic setup required for the langgraph further
- It has the information regarding the different fields of chat models such as their temperature(Randomness), stream(stream chunks of response), invoke.

# Module 1
## Lesson 1: Motivation
- LLM uses control flow. (very reliable as same path taken every time)
- ⁠Agent is a control flow determined by an LLM.
⁠- When we go from a simple agent (router) to complex (autonomous) the application reliability decreases and the level of control increases. (as the randomness for the autonomous is much more than simple agent)
- ⁠We can balance reliability with langgraph according to our need.
- Langgraph comes with an IDE which helps you visulaise and debug the agents that you build.

## Lesson 2: Simple graph
- Learning how to build a simple graph with 3 nodes.
- State is the path between the nodes and edges of the graph.
- Edges are interconnected through nodes
- In the given example we use if statement to choose between node 2 and 3.
- When the invoke command is called it starts the graph from _START_ then traverses through node 1 in the given example, makes a choice between 2 or 3 and the _END_
- In the **tweaks** i have tried making a bigger graph using the same exact logic.

## Lesson 3: LangSmith Studio
- 



