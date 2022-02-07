# Measurement Error Mitigation

Everything about the tests, attempts and all others on the enhancement of measurement error mitigation. Below is content of this repository

* `response`: include response matrix obtained from different methods
  * `classical-response`: the classical response matrix $A$, obtained from $2^n$ calibration experiment
  * `simple-tensor`: response matrix of tensor product noise
  * `gamma-matrix`: response matrix with no state-preparation error, obtained from GST techniques
  * `simple-scalable`: scalable response matrix $A$ with subspace reduction
  * `pure-ctmps`: response matrix obtained from continuous time Markov processes (CTMPs) (coming soon)
* `correction`: include available methods to mitigate readout error
  * `inverse-matrix`: use inverse matrix method to mitigate readout error
  * `least-square`: use linear regression method to mitigate readout error
  * `iterative-bayes`: use iterative Bayesian unfolding method to mitigate readout error

* `score`: include available method to evaluate the performance of mitigation method
  * `ghz`: generate GHZ state and compare the measurement result with ideal output after mitigation
  * `vqe`: test the performance of MEM in VQE (coming soon)
* `others`: ancillary tools for the project
  * `state-tomography`: estimate raw output state using state-tomography (coming soon)


