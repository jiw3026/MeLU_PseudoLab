# MeLU: Meta-Learned User Preference Estimator for Cold-Start Recommendation

PyTorch implementation of the paper: "MeLU: Meta-Learned User Preference Estimator for Cold-Start Recommendation", KDD, 2019.

## Abstract
This paper proposes a recommender system to alleviate the coldstart problem that can estimate user preferences based on only a small number of items. To identify a user’s preference in the cold state, existing recommender systems, such as Netflix, initially provide items to a user; we call those items evidence candidates. Recommendations are then made based on the items selected by the user. Previous recommendation studies have two limitations: (1) the users who consumed a few items have poor recommendations and (2) inadequate evidence candidates are used to identify user preferences. We propose a meta-learning-based recommender system called MeLU to overcome these two limitations. From metalearning, which can rapidly adopt new task with a few examples, MeLU can estimate new user’s preferences with a few consumed items. In addition, we provide an evidence candidate selection strategy that determines distinguishing items for customized preference estimation. We validate MeLU with two benchmark datasets, and the proposed model reduces at least 5.92% mean absolute error than two comparative models on the datasets. We also conduct a user study experiment to verify the evidence selection strategy.

## Usage
### Requirements
- python 3.6+
- pytorch 1.1+
- tqdm 4.32+
- pandas 0.24+
