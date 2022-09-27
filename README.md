# Prototypes of Temporally Activated Patterns (PTAP)

Interpreting Internal Activation Patterns in Deep Temporal Neural Networks by Finding Prototypes (KDD 2021)

Sohee Cho*, Wonjoon Chang*, Ginkyeng Lee, Jaesik Choi

paper link: https://dl.acm.org/doi/abs/10.1145/3447548.3467346

## Summary
We propose a new framework with which to visualize temporal representations learned in deep neural networks without hand-crafted segmentation labels. Given input data, our framework extracts highly activated temporal regions that contribute to activating internal nodes and characterizes such regions by prototype selection method based on Maximum Mean Discrepancy (MMD). Representative temporal patterns referred to here as **Prototypes of Temporally Activated Patterns (PTAP)** provide core examples of subsequences in the sequential data for interpretability.

We will provide a tutorial code for our framework soon.

- - - 

## Prototype Selection
Our approach is mainly inspired by the following work, which suggests the greedy algorithm to find prototypes of high-dimensional data.

Examples are not enough, learn to criticize! Criticism for Interpretability (NIPS 2016)

paper link: https://proceedings.neurips.cc/paper/2016/hash/5680522b8e2bb01943234bce7bf84534-Abstract.html

Tutorial code: https://github.com/onejoon/PTAP/blob/main/Prototype-Selection-tutorial.ipynb

