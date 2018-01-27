This is just a minor tweak from [this](https://github.com/pemami4911/deep-rl) repo.

The algorithm is DDPG. See [this post](http://pemami4911.github.io/blog/2016/08/21/ddpg-rl.html) as a great intro to the algorithm.

The main difference is that this repo uses [roboschool](https://github.com/openai/roboschool) instead of plain OpenAi Gym. Roboschool features the awesome [Bullet 3D physics engine](http://bulletphysics.org/wordpress/).

The repo defaults to the classic cartpole problem, and with Roboschool the actions for this env are continuous (in this case representing motor voltage), which really lets the DDPG algorithm stretch its legs.

![demo](small_demp.gif "Small Demo of Render")


Dependencies:

* [Tensorflow 1.3.0](https://www.tensorflow.org/install/)
* [tflearn](http://tflearn.org/installation/)
* [OpenAI Gym 0.9.2](https://github.com/openai/gym/)
* [Roboschool](https://github.com/openai/roboschool)

Tested with Python 2.7 and Python 3.6
