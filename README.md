# Regression

This project reframes regression as an inverse problem and uses the spectrum (singular values / eigenvalues)
as the main language for understanding (i) instability under multicollinearity, (ii) bias–variance trade-offs
under regularization, and (iii) computational scaling of common solvers. The central thesis is that many
seemingly different estimators are best understood as spectral filters: they replace an unbounded inverse (OLS)
by bounded, direction-dependent shrinkage, stabilizing prediction in ill-conditioned and overparameterized
regimes
