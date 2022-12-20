# Jupyter Python notebook to calculate yield points

Applies work equivalence principle for calculation yield points of uniaxial and biaxial tensile tests

Reference: https://link.springer.com/article/10.1007/s11340-020-00601-9

Integrates uniaxial stress-strain curves to calculate plastic work.

$W_0 = \int_0^{\varepsilon_0^p} \sigma_x d\varepsilon_x^p$

$W_0 = W_x + W_y$

**Caution:** Same row of $W_x$ and $W_y$ must represent the same physical state (i.e, same time) in the experiment.
