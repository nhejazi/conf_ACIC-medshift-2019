# ACIC 2019 Poster

## Abstract

**Title:* _Nonparametric-efficient causal mediation analysis for stochastic
interventions_

**Authors:** Nima Hejazi, Mark van der Laan, and Iván Díaz

**Abstract:**

Traditionally, the focus of mediation analysis in causal inference has centered
on static treatment regimes and binary exposures, with classical theory
introducing the natural direct and indirect effects through a decomposition of
the average treatment effect. We present an analogous decomposition of the
population intervention effect, defined through stochastic interventions on both
the exposure and mediator nodes, constructing a generalized framework in which
a variety of interesting causal contrasts can be defined, including effects
accommodating both continuous and categorical exposures. Summarizing new
identification results, we show that our direct and indirect effects require
weaker assumptions than effects based on the classical average treatment effect
counterpart, providing an alternative mediation analysis for settings wherein
the cross-world counterfactual independencies required for traditional mediation
analysis are unverifiable. Principally, we discuss the construction and
evaluation of semiparametric-efficient estimators of the direct and indirect
effects, comparing and contrasting the classical one-step (or AIPW) estimator
and a modern targeted minimum loss (TML) alternative under a setting in which
data-adaptive, machine learning techniques are used in estimating relevant
nuisance functions. We show these efficient estimators to be asymptotically
linear under a condition requiring $n^{1/4}$-consistency of certain regression
functions, and we present the results of a simulation study in which the
finite-sample properties of these two estimators are evaluated; moreover, we
introduce the medshift R package, using this new open source software to apply
this proposed methodology in an illustrative investigation of the effect of
sports team participation on children's BMI, with mediators including exercise
habits, daily consumption of snacks, and overweight status.

---

## Related Work

* `medshift` R package:
   * GitHub repository: https://github.com/nhejazi/medshift
   * Documentation site: http://code.nimahejazi.org/medshift

* manuscript: Díaz, Iván, and Nima S Hejazi (2019). "Causal Mediation Analysis
   for Stochastic Interventions." arxiv.org/abs/1901.02776.

---

## License

&copy; 2019 [Nima Hejazi](https://nimahejazi.org), [Iván
Díaz](https://www.idiaz.xyz/)

