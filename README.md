# Randomized-Anonymization

We proposed privacy-preserving methods for data sharing that satisfy both k-anonymity and ε-differential privacy.

The proposed methods are
k-RR (k-anonymization → randomized response), RR-k (randomized response → k-anonymization), and (ε, k)-Randomized Anonymization.

## Important future directions

・Developing k-anonymization methods more suited for the integration with Randomized Response. In particular, the method for calculating representative values should be carefully considered. (In our experiments, we ignore events in which the representative values vary between neighboring datasets.)

・Utilizing Optiimized Local Hashing (OLH) [[Wang et al., 2017](https://www.usenix.org/system/files/conference/usenixsecurity17/sec17-wang-tianhao.pdf)] instead of Randomized Response.

・Improving the handling of numeric (continuous value) data.

(・How should we determine appropriate values of ε and k for each medical information?)

## Note

For details of our mechanisms, please see our paper entitled "(ε, k)-Randomized Anonymization: ε-Differentially Private Data Sharing with k-Anonymity" (https://doi.org/10.5220/0011665600003414) presented at HEALTHINF 2023.

Errata:

・p.289. 3.2.1
  "When the following inequality holds: $ε ≥$" → "When the following inequality holds: $e^ε ≥$"

### Contact
Akito Yamamoto

Division of Medical Data Informatics, Human Genome Center,

the Institute of Medical Science, the University of Tokyo

a-ymmt@ims.u-tokyo.ac.jp
