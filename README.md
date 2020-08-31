# MultiplierIdeals.m2
### MultiplierIdeals package for Macaulay2

A package for computing multiplier ideals


*MultiplierIdeals*
is a package for computing multiplier ideals,
log canonical thresholds, and jumping numbers,
using specialized routines wherever possible.

The package *Dmodules*
provides computations of multiplier ideals,
log canonical thresholds, and jumping numbers of arbitrary ideals
using general algorithms.

This package provides alternatives for special classes of ideals,
including monomial ideals, hyperplane arrangements,
generic determinantal ideals,
and binomial ideals
(currently, ideals of curves in 3-space parametrized by monomials).
These special computations are typically much faster than general methods
and can often handle larger examples.
