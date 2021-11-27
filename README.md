# do(Y)
AI systems have been criticized for not being truly intelligent at all. They learn fast but reason lazily, thus tend to be biased, have poor generalization and vulnerable to adversarial attacks. There has been a recent explosion in papers attempting to solve this by using causal inference theories. This repo bridges the gap between researchers and the progress in this field. 

Everyone in Github is welcomed to contribute to this collection. 

## Contents
### I. General Theory
1. **Commonsense Reasoning about Causality: Deriving Behavior From Structure** (B. J. Kuipers. 1984) [[paper](https://web.eecs.umich.edu/~kuipers/papers/Kuipers-aij-84-els.pdf)] 
2. **On Causal and Anticausal Learning** (Schölkopf et al. 2012) [[paper](https://icml.cc/2012/papers/625.pdf)][[summary](https://isvy08.github.io/blog/causal-ml.html)]
3. **Causality for Machine Learning** (Bernhard Schölkopf 2019) [[paper](https://arxiv.org/pdf/1911.10500.pdf)]
4. **Towards Causal Representation Learning** (Schölkopf et al. 2020) [[paper](https://cardiacmr.hms.harvard.edu/files/cardiacmr/files/toward_causal_representation_learning.pdf)]
5. **Adversarial Robustness through the Lens of Causality** (Zhang et al. 2021) [[paper](https://arxiv.org/pdf/2106.06196.pdf)]

### II. Learning Invariant Distribution
1. **Causal Inference Using Invariant Prediction: identification and confidence intervals** (Peters et al. 2015) [[paper](https://arxiv.org/pdf/1501.01332.pdf)]
2. **Invariant Models for Causal Transfer Learning** (Rojas-Carulla et al. 2018) [[paper](https://www.jmlr.org/papers/volume19/16-432/16-432.pdf)]
3. **Domain Adaptation by Using Causal Inference to Predict Invariant Conditional Distributions** (Magliacane et al. 2018) [[paper](https://proceedings.neurips.cc/paper/2018/file/39e98420b5e98bfbdc8a619bef7b8f61-Paper.pdf)]
4. **Detecting and Correcting for Label Shift with Black Box Predictors** (Lipton et al. 2018) [[paper](https://arxiv.org/pdf/1802.03916.pdf)]
5. **Conditional Adversarial Domain Adaptation** (Long et al. 2018) [[paper](https://papers.nips.cc/paper/2018/file/ab88b15733f543179858600245108dd8-Paper.pdf)]
6. **Representation Learning via Invariant Causal Mechanisms** (Mitrovic et al. 2020) [[paper](https://openreview.net/pdf?id=9p2ekP904Rs)][[video summary](https://drive.google.com/file/d/1o36Uv3YJgpJPQ9XACzlOG-sDZ1psLHUD/view?usp=sharing)]
7. **Domain Generalization using Causal Matching** (Mahajan et al. 2021) [[paper](https://www.microsoft.com/en-us/research/uploads/prod/2021/06/DG_with_causal_matching.pdf)]
8. **Causally Invariant Predictor with Shift-Robustness** (Zheng et al. 2021) [[paper](https://arxiv.org/pdf/2107.01876.pdf)]

### III. Invariant Risk Minimization
1. **Invariant Risk Minimization** (Arjovsky et al. 2020) [[paper](https://arxiv.org/pdf/1907.02893.pdf)]
2. **The Risks of Invariant Risk Minimization** (Rosenfeld et al. 2021) [[paper](https://arxiv.org/pdf/2010.05761.pdf)]
3. **Invariance Principle Meets Information Bottleneck for Out-of-Distribution Generalization** (Ahuja et al. 2021) [[paper](https://arxiv.org/pdf/2106.06607.pdf)]
4. **When is Invariance Useful in an Out-of-Distribution Generalization problem ?** (Koyama & Yamaguchi 2020) [[paper](https://arxiv.org/pdf/2008.01883.pdf)]
5. **Out-of-Distribution Generalization via Risk Extrapolation** (Krueger et al. 2021) [[paper](http://proceedings.mlr.press/v139/krueger21a/krueger21a.pdf)]

### IV. Causal Structural Learning
1. **Discovering Causal Signals in Images** (Lopez-Paz et al. 2017) [[paper](https://arxiv.org/pdf/1605.08179.pdf)]
2. **Learning Independent Causal Mechanisms** (Parascandolo et al. 2018) [[paper](http://proceedings.mlr.press/v80/parascandolo18a/parascandolo18a.pdf)]
3. **A Meta-Transfer Objective for Learning to Disentangle Causal Mechanisms** (Bengio et al. 2020) [[paper](https://openreview.net/pdf?id=ryxWIgBFPS)]
4. **Learning Neural Causal Models from Unknown Interventions** (Ke et al. 2020) [[paper](https://arxiv.org/pdf/1910.01075.pdf)]
5. **Selecting Data Augmentation for Simulating Interventions** (Ilse et al. 2021) [[paper](http://proceedings.mlr.press/v139/ilse21a/ilse21a.pdf)]
6. **The Causal-Neural Connection: Expressiveness, Learnability, and Inference** (Xia et al. 2021) [[paper](https://causalai.net/r80.pdf)]
7. **Self-Supervised Learning with Data Augmentations Provably Isolates Content from Style** (Kügelgen et al. 2021) [[paper](https://arxiv.org/pdf/2106.04619.pdf)]

### Applications

### V. Visual-Language Tasks
1. **Visual Commonsense R-CNN** (Wang et al. 2020) [[paper](https://openaccess.thecvf.com/content_CVPR_2020/papers/Wang_Visual_Commonsense_R-CNN_CVPR_2020_paper.pdf)]
2. **Two Causal Principles for Improving Visual Dialog** (Qi et al. 2020) [[paper](https://openaccess.thecvf.com/content_CVPR_2020/papers/Qi_Two_Causal_Principles_for_Improving_Visual_Dialog_CVPR_2020_paper.pdf)]
3. **Causal Attention for Vision-Language Tasks** (Yang et al. 2021) [[paper](https://openaccess.thecvf.com/content/CVPR2021/papers/Yang_Causal_Attention_for_Vision-Language_Tasks_CVPR_2021_paper.pdf)]
4. **Counterfactual VQA: A Cause-Effect Look at Language Bias** (Niu et al. 2021) [[paper](https://openaccess.thecvf.com/content/CVPR2021/papers/Niu_Counterfactual_VQA_A_Cause-Effect_Look_at_Language_Bias_CVPR_2021_paper.pdf)]

### VI. NLP
1. **Counterfactual Story Reasoning and Generation** (Qin et al. 2019) [[paper](https://arxiv.org/pdf/1909.04076.pdf)]
2. **Causal Effects of Linguistic Properties** (Pryzanr et al. 2020) [[paper](https://arxiv.org/abs/2010.12919)]
3. **Causal Inference in Natural Language Processing: Estimation, Prediction, Interpretation and Beyond** (Feder et al. 2021) [[paper](https://arxiv.org/abs/2109.00725)]
4. **Causal Direction of Data Collection Matters: Implications of Causal and Anticausal Learning for NLP** (Jin et al. 2021) [[paper](https://arxiv.org/pdf/2110.03618.pdf)]

<hr>

### VII. Foundational Causal Inference Literature
1. **Causality: Models, Reasoning and Inference** (Judea Pearl 2009) [[book](http://bayes.cs.ucla.edu/BOOK-2K/viewgraphs.html)]
2. **Primer: Causal Inference in Statistics** (Pearl, Glymour & Jewell) [[book](http://bayes.cs.ucla.edu/PRIMER/)]
3. **Causal Inference In Statistics: An Overview** (Judea Pearl 2009) [[paper](https://ftp.cs.ucla.edu/pub/stat_ser/r350.pdf)]
4. **Causal Inference: What If** (Robins & Hernan 2010) [[book](https://cdn1.sph.harvard.edu/wp-content/uploads/sites/1268/2019/10/ci_hernanrobins_1oct19.pdf)]
5. **On Pearl’s Hierarchy and the Foundations of Causal Inference** (Bareinboim et al. 2020) [[chapter 1](https://causalai.net/r60.pdf)]


