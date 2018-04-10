# figures of merit

One popular figure of merit in searches is the ``Punzi figure of merit''
(Sensitivity of searches for new signals and its optimization https://arxiv.org/abs/physics/0308063).

Its appeal is that it does not require the input of an expected signal strength
/ cross section to compute (other than a signal-to-background ratio or signal
purity) and does not vanish if the expected signal yield is zero.

(One should compare this to Andrea's talk at the workshop on figures of merit,
if there is something else of interest / better)

Yet, it may not be implemented in ML toolkits for quick and easy evaluation (or
even hyper parameter optimization and model selection). So it would be nice to
write a small python module to work with the scikit-learn interfaces and create
a pull request to the `hep_ml` package, and/or a small extension to the TMVA
Gui.

Alternatively, if such implementations already exist, we might want to
advertise them (start with a pull request to popular packages directly, make
the paper-software link findable on the HEP-ML-resources list …).
