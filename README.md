# Tabula Rasa Doom

![godlike](https://github.com/LawnboyMax/tabula_rasa_doom/blob/master/doom-god-mode.jpg)

An implementation of deep Q-learning neural network playing ViZDoom that uses TF Eager Execution :godmode:

This project was completed during [CodeJam 2018 at McGill University](https://codejam.mcgilleus.ca). Here's the [Devpost submission](https://devpost.com/software/1337-doom).

# Description

We've re-implemented a CNN used in the original article using TF Eager Execution and put an agent into a different environment called "Take Cover". See more detailed description on the Devpost page.

# Tools and resources used

- [Deep Q learning with Doom](https://github.com/simoninithomas/Deep_reinforcement_learning_Course/blob/master/Deep%20Q%20Learning/Doom/Deep%20Q%20learning%20with%20Doom.ipynb) article and notebook by [@simoninithomas](https://github.com/simoninithomas) was used heavily as a guide.
- [Tensorflow Eager Execution](https://www.tensorflow.org/guide/eager) was used to re-write the deep learning model and training procedure in order to make them easier to understand and improve performance.
- [ViZDoom](https://github.com/mwydmuch/ViZDoom) Doom-based AI research platform for reinforcement learning from raw visual information. It allows developing AI bots that play [Doom](https://en.wikipedia.org/wiki/Doom_(1993_video_game)) using only the screen buffer
- [SLADE3](http://slade.mancubus.net/) Doom map scenario and script editor. It was used to customize the environment (e.g. speeding up the agent's and enemies' speed reduces the lenght of each training episode and overall training time).
