# Sustainability Hackathon


## Timetable for the day?
10 - 5
2x speakers. 1 more general sustainability + data science, 1 more technical

|time |activity|
|-----|--------|
|1000 |demos and exercises|
|1200 |speaker general|
|1300 |lunch break|
|1400 |speaker technical|
|1500 |hack!|
|1630 |results and wrap up|


## Demos and Exercises section


### Thinking about costs of research computing
- programmer time/effort
- processor time/energy
- data centre water
- …

### How to estimate carbon footprint of the code?
Demo: NetworkX / betweenness centrality on a random network?
- is there a simple equation to estimate carbon footprint?
 - use basic profiling tools to estimate (look at Chris's course?)
- show more sophisticated tools to estimate (codecarbon etc?)
- Exercise: Train MultiLayerPerceptron (neural network) for regression task
 - investigate how regression performance increases with number of layers / size of layers
  - investigate how training cost (carbon) increases with number of layers / size of layers …


### Which approaches / packages will help us to reduce carbon?
- ?using vectorised computations in python
- ?sparse vs dense matrices trade off
- ?using parallelisation where appropriate
- ?other things?

### Introduction to hackathon task
You are given some data about houses and their prices.
Your task is to build a workflow to train a regression model (of any kind) to estimate house price. 
You can make use of any python packages you like.
You are free to use GenAI as much as you like.
You must include in your submission an estimate of your development carbon cost.

We will run your workflow *on a new set of training data* and estimate total carbon cost for training + 1000 predictions.
The model will be considered useful if it achieves an r2 score >0.9 on our test dataset.
The team with the lowest total carbon cost (development + training + predictions) will be declared the winners.

#### how to estimate carbon footprint of LLM use including copilot?
- estimate using single query (ideally copilot?)
- how to apply this to get a rough estimate of own development cost.

#### how to set up github codespace for reproducibility
- give people the essential info to make codespace and submit to competition.



## Part 2

Hack…

Competition / results / discussion

