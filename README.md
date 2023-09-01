<h1>👋 Hi there, I’m Pavel</h1>

<h2>Learning to Rank</h2>

| Model      | Stack           | Dataset    | Task description                                                                                                                   | ndcg@10 |
|:----------:|:---------------:|:----------:|:----------------------------------------------------------------------------------------------------------------------------------:|:-------:|
| [MLP](https://github.com/pkshcherbakov/Data_Science/blob/main/LTR/MLP_MSRANK.ipynb)       | PyTorch, Optuna | MSrank     | Using the pointwise approach on the MSRANK dataset, the task of ranking involves determining the order of documents based on their relevance to a query. Employing the MLP architecture (Multi-Layer Perceptron), we build a model that predicts the relevance of individual query-document pairs.| 0.4087                                                                                                  
| [RankNet](https://github.com/pkshcherbakov/Data_Science/blob/main/LTR/RankNet_MSRANK.ipynb)   | PyTorch, Optuna        | MSrank  | Utilizing the RankNet architecture within the framework of the pairwise approach and the MSRANK dataset, the ranking task revolves around establishing the sequence of documents by assessing their relevance concerning a given query. The RankNet architecture is specifically tailored for learning these relative rankings between pairs of documents.| 0.4442
| [ListNet]([https://github.com/pkshcherbakov/Data_Science/blob/main/LTR/RankNet_MSRANK.ipynb](https://github.com/pkshcherbakov/Data_Science/blob/main/LTR/ListNet_MSRANK.ipynb)) | PyTorch, Optuna| MSrank | |0.5137
                                                                                                                


<!---
pkshcherbakov/pkshcherbakov is a ✨ special ✨ repository because its `README.md` (this file) appears on your GitHub profile.
You can click the Preview link to take a look at your changes.
--->
