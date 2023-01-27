# Invariant manifolds eigenfunctions for 2D ODEs

Solve for 1-dimensional invariant manifolds numerically and then test whether the invariant manifolds can be combined to generate an eigenfunction.

(1) Find fixed points and eigenvectors using linearize.nb \
(2) Select starting values from linearization along eigenvector directions \
(3) Numerically integrate to determine invariant manifolds \
(4) Do linear regression to see if there is an eigenfunction

## Example 1

$\frac{dx}{dt} =  x-xy$ \
$\frac{dy}{dt} = -y+x^2-2y^2$

**linearize.nb** computes the fixed points and eigenvectors of the system linearized at the fixed points in Mathematica. \
**numerical_find_invariant_manifold_test.ipynb** computes the invariant manifolds numerically and numerically tests if an eigenfunction can be generated from the invariant manifold generating functions.

## Example 2

$\frac{dx}{dt} =  x+y$ \
$\frac{dy}{dt} = y+x^3$


**linearize2.nb** computes the fixed points and eigenvectors of the system linearized at the fixed points in Mathematica. \
**numerical_find_invariant_manifold_test2.ipynb** computes the invariant manifolds numerically and numerically tests if an eigenfunction can be generated from the invariant manifold generating functions.
