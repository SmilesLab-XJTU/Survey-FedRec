# A Scenario-Oriented Survey of Federated Recommender Systems: Techniques, Challenges, and Future Directions

This is a repository for our survey "**A Scenario-Oriented Survey of Federated Recommender Systems: Techniques, Challenges, and Future Directions**", which is organized into the following five parts.

|[Collaborative FedRec](#Collaborative)|[Cross-domain FedRec](#cross-domain-fedrec)|[Multi-modal FedRec](#multi-modal-fedrec)|[LLM-based FedRec](#llm-based-fedrec)|[Dataset](#dataset)|
|--|--|--|--|--|

## 🔍Collaborative FedRec <a id = "Collaborative"></a>
### Ensuring interaction Privacy

|Title|Abbreviation|Year|Venue|Code|
|-----|------------|----|-----|----|
|[Federated Meta-Learning with Fast Convergence and Efficient Communication](https://arxiv.org/abs/1802.07876v2)|FCF|2019|arxiv||
|[Secure federated matrix factorization](https://ieeexplore.ieee.org/document/9162459)|FedMF|2021|IEEE Intelligent Systems||
| [FedRec: Federated Recommendation With Explicit Feedback](https://ieeexplore.ieee.org/document/9170754) |FedRec|2021| IEEE Intelligent Systems ||
| [FedRec++: Lossless Federated Recommendation with Explicit Feedback](https://ojs.aaai.org/index.php/AAAI/article/view/16546) |FedRec++|2021|AAAI|[![Github](https://img.shields.io/badge/Code-white?logo=codementor&labelColor=b31b1b)](https://csse.szu.edu.cn/staff/panwk/publications/FedRecPlusPlus/)|
| [Stronger Privacy for Federated Collaborative Filtering With Implicit Feedback](https://dl.acm.org/doi/10.1145/3460231.3474262) |SP-FCF|2021|RecSys||
| [FR-FMSS: Federated Recommendation via Fake Marks and Secret Sharing](https://dl.acm.org/doi/10.1145/3460231.3478855) |FR-FMSS|2021| RecSys |  |
| [Federated Neural Collaborative Filtering](https://www.sciencedirect.com/science/article/pii/S0950705122001812) |FedNCF|2022|KBS |  |
| [Fast-adapting and Privacy-preserving Federated Recommender System](https://link.springer.com/article/10.1007/s00778-021-00700-6) |DP-PrivRec|2022| VLDB |  |
| [HFSA: A Semi-Asynchronous Hierarchical Federated Recommendation System in Smart City](https://ieeexplore.ieee.org/document/10149002) |HFSA| 2023 |IOTJ |  |
| [Federated Unlearning for On-Device Recommendation](https://dl.acm.org/doi/10.1145/3539597.3570463) |FRU|2023| WSDM ||
|[Efficient federated item similarity model for privacy-preserving recommendation](https://doi.org/10.1016/j.ipm.2023.103470)|FedIS|2023|IP&M|[![Github](https://img.shields.io/github/stars/XuanangD/FedIS?style=flat)](https://github.com/XuanangD/FedIS)|
| [Marking the Pace: A Blockchain-Enhanced Privacy-Traceable Strategy for Federated Recommender Systems](https://ieeexplore.ieee.org/document/10308576)|LIBERATE|2024| IOTJ |  |
| [HN3S: A Federated AutoEncoder framework for Collaborative Filtering via Hybrid Negative Sampling and Secret Sharing](https://www.sciencedirect.com/science/article/abs/pii/S0306457323003175) | HN3S|2024|IP&M | [![Github](https://img.shields.io/github/stars/LukeZane118/HN3S?style=flat)](https://github.com/LukeZane118/HN3S) |
|[Ownership Verification for Federated Recommendation](https://dl.acm.org/doi/10.1145/3715320)|OVFR|2025|TOIS||
|[P4GCN: Vertical Federated Social Recommendation with Privacy-Preserving Two-Party Graph Convolution Network](https://arxiv.org/pdf/2410.13905)|P4GCN|2025|WWW||
|[Certified Unlearning for Federated Recommendation](https://dl.acm.org/doi/10.1145/3706419)|CFRU|2025|TOIS||
|[Privacy-Preserving Sequential Recommendation with Collaborative Confusion](https://dl.acm.org/doi/full/10.1145/3707204)|CLOUD|2025|TOIS||


### Handling model inconsistency
|Title|Abbreviation|Year|Venue|Code|
|-----|------------|----|-----|----|
| [Meta Matrix Factorization for Federated Rating Predictions](https://dl.acm.org/doi/abs/10.1145/3397271.3401081) |MetaMF| 2020| SIGIR |[![Github](https://img.shields.io/github/stars/TempSDU/MetaMF?style=flat)](https://github.com/TempSDU/MetaMF)|
| [FedFast: Going Beyond Average for Faster Training of Federated Recommender Systems](https://dl.acm.org/doi/10.1145/3394486.3403176) |FedFast|2020|KDD |  |
|[Personalized Federated Recommendation via Joint Representation Learning, User Clustering, and Model Adaptation](https://dl.acm.org/doi/abs/10.1145/3511808.3557668)|PerFedRec|2022|CIKM|[![Github](https://img.shields.io/github/stars/sichunluo/PerFedRec?style=flat)](https://github.com/sichunluo/PerFedRec)|
| [Dual Personalization on Federated Recommendation](https://www.ijcai.org/proceedings/2023/507) |PFedRec|2023 |IJCAI | [![Github](https://img.shields.io/github/stars/Zhangcx19/IJCAI-23-PFedRec?style=flat)](https://github.com/Zhangcx19/IJCAI-23-PFedRec) |
| [Fine-Grained Preference-Aware Personalized Federated POI Recommendation with Data Sparsity](https://dl.acm.org/doi/10.1145/3539618.3591688) |PrefFedPOI|2023| SIGIR | [![Github](https://img.shields.io/github/stars/Leavesy/PrefFedPOI?style=flat)](https://github.com/Leavesy/PrefFedPOI)|
| [Federated Recommendation with Additive Personalization](https://doi.org/10.48550/arXiv.2301.09109) | FedRAP|2024|ICLR |[![Github](https://img.shields.io/github/stars/mtics/FedRAP?style=flat)](https://github.com/mtics/FedRAP)  |
| [GPFedRec: Graph-Guided Personalization for Federated Recommendation](https://dl.acm.org/doi/10.1145/3637528.3671702) | GPFedRec|2024|KDD | [![Github](https://img.shields.io/github/stars/zhangcx19/gpfedrec?style=flat)](https://github.com/zhangcx19/gpfedrec) |
| [PerFedRec++: Enhancing Personalized Federated Recommendation with Self-Supervised Pre-Training](https://dl.acm.org/doi/abs/10.1145/3664927) |PerFedRec++|2024| ACM TIST |  |
|[Cluster-driven Personalized Federated Recommendation with Interest-aware Graph Convolution Network for Multimedia](https://doi.org/10.1145/3664647.3680788)|CPF-GCN|2024|MM||
|[Federated Recommender System Based on Diffusion Augmentation and Guided Denoising](https://dl.acm.org/doi/10.1145/3688570)|DGFedRS|2025|TOIS||


### Facilitating client participation
|Title|Abbreviation|Year|Venue|Code|
|-----|------------|----|-----|----|
| [Federated Multi-view Matrix Factorization for Personalized Recommendations](https://link.springer.com/chapter/10.1007/978-3-030-67661-2_20) |FED-MVMF|2020| ECML/PKDD |  |
| [Efficient-FedRec: Efficient Federated Learning Framework for Privacy-Preserving News Recommendation](https://aclanthology.org/2021.emnlp-main.223.pdf) |FedNewsRec|2021|EMNLP|[![Github](https://img.shields.io/github/stars/yjw1029/Efficient-FedRec?style=flat)](https://github.com/yjw1029/Efficient-FedRec) |
| [A Payload Optimization Method for Federated Recommender Systems](https://dl.acm.org/doi/abs/10.1145/3460231.3474257) |PO-FCF|2021|RecSys| |
| [Towards Fair Federated Recommendation Learning: Characterizing the Inter-Dependence of System and Data Heterogeneity](https://dl.acm.org/doi/10.1145/3523227.3546759) |RF$^2$|2022| RecSys | [![Github](https://img.shields.io/github/stars/facebookresearch/RF2?style=flat)](https://github.com/facebookresearch/RF2)|
| [LightFR: Lightweight Federated Recommendation with Privacy-preserving Matrix Factorization](https://dl.acm.org/doi/abs/10.1145/3578361) |LightFR |2022|TOIS | |
| [ReFRS: Resource-efficient Federated Recommender System for Dynamic and Diversified User Preferences](https://dl.acm.org/doi/abs/10.1145/3560486) | ReFRS|2023|TOIS |  |
|[No Prejudice! Fair Federated Graph Neural Networks for Personalized Recommendation](https://doi.org/10.1609/aaai.v38i10.28950)|F$^2$PGNN|2024|AAAI|[![Github](https://img.shields.io/github/stars/nimeshagrawal/F2PGNN-AAAI24?style=flat)](https://github.com/nimeshagrawal/F2PGNN-AAAI24)|
|[Towards Efficient Communication and Secure Federated Recommendation System via Low-rank Training](https://dl.acm.org/doi/abs/10.1145/3589334.3645702)|CoLR|2024|WWW|[![Github](https://img.shields.io/github/stars/NNHieu/CoLR-FedRec?style=flat)](https://github.com/NNHieu/CoLR-FedRec)|
| [When Federated Recommendation Meets Cold-Start Problem: Separating Item Attributes and User Interactions](https://dl.acm.org/doi/10.1145/3589334.3645525) |IFedRec|2024| WWW | [![Github](https://img.shields.io/github/stars/Zhangcx19/IFedRec?style=flat)](https://github.com/Zhangcx19/IFedRec) |
|[Hetefedrec: Federated Recommender Systems with Model Heterogeneity](https://ieeexplore.ieee.org/document/10598074)|HeteFedRec|2024|ICDE||
| [Hide Your Model: A Parameter Transmission-free Federated Recommender System](https://ieeexplore.ieee.org/document/10597708) |PTF-FedRec|2024| ICDE | [![Github](https://img.shields.io/github/stars/hi-weiyuan/PTF-FedRec?style=flat)](https://github.com/hi-weiyuan/PTF-FedRec)  |
| [Discrete Federated Multi-behavior Recommendation for Privacy-Preserving Heterogeneous One-Class Collaborative Filtering](https://dl.acm.org/doi/abs/10.1145/3652853) | DMFR|2024 |TOIS |  |
|[Personalized Federated Recommendation for Cold-Start Users via Adaptive Knowledge Fusion](https://openreview.net/forum?id=bhWngwuo74#discussion)|FR-CSU|2025|WWW||

### High-order interaction mending

|Title|Abbreviation|Year|Venue|Code|
|-----|------------|----|-----|----|
| [A Federated Graph Neural Network Framework for Privacy-preserving Personalization](https://www.nature.com/articles/s41467-022-30714-9#Sec8) | FedPerGNN|2022|Nature Communications | [![Github](https://img.shields.io/github/stars/wuch15/FedPerGNN?style=flat)](https://github.com/wuch15/FedPerGNN) |
| [Privacy-preserving graph convolution network for federated item recommendation](https://www.sciencedirect.com/science/article/pii/S000437022300142X) | P-GCN|2023|Artificial Intelligence |  |
| [Vertical Federated Graph Neural Network for Recommender System](https://proceedings.mlr.press/v202/mai23b.html)|VerFedGNN|2023 | ICML | [![Github](https://img.shields.io/github/stars/RishabhSri14/VerFedGNN?style=flat)](https://github.com/RishabhSri14/VerFedGNN)|
|[Semi-decentralized federated ego graph learning for recommendation](https://dl.acm.org/doi/10.1145/3543507.3583337)|SemiDFEGL|2023|WWW||
| [Towards Personalized Privacy: User-Governed Data Contribution for Federated Recommendation](https://dl.acm.org/doi/10.1145/3589334.3645690) |CDCGNNFed|2024 |WWW |  |
| [Federated Heterogeneous Graph Neural Network for Privacy-preserving Recommendation](https://dl.acm.org/doi/10.1145/3589334.3645693) |FedHGNN| 2024 |WWW | [![Github](https://img.shields.io/github/stars/BUPT-GAMMA/FedHGNN?style=flat)](https://github.com/BUPT-GAMMA/FedHGNN)|
| [GPFedRec: Graph-Guided Personalization for Federated Recommendation](https://dl.acm.org/doi/10.1145/3637528.3671702) | GPFedRec|2024|KDD | [![Github](https://img.shields.io/github/stars/zhangcx19/gpfedrec?style=flat)](https://github.com/zhangcx19/gpfedrec) |
|[Cluster-driven Personalized Federated Recommendation with Interest-aware Graph Convolution Network for Multimedia](https://doi.org/10.1145/3664647.3680788)|CPF-GCN|2024|MM||
|[P4GCN: Vertical Federated Social Recommendation with Privacy-Preserving Two-Party Graph Convolution Network](https://arxiv.org/pdf/2410.13905)|P4GCN|2025|WWW||
|[Defedgcn: Privacy-preserving decentralized federated gcn for recommender system](https://ieeexplore.ieee.org/abstract/document/10858404)|DeFedGCN|2025|TSC|[![Github](https://img.shields.io/github/stars/kqkq926/DeFedGCN?style=flat)](https://github.com/kqkq926/DeFedGCN)|


### Attack & Defense
- 🍎 Targeted attack
- 🍇 Untargeted attack
- 🍈 Inference attack


|Title|Abbreviation|Year|Venue|Code|
|-----|------------|----|-----|----|
|🍎 [Poisoning Deep Learning based Recommender Model in Federated Learning Scenarios](https://www.ijcai.org/proceedings/2022/306)  |A-ra/A-hum|2022| IJCAI | [![Github](https://img.shields.io/github/stars/rdz98/PoisonFedDLRS?style=flat)](https://github.com/rdz98/PoisonFedDLRS) |
|🍎 [FedRecAttack: Model Poisoning Attack to Federated Recommendation](https://ieeexplore.ieee.org/document/9835228)|FedRecAttack|2022| ICDE | [![Github](https://img.shields.io/github/stars/rdz98/FedRecAttack?style=flat)](https://github.com/rdz98/FedRecAttack) |
|🍎 [PipAttack: Poisoning Federated Recommender Systems for Manipulating Item Promotion](https://dl.acm.org/doi/abs/10.1145/3488560.3498386) |PipAttack|2022| WSDM |  |
|🍎 [Eyes on Federated Recommendation: Targeted Poisoning With Competition and Its Mitigation](https://ieeexplore.ieee.org/document/10739366) | StairClimbing & CrossEU |2024| TIFS ||
|🍎 [Poisoning Federated Recommender Systems with Fake Users](https://dl.acm.org/doi/10.1145/3589334.3645492) |PoisonFRS| 2024 |WWW |  |
|🍎 [Preventing the Popular Item Embedding Based Attack in Federated Recommendations](https://ieeexplore.ieee.org/document/10597721) |PIECK|2024| ICDE | [![Github](https://img.shields.io/github/stars/junzhang-zj/PIECK?style=flat)](https://github.com/junzhang-zj/PIECK) |
|🍎 [Poisoning Decentralized Collaborative Recommender System and Its Countermeasures](https://dl.acm.org/doi/10.1145/3626772.3657814)|PAMN|2024|SIGIR||
|🍎 [Revisit Targeted Model Poisoning on Federated Recommendation: Optimize via Multi-objective Transport](https://dl.acm.org/doi/10.1145/3626772.3657764) |HMTA|2024| SIGIR |  |
|🍎 [Hidattack: An effective and undetectable model poisoning attack to federated recommenders](https://ieeexplore.ieee.org/document/10816078)|HidAttack|2024|TKDE|[![Github](https://img.shields.io/github/stars/waqar-uestc/HidAttack?style=flat)](https://github.com/waqar-uestc/HidAttack/tree/main)|
| 🍇 [FedAttack: Effective and Covert Poisoning Attack on Federated Recommendation via Hard Sampling](https://dl.acm.org/doi/10.1145/3534678.3539119) |FedAttack|2022| KDD | [![Github](https://img.shields.io/github/stars/wuch15/FedAttack?style=flat)](https://github.com/wuch15/FedAttack) |
|🍇 [UA-FedRec: Untargeted Attack on Federated News Recommendation](https://dl.acm.org/doi/abs/10.1145/3580305.3599923)  |UA-FedRec| 2023|KDD | [![Github](https://img.shields.io/github/stars/yjw1029/UA-FedRec?style=flat)](https://github.com/yjw1029/UA-FedRec) |
|🍇 [Untargeted Attack against Federated Recommendation Systems via Poisonous Item Embeddings and the Defense](https://ojs.aaai.org/index.php/AAAI/article/view/25611)  |ClusterAttack & UNION|2023| AAAI | [![Github](https://img.shields.io/github/stars/yflyl613/FedRec?style=flat)](https://github.com/yflyl613/FedRec) |
|🍇 [Not One Less: Exploring Interplay between User Profiles and Items in Untargeted Attacks against Federated Recommendation](https://dl.acm.org/doi/10.1145/3658644.3670365)|FedRecAttack$^2$ & GuardCQ|2024|CCS||
|🍇 [Defending Federated Recommender Systems against Untargeted Attacks: A Contribution-Aware Robust Aggregation Scheme](https://dl.acm.org/doi/full/10.1145/3706112)|ConDA|2025|TKDD||
|🍈 [Interaction-level Membership Inference Attack Against Federated Recommender Systems](https://dl.acm.org/doi/10.1145/3543507.3583359) | IMIA|2023|WWW | |
|🍈 [Comprehensive Privacy Analysis on Federated Recommender System against Attribute Inference Attacks](https://ieeexplore.ieee.org/abstract/document/10184063) |(Zhang et al.)|2023|  TKDE |  |
|🍈 [User Consented Federated Recommender System Against Personalized Attribute Inference Attack](https://dl.acm.org/doi/abs/10.1145/3616855.3635830) |UC-FedRec|2024| WSDM | [![Github](https://img.shields.io/github/stars/HKUST-KnowComp/UC-FedRec?style=flat)](https://github.com/HKUST-KnowComp/UC-FedRec) |
|🍈 [Defending Against Membership Inference Attack for Counterfactual Federated Recommendation with Differentially Private Representation Learning](https://ieeexplore.ieee.org/document/10662889) |CIRDP|2024| TIFS |  |
|🍈 [Aegis: Post-Training Attribute Unlearning in Federated Recommender Systems against Attribute Inference Attacks](https://openreview.net/forum?id=OHtjMJABg0#discussion)|Aegis|2025|WWW||


## 🔍 Cross-domain FedRec <a id = "cross-domain-fedrec"></a>

|Title|Abbreviation|Year|Venue|Code|
|-----|------------|----|-----|----|
|[A Federated Multi-View Deep Learning Framework for Privacy-Preserving Recommendations](https://doi.org/10.48550/arXiv.2008.10808)|FL-MV-DSSM |2020|FTL-IJCAI||
| [FedCT: Federated Collaborative Transfer for Recommendation](https://dl.acm.org/doi/10.1145/3404835.3462825) |FedCT|2021| SIGIR |  |
|[FedCDR: Federated Cross-Domain Recommendation for Privacy-Preserving Rating Prediction](https://dl.acm.org/doi/10.1145/3511808.3557320)| FedCDR|2022|CIKM||
|[Differential Private Knowledge Transfer for Privacy-Preserving Cross-Domain Recommendation](https://dl.acm.org/doi/10.1145/3485447.3512192)|PriCDR|2022|WWW|[![Github](https://img.shields.io/github/stars/TiliaceaeSU/PriCDR?style=flat)](https://github.com/TiliaceaeSU/PriCDR)|
| [Federated Probabilistic Preference Distribution Modelling with Compactness Co-Clustering for Privacy-Preserving Multi-Domain Recommendation](https://www.ijcai.org/proceedings/2023/245) |FPPDM|2023| IJCAI |  |
|[Differentially Private Sparse Mapping for Privacy-Preserving Cross Domain Recommendation](https://dl.acm.org/doi/10.1145/3581783.3611924)|DPSMRec|2023|MM||
| [Win-Win: A Privacy-Preserving Federated Framework for Dual-Target Cross-Domain Recommendation](https://ojs.aaai.org/index.php/AAAI/article/view/25531) |P2FCDR|2023| AAAI | |
|[PPGenCDR: A Stable and Robust Framework for Privacy-Preserving Cross-Domain Recommendation](https://doi.org/10.48550/arXiv.2305.16163)|PPGenCDR|2023|AAAI|[![Github](https://img.shields.io/github/stars/XeniaLLL/PPGenCDR?style=flat)](https://github.com/XeniaLLL/PPGenCDR)|
| [ReFer: Retrieval-Enhanced Vertical Federated Recommendation for Full Set User Benefit](https://dl.acm.org/doi/10.1145/3626772.3657763) |ReFer|2024| SIGIR |  |
|[FedDCSR: Federated Cross-domain Sequential Recommendation via Disentangled Representation Learning](http://dx.doi.org/10.1137/1.9781611978032.62)|FedDCSR|2024|SDM|[![Github](https://img.shields.io/github/stars/orion-orion/FedDCSR?style=flat)](https://github.com/orion-orion/FedDCSR)|
|[FedHCDR: Federated Cross-Domain Recommendation with Hypergraph Signal Decoupling](https://link.springer.com/chapter/10.1007/978-3-031-70341-6_21)|FedHCDR|2024|ECML PKDD|[![Github](https://img.shields.io/github/stars/orion-orion/FedHCDR?style=flat)](https://github.com/orion-orion/FedHCDR)|
| [Privacy-preserving Cross-domain Recommendation with Federated Graph Learning](https://dl.acm.org/doi/10.1145/3653448) |PPCDR|2024| TOIS |  |
|[Prompt-enhanced Federated Content Representation Learning for Cross-domain Recommendation](https://dl.acm.org/doi/10.1145/3589334.3645337)|PFCR|2024|WWW|[![Github](https://img.shields.io/github/stars/Sapphire-star/PFCR?style=flat)](https://github.com/Sapphire-star/PFCR)|
| [FedCORE: Federated Learning for Cross-Organization Recommendation Ecosystem](https://ieeexplore.ieee.org/document/10443503) |FedCORE|2024| TKDE | [![Github](https://img.shields.io/github/stars/seek-up-well/FedCORE-code?style=flat)](https://github.com/seek-up-well/FedCORE-code) |
|[Federated Graph Learning for Cross-Domain Recommendation](https://arxiv.org/pdf/2410.08249v1)|FedGCDR|2024|NeurIPS| [![Github](https://img.shields.io/github/stars/LafinHana/FedGCDR?style=flat)](https://github.com/LafinHana/FedGCDR/tree/main)|
|[Privacy-Preserving Cross-Domain Sequential Recommendation](https://ieeexplore.ieee.org/abstract/document/10415824)|PriCDSR|2024|ICDM||
|[FedCSR: A Federated Framework for Multi-Platform Cross-Domain Sequential Recommendation with Dual Contrastive Learning](https://aclanthology.org/2025.coling-main.581.pdf)|FedCSR|2025|COLING|[![Github](https://img.shields.io/github/stars/zdy769243418/FedCSR-v1?style=flat)](https://github.com/zdy769243418/FedCSR-v1)|



## 🔍 Multi-modal FedRec <a id = "multi-modal-fedrec"></a>


|Title|Abbreviation|Year|Venue|Code|
|-----|------------|----|-----|----|
|[Recommendation Algorithm Based on Federated Multi-modal Learning](https://ieeexplore.ieee.org/document/10627177)|AMMFRS|2024|ICASSP Workshop||
| [Towards Resource-Efficient and Secure Federated Multimedia Recommendation](https://ieeexplore.ieee.org/document/10448131) |FedMMR|2024| ICASSP |  |
|[A privacy-preserving framework with multi-modal data for cross-domain recommendation](https://doi.org/10.1016/j.knosys.2024.112529)|P2M2-CDR|2024|KBS|[![Github](https://img.shields.io/github/stars/Lili1013/P2M2-CDR?style=flat)](https://github.com/Lili1013/P2M2-CDR)|
|[Personalized Item Representations in Federated Multimodal Recommendation](https://doi.org/10.48550/arXiv.2410.08478)|FedMR|2024|arxiv|[![Github](https://img.shields.io/badge/Code-white?logo=codementor&labelColor=b31b1b)](https://anonymous.4open.science/r/FedMR/)|


## 🔍 LLM-based FedRec <a id = "llm-based-fedrec"></a>
|Title|Abbreviation|Year|Venue|Code|
|-----|------------|----|-----|----|
|[Federated Adaptation for Foundation Model-based Recommendations](https://www.ijcai.org/proceedings/2024/0603.pdf)|FedPA|2024|IJCAI|[![Github](https://img.shields.io/github/stars/Zhangcx19/IJCAI-24-FedPA?style=flat)](https://github.com/Zhangcx19/IJCAI-24-FedPA)|
|[FELLAS: Enhancing Federated Sequential Recommendation with LLM as External Services](https://dl.acm.org/doi/10.1145/3709138)|FELLAS|2024|TOIS||
|[A Federated Framework for LLM-based Recommendation](https://doi.org/10.48550/arXiv.2402.09959)|PPLR|2025|NAACL Findings||
|[Multifaceted User Modeling in Recommendation: A Federated Foundation Models Approach](https://doi.org/10.48550/arXiv.2412.16969)|MRFF|2025|AAAI|[![Github](https://img.shields.io/github/stars/Zhangcx19/AAAI-25-MRFF?style=flat)](https://github.com/Zhangcx19/AAAI-25-MRFF)|

## 🔑Dataset <a id = "dataset"></a>

- A: Collaborative
- B: Cross-domain
- C: Multi-modal
- D: LLM-based

| Dataset Name | Domain |Scenario|
|---|---|---|
| [Amazon review](https://jmcauley.ucsd.edu/data/amazon/) | E-commerce | A/B/C/D |
| [MovieLens](https://grouplens.org/datasets/movielens/) | Movie | A/D |
| [Yelp](https://www.yelp.com/dataset) | E-commerce | A/B/D |
| [HetRec](https://grouplens.org/datasets/hetrec-2011/) | Book, Music, Movie | A |
| [Ciao](https://www.cse.msu.edu/~tangjili/datasetcode/truststudy.htm) | Movie | A |
| [Epinions](https://www.cse.msu.edu/~tangjili/datasetcode/truststudy.htm) | Relation-ship | A |
| [Steam](https://cseweb.ucsd.edu/~jmcauley/datasets.html#steam_data) | Game | A |
| [Yahoo](https://webscope.sandbox.yahoo.com/catalog.php?datatype=r) | Movie, Music | A |
| [MIND](https://msnews.github.io/) | News | A/D |
| [Adressa](https://reclab.idi.ntnu.no/dataset/) | News | A |
| [Taobao](https://tianchi.aliyun.com/dataset/649) | Behavior | A |
| [Last.FM](https://grouplens.org/datasets/hetrec-2011/) | Music | A |
| [Flixster](https://networkrepository.com/soc-flixster.php) | Relation-ship | A |
| [Gowalla](https://www.yongliu.org/datasets/) | Check-in | A |
| [Anime](https://www.kaggle.com/datasets/CooperUnion/anime-recommendations-database) | Video | A |
| [Douban](https://www.kaggle.com/datasets/fengzhujoey/douban-datasetratingreviewside-information) | Movie, Music, Book | A/B/D |
| [Online-Retail](https://www.kaggle.com/datasets/carrie1/ecommerce-data) | E-commerce | B |
| [NineRec](https://github.com/westlake-repl/NineRec) | General | A/B/C/D |
| [Foursquare](https://paperswithcode.com/dataset/foursquare) | Check-in | A/B |
| [Weeplaces](https://www.yongliu.org/datasets/) | Check-in | A |
| [ACM](https://www.aminer.cn/citation) | Citation | A |
| [DBLP](https://www.aminer.cn/citation) | Citation | A |
| [Tenrec](https://tenrec0.github.io/) | Video, Article | A/D |
| [KuaiSAR](https://kuaisar.github.io/) | Video | A/D |
| [XING](https://github.com/MilkaLichtblau/xing_dataset) | Job | A |
| [Pinterest](https://github.com/edervishaj/pinterest-recsys-dataset) | Image | A |
