# deep_learning_fairness
Repo for Deep Learning tutorial 

1. Tutorial title 

What is the gender of a data scientist? Addressing bias in Natural Language Processing.

2. Names of all group members

Angela Duarte Pardo
Anna Clara Deniz
Anna Weronika Matysiak
Francesca Giacco
Helena Bakic

3. Description of preferred topic: 

Large NLP models are often trained by scraping large quantities of internet data, which might be unbalanced and reflect biases against specific populations, including stereotypical associations and negative sentiments (see, Bender, 2021). It’s not surprising that the models reproduce these biases in language generating and translation tasks. Female/male gender stereotypes were found in various pre-trained word embeddings, even the commonly used word2vec trained on Google News articles. In our tutorial, we will test how a Double-Hard Debias algorithm works compared to no debiasing in a language generation task on a challenge data set, such as Winogender.

Note: for the language generation task, we plan to reuse one of the existing models, in order to focus on debiasing.

Further resources:

Hard Debias algorithm
Double-Hard Debias algorithm + GitHub repository
Gender Bias in NMT
Winogender dataset
Fairness and Bias Mitigation · A Guide to Natural Language Processing With AllenNLP

4. Description of alternative topic:

To keep models from reproducing biases, datasets should be inspected to account for such stereotypical associations. “Garbage in-Garbage out” the saying goes. Balancing, diversifying, and Counterfactual Data Substitution are methods used to provide models with higher quality training data. 

In an alternative scenario, we would use the Winogender dataset on the same models to test the performance of  the Counterfactual Data Substitution approach, as presented by Maudslay et. al and Zaho et al. (2018).
5. Optional comments, such as why your group wants to focus on that topic

Algorithms and models are used to substitute humans in several processes, including decision-making ones. In many cases they are implemented especially because they are believed to reduce human biases. However, we have now learnt how algorithms and models can learn, reproduce and even reinforce biases, depending on their use. With this tutorial, we aim to learn how, either models or datasets used for training, can be “debiased”. We have decided to focus on gender biases because this topic touches us all personally.
