# Multi-Armed Bandit Problem and UCB Algorithm

This project explores the **Multi-Armed Bandit problem**, a classic reinforcement learning scenario where an agent must choose actions (like selecting ads) to maximize cumulative reward. We will focus on implementing and evaluating the **Upper Confidence Bound (UCB)** algorithm, a popular strategy for balancing exploration (trying new options) and exploitation (sticking with known good options). We will also compare UCB's performance to other simple strategies like Random Selection and Epsilon-Greedy.

## 📝 Dataset

This project uses the `Ads_CTR_Optimisation.csv` dataset. This dataset contains 10,000 rows, representing users, and 10 columns, representing different ads. Each cell contains a 1 if the user clicked on the ad and a 0 otherwise.

## 🤖 Algorithms

### Upper Confidence Bound (UCB)

The UCB algorithm is a deterministic algorithm that helps to solve the multi-armed bandit problem. It creates a balance between exploration and exploitation by maintaining an upper confidence bound for each arm (ad). In each round, the algorithm selects the arm with the highest upper confidence bound.

### Other Algorithms

  * **Random Selection**: This is a simple strategy where we randomly select an ad to show to the user in each round.
  * **Epsilon-Greedy**: This algorithm is a simple method to balance exploration and exploitation by choosing between exploration and exploitation randomly.

## 📊 Results

The project includes a visualization of the total rewards per ad, which helps in understanding the performance of each ad. The notebook also visualizes the results of the UCB algorithm, comparing its performance with the other strategies.

## ⚙️ Dependencies

This project requires the following Python libraries:

  * `math`
  * `numpy`
  * `pandas`
  * `matplotlib`

You can install the dependencies using pip:

```bash
pip install numpy pandas matplotlib
```

## ▶️ How to Run

To run this project, you can use Jupyter Notebook or any other IDE that supports `.ipynb` files.

1.  Clone the repository:
    ```bash
    git clone https://github.com/your-username/your-repository.git
    ```
2.  Navigate to the project directory:
    ```bash
    cd your-repository
    ```
3.  Open the `UCB_ad_prediction.ipynb` notebook in Jupyter Notebook:
    ```bash
    jupyter notebook UCB_ad_prediction.ipynb
    ```
4.  Run the cells in the notebook to see the implementation and results.
