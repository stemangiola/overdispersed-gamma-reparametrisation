gamma\_approx\_to\_nb
================
Mangiola Stefano
15/06/2018

-   [Comparison of overdispersion between gamma, negative binomial, with poisson](#comparison-of-overdispersion-between-gamma-negative-binomial-with-poisson)
-   [Both negative binomial and gamma can limit to a poisson](#both-negative-binomial-and-gamma-can-limit-to-a-poisson)
-   [Gamma with increasing overdispersion](#gamma-with-increasing-overdispersion)
-   [Negative binomial with increasing overdispersion](#negative-binomial-with-increasing-overdispersion)
-   [Gamma + negative binomial](#gamma-negative-binomial)
-   [Reparametrise the gamma](#reparametrise-the-gamma)
-   [Gamma reparametrised + gamma + negative binomial](#gamma-reparametrised-gamma-negative-binomial)

Comparison of overdispersion between gamma, negative binomial, with poisson
---------------------------------------------------------------------------

Both negative binomial and gamma can limit to a poisson
=======================================================

![](README_files/figure-markdown_github/unnamed-chunk-1-1.png)

However gamma and negative binomial introduce overdispersion "generalising" the relation between expected value and variance of the poisson in a different way

Gamma with increasing overdispersion
====================================

![](README_files/figure-markdown_github/unnamed-chunk-2-1.png)

Negative binomial with increasing overdispersion
================================================

![](README_files/figure-markdown_github/unnamed-chunk-3-1.png)

Gamma + negative binomial
=========================

![](README_files/figure-markdown_github/unnamed-chunk-4-1.png)

Reparametrise the gamma
=======================

to have constant SD and apply a linear dependence between SD and mean

![](README_files/figure-markdown_github/unnamed-chunk-5-1.png)

Gamma reparametrised + gamma + negative binomial
================================================

![](README_files/figure-markdown_github/unnamed-chunk-6-1.png)
