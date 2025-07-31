# Drone Reinforcement Learning Project

## Overview
This project, located in the `004 Dron Game` directory, focuses on developing and training a reinforcement learning (RL) agent to navigate a drone in a custom environment. The project uses Python, Jupyter Notebooks, and reinforcement learning techniques, specifically Q-learning, to train and evaluate the drone's performance. The environment is built using the Gymnasium library, and the results are visualized through rendered HTML outputs and evaluation plots.

## Directory Structure
- **Root Directory (`MYRL/`)**:
  - `001 Gymnasium/`: Initial experiments with Gymnasium for environment setup.
  - `002 Q_learning/`: Implementation of Q-learning algorithms.
  - `003 DQN/`: Deep Q-Network (DQN) experiments.
  - `004 Dron Game/`: Main project directory for the drone RL environment.
  - `Test_gym/`: Testing Gymnasium environments.
  - `imgs/`: Stores evaluation plots for the drone's performance.
  - `README.md`: Project overview and instructions.

- **004 Dron Game Directory**:
  - `001 Create_Dron_env.ipynb`: Notebook for creating the custom drone environment.
  - `002 Drone_train.ipynb`: Notebook for training the RL agent using Q-learning.
  - `003 Dron_Eval.ipynb`: Notebook for evaluating the trained agent's performance.
  - `Drone_env.ipynb`: Additional notebook for environment setup and testing.
  - `drone_environment_render.html`: Rendered visualization of the drone environment.
  - `drone_environment_render2.html`: Alternative rendered visualization.

- **imgs Directory**:
  - `dron_q_learn_1_eval.png`: Evaluation plot 1 for Q-learning performance.
  - `dron_q_learn_2_eval.png`: Evaluation plot 2 for Q-learning performance.
  - `dron_q_learn_3_eval.png`: Evaluation plot 3 for Q-learning performance.

## Project Goals
- Create a custom Gymnasium-based environment for a drone.
- Train an RL agent using Q-learning to navigate the environment.
- Evaluate the agent's performance and visualize results using plots and rendered HTML outputs.

## Prerequisites
To run this project, ensure you have the following installed:
- Python 3.8+
- Jupyter Notebook
- Required Python libraries:
  - `gymnasium`
  - `numpy`
  - `matplotlib`
  - `pandas`
  - Any additional dependencies listed in the notebooks

Install dependencies using:
```bash
pip install gymnasium numpy matplotlib pandas
```

## Getting Started
1. **Clone the Repository**:
   ```bash
   git clone https://github.com/your-username/your-repo.git
   cd your-repo/RL/MYRL/004\ Dron\ Game
   ```

2. **Run the Notebooks**:
   - Start with `001 Create_Dron_env.ipynb` to set up the drone environment.
   - Proceed to `002 Drone_train.ipynb` to train the RL agent.
   - Use `003 Dron_Eval.ipynb` to evaluate the agent's performance.
   - Optionally, explore `Drone_env.ipynb` for additional environment testing.

3. **View Visualizations**:
   - Open `drone_environment_render.html` or `drone_environment_render2.html` in a web browser to view the rendered drone environment.
   - Check the `imgs/` directory for evaluation plots (`dron_q_learn_1_eval.png`, etc.).

## Usage
- **Environment Creation**: The `001 Create_Dron_env.ipynb` notebook defines the custom drone environment using Gymnasium, including state space, action space, and reward structure.
- **Training**: The `002 Drone_train.ipynb` notebook implements Q-learning to train the drone agent to navigate the environment.
- **Evaluation**: The `003 Dron_Eval.ipynb` notebook evaluates the trained agent and generates performance metrics, visualized in the `imgs/` directory.
- **Visualization**: The rendered HTML files (`drone_environment_render.html` and `drone_environment_render2.html`) provide interactive visualizations of the drone's behavior.

## Results
The evaluation plots in the `imgs/` directory (`dron_q_learn_1_eval.png`, `dron_q_learn_2_eval.png`, `dron_q_learn_3_eval.png`) show the agent's performance metrics, such as cumulative rewards and episode lengths, over multiple evaluation runs.

## Contributing
Contributions are welcome! Please follow these steps:
1. Fork the repository.
2. Create a new branch (`git checkout -b feature-branch`).
3. Make your changes and commit (`git commit -m "Add feature"`).
4. Push to the branch (`git push origin feature-branch`).
5. Open a pull request.

## License
This project is licensed under the MIT License. See the [LICENSE](LICENSE) file for details.

## Contact
For questions or suggestions, please open an issue on GitHub or contact [your-email@example.com].