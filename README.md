

# Awesome Machine Learning for Combinatorial Optimization Resources
We would like to maintain a list of resources that utilize machine learning technologies to solve combinatorial optimization problems.

We mark work contributed by [Thinklab](http://thinklab.sjtu.edu.cn) with ⭐.

*Maintained by members in SJTU-Thinklab: Chang Liu, Runzhong Wang, Jiayi Zhang, Zelin Zhao, Haoyu Geng, Tianzhe Wang, Wenxuan Guo, Wenjie Wu, Nianzu Yang, Ziao Guo, Yang Li, Hao Xiong and Junchi Yan. We also thank [all contributers from the community](https://github.com/Thinklab-SJTU/awesome-ml4co/graphs/contributors)!*

*We are looking for post-docs interested in machine learning especially for learning combinatorial solvers, dynamic graphs, and reinforcement learning. Please send your up-to-date resume via yanjunchi AT sjtu.edu.cn.*

## [Content](#content)

<table>
<tr><td colspan="2"><a href="#survey-papers">1. Survey</a></td></tr>
<tr><td colspan="2"><a href="#problems">2. Problems</a></td></tr> 
<tr>
	<td>&emsp;<a href=#graph-matching>2.1 Graph Matching (GM)</a></td>
	<td>&emsp;<a href=#quadratic-assignment-problem>2.2 Quadratic Assignment Problem (QAP)</a></td>
</tr>
<tr>
	<td>&emsp;<a href=#travelling-salesman-problem>2.3 Travelling Salesman Problem (TSP)</a></td>
	<td>&emsp;<a href=#portfolio-optimization>2.4 Portfolio Optimization (PortOpt)</a></td>
</tr>
<tr>
	<td>&emsp;<a href=#maximal-cut>2.5 Maximal Cut</a></td>
	<td>&emsp;<a href=#vehicle-routing-problem>2.6 Vehicle Routing Problem (VRP)</a></td>
</tr>
<tr>
	<td>&emsp;<a href=#job-shop-scheduling-problem>2.7 Job Shop Scheduling Problem (JSSP)</a></td>
	<td>&emsp;<a href=#maximum-independent-set>2.8 Maximum Independent Set</a></td>
</tr>
</table>

## Macro Trajectory Generation

+ **The TimeGeo Modeling Framework for Urban Mobility without Travel Surveys.** [paper](https://www.pnas.org/doi/abs/10.1073/pnas.1524261113)
    
   *Shan Jiang, Yingxiang Yang, Siddharth Gupta, et al.* PNAS, 2016.

+ **Synthesizing Plausible Privacy-Preserving Location Traces.** [paper](https://ieeexplore.ieee.org/abstract/document/7546522/)

   *Bindschaedler V, Shokri R.* IEEE Symposium on Security and Privacy (SP), 2016.

+ **SeqGAN: Sequence Generative Adversarial Nets with Policy Gradient.** [paper](https://ojs.aaai.org/index.php/AAAI/article/view/10804)

   *Yu L, Zhang W, Wang J, et al.* AAAI, 2017.

+ **A Generative Model of Urban Activities from Cellular Data.** [paper](https://ieeexplore.ieee.org/abstract/document/7932990/)

   *Yin M, Sheehan M, Feygin S, et al.* IEEE Transactions on Intelligent Transportation Systems, 2017.

+ **Mobility Knowledge Discovery to Generate Activity Pattern Trajectories.** [paper](https://ieeexplore.ieee.org/abstract/document/8317737)

   *Allahviranloo M, De Castaing L C, Rehmann J.* International Conference on Intelligent Transportation Systems (ITSC), 2017.

+ **A Non-Parametric Generative Model for Human Trajectories.** [paper](https://www.researchgate.net/profile/Kun-Ouyang/publication/326204971_A_Non-Parametric_Generative_Model_for_Human_Trajectories/links/5e3cdd49299bf1cdb914b1ef/A-Non-Parametric-Generative-Model-for-Human-Trajectories.pdf)

   *Ouyang K, Shokri R, Rosenblum D S, et al.* IJCAI, 2018.

+ **trajGANs: Using Generative Adversarial Networks for Geo-privacy Protection of Trajectory Data.** [paper](https://ptal-io.github.io/lopas2018/papers/LoPaS2018_Liu.pdf)

   *Liu X, Chen H, Andris C.* Location Privacy and Security Workshop, 2018.

+ **Data-driven Generation of Spatio-temporal Routines in Human Mobility.** [paper](https://link.springer.com/article/10.1007/s10618-017-0548-4)

   *Pappalardo L, Simini F.* Data Mining and Knowledge Discovery, 2018.

+ **Generative Models for Simulating Mobility Trajectories.** [paper](https://arxiv.org/abs/1811.12801)

   *Kulkarni V, Tagasovska N, Vatter T, et al.* 2018.

+ **Differentially Private and Utility Preserving Publication of Trajectory Data.** [paper]()

   *Gursoy M E, Liu L, Truex S, et al.* IEEE Transactions on Mobile Computing, 2018.

+ **A Variational Autoencoder Based Generative Model of Urban Human Mobility.** [paper](https://ieeexplore.ieee.org/abstract/document/8695407/)

   *Huang D, Song X, Fan Z, et al.* IEEE Conference on Multimedia Information Processing and Retrieval (MIPR), 2019.

+ **Generating Human Mobility Route Based on Generative Adversarial Network.** [paper](https://ieeexplore.ieee.org/abstract/document/8860038/)

   *Song H Y, Baek M S, Sung M.* Federated Conference on Computer Science and Information Systems (FedCSIS), 2019.

+ **Human Mobility Simulator for Smart Applications.** [paper](https://ieeexplore.ieee.org/abstract/document/8958668/)
   
   *De Paola A, Giammanco A, Re G L, et al.* International Symposium on Distributed Simulation and Real Time Applications (DS-RT), 2019.

+ **TGM: A Generative Mechanism for Publishing Trajectories with Differential Privacy.** [paper](https://ieeexplore.ieee.org/abstract/document/8848444)

   *Ghane S, Kulik L, Ramamohanarao K.* IEEE Internet of Things Journal, 2019.

+ **What is the Human Mobility in a New City: Transfer Mobility Knowledge Across Cities.** [paper](https://dl.acm.org/doi/abs/10.1145/3366423.3380210)

   *He T, Bao J, Li R, et al.* WWW, 2020.

+ **Learning to Simulate Human Mobility.** [paper](https://dl.acm.org/doi/abs/10.1145/3394486.3412862)
    
   *Feng J, Yang Z, Xu F, et al.* KDD, 2020.

+ **TraG: A Trajectory Generation Technique for Simulating Urban Crowd Mobility.** [paper](https://ieeexplore.ieee.org/abstract/document/9016086/)

   *Kang X, Liu L, Zhao D, et al.*  IEEE Transactions on Industrial Informatics, 2020.

+ **Learning to Simulate on Sparse Trajectory Data.** [paper](https://link.springer.com/chapter/10.1007/978-3-030-67667-4_32)
    
  *Wei H, Chen C, Liu C, et al.* ECML-PKDD, 2020.

+ **LSTM-TrajGAN: A Deep Learning Approach to Trajectory Privacy Protection.**  [paper](https://arxiv.org/abs/2006.10521)

   *Jinmeng Rao, Song Gao, Yuhao Kang et al.* 2020.

+ **Population Mobility Modelling for Mobility Data Simulation.** [paper](https://www.sciencedirect.com/science/article/pii/S0198971520302593)

   *Smolak K, Rohm W, Knop K, et al.* Computers, Environment and Urban Systems, 2020.

+ **RNN-DP: A New Differential Privacy Scheme Base on Recurrent Neural Network for Dynamic Trajectory Privacy Protection.** [paper](https://www.sciencedirect.com/science/article/pii/S1084804520302101)

   *Chen S, Fu A, Shen J, et al.* Journal of Network and Computer Applications, 2020.

+ **Generating Mobility Trajectories with Retained Data Utility.** [paper](https://dl.acm.org/doi/abs/10.1145/3447548.3467158)

   *Cao C, Li M.* KDD, 2021.

+ **How Do We Move: Modeling Human Movement with System Dynamics.** [paper](https://ojs.aaai.org/index.php/AAAI/article/view/16571)

   *Wei H, Xu D, Liang J, et al.* AAAI, 2021.

+ **Simulating Continuous-time Human Mobility Trajectories.** [paper](https://simdl.github.io/files/47.pdf)
  
   *Xu N, Trinh L, Rambhatla S, et al.* ICLR SimDL Workshop, 2021.

+ **TrajGAIL: Generating Urban Vehicle Trajectories using Generative Adversarial Imitation Learning.** [paper]()

   *Choi S, Kim J, Yeo H.* Transportation Research Part C: Emerging Technologies, 2021.

+ **TrajVAE: A Variational AutoEncoder Model for Trajectory Generation.** [paper](https://www.sciencedirect.com/science/article/pii/S0925231220312017)

   *Chen X, Xu J, Zhou R, et al.* Neurocomputing, 2021.

+ **Large Scale GPS Trajectory Generation Using Map Based on Two Stage GAN.** [paper](https://www.airitilibrary.com/Article/Detail/16838602-202101-202103090003-202103090003-126-141)

   *Wang X, Liu X, Lu Z, et al.* Journal of Data Science, 2021.

+ **VTSV: A Privacy-Preserving Vehicle Trajectory Simulation and Visualization Platform Using Deep Reinforcement Learning** [paper](https://dl.acm.org/doi/abs/10.1145/3486635.3491073)

   *Rao J, Gao S, Zhu X.* GeoAI, 2021.

+ **Activity Trajectory Generation via Modeling Spatiotemporal Dynamics.** [paper](https://dl.acm.org/doi/abs/10.1145/3534678.3542671)

   *Yuan Y, Ding J, Wang H, et al.* KDD, 2022.

+ **A Deep Generative Model for Trajectory Modeling and Utilization.** [paper](https://dl.acm.org/doi/abs/10.14778/3574245.3574277)

   *Wang Y, Li G, Li K, et al.* Proceedings of the VLDB Endowment, 2022.

+ **RMGen: A Tri-Layer Vehicular Trajectory Data Generation Model Exploring Urban Region Division and Mobility Pattern.** [paper](https://ieeexplore.ieee.org/abstract/document/9779566/)

   *Kong X, Chen Q, Hou M, et al.* IEEE Transactions on Vehicular Technology, 2022.

+ **Generating Synthetic Mobility Data for a Realistic Population with RNNs to Improve Utility and Privacy.** [paper](https://dl.acm.org/doi/abs/10.1145/3477314.3507230)

   *Berke A, Doorley R, Larson K, et al.* ACM/SIGAPP Symposium on Applied Computing, 2022.

+ **Geolocated Data Generation and Protection Using Generative Adversarial Networks.** [paper](https://link.springer.com/chapter/10.1007/978-3-031-13448-7_7)

   *Alatrista-Salas H, Montalvo-Garcia P, Nunez-del-Prado M, et al.* International Conference on Modeling Decisions for Artificial Intelligence, 2022.

+ **Synthesis of Longitudinal Human Location Sequences: Balancing Utility and Privacy.** [paper](https://dl.acm.org/doi/abs/10.1145/3529260)

   *Benarous M, Toch E, Ben-Gal I.* ACM Transactions on Knowledge Discovery from Data (TKDD), 2022.

+ **DiffTraj: Generating GPS Trajectory with Diffusion Probabilistic Model.** [paper](https://proceedings.neurips.cc/paper_files/paper/2023/hash/cd9b4a28fb9eebe0430c3312a4898a41-Abstract-Conference.html)

   *Zhu Y, Ye Y, Zhang S, et al.* NIPS, 2023.

+ **SynMob: Creating High-Fidelity Synthetic GPS Trajectory Dataset for Urban Mobility Analysis.** [paper](https://proceedings.neurips.cc/paper_files/paper/2023/hash/4786c0d1b9687a841bc579b0b8b01b8e-Abstract-Datasets_and_Benchmarks.html)

   *Zhu Y, Ye Y, Wu Y, et al.* NIPS, 2023.

+ **Practical Synthetic Human Trajectories Generation Based on Variational Point Processes.** [paper](https://dl.acm.org/doi/abs/10.1145/3580305.3599888)

   *Long Q, Wang H, Li T, et al.* KDD, 2023.

+ **PateGail: A Privacy-Preserving Mobility Trajectory Generator with Imitation Learning.** [paper](https://ojs.aaai.org/index.php/AAAI/article/view/26700)

   *Wang H, Gao C, Wu Y, et al.* AAAI, 2023.

+ **Continuous Trajectory Generation Based on Two-Stage GAN.** [paper](https://arxiv.org/abs/2301.07103)

   *Jiang W, Zhao W X, Wang J, et al.* AAAI, 2023.

+ **DP-TrajGAN: A Privacy-aware Trajectory Generation Model with Differential Privacy.** [paper](https://www.sciencedirect.com/science/article/pii/S0167739X22004319)

   *Zhang J, Huang Q, Huang Y, et al.* Future Generation Computer Systems, 2023.

+ **CSGAN: Modality-Aware Trajectory Generation via Clustering-based Sequence GAN.**  [paper](https://ieeexplore.ieee.org/abstract/document/10214943/)

   *Minxing Zhang, Haowen Lin, Shun Takagi, et al.* IEEE International Conference on Mobile Data Management, 2023.

+ **Enhanced Generation of Human Mobility Trajectory with Multiscale Model.** [paper](https://link.springer.com/chapter/10.1007/978-981-99-8178-6_24)

   *Han L.* International Conference on Neural Information Processing, 2023.

+ **Trajectory Generation of Ultra-Low-Frequency Travel Routes in Large-Scale Complex Road Networks.** [paper](https://www.mdpi.com/2079-8954/11/2/61)

   *Li J, Zhao W.* Systems, 2023.

+ **A Deep Learning Framework to Generate Synthetic Mobility Data.** [paper](https://ieeexplore.ieee.org/abstract/document/10241677)
   
   *Arkangil E, Yildirimoglu M, Kim J, et al.* International Conference on Models and Technologies for Intelligent Transportation Systems (MT-ITS), 2023.

+ **TrajSGAN: A Semantic-Guiding Adversarial Network for Urban Trajectory Generation.** [paper](https://ieeexplore.ieee.org/abstract/document/10025663)

   *Xiong G, Li Z, Zhao M, et al.* IEEE Transactions on Computational Social Systems, 2023.

+ **LDPTrace: Locally  Differentially Private Trajectory Synthesis.** [paper](https://arxiv.org/abs/2302.06180)

   *Du Y, Hu Y, Zhang Z, et al.* 2023.

## Micro Trajectory Simulation

+ **Conditional Generative Models for Dynamic Trajectory Generation and Urban Driving.** [paper](https://www.mdpi.com/1424-8220/23/15/6764)

   *Paz D, Zhang H, Xiang H, et al.* Sensors, 2023.





