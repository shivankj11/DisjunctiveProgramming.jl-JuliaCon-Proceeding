# DisjunctiveProgramming.jl

## Generalized Disjunctive Programming Models and Algorithms for JuMP

We present a Julia package, \textit{DisjunctiveProgramming.jl}, that extends the functionality in \textit{JuMP.jl} (Dunning, et al., 2017) to allow modeling problems via logical propositions and disjunctive constraints. Logical propositions are converted into algebraic expressions by converting the Boolean expressions to Conjunctive Normal Form and then to algebraic inequalities. The package allows the user to specify the technique to reformulate the disjunctions (Big-M or Hull reformulations) into mixed-integer constraints. This allows generating models that can be solved by the various MIP solvers supported by JuMP (JuMP Supported Solvers, 2022). The package supports reformulations for disjunctions containing linear, quadratic, and nonlinear constraints.
