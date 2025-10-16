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
- LangSmith Studio allows you to set up, view, and test your agents in an interactive environment.
- In the Threads section of the Studio, you can monitor and trace different runs of your graphs.
- You can also add multiple inputs to the graph state to create and connect various nodes, building the complete graph structure.
![Alt Text](image1.png)

## Lesson 4: Chain
- We create a basic process where chat messages are used, the AI model talks back, we connect tools to the AI, and the AI can use those tools while running the process.
- We can give a bunch of messages to the chat AI for it to read and respond.
- To link our chat AI to an external tool like an API, we need to give it a set of information to work.
- Reducers let you attach or combine new messages into your chat.
- In the **tweaks** I have made changes in the given datasets used my own questions and prepared a different tool and then integrated into the chat model.
