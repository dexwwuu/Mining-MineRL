MineRL is a dataset of player actions and observations recorded as players completed various tasks in the popular game Minecraft. Each player "episode" contained thousands of frames, with each frame recording actions, observations, camera positions, and the reinforcement learning rewards associated with that frame.

While we did not use reinforcement learning, we wanted to see if we could perform a couple tasks on the data, namely:
​
Can we predict a future action or state given the current and previous states?
Can we categorize players into different groups based on their behavior in an unsupervised way?

This Google Colab notebook covers my portion of the project where I used a Random Forest and XGBoost model to determine if it is possible to predict player state-actions.

Download the dataset from the website in the about to run the code in Colab.
