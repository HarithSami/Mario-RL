## Mario Reinforcement Learning Project
This project uses reinforcement learning to teach Mario to play the classic Super Mario Bros game. The project is divided into three parts: preprocessing the environment, training the reinforcement learning model, and testing the model.

# Preprocessing Environment
In this section, the environment is preprocessed to simplify the controls, grayscale the frames, wrap the environment in a dummy environment, and stack the frames. This is done to reduce the complexity of the environment and make it easier for the reinforcement learning model to learn.

# Training the RL Model
In this section, the reinforcement learning model is trained using the PPO algorithm. The model is saved at regular intervals using a callback to enable resuming training if needed. The model is trained for 1,000,000 steps.

# Testing the Model
In this section, the trained model is loaded, and the game is played using the trained model. The model is used to predict actions, and the game is rendered on the screen.

# Requirements
This project requires the following packages to be installed:

gym_super_mario_bros==7.3.0
nes_py
stable-baselines3
# Usage
To run this project, please follow the steps below:

Install the required packages using the following command:

!pip install gym_super_mario_bros==7.3.0 nes_py stable-baselines3[extra]

Run the code blocks in the provided order to preprocess the environment, train the reinforcement learning model, and test the model.

Note: Some of the code blocks may take a long time to run, especially the training section.

# References
The code in this project is based on the following resources:

[gym-super-mario-bros](https://github.com/Kautenja/gym-super-mario-bros)

[stable-baselines3](https://github.com/DLR-RM/stable-baselines3)
