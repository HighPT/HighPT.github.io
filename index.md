---
layout: default
katex: true
---
# HighPT

`HighPT` (pronounced *"hyped"*) is a `Mathematica` package for the analysis of high-energy semileptonic transitions at hadron colliders. It allows to compute high-$p_T$ tail observables for semileptonic processes, i.e. Drell-Yan cross sections, for dilepton and monolepton final states at the LHC. 

The `HighPT` code is publicly available in the GitHub repository: [https://github.com/HighPT/HighPT](https://github.com/HighPT/HighPT)

---

## Models

`HighPT` can calculate the high-$p_T$ observables either within the Standard Model Effective Field Theory (SMEFT) or in explicit New Physics (NP) models, which allows for an assesment of a wide range of NP scenarios.

* ### SMEFT
In the SMEFT observables can be computed at tree level, including the relevant energy-enhanced operators up to mass-dimension eight. This allows for a consistent description of the cross section including terms of $\mathcal{O}(\Lambda^{−4})$ in the EFT cutoff scale $\Lambda$.

* ### NP models
In explicit BSM theories with new tree-level mediators, that can be resolved at LHC energies, observables can be computed including the full propagation effects of these new particles. The list of all currently impleneted mediators and their available masses can be found [here](./mediators.html).

---

## Functionalities

The main routines of the `HighPT` code are:

* `DifferentialCrossSection` computes differential cross sections.
* `CrossSection` computes integrated cross sections.
* `EventYield` computes NP event yields for the recasted [experimental searches](./searches.html).
* `ChiSquareLHC` computes $\chi^2$ likelihoods for NP in the recasted [experimental searches](./searches.html).

Further functionalities include the option to redefine the alignment of the mass and flavor basis for quarks and the possibility to translate the results obtained by `HighPT` in `Mathematica` to a `python` file using the [`WCxf` format](https://wcxf.github.io).

---

## Open source

`HighPT` is an open source software. If you find a bug, have a question, or are looking for further features, please have a look at our [issue page](https://github.com/HighPT/HighPT/issues) in the GitHub repositors where you can open a new topic. If you want to contribute to `HighPT` please feel free to open a pull request.

---

## References

If you use `HighPT` please cite:

* L. Allwicher, D. A. Faroughy, F. Jaffredo, O. Sumensari, and F. Wilsch, *HighPT: A Tool for high-*$p_T$ *Drell-Yan Tails Beyond the Standard Model*, [\[arXiv:2207.10756\]](http://arxiv.org/abs/2207.10756)

* L. Allwicher, D. A. Faroughy, F. Jaffredo, O. Sumensari, and F. Wilsch, *Drell-Yan Tails Beyond the Standard Model*, [\[arXiv:2207.10714\]](http://arxiv.org/abs/2207.10714).

[[INSPIRE HEP]]({{site.sidebar[3].link}}) &nbsp;&nbsp; [[BibTeX]](./about.html#latex)
