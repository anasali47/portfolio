# ML-Agent AI (Reinforcement Learning)
The project's aim is to train an AI that is capable of picking up an object and 
bring it to a target position. In this case, the ai will learn to pickup the coin and bring it to the bucket
<br/><br/>
![mlAgent1](https://raw.githubusercontent.com/anasali47/portfolio/main/MLAgentAI/Images/mlagent1.PNG)
<br/><br/>
The AI will be trained using Reinforcement/Deep-q learning method where the agent is given list of actions that they can perform. The programmer then can give rewards to encourage or discourage a certain behaviours. In this case, the agent is given 2 actions, which is the ability to move on the X-axis and Z-axis. For the rewards, the agent will get positive reward whenever it picks up the coin and bring it to the bucket. Negative reward is given when the agent falls down from the platform.
<br/><br/>
Here's the result
<br/><br/>
Episode 0-100000 of training
<br/><br/>
![mlAgent2](https://raw.githubusercontent.com/anasali47/portfolio/main/MLAgentAI/Images/MLagentE0.gif)
<br/><br/>
After 5000000 episodes of training
<br/><br/>
![mlAgent3](https://raw.githubusercontent.com/anasali47/portfolio/main/MLAgentAI/Images/MLAgentTrained.gif)