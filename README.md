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

<h2>Deep Learning</h2>

| Model                        | Stack      | Dataset  | Task description                                            | Accuracy |
|:----------------------------:|:----------:|:--------:|:-----------------------------------------------------------:|:-----------:|
| [CNN](https://github.com/pkshcherbakov/Data_Science/blob/main/Audio%20processing/ESC50.ipynb)  | librosa, keras| ESC-50  | The goal of the work was to classify various sounds (for example, frog, wind, footsteps, etc.) according to an audio track  | 94.9%        |

<h2>NLP</h2>

| Model                        | Stack      | Dataset  | Task description                                            | Metrics |
|:----------------------------:|:----------:|:--------:|:-----------------------------------------------------------:|:-----------:|
| [NER](https://github.com/pkshcherbakov/Data_Science/blob/main/NLP/Named%20entity%20recognition.ipynb)  | yargy, natasha| custom  | NER task. The purpose of this task is to extract from the machine recording of the dialogue between the operator and the client phrases corresponding to greetings, farewells and other communication patterns  | -       |


# List of books
## Python
- Lutz, Mark. **Learning Python**. O'Reilly Media, Inc., 2013.

## Data Science
- Bhargava, Aditya. **Grokking Algorithms: An Illustrated Guide for Programmers and Other Curious People**. Simon and Schuster, 2016.
- Trask, Andrew W. **Grokking Deep Learning**. Simon and Schuster, 2019.
- Avila, Julian, and Trent Hauck. **Scikit-learn cookbook: over 80 recipes for machine learning in Python with scikit-learn**. Packt Publishing Ltd, 2017.
- Grus, Joel. **Data science from scratch: first principles with python**. O'Reilly Media, 2019.
- Lakshmanan, Valliappa, Sara Robinson, and Michael Munn. **Machine learning design patterns**. O'Reilly Media, 2020.

## Statistics
- Савельев, Владимир. **Статистика и Котики**. Litres, 2018.
- Bruce, Peter, Andrew Bruce, and Peter Gedeck. **Practical statistics for data scientists: 50+ essential concepts using R and Python**. O'Reilly Media, 2020.

## Git
- Gandhi, Raju. **Head First Git**. " O'Reilly Media, Inc.", 2022.

<!---
pkshcherbakov/pkshcherbakov is a ✨ special ✨ repository because its `README.md` (this file) appears on your GitHub profile.
You can click the Preview link to take a look at your changes.
--->
