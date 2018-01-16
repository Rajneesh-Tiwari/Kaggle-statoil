# Kaggle-statoil
Repo for kaggle statoil competition

Approaches tried:

1. Pretrained VGG16 based network with 'incidence angle' as a separate input layer
2. Pretrained VGG19 based network with 'incidence angle' as a separate input layer
3. Pretrained Inception based network without 'incidence angle' as a separate input layer
4. Four layer CNN with 'incidence angle' as a separate input layer
5. 4 layer CNN without 'incidence angle' as a separate input layer
6. Feature engineering on band sizes based on Kaggle kernel listed below. A couple VGG based models are used with additional features concatenated after getting pretrained output. The additional features are used in b/w layers and are concatendated with pre-trained models' outputs for a certain layer (Blockpool5 for VGG16)
7. Most models also include 'data augmentation', 'test time augmentation' and use of pesudolabels to improve generalization in presence  of low sample size
8. A stacking based approach is also listed
9. All featre engineering stuff is based on Kaggle kernels https://www.kaggle.com/submarineering/submarineering-even-better-public-score-until-now
