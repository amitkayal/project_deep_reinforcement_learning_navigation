Navigation Project
===========================

In this project I have to train an agent to navigate and collect bananas in a large square world. A reward of +1 is provided
 for collecting a yellow banana, and a reward of -1 is provided for collecting a blue banana. Thus, the goal of my agent is 
 to collect as many yellow bananas as possible while avoiding blue bananas.  Given this information, the agent has to learn how 
 to best select actions. 


In this project, I have used Unity Machine Learning Agent Toolkit to train, evaluate and test the machine Reinforcement Learning
 algorithm. 


<p align="center"><img src="https://user-images.githubusercontent.com/10624937/42135619-d90f2f28-7d12-11e8-8823-82b970a54d7e.gif" alt="Example game of isolation" width="50%" style="middle"></p>



The task is episodic, and The environment is considered solved when a mean score of 17 is achived over 100 consecutive episodes.
 This project is part of the [Deep Reinforcement Learning Nanodegree](https://www.google.com/url?sa=t&rct=j&q=&esrc=s&source=web&cd=1&cad=rja&uact=8&ved=2ahUKEwigwuKwr4LdAhUMI5AKHTuBCz0QFjAAegQIDBAB&url=https%3A%2F%2Fwww.udacity.com%2Fcourse%2Fdeep-reinforcement-learning-nanodegree--nd893&usg=AOvVaw3OfEe4LlR9h_4vW3TZpE_o) program, from Udacity. You can check my report [here](Report.pdf).

### Install
This project requires **Python 3.5** or higher, the Banana Collector Environment, download the code from this repository and the following Python libraries installed:

- [NumPy](http://www.numpy.org/)
- [Torch](https://pytorch.org)
- [UnityAgents](https://github.com/Unity-Technologies/ml-agents)
- [OpenAI Gym](https://gym.openai.com)


### Run
In a terminal or command window, navigate to the top-level project directory `banana-rl/` (that contains this README) and run the following command:

```shell
$ jupyter notebook
```

This will open the Jupyter Notebook software and notebook in your browser which you can use to explore and reproduce the experiments that have been run. 



### License
The contents of this repository are covered under the [MIT License](LICENSE).
