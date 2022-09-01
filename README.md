# Towards stealthy attacks on graphs

## Paper collection on attacks


| Year | Paper/Venue |Name| Target Model |Attack Type|Datasets| Task|
| ------ | ------ | ------ | ------ | ------ |------ |------ | 
| 2019 | XXX/XXX | Metattack | GCN |e.g., add/delete edges, node injection|XXX| node classification|
| 2022 | Unsupervised Graph Poisoning Attack via Contrastive Loss Back-propagation/WWW 2022 | CLGA | GCN | add/delete edges, gradient ascent | Cora,CiteSeer, PolBlog | node classification, link prediction | 
| 2022 | Neighboring Backdoor Attacks on GraphConvolutional Network/Arxiv | GB-FGSM,GB-IG,GB-PGD,LGCB | 2-layer GCN | backdoor attack | BlogCatalog,Flickr,Cora,Pubmed | node classification |
| 2022 | Interpretable and Effective Reinforcement Learning for Attacking against Graph-based Rumor Detection/CORR2022 |  AdRumor-RL  | RGCN | add edges| Weibo,Twitter | rumor detection |
| 2021 | Task and Model Agnostic Adversarial Attack on Graph Neural Networks/Arxiv | GRAND | GNN | neighborhood distortion | Cora,CiteSeer | node classification,link prediction,pairwise  node-classification |
| 2021 | Model Stealing Attacks Against Inductive Graph Neural Networks/IEEE S&P 2022 | Model Stealing Attack I/II | inductive GNNs: GIN, GAT, SAGE | model stealing | DBLP,Pubmed,Citeseer Full,Coauthor Physics,ACM,Amazon Co-purchase Network for Photos | node classification, model stealing |

## Graph Metrics -- measuring the difference between clean graph and attacked graph

| Name| Type| Math Formulation |Ref.|Note|
| ------ | ------ | ------ | ------ | ------ |
| - | -|- | - |-|-| -|


