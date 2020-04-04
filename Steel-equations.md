# A collection of equations for steel

1. Hall-Petch relationship:

$$
\sigma_{y}=\sigma_{0}+k_{y} \cdot d^{-1 / 2}
$$

2. DBTT
  

The ductile-to-brittle transition temperature (DBTT) is defined as the temperature for 50% cleavage on the fracture surfaces of the Charpy impact samples.

$$
\mathrm{DBTT}=A-k^{\prime} \cdot d^{-1 / 2}
$$

# 20200404-Considère&#39;s Criterion


塑性变形颈缩判据：
$$
\frac{d\sigma_t}{d\varepsilon_t}=\sigma_t
$$
当真应力-应变曲线斜率等于真应力，停止均匀变形，开始颈缩开始。

## 5.18 Considère's Criterion[^2]



> A condition for the onset of necking was originally proposed by Considère's based on the assumption that necking begins at the point of maximum load. At the maximum load
> $$
> dP=Ad\sigma_t+\sigma_t dA =0
> $$
> where ![](https://cdn.nlark.com/yuque/__latex/44c29edb103a2872f519ad0c9a0fdaaa.svg#card=math&code=P&height=16&width=12) is the load, ![](https://cdn.nlark.com/yuque/__latex/7fc56270e7a70fa81a5935b72eacbe29.svg#card=math&code=A&height=16&width=12) is the cross-section area, and ![](https://cdn.nlark.com/yuque/__latex/7c776afdc7c49e110f1bf39b2edee0b1.svg#card=math&code=%5Csigma_t&height=14&width=15) is the true stress. In effect, this relationship states that for a given strain increment, the resulting decrease in specimen area reduces the load-carrying ability of the cross-section by the same amount that the load-carrying ability of the specimen is increased by the rise in its strength due to strain hardening. The above relationship may be rearranged to read
> $$
> dP=Ad\sigma_t+\sigma_t dA =0
> $$
> In plastic deformation, a reasonable assumption is that the volume remains constant, so that
> $$
> d\sigma_t=-\sigma_t\frac{dA}{A}
> $$
> or
>
> ![](https://cdn.nlark.com/yuque/__latex/a46d0110aae493febac8461780b43eb9.svg#card=math&code=%5Cfrac%7BdA%7D%7BA%7D%3D-%5Cfrac%7Bdl%7D%7Bl%7D&height=40&width=82)
>
> where ![](https://cdn.nlark.com/yuque/__latex/2db95e8e1a9267b7a1188556b2013b33.svg#card=math&code=l&height=16&width=4) is the specimen gate length and ![](https://cdn.nlark.com/yuque/__latex/4f46f9e3a9edeccffb466047332a8655.svg#card=math&code=dl%2Fl&height=20&width=27) is ![](https://cdn.nlark.com/yuque/__latex/8e848dbe0cee1b563f128f0c77ab08bf.svg#card=math&code=%5Cepsilon_%7Bt%27%7D&height=14&width=16)the true strain. Therefore,
>
> ![](https://cdn.nlark.com/yuque/__latex/83cb2a42dfa63b9a81ce9fdc9e6636fc.svg#card=math&code=%5Cfrac%7Bd%5Csigma_t%7D%7Bd%5Cepsilon_t%7D%3D%5Csigma_t&height=42&width=68)
> $$
> \frac{d\sigma_t}{d\epsilon_t}=\sigma_t
> $$
> This is Considère's criterion for necking. When the slope of the true-stress true-strain curve,  is equal to the true stress  necking should begin. As will be shown presently, this relationship can help to reationalize a basic difference in the observed stress-strain behavior of face-centered cubic and body-centered cubic metals.

[^2]: R. Abbaschian, R.E. Reed-Hill, Physical Metallurgy Principles - SI Version, 4 edition, Section 5.18, P150-151, Cengage Learning, Stamford, CT, 2009.