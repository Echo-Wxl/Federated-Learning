# Federated-Learning

A collection of research papers,  tutorials , blogs and Frameworks on FL

## 1.Contents

1. [Contents](#1.Contents)

2. [ResearchPapers](#2.Papers)

   2.1 [Top-tier(ICML, NeurIPS, ICLR, CVPR, IJCAI, AAAI)](#2.1Top-tier)

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
   - [Non-IID](#Non-IID)
   
3. [Tutorials](#3.Tutorials )

   3.1 [book](#3.1book)

   3.2 [blogs](#3.2blogs)

   3.3 [slide](#3.3slide)

4. [Frameworks](#4.Frameworks)

5. [Company & Application](#5.Company&Application)

------

##  2.Papers

###  2.1Top-tier

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

- [Federated Optimization: Distributed Optimization Beyond the Datacenter](https://arxiv.org/pdf/1511.03575.pdf) NIPS 2016 workshop
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
* [FPGA-Based Hardware Accelerator of Homomorphic Encryption for Efficient Federated Learning](https://arxiv.org/abs/2007.10560) [IJCAI 2021 Workshop Best Student Paper]
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
- [Federated Learning via Posterior Avgeraging: A New Perspective and Practical Algorithms](https://openreview.net/forum?id=GFsU8a0sGB)
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
* [联邦学习算法综述，王健宗，孔令炜](http://www.infocomm-journal.com/bdr/CN/10.11959/j.issn.2096-0271.2020055)

####  VerticalFL

- ["Communication-Efficient Multimodal Split Learning for mmWave Received Power Prediction,"Yusuke Koda, Jihong Park, Mehdi Bennis, Koji Yamamoto, Takayuki Nishio, and Masahiro Morikura,  Mar. 2020.](https://arxiv.org/abs/2003.00645)
- ["Federated Hierarchical Hybrid Networks for Clickbait Detection,"Feng Liao, Hankz Hankui Zhuo, Xiaoling Huang, and Yu Zhang,  Jun. 2019.](https://arxiv.org/abs/1906.00638)
- [ "Private federated learning on vertically partitioned data via entity resolution and additively homomorphic encryption,"Stephen Hardy, Wilko Henecka, Hamish Ivey-Law, Richard Nock, Giorgio Patrini, Guillaume Smith, and Brian Thorne, Nov. 2017.](https://arxiv.org/abs/1711.10677)
- [ "FDML: A Collaborative Machine Learning Framework for Distributed Features," Yaochen Hu, Di Niu, Jianming Yang, and Shengping Zhou,May 2019.](https://arxiv.org/abs/1812.06415)
- [ "Learning Privately over Distributed Features: An ADMM Sharing Approach,"Yaochen Hu, Peng Liu, Linglong Kong, and Di Niu, Jul. 2019.](https://arxiv.org/abs/1907.07735)
- ["SplitFed: When Federated Learning Meets Split Learning,"Chandra Thapa, M. A. P. Chamikara, and Seyit Camtepe,  Apr. 2020.]( https://arxiv.org/abs/2004.12088v1)
- ["Privacy Enhanced Multimodal Neural Representations for Emotion Recognition,"Mimansa Jaiswal, and Emily Mower Provost, Oct. 2019.](https://arxiv.org/abs/1910.13212v1)
- ["Privacy-preserving Neural Representations of Text,"Maximin Coavoux, Shashi Narayan, and Shay B. Cohen,  Aug. 2018.](https://arxiv.org/abs/1808.09408)
- ["PrivyNet: A Flexible Framework for Privacy-Preserving Deep Neural Network Training,"Meng Li, Liangzhen Lai, Naveen Suda, Vikas Chandra, and David Z. Pan,  Sep. 2017.](https://arxiv.org/abs/1709.06161https://arxiv.org/abs/1709.06161)
- ["One Pixel Image and RF Signal Based Split Learning for mmWave Received Power Prediction," Yusuke Koda, Jihong Park, Mehdi Bennis, Koji Yamamoto, Takayuki Nishio, and Masahiro Morikura, Nov. 2019.](https://arxiv.org/abs/1911.01682)
- ["Communication-Efficient Multimodal Split Learning for mmWave Received Power Prediction," Yusuke Koda, Jihong Park, Mehdi Bennis, Koji Yamamoto, Takayuki Nishio, and Masahiro Morikura, Mar. 2020.](https://arxiv.org/abs/2003.00645)
- ["Optimization for Large-Scale Machine Learning with Distributed Features and Observations," Alexandros Nathan, and Diego Klabjan, Apr. 2017.](https://arxiv.org/abs/1610.10060)
- ["SecureBoost: A Lossless Federated Learning Framework," Kewei Cheng, Tao Fan, Yilun Jin, Yang Liu, Tianjian Chen, Qiang Yang, Jan. 2019.](https://arxiv.org/abs/1901.08755)
- ["Privacy-Preserving Backpropagation Neural Network Learning," Tingting Chen, Sheng Zhong, Oct. 2009.](https://cse.buffalo.edu/caeiae/documents/pdf/back-propagation-chen-zhong-2009.pdf)
- ["Split learning for health: Distributed deep learning without sharing raw patient data,"Praneeth Vepakomma, Otkrist Gupta, Tristan Swedish, and Ramesh Raskar,  Dec. 2018.](https://arxiv.org/abs/1812.0056)

####  Non-IID

- [The Non-IID Data Quagmire of Decentralized Machine Learning](https://arxiv.org/pdf/1910.00189.pdf);Kevin Hsieh， Amar Phanishayee， Onur Mutlu， Phillip B. Gibbons；Microsoft Research；PMLR 2020
- [Federated Learning with Non-IID Data](https://arxiv.org/pdf/1806.00582.pdf);Yue Zhao，Vikas Chanra；San Jose, CA；arXiv 2018
- [FedCD: Improving Performance in non-IID Federated Learning. 2020](https://arxiv.org/pdf/2006.09637.pdf)
- [Survey of Personalization Techniques for Federated Learning](https://arxiv.org/pdf/2003.08673) 
- [Data selection for federated learning with relevant and irrelevant data at clients](https://arxiv.org/pdf/2001.08300),  Tiffany Tuor, Shiqiang Wang, Bong Jun Ko, Changchang Liu, Kin K. Leung;  arXiv 2020
- [Three approaches for personalization with applications to federated learning](https://arxiv.org/pdf/2002.10619), Yishay Mansour, Mehryar Mohri, Jae Ro, Ananda Theertha Suresh, arXiv 2020
- [Life Long Learning: FedFMC: Sequential Efficient Federated Learning on Non-iid Data. 2020](https://arxiv.org/pdf/2006.10937.pdf)
- [Personalized Federated Learning with Moreau Envelopes. 2020](https://arxiv.org/pdf/2006.08848.pdf)
- [Proxy Experience Replay: Federated Distillation for Distributed Reinforcement Learning. 2020](https://arxiv.org/pdf/2005.06105.pdf)
- [Towards Flexible Device Participation in Federated Learning for Non-IID Data. 2020](https://arxiv.org/pdf/2006.06954.pdf)
- [NeurIPS 2020 submission: An Efficient Framework for Clustered Federated Learning](https://arxiv.org/pdf/2006.04088.pdf)
- [FedPD: A Federated Learning Framework with Optimal Rates and Adaptivity to Non-IID Data](https://arxiv.org/pdf/2005.11418.pdf)
- [Federated learning with hierarchical clustering of local updates to improve training on non-IID data](https://arxiv.org/pdf/2004.11791.pdf)
- [Federated Learning with Only Positive Labels](https://arxiv.org/pdf/2004.10342.pdf)
- [Adaptive Personalized Federated Learning](https://arxiv.org/pdf/2003.13461.pdf)
- [Personalized Federated Learning for Intelligent IoT Applications: A Cloud-Edge based Framework](https://arxiv.org/pdf/2002.10671.pdf)
- [Three Approaches for Personalization with Applications to Federated Learning](https://arxiv.org/pdf/2002.10619.pdf)
- [Personalized Federated Learning: A Meta-Learning Approach](https://arxiv.org/pdf/2002.07948.pdf)
- [Federated Learning with Personalization Layers](https://arxiv.org/pdf/1912.00818.pdf)
- [Federated Evaluation of On-device Personalization](https://arxiv.org/pdf/1910.10252.pdf)
- [Overcoming Forgetting in Federated Learning on Non-IID Data](https://arxiv.org/pdf/1910.07796.pdf)
- [Clustered Federated Learning: Model-Agnostic Distributed Multi-Task Optimization under Privacy Constraints](https://arxiv.org/pdf/1910.01991.pdf)
- [Improving Federated Learning Personalization via Model Agnostic Meta Learning](https://arxiv.org/pdf/1909.12488.pdf)
- [Client Adaptation improves Federated Learning with Simulated Non-IID Clients](https://arxiv.org/pdf/2007.04806.pdf)
- [Adaptive gradient-based meta-learning methods](https://arxiv.org/pdf/1906.02717)
- [Salvaging federated learning by local adaptation](https://arxiv.org/pdf/2002.04758)
- [Federated learning of a mixture of global and local models](https://arxiv.org/pdf/2002.05516)
- [Federated multi-task learning](https://arxiv.org/pdf/1705.10467)



##  3.Tutorials 

### 3.1book

- 杨强，刘洋，程勇，康焱，陈天健，于涵，《联邦学习》，电子工业出版社，2020年5月

### 3.2blogs

- [杨强，刘洋，陈天健，童咏昕，“联邦学习”，中国计算机学会通讯](https://mp.weixin.qq.com/s?__biz=MjM5MTY5ODE4OQ==&mid=2651453786&idx=1&sn=1f189cbb8ff159428d65e100fdb5dc77&scene=21)
- [中国信息通信研究院《隐私保护计算与合规应用研究报告 (2021年)](http://www.caict.ac.cn/kxyj/qwfb/ztbg/202104/P020210401408574284747.pdf)
- [Federated Learning Comic](https://federated.withgoogle.com/)
- [Federated Learning: Collaborative Machine Learning without Centralized Training Data](http://ai.googleblog.com/2017/04/federated-learning-collaborative.html)
- [An Introduction to Federated Learning](http://vision.cloudera.com/an-introduction-to-federated-learning/)
- [Online Comic from Google AI on Federated Learning](https://federated.withgoogle.com/)
- [GDPR, Data Shotrage and AI , AAAI-19](https://aaai.org/Conferences/AAAI-19/invited-speakers/#yang)

### 3.3slide

- [《隐私保护机器学习》slide](./src/ppt/README.md)
- [面向隐私安全保密的联邦学习和迁移学习](./src/ppt/面向隐私安全保密的联邦学习与迁移学习.pdf)
- [联邦学习的研究和应用](./src/ppt/联邦学习的研究和应用.pdf)
- [用非对称联邦保护客户隐私](./src/ppt/用非对称联邦保护客户隐私.pdf)
- [云原生联邦学习的开源框架](./src/ppt/云原生联邦学习的开源框架.pdf)
- [联邦学习与安全多方计算](./src/ppt/联邦学习与安全多方计算.pdf)
- [FATE：联邦学习技术落地与应用](./src/ppt/FATE：联邦学习技术落地与应用.pdf)

## 4.Frameworks

* [PySyft](https://github.com/OpenMined/PySyft)
* [Tensorflow Federated](https://www.tensorflow.org/federated)
* [FATE](https://github.com/FederatedAI/FATE); WeBank
* [FedLearner](https://github.com/bytedance/fedlearner) ByteDance
* [PaddleFL](https://github.com/PaddlePaddle/PaddleFL); Baidu 
* [LEAF: A Benchmark for Federated Settings ](https://leaf.cmu.edu/)
* [FedML:A Research Library and Benchmark for Federated Machine Learning](https://github.com/FedML-AI/FedML)
* [XayNe:Open source framework for federated learning in Rust]( https://xaynet.webflow.io/)
* [PyTorch Federated Learning](https://github.com/shaoxiongji/federated-learning)
* [[FedMA](https://github.com/IBM/federated-learning-lib)](https://github.com/IBM/federated-learning-lib); IBM
* [federated](https://github.com/google-research/federated);Google Research
* [Flower](https://flower.dev/)

##  5.Company&Application

|     公司     |                          产品&地址                           |                    开源地址                    |
| :----------: | :----------------------------------------------------------: | :--------------------------------------------: |
|   微众银行   |           [联邦学习FATE](https://fate.fedai.org/)            |      https://github.com/FederatedAI/FATE       |
|   蚂蚁金服   | [摩斯多方安全计算平台](https://antchain.antgroup.com/products/morse) |                       -                        |
|     百度     | [联邦计算](https://anquan.baidu.com/product/federatedcomputing) |    https://gitee.com/paddlepaddle/PaddleFL     |
| 百度安全部门 | [MesaTEE 安全计算平台](https://anquan.baidu.com/product/mesatee) |  https://github.com/apache/incubator-teaclave  |
|   京东数科   |             [Fedlearn](https://www.jdcloud.com/)             |                       -                        |
|   洞见智慧   |           [Insightone](https://www.insightone.cn/)           |                       -                        |
|   华控清交   |      [PrivPy 多方安全计算平台](https://www.tsingj.com/)      |                       -                        |
|   字节跳动   |    [Fedlearner](https://github.com/bytedance/fedlearner)     |    https://github.com/bytedance/fedlearner     |
|   富数科技   |                [FMPC](https://www.fudata.cn/)                |                       -                        |
|    矩阵元    |  [rosetta](https://www.matrixelements.com/product/rosetta)   | https://github.com/LatticeX-Foundation/Rosetta |
|   数犊科技   |  [platone](https://www.matrixelements.com/product/platone)   |                       -                        |
|   同盾科技   |                   https://www.tongdun.cn/                    |                       -                        |
|   致星科技   |            [星云Clustar](https://www.clustar.ai/)            |                       -                        |



