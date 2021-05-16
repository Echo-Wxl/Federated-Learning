# Federated-Learning

A collection of research papers,  tutorials , blogs and Frameworks on FL

## 1.Contents

1. [Contents](#1.Contents)

2. [ResearchPapers](2.ResearchPapers)

   2.1 [Top-tier(ICML, NeurIPS, ICLR, CVPR, IJCAI, AAAI)](#2.1Top-tier(ICML, NeurIPS, ICLR, CVPR, IJCAI, AAAI))

   - [ICML2020](#ICML2020)
   - [ICML2019](#ICML2019)
   - [NeurIPS2020](#NeurIPS2020)
   - [NeurIPS2016-2019](#NeurIPS2016-2019)
   - [AAAI2021](#AAAI2021)
   - [AAAI2020](#AAAI2020)
   - [IJCAI2021](#IJCAI2021)
   - [IJCAI2020](#IJCAI2020)
   - [ICLR2021](#ICLR2021)
   - [KDD2020](#KDD2020)

   2.2 [ByResearchArea](#2.2ByResearchArea)

   - [Survey](#Survey)
   - [VerticalFL](#VerticalFL)
   - [HorizontalFL](#HorizontalFL)

3. [Tutorials](#3.Tutorials )

   3.1 [book](#3.1book)

   3.2 [blogs](#3.2blogs)

   3.3 [ppt](#3.3ppt)

4. [Frameworks](#4.Frameworks)

5. [Company & Application](#5.Company&Application)

------

##  2.ResearchPapers

###  2.1Top-tier(ICML, NeurIPS, ICLR, CVPR, IJCAI, AAAI)

####  ICML2020

- [Federated Learning with Only Positive Labels](https://arxiv.org/pdf/2004.10342.pdf);Google Research;2020;label deficiency in multi-class classification
- [SCAFFOLD: Stochastic Controlled Averaging for Federated Learning](https://arxiv.org/abs/1910.06378);Google Research;2020;non-iid
- [FedBoost: A Communication-Efficient Algorithm for Federated Learning](https://proceedings.icml.cc/static/paper_files/icml/2020/5967-Paper.pdf);NYU & Google Research;2020;communication cost
- [FetchSGD: Communication-Efficient Federated Learning with Sketching](https://arxiv.org/abs/2007.07682);UC Berkeley;2020;communication cost
- [From Local SGD to Local Fixed-Point Methods for Federated Learning](https://arxiv.org/pdf/2004.01442.pdf);KAUST;2020;communication cost

####  ICML2019

- [Analyzing Federated Learning through an Adversarial Lens](http://proceedings.mlr.press/v97/bhagoji19a/bhagoji19a.pdf)
- [Bayesian Nonparametric Federated Learning of Neural Networks](http://proceedings.mlr.press/v97/yurochkin19a/yurochkin19a.pdf)
- [Agnostic Federated Learning](http://proceedings.mlr.press/v97/mohri19a/mohri19a.pdf)

####  NeurIPS2020

* [Personalized Federated Learning with Moreau Envelopes](https://arxiv.org/abs/2006.08848)
* [Lower Bounds and Optimal Algorithms for Personalized Federated Learning](https://papers.nips.cc/paper/2020/file/187acf7982f3c169b3075132380986e4-Paper.pdf) [KAUST]
* [Personalized Federated Learning with Theoretical Guarantees: A Model-Agnostic Meta-Learning Approach](https://papers.nips.cc/paper/2020/file/24389bfe4fe2eba8bf9aa9203a44cdad-Paper.pdf) [MIT]
* [Federated Principal Component Analysis](https://papers.nips.cc/paper/2020/file/47a658229eb2368a99f1d032c8848542-Paper.pdf) [Cambridge]
* [FedSplit: an algorithmic framework for fast federated optimization](https://papers.nips.cc/paper/2020/file/4ebd440d99504722d80de606ea8507da-Paper.pdf) [Berkeley]
* [Minibatch vs Local SGD for Heterogeneous Distributed Learning](https://papers.nips.cc/paper/2020/file/45713f6ff2041d3fdfae927b82488db8-Paper.pdf) [Toyota]
* [Distributed Training with Heterogeneous Data: Bridging Median- and Mean-Based Algorithms](https://papers.nips.cc/paper/2020/file/f629ed9325990b10543ab5946c1362fb-Paper.pdf)
* [Throughput-Optimal Topology Design for Cross-Silo Federated Learning](https://papers.nips.cc/paper/2020/file/e29b722e35040b88678e25a1ec032a21-Paper.pdf)
* [Distributed Distillation for On-Device Learning ](https://papers.nips.cc/paper/2020/file/fef6f971605336724b5e6c0c12dc2534-Paper.pdf) [Stanford]
* [Ensemble Distillation for Robust Model Fusion in Federated Learning ](https://papers.nips.cc/paper/2020/file/18df51b97ccd68128e994804f3eccc87-Paper.pdf)
* [Group Knowledge Transfer: Federated Learning of Large CNNs at the Edge](https://papers.nips.cc/paper/2020/file/a1d4c20b182ad7137ab3606f0e3fc8a4-Paper.pdf) [USC]
* [Federated Accelerated Stochastic Gradient Descent](https://papers.nips.cc/paper/2020/file/39d0a8908fbe6c18039ea8227f827023-Paper.pdf) [[Github]](https://github.com/hongliny/FedAc-NeurIPS20) [Stanford]
* [Distributionally Robust Federated Averaging](https://papers.nips.cc/paper/2020/file/ac450d10e166657ec8f93a1b65ca1b14-Paper.pdf)
* [An Efficient Framework for Clustered Federated Learning](https://papers.nips.cc/paper/2020/file/e32cc80bf07915058ce90722ee17bb71-Paper.pdf) [Berkeley]
* [Robust Federated Learning: The Case of Affine Distribution Shifts](https://papers.nips.cc/paper/2020/file/f5e536083a438cec5b64a4954abc17f1-Paper.pdf) [MIT]
* [Tackling the Objective Inconsistency Problem in Heterogeneous Federated Optimization](https://papers.nips.cc/paper/2020/file/564127c03caab942e503ee6f810f54fd-Paper.pdf) [CMU]
* [Federated Bayesian Optimization via Thompson Sampling](https://papers.nips.cc/paper/2020/file/6dfe08eda761bd321f8a9b239f6f4ec3-Paper.pdf) [NUS] [MIT]
* [Distributed Newton Can Communicate Less and Resist Byzantine Workers](https://arxiv.org/pdf/2006.08737.pdf) [Berkeley]
* [Byzantine Resilient Distributed Multi-Task Learning](https://papers.nips.cc/paper/2020/file/d37eb50d868361ea729bb4147eb3c1d8-Paper.pdf)
* [A Scalable Approach for Privacy-Preserving Collaborative Machine Learning](https://papers.nips.cc/paper/2020/file/5bf8aaef51c6e0d363cbe554acaf3f20-Paper.pdf) [USC]
* [Inverting Gradients - How easy is it to break privacy in federated learning?](https://papers.nips.cc/paper/2020/file/c4ede56bbd98819ae6112b20ac6bf145-Paper.pdf)
* [Attack of the Tails: Yes, You Really Can Backdoor Federated Learning](https://papers.nips.cc/paper/2020/file/b8ffa41d4e492f0fad2f13e29e1762eb-Paper.pdf)
* [Election Coding for Distributed Learning: Protecting SignSGD against Byzantine Attacks](https://papers.nips.cc/paper/2020/file/a7f0d2b95c60161b3f3c82f764b1d1c9-Paper.pdf)
* [Differentially-Private Federated Linear Bandits](http://web.mit.edu/dubeya/www/files/dp_linucb_20.pdf) [MIT]

#### NeurIPS2016-2019

- [Federated Optimization: Distributed Optimization Beyond the Datacenter]((https://arxiv.org/pdf/1511.03575.pdf)) NIPS 2016 workshop
- [Practical Secure Aggregation for Federated Learning on User-Held Data](https://arxiv.org/pdf/1611.04482.pdf) NIPS 2016 workshop
- [Differentially Private Federated Learning: A Client Level Perspective](https://arxiv.org/pdf/1712.07557.pdf) NIPS 2017 Workshop
- [Federated Multi-Task Learning](https://papers.nips.cc/paper/2017/hash/6211080fa89981f66b1a0c9d55c61d0f-Abstract.html) NIPS 2017
- [Deep Leakage from Gradients](https://papers.nips.cc/paper/9617-deep-leakage-from-gradients.pdf) NIPS 2019

####  AAAI2021

* [Federated Multi-Armed Bandits](https://arxiv.org/abs/2101.12204)
* [Curse or Redemption? How Data Heterogeneity Affects the Robustness of Federated Learning](https://www.aaai.org/AAAI21Papers/AAAI-8990.ZawadS.pdf)
* [Provably Secure Federated Learning against Malicious Clients](https://arxiv.org/pdf/2102.01854)
* [On the Convergence of Communication-Efficient Local SGD for Federated Learning](https://www.aaai.org/AAAI21Papers/AAAI-3649.GaoH.pdf)
* [Secure Bilevel Asynchronous Vertical Federated Learning with Backward Updating](https://arxiv.org/pdf/2103.00958)
* [Communication-Aware Collaborative Learning](https://arxiv.org/abs/2012.10569)
* [Peer Collaborative Learning for Online Knowledge Distillation](https://arxiv.org/abs/2006.04147)
* [A Communication Efficient Collaborative Learning Framework for Distributed Features](https://arxiv.org/abs/1912.11187)
* [Defending Against Backdoors in Federated Learning with Robust Learning Rate](https://arxiv.org/pdf/2007.03767.pdf)
* [FLAME: Differentially Private Federated Learning in the Shuffle Model](https://arxiv.org/abs/2009.08063)
* [Toward Understanding the Influence of Individual Clients in Federated Learning](https://arxiv.org/abs/2012.10936)
* [Personalized Cross-Silo Federated Learning on Non-IID Data](https://arxiv.org/abs/2007.03797)
* [Model-sharing Games: Analyzing Federated Learning Under Voluntary Participation](https://arxiv.org/abs/2010.00753)
* [Federated Block Coordinate Descent Scheme for Learning Global and Personalized Models](https://arxiv.org/abs/2012.13900)
* [Addressing Class Imbalance in Federated Learning](https://arxiv.org/abs/2008.06217)

#### AAAI2020

- [Federated Learning for Vision-­‐and-­‐Language Grounding Problems](https://ojs.aaai.org/index.php/AAAI/article/view/6824/6678);2020
- [Federated Latent Dirichlet Allocation: A Local Differential Privacy Based Framework](https://ojs.aaai.org/index.php/AAAI/article/download/6096/5952);2020
- [Federated Patient Hashing](https://ojs.aaai.org/index.php/AAAI/article/download/6121/5977);2020
- [Robust Federated Learning via Collaborative Machine Teaching](https://ojs.aaai.org/index.php/AAAI/article/download/5826/5682);2020
- [Practical Federated Gradient Boosting Decision Trees](https://ojs.aaai.org/index.php/AAAI/article/download/5895/5751);2020

####  IJCAI2021

* [Collaborative Fairness in Federated Learning](https://arxiv.org/abs/2008.12161) [IJCAI 2021 Workshop Best Paper] 
* [FPGA-Based Hardware Accelerator of Homomorphic Encryption for Efficient Federated Learning](FPGA-Based Hardware Accelerator of Homomorphic Encryption for Efficient Federated Learning) [IJCAI 2021 Workshop Best Student Paper]
* [Federated Learning with Diversified Preference for Humor Recognition](https://arxiv.org/abs/2012.01675) [IJCAI 2021 Workshop Best Application Paper]
* [Heterogeneous Data-Aware Federated Learning](https://arxiv.org/abs/2011.06393) [IJCAI 2021 Workshop]
* [Privacy-Preserving Technology to Help Millions of People: Federated Prediction Model for Stroke Prevention](https://arxiv.org/abs/2006.10517) [IJCAI 2021 Workshop]
* [FedMVT: Semi-supervised Vertical Federated Learning with MultiView Training](https://arxiv.org/abs/2008.10838) [IJCAI 2021 Workshop]
* [FOCUS: Dealing with Label Quality Disparity in Federated Learning](https://arxiv.org/abs/2001.11359) [IJCAI 2021 Workshop]
* [Fed-Focal Loss for imbalanced data classification in Federated Learning](https://arxiv.org/abs/2011.06283) [IJCAI 2021 Workshop]
* [Threats to Federated Learning: A Survey](https://arxiv.org/abs/2003.02133) [IJCAI 2021 Workshop]
* [Asymmetrical Vertical Federated Learning](https://arxiv.org/abs/2004.07427) [IJCAI 2021 Workshop]
* [Federated Learning System without Model Sharing through Integration of Dimensional Reduced Data Representations](https://arxiv.org/abs/2011.06803) [IJCAI 2021 Workshop]
* [Achieving Differential Privacy in Vertically Partitioned Multiparty Learning](https://arxiv.org/abs/1911.04587) [IJCAI 2021 Workshop]
* [Privacy Threats Against Federated Matrix Factorization](https://arxiv.org/abs/2007.01587) [IJCAI 2021 Workshop]
* [TF-SProD: Time Fading based Sensitive Pattern Hiding in Progressive Data](http://fl-ijcai20.federated-learning.org/FL-IJCAI20_paper_17.pdf)  [IJCAI 2021 Workshop]

#### IJCAI2020

- [Federated Meta-Learning for Fraudulent Credit Card Detection](https://www.ijcai.org/Proceedings/2020/0642.pdf)
- [A Multi-player Game for Studying Federated Learning Incentive Schemes](https://www.ijcai.org/Proceedings/2020/0769.pdf)

#### ICLR2021

- [Federated Learning Based on Dynamic Regularization](https://openreview.net/forum?id=B7v4QMR6Z9w)
- [Adaptive Federated Optimization](https://openreview.net/forum?id=LkFG3lB13U5)
- [Federated Learning via Posterior Averaging: A New Perspective and Practical Algorithms](https://openreview.net/forum?id=GFsU8a0sGB)
- [Achieving Linear Speedup with Partial Worker Participation in Non-IID Federated Learning ](https://openreview.net/forum?id=jDdzh5ul-d)
- [Federated Semi-Supervised Learning with Inter-Client Consistency & Disjoint Learning](https://openreview.net/forum?id=ce6CFXBh30h)
- [FedBN: Federated Learning on Non-IID Features via Local Batch Normalization](https://openreview.net/forum?id=6YEQUn0QICG)
- [FedBE: Making Bayesian Model Ensemble Applicable to Federated Learning](https://openreview.net/forum?id=dgtpE6gKjHn)
- [FedMix: Approximation of Mixup under Mean Augmented Federated Learning ](https://openreview.net/forum?id=Ogga20D2HO-)
- [HeteroFL: Computation and Communication Efficient Federated Learning for Heterogeneous Clients](https://openreview.net/forum?id=TNkPBBYFkXg)
- [Personalized Federated Learning with First Order Model Optimization](https://openreview.net/forum?id=ehJqJQk9cw)

#### KDD2020

* [FedFast: Going Beyond Average for Faster Training of Federated Recommender Systems](https://dl.acm.org/doi/abs/10.1145/3394486.3403176)
* [Federated Doubly Stochastic Kernel Learning for Vertically Partitioned Data](https://arxiv.org/pdf/2008.06197)
* [FedCD: Improving Performance in non-IID Federated Learning](https://arxiv.org/pdf/2006.09637) [KDD20 Workshop]
* [Resource-Constrained Federated Learning with Heterogeneous Labels and Models](https://arxiv.org/pdf/2011.03206) [KDD2020 Workshop]

###  2.2ByResearchArea

####  Survey

* [Federated Machine Learning: Concept and Applications](https://dl.acm.org/citation.cfm?id=3298981)
* [Federated Learning: Challenges, Methods, and Future Directions](https://arxiv.org/abs/1908.07873)
* [Advances and Open Problems in Federated Learning](https://arxiv.org/abs/1912.04977)
* [IBM Federated Learning: an Enterprise Framework White Paper V0.1](https://arxiv.org/abs/2007.10987)
* [Federated Learning White Paper V1.0](https://arxiv.org/pdf/2007.10987)
* [Federated Learning Systems: Vision, Hype and Reality for Data Privacy and Protection](https://arxiv.org/abs/1907.09693)
* [Survey of Personalization Techniques for Federated Learning. 2020-03-19](https://arxiv.org/pdf/2003.08673.pdf)
* [Federated Learning in Mobile Edge Networks: A Comprehensive Survey ](https://arxiv.org/abs/1909.11875)
* [Threats to Federated Learning: A Survey](https://arxiv.org/pdf/2003.02133.pdf)
* [An Introduction to Communication Efficient Edge Machine Learning](https://arxiv.org/pdf/1912.01554.pdf)
* [Federated Learning for Wireless Communications: Motivation, Opportunities and Challenges](https://arxiv.org/abs/1908.06847)
* [A Review of Applications in Federated Learning](https://www.sciencedirect.com/science/article/abs/pii/S0360835220305532)
* [A Survey on Federated Learning Systems: Vision, Hype and Reality for Data Privacy and Protection](https://arxiv.org/pdf/1907.09693.pdf)
* [Federated Learning for 6G Communications: Challenges, Methods, and Future Directions](https://arxiv.org/pdf/2006.02931.pdf)
* [Federated Learning for Wireless Communications: Motivation, Opportunities and Challenges](https://arxiv.org/abs/1908.06847)

####  VerticalFL

####  HorizontalFL

##  3.Tutorials 

### 3.1book

- 杨强，刘洋，程勇，康焱，陈天健，于涵，《联邦学习》，电子工业出版社，2020年5月

### 3.2blogs

- [杨强，刘洋，陈天健，童咏昕，“联邦学习”，中国计算机学会通讯](https://mp.weixin.qq.com/s?__biz=MjM5MTY5ODE4OQ==&mid=2651453786&idx=1&sn=1f189cbb8ff159428d65e100fdb5dc77&scene=21)
- [中国信息通信研究院《隐私保护计算与合规应用研究报告 (2021年)](http://www.caict.ac.cn/kxyj/qwfb/ztbg/202104/P020210401408574284747.pdf)

### 3.3ppt

- [ADL115《隐私保护机器学习》ppt](./src/ppt/README.md)

## 4.Frameworks

* [PySyft](https://github.com/OpenMined/PySyft)
* [Tensorflow Federated](https://www.tensorflow.org/federated)
* [FATE](https://github.com/FederatedAI/FATE); WeBank
* [FedLearner](https://github.com/bytedance/fedlearner) ByteDance
* [PaddleFL](https://github.com/PaddlePaddle/PaddleFL); Baidu 
* [LEAF](https://leaf.cmu.edu/)
* [FedML:A Research Library and Benchmark for Federated Machine Learning](https://github.com/FedML-AI/FedML)
* [XayNe:Open source framework for federated learning in Rust]( https://xaynet.webflow.io/)
* [PyTorch Federated Learning](https://github.com/shaoxiongji/federated-learning)
* [[FedMA](https://github.com/IBM/federated-learning-lib)](https://github.com/IBM/federated-learning-lib); IBM
* [federated](https://github.com/google-research/federated);Google Research
* [Flower](https://flower.dev/)

##  5.Company&Application





