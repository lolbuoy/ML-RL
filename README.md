# Q-Learning with Cart-Pole Environment

This project demonstrates the implementation of Q-learning in the Cart-Pole environment using Python. The Cart-Pole problem is a classic reinforcement learning task where the objective is to balance a pole on a cart by applying forces to the cart.

![Cart-Pole Environment](placeholder-image.jpg)

## Project Structure

- `driverCode.py`: The main script that initializes the environment and runs the Q-learning algorithm.
- `functions.py`: Contains helper functions for Q-learning, such as state discretization, action selection, and Q-table updates.
- `convergence.png`: A plot showing the sum of rewards obtained in each episode, demonstrating the learning progress of the Q-learning algorithm.

## Prerequisites

Make sure you have Python (>= 3.6) installed. You can install the necessary libraries using the following command:

```
pip install -r requirements.txt
```

## Running the Code

1. Clone the repository to your local machine.
2. Navigate to the project directory.
3. Install the required dependencies:
   ```
   pip install -r requirements.txt
   ```
4. Run the main script:
   ```
   python driverCode.py
   ```
