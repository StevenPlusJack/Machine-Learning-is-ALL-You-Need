# Machine-Learning-Basic-Codesð

æ±å­äºï¼

> æè°è´ç¥å¨æ ¼ç©èï¼è¨æ¬²è´å¾ä¹ç¥ï¼å¨å³ç©èç©·å¶çä¹ãçäººå¿ä¹çµï¼è«ä¸æç¥ï¼èå¤©ä¸ä¹ç©ï¼è«ä¸æçãæäºçææªç©·ï¼æå¶ç¥æä¸å°½ä¹ãæ¯ä»¥å¤§å­¦å§æï¼å¿ä½¿å­¦èå³å¡å¤©ä¸ä¹ç©ï¼è«ä¸å å¶å·²ç¥ä¹çèçç©·ä¹ï¼ä»¥æ±è³ä¹å¶æãè³äºç¨åä¹ä¹ï¼èä¸æ¶è±ç¶è´¯éçï¼åä¼ç©ä¹è¡¨éç²¾ç²æ ä¸å°ï¼èå¾å¿ä¹å¨ä½å¤§ç¨æ ä¸æç£ã

ðð
> **æ ¼ç© (Ko Wu) which means 'investigate the essence of things' in English is a key method for study and better understanding of the knowledge.** It is proposed by ancient Chinese philosophers about 2000 years ago and has a profound impact on later generations. The spirit of Ko Wu asks us to not only learn how to use knowledge, but also clearly understand the intrinsic theory. Therefore, it is necessary to re-implement ML algorithms by ourselves to figure out what exactly they did and why they succeed.

This repository aims to implement popular Machine Learning and Deep Learning algorithms by **both pure python and use open-source frameworks**.

- Common Machine Learning Part: switch by **`use_sklearn` flag** in the main functionï¼
- Deep Learning Part: **four** implement methods for each algorithm (`use_sklearn`, `use_keras`, `use_torch` and **`self_implement`**)ï¼
- Applications Part: **RL + NLP + CV**
- New trend: **GNNs**

## Welcome everyone to help me finish this Ko Wu project by pulling requests or giving me some suggestions and issues!!!

## å³èç¥ä¹ä¸æ  Associated Zhihu Blog

[RL in Robotics](https://zhuanlan.zhihu.com/c_1188392852261134336)

[Machine Learning æ ¼ç©å¿](https://zhuanlan.zhihu.com/c_1236984830903996416)

## ä»£ç ç®å½ Code Catalog

### Regression
1. [Single Linear Regression](./01Single_Linear_Regression/1Single_Linear_Regression.py)
2. [Multiple Linear Regression](./02Multiple_Linear_Regression/2Multiple_Linear_Regression.py)

### Classification
3. [Logistic Regression](./03Logistic_Regression/3Logistic_Regression.py)
4. [KNN](./04K_Nearest_Neighbours/)
5. [Support Vector Machine](./05Support_Vector_Machine/)
6. [Naive Bayes](./06Naive_Bayes/)

### Regression & Classification
7. [Decision Tree](./07Decision_Trees/)
8. [Random Forest](./08Random_Forest/)

### Neural Network
9. [Feedforward Neural Network](./09Neural_Network/)
10. [Convolutional Neural Network](./10CNN/)
11. [LSTM](./11LSTM/)

### Unsupervised Learning
12. [PCA](./12PCA/)
13. [K-Means](./13Kmeans/)

### Ensemble Model
14. [Boosting](./14Boost/)

### Reinforcement Learning
1.  [**Value Based Methods**](./RL_DQN/): [Q-learning(Tabular)](./RL_DQN/Q_learning.py), [DQN](./RL_DQN/15DQN.py)
2.  [**Policy Based Methods**](./RL_PPO/): [Vanilla Policy Gradient](./RL_PPO/vanilla_PG.py), [TRPO](./RL_PPO/TRPO.py), [PPO](./RL_PPO/16PPO.py)
3.  [**Actor-Critic Structure**](./RL_Actor_Critic/): AC, [A2C](./RL_Actor_Critic/17Actor_Critic.py), A3C
4.  [**Deep Deterministic Policy Gradient**](./RL_DDPG): [DDPG](./RL_DDPG/18DDPG.py), [DDPG C++ (Undone)](./RL_DDPG/DDPG_LibTorch-master/), [TD3](./RL_DDPG/TD3.py)
5.  [**Soft Actor-Critic**](./RL_SAC/)

### Computer Vision
1. [ **GAN** ](./CV_GAN/)
2. [**Resnet**](./CV_Resnet/): [Pytorch version](./CV_Resnet/21Resnet.py), [libtorch C++ version](./CV_Resnet/Resnet_libtorch_C++/py_2_C.py)
3. [**VGG**](./CV_VGG/)
4. [**FlowNet**](./CV_FlowNet/)

### Natural Language Processing
1. [Attention mechanism](./NLP_Attention/)
2. [Transformer](./NLP_Transformer/)
3. BERT

### Graph Neural Networks 
1. [Graph Neural Network (GNN)](./Graph_GNN/)
2. Graph Convolutional Neural Network (GCN)
3. Graph Attention Networks (GAT)
4. GraphSAGE
5. GraphRNN
6. Variational Graph Auto-Encoders (GAE)
