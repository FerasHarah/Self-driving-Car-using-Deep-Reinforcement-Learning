# Self-driving-Car-using-Deep-Reinforcement-Learning
An significant aspect of the Self-driving vehicle is the steering system that
can mimic the actions of human drivers as a self-driving car controller. This removes
the need for human engineering to predict what is critical in the picture and to set down
all the appropriate rules for safe driving. Deep Renforcement Learning (DRL), due
to its ability to perform and the interaction with the virtual simulation environment,
is the most mature computer training system for this mission. In my project lab, my
car in Carla simulator is being trained using DRL algorithms, our code is pythoned
with the sublime text editor and we have used anaconda3 as a prompt for instructions,
and we have also taken Colab to use it. First, we used the DQN(Deep Q-Learning)
algorithm to train our model to see whether our agent will take ongoing steps, and we
try using a DDPG algorithm that is useful in continuing tracking of behavior.

During this job, I will prepare CARLA simulator for training and attach the
requisite objects such as vehicles, the camera and the sensors of collision. I then
proceed to incorporate our RL algorithms. First, I developed our environment
class with which our agent communicates and the incentives functionality used
in training has been introduced. Next, I built our agent, we must use the reply
memory to practice in DQN in order to make the model more reliable, and tried
to do more random stuff at the start of the training because the model prediction
is more sluggish. Then I added numerous situations I wanted to prepare our
agent.


I’ve concentrated on two models I used to train our agent here. I used a
much complex Xception model with additional parameters. After that I have
turned the model into a much easier 64*4 CNN model. In addition to the
reward functions we carried out, I showed the effects on the tensorboard to test
our model such as accuracy and loss of model. Lastly, on the second model,
our agent checked good behavior, but turning right or left it takes hundreds
of thousands of episodes to be conditioned in order to take good action. We
cannot train more than 12 000 episodes because of our limited capabilities.
