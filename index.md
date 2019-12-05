
## Projects


### Intrinsic Dimension of Data Representations in Deep Networks

Deep neural networks transform their inputs across multiple layers.<br/>
Here we study the intrinsic dimensionality (ID) of data-representations,<br/>
i.e. the minimal number of parameters needed to describe a representation.<br/>

We estimate ID in multiple CNNs with the [TWO-NN](https://www.nature.com/articles/s41598-017-11873-y) algorithm<br/>
and find that<br/>

- the ID is much lower than the number of units (ED, embedding dimensions)
- the ID along the layers has a typical “hunchback” shape
- in the last hidden layer the ID strongly predicts performance
- even in the last hidden layer, representations are curved.

Look inside [the repo](https://github.com/ansuini/IntrinsicDimDeep) for an outline of our work, extra materials (video, poster) and the code.<br/> 
Full details are in our [**NeurIPS 2019** paper](https://arxiv.org/abs/1905.12784), hope you enjoy it!

<img src="/figs/intrinsic_dimension/wrap_up_no_letters.png" alt="Drawing" style="width: 600px;"/>
