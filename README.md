<h1>👋 Hi there, I’m Pavel</h1>

<h2>Learning to Rank</h2>

| Model      | Stack           | Dataset    | Task description                                                                                                                   | ndcg@10 |
|:----------:|:---------------:|:----------:|:----------------------------------------------------------------------------------------------------------------------------------:|:-------:|
| [MLP](https://github.com/pkshcherbakov/Data_Science/blob/main/LTR/MLP_MSRANK.ipynb)       | PyTorch, Optuna | MSrank     | The primitive pointwise approach for LTR task using MLP architecture| 0.5031                                                                            
| [RankNet](https://github.com/pkshcherbakov/Data_Science/blob/main/LTR/RankNet_MSRANK.ipynb)   | PyTorch, Optuna        | MSrank  | The pairwise approach of RankNet architecture allows to minimize number of swapped documents pairs | 0.5116
| [ListNet](https://github.com/pkshcherbakov/Data_Science/blob/main/LTR/ListNet_MSRANK.ipynb) | PyTorch, Optuna| MSrank | The listwise approach of ListNet architecture allows to use the loss function that is calculated over the entire set of documents|0.5137|
                                                                                                                
<h2>RL (Reinforcement learning)</h2>

| Model                                                                                                                   | Stack      | Dataset  | Task description                                            | Mean reward |
|:-----------------------------------------------------------------------------------------------------------------------:|:----------:|:--------:|:-----------------------------------------------------------:|:-----------:|
| [CrossEntropy](https://github.com/pkshcherbakov/Data_Science/blob/main/RL/CrossEntropy.ipynb)                           | Gym, Optuna| Taxi-v3  | It is required to train a taxi to pick up a passenger and then take him to the destination point                             | 7.93        |

# List of books
## Python
- Lutz, Mark. **Learning Python**. O'Reilly Media, Inc., 2013.

## Data Science
- Bhargava, Aditya. **Grokking Algorithms: An Illustrated Guide for Programmers and Other Curious People**. Simon and Schuster, 2016.
- Trask, Andrew W. **Grokking Deep Learning**. Simon and Schuster, 2019.

## Statistics
- Савельев, Владимир. **Статистика и Котики**. Litres, 2018.

<!---
pkshcherbakov/pkshcherbakov is a ✨ special ✨ repository because its `README.md` (this file) appears on your GitHub profile.
You can click the Preview link to take a look at your changes.
--->
