
.. _discrete-pbinom:

Poisson Binomial Distribution
=============================

A Poisson binomial random variable with parameters :math:`{p}\in [0,1]^n` can be described as the sum of :math:`n` independent Bernoulli random variables that are not necessarily identically distributed.

.. math::

    `p_i in [0, 1] \\forall i \\in [0, N]` for :math:`N` independent but not identically distributed Bernoulli random variables.

For details see: https://en.wikipedia.org/wiki/Poisson_binomial_distribution

Method as described in the reference [Hong2013]_, and implemented in Python by [Mika Straka]_.

References
----------

.. [Hong2013] Yili Hong, "On computing the distribution function for the
        Poisson binomial distribution",
        *Computational Statistics & Data Analysis, Volume 59, March 2013*,
        Pages 41-51, ISSN 0167-9473,
        https://dx.doi.org/10.1016/j.csda.2012.10.006.
.. [Mika Straka] https://github.com/tsakim/poibin


Implementation: `scipy.stats.pbinom`
