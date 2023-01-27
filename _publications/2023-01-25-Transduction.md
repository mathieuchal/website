---
layout: post
title: Learning Functional Transduction
---

**Abstract** 
Research in Machine Learning has polarized into two general regression approaches: Transductive methods derive straight estimates from available data but are usually problem unspecific. Inductive methods can be much more specific, but generally require tuning and compute-intensive searches for solutions. In this work, we  adopt a hybrid approach: We leverage the theory of Reproducing Kernel Banach Spaces (RKBS) and show that transductive principles can be induced through gradient descent to form efficient \textit{in-context} neural approximators. We apply this approach to RKBS of function-valued operators and show that once trained, our Transducer model can capture on-the-fly relationships between infinite-dimensional input and output functions, given a few example pairs, and return new function estimates. We demonstrate the benefit of our transductive approach to model complex physical systems influenced by varying external factors with little data at a fraction of the usual deep learning training computation cost for partial differential equations and climate modeling applications.

