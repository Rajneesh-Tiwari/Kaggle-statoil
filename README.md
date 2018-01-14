# Kaggle-statoil
Repo for kaggle statoil competition

Approaches tried:

1. Pretrained VGG16 based network with 'incidence angle' as a separate input layer
2. Pretrained VGG19 based network with 'incidence angle' as a separate input layer
3. Pretrained Inception based network without 'incidence angle' as a separate input layer
4. Four layer CNN with 'incidence angle' as a separate input layer
5. 4 layer CNN without 'incidence angle' as a separate input layer
6. Most models also include 'data augmentation', 'test time augmentation' and use of pesudolabels to improve generalization in presence  of low sample size
