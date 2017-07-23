# OpenAi-CartPole_v0-Agent
An OpenAi game bot for CartPole built using a 5 layer Deep Neural Network.

5 layered deep neural network built on Tensorflow on top of tflearn.

The game bot/agent learns with experience(training). At one point of time with enough data/training, eventually the agent will get so good at this that even the best human player of this game on the planet will not be able to achieve.

I've used 5 epochs to train the model, feel free to tune this or the learning rate to your needs when you fork this.
Getting an average score of about 180+.

I leveraged the CUDA enabled GeForce 940MX with a compute capability of 5.1 to train this model. Now, you might be running python on a machine without this capability. So, I've uploaded the trained model as well (.model file). Simply load this model, uncomment the model.save() line and you should be on your way.

You can pretty easily modify this agent to support different OpenAi simulations.

Requirements:

Python3.5

numpy

scipy

tensorflow(tensorflow-gpu)

tflearn

gym
