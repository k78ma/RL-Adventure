# RL-Adventure

Learning control policies for text-based games using reinforcement learning!
In these games:
- All interactions between players and the virtual world are through text.
- The current world state is described by elaborate text, and the underlying state is not directly observable.
- Players read descriptions of the state and respond with natural language commands to take actions.

We use a small "Home World", mimicking the environment of a typical house with a few rooms, with each room containing a representative object that the player can be interacted with. The player is given a quest, which must be completed; for example, if the given quest is "You are hungry now", the player has to navigate to the kitchen and eat an apple.

The following methods are used to solve this problem:
- Tabular Q-learning algorithm for a simple setting, where each text description is associated with a unique index.
- Q-learning algorithm with linear approximation architecture, using bag-of-words representation for textual state description.
- Deep Q-network

Project from MITx 6.86x (Graduate-level course "Machine Learning with Python-From Linear Models to Deep Learning").

