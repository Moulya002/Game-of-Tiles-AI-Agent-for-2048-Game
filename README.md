## **🕹️ Game of Tiles – AI Agent for 2048**

Deep Reinforcement Learning Agent that Learns to Play 2048

## **🚀 Overview**

This project implements an AI agent capable of playing the popular puzzle game 2048 using Deep Reinforcement Learning and Neural Networks.
The objective is to build an autonomous agent that learns optimal gameplay strategies through rewards, improving performance over time and achieving scores higher than human players.

This project demonstrates how machine learning, particularly reinforcement learning, can be used to solve complex decision-making problems in game environments.

## **🎯 Problem Statement**

To develop an intelligent agent that can play the 2048 game efficiently, learn from gameplay experience, and maximize its final score by making optimal moves.

## **🧠 Objectives**

    Train the agent using reinforcement learning to play autonomously.

    Enable the AI to learn from experience and adjust strategies based on rewards.

    Improve performance over time through exploration and exploitation.

    Optimize resource usage so the agent can run on various hardware platforms.

## **🧩 Game Summary**

   Played on a 4×4 grid

   Player moves: Up / Down / Left / Right

   Tiles with the same value merge and form a new tile

   Game objective: Reach tile 2048 (or even higher with the agent)

   Game ends when no more valid moves are available

**🔍 Existing System**

  Traditional gameplay requires manual human input.

  Previous automated approaches used Convolutional Neural Networks trained using supervised learning, but performance was limited.

**🏗️ Proposed System**

  This project replaces the human player with a **Deep Reinforcement Learning agent**.
  
  The agent:

  Observes the board state

  Selects an action based on a learned policy

  Receives a reward

  Updates its neural network weights

  Improves strategy iteratively

**⚙️ Algorithm Overview**

  Initialize board with two random tiles (2 or 4)

  Shift tiles in the chosen direction

  Merge equal-value tiles

  Add a new tile in a random empty cell

  Continue until no valid moves remain

  Reward = number of successful merges (used to train the agent)

## **🧠 Model & Implementation**

    Neural Network: Deep Neural Network (DNN)

    Framework: TensorFlow + Keras

    Optimizer: RMSPropOptimizer

    Activation Function: ReLU

    Training Episodes: 100 million+

    Evaluation every 1 million training episodes

**Techniques used:**

    Q-learning

    Epsilon-greedy exploration

    Reward shaping

    Storing trained weights for reuse

    The network learns game patterns and predicts the best possible move for any given board state.

**💻 Software & Hardware Requirements**

   Languages: Python

   Libraries: Pandas, NumPy, TensorFlow, Keras, OS

   OS: Windows (7, 8, 10)

   Recommended RAM: 4GB or more

## **📊 Results**

    The agent successfully reached the 2048 tile and higher

    Achieved scores significantly higher than human players

    Demonstrated consistent improvement with more training

    Graphical results include:

    Score trends across episodes

    Comparison between human vs. agent moves

    Outputs showing max-tile achievements

## **🧾 Conclusion**

   Deep Reinforcement Learning proves to be an effective approach for learning and mastering the 2048 game.

   The agent learns complex tile-merging patterns that are hard for rule-based systems.

   The project builds upon prior research and demonstrates improved performance using neural networks and reinforcement learning.

## **🛠️ Technologies Used**

    Python

    TensorFlow

    Keras

    NumPy

    Pandas

    Reinforcement Learning (Q-learning)

## **📝 Authors**

  Moulya R. B

  Pranathi
  
  (Under the guidance of Dr. B. Narendra Kumar Rao, Dept. of CSE)

## 🔗 Contact
📧 [moulyarb02@gmail.com](mailto:moulyarb02@gmail.com)  
💼 [LinkedIn](https://www.linkedin.com/in/moulyarb/)  
🌐 [GitHub](https://github.com/Moulya002)
