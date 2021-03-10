<div align="center">

<!-- title -->
<!--lint ignore no-dead-urls-->
# Awesome XAI [![Awesome](https://awesome.re/badge.svg)](https://awesome.re) ![Lint Awesome List](https://github.com/altamiracorp/awesome-xai/workflows/Lint%20Awesome%20List/badge.svg)

<!-- subtitle -->
A curated list of XAI papers, methods, critiques, and resources.

<!-- image -->
<img src="https://github.com/altamiracorp/awesome-xai/blob/master/images/icon.png?raw=true" />

<!-- description -->
Explainable AI (XAI) is a branch of machine learning research which seeks to make various 
ML techniques more interpretable.

</div>

<!-- TOC -->

## Contents
- [Surveys](#surveys)
    - [Surveys](#surveys)
    - [Methods](#methods)
    - [Critiques](#critiques)
- [Books](#books)
- [Open Courses](#open-courses)
- [Repositories](#repositories)


<!-- CONTENT -->
## Papers
<!-- - [Apple](https://apple.com) - Apple as a placeholder. -->
### Surveys

### Methods
* [ALE](https://rss.onlinelibrary.wiley.com/doi/abs/10.1111/rssb.12377) - Accumulated local effects plot
* [ALIME](https://link.springer.com/chapter/10.1007/978-3-030-33607-3_49) - Autoencoder Based Approach for Local Interpretability
* [Anchors](https://ojs.aaai.org/index.php/AAAI/article/view/11491) - High-Precision Model-Agnostic Explanations
* [BayLIME](https://arxiv.org/abs/2012.03058) - Bayesian local interpretable model-agnostic explanations
* [Break Down](http://ema.drwhy.ai/breakDown.html#BDMethod) - Break down plots for additive attributions
* [CDT](https://ieeexplore.ieee.org/abstract/document/4167900) - Confident interpretation of Bayesian decision tree ensembles
* [CICE](https://christophm.github.io/interpretable-ml-book/ice.html) - Centered ICE plot
* [CMM](https://citeseerx.ist.psu.edu/viewdoc/download?doi=10.1.1.40.2710&rep=rep1&type=pdf) - Combined multiple models metalearner
* [Conj Rules](https://www.sciencedirect.com/science/article/pii/B9781558603356500131) - Using sampling and queries to extract rules from trained neural networks
* [DecText](https://dl.acm.org/doi/abs/10.1145/775047.775113) - Extracting decision trees from trained neural networks
* [DeepLIFT](https://ieeexplore-ieee-org.ezproxy.libraries.wright.edu/abstract/document/9352498) - Deep label-specific feature learning for image annotation
* [FIRM](https://link.springer.com/chapter/10.1007/978-3-642-04174-7_45) - Feature importance ranking measure
* [G-REX](https://www.academia.edu/download/51462700/s0362-546x_2896_2900267-220170122-9600-1njrpyx.pdf) - Rule extraction using genetic algorithms
* [Gibbons, et. al.](https://www.ncbi.nlm.nih.gov/pmc/articles/PMC3977175/) - Explain random forest using decision tree
* [GPDT](https://ieeexplore.ieee.org/abstract/document/4938655) - Genetic program to evolve decision trees
* [GradCAM](https://openaccess.thecvf.com/content_iccv_2017/html/Selvaraju_Grad-CAM_Visual_Explanations_ICCV_2017_paper.html) - Gradient-weighted Class Activation Mapping
* [GradCAM++](https://ieeexplore.ieee.org/abstract/document/8354201/) - Generalized gradient-based visual explanations
* [GoldenEye](https://link-springer-com.ezproxy.libraries.wright.edu/article/10.1007/s10618-014-0368-8) - Exploring classifiers by randomization
* [Hara, et. al.](https://arxiv.org/abs/1606.05390) - Making tree ensembles interpretable
* [ICE](https://www.tandfonline.com/doi/abs/10.1080/10618600.2014.907095) - Individual conditional expectation plots
* [inTrees](https://link.springer.com/article/10.1007/s41060-018-0144-8) - Interpreting tree ensembles with inTrees
* [KL-LIME](https://arxiv.org/abs/1810.02678) - Kullback-Leibler Projections based LIME
* [Krishnan, et. al.](https://www.sciencedirect.com/science/article/abs/pii/S0031320398001812) - Extracting decision trees from trained neural networks
* [LIME](https://dl.acm.org/doi/abs/10.1145/2939672.2939778) - Local Interpretable Model-Agnostic Explanations
* [Lou, et. al.](https://dl.acm.org/doi/abs/10.1145/2487575.2487579) - Accurate intelligibile models with pairwise interactions
* [MFI](https://arxiv.org/abs/1611.07567) - Feature importance measure for non-linear algorithms
* [OptiLIME](https://arxiv.org/abs/2006.05714) - Optimized LIME
* [PALM](https://dl.acm.org/doi/abs/10.1145/3077257.3077271) - Partition aware local model
* [PDA](https://arxiv.org/abs/1702.04595) - Prediction Difference Analysis: Visualize deep neural network decisions
* [PDP](https://projecteuclid.org/download/pdf_1/euclid.aos/1013203451) - Partial dependence plots
* [POIMs](https://academic.oup.com/bioinformatics/article/24/13/i6/233341) - Positional oligomer importance matrices for understanding SVM signal detectors
* [ProfWeight](https://arxiv.org/abs/1807.07506) - Transfer information from deep network to simpler model
* [REFNE](https://content.iospress.com/articles/ai-communications/aic272) - Extractin symbolic rules from trained neural network ensembles
* [RETAIN](https://arxiv.org/abs/1608.05745) - Reverse time attention model
* [RISE](https://arxiv.org/abs/1806.07421) - Randomized input sampling for explanation
* [RxREN](https://link.springer.com/article/10.1007%2Fs11063-011-9207-8) - Reverse engineering neural networks for rule extraction
* [SHAP](https://arxiv.org/abs/1705.07874) - A unified approach to interpretting model predictions
* [SIDU](https://arxiv.org/abs/2101.10710) - Similarity, difference, and uniqueness input perturbation
* [STA](https://arxiv.org/abs/1610.09036) - Interpreting models via Single Tree Approximation
* [SVM+P](https://www.academia.edu/download/2471122/3uecwtv9xcwxg6r.pdf) - Rule extraction from support vector machines
* [TCAV](https://openreview.net/forum?id=S1viikbCW) - Testing with concept activation vectors
* [Tree Metrics](https://www.researchgate.net/profile/Edward-George-2/publication/2610587_Making_Sense_of_a_Forest_of_Trees/links/55b1085d08aec0e5f430eb40/Making-Sense-of-a-Forest-of-Trees.pdf) - Making sense of a forest of trees
* [TreeSHAP](https://arxiv.org/abs/1706.06060) Consistent feature attribute for tree ensembles
* [Tolomei, et. al.](https://dl.acm.org/doi/abs/10.1145/3097983.3098039) - Interpretable predictions of tree-ensembles via actionable feature tweaking
* [TREPAN](http://www.inf.ufrgs.br/~engel/data/media/file/cmp121/TREPAN_craven.nips96.pdf) - Extracting tree-structured representations of trained networks
* [TSP](https://dl.acm.org/doi/abs/10.1145/3412815.3416893) - Tree space prototypes
* [X-TREPAN](https://arxiv.org/abs/1508.07551) - Adapted etraction of comprehensible decision tree in ANNs



### Critiques

## Books
t
## Open Courses

## Repositories

- [EthicalML/xai](https://github.com/EthicalML/xai) - A toolkit for XAI which is focused exclusively on tabular data. It implements a variety of data and model evaluation techniques.
- [PAIR-code/what-if-tool](https://github.com/PAIR-code/what-if-tool) - A tool for Tensorboard or Notebooks which allows investigating model performance and fairness.
- [slundberg/shap](https://github.com/slundberg/shap) - A python module for using Shapley Additive Explanations.


<!-- END CONTENT -->

## Follow
- [The Institute for Ethical AI & Machine Learning](https://ethical.institute/index.html) - A UK-based research center that performs research into ethical AI/MO, which frequently involves XAI.

Who else should we be following!?

## Contributing

[Contributions of any kind welcome, just follow the guidelines](contributing.md)!

### Contributors
[Thanks goes to these contributors](https://github.com/altamiracorp/awesome-xai/graphs/contributors)!

## License
[CC0 License](license)
