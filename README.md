# Readings 

## Neuroscience / Biology inspired ML

> [**Orientation Selectivity, Preference, and Continuity in Monkey Striate Cortex**](https://www.jneurosci.org/content/jneuro/12/8/3139.full.pdf)

> [Measuring and interpreting neuronal correlations](http://www.marlenecohen.com/pubs/CohenKohn2011.pdf)
> 
> [Performance-optimized hierarchical models predict neural responses in higher visual cortex](https://www.pnas.org/doi/full/10.1073/pnas.1403112111)
>   - Demonstrates similarities between the human/mammalian visual cortex and CNNs
>
>  [Edges are the 'Independent Components' of Natural Scenes. ](https://papers.nips.cc/paper_files/paper/1996/file/f9be311e65d81a9ad8150a60844bb94c-Paper.pdf)
>   - Describes the edge selective neurons ("receptive fields of simple cells in visual cortex") in the mammalian (cats and monkeys) visual cortex, and how their importance in capturing the dominant features/components found in natural images.
>   - Applies Non-Linear Infomax on multiple natural images to generate image filters that are oriented,  resembling Gabor Filters.
>
>  [Correlation-Based Models of Neural Development (From **Neuroscience and Connectionist Theory**)](https://www.taylorfrancis.com/chapters/edit/10.4324/9780203762981-7/correlation-based-models-neural-development-kenneth-miller)
>
>  [Non Linear Neurons in the Low Noise Limit: A Factorial Code Maximizes Information Transfer](https://www.researchgate.net/publication/2429553_Non_Linear_Neurons_in_the_Low_Noise_Limit_A_Factorial_Code_Maximizes_Information_Transfer)
>
>  [Edge co-occurrence in natural images predicts contour grouping performance (Geisler et al. 2001)](https://pubmed.ncbi.nlm.nih.gov/11248261/)

## ML

> [**How does Weight Correlation Affect the Generalisation Ability of Deep Neural Networks?**](https://proceedings.neurips.cc/paper/2020/file/f48c04ffab49ff0e5d1176244fdfb65c-Paper.pdf)
>  - [Reviews](https://proceedings.neurips.cc/paper/2020/file/f48c04ffab49ff0e5d1176244fdfb65c-Review.html)
>    
> [**Interpretation of ResNet by Visualization of Preferred Stimulus in Receptive Field**](https://arxiv.org/abs/2006.01645.pdf)
>   - Analysis of learned kernels in Resnet.
>   - Mentions **orientation selective** and **color neurons**
>   - Uses activation maximization to visualise **prefered stimuli**
>   - Lacks analysis of deeper layers
>
> [**Understanding intermediate layers using linear classifier probes**](https://arxiv.org/abs/1610.01644.pdf)
>
> [**SVCCA: Singular Vector Canonical Correlation Analysis for Deep Learning Dynamics and Interpretability**](https://arxiv.org/abs/1706.05806)
>
> [**Convergent Learning: Do different neural networks learn the same representations?**](https://arxiv.org/abs/1511.07543)
>
> [**Pruning Filters for Efficient ConvNets**](https://arxiv.org/abs/1608.08710)
>   - Uses $l_2$-norm as a metric to determine which filters to prune
>   - (Figure 2c) Demontrastes for VGG16 that removing 90% of the lowest magnitude filters in all layers doesn't severely harm accuracy (after retraining only 20 epochs)
>
> [** Learning a smooth kernel regularizer for convolutional neural networks **](https://cims.nyu.edu/~brenden/papers/FeinmanLake2019CogSci.pdf)
>   - Proposes a regularizer that encourages correlation in weights
>   - Links to biological papers [Geisler et al 2001](https://pubmed.ncbi.nlm.nih.gov/11248261/) which discuss the importance of correlation (correlated receptive fields) especially for contour perception.
>   - 
>   -  


## Initialization 

> [**ZerO Initialization: Initializing Neural Networks with only Zeros and Ones**](https://arxiv.org/abs/2110.12661)
>  - [Reviews](https://openreview.net/forum?id=1AxQpKmiTc)
>    
> [**The Shattered Gradients Problem: If resnets are the answer, then what is the question?**](https://proceedings.mlr.press/v70/balduzzi17b/balduzzi17b.pdf)
> 
> [**MetaInit: Initializing learning by learning to initialize**](https://papers.nips.cc/paper_files/paper/2019/file/876e8108f87eb61877c6263228b67256-Paper.pdf)
>
> [**Beyond Signal Propagation: Is Feature Diversity Necessary in Deep Neural Network Initialization?**](https://arxiv.org/abs/2007.01038)

