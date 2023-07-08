# Task-Classification

We are classifying a given task into a group of predefined projects.

It could be helpful with Productivity environments/programs to classify new tasks to the current projects automatically.

This project uses pre-trained GloVe word embeddings following a technique to measure the distance between the task sentence and the projects name and use this distance to calculate the probability for each class using the SOFTMAX equation, then assign the new task to the class with the highest probability.

## Example:
* We have the following task sentence.... </br>
    ![image](https://github.com/Mohamed2bdelaziz/Task-Classification-/assets/110987609/4d54c003-83b3-41ff-93b8-55235b624a91)
* And we have projects named as follows     ["Personal", "Work", "Technology", "Family", "collage"]
* The algorithm will calculate the probability that the new task follows each project as follows....</br>
      ![image](https://github.com/Mohamed2bdelaziz/Task-Classification-/assets/110987609/cb5a89be-075b-4cf4-946d-3bb1e0eea470)
* Finally, it will assign the new task to the project with the highest probability.
