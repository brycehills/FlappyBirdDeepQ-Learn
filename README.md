# Deep Q-Learning using Flappy Bird
### Graduate Aritificial Intelligence Project #2

* Question: Since the game of Flappy bird can be frustrating and hard to complete, we want to know if it is possible to train an AI to complete the game using a machine learning techinques.

* Dataset: With a pre-defined flappy bird game enviorment, we determine that our dataset will consist of every possbile game state combined with all possible actions and then train it to learn actions by using reward scores. We are hopeful that a combination of this data with a learning technique can effectively solve our problem.

* Method: We decided that an effective techinque to solve our problem defined in (1) and using the dataset defined in (2), will be using reinforcement learning. At a high level, this method will train our agent when it takes an action in the flappy bird enviornment, and give it a score based on the outcome of the move. This way at each step we can learn from previous actions (rewards vs consequences) to determine the best overall score.

### Authors
* Shuai Yan 
* Bryce Hills
* Varun Sapre

### Package Installation
```bash
* !pip3 install torch==1.12.1 torchvision==0.13.1 -f https://download.pytorch.org/whl/torch_stable.html
* !pip install pygame
* !pip install numpy
* !pip install wget
```
