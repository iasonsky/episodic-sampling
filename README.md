# Disentangling Sampling from Training Budget in Class-Imbalanced CT Body Composition Segmentation

### Iason Skylitsis, Dimitrios Karkalousos, Ivana Išgum

## Abstract
Class imbalance is a fundamental challenge in medical image segmentation, where frequent classes dominate training at the expense of rare classes. In this work, we adopt episodic sampling from few-shot learning to promote class-balanced batch construction in a fully supervised setting, decoupling it from its conventional metric-learning context. We compare episodic, random, and weighted sampling on nine muscle and adipose tissue classes from 210 CT scans of the public SAROS dataset, under full-data and low-data regimes with additional comparisons under matched training iteration budgets. We show that the apparent advantage of episodic sampling is largely driven by a 12-fold difference in training iterations per epoch, not the sampling mechanism itself. Under matched budgets, random and weighted sampling overfit earlier, while episodic continued improving for approximately three times more iterations. Our findings identify the training iteration budget as an under-recognized confound in sampling-strategy comparisons, motivating iteration-aware evaluation protocols for small datasets.

> **Note:** Code for the episodic sampler will be made available soon.

## BibTeX citation:

```
@misc{skylitsis2026disentanglingsamplingtrainingbudget,
      title={Disentangling Sampling from Training Budget in Class-Imbalanced CT Body Composition Segmentation}, 
      author={Iason Skylitsis and Dimitrios Karkalousos and Ivana Išgum},
      year={2026},
      eprint={2605.20405},
      archivePrefix={arXiv},
      primaryClass={eess.IV},
      url={https://arxiv.org/abs/2605.20405}, 
}
```
