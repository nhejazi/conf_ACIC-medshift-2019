# ACIC 2019 Poster

## Abstract

**Title:** _Causal Mediation Analysis for Stochastic Interventions_

**Authors:** Nima Hejazi and Iván Díaz (and Mark van der Laan?)

**Abstract:**

Mediation analysis in causal inference has traditionally focused on binary
treatment regimes and deterministic interventions, as well as a decomposition of
the average treatment effect in terms of direct and indirect effects. In this
paper we present an analogous decomposition of the _population intervention
effect_, defined through stochastic interventions. Population intervention
effects provide a generalized framework in which a variety of interesting causal
contrasts can be defined, including effects for continuous and categorical
exposures. We show that identification of direct and indirect effects for the
population intervention effect requires weaker assumptions than its average
treatment effect counterpart. In particular, identification of direct effects is
guaranteed in experiments that randomize the treatment and the mediator. Our
proposal thus provides an alternative mediation analysis in situations where
the cross-world counterfactual independencies required for traditional
mediation analysis do not hold or are unverifiable. We discuss various
estimators of the direct and indirect effects, including substitution,
re-weighted, and efficient estimators based on flexible regression techniques.
Our efficient estimator is asymptotically linear under a condition requiring
$n^{1/4}$-consistency of certain regression functions. We perform a simulation
study in which we assess the finite-sample properties of our proposed
estimators. We present the results of an illustrative study where we assess the
effect of participation in a sports team on BMI among children, using mediators
such as exercise habits, daily consumption of snacks, and overweight status.

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

