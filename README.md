#### DREAM Single Cell Transcriptomics Challenge
- https://www.synapse.org/#!Synapse:syn15665609/wiki/582909
#### Team Thin Nguyen's ranking: https://www.life-science-alliance.org/content/lsa/3/11/e202000867.full.pdf (Figure 1)
- Sub challenge 1: 1<sup>st</sup>
- Sub challenge 2: 2<sup>nd</sup>
- Sub challenge 3: 2<sup>nd</sup>
#### Leaderboards: 
- https://dream-sctc.uni.lu/ranking/team_rankings.html
- https://dream-sctc.uni.lu/ranking/post_team_rankings.html
- https://www.synapse.org/#!Synapse:syn15665609/wiki/583247
#### Data: 
- Data is freely available to Synapse users: ALL_files.zip at https://www.synapse.org/#!Synapse:syn16782362.
- Related data: https://github.com/thinng/exp2loc/blob/master/data.zip.

#### Python libraries needed:
* sklearn: 
     * for popular machine learning methods, including those for feature selection, such as variance-based algorithms. 
     * install: pip install scikit-learn
* skfeature:  
   * for Multi-Cluster Feature Selection (MCFS) (Cai et al., 2010) and Nonnegative Discriminative Feature Selection (NDFS) (Li et al., 2012).
   * Cai, D., Zhang, C., and He, X. (2010). Unsupervised feature selection for multi-cluster data. In Proceedings of the ACM SIGKDD International Conference on Knowledge Discovery & Data Mining, pages 333–342.
   * Li, Z., Yang, Y., Liu, J., Zhou, X., and Lu, H. (2012). Unsupervised feature selection using nonnegative spectral analysis. In Proceedings of the AAAI Conference on Artificial Intelligence, pages 1026–1032.
   * install: pip install skfeature-chappers


#### Source is written in Python. It can be run in Jupyter Notebook.
* By sub challenge
    * sub_challenge_1.ipynb: Source code and step by step instructions for Sub challenge 1
    * sub_challenge_2.ipynb: Source code and step by step instructions for Sub challenge 2
    * sub_challenge_3.ipynb: Source code and step by step instructions for Sub challenge 3
* You may also want to choose your own combination of feature selection and cell prediction
methods through using all_sub_challenges.ipynb

