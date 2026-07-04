# Observational Compatibility and Gaussian Covariance Invariants

This repository contains research materials related to **observational compatibility**, inverse problems, Gaussian time-frequency analysis, and stable covariance invariants.

The repository supports the development of the article:

**Observational Compatibility and Stable Covariance Invariants in Gaussian Time-Frequency Analysis**  
Paulo Vieira, 2026.

---

## Overview

Many inverse problems are traditionally formulated as pointwise reconstruction problems: given an observed datum, one tries to recover the generating state. However, in many regimes of interest, the observation process is not injective. It may discard phase, apply localization, average information, impose a window, or blur structural features.

The framework of **observational compatibility** shifts the focus from pointwise reconstruction to the geometry of observational fibers. Given an observation operator, the natural object is not necessarily a single generating state, but the class of all states that produce the same effective observable.

In this repository, this perspective is developed through a concrete model in Gaussian time-frequency analysis: chirped Gaussian states observed through Gaussian spectrograms.

---

## Main mathematical identity

For the chirped Gaussian state

```text
g_{a,sigma}(t) = exp(i a t^2) exp(-pi (t/sigma)^2),
